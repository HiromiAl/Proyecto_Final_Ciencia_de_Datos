#  Proyecto Final: Análisis Exploratorio y de Negocio — Brazilian E-Commerce (Olist)

## 📌 Información Académica
* **Institución:** Instituto Tecnológico Superior de Alvarado (ITSAV)
* **Materia:** Ciencia de Datos
* **Profesor:** I.S.C. Fernando Mayorga Guittins
* **Equipo A:**
  1. Hiromi Alejandra Mosqueda Salto (Líder Técnico)
  2. Christopher Vasquez Carvajal (Desarrollador - Limpieza)
  3. Erik Alberto Hernández Orozco(Desarrollador - Ingeniería de Datos)
  4. Alberto Quevedo Gapi (Desarrollador - EDA y Visualización)

---

## 📊 Descripción del Proyecto
Este proyecto realiza un **Análisis Exploratorio de Datos (EDA)** sobre el conjunto de datos público de e-commerce de **Olist** (Brasil), compuesto por más de 100,000 órdenes de compra entre 2016 y 2018. El objetivo es responder a tres preguntas estratégicas de negocio evaluando el rendimiento logístico, comercial y financiero.

---

## 🎯 Preguntas de Negocio
1. **Satisfacción Logística:** ¿Cómo impacta el tiempo de entrega real frente al estimado en la calificación de satisfacción del cliente? *(Cruce entre `orders` y `reviews`)*.
2. **Rendimiento Comercial:** ¿Cuáles son las 5 categorías de productos que generan mayores ingresos económicos en la plataforma? *(Cruce entre `order_items`, `products` y `translation`)*.
3. **Análisis Financiero:** ¿Cuál es la relación entre el método de pago elegido por el usuario y el valor total del ticket de compra? *(Cruce entre `orders` y `payments`)*.

---

## 📂 Estructura del Repositorio

\`\`\`text ├── .gitignore # Exclusión de archivos pesados (.csv) y temporales de Python/Colab ├── requirements.txt # Lista de dependencias y librerías necesarias (pandas, numpy, seaborn, etc.) ├── README.md # Documentación principal del proyecto e instrucciones └── Proyecto\_Final\_EDA.ipynb # Cuaderno ejecutable unificado (Secciones 1 a 7)

---

## 🚀 Instrucciones de Ejecución
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git

Asegurarse de tener la estructura de carpetas en Google Drive:
 Mi Unidad/Proyecto_Final/data/


Guardar los archivos .csv de Olist dentro de dicha carpeta.
Abrir el cuaderno Proyecto_Final_EDA.ipynb en Google Colab, ejecutar todas las celdas en orden secuencial.

Enlace al dataset : https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?select=olist_geolocation_dataset.csv
