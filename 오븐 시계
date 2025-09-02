//오븐 시계 설정

import java.io.BufferedReader;
import java.io.InputStreamReader;
import java.io.IOException;

public class Main{
    public static void main(String[] args)throws IOException{
        BufferedReader br=new BufferedReader(new InputStreamReader(System.in));
        String[] input=br.readLine().split(" ");

        int h=Integer.parseInt(input[0]);
        int m=Integer.parseInt(input[1]);
        int add=Integer.parseInt(br.readLine());
      
        /*
        int totalM=h*60+m+add;
        h=(totalM/60)%24;
        m=totalM%60;
        */
      
        m+=add;
        //if문 한 번만 체크하므로 큰 시간 처리 불가능->while문 반복체크 통해 모든 경우 처리 가능
        while(m>=60){
            h+=1;
            m-=60;
            while(h>=24){
                h-=24;
            }
        } System.out.println(h+" "+m);
        br.close();
    }
}
