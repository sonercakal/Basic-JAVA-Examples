package cokludizi;


public class Cokludizi {

    
    public static void main(String[] args) {
        int firstarray[][] ={{8,9,10,11,12},{13,14,15,16}};
        int secondarray[][] = {{90,91,93},{8888},{23,24,25}};
        System.out.println("ilk dizi");
         display(firstarray);
        System.out.println("ikinci dizi");
         display(secondarray);
      
        
    }
    public static void display (int x[][]){
        for (int row=0;row<x.length;row++){
            for(int column=0;column<x[row].length;column++){
                System.out.print(x[row][column]+"\t");
                
            }
            System.out.println();
        }
            
    }
    
}
