# Practica_Matriz
Practica OpenBootcamp

public class matriz {
    private static int i;

    public static void main(String[] args) {

        int  [][] numeros = new int [3][4];

        numeros[0][0]=10;
        numeros[0][1]=20;
        numeros[0][2]=25;
        numeros[0][3]=30;

        numeros[1][0]=40;
        numeros[1][1]=50;
        numeros[1][2]=80;
        numeros[1][3]=85;

        numeros[2][0]=40;
        numeros[2][1]=50;
        numeros[2][2]=80;
        numeros[2][3]=85;



        for (int i = 0; i < 3 ;  i++) {
            System.out.println();
            for (int j=0; j < 4 ; j++){

                System.out.println(numeros[i][j] +"");



            }
        }
    }
}
