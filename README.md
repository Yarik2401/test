package com.company;

import javax.lang.model.element.Name;

/**
* Created by aroslav on 28.11.16.
*/
public class Dog {
String name;
String says ;
public Dog(String name,String says )
{
this.name=name;
this.says=says;
}
public void setName(String name)
{
this.name=name;

}
public String getName()
{
return name;
}

public void setSays(String says)
{
this.says=says;

}
public String getSays()
{
return says;
}

}
___________________________________
package com.company;
import java.util.Scanner;

public class Main {

static Scanner sc = new Scanner(System.in);

public static void main(String[] args) {

Dog p=new Dog("Spot","Ruff!");
System.out.println(p.getName());
System.out.println(p.getSays());
Dog k=new Dog("Scruffy", "Wurf!");
System.out.println(k.getName());
System.out.println(k.getSays());

// write your code here
}
}

