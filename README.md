# EXPERIMENT-8 JAVA PROGRAM TO ADD, RETREIVE AND REMOVE THE ELEMENT FROM AN ARRAYLIST.

## AIM:
To write a Java program to add , remove, retrieve an element in an Array.

## ALGORITHM:
1. Open Intelli J application or any other code editor.

2.  Create an array with a name of your choice.

3. Using Scanner, Input a number or a element from the user.

4. Using for loop insert,remove,retrieve the input element at the end of the array.

5. Display the appended array in the terminal.

## PROGRAM:

import java.util.*;

class Main

{

    public static void main(String[] args) {
    
        ArrayList<String> al = new ArrayList<String>();
        
        System.out.println("Size of ArrayList: " + al.size());
        
        al.add("Jawa");
        
        al.add("KTM");
        
        System.out.println("Elements of first ArrayList: " + al);
        
        ArrayList<String> al2 = new ArrayList<String>();
        
        al2.add("R15");
        
        al2.add("RoyalEnfiled");
        
        al2.addAll(al);
        
        System.out.println("Elements of second ArrayList: " + al2);
        
        al2.remove("R15");
        
        System.out.println("Elements of ArrayList after deletion: " + al2);
        
        System.out.println("Size of ArrayList: " + al2.size());
        
        System.out.println("The element at 2nd index is: " + al2.get(2));
        
    }
    
}

## OUTPUT:
  <img width="417" alt="java ex8 op" src="https://github.com/divvisha/ADD-RETREIVE-REMOVE/assets/127508123/b112460b-ae60-411a-8ae3-44fa5758cb4a">

## RESULT:
  Thus the program to add, retreive and remove the element from an arraylist has been created and executed successfully.
  
