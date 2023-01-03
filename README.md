# BOOK A ROOM - BACKEND

Repositorio para el backend del proyecto de Desarrollo de Sistemas Móviles
Tibu: Reggaeton
Squad: Bad Bunny


## Principales librerías

Se implementó el IDE Android Studio, se utilizaron diversas clases Kotlin y Java
Es necesario implementar las siguientes librerías para el correcto funcionamiento

```bash
    implementation "com.stripe:stripe-java:22.2.0"
    implementation 'com.stripe:stripe-android:17.2.0'
    implementation 'com.android.volley:volley:1.2.1'
    implementation "androidx.lifecycle:lifecycle-viewmodel-compose:2.5.1"
```

## Rutas al Backend

```python
GET /api/reservar/v1/hotel
GET /api/reservar/v1/usuario
GET /api/reservar/v1/habitacion
GET /api/reservar/v1/reserva

GET /api/reservar/v1/hotel/{hotelId}
GET /api/reservar/v1/reserva/{reservaId}
GET /api/reservar/v1/usuario/{usuarioId}
GET /api/reservar/v1/habitacion/{habitacionId}
```
## Uso

Para ejecutar el programa es necesario contar con un dispositivo móvil.
Se puede utilizar un dispositivo externo, o un emulador proporcionado por Android Studio.


```bash
    Emulador utilizado: Pixel_3a_API_33_x86_64
    Dispositivo externo: Conectar por medio de DeviceManager
```
