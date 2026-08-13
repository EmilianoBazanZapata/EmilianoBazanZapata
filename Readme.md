# 👋 ¡Hola! Soy Emiliano Bazan-Zapata

### 🎮 Software & Game Developer | 💻 .NET | 🕹️ Unity & Unreal Engine | 🎨 3D Artist

Soy desarrollador de software especializado en el ecosistema **.NET** y estudiante de **Administración y Desarrollo de Videojuegos en UTN Buenos Aires**.

Me interesa especialmente la arquitectura de software, el desarrollo de videojuegos y la combinación entre **programación y arte 3D**.

Actualmente trabajo en proyectos personales y académicos que van desde aplicaciones multiplataforma hasta videojuegos desarrollados con **Unity y Unreal Engine**.

---

## 🔗 Acceso rápido

🤠 **WesternShooter — Unity 6 / C# / Modular Monolith**
👉 [github.com/EmilianoBazanZapata/WesternShooter](https://github.com/EmilianoBazanZapata/WesternShooter)

👑 **Jorge el Rey Justiciero — Unity / C# / Gameplay Refactoring**
👉 [github.com/EmilianoBazanZapata/JorgeElReyJusticiero](https://github.com/EmilianoBazanZapata/JorgeElReyJusticiero)

⏱️ **Timely — .NET MAUI**
👉 [Disponible en Google Play](https://play.google.com/store/apps/details?id=com.binarysuns.timely)

🌐 **Binary Suns Studio — Portfolio & Game Studio**
👉 [binarysunsstudio.com.ar](https://binarysunsstudio.com.ar)

💼 **LinkedIn**
👉 [linkedin.com/in/emiliano-bazán-zapata-18705721a](https://www.linkedin.com/in/emiliano-bazán-zapata-18705721a)

---

## 🚀 Sobre mí

* 💻 **Desarrollador .NET Semi-Senior**
* 🎓 Estudiante de **Administración y Desarrollo de Videojuegos — UTN**
* 🎮 Desarrollo de videojuegos con **Unity, Unreal Engine, C# y C++**
* 📱 Desarrollo de aplicaciones multiplataforma con **.NET MAUI**
* 🧱 Interés en **Clean Architecture, Vertical Slice Architecture y sistemas modulares**
* 🎨 Experiencia con **Blender y Adobe Illustrator**
* 🌎 Argentina
* 🌌 Objetivo a largo plazo: crear mi propio **estudio de videojuegos**

---

# 🛠️ Tecnologías

## 💻 Lenguajes

`C#` `C++` `SQL`

## 🌐 Backend & aplicaciones

`.NET` `.NET MAUI` `Entity Framework Core` `MediatR` `FluentValidation`

## 🗄️ Bases de datos

`SQLite` `SQL Server`

## ⚙️ Herramientas

`Git` `GitHub` `Azure DevOps` `Visual Studio` `Rider`

## 🎮 Game Development

`Unity` `Unreal Engine` `URP` `Unity Input System` `NavMesh`

## 🎨 Arte y diseño

`Blender` `Adobe Illustrator`

---

# 🚀 Proyectos destacados

## 🤠 WesternShooter

> 🎮 **Repositorio:**
> [github.com/EmilianoBazanZapata/WesternShooter](https://github.com/EmilianoBazanZapata/WesternShooter)

**WesternShooter** es un prototipo de shooter western en tercera persona desarrollado con **Unity 6 y C#**.

El proyecto nació principalmente como un trabajo académico enfocado en **audio interactivo**, utilizando un gameplay compacto como soporte para experimentar con música adaptativa, snapshots, ambientación, voces y efectos de sonido.

Posteriormente utilicé el proyecto como ejercicio de **refactorización y arquitectura aplicada a videojuegos**, reorganizando progresivamente el código hacia un enfoque de **monolito modular**.

### 🎧 Audio interactivo

El proyecto incluye sistemas como:

* Audio Mixer con buses independientes.
* Música adaptativa.
* Snapshots según el estado del gameplay.
* Ambientes.
* Voces del jugador.
* Audio de enemigos.
* Transiciones entre estados de audio.
* Control independiente de Music, SFX, Voice y Ambience.

### 🧱 Arquitectura

Actualmente el proyecto se encuentra dividido en módulos:

```text
WesternShooter.Shared
WesternShooter.Player
WesternShooter.Zombies
WesternShooter.Spawning
WesternShooter.Audio
WesternShooter.Camera
WesternShooter.GameFlow
WesternShooter.UI
```

Cada módulo posee responsabilidades específicas y sus dependencias están reforzadas mediante **Unity Assembly Definition Files (`.asmdef`)**.

Entre los conceptos aplicados se encuentran:

* Modular Monolith
* Separation of Concerns
* Event-Driven Communication
* State Machines
* Assembly Definitions
* Dependency Boundaries
* Pure C# Domain Models
* Unity Lifecycle Management

### 🎮 Gameplay

El jugador puede:

* desplazarse por el escenario;
* correr;
* apuntar;
* disparar;
* combatir zombies;
* recibir daño;
* activar estados de audio mediante gameplay;
* alcanzar estados de victoria o derrota.

El alcance del gameplay es deliberadamente pequeño porque el objetivo principal del proyecto es experimentar con **audio interactivo y arquitectura de gameplay**.

### 🔗 Ver proyecto

👉 **[Abrir WesternShooter en GitHub](https://github.com/EmilianoBazanZapata/WesternShooter)**

---

## 👑 Jorge el Rey Justiciero

> 🎮 **Repositorio:**
> [github.com/EmilianoBazanZapata/JorgeElReyJusticiero](https://github.com/EmilianoBazanZapata/JorgeElReyJusticiero)

**Jorge el Rey Justiciero** es un videojuego 2D desarrollado con **Unity y C#** que retomé como ejercicio de **modernización y refactorización de un proyecto existente**.

El objetivo no fue reconstruir el juego desde cero, sino trabajar sobre una base legacy y mejorar progresivamente su arquitectura, organización y mantenibilidad sin agregar complejidad innecesaria.

### 🧱 Refactorización

Entre las mejoras realizadas se encuentran:

* Separación de responsabilidades del jugador.
* Implementación de una **Finite State Machine** para los estados del personaje.
* Estados independientes como `Idle`, `Run`, `Jump`, `Fall` y `Dead`.
* Migración al **Unity Input System** moderno.
* Separación del flujo general del juego.
* Organización del código por features y namespaces.
* Uso de **Assembly Definition Files (`.asmdef`)** para establecer límites entre dependencias.
* Eliminación de responsabilidades mezcladas y lógica duplicada.
* Corrección de errores detectados durante el proceso de refactorización.

### 🧠 Objetivo técnico

El proyecto funciona como un pequeño **case study de refactorización aplicada a videojuegos**.

La idea principal fue practicar cómo evolucionar código existente hacia una estructura más clara y mantenible, buscando un equilibrio entre:

* Separation of Concerns
* State Machines
* Dependency Boundaries
* Modularización
* Código mantenible
* Refactorización incremental
* Evitar sobrearquitectura

El alcance del juego es relativamente pequeño, pero justamente permite concentrarse en las decisiones técnicas y en la evolución del código.

### 🔗 Ver proyecto

👉 **[Abrir Jorge el Rey Justiciero en GitHub](https://github.com/EmilianoBazanZapata/JorgeElReyJusticiero)**

---

## ⏱️ Timely

**Timely** es una aplicación multiplataforma de seguimiento y gestión de tiempo desarrollada con **.NET MAUI** y publicada en **Google Play**.

El proyecto comenzó como una aplicación relativamente pequeña y evolucionó progresivamente hacia una arquitectura más escalable y mantenible.

### 🧱 Tecnologías y conceptos

* .NET MAUI
* C#
* Entity Framework Core
* SQLite
* MediatR
* FluentValidation
* MVVM
* Dependency Injection
* Vertical Slice Architecture
* Arquitectura modular

Timely también funciona como espacio de experimentación para aplicar patrones y conceptos de arquitectura utilizados habitualmente en backend dentro de una aplicación cliente multiplataforma.

### 📱 Disponible en Google Play

👉 **[Ver Timely en Google Play](https://play.google.com/store/apps/details?id=com.binarysuns.timely)**

---

## 🧱 Tetris Game

Implementación de **Tetris desarrollada en C# utilizando SDL Tao**.

Incluye:

* Sistema de puntuación.
* Condiciones de victoria y derrota.
* Controles mediante teclado y mouse.
* Lógica completa de piezas y tablero.
* Arquitectura modular basada en principios de **Clean Architecture**.

---

# 🧠 Arquitectura y desarrollo de software

Además del desarrollo funcional, utilizo mis proyectos para experimentar y profundizar en conceptos como:

* Clean Architecture
* Vertical Slice Architecture
* Modular Monolith
* Dependency Injection
* Event-Driven Systems
* State Machines
* SOLID
* Separation of Concerns
* Dependency Boundaries
* Diseño de sistemas para videojuegos
* Arquitectura de gameplay
* Refactorización de código legacy
* Optimización
* Mantenibilidad y escalabilidad

Me interesa especialmente trasladar conceptos utilizados tradicionalmente en desarrollo de software al contexto de los videojuegos, adaptándolos a las necesidades reales de cada proyecto y **sin agregar complejidad innecesaria**.

---

# 🌱 Actualmente

Estoy profundizando mis conocimientos en:

* 🕹️ Unity
* ⚙️ Unreal Engine
* 💻 C++ aplicado al desarrollo de videojuegos
* 🎮 Arquitectura para videojuegos
* 🧱 Diseño de sistemas de gameplay
* ⚡ Optimización
* 🌐 Servicios online para videojuegos
* ☁️ Cloud y backend
* 🎨 Modelado y diseño 3D
* 🧠 Diseño de motores y sistemas de videojuegos

---

# 🌌 Mi objetivo

Mi objetivo a largo plazo es crear un **estudio independiente de videojuegos** donde pueda combinar dos áreas que disfruto especialmente:

### 💻 Programación + 🎨 Arte

Quiero desarrollar experiencias donde la tecnología, la arquitectura del software, el gameplay y la identidad visual formen parte del mismo proceso creativo.

También busco seguir creciendo como desarrollador, experimentar con distintas tecnologías y construir proyectos cada vez más completos, tanto en el mundo del software como en el desarrollo de videojuegos.

---

# 🌐 Binary Suns Studio

**Binary Suns Studio** es mi espacio personal para reunir proyectos de software, videojuegos y trabajos relacionados con desarrollo y arte digital.

🌐 **Sitio web / Portfolio**
👉 [binarysunsstudio.com.ar](https://binarysunsstudio.com.ar)

La idea es que el estudio funcione progresivamente como punto de encuentro entre mis proyectos de desarrollo de software y mi trabajo en videojuegos, combinando **programación, arquitectura, gameplay y arte**.

---

# 📫 Contacto

💼 **LinkedIn**
[linkedin.com/in/emiliano-bazán-zapata-18705721a](https://www.linkedin.com/in/emiliano-bazán-zapata-18705721a)

🐙 **GitHub**
[github.com/EmilianoBazanZapata](https://github.com/EmilianoBazanZapata)

🌐 **Binary Suns Studio — Portfolio & Game Studio**
[binarysunsstudio.com.ar](https://binarysunsstudio.com.ar)

📧 **Email**
[emilianobz546@gmail.com](mailto:emilianobz546@gmail.com)

---

### 🌌 Nos veremos en las estrellas.
