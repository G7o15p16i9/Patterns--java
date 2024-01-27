# Patterns--java
Loops- Controle
import java.util.Scanner;

// public static void main(String[] args) {
//     Scanner sc = new Scanner(System.in);
//     int n = sc.nextInt();
      /*    Squre Pattern
             ******
             ******
             ******
             ******
       */  
        // for(int i = 0;i < n;i++){
        //     for(int j = 0; j < n;j++){
        //         System.out.print("*"+ i);
        //     }
        //     System.out.println();
        // }
// public class Pattern {
    /*Square hallow pattern
     * ********
     * *      *
     * *      *
     * *      *
     * ********
     */
//     public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);
//         int n = sc.nextInt();

//         for(int i = 0;i < n;i++){
//             for(int j = 0; j < n;j++){
//                 if(i == 0 ||  j == 0 || i == n -1 || j == n-1){
//                 System.out.print("*" + " ");
//             }
//             else{
//                 System.out.print("  ");
//             }
//         }
//         System.out.println();
//         }
//     }
// }


// public class Pattern {
//     /* Number Increasing Piramid
//      * 1
//      * 1 2
//      * 1 2 3
//      * 1 2 3 4
//      */
//     public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);
//         int n = sc.nextInt();

//         for (int i = 0; i < n ; i++) {
//             for (int j = 0; j <= n ; j++) {
                
//                     System.out.print(" ");
//                 }
//                 for(int j = 1; j <= i;j++){
//                     System.out.print(j + " ");
//                 }
//                 System.out.println();
//             }
            
//         }
//     }


// public class Pattern {
//     /* Number Increasing Reverse Pyramid
//     1 2 3 4
//     1 2 3
//     1 2
//     1
//      */
//     public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);
//         int n = sc.nextInt();

//         for (int i = 0; i < n ; i++) {
//             for (int j = 0; j <= i ; j++) {
                
//                     System.out.print(" ");
//                 }
//                 for(int j = 1; j <= n - i;j++){
//                     System.out.print(j + " ");
//                 }
//                 System.out.println();
//             }
            
//         }
//     }

// public class Pattern {
//     /* Number Changing  Pyramid
//     1
//     2 3
//     4 5 6
//     7 8 9 10 
//     */
//     public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);
//         int n = sc.nextInt();
//         int num = 1;
       
//         for (int i = 1; i < n ; i++) {
//                 for(int j = 1; j <= i;j++){
//                     System.out.print(num + " ");
//                     num++;
//                 }
//                 System.out.println();
//             }
//            }
//         }
    
// public class Pattern {
//     /* Zero one triangle
//      * 1
//      * 0 1
//      * 1 0 1
//      * 0 1 0 1
//      */
//     public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);
//         int n = sc.nextInt();

//         for (int i = 0; i < n ; i++) {
//             for (int j = 0; j <= i ; j++) {
//                 if((i + j) % 2 == 0 ){
//                     System.out.print(1 + " ");
//                 }else{
//                     System.out.print(0 + " ");
//                 }
//                 }
//                 System.out.println();
//             }
            
//         }
//     }

// public class Pattern {
//     /* Palindrome Triangular
//             1
//           2 1 2
//         3 2 1 2 3
//        4 3 2 1 2 3 4 
//      */
//     public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);
//         int n = sc.nextInt();

//         for (int i = 1; i < n ; i++) {
//             for (int j = 1; j <=2 * (n - i) ; j++) {
                
//                     System.out.print(" ");
//                 }
//                 for(int j = i; j >= 1;j--){
//                     System.out.print(j+ " ");
//                 }
//                 for(int j = 2; j <= i;j++){
//                     System.out.print(j+ " ");
//                 }
//                 System.out.println();
//             }
            
//         }
//     }


// public class Pattern {
//     /* Rhombus Pattern
//         * * * *
//          * * * *
//           * * * *
//            * * * * 
//      */
//     public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);
//         int n = sc.nextInt();
//             for(int i = 0; i < n; i++){
//                 for(int j = 0; j < i; j++){
//                     System.out.print(" ");
//                 }
//                 for(int j = 0;j < n; j++){
//                     System.out.print("*" + " ");
//                 }
//                 System.out.println();
//             }
//         }
//     }



// public class Pattern {
//     /* Diamond Pattern
//           *
//         *   *
//       *   *   *
//         *    *
//           *
//      */
//     public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);
//         int n = sc.nextInt();
//             for(int i = 0; i <  n; i++){
//                 for(int j = 0; j < n-i; j++){
//                     System.out.print(" ");
//                 }
//                 for(int j = 0;j < i; j++){
//                     System.out.print("*" + " ");
//                 }
//                 System.out.println();
//             }
//             for(int i = 0; i <  n; i++){
//                 for(int j = 0; j < i; j++){
//                     System.out.print(" ");
//                 }
//                 for(int j = 0;j < n-i; j++){
//                     System.out.print("*" + " ");
//                 }
//                 System.out.println();
//             }
//         }
//     }

