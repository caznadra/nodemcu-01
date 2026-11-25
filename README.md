# Blinkprogram med hjälp av Arduino IDE
## ESP8266

![Bild på ESP8266](https://www.electrokit.com/resource/u2Wd/usd/GOkVovhlCi5/quick/73/4a/42e4_41017574.jpg)

## Mikrokontroller
Baskomponenter i en mikroprocessor

- CPU - Central processing Unit (Flyttar resultat till minnet)

- Minne

- Interface - Punkten där systemen möts, interaktion uppstår här

## Basfunktioner i Arduino
 
- void setup = Körs alltid först, och en gång

- void loop = Körs om och om igen, i en loop. Ex. läser av en temperatur

```
void setup() {

}

void loop() {
               
}
```

## Portinitiering

![Karta över kopplingar](https://acebott.com/wp-content/uploads/2025/03/ESP8266-2.webp)

Kopplingar i setup'en

```
void setup() {
  pinMode(D5, OUTPUT);
}
```

Kopplingar i loop'en

```
void loop() {
  digitalWrite(D5, HIGH);
  delay(50);                     
  digitalWrite(D5, LOW);
  delay(50);                     
}
```

### Serial Monitoring

