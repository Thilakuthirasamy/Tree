import java.util.*;
public class Tree
{
public static void main(String[] args)
{
    Scanner s=new Scanner(System.in);
    String str=s.nextLine();
    String str2="";
    String[] str1=str.split("");
    LinkedHashSet<String> lh=new LinkedHashSet<String>();
    for(int i=0;i<str1.length;i++)
    {
    lh.add(str1[i]);
    }
    str2=lh.toString();
    String str3=str2.replace("[","").replace("]","").replace(",","").replace(" ","");
    System.out.println(str3);

}
}



