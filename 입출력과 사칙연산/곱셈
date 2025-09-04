//(세 자리 수) × (세 자리 수) = 각 자리 수의 곱 출력

import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;



public class Main{
    public static void main(String[] args)throws IOException{

        BufferedReader br=new BufferedReader(new InputStreamReader(System.in));

        int num1=Integer.parseInt(br.readLine());
        String strNum2=br.readLine();
        int num2=Integer.parseInt(strNum2);


        for(int i=strNum2.length()-1;i>=0;i--){
            int d=strNum2.charAt(i)-'0';
            System.out.println(num1*d);
        }
        System.out.println(num1*num2);
        br.close();
    }
}


