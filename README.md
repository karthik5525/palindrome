# palindrome
import java.util.Scanner;

class palindrome

{public static void main(String args[])

  {String word;

  int i;

  boolean isPalindrome=true;

  Scanner sc=new Scanner(System.in);

  System.out.println("Enter your string");

  word=sc.nextLine();

  String copy=word;

  word=word.toLowerCase();

  int length=word.length();

  for(i=0;i<(length/2);i++)

      {if(word.charAt(i)!=(word.charAt(length-i-1)))

        {isPalindrome=false;

        break;

        }

      }

  if(isPalindrome)

  System.out.println("is Palindrome");

  else

  System.out.println("not Palindrome");

  }	

}


