

```@Instituto Tecnológico de Tijuana.
@Departamento de Sistemas y Computación.
@Ingeniería en Sistemas Computacionales.
@Autor: López Partida Salvador Eli.
Fecha de entrega: 7 de Octubre del 2022.


  void setup() {
  // initialize digital pin LED_BUILTIN as an output.
  pinMode(LED_BUILTIN, OUTPUT);      //inicializa el pin digital del Led como un dato de salida. 
}

// crea el búcle de la función
void loop() {
  Serial.print(F("prendido \n"));   // manda el mensaje de perndido para cuando se prende el led
  digitalWrite(LED_BUILTIN, HIGH);  // manda la señal para que se prende el led
  delay(1000);                      // tiempo de espera de mil milisegundos para prender
  Serial.print(F("apagado \n"));    // manda el mensaje de apagado para cuando se apaga el led
  digitalWrite(LED_BUILTIN, LOW);   // manda la señal para que se apague el led
  delay(1000);                      // tiempo de espera de mil milisegundos para apagarse
   
}```
