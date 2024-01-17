# JavaSpark
Spark using Java from Zero to intermediate
**JAVA ARRAYS 1  DIMENSIONAL**
import java.sql.SQLOutput;
import java.util.*;
public class Main {


    public static void main(String[] args) {
    Scanner sc=new Scanner(System.in);
        System.out.println("Enter The size of the array :");
    int size= sc.nextInt();
    int array[]= new int [size];
    for(int i=0;i<size;i++){
        System.out.println("Enter the "+ i + " Element");
        array[i]= sc.nextInt();
    }
    System.out.println("Enter the Element to search :");
    int search = sc.nextInt();
    for(int i= 1; i <size;i++){
        if(array[i]==search){
            System.out.println("Element Found at index " + i);
        }
    }


    }
}
