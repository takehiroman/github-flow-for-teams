# 付録

## 2,3,5でGithubを表示するプログラム

~~~{.java}
public class FizzBuzz{
    public static void main(String[] args){
        for(int i=1; i<=100; i++){
            if((i%3==0) && (i%5==0) && (i%2==0)){
                System.out.println("Github");
            }else if((i%3==0) && (i%5==0)){
                System.out.println("FizzBuzz");
            }else if(i%3==0){
                System.out.println("Fizz");
            }else if(i%5==0){
                System.out.println("Buzz");
            }else{
                System.out.println(i);
            }
        }
    }
}
~~~

