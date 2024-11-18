# 🚗 Generador de Datos de Ventas de Vehículos en JSON 📊

## 📋 Descripción del Proyecto
Esta aplicación web interactiva está diseñada para generar datos simulados de ventas de vehículos, proporcionando una representación realista y completa de un sistema de ventas en el sector automotriz. La aplicación permite crear información detallada sobre clientes, vendedores, vehículos, ventas y transacciones asociadas, siendo ideal para realizar prácticas de análisis de datos, pruebas de sistemas y desarrollo de aplicaciones.

## 🎯 Objetivo Principal
El objetivo principal de esta aplicación es proporcionar un conjunto de datos ficticios que pueden utilizarse para comprender y analizar la estructura de un sistema de ventas de vehículos. Los datos generados son completos y cubren aspectos clave del proceso de ventas, permitiendo simular un escenario de ventas real.

### 📑 Este proyecto se enfoca en la creación de un modelo de datos con cinco tablas fundamentales:

- 👥 **Clientes**: Información sobre los compradores, como códigos, nombres, y preferencias.
- 👨‍💼 **Vendedores**: Datos de los empleados de ventas, incluyendo códigos, nombres y otras características.
- 🚙 **Vehículos**: Descripción de los vehículos disponibles, incluyendo marcas, modelos, precios y características.
- 💰 **Ventas**: Registro de transacciones realizadas, con detalles como número de factura, cliente, vendedor y fecha.
- 📝 **Detalles de Ventas**: Información específica sobre vehículos vendidos en cada transacción.

## 📚 Propósito Educativo y Analítico
Este conjunto de datos permite realizar análisis en varias áreas fundamentales de la gestión de datos y modelos de ventas. Los usuarios podrán:

- 🔄 **Entender la Cardinalidad y Normalización**: Identificar relaciones entre datos y estructura de bases de datos.
- 🔗 **Explorar Relaciones entre Entidades**: Comprender interacciones entre vendedores, ventas y clientes.
- 📊 **Prácticas de Análisis de Datos**: Experimentar con herramientas para crear análisis visuales y generar informes.

## 💻 Aplicaciones y Tecnologías
Este generador puede utilizarse con diversas herramientas de análisis:

- 📈 **Excel**: Análisis con tablas dinámicas, gráficos y fórmulas.
- 📊 **Power BI**: Creación de dashboards e informes interactivos.
- 🔧 **Otras tecnologías**: Integración flexible gracias al formato JSON.

## ✨ Beneficios del Proyecto
Al trabajar con esta aplicación, los usuarios obtienen:

- 📈 Desarrollo de habilidades en análisis y modelado de datos
- 🎓 Familiarización con estructuras de bases de datos relacionales
- 📑 Capacidad para crear informes detallados para toma de decisiones empresariales
## ✨ Características Principales
- 🎯 Generación de datos realistas de ventas de vehículos
- 👥 Creación de perfiles de clientes y vendedores
- 🚙 Catálogo de vehículos con imágenes y especificaciones
- 📄 Exportación de datos en formato JSON
- 📦 Empaquetado automático en archivo ZIP
- 🎚️ Controles interactivos para personalizar la cantidad de datos

## 🛠️ Tecnologías Utilizadas
- **Python** 🐍 - Lenguaje de programación principal
- **Streamlit** 🌟 - Framework para crear aplicaciones web
- **Faker** 👤 - Biblioteca para generar datos ficticios
- **JSON** 📋 - Formato de datos estructurados
- **BytesIO** 💾 - Manejo de datos en memoria
- **ZipFile** 🗜️ - Compresión de archivos

## 📚 Bibliotecas Requeridas
```bash
streamlit
faker
```

## 🚀 Instalación

1. **Crear entorno virtual** 🔧
```bash
python -m venv venv
```

2. **Activar entorno virtual** ⚡
```bash
# Windows
.\venv\Scripts\activate

# macOS/Linux
source venv/bin/activate
```

3. **Instalar dependencias** 📦
```bash
pip install streamlit faker
```

## 🎮 Uso

1. **Ejecutar la aplicación** 🖥️
```bash
streamlit run app.py
```

2. **Configurar parámetros** ⚙️
   - Ajustar número de clientes 👥
   - Definir cantidad de vendedores 👨‍💼
   - Establecer número de ventas 💰
   - Seleccionar vehículos a incluir 🚙
   - Especificar rango de fechas 📅

3. **Generar datos** 🎲
   - Presionar el botón "Generar Datos"
   - Revisar los datos generados
   - Descargar el archivo ZIP con los JSON

## 💡 Casos de Uso
- 📊 Prácticas de análisis de datos
- 🔍 Testing de aplicaciones de gestión de ventas
- 📈 Desarrollo de dashboards
- 🎓 Ejercicios educativos de bases de datos
- 🧪 Pruebas de sistemas de reportería

## 🌟 Resultados Esperados
Los archivos JSON generados incluyen:
- `clientes.json` 👥 - Información de clientes
- `vendedores.json` 👨‍💼 - Datos de vendedores
- `ventas.json` 💰 - Registro de transacciones
- `detalles_ventas.json` 📋 - Detalles específicos de cada venta
- `vehiculos.json` 🚗 - Catálogo de vehículos disponibles

## 👨‍💻 Autor
**Ing. Juancito Peña**

¡Me encantaría conectar contigo! Encuentra más contenido y actualizaciones en mis redes:

## 📱 Redes Sociales

1. 🎬 [Youtube](https://www.youtube.com/channel/UCSob-3E5z4IHtMF5B4bN-FA)
2. 👨‍💼 [LinkedIn](https://www.linkedin.com/in/juancitope%C3%B1a/)
3. 📷 [Instagram](https://www.instagram.com/juancito.pena.v/)
4. 📑 [Facebook](https://www.facebook.com/juancito.p.v)
5. 🐦 [Twitter](https://twitter.com/JuancitoPenaV)

## 📬 Contacto Directo

📧 Email: juancito.pena@gmail.com

## 💪 ¡Apoya mi Contenido!

⭐ Dale like y comparte si te resulta útil
💬 Déjame tus comentarios y sugerencias
🔔 Suscríbete para más contenido de calidad

¡Tu apoyo hace posible la creación de más contenido educativo y profesional! 🙌

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Si tienes sugerencias o mejoras:
1. 🍴 Haz fork del repositorio
2. 🔧 Crea una rama para tu feature
3. 📝 Realiza tus cambios
4. 📫 Envía un pull request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE.md](LICENSE.md) para más detalles.