// public class Pattern {
//     /* Butterfly Star Pattern
//         *                          *
//            *                   *
//         *     *            *       *
//            *     *     *       *
//         *     *     *      *       *
//            *     *     *       *
//         *     *            *       *
//            *                   *
//         *                          *
//      */
//     public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);
//         int n = sc.nextInt();
//        Butterfly(n); 
//     }
//     static void Butterfly(int n){
//         int i , j ;
//         for(i = 1; i <= n;i++){
//             for(j = 1; j <= i;j++){
//                 System.out.print("*" + " ");
//             }
//             int space = 2 * (n - i);
            
//             for(j = 1; j <= 2*space;j++){
//                 System.out.print(" ");
//             }
//             for(j = 1;j <= i; j++){
//                 System.out.print("*"+ " ");
//             }
//             System.out.println();
//         }
//         for(i = n;i >= 1;i-- ){
//             for(j = 1; j <= i; j++){
//                 System.out.print("*" + " ");
//             }
//             int space = 2 * (n - i);
//             for(j = 1;j <= 2*space;j++){
//                 System.out.print(" ");
//             }
//             for(j = 1; j <= i;j++){
//                 System.out.print("*"+ " ");
//             }
//             System.out.println();
//         }
//     }
// }


// public class Pattern{
//     //Square Fill Pattern
//     /* ******
//      * ******
//      * ******
//      * ******
//      */
//     public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);
//         int n = sc.nextInt();
//         for(int i = 0;i< n;i++){
//             for(int j = 0;j <  n;j++){
//                 System.out.print("*" + " ");
//             }
//             System.out.println();
//         }
//     }
// }

// public class Pattern{
//         //Right Half Triangle
//         /* *
//            * *
//            * * *
//            * * * *
//          */
//         public static void main(String[] args) {
//             Scanner sc = new Scanner(System.in);
//             int n = sc.nextInt();
//             for(int i = 0;i< n;i++){
//                 for(int j = 0;j <=  i;j++){
//                     System.out.print("*" + " ");
//                 }
//                 System.out.println();
//             }
//         }
//     }


// public class Pattern{
//         //Reverse Right Half Pyramid
//         /*  * * * * *
//             * * * *
//             * * *
//             * *
//             *
//          */
//         public static void main(String[] args) {
//             Scanner sc = new Scanner(System.in);
//             int n = sc.nextInt();
//            for(int i = 0; i < n;i++){
//             for(int j = n - i; j > 0;j--){
//                 System.out.print("*" + " ");
//             }
//             System.out.println();
//            }
//         }
//     }

// public class Pattern{
//         //Left Half Pyramid
//         /*          *
//                   * *
//                 * * *
//               * * * *
//             * * * * *
//          */
//         public static void main(String[] args) {
//             Scanner sc = new Scanner(System.in);
//             int n = sc.nextInt();
//             for(int i = 1;i<= n;i++){
//                 for(int j =2 * (n-i);j >= 1;j--){
//                     System.out.print(" ");
//                 }
//                 for(int j = 1;j <= i;j++){
//                     System.out.print("*" + " ");
//                 }
//                 System.out.println();
//             }
//         }
//     }


// public class Pattern{
//         //Reverse Left Half Pyramid
//         /*  * * * * *
//               * * * *
//                 * * *
//                   * *
//                     *
//          */
//         public static void main(String[] args) {
//             Scanner sc = new Scanner(System.in);
//             int n = sc.nextInt();
//             for(int i = n;i > 0;i--){
//                 for(int j = 0;j < 2*(n-i);j++){
//                     System.out.print(" ");
//                 }
//                 for(int j = 0;j < i;j++){
//                     System.out.print("*" + " ");
//                 }
                
//                 System.out.println();
//             }
//         }
//     }


// public class Pattern{
//     //K Pattern
//     /*  * * * * *
//         * * * *
//         * * * 
//         * *
//         *
//         * *
//         * * *
//         * * * *
//         * * * * *
//      */
//     public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);
//         int n = sc.nextInt();
//      for(int i = 0; i< n; i++){
//         for(int j = n - i;j > 0;j--){
//             System.out.print("*" + " ");
//         }
//         System.out.println();
//      }
//      for(int i = 1; i<= n; i++){
//         for(int j = 1;j <= i;j++){
//             System.out.print("*" + " ");
//         }
//         System.out.println();
//      }
//     }
// }



// public class Pattern{
//     //Triangle Star Pattern
//     /*      *
//            * *
//           * * *
//          * * * *
//         * * * * *
//      */
//     public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);
//         int n = sc.nextInt();
//         for(int i = 0;i < n;i++){
//             for(int j = n - i;j > 0;j--){
//                 System.out.print(" ");
//             }
//             for(int j = 0; j <= i; j++ ){
//                System.out.print("*" + " ");
//             }
//             System.out.println();
//         }
//     }
// }


