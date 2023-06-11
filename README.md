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

import java.util.*;<br>
class Main<br>
{<br>
    public static void main(String[] args) {<br>
        ArrayList<String> al = new ArrayList<String>();<br>
        System.out.println("Size of ArrayList: " + al.size());<br>
        al.add("Jawa");<br>
        al.add("KTM");<br>
        System.out.println("Elements of first ArrayList: " + al);<br>
        ArrayList<String> al2 = new ArrayList<String>();<br>
        al2.add("R15");<br>
        al2.add("RoyalEnfiled");<br>
        al2.addAll(al);<br>
        System.out.println("Elements of second ArrayList: " + al2);<br>
        al2.remove("R15");<br>
        System.out.println("Elements of ArrayList after deletion: " + al2);<br>
        System.out.println("Size of ArrayList: " + al2.size());<br>
        System.out.println("The element at 2nd index is: " + al2.get(2));<br>
    }<br>
}

## OUTPUT:
  <img width="417" alt="java ex8 op" src="https://github.com/divvisha/ADD-RETREIVE-REMOVE/assets/127508123/b112460b-ae60-411a-8ae3-44fa5758cb4a">

## RESULT:
  Thus the program to add, retreive and remove the element from an arraylist has been created and executed successfully.
  
