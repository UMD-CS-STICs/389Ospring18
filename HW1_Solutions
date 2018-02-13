# Homework
- [Lonely Integer](https://www.hackerrank.com/challenges/ctci-lonely-integer/problem)
- [Bitwise-And](https://www.hackerrank.com/challenges/30-bitwise-and/problem)
  
## Potential Solutions
1. (Java Solution)

public static int lonelyInteger(int[] a) {
    int value = 0;

    for (int i : a) {
        value ^= i;
    }
    return value;
}

2. (Java Solution)
public class Solution {
    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        int t = in.nextInt();
        for(int a0 = 0; a0 < t; a0++){
            int n = in.nextInt();
            int k = in.nextInt();
            if(((k-1)|k) > n && k%2==0){
                System.out.println(k-2);
            }else{
                System.out.println(k-1);               
            }
        }
    }
}
