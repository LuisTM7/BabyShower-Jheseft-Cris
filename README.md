# Baby Shower · Jheseft & Cris 💙

Sitio web de invitación para el Baby Shower de Jheseft y Cris, construido con Astro.

## Evento

- **Fecha:** Sábado 14 de Junio de 2026
- **Hora:** 8:00 PM
- **Lugar:** 224 E Charleston Ave, Lawnside, NJ 08045

## Tecnologías

- [Astro](https://astro.build/) v4
- CSS puro con variables personalizadas
- Vanilla JS para el contador regresivo y el reproductor de audio

## Estructura

```
src/
├── components/
│   ├── Hero.astro          # Sección principal con contador
│   ├── ParentsPhoto.astro  # Foto de los futuros papás
│   ├── EventDetails.astro  # Fecha, hora y carrito animado
│   ├── Ultrasound.astro    # Foto del ultrasonido
│   ├── Map.astro           # Mapa de ubicación
│   ├── RSVP.astro          # Confirmación de asistencia por WhatsApp
│   ├── Countdown.astro     # Contador (oculto)
│   └── AudioPlayer.astro   # Reproductor de música
└── pages/
    └── index.astro         # Página principal
public/
├── images/                 # Imágenes decorativas y fotos
└── audio/                  # Música de fondo (Ice-Age.mp3)
```

## Comandos

```bash
# Instalar dependencias
pnpm install

# Levantar servidor de desarrollo
pnpm dev

# Construir para producción
pnpm build
```
