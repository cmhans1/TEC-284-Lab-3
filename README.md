# TEC-284-Lab-3
This code will relay information for debugging.
void setup() {
  // put your setup code here, to run once:
pinMode(A6, INPUT);
int lightLevel = analogRead(A6);
Serial.begin(9600);
Serial.println(lightLevel);

void setup() {
  // put your setup code here, to run once:
  
pinMode(A6, INPUT);
int lightLevel = analogRead(A6);
Serial.begin(9600);
Serial.println(lightLevel);

if (lightLevel > 100)
{
  digitalWrite(4, LOW);
  delay (100);
}
if (lightLevel < 100)
{
  digitalWrite(4, HIGH);
}

}

void loop() {
  // put your main code here, to run repeatedly:

}

void loop() {
  // put your main code here, to run repeatedly:

}
