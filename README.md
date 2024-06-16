public class aprendizado{
    public static void main(String[] args){

        int mariano = 30;
        double israel = 20.5;
        int rodolfo = (int) israel;

        System.out.println(israel + mariano);

        char basico = 's';
        String restante = "bomba";

        System.out.println(restante + basico);

        double ovo = 7.5;
        int ovos = 10;
        double soma = ovos * ovo;
        
        if (ovos <= 10)

        System.out.println (String.format ("o valor do ovos sairam %.2f" , soma));
        
        else 
        
        System.out.println( "nao temos essa quantidade"); 

        int real = 1;
        double dolares = 4.50;


        if(real <= 10)

        System.out.println  (String.format("o valor do real esta %d porem o valor em dolar e %.2f",real , dolares));

        else System.out.println("o valor nao explicado" );


        System.out.println("mas para efeito de comparacao tem como nos termo uma nocao basica de quanto custaria 2 dolares e " + dolares * 2 );

        int moeda = (int) dolares;

    }
}
