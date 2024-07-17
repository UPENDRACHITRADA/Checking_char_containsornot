import java.util.*;
public class Main {
    public static void main(String args[]) {
        String s[] = {"abc","bcb","ccc","aaa"};
        int n= s.length;
        ArrayList<Integer> result = new ArrayList<Integer>();
        String s1 = "a";
        for(int i =0;i<n;i++) {
            if(s[i].contains(s1)) {
                result.add(i);
            }
        }
        System.out.println(result);
    }
}
