//영수증 계산 확인

import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;

public class Main{
    public static void main(String[] args)throws IOException{
        BufferedReader br=new BufferedReader(new InputStreamReader(System.in));
        int sum=0;
        int X=Integer.parseInt(br.readLine());
        int N=Integer.parseInt(br.readLine());
        for(int i=0;i<N;i++){
            String[] line=br.readLine().split(" ");
            //매번 새로운 줄 읽기
            int a=Integer.parseInt(line[0]);
            int b=Integer.parseInt(line[1]);
            sum+=a*b;
            
        }

        if(X==sum) System.out.println("Yes");
        else System.out.println("No");
    }
}
