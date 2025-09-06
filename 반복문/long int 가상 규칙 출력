/*
long int를 이용한 가상의 규칙 출력
int 앞에 long을 붙일 때마다 4바이트씩 증가한다는 착각
실제로는
int 4바이트
long int(long) 4바이트
long long int(long long) 8바이트
즉 long long long int 는 존재하지 않음
*/

import java.io.IOException;
import java.io.InputStreamReader;
import java.io.BufferedReader;

public class Main{
    public static void main(String[] args)throws IOException{
        BufferedReader br=new BufferedReader(new InputStreamReader(System.in));
        int num=Integer.parseInt(br.readLine());
        if(num==4) {
            System.out.println("long int");
        }
        else {
            int count=num/4;
            for(int i=0;i<count;i++){
                System.out.print("long ");
            }
            System.out.println("int");
        }
    }
}
