void setup() {
Serial.begin(9600);
}
void loop() {
 if(Serial.available()>0) //verifico si hay datos disponibles en el puerto
 {    
String lectura = Serial.readString(); //leo lo que haya en el puerto  lo almaceno en la variable 'lectura'
if(lectura == "mi_contraseña")
  {
  Serial.println("Contraseña correcta");
  delay(1000);
  }
else{
  Serial.println("Contraseña incorrecta");
  delay(1000);
     }
 }
}
