En este primer archivo conocimos lo basico de dart con este codigo, el cual en este momento lo estamos usando para imprimir el nombre definiendo constantes,
viendo la diferencia entre variables y constantes
void main() {
  //var myname = 'Name';
    //String myname = 'Name';
  late final myname; //Declarar constantes que no cambian de valor desde su definición, mientras que en const puede cambiar su valor antes de la contrucción
  myname = 'Name';
  print('Hola, ${myname.toUpperCase()}');
}
