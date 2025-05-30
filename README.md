# Inteligencia de Negocios Geoespacial en Python 🌍

> Proyecto en Python que integra inteligencia artificial, geocodificación y análisis geoespacial para mejorar direcciones, obtener coordenadas y asignar clientes automáticamente a oficinas según su ubicación.

---

## 🎯 Objetivo del Proyecto

Este proyecto tiene como finalidad **automatizar la gestión comercial y logística** mediante:
- Mejora de direcciones con **Google Gemini (IA)**
- Obtención de coordenadas con **OpenRouteService**
- Asignación automática a oficinas usando un archivo **GeoJSON**
- Visualización interactiva con **Folium**
- Generación de un informe en **Excel**

Es ideal para empresas que desean **optimizar rutas, zonificar clientes o automatizar procesos comerciales**.

---

## 🧩 Funcionalidades clave

✅ Estándar de direcciones peruanas con IA  
✅ Geocodificación avanzada  
✅ Validación espacial: ¿el cliente está dentro de una zona específica?  
✅ Mapa interactivo con Folium  
✅ Informe consolidado en Excel con estado de cobertura

---

## 📁 Archivos requeridos

Para ejecutar este proyecto, necesitas los siguientes archivos:

- `clientes.xlsx`: Datos de entrada con columnas:
  - Departamento
  - Provincia
  - Distrito
  - Dirección

- `cercos.geojson`: Polígonos de cobertura con propiedad `"name"` (por ejemplo: `"Oficina Norte"`)

Puedes modificar estos archivos fácilmente para adaptarlos a tus necesidades.

---

## 📄 Archivos generados

Este proyecto genera dos archivos al finalizar:

- `clientes_con_cobertura.xlsx`: Excel con:
  - Dirección original y mejorada
  - Latitud y longitud obtenidas
  - Columna `"Cobertura"`: nombre de la oficina o `"Sin cobertura"`

- `mapa_cobertura.html`: Mapa interactivo con:
  - Los cercos definidos en el GeoJSON
  - Puntos de clientes coloreados por oficina

---

## 🔧 Requisitos técnicos

Instala las dependencias con:

```bash
pip install -r requirements.txt

## 🚀 ¿Cómo usar?

Ejecuta el notebook `inteligencia-negocios-geoespacial.ipynb` en Jupyter o Colab.

## 📬 ¿Quieres ver más proyectos como este?

📌 Sígueme en [LinkedIn](https://www.linkedin.com/in/larry-humpiri-obregon-565145189/)   
📷 Instagram / TikTok: [@tuusuario](https://instagram.com/lionho26) 