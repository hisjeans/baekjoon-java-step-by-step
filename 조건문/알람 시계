//알람 시계 45분 일찍 알람 설정

import java.io.BufferedReader;
import java.io.InputStreamReader;
import java.io.IOException;

public class Main {
    public static void main(String[] args) throws IOException {
        BufferedReader br = new BufferedReader(new InputStreamReader(System.in));
        String[] input = br.readLine().split(" ");
        
        int h = Integer.parseInt(input[0]);
        int m = Integer.parseInt(input[1]);
/*
        m-=45;
        
        if(m<0){
            h-=1;
            m+=60;
            
            if(h<0) {
                h=23;
            }
        }
        System.out.println(h+" "+m);
        br.close();
*/
        if (m >= 45) {
            System.out.println(h + " " + (m - 45));
        } else {
            if (h == 0) {
                System.out.println("23 " + (m + 60 - 45));
            } else {
                System.out.println((h - 1) + " " + (m + 60 - 45));
            }
        }
        
        br.close();
    }
}
