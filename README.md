# Tromen GPT Bot 🎉

Este repositorio contiene el código para **Bruno**, un bot inteligente basado en GPT desarrollado para **Tromen**, una empresa líder en Argentina especializada en soluciones de calefacción. El bot está diseñado para interactuar con los usuarios a través de la plataforma de [AsisteClick](https://asisteclick.com/), proporcionando respuestas rápidas y efectivas a consultas relacionadas con los productos y servicios de Tromen.

## 🌐 Sitio web de Tromen

[Tromen](https://tromen.com/) ofrece una amplia gama de productos diseñados para brindar calidez y confort a los hogares. Visita el sitio para obtener más información sobre la empresa y sus productos.

## ✨ Características del Bot

- 🤖 **Asistente Virtual Bruno**: IA especializada en productos Tromen con procesamiento de lenguaje natural
- 🔗 **Integración con AsisteClick**: Comunicación en tiempo real con los usuarios
- 🎯 **Base de conocimientos especializada**: Información detallada sobre estufas, cocinas, hornos y accesorios
- 📧 **Enrutamiento inteligente**: Deriva consultas complejas a departamentos específicos
- 🔍 **Búsqueda de productos**: Funcionalidad integrada para consultar el catálogo de Tromen
- 🚀 **Escalabilidad**: Arquitectura preparada para crecimiento

## 🛠️ Tecnologías utilizadas

- **GPT (Generative Pre-trained Transformer)**: Motor de inteligencia artificial para el procesamiento del lenguaje natural
- **AsisteClick**: Plataforma de atención al cliente y chat en vivo
- **Node.js**: Para la lógica del backend y la integración con APIs
- **Docker**: Para facilitar la implementación y el despliegue
- **GitHub Actions**: Para CI/CD automatizado

## 📁 Estructura del Proyecto

```
├── 0 Configuracion/
│   └── 0 Bases de conocimiento.md    # Base de conocimientos de productos Tromen
├── README.md
├── package.json
├── Dockerfile
└── .github/
    └── workflows/                    # Configuración de CI/CD
```

## ✅ Requisitos previos

- 📦 Node.js (versión 14 o superior)
- 🐳 Docker (opcional para el despliegue)
- 🔑 Una cuenta activa en AsisteClick con credenciales de API
- 🔑 Clave de API de GPT

## 🚀 Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/sanchezluys/ChatBot-con-GPT-IA-para-Tromen.git
   cd ChatBot-con-GPT-IA-para-Tromen
   ```

2. Instala las dependencias:
   ```bash
   npm install
   ```

3. Configura las variables de entorno:
   Crea un archivo `.env` en la raíz del proyecto:
   ```env
   GPT_API_KEY=tu_clave_api_de_gpt
   ASISTECLICK_API_KEY=tu_clave_api_de_asisteclick
   ```

4. Inicia el servidor:
   ```bash
   npm start
   ```

## 💬 Uso

- Accede a la plataforma de AsisteClick para interactuar con Bruno
- Realiza consultas sobre:
  - Productos Tromen (estufas, cocinas, hornos)
  - Instalación y mantenimiento
  - Servicio técnico y garantías
  - Distribuidores y puntos de venta

## 📦 Despliegue

### Con Docker
```bash
docker build -t tromen-gpt-bot .
docker run -p 3000:3000 --env-file .env tromen-gpt-bot
```

### CI/CD con GitHub Actions
El repositorio incluye workflows automatizados para testing y despliegue. Los cambios en la rama principal activan automáticamente el pipeline de CI/CD.

## 🧠 Base de Conocimientos

El bot cuenta con una extensa base de conocimientos que incluye:
- Información técnica de productos
- Procedimientos de instalación y mantenimiento
- Respuestas predeterminadas para consultas frecuentes
- Directorio de distribuidores internacionales
- Guías de servicio técnico

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! 💡 Por favor, sigue estos pasos:

1. Haz un fork del repositorio
2. Crea una rama con tu funcionalidad: `git checkout -b nueva-funcionalidad`
3. Realiza tus cambios y haz un commit: `git commit -m 'Agrega nueva funcionalidad'`
4. Envía un pull request

## 📜 Licencia

Este proyecto está licenciado bajo la [MIT License](LICENSE).

---

[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/sanchezluys/ChatBot-con-GPT-IA-para-Tromen)

**📩 Contacto**
