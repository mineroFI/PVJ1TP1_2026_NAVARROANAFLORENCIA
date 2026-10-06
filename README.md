# TP1 - Proyecto de Videojuegos 1

## 🎮 Descripción del juego

Este proyecto consiste en un videojuego de movimiento y plataforma desarrollado con **Unity 6000.5.7f1**. El objetivo principal es recorrer el escenario, recoger un objeto, transportarlo hasta la zona de entrega y completar la partida.

El jugador (Glorp) puede desplazarse por el mapa, saltar, recoger y soltar objetos, utilizar plataformas móviles y evitar o reaccionar ante los obstáculos generados por el escenario.

## 📸 Captura del escenario

En Documentation.

## 🧩 Mecánicas implementadas

- **Movimiento del personaje:** desplazamiento con `WASD` o flechas, salto con `Space` y orientación hacia la dirección de movimiento.
- **Agarre y transporte:** el jugador puede recoger un objeto cercano mediante `E` y transportarlo en un punto establecido del personaje.
- **Entrega:** la zona de meta detecta el objeto correcto y activa una señal visual y partículas de victoria.
- **Power-up de salto:** aumenta temporalmente la fuerza del salto y reaparece después de un intervalo.
- **Plataformas móviles:** se desplazan entre dos puntos y llevan al jugador mientras mantiene contacto con ellas.
- **Obstáculos:** los spawners instancian bolas de lana que se lanzan y empujan al jugador al colisionar.
- **Cámara:** sigue al personaje con suavizado y mantiene el objetivo visible en pantalla.
- **Entrada de control:** el proyecto incluye bindings para teclado, mando y otros dispositivos mediante Unity Input System.

## 🕹️ Controles

| Acción | Teclado |
|---|---|
| Moverse | `W`, `A`, `S`, `D` o flechas |
| Saltar | `Space` |
| Recoger o soltar objeto | `E` |
| Soltar objeto | `Q` |

## 🚀 Requisitos

- Unity Hub.
- Unity **6000.5.7f1**.
- Windows 64 bits para la plataforma de destino configurada por el proyecto.
- Una instalación de Unity con soporte para el paquete **Input System** y **Universal Render Pipeline (URP)**.

## 📦 Instrucciones para abrir y ejecutar el proyecto

1. Descarga e instala **Unity Hub** y la versión **6000.5.7f1**.
2. Clona o descarga este repositorio.
3. Abre Unity Hub y selecciona **Open**.
4. Selecciona la carpeta raíz del proyecto.
5. Espera a que Unity importe y cargue los paquetes.
6. En el Project Window, abre la escena `Assets/Scenes/SampleScene.unity`.
7. Pulsa **Play** en la barra superior para ejecutar el juego.

## 🗂️ Estructura principal del proyecto

```text
Assets/
├── InputSystem_Actions.inputactions
├── Modelos/
├── Prefabs/
│   └── YarnBall.prefab
├── Scenes/
│   └── SampleScene.unity
└── Scripts/
    ├── CameraFollow.cs
    ├── CarriableItem.cs
    ├── DeliveryZone.cs
    ├── MovingPlatform.cs
    ├── ObstacleSpawner.cs
    ├── PlayerCarry.cs
    ├── PlayerController.cs
    ├── PowerUp.cs
    └── RollingYarn.cs
```

## 🛠️ Tecnologías utilizadas

- Unity 6000.5.7f1
- C#
- Unity Physics mediante `Rigidbody` y `Collider`
- Unity Input System
- Universal Render Pipeline (URP)

## 👩‍💻 Autor

Ana Florencia Navarro

## 📄 Licencia

Este proyecto no incluye una licencia explícita. No se permite reutilizar ni distribuir el contenido sin consultar previamente al autor.
