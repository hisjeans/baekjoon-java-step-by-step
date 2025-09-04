//나머지

/*
scanner 성능 안 좋음

import java.util.Scanner;

public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int A=sc.nextInt();
        int B=sc.nextInt();
        int C=sc.nextInt();
        System.out.println((A+B)%C);
        System.out.println((A%C+B%C)%C);
        System.out.println((A*B)%C);
        System.out.println((A%C)*(B%C)%C);
        //첫째 줄에 (A+B)%C, 
        //둘째 줄에 ((A%C) + (B%C))%C, 
        //셋째 줄에 (A×B)%C, 
        //넷째 줄에 ((A%C) × (B%C))%C
    }
}
*/


//성능 개선 방법 


import java.io.BufferedReader;
import java.io.InputStreamReader;
import java.io.IOException;
import java.util.StringTokenizer;

public class Main{
    public static void main(String[] args) throws IOException {
        BufferedReader br=new BufferedReader(new InputStreamReader(System.in));
        
        String str=br.readLine();
        StringTokenizer st=new StringTokenizer(str," ");
//StringTokenizer st=new StringTokenizer(br.readLine(),"");
        int A=Integer.parseInt(st.nextToken());
        int B=Integer.parseInt(st.nextToken());
        int C=Integer.parseInt(st.nextToken());

        System.out.println((A+B)%C);
        System.out.println((A%C+B%C)%C);
        System.out.println((A*B)%C);
        System.out.println((A%C)*(B%C)%C);

/*
StringBuilder sb=new StringBuilder();
sb.append((A+B)%C);
sb.append('\n');
sb.append((A%C+B%C)%C);
sb.append('\n');
sb.append((A*B)%C);
sb.append('\n');
sb.append((A%C*B%C)%C);
System.out.println(sb);
*/

/*
BufferedWriter bw=new BufferedWriter(new OutputStreamWriter(System.out));
bw.write((A+B)%C)+"\n");
bw.write(((A%C+B%C)%C)+"\n");
bw.write((A*B)%C)+"\n");
bw.write(((A%C*B%C)%C)+"\n");
bw.flush();
bw.close();
*/
}
}
