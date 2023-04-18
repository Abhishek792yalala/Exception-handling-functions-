# Exception-handling-functions-
// Problem: Exception handling using the exception functions

class Code{

    public static int divide(int a, int b) throws ArithmeticException{

        int res=a/b;

        return res;

    }

    public static void main(String... java){

        try {

            int c = divide(4, 0);

            System.out.println(c);

        }

        catch (Exception e){

            System.out.println("Checked Exception... please try again");

        }

    }

}

//Checked Exception... please try again
