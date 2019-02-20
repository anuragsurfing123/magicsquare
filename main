import java.util.Scanner;
class Magicsquare
{
public static void main(String ... args)
{
System.out.println("Enter any odd no");
Scanner sc=new Scanner(System.in);
int n=sc.nextInt();
int [][] MagicSquare=new int[n][n];
int num=1;
int row=0;
int column=n/2;
int crow;
int ccol;
while(num<=n*n)
{

MagicSquare [row][column]=num;
num++;
crow=row;
ccol=column;
row=row-1;
column=column+1;
if (row == -1) {
            row = n - 1;
        }
        if (column == n) {
            column = 0;
        }
        if (MagicSquare[row][column] != 0) {
            row = crow + 1;
            column = ccol;
            if (row == -1) {
                row = n - 1;
            }}





}
for(int i=0;i<MagicSquare.length;i++){
for(int j=0;j<MagicSquare.length;j++)
{
System.out.print(MagicSquare[i][j]+" ");

}
System.out.println();
}
}
}
