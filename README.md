int i;
int speakerPin = 8;
int numTones = 10;
int tones[] = {261,277,294,311,330,349,370,392,415,440};
void setup(){

for (int i=0; i<9; i++);{


  digitalwrite(speakerPins[i]; HIGH);
  delay(500);
  digitalwrite(speakerPins[i]; LOW);
delay(500);
}

}

void loop() {
  // put your main code here, to run repeatedly:
