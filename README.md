# zoho-recruitment-2020
public class Main {
  public static void main(String[] args) {
    String str = "welcome";
   int len = str.length();
        int middle = len / 2;
        char[] ch = new char[str.length()];
        for (int i = middle; i < str.length(); i++) {
            ch[i] = str.charAt(i);
            System.out.print(ch);
            }
            for (int i = 0;i <middle ; i++) {
            ch[i] = str.charAt(i);
            System.out.println(ch);}
            
        
        
  }
}
