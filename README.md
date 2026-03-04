# ⚰️ Cementerio de Écija – Aplicación Android

<div align="center">

[![Android](https://img.shields.io/badge/Android-Java-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://www.android.com/)
[![IDE](https://img.shields.io/badge/IDE-Android%20Studio-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://developer.android.com/studio)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

*Una aplicación móvil para consultar información de fallecidos en el Cementerio de Écija*

[Características](#-características-principales) • [Instalación](#-instalación-y-uso) • [Estructura](#-estructura-del-proyecto) • [Licencia](#-licencia)

</div>

---

## 📖 Descripción del Proyecto

Esta aplicación permite consultar información de personas fallecidas en el Cementerio de Écija de forma **rápida y sencilla** desde un dispositivo móvil Android.

**¿Qué puedes hacer?**
- 📝 Buscar por nombre completo del fallecido
- 📅 Filtrar opcionalmente por fecha
- 🪦 Obtener número de lápida
- 📍 Conocer ubicación exacta
- 📄 Acceder a datos asociados

El objetivo principal es **mejorar la accesibilidad** y la experiencia de usuario respecto a la versión web original.

---

## ✨ Características Principales

- 🔎 **Búsqueda por nombre completo** – Encuentra rápidamente a la persona que buscas
- 📅 **Filtro opcional por fecha** – Refina resultados si lo necesitas
- ⚡ **Resultados rápidos y claros** – Información instantánea
- 🎨 **Interfaz intuitiva** – Diseño sencillo y fácil de usar
- 📱 **Optimizado para móvil** – Experiencia adaptada a dispositivos pequeños
- 🌙 **Compatible con múltiples versiones** – Funciona en diferentes dispositivos

---

## 🛠️ Tecnologías Utilizadas

| Tecnología | Descripción |
|-----------|-------------|
| ☕ **Java** | Lenguaje de programación principal |
| 🤖 **Android SDK** | Kit de desarrollo para Android |
| 🧩 **Android Studio** | Entorno de desarrollo integrado |
| 🌐 **API Web** | Datos adaptados desde plataforma web |

---

## 🚀 Instalación y Uso

### Requisitos previos
- Android Studio instalado
- JDK 8 o superior
- Git configurado en tu sistema

### Pasos de instalación

**1️⃣ Clonar el repositorio**
```bash
git clone https://github.com/areyort4827/Cementerio-ecija.git
cd Cementerio-ecija
```

**2️⃣ Abrir en Android Studio**
- Abre Android Studio
- Selecciona `File → Open` y navega hasta la carpeta del proyecto

**3️⃣ Sincronizar Gradle**
- Android Studio descargará automáticamente las dependencias
- Espera a que se complete la sincronización

**4️⃣ Ejecutar la aplicación**
- Selecciona un emulador o conecta un dispositivo físico
- Haz clic en `Run → Run 'app'` o presiona `Shift + F10`

---

## 🧠 Flujo de Funcionamiento

```
1. Usuario introduce nombre completo
   ↓
2. Opcionalmente añade fecha
   ↓
3. Se realiza la consulta a la base de datos
   ↓
4. Se muestran resultados:
   - Número de lápida
   - Ubicación exacta
   - Datos adicionales
```

---

## 📂 Estructura del Proyecto

```
Cementerio-ecija/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/areyort4827/cementerioecija/
│   │   │   │       ├── MainActivity.java
│   │   │   │       ├── SearchActivity.java
│   │   │   │       └── DetailActivity.java
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   ├── drawable/
│   │   │   │   ├── values/
│   │   │   │   └── AndroidManifest.xml
│   │   └── test/
│   └── build.gradle
├── gradle/
├── .gitignore
├── README.md
└── LICENSE
```

---

## 🎯 Objetivos del Proyecto

✅ Adaptar una web informativa a una aplicación móvil funcional

✅ Aplicar buenas prácticas en desarrollo Android con Java

✅ Mejorar significativamente la experiencia de usuario en dispositivos móviles

✅ Optimizar la accesibilidad a información del cementerio

---

## 🔮 Mejoras Futuras

- [ ] 🌍 **Geolocalización en mapa** – Ubicar lápidas con GPS
- [ ] 🌙 **Modo oscuro** – Interfaz adaptable a diferentes condiciones
- [ ] 🔍 **Filtros avanzados** – Búsquedas más precisas
- [ ] 📊 **Historial de búsquedas** – Guardar búsquedas recientes
- [ ] 🔔 **Notificaciones** – Alertas de aniversarios
- [ ] 🌐 **Multi-idioma** – Soporte para varios idiomas

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para cambios importantes:

1. Fork el repositorio
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

---

## 👨‍💻 Autor

Antonio Reyes Ortega
📍 Écija, España  
📧 areyesortegatrabajo@gmail.com

---

## 📄 Licencia

Este proyecto se distribuye bajo la **Licencia MIT**.

Para más información, consulta el archivo [LICENSE](LICENSE).

---

<div align="center">

⭐ Si este proyecto te fue útil, considera darle una estrella

Hecho con ❤️ en Écija

</div>
