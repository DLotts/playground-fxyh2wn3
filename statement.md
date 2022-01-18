import java.util.stream.*;

# Silly reminider of streams
Stream sum of even numbers includeing 2 up to including N.  Go to the Java streams cheat sheet for more.

```java runnable
// { autofold
public class Main {

public static void main(String[] args) {
// }

int N=4;
System.out.println(IntStream.rangeClosed(2,N).filter(x -> x%2==0).sum());
// 6

//{ autofold
}

}
//}

