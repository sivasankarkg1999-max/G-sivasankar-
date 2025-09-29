# G-sivasankar-
Led blink program 
void setup() {
  pinMode(13, OUTPUT);   // Set pin 13 as output
}

void loop() {
  digitalWrite(13, HIGH); // LED ON
  delay(500);             // wait 500ms
  digitalWrite(13, LOW);  // LED OFF
  delay(500);             // wait 500ms
}
