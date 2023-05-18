(#10 day internship
>day-1
- github
- acc making in github
- made .md file 
> uese of symbol
1. using # for big size
2. ling
3. linking link
4. code
```
f=int(input("enter a number")
h=int("input("enter a number")
sum=f+h
print("sum=",sum)
```
[lukosevv/vvl](https://github.com/lukosevv/vvl)


#DAY 2




![alt n0 loding](https://github.com/dakshajith/daksh/blob/main/circuit.png)


![alt noloding](circuit.png)




#DAY 3




!thinker this](https://www.tinkercad.com/things/8uIxXHKhopy-amazing-stantia/editel?tenant=circuits)

[thinker this](https://www.tinkercad.com/things/adxwkp20WCi-smooth-elzing/editel?tenant=circuits)

[thinker this](https://www.tinkercad.com/things/bNyTkXKGWgF-grand-bigery-lappi/editel?tenant=circuits)

CODE


// C++ code
//
void setup()
{
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop()
{
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}

DAY 5

ASSIGNMENT 1


7 segments 


https://www.tinkercad.com/things/hARFVBEgiQh-copy-of-7-segament-display-using-arduino-board/editel?tenant=circuits

CODE

// C++ code
//
void setup()
{
  pinMode(13, OUTPUT);
  pinMode(12,OUTPUT);
  pinMode(11,OUTPUT);
  pinMode(10,OUTPUT);
  pinMode(9,OUTPUT);
  pinMode(8,OUTPUT);
  pinMode(7,OUTPUT);
}

void loop()
{
  digitalWrite(13, LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,HIGH);
  delay(1000); // Wait for 1000 millisecond(s
  digitalWrite(11,LOW);
  digitalWrite(12,LOW);
  digitalWrite(10,HIGH);
  digitalWrite(13,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  digitalWrite(7,HIGH);
  delay(1000);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(7,LOW);
  digitalWrite(9,LOW);
  digitalWrite(10,LOW);
  digitalWrite(8,HIGH);
  digitalWrite(11,HIGH);
  delay(1000);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(7,LOW);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  delay(1000);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(13,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(10,HIGH);
  delay(1000);
  digitalWrite(13,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,HIGH);
  digitalWrite(12,HIGH);
  delay(1000);
  digitalWrite(13,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(12,HIGH);
  delay(1000);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  digitalWrite(7,HIGH);
  delay(1000);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  delay(1000);
  digitalWrite(10,HIGH);
  digitalWrite(9,HIGH);
  delay(1000);
  
  delay(1000); // Wait for 1000 millisecond(s)
}


program 1


delay(1000);//waight for mellion seacond(s)

https://www.tinkercad.com/things/gcpjhDdJdec-grand-maimu-fyyran/editel

code 

const int potpin = A0;
  
  void setup() {
    Serial.begin(9600);
}

void loop() {
  int potValue = analogRead(potpin);
  Serial.println(potValue);
  delay(100);
}

DAY 8

https://www.tinkercad.com/things/hARFVBEgiQh-copy-of-7-segament-display-using-arduino-board/editel

CODE

const int potpin = A0;
  
  void setup() 
  {
    Serial.begin(9600);


  pinMode(13, OUTPUT);//a
  pinMode(12,OUTPUT);//b
  pinMode(11,OUTPUT);//c
  pinMode(10,OUTPUT);//d
  pinMode(9,OUTPUT);//e
  pinMode(8,OUTPUT);//f
  pinMode(7,OUTPUT);//g


  }

 
void loop()
{
  int potValue = analogRead(potpin);
  Serial.println(potValue);
  delay(0.100);digitalWrite(13, LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,HIGH);
  delay(0.100); // Wait for 0-2004 millisecond(s
  digitalWrite(11,LOW);
  digitalWrite(12,LOW);
  digitalWrite(10,HIGH);
  digitalWrite(13,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  digitalWrite(7,HIGH);
  delay(0.100);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(7,LOW);
  digitalWrite(9,LOW);
  digitalWrite(10,LOW);
  digitalWrite(8,HIGH);
  digitalWrite(11,HIGH);
  delay(0.100);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(7,LOW);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  delay(0.100);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(13,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(10,HIGH);
  delay(0.100);
  digitalWrite(13,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,HIGH);
  digitalWrite(12,HIGH);
  delay(0.100);
  digitalWrite(13,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(12,HIGH);
  delay(0.100);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  digitalWrite(7,HIGH);
  delay(0.100);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  delay(0.100);
  digitalWrite(10,HIGH);
  digitalWrite(9,HIGH);
  delay(0.100);
  
  delay(0.100); // Wait for 0-2004 millisecond(s)
}
