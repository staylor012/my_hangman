```java

public class Main {
    
    public static String getHangMAn(int numWrongGuesses){

        switch(numWrongGuesses){

            case 0:
                return  """
                        -----------------
                        |                |
                        |
                        |
                        |
                        |
                        |
                        |
                   `    |
                        |
                        |
                       ===
                        """;
            case 1:

                return  """
                        -----------------
                        |                |
                        |              ('_')
                        |                
                        |
                        |
                        |
                        |
                        |
                        |
                        |
                       ===
                        """;
            case 2:
                return  """
                        -----------------
                        |                |
                        |              ('?')
                        |                |
                        |
                        |
                        |
                        |
                        |
                        |
                        |
                       ===
                        """;
            case 3:
                return """
                        -----------------
                        |                |
                        |             (0 _ 0)
                        |                |
                        |               [ ]  
                        |
                        |
                        |
                        |
                        |
                        |
                       ===
                        """;
            case 4:
                return  """
                        -----------------
                        |                |
                        |              (~_0)
                        |                |
                        |             \\ [ ]
                        |
                        |
                        |
                        |
                        |
                        |
                       ===
                        """;
            case 5:
                return """
                        -----------------
                        |                |
                        |              (~_~)
                        |                |
                        |              \\[ ]/  
                        |
                        |
                        |
                        |
                        |
                        |
                       ===
                        """;
            case 6:
                return """
                        -----------------
                        |                |
                        |              ('_+)
                        |                |
                        |              \\[ ]\\_  
                        |                |  
                        |
                        |
                        |
                        |
                        |
                       ===
                        """;
            case 7:
                return  """
                        -----------------
                        |                |
                        |              (+_')
                        |                |
                        |             _/[ ]\\_  
                        |                | 
                        |               [
                        |
                        |
                        |
                        |
                       ===
                        """;
            case 8:
                return  """
                        -----------------
                        |                |
                        |              (!_')
                        |                |
                        |             _/[ ]\\_  
                        |                | 
                        |               [ ]
                        |
                        |
                        |
                        |
                       ===
                        """;
            case 9:
                return  """
                        -----------------
                        |                |
                        |              ('_x)
                        |                |
                        |              /[ ]\\_  
                        |                | 
                        |               [ ]
                        |               |
                        |
                        |
                        |
                       ===
                        """;
            case 10:
                return  """
                        -----------------
                        |                |
                        |              (x_x)
                        |                |
                        |              /[ ]\\  
                        |                | 
                        |               [ ]
                        |               | |
                        |
                        |
                        |
                       ===
                        """;


            default:
                return null;
        }
    }
    public static void main(String[] args) {

        
        System.out.println(getHangMAn(9));


    }
}
```
