//arduino-proximity-code
//arduino programing code for proximity sensor reading 


#define inSensor 7
#define outSensor 6

int inStatus;
int outStatus;

int i;
int o;
#define relay 12


void setup()
{
  pinMode(inSensor, INPUT);
  pinMode(outSensor, INPUT);
  pinMode(relay, OUTPUT);
  digitalWrite(relay, HIGH);
  Serial.begin(9600);
  delay(500);
}
 
void loop()
{
  i =  digitalRead(inSensor);
  outStatus = digitalRead(outSensor);
i == LOW;

for (i==0)
{ 
  
  Serial.println(i);
}
}
