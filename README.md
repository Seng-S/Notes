# Notes 

## Java

How to declare and use a function in Java

```Java 
public class MyProgram
{
    public static void main(String[] args)
    {
    //Declaring a variable
        String text = "mamamia he gun mad";
    //Calling a function
        printing(text);
    } 
    
    //Declaring a public static function
    public static String printing (String text) {
        System.out.println(text);
        return text;
    }
}
```

ComputeClosestToZero(int[] ts)
```Java
public static int computeClosestToZero(int[] ts) {
        // Write your code here
        // To debug: System.err.println("Debug messages...");

        if (ts.length == 0) {
            return 0;
        }

        int res = ts[0];

        for (int i : ts) {
            int x = Math.abs(i);
            int y = Math.abs(res);

            if (y > x) {
                res = x;
            } else if (y == x) {
                res = y;
            }

        }
        return res;
    }
    ```
    
    Compare weights
    ```JavaScript
    function solve(weight0, weight1, weight2) {
    // Write your code here
    // To debug: console.error('Debug messages...');
    const array = [weight0, weight1, weight2]

    if (array.lenght == 0) {
        return 0
    }

    const highest = Math.max(...array);
    const results = array.indexOf(highest);

    return results;
}
```

