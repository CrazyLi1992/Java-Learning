# Java-Learning
# Hello World!!!!
public class MyFirstApp{
  
  public static void main (String[] args){
    
    System.out.println("I Rule!");
    System.out.println("The World");
    
  } 

}


# while循环的范例
public class loopy{

  public static void main (String[] args){
  
  int x = 1;
  System.out.println("Before the Loop");
  while (x<4){
  
    System.out.println("In the Loop");
    System.out.println("Value of x is" + x);
      x = x + 1;
      
   }
  
  System.out.println("This is after the Loop");
  
  }
}


#if循环的范例1
class IfTest{
  public static void main(String[] args){
    int x = 3;
    if(x == 3){
      System.out.println("x must be 3");

}
      System.out.println("This runs no matter what");
}
}

#if循环的范例2
class IfTest2{
  public static void main(String[] args){
    int x = 2;
    if(x == 3){
      System.out.println("x must be 3");
}else{
      System.out.println("x is not 3");

      }
    System.out.println("This runs no matter what");
}
}

# 从99到0计数
public class ss{
  public static void main(String[] args){
    int x = 99;
    while(x>0){
      System.out.println(x);
      x = x-1;
    }
    if(x==0){
      System.out.print(x);
    }
  }
}
 # 数啤酒瓶童谣
 public class BeerSong{
  public static void main (String[] args){
    int beerNum = 99;
    String word = "bottles ";
    while(beerNum>0){
      if(beerNum == 1){
        word = "bottle";
      }
    System.out.println(beerNum + " " + word + "of beer on the wall");
    System.out.println(beerNum + " " + word +"of beer");
    System.out.println("Take one down");
    System.out.println("Pass it around");
    beerNum = beerNum - 1;
    if(beerNum>1){
      System.out.println(beerNum + " " + word + "of beer on the wall");
      }else{
      System.out.println("No more bottles of beer on the wall");
      }
    }
  }
}
