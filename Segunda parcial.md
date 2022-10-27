# Segunda Parcial
## Diagramas de flujo de datos elaborados a lo largo de la segunda parcial por medio de for, while, do while y vectores

### Ejercicio 1. Realiza un dfd que cuente del 1 al 10

#### 1.1 Análisis
1,2,3,4,5,6,7,8,9,10  

#### 1.2 Diagrama de Flujo de Datos
#### For
![dfd1for](https://user-images.githubusercontent.com/113869976/197417497-06e229be-0ec9-4bff-ae4c-b3e88aa20f69.jpg)

#### While
![dfd1while](https://user-images.githubusercontent.com/113869976/197417509-42575ea8-6c84-465e-b0f7-36addfc5cdc0.jpg)

#### Do while
![dfd1dowhile](https://user-images.githubusercontent.com/113869976/197417516-af9cfdf1-d1d3-49ba-b44f-d1a6b942320e.jpg)

#### 1.3 Prueba de Escritorio
#### For
![image](https://user-images.githubusercontent.com/113869976/197417878-c87a1150-b629-4076-a7e4-5ade7a52e052.png)

#### While
![image](https://user-images.githubusercontent.com/113869976/197417882-bde40aea-e7f6-4a10-b1c8-16646983d980.png)

#### Do while
![image](https://user-images.githubusercontent.com/113869976/197417887-fbeee6b7-5f17-40c3-9fd3-b61bda27f3a0.png)

#### 1.4 Entradas
NA
#### 1.5 Salidas
1 2 3 4 5 6 7 8 9 10
#### 1.6 Código dart
#### For
void main() {  
  for (var i = 1; i <= 10; i++) {  
    print(i);  
  }  
}  
#### While
void main() {  
  int cont = 1;  

  while (cont <= 10) {  
    print(cont);  
    cont = cont + 1;  
  }  
}  
#### Do while
void main() {  
  int cont = 1;  
  do {  
    print(cont);  
    cont = cont + 1;  
  } while (cont <= 10);  
}  

### Ejercicio 2. Dfd que cuente del 1 al 10 y sume todos los números

#### 2.1 Análisis
1,2,3,4,5,6,7,8,9,10  
1+2+3+4+5+6+7+8+9+10=55  

#### 2.2 Diagrama de Flujo de Datos
#### For
![dfd2for](https://user-images.githubusercontent.com/113869976/197418355-6778287a-f3df-48ee-a63d-7679b9211bd3.jpg)

#### While
![dfd2while](https://user-images.githubusercontent.com/113869976/197418354-49177314-d51e-475c-a590-445782144c50.jpg)

#### Do while
![dfd2dowhile](https://user-images.githubusercontent.com/113869976/197418345-5b385b50-f9fd-46a4-9964-6e83239d9a83.jpg)

#### 2.3 Prueba de Escritorio
#### For
![image](https://user-images.githubusercontent.com/113869976/197418476-67b4837a-f642-4f61-9d7e-fa467c65a778.png)

#### While
![image](https://user-images.githubusercontent.com/113869976/197418482-7aa9927c-b4ee-4352-abd1-ae4398c29c51.png)

#### Do while
![image](https://user-images.githubusercontent.com/113869976/197418487-d42f2c9b-7aba-4bdf-97c0-25677f265271.png)

#### 2.4 Entradas
NA
#### 2.5 Salidas
1 2 3 4 5 6 7 8 9 10
55

#### 2.6 Código dart
#### For
void main() {  
  var Suma = 0;  
  for (var i = 1; i <= 10; i++) {  
    Suma = Suma + i;  
  }  
  print(Suma);  
}  
#### While
void main() {  
  int suma = 0;  
  int cont = 1;  

  while (cont <= 10) {  
    suma = suma + cont;  
    cont = cont + 1;  
  }  

  print(suma);  
}  
#### Do while
void main() {  
  var suma = 0;  
  int cont = 1;  

  do {  
    suma = suma + cont;  
    cont = cont + 1;  
  } while (cont <= 10);  

  print(suma);  
}  

### Ejercicio 3. Obtenga la suma de los 5 números pares del 1 al 10

#### 3.1 Análisis
1,(2),3,(4),5,(6),7,(8),9,(10)  
2,4,6,8,10  
2+4+6+8+10=30  

#### 3.2 Diagrama de Flujo de Datos
#### For
![dfd3for](https://user-images.githubusercontent.com/113869976/197418362-67eabfa2-cd72-4056-9ae1-846b1773b16e.jpg)

#### While
![dfd3while](https://user-images.githubusercontent.com/113869976/197418367-9069d502-1b68-430a-a959-b92957ba8a61.jpg)

#### Do while
![dfd3dowhile](https://user-images.githubusercontent.com/113869976/197418360-64d2fa76-b59a-4df3-8b0f-25caed0b41b8.jpg)

#### 3.3 Prueba de Escritorio
#### For
![image](https://user-images.githubusercontent.com/113869976/197418491-198b85b0-2fc7-40e7-8378-686317daf74a.png)

#### While
![image](https://user-images.githubusercontent.com/113869976/197418493-e19f5b31-fa63-4f5b-a440-c5fb96094df0.png)

#### Do while
![image](https://user-images.githubusercontent.com/113869976/197418497-768ff3b3-3fba-49e2-8f41-0154dfa5e6ac.png)

#### 3.4 Entradas
NA
#### 3.5 Salidas
30

#### 3.6 Código dart
#### For
void main() {  
  int suma = 0;  

  for (var i = 2; i <= 10; i += 2) {  
    suma = suma + i;  
  }  
  
  print(suma);  
}  
#### While
void main() {  
  int suma = 0;  
  int cont = 1;  

  while (cont <= 5) {  
    suma = suma + cont * 2;  
    cont = cont + 1;  
  }  

  print(suma);  
}  
#### Do while
void main() {  
  int suma = 0;  
  int cont = 1;  

  do {  
    suma = suma + cont * 2;  
    cont = cont + 1;  
  } while (cont <= 5);  

  print(suma);  
}  

### Ejercicio 4. Almacena en un array el número n leído del teclado. El tamaño del array es 10

#### 4.1 Análisis
[0] 9  
[1] 9  
[2] 9  
[3] 9  
[4] 9  
[5] 9  
[6] 9  
[7] 9  
[8] 9  
[9] 9  

#### 4.2 Diagrama de Flujo de Datos
#### For
![dfd4for](https://user-images.githubusercontent.com/113869976/197418395-31d4d079-8225-4b47-a6b0-3bd878723aa8.jpg)

#### While
![dfd4while](https://user-images.githubusercontent.com/113869976/197418407-19f5e827-3f90-434c-a1ce-892a113d715c.jpg)

#### Do while
![dfd4dowhile](https://user-images.githubusercontent.com/113869976/197418401-71e34807-d45e-4fc5-b823-157e932707e2.jpg)

#### 4.3 Prueba de Escritorio
#### For
![image](https://user-images.githubusercontent.com/113869976/197418510-7ad6bb0e-3e91-4569-9e8f-b297fac25051.png)

#### While
![image](https://user-images.githubusercontent.com/113869976/197418514-d86a99ab-4c4a-4f01-9cf0-a61f1dc7d088.png)

#### Do while
![image](https://user-images.githubusercontent.com/113869976/197418518-e852d24e-56e8-46a4-a0d0-d7ab77111f2e.png)

#### 4.4 Entradas
num=15
#### 4.5 Salidas
[0] 15  
[1] 15  
[2] 15  
[3] 15  
[4] 15  
[5] 15  
[6] 15  
[7] 15  
[8] 15  
[9] 15  

#### 4.6 Código dart
#### For
import 'dart:io';  
import 'dart:async';  

void main() {  
  var array = [];  
  int n = int.parse(stdin.readLineSync()!);  
  for (var i = 0; i < 10; i++) {  
    array.add(n);  
  }  
  print(array);  
}  
#### While
import 'dart:io';  
import 'dart:async';  
  
void main() {  
  var cont = 0;  
  var array = [];  
  int n = int.parse(stdin.readLineSync()!);  
  while (cont <= 9) {  
    array.add(n);  
    cont = cont + 1;  
  }  

  print(array);  
}  
#### Do while
import 'dart:io';  
import 'dart:async';  

void main() {  
  var cont = 0;  
  var array = [];  
  int n = int.parse(stdin.readLineSync()!);  
  do {  
    array.add(n);  
    cont = cont + 1;  
  } while (cont <= 9);  

  print(array);  
}  

### Ejercicio 5. Almacena los números leídos del teclao en un vector de 10 elementos

#### 5.1 Análisis
[0] 20  
[1] 18  
[2] 25  
[3] 36  
[4] 28  
[5] 14  
[6] 5  
[7] 9  
[8] 10  
[9] 50  

#### 5.2 Diagrama de Flujo de Datos
#### For
![dfd5for](https://user-images.githubusercontent.com/113869976/197418434-29b90c86-be77-41cb-b06b-36e7c5b55ae3.jpg)

#### While
![dfd5while](https://user-images.githubusercontent.com/113869976/197418436-9c320ccf-a9ae-4fcf-b8cb-fc1c0c719f2a.jpg)

#### Do while
![dfd5dowhile](https://user-images.githubusercontent.com/113869976/197418429-c9ca41af-efd8-44c1-a2fe-0172001a4646.jpg)

#### 5.3 Prueba de Escritorio
#### For
![image](https://user-images.githubusercontent.com/113869976/197418527-dcfcf7b6-7148-4e79-8449-c31e76f1d228.png)

#### While
![image](https://user-images.githubusercontent.com/113869976/197418531-ab107c13-76aa-4a37-bf23-7108db770685.png)

#### Do while
![image](https://user-images.githubusercontent.com/113869976/197418541-60b85e6f-04d6-4267-bca2-23b017d20f15.png)

#### 5.4 Entradas
num=19,8,6,9,2,4,36,18,20,25
#### 5.5 Salidas
[0] 19  
[1] 8  
[2] 6  
[3] 9  
[4] 2  
[5] 4  
[6] 36  
[7] 18  
[8] 20  
[9] 25

#### 5.6 Código dart
#### For
import 'dart:io';  
import 'dart:async';  

void main() {  
  var array = [];  

  for (var i = 0; i < 10; i++) {  
    int n = int.parse(stdin.readLineSync()!);  
    array.add(n);  
  }  
  print(array);  
}  
#### While
import 'dart:io';  
import 'dart:async';  

void main() {  
  var cont = 0;  
  var array = [];  

  while (cont <= 9) {  
    int n = int.parse(stdin.readLineSync()!);  
    array.add(n);  
    cont = cont + 1;  
  }  
  print(array);  
}  
#### Do while
import 'dart:io';  
import 'dart:async';  

void main() {  
  var cont = 0;  
  var array = [];  
  do {  
    int n = int.parse(stdin.readLineSync()!);  
    array.add(n);  
    cont = cont + 1;  
  } while (cont <= 9);  

  print(array);  
}  
### Ejercicio 6. Almacena un contador regresivo en un vector. El conteo es de 10 a 0

#### 6.1 Análisis
[0] 10  
[1] 9  
[2] 8  
[3] 7  
[4] 6  
[5] 5  
[6] 4  
[7] 3  
[8] 2  
[9] 1  
[10] 0  

#### 6.2 Diagrama de Flujo de Datos
#### For
![dfd6for](https://user-images.githubusercontent.com/113869976/197418443-c5ef11c3-24e6-45fb-aba2-25866fe50cf9.jpg)

#### While
![dfd6while](https://user-images.githubusercontent.com/113869976/197418446-2dbf5179-7ca6-4f34-becf-55e9f4c985d1.jpg)

#### Do while
![dfd6dowhile](https://user-images.githubusercontent.com/113869976/197418442-2ac64c44-faaf-464d-98f7-460ddf486f3b.jpg)

#### 6.3 Prueba de Escritorio
#### For
![image](https://user-images.githubusercontent.com/113869976/197418545-5345df89-7cd0-4f11-80dd-fb9456bd758a.png)

#### While
![image](https://user-images.githubusercontent.com/113869976/197933266-295e1433-6a2b-4da3-967a-670970b99ce8.png)

#### Do while
![image](https://user-images.githubusercontent.com/113869976/197933279-4be0da2b-3b88-48f3-b86e-b03d53dcc5a9.png)

#### 6.4 Entradas
NA
#### 6.5 Salidas
[0] 10  
[1] 9  
[2] 8  
[3] 7  
[4] 6  
[5] 5  
[6] 4  
[7] 3  
[8] 2  
[9] 1  
[10] 0  

#### 6.6 Código dart
#### For
void main() {  
  var array = [];  

  for (var i = 10; i >= 0; i--) {  
    array.add(i);  
  }  
  print(array);  
}  
#### While
void main() {  
  var array = [];  
  var c = 10;  

  while (c >= 0) {  
    array.add(c);  
    c--;  
  }  

  print(array);  
}  
#### Do while
void main() {  
  var array = [];  
  var c = 10;  
  do {  
    array.add(c);  
    c--;  
  } while (c >= 0);  

  print(array);  
}  

### Ejercicio 7. Almacene un vector de tamaño 10 todos los números pares capturados hasta completar 10

#### 7.1 Análisis
3,(8),15,(30),(18),17,(22),9,(16),(6),(8),(18),29,(12),(42)  
[0] 8  
[1] 30  
[2] 18  
[3] 22  
[4] 16  
[5] 6  
[6] 8  
[7] 18  
[8] 12  
[9] 42  

#### 7.2 Diagrama de Flujo de Datos
#### For
![dfd7for](https://user-images.githubusercontent.com/113869976/197418453-735d5ed8-5a27-48ab-8be2-c7ae4925a9d3.jpg)

#### While
![dfd7while](https://user-images.githubusercontent.com/113869976/197418455-3a66a8e4-563f-4654-8e48-510e95efe7cd.jpg)

#### Do while
![dfd7dowhile](https://user-images.githubusercontent.com/113869976/197418452-b07ffd48-0c9f-4496-9347-777268d36e6a.jpg)

#### 7.3 Prueba de Escritorio
#### For
![image](https://user-images.githubusercontent.com/113869976/197418557-6af80db7-75f5-4672-a2b0-b5feeab9ce71.png)

#### While
![image](https://user-images.githubusercontent.com/113869976/197418567-025bdf21-0deb-4fdc-b92c-c6977791ccbe.png)

#### Do while
![image](https://user-images.githubusercontent.com/113869976/197418570-f335e459-49c7-4b4b-b558-dd8892263db2.png)

#### 7.4 Entradas
num=16,17,28,8,14,6,30,22,18,2,4
#### 7.5 Salidas
[0] 16  
[1] 28  
[2] 8  
[3] 14  
[4] 6  
[5] 30  
[6] 22  
[7] 18  
[8] 2  
[9] 4

#### 7.6 Código dart
#### For
import 'dart:io';  
import 'dart:async';  

void main() {  
  var array = [];  

  for (var i = 0; i <= 10; i++) {  
    int n = int.parse(stdin.readLineSync()!);  
    if (n % 2 == 0) {  
      array.add(n);  
      i = i - 1;  
    }  
  }  
  print(array);  
}  
#### While
import 'dart:io';  
import 'dart:async';  

void main() {  
  var array = [];  
  var c = 0;  

  while (c <= 10) {  
    int n = int.parse(stdin.readLineSync()!);  
    c = c + 1;  
    if (n % 2 == 0) {  
      array.add(n);  
      c = c - 1;  
    }  
  }  
  print(array);  
}  
#### Do while
import 'dart:io';  
import 'dart:async';  

void main() {  
  var array = [];  
  var c = 0;  
  do {  
    int n = int.parse(stdin.readLineSync()!);  

    if (n % 2 == 0) {  
      array.add(n);  
      c = c + 1;  
    }  
  } while (c <= 9);  
  print(array);  
}  

### Ejercicio 8. Obtenga el promedio de las calificaciones aprobatorias, la cantidad de alumnos aprobados y la cantidad de alumnos reprobados. 
### La calificación es entre 0 y 10 y el máximo de alumnos es de 15.

#### 8.1 Análisis
Promedio aprobatorias= PRA  
Alumnos aprobados= AP  
Alumnos reprobados= AR  
Calificación 0-10  
Máximo 15 alumnos  
Número de alumnos= NA  
1,5,10,2,7,8,9,9,10,3,4,8  
NA=12  
AP=10,7,8,9,9,10,8  
AP=7  
AR=1,5,2,3,4  
AR=5  
PRA=(10+7+8+9+9+10+8)/7  
PRA=8.71  

#### 8.2 Diagrama de Flujo de Datos
#### For
![dfd8for](https://user-images.githubusercontent.com/113869976/197427788-2dc94616-823a-4a2e-ab35-ed97ed453b37.jpg)

#### While
![dfd8while](https://user-images.githubusercontent.com/113869976/197427793-b867998d-2829-497c-84e9-6a37d270f3f9.jpg)

#### Do while
![dfd8dowhile](https://user-images.githubusercontent.com/113869976/197427779-824ff7a3-4282-4465-8f1f-7fc504834b9f.jpg)

#### 8.3 Prueba de Escritorio
#### For
![image](https://user-images.githubusercontent.com/113869976/197432996-55824fbb-7fbc-415f-a01b-cdb16f1c170b.png)

#### While
![image](https://user-images.githubusercontent.com/113869976/197432528-e6e12f1a-08d4-4531-8d26-3321a864cf40.png)

#### Do while
![image](https://user-images.githubusercontent.com/113869976/197432536-3e200546-e140-4955-9943-f96c34257e95.png)

#### 8.4 Entradas
NA=10  
CAL=8,10,5,6,7,2,4,10,10,5  
#### 8.5 Salidas
Reprobados: 4  
Aprobados: 6  
Promedio Aprobados: 8.5  

#### 8.6 Código dart
#### For
import 'dart:io';  
import 'dart:async';  

void main() {  
  double proma = 0;  
  var contr = 0;  
  double sumaa = 0;  
  double conta = 0;  
  double cal1 = 0;  
  double cal2 = 1;  

  for (var i = 1; i <= 15; i++) {  
    double c = double.parse(stdin.readLineSync()!);  
    if (c > 10) {  
      print('la calificacion no puede ser mayor a 10');  
      i = i - 1;  
    }  
    if (c < 0) {  
      print('la calificacion no puede ser menor a 0');  
      i = i - 1;  
    }  
    if (c < 6 && c > 0) {  
      contr = contr + 1;  
    }  
    if (c <= 10 && c >= 6) {  
      cal1 = c;  
      sumaa = sumaa + cal1;  
      conta++;  
    }  
    if (cal1 > cal2) {  
      cal2 = cal1;  
    }  
  }  
  proma = sumaa / conta;  
  print('el promedio de aprobados es $proma');  
  print('la calificacion mas alta es $cal2');  
  print('la cantidad de reprobados son $contr');  
}  
#### While
import 'dart:io';  
import 'dart:async';  

void main() {  
  double proma = 0;  
  var contr = 0;  
  double sumaa = 0;  
  double conta = 0;  
  double cal1 = 0;  
  double cal2 = 1;  
  var cont = 0;  
 
  while (cont <= 14) {  
    double c = double.parse(stdin.readLineSync()!);  
    cont = cont + 1;  
    if (c > 10) {  
      print('la calificacion no puede ser mayor a 10');  
      cont = cont - 1;  
    }  
    if (c < 0) {  
      print('la calificacion no puede ser menor a 0');  
      cont = cont - 1;  
    }  
    if (c < 6 && c > 0) {  
      contr = contr + 1;  
    }  
    if (c <= 10 && c >= 6) {  
      cal1 = c;  
      sumaa = sumaa + cal1;  
      conta++;  
    }  
    if (cal1 > cal2) {  
      cal2 = cal1;  
    }  
  }  

  proma = sumaa / conta;  
  print('el promedio de aprobados es $proma');  
  print('la calificacion mas alta es $cal2');  
  print('la cantidad de reprobados son $contr');  
}  
#### Do while
import 'dart:io';  
import 'dart:async';  
 
void main() { 
  double proma = 0;  
  var contr = 0;  
  double sumaa = 0;  
  double conta = 0;  
  double cal1 = 0;  
  double cal2 = 1;  
  var cont = 0;  
  do {  
    double c = double.parse(stdin.readLineSync()!);  
    cont = cont + 1;  
    if (c > 10) {  
      print('la calificacion no puede ser mayor a 10');  
      cont = cont - 1;  
    }  
    if (c < 0) {  
      print('la calificacion no puede ser menor a 0');  
      cont = cont - 1;  
    }  
    if (c < 6 && c > 0) {  
      contr = contr + 1;  
    }  
    if (c <= 10 && c >= 6) {  
      cal1 = c;  
      sumaa = sumaa + cal1;  
      conta++;  
    }  
    if (cal1 > cal2) {  
      cal2 = cal1;  
    }  
  } while (cont <= 14);  

  proma = sumaa / conta;  
  print('el promedio de aprobados es $proma');  
  print('la calificacion mas alta es $cal2');  
  print('la cantidad de reprobados son $contr');  
}
### Ejercicio 9. Obtenga el promedio de las calificaciones aprobatorias, la cantidad de alumnos aprobados y la cantidad de alumnos reprobados. La calificación es entre 0 y 10 y el máximo de alumnos es de 15 e indique la calificación más alta

#### 9.1 Análisis
Promedio aprobatorias= PRA  
Alumnos aprobados= AP  
Alumnos reprobados= AR  
Calificación más alta= CA  
Calificación 0-10  
Máximo 15 alumnos   
Número de alumnos= NA  
1,5,10,2,7,8,9,9,10,3,4,8  
NA=12  
AP=10,7,8,9,9,10,8  
AP=7  
AR=1,5,2,3,4  
AR=5  
PRA=(10+7+8+9+9+10+8)/7  
PRA=8.71  
CA=10  

#### 9.2 Diagrama de Flujo de Datos
#### For
![dfd9for](https://user-images.githubusercontent.com/113869976/197933392-bae08253-948b-4109-9cc7-4337810066eb.jpg)

#### While
![dfd9while](https://user-images.githubusercontent.com/113869976/197933411-991f5609-2464-44cf-bffa-176bf7ac1cc7.jpg)

#### Do while
![dfd9dowhile](https://user-images.githubusercontent.com/113869976/197933424-d47e66c7-da18-4afc-8678-987dfc9d4757.jpg)

#### 9.3 Prueba de Escritorio
#### For
![image](https://user-images.githubusercontent.com/113869976/197933328-0a85f7f1-7138-45bf-a271-d6d2754f6034.png)

#### While
![image](https://user-images.githubusercontent.com/113869976/197933336-c70bb930-3ae4-4c41-822d-af7ee85a0cfa.png)

#### Do while
![image](https://user-images.githubusercontent.com/113869976/197933348-becfa12b-7657-4270-80e1-4f1fc4a75542.png)

#### 9.4 Entradas
NA=8  
CAL=8,9,10,10,5,2,2,5  
#### 9.5 Salidas
Reprobados: 4  
Aprobados: 4  
Promedio Aprobados: 9.25  
La calificación mayor es: 10

#### 9.6 Código dart
#### For
import 'dart:io';  
import 'dart:async';  

void main() {  
  double proma = 0;  
  var contr = 0;  
  double sumaa = 0;  
  double conta = 0;  
  double cal1 = 0;  
  double cal2 = 1;  

  for (var i = 1; i <= 15; i++) {  
    double c = double.parse(stdin.readLineSync()!);  
    if (c > 10) {  
      print('la calificacion no puede ser mayor a 10');  
      i = i - 1;  
    }  
    if (c < 0) {  
      print('la calificacion no puede ser menor a 0');  
      i = i - 1;  
    }  
    if (c < 6 && c > 0) {  
      contr = contr + 1;  
    }  
    if (c <= 10 && c >= 6) {  
      cal1 = c;  
      sumaa = sumaa + cal1;  
      conta++;  
    }  
    if (cal1 > cal2) {  
      cal2 = cal1;  
    }  
  }  
  proma = sumaa / conta;  
  print('el promedio de aprobados es $proma');  
  print('la calificacion mas alta es $cal2');  
  print('la cantidad de reprobados son $contr');  
}  
#### While
import 'dart:io';  
import 'dart:async';  

void main() {  
  double proma = 0;  
  var contr = 0;  
  double sumaa = 0;  
  double conta = 0;  
  double cal1 = 0;  
  double cal2 = 1;  
  var cont = 0;  

  while (cont <= 14) {  
    double c = double.parse(stdin.readLineSync()!);  
    cont = cont + 1;  
    if (c > 10) {  
      print('la calificacion no puede ser mayor a 10');  
      cont = cont - 1;  
    }  
    if (c < 0) {  
      print('la calificacion no puede ser menor a 0');  
      cont = cont - 1;  
    }  
    if (c < 6 && c > 0) {  
      contr = contr + 1;  
    }  
    if (c <= 10 && c >= 6) {  
      cal1 = c;  
      sumaa = sumaa + cal1;  
      conta++;  
    }  
    if (cal1 > cal2) {  
      cal2 = cal1;  
    }  
  }  

  proma = sumaa / conta;  
  print('el promedio de aprobados es $proma');  
  print('la calificacion mas alta es $cal2');  
  print('la cantidad de reprobados son $contr');  
}  
#### Do while
import 'dart:io';  
import 'dart:async';  

void main() {  
  double proma = 0;  
  var contr = 0;  
  double sumaa = 0;  
  double conta = 0;  
  double cal1 = 0;  
  double cal2 = 1;  
  var cont = 0;  
  do {  
    double c = double.parse(stdin.readLineSync()!);  
    cont = cont + 1;  
    if (c > 10) {  
      print('la calificacion no puede ser mayor a 10');  
      cont = cont - 1;  
    }  
    if (c < 0) {  
      print('la calificacion no puede ser menor a 0');  
      cont = cont - 1;  
    }  
    if (c < 6 && c > 0) {  
      contr = contr + 1;  
    }  
    if (c <= 10 && c >= 6) {  
      cal1 = c;  
      sumaa = sumaa + cal1;  
      conta++;  
    }  
    if (cal1 > cal2) {  
      cal2 = cal1;  
    }  
  } while (cont <= 14);  

  proma = sumaa / conta;  
  print('el promedio de aprobados es $proma');  
  print('la calificacion mas alta es $cal2');  
  print('la cantidad de reprobados son $contr');  
}
### Ejercicio 10. Capturen n números en el rango de [li,ls] donde:
### li=límite inferior ls=límite superior y li < ls y li > ls
### Obtenga:
### -Cantidad de números pares y su promedio
### -Cantidad de números impares y su promedio
### -¿Qué promedio es mayor?

#### 10.1 Análisis
n números= n  
li < ls y li > ls  
Pares y promedio= NP y PP  
Impares y promedio= NI y PI  
Promedio mayor= PM  
n=10  
li=6  
ls=32  
2,6,8,10,15,22,32,-3,10,9,26,29  
6,8,10,15,22,32,10,9,26,29  
PARES  
6,8,10,22,32,10,25
NP=7  
PP=(6+8+10+22+32+10+25)/7  
PP=16.1  
IMPARES  
15,9,29  
NI=3  
PI=(15+9+29)/3  
PI=17.6  
PROMEDIO MAYOR  
PM=17.6  

#### 10.2 Diagrama de Flujo de Datos
#### For
![dfd10for](https://user-images.githubusercontent.com/113869976/197431307-f0be5aa7-0c78-45cd-a560-4c2c37f36125.jpg)

#### While
![dfd10while](https://user-images.githubusercontent.com/113869976/197431312-dad70302-225a-4ed5-8a2e-a2d7e95a8574.jpg)

#### Do while
![dfd10dowhile](https://user-images.githubusercontent.com/113869976/197431302-c5f153d7-82dc-4944-806c-050599aa79cb.jpg)

#### 10.3 Prueba de Escritorio
#### For
![image](https://user-images.githubusercontent.com/113869976/197431273-f4500afa-d658-448b-b633-e2d58d9d9013.png)

#### While
![image](https://user-images.githubusercontent.com/113869976/197431275-9b43bcd3-138c-4ad7-9697-1559596c4a62.png)

#### Do while
![image](https://user-images.githubusercontent.com/113869976/197431277-c8064e50-871d-468a-ba07-bf2c64baa13a.png)

#### 10.4 Entradas
li=5  
ls=15  
cant=6  
num=5,,7,10,15,12,9  
#### 10.5 Salidas
Pares: 2  
Promedio Pares: 11  
Impares: 4  
Promedio Impares: 9  
Los pares tienen mayor promedio  

#### 10.6 Código dart
#### For
import 'dart:io';  

void main() {  
  var num = []; 
  var mayor = 0;  
  var menor = 0;  
  for (var i = 0; i <= 9; i++) {  
    int n = int.parse(stdin.readLineSync()!);  
    if (n > 0) {  
      num.add(n);  
      if (n < 0) {  
        print('el numero debe ser positivo');  
        i = i - 1;  
      }  
    }  
  }  
  print(num);  
  for (var i = 0; i <= 9; i++) {  
    if (mayor < num[i]) {  
      mayor = num[i];  
    }  
  }  
  print('el numero mayor es $mayor');  
  menor = mayor;  
  for (var i = 0; i <= 9; i++) {  
    if (menor > num[i]) {  
      menor = num[i];
    }  
  }  
  print('el numero menor es $menor');  
}  
#### While
import 'dart:io';  

void main() {  
  double sumap = 0;  
  double sumai = 0;  
  var contp = 0;  
  var conti = 0;  
  double promp = 0;  
  double promi = 0;  
  print('Introduce el limite inferior, mayor a 0');  
  var li = int.parse(stdin.readLineSync()!);  
  if (li < 0) {  
    print('tu limite inferior debe ser mayor a 0');  
  }  
  if (li > 0) {  
    print('Ahora introduce un limite superior');  
    var ls = int.parse(stdin.readLineSync()!);  
    if (ls < li) {  
      print('tu limite superior debe ser mayor a tu limite inferior');  
    }  
    var cont = li;  
    do {  
      if (cont <= ls) {  
        sumai = sumai + cont;  
        conti = conti + 1;  
      }  
      if (cont % 2 == 0) {  
        sumap = sumap + cont;  
        contp = contp + 1;  
        sumai = sumai - cont;  
        conti = conti - 1;  
      }  
      cont = cont + 1;  
    } while (cont <= ls);  

    promi = sumai / conti;  
    print('los impares son $conti y su promedio es $promi');  
    promp = sumap / contp;  
    print('los pares son $contp y su promedio es $promp');  
    if (promp < promi) {  
      print('$promi es mayor');  
    }  
    if (promp > promi) {  
      print('el promedio $promp es mayor');  
    }  
  }  
}  
#### Do while
import 'dart:io';  

void main() {  
  double sumap = 0;  
  double sumai = 0;  
  var contp = 0;  
  var conti = 0;  
  double promp = 0;  
  double promi = 0;  
  print('Introduce el limite inferior, mayor a 0');  
  var li = int.parse(stdin.readLineSync()!);  
  if (li < 0) {  
    print('tu limite inferior debe ser mayor a 0');  
  }  
  if (li > 0) {  
    print('Ahora introduce un limite superior');  
    var ls = int.parse(stdin.readLineSync()!);  
    if (ls < li) {  
      print('tu limite superior debe ser mayor a tu limite inferior');  
    }  
    var cont = li;  
    do {  
      if (cont <= ls) {  
        sumai = sumai + cont;  
        conti = conti + 1;  
      }  
      if (cont % 2 == 0) {  
        sumap = sumap + cont;  
        contp = contp + 1;  
        sumai = sumai - cont;  
        conti = conti - 1;  
      }  
      cont = cont + 1;  
    } while (cont <= ls);  

    promi = sumai / conti;  
    print('los impares son $conti y su promedio es $promi');  
    promp = sumap / contp;  
    print('los pares son $contp y su promedio es $promp');  
    if (promp < promi) {  
      print('$promi es mayor');  
    }  
    if (promp > promi) {  
      print('el promedio $promp es mayor');  
    }  
  }  
}  

### Ejercicio 11. Obtener la frecuencia de n. Calificaciones entre [1,10]
### -Indique la cantidad de reprobados
### -Indique la cantidad de aprobados
### -Promedio de aprobados
### -Promedio general

#### 11.1 Análisis
Frecuencia n  
Número alumnos= NA  
Reprobados= R  
Aprobados= A  
Promedio aprobados= PA  
Promedio general= PG  
NA=12  
5,8,10,2,4,6,7,6,1,2,3,4   
REPROBADOS  
5,2,4,1,2,3,4  
R=7  
APROBADOS  
6,10,6,7,6  
A=5  
PROMEDIO APROBADOS  
PA=(6+10+6+7+6)/5  
PA=7  
PROMEDIO GENERAL  
PG=(5+8+10+2+4+6+7+6+1+2+3+4)/12  
PG=4.8  

#### 11.2 Diagrama de Flujo de Datos
#### For
![dfd11for](https://user-images.githubusercontent.com/113869976/197439155-008af61f-b3ed-4a26-a4ff-c7ea04ff6835.jpg)

#### While
![dfd11while](https://user-images.githubusercontent.com/113869976/197439162-c357a8d5-50eb-4822-b3b7-92d9fc3fd9ee.jpg)

#### Do while
![dfd11dowhile](https://user-images.githubusercontent.com/113869976/197439150-a4bb2a01-0706-4b3f-8aee-e659c650aa1a.jpg)

#### 11.3 Prueba de Escritorio
#### For
![image](https://user-images.githubusercontent.com/113869976/197439113-927dce9c-3be5-4542-a744-a22a6815d558.png)

#### While
![image](https://user-images.githubusercontent.com/113869976/197933487-346e2c69-94ed-465a-b21a-f5f883f8b3f8.png)

#### Do while
![image](https://user-images.githubusercontent.com/113869976/197933497-9790734f-31aa-4292-93c5-355186be51b1.png)

#### 11.4 Entradas
NA=8
CAL=10,10,4,6,3,8,9,10
#### 11.5 Salidas
Reprobados: 2  
Aprobados: 6  
Promedio de aprobados: 8.83333333  
Promedio General: 7.5  
La frecuencia es 10 y se repite 3 veces  

#### 11.6 Código dart
#### For
import 'dart:io';  

void main() {  
  var contr = 0;  
  var conta = 0;  
  var contt = 0;  
  double sumag = 0;  
  double sumaa = 0;  
  double promg = 0;  
  double porma = 0;  
  var C0 = 0;  
  var C1 = 0;  
  var C2 = 0;  
  var C3 = 0;  
  var C4 = 0;  
  var C5 = 0;  
  var C6 = 0;  
  var C7 = 0;  
  var C8 = 0;  
  var C9 = 0;  
  var C10 = 0;  

  print('inserta las 10 calificaciones entera positiva, entre 1 y 10');  
  for (var i = 0; i <= 9; i++) {  
    int c = int.parse(stdin.readLineSync()!);  
  
    if (c > 11) {  
      print('La calificacion debe ser menor a 10');  
      i = i--;  
    } 
    if (c < 0) {  
      print('la calificacion debe ser mayor a 0');  
      i = i--;  
    }  
    if (c == 0) {  
      C0 = C0 + 1;  
    }  
    if (c == 1) {  
      C1 = C1 + 1;  
    }  
    if (c == 2) {  
      C2 = C2 + 1;  
    }  
    if (c == 3) {  
      C3 = C3 + 1;  
    }  
    if (c == 4) {  
      C4 = C4 + 1;  
    }  
    if (c == 5) {  
      C5 = C5 + 1;  
    }  
    if (c == 6) {  
      C6 = C6 + 1;  
    }  
    if (c == 7) {  
      C7 = C7 + 1;  
    }  
    if (c == 8) {  
      C8 = C8 + 1;  
    }  
    if (c == 9) {  
      C9 = C9 + 1;  
    }  
    if (c == 10) {  
      C10 = C10 + 1;  
    }  
    if (c < 11 && c >= 0) { 
      if (c >= 6) {  
        conta = conta + 1;  
        sumaa = sumaa + c;  
      }  
      if (c < 6) {  
        contr = contr + 1;  
      }  
      sumag = sumag + c;  
    }  
  }  
  porma = sumaa / conta;  
  contt = conta + contr;  
  promg = sumag / contt;  

  print('La frecuencia de 0 es $C0');  
  print('La frecuencia de 1 es $C1');  
  print('La frecuencia de 2 es $C2');  
  print('La frecuencia de 3 es $C3');  
  print('La frecuencia de 4 es $C4');  
  print('La frecuencia de 5 es $C5');  
  print('La frecuencia de 6 es $C6');   
  print('La frecuencia de 7 es $C7');  
  print('La frecuencia de 8 es $C8');  
  print('La frecuencia de 9 es $C9');  
  print('La frecuencia de 10 es $C10');  
  print('Cantidad de reprobados $contr');  
  print('cantidad de aprovaodos $conta');  
  print('promedio general $promg');  
  print('promedio aprobados $porma');  
}  

### Ejercicio 12. Registrar cuántas veces se repite cada calificación [1,10], en un grupo de n alumnos

#### 12.1 Análisis
Número de alumnos= NA
NA=15
[0] 1  
[1] 3  
[2] 0  
[3] 0  
[4] 0  
[5] 0  
[6] 1  
[7] 1  
[8] 5  
[9] 2  
[10] 2   

#### 12.2 Diagrama de Flujo de Datos
#### For
![dfd12for](https://user-images.githubusercontent.com/113869976/197454963-ee3c170a-aa56-4d1d-9761-c4df1f0b3fcb.jpg)

#### While
![dfd12while](https://user-images.githubusercontent.com/113869976/197454970-af427064-aa4b-44d6-9609-d563e60857a3.jpg)

#### Do while
![dfd12dowhile](https://user-images.githubusercontent.com/113869976/197454954-bff523a5-cbe6-4415-ad7c-a77da0f79162.jpg)

#### 12.3 Prueba de Escritorio
#### For
![image](https://user-images.githubusercontent.com/113869976/197454903-70e437a1-9a4c-44ff-9abe-5536a9332dff.png)

#### While
![image](https://user-images.githubusercontent.com/113869976/197933521-d9dbac12-977b-426e-a613-b2208d0fc64a.png)

#### Do while
![image](https://user-images.githubusercontent.com/113869976/197933528-59210ad8-5e99-4c7e-8ae8-094575ea4dc8.png)

#### 12.4 Entradas
num=11
C=8,7,5,10,9,4,5,0,9,6,7
#### 12.5 Salidas
[0] 1  
[1] 0  
[2] 0  
[3] 0  
[4] 1  
[5] 2  
[6] 1  
[7] 2  
[8] 1  
[9] 2  
[10] 1  

### Ejercicio 13. Capturar 2 números y decir cuál es el mayor

#### 13.1 Análisis
n1=15  
n2=19  
n1>n2  
n2=19 es mayor  

#### 13.2 Diagrama de Flujo de Datos
![dfd13](https://user-images.githubusercontent.com/113869976/197419665-8655bfd7-9487-47a1-b36b-3ebbc5cd2848.jpg)

#### 13.3 Prueba de Escritorio
![image](https://user-images.githubusercontent.com/113869976/197439827-876f6afd-24e7-4e5c-8907-111671804d20.png)

#### 13.4 Entradas
1. n1=10 n2=5  
2. n1=2 n2=25  
3. n1=15 n2=6  
4. n1=8 n2=12  
5. n1=19 n2=18  

#### 13.5 Salidas
1. 10 es mayor
2. 25 es mayor
3. 15 es mayor
4. 12 es mayor
5. 19 es mayor

### Ejercicio 14. Elabora un dfd que capture 10 número enteros positivos y los almacene en un vector, sacar cuál es el mayor y cuál es el menor

#### 14.1 Análisis
[0] 15  
[1] 62  
[2] 18  
[3] 25  
[4] 6  
[5] 31  
[6] 32  
[7] 8  
[8] 2  
[9] 4  
Mayor= 62  
Menor= 2  

#### 14.2 Diagrama de Flujo de Datos
#### For
![dfd14for](https://user-images.githubusercontent.com/113869976/197460044-71416ad8-99ae-404a-8833-60baf3f9cbcd.jpg)

#### While
![dfd14while](https://user-images.githubusercontent.com/113869976/197933651-b4c8f261-3248-4bbf-81c5-73cda358ff84.jpg)

#### Do while
![dfd14dowhile](https://user-images.githubusercontent.com/113869976/197933629-fc82458e-ff23-4f51-a873-6c2bc740ec4e.jpg)

#### 14.3 Prueba de Escritorio
#### For
![image](https://user-images.githubusercontent.com/113869976/197460071-4c80ade2-2ace-4723-99ba-7e6447b98f39.png)

#### While
![image](https://user-images.githubusercontent.com/113869976/197933597-becd588c-adc8-490f-ad46-d8b0c340a457.png)

#### Do while
![image](https://user-images.githubusercontent.com/113869976/197933604-7e11de99-9d69-4e82-93a6-4e9861694c5a.png)

#### 14.4 Entradas
num=8,25,41,10,36,5,78,109,2,15
#### 14.5 Salidas
[0] 8  
[1] 25  
[2] 41  
[3] 10  
[4] 36  
[5] 5  
[6] 78  
[7] 109  
[8] 2  
[9] 15  
El número mayor es: 109  
El número menor es: 2  

### Ejercicio 15. Obtenga la distancia mayor entre 2 números consecutivos en una lista de 10 números

#### 15.1 Análisis
NÚMEROS  
[0] 15 
[1] 26  
[2] 18  
[3] 25  
[4] 6  
[5] 31  
[6] 32  
[7] 8  
[8] 2  
[9] 4  
DISTANCIAS  
[0] 15-26=-11*-1=11  
[1] 26-18=8  
[2] 18-25=-7*-1=7  
[3] 25-6=19  
[4] 6-31=-25*-1=25  
[5] 31-32=-1*-1=1  
[6] 32-8=24  
[7] 8-2=6  
[8] 2-4=-2*-1=2  
Distancia Mayor= DM  
DM=25  

#### 15.2 Diagrama de Flujo de Datos
#### For
![dfd15for](https://user-images.githubusercontent.com/113869976/197938681-d1240f19-dcfe-4c8d-b755-5587a31f36a4.jpg)

#### While
![dfd15while](https://user-images.githubusercontent.com/113869976/197938697-8b3fce8b-5445-4663-81ac-cbab7f8dc359.jpg)

#### Do while
![dfd15dowhile](https://user-images.githubusercontent.com/113869976/197938770-ed973355-5915-42c0-88be-5333b4e2153e.jpg)

#### 15.3 Prueba de Escritorio
#### For
![image](https://user-images.githubusercontent.com/113869976/197938787-85d2caf9-10a6-4904-8970-f06262a3b6cf.png)

#### While
![image](https://user-images.githubusercontent.com/113869976/197938794-5fdc11db-8343-477e-80ee-4dd25ae088df.png)

#### Do while
![image](https://user-images.githubusercontent.com/113869976/197938810-b730797c-ea9d-410a-8180-61c1c498e96f.png)

#### 15.4 Entradas
num=10,5,36,11,45,20,18,47,29,15
#### 15.5 Salidas
La distancia mayor es: 34

#### 15.6 Código dart
#### For
import 'dart:io';  

void main() {   
  var num = [];  
  var d = [];  
  var dis = 0;  
  var mayor = 0;  

  for (var i = 0; i <= 9; i++) {  
    int n = int.parse(stdin.readLineSync()!);  
    if (n < 0) {  
      print('el numero no debe ser negativo');  
      i = i--;  
    }  
    if (n > 0) {  
      num.add(n);  
    }  
  }  
  print('los numeros son $num');  
  for (var i = 0; i < 9; i++) {  
    dis = num[i] - num[i + 1];  
    d.add(i);  
    if (dis < 0) {  
      d[i] = dis * -1;  
    }  
    if (dis > 0) {  
      d[i] = dis;  
    }  
  }  
  print('las distancias son $d');  
  for (var i = 0; i < 9; i++) {  
    if (mayor < d[i]) {  
      mayor = d[i];  
    }  
  }  
  print('la distacia mayor es $mayor');  
}  

### Ejercicio 16. Almacene en un vector el resultado de una tabla de multiplicar (10 números)

#### 16.1 Análisis
Tabla del 9  
[0]  
[1] 9  
[2] 18  
[3] 27  
[4] 36  
[5] 45  
[6] 54  
[7] 63  
[8] 72  
[9] 81  
[10] 90  

#### 16.2 Diagrama de Flujo de Datos
#### For
![dfd16for](https://user-images.githubusercontent.com/113869976/197943509-9a8eb0e3-c6b9-45aa-8b75-4e4c235cba46.jpg)

#### While
![dfd16while](https://user-images.githubusercontent.com/113869976/197943520-5c77e64f-0e78-4bb2-b9fb-64138adba022.jpg)

#### Do while
![dfd16dowhile](https://user-images.githubusercontent.com/113869976/197943502-98f10cc7-7b0e-4da3-8b12-546e58a447f8.jpg)

#### 16.3 Prueba de Escritorio
#### For
![image](https://user-images.githubusercontent.com/113869976/197943550-64fa6d82-c1e7-4c33-bb57-39f2d7967132.png)

#### While
![image](https://user-images.githubusercontent.com/113869976/197943564-7e8fc40a-a67e-4787-bf1d-df8cbae16e96.png)

#### Do while
![image](https://user-images.githubusercontent.com/113869976/197943571-a71eb0d1-bdfe-4497-8069-2fadaa68d52b.png)

#### 16.4 Entradas
num=16
#### 16.5 Salidas
[0]  
[1]16  
[2]32  
[3]48  
[4]64  
[5]80  
[6]96  
[7]112  
[8]128  
[9]144  
[10]160  

#### 16.6 Código dart
#### For
import 'dart:io';  

void main() {  
  var array = [];  
  int n = int.parse(stdin.readLineSync()!);  
  for (var i = 0; i < 11; i++) {  
    array.add(i);  
    array[i] = n * i;  
  }  
  print('$array');  
}  

### Ejercicio 17. Escriba un dfd que escriba el siguiente dibujo
![image](https://user-images.githubusercontent.com/113869976/197947566-61a2a0e3-28dd-4d76-8dbd-8e99ae102f1c.png)

#### 17.1 Análisis
1  
12  
123  
1234  
12345
#### 17.2 Diagrama de Flujo de Datos
#### For
![dfd17for](https://user-images.githubusercontent.com/113869976/197947833-32958fb8-a2c0-4d4b-b48c-44c124de3bb7.jpg)

#### 17.3 Prueba de Escritorio
#### For
![image](https://user-images.githubusercontent.com/113869976/197947727-2e640706-ca6f-44cd-a8c9-7bfb770413c4.png)

#### 17.4 Entradas
NA
#### 17.5 Salidas
1  
1 2  
1 2 3  
1 2 3 4  
1 2 3 4 5  

#### .6 Código dart
#### For
import 'dart:io';  

void main() {  
  var n = 5;  
  for (var i = 0; i < 5; i++) {  
    for (var j = 0; j <= i; j++) {  
      stdout.write('*');  
    }  
    print('');  
  }  
}  
