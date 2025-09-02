//3개의 주사위를 던져 상금 받는 게임
import java.io.BufferedReader;
import java.io.InputStreamReader;
import java.io.IOException;

public class Main{
    public static void main(String[] args)throws IOException{
        BufferedReader br=new BufferedReader(new InputStreamReader(System.in));
        String[] input=br.readLine().split(" ");
        
        int a=Integer.parseInt(input[0]);
        int b=Integer.parseInt(input[1]);
        int c=Integer.parseInt(input[2]);
        
        //특정 값 몇 번 나타났는지 세는 counting 배열 because if문 복잡
        int[] count=new int[7];
        count[a]++;
        count[b]++;
        count[c]++;
        
        //카운팅 배열 이용해 경우 판별
        for(int i=1; i<=6; i++){
            if(count[i]==3){
                System.out.println(10000+i*1000);
                return;

            }
       
            else if(count[i]==2){
                System.out.println(1000+i*100);
                return; //return->프로그램 종료되므로 하나의 반복문 사용 가능
            }
            
        }
        //최댓값
        int max=Math.max(a,Math.max(b,c));
        System.out.println(max*100);

            
        br.close();

    }
}
