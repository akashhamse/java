package javaapplication1;

/**
 * inheritance
 * @author akashhamse.e
 */
public class JavaApplication1 extends B {
    
    private int B=20;
    public void print1(){
        System.out.println("child class");
    }
    public static void main(String args[]){
        JavaApplication1 javaapplication1 = new JavaApplication1();
        javaapplication1.print();
   
   }
}
class B {
    private int a=10;
   public void print(){
       System.out.println("parent class");
    }
}

   
