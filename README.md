# Natural-No-program.java

import java.util.*;

class Natural {

Scanner sc=new Scanner(System.in);

public static void main(String args[]) {

Natural na=new Natural();

na.naturalNo();

}

void naturalNo()

{

int num=sc.nextInt();

int i=1;

int res=0;

while(i<=num)

{

res=res+i;

i++;

}

System.out.println(res);


}

}
