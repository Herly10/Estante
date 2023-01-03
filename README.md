# Estante

Se implementó el IDE Android Studio, se utilizaron diversas clases Kotlin y Java

## Principales librerías

Es necesario implementar las siguientes librerías

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
