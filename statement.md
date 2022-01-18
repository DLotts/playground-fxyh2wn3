import java.util.stream.*;

# Welcome!
This Java template lets you get started quickly with a simple one-page playground.

```java runnable
// { autofold
public class Main {

public static void main(String[] args) {
// }

// Stream sum of even numbers includeing 2 up to including N
int N=4;
System.out.println(IntStream.rangeClosed(2,N).filter(x -> x%2==0).sum());
// 6

//{ autofold
}

}
//}
```

# Advanced usage

If you want a more complex example (external libraries, viewers...), use the [Advanced Java template](https://tech.io/select-repo/385)
