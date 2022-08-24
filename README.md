# aula-do-dia-24

public static void main(String[] args) {

Scanner entrada = new Scanner (System.in);
double salario = 1000.00;
int total_carros ;
System.out.println ("Informe a quantidade de carros vendidos ");
total_carros = entrada.nextInt();
if ( total_carros < 5 ){
total_carros = total_carros*500;
salario = salario+total_carros;
System.out.println( " Valor do salario com comissao : " +salario);
}
else {
total_carros = total_carros*1000;
salario = salario+total_carros;
System.out.println( " Valor do salario com comissao : " + salario);
