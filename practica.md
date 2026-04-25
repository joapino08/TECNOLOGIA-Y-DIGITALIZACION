---
layout: default
title: Practica
nav_order: 3
---

# 📘 DISEÑO DE UN SISTEMA DE ILUMINACIÓN AUTOMÁTICA CON ARDUINO

## 🎯 Objetivo

En este apartado encontraras diferentes ejercicios para poner en práctica lo aprendido en la reoria.

---

## 🧭 Ejercicios circuitos

### 1.	Dibuja un circuito básico con una Led y una pila.

### 2.	Amplia el circuito anterior con un interruptor.

### 3.	Indica si el siguiente circuito está en paralelo o en serie.
 
### 4.	Indica con flechas el sentido de la corriente en el siguiente circuito
 
### 5.	Indica cual es el valor de la siguiente resistencia

 
## 🧭 Ejercicios arduino

### 1.	Escribe el trozo de código que utilizarías para crear una variable de tipo entero llamada velocidad que almacene los datos de un potenciómetro conectado al pin A5.

### 2.	Explica que hace este código
void setup()
{
  pinMode(7, OUTPUT);
}
 
void loop()
{
  digitalWrite(7, HIGH);
  delay(500);
  digitalWrite(7, LOW);
  delay(500);
}

### 3.	Explica que hace este código
if (alumnos < 20) {
  digitalWrite(11, HIGH);
}

### 4.	Amplia el código anterior para que aparte de la función actual, apague el led conectado en el pin 11 cuando hay 20 o más alumnos en clase.

### 5.	Tenemos 3 leds (Led 1 rojo, Led 2 naranja, Led 3 Verde) conectados a los pines 10,11 y 12 respectivamente, estos leds nos van a indicar la calidad del aire en función del valor medido por un sensor de CO2 conectado en la entrada analógica A1.
Los pines de salida deben nombrarse como Malo (Led rojo), Medio (Led naranja), Bueno (Led verde) en nuestro código.
Si el CO2 está entre 0 y 15 la calidad del aire es Buena
Si el CO2 está entre 16 y 20 la calidad del aire es Media
Si el CO2 es superior a 20 la calidad del aire es Mala















