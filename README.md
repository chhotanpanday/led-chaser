# led-chaser

led-chaser

AIM:-To make a led chaser using arduino.

EQUIPMENTS USED:-Breadboard,LED bulbs,connecting wires,arduino board,resistor,etc.

Code:- int pinsCount=10;

int pins[] = {2,3,4,5,6,7,8,9,10,11};

void setup() {

for (int i=0; i<pinsCount; i=i+1)

pinMode(pins[i], OUTPUT);            

}

}

void loop() {

for (int i=0; i<pinsCount; i=i+1)

{ // chasing right

digitalWrite(pins[i], HIGH);         



delay(100);                         


digitalWrite(pins[i], LOW);          

}

for (int i=pinsCount-1; i>0; i=i-1){

digitalWrite(pins[i], HIGH);         



delay(100);                          


digitalWrite(pins[i], LOW);          

}

}

LEARNING OUTCOMES:-1.learned how to make a led chaser using arduino and breadboard.

PRECAUTION/ERROR:-1.Connection should be correct . 2.Bulbs should be working.

