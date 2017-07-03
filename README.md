# Rev
import java.io.*;
import java.util.*;
  public class Rev{
    
    public static void main(String args[])throws IOException
    {
      
      BufferedReader br=new BufferedReader(new InputStreamReader(System.in));
      String a=br.readLine();
      
      String c=new StringBuffer(a).reverse().toString();
      System.out.println(c);
      }}
      
