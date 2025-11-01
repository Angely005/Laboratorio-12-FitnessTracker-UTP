# 🧪 Laboratorio Nº 12 - Fitness Tracker UTP

## 📋 Descripción

Este proyecto corresponde al **Laboratorio Nº 12** del curso *Desarrollo de Aplicaciones Móviles* en la Universidad Tecnológica del Perú. El objetivo es construir una aplicación móvil en **React Native (Expo)** que integre sensores del dispositivo (GPS y acelerómetro), visualización en mapa, almacenamiento local y cálculo de métricas en tiempo real.

La app simula funcionalidades de apps como **Nike Run Club**, **Google Fit** o **Strava**, convirtiendo el celular en un rastreador de actividad física.

---

## 📁 Estructura del proyecto
<img width="281" height="237" alt="image" src="https://github.com/user-attachments/assets/69a505bd-8f1b-4f53-80a8-22890febe461" />

---

## 🧠 Modificaciones en App.js

<img width="715" height="955" alt="image" src="https://github.com/user-attachments/assets/f37b0aef-053d-4655-accf-730fd78ceaf7" />

---

<img width="655" height="948" alt="image" src="https://github.com/user-attachments/assets/e07d8a33-2889-40eb-a290-04c798801174" />

---

<img width="779" height="876" alt="image" src="https://github.com/user-attachments/assets/be14306f-2727-4779-b53c-d8365a2beed2" />


---

## ⚙️ ¿Cómo funciona?

1. **Permisos GPS:** Al iniciar, la app solicita acceso a la ubicación.
2. **Ubicación inicial:** Se muestra la posición actual en el mapa con un marcador.
3. **Ruta y distancia:** Cada 5 segundos se actualiza la ubicación y se calcula la distancia recorrida.
4. **Acelerómetro:** Se leen los valores `x`, `y`, `z` en tiempo real y se estiman pasos por cambios de aceleración.
5. **Velocidad:** Se muestra la velocidad promedio en km/h.
6. **Almacenamiento local:** Se guarda la última ubicación y el historial de recorridos en `AsyncStorage`.
7. **Reinicio:** Un botón permite reiniciar la distancia y los pasos.
8. **Historial:** Los recorridos se guardan con timestamp, coordenadas, pasos y distancia.

---
## Ejecución:

<img width="720" height="1420" alt="image" src="https://github.com/user-attachments/assets/b999110a-dcab-425b-96b2-41382c565b81" />

---
<img width="723" height="1600" alt="image" src="https://github.com/user-attachments/assets/b5380ca7-9598-406c-bc27-ca950bca3a9e" />

---
<img width="723" height="1600" alt="image" src="https://github.com/user-attachments/assets/24a4479d-94ff-4975-9e38-3b291d0d3ee4" />

---

<img width="723" height="1600" alt="image" src="https://github.com/user-attachments/assets/8883fea5-6b75-4bcf-a7f6-3d2e79ac1a12" />

---



