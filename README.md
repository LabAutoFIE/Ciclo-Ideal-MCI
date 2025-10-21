# Ciclo-Ideal-MCI
<div align="center">
  <img width="150" height="150" alt="AutoSolo3_circle" src="https://github.com/user-attachments/assets/38627ca5-195e-4675-b25b-05d910e9b540" />
</div>
# 🔧 Ciclo Ideal de Motor de Combustión Interna – Python Notebook

**Archivo fuente:** [`CicloIdeal.ipynb`](https://colab.research.google.com/drive/1joduDgb9NQuNTUs34p9TW44qeP2Fuxaj)  
**Generado automáticamente por Google Colab**  
**Autor:** Gerhard Raith  
**Lenguaje:** Python 3.x  
**Entorno sugerido:** Google Colab o Jupyter Notebook

---

## 📘 Descripción del proyecto:

Este notebook simula el comportamiento termodinámico de un motor de combustión interna de 4 tiempos bajo condiciones ideales. Se modelan y grafican los siguientes ciclos:

- Ciclo Otto ideal en coordenadas P–V
- Ciclo adiabático en coordenadas P–α
- Ciclo ideal sin salto de combustión
- Ciclo ideal con salto de combustión

Incluye visualizaciones técnicas de presión vs volumen y presión vs ángulo del cigüeñal, con parámetros geométricos realistas y coeficientes adiabáticos del aire.

---

## ⚙️ Requisitos

```bash
pip install numpy matplotlib
```
## 📊 Contenido técnico

### 1. Ciclo Otto ideal (P–V)

- **Modelo:** 4 tiempos con compresión y expansión adiabática + procesos isocóricos
- **Parámetros:**
  - γ = 1.403 (aire)
  - Patm = 101325 Pa
  - Vtotal = 520e-6 m³
  - Rc = 10 (relación de compresión)

### 2. Ciclo adiabático (P–α)

- **Ángulo cigüeñal:** de –180° a 180°
- **Geometría:**
  - Diámetro = 85.5 mm
  - Radio cigüeñal = 41.25 mm
  - Longitud biela = 144.375 mm
  - Volumen cámara = 52 cm³

### 3. Ciclo ideal sin salto de combustión

- **Ángulo cigüeñal:** 0° a 720°
- **Presión constante en admisión y escape**
- **Presión máxima sin incremento artificial**

### 4. Ciclo ideal con salto de combustión

- Igual al anterior, pero con incremento de presión ideal (P3 = P2 × 2.5)

---

## 📈 Resultados esperados

- Gráficos P–V y P–α con curvas adiabáticas e isocóricas
- Identificación del punto de máxima presión (PMS)
- Comparación entre ciclos con y sin salto de combustión

---

## 🌐 Versión en alemán

### 🔧 Idealer Verbrennungsmotor-Zyklus – Python Notebook

Dieses Notebook simuliert den thermodynamischen Verlauf eines idealisierten Viertakt-Verbrennungsmotors. Es enthält:

- Otto-Zyklus in P–V-Koordinaten
- Adiabatischer Zyklus in P–α-Koordinaten
- Zyklus ohne Verbrennungssprung
- Zyklus mit Verbrennungssprung

---

## 📍 Ubicación y contacto:
**Facultad de Ingeniería del Ejército "Grl. Div. Manuel N. Savio"**  
<img src="https://img.icons8.com/color/48/marker--v1.png" alt="Dirección" width="20" height="20" style="vertical-align:middle;"/> Av. Cabildo 15, C1426AAA Ciudad Autónoma de Buenos Aires, Argentina   
📞 Teléfono: (+54 11) 4779-3300  
<img src="https://img.icons8.com/color/48/new-post.png" alt="Email" width="20" height="20" style="vertical-align:middle;"/> e-mail Institucional: [info@fie.undef.edu.ar](mailto:info@fie.undef.edu.ar)  
<img src="https://img.icons8.com/color/48/new-post.png" alt="Email" width="20" height="20" style="vertical-align:middle;"/> e-mail Laboratorio: [automotores@fie.undef.edu.ar](mailto:automotores@fie.undef.edu.ar)  
🌐 Sitio web: [www.fie.undef.edu.ar](https://www.fie.undef.edu.ar)  
📌 [Google Maps](https://www.google.com/maps?q=Av.+Cabildo+15,+C1426+Ciudad+Aut%C3%B3noma+de+Buenos+Aires,+Argentina)  
<a href="https://web.whatsapp.com/send?phone=5491138569689&text=Hola%2C+quisiera+consultar+sobre+el+Laboratorio+de+Automotores." target="_blank">
  <img src="https://img.icons8.com/color/48/whatsapp--v1.png" alt="WhatsApp" width="20" height="20" style="vertical-align:middle;"/> Mensaje Institucional FIE
</a>  

---

## 📝 Licencia

Este proyecto se distribuye bajo licencia institucional para fines educativos y de simulación técnica.  
Para uso público, incluir atribución a Gerhard Raith y enlace al notebook original.