// public class Pattern{
//     //Reverse Number Triangle Pattern
//     /*     1 2 3 4
//             2 3 4
//              3 4
//               4
//      */    public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);
//         int n = sc.nextInt();
//         int num  = 5;
//         for(int i = 1;i <= n;i++){
//             for(int j = 1; j < i; j++){
//                System.out.print(" "); 
//             }
//             for(int j = i;j <= n;j++){ 
//                 System.out.print(j + " ");
                
//             }
//             System.out.println();
//         }
//     }
// }

// public class Pattern{
//     //Mirror Image Triangle Pattern
//     /*     1 2 3 4
//             2 3 4
//              3 4
//               4
//              3 4
//             2 3 4
//            1 2 3 4
//      */    public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);
//         int n = sc.nextInt();
//         for(int i = 1;i < n;i++){
//             for(int j = 1; j < i; j++){
//                System.out.print(" "); 
//             }
//             for(int j = i;j < n;j++){ 
//                 System.out.print(j + " ");
                
//             }
//             System.out.println();
//         }
//         for(int i =n- 1;i >= 1;i--){
//             for(int j = 1; j < i; j++){
//                System.out.print(" "); 
//             }
//             for(int j = i;j < n ;j++){ 
//                 System.out.print(j + " ");
                
//             }
//             System.out.println();
//         }
//     }
// }

// public class Pattern{
//     //Hollow Triangle Pattern
//     /*       *
//             * *
//            *   *
//           *     *
//         *         *
//        * * * * * * * *
//      */    public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);
//         int n = sc.nextInt();
//       for(int i = 1; i <= n;i++){
//         for(int j = i;j < n ; j++){
//             System.out.print("  ");
//         }
//         for(int k = 1; k <= ( 2 * i - 1); k++){
//             if(k == 1 || i == n || k == (2 * i - 1)){
//                 System.out.print("*" + " ");
//             }else{
//                 System.out.print("  ");
//             }
//         }
//         System.out.println();
//       }
//     }
// }

// public class Pattern{
//     //Hallow Reverse Triangle Patern
//     /*      * * * * * *
//              *       *
//               *     *
//                *   *
//                  *  
//      */    public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);
//         int n = sc.nextInt();
//       for(int i = n; i >0;i--){
//         for(int j = i;j < n ; j++){
//             System.out.print("  ");
//         }
//         for(int k = 1; k <= ( 2 * i - 1); k++){
//             if(k == 1 || i == n || k == (2 * i - 1)){
//                 System.out.print("*" + " ");
//             }else{
//                 System.out.print("  ");
//             }
//         }
//         System.out.println();
//       }
//     }
// }


// public class Pattern{
//     //Hallow Hour Glass Pattern
//     /*    * * * * * * * *
//             *         *
//               *     *
//                 *  *
//                   *
//                  *
//                 * *
//                *   *
//               *     *
//             *         *
//            * * * * * * *
//      */    public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);
//         int n = sc.nextInt();
//         for(int i = n; i > 0;i--){
//             for(int j = i;j < n ; j++){
//                 System.out.print("  ");
//             }
//             for(int k = 1; k <= ( 2 * i - 1); k++){
//                 if(k == 1 || i == n || k == (2 * i - 1)){
//                     System.out.print("*" + " ");
//                 }else{
//                     System.out.print("  ");
//                 }
//             }
//             System.out.println();
//           }
//       for(int i = 1; i <= n;i++){
//         for(int j = i;j < n ; j++){
//             System.out.print("  ");
//         }
//         for(int k = 1; k <= ( 2 * i - 1); k++){
//             if(k == 1 || i == n || k == (2 * i - 1)){
//                 System.out.print("*" + " ");
//             }else{
//                 System.out.print("  ");
//             }
//         }
//         System.out.println();
//       }
//     }
// }

// public class Pattern{
//     //Pascal's Triangle
//     /*      1
//           1   1
//         1   2   1
//       1   3   3   1
//      */    public static void main(String[] args) {
//         Scanner sc = new Scanner(System.in);
//         int n = sc.nextInt();
//         for(int i = 1;i <= n; i++){
//             for(int j = 0;j <= n - i;j++){
//                 System.out.print(" ");
//             }
//             int  x = 1;
//             for(int k = 1; k <= i;k++){
//                 System.out.print(x + " ");
//                 x = x * (i - k) / k;
//             }
//             System.out.println();
//         }
//      }
//  }

public class Pattern{
    //Right Pascal's Triangle
    /*   *
            *
         *     *
            *     *
         *     *
            *  
         *  
         
     */    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        for(int i = 1;i <= n; i++){
            for(int j = 1;j <= i ;j++){
                System.out.print("*" + " ");
            }            
            System.out.println();
        }
        for(int i = n - 1; i >= 1; i--){
            for(int j = 1; j <= i; j++){
                System.out.print("*" + " ");
            }
            System.out.println();
        }
     }
 }
