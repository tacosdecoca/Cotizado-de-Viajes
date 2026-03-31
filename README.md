# Cotizador-de-Viajes

Pequeño formulario web para realizar una **cotización de viajes por México**. El usuario captura sus datos (nombre, destino, transporte, acompañantes, días/noches) y el sistema calcula un **total estimado** con base en costos fijos.

## Demo / Vista rápida
Abre el archivo `Psb1.html` en tu navegador (doble clic o “Open with…”).

---

## Características
- Formulario para capturar:
  - Nombre y apellidos
  - Estado de la República Mexicana (con `datalist`)
  - Medio de transporte (Autobús / Tren / Avión)
  - Número de acompañantes
  - Días de viaje y noches de hospedaje
  - Extras (checkbox): desayuno, comida y cena
- Cálculo automático del costo total al presionar **Cotizar**
- Muestra el resultado en una alerta (`alert(...)`)

---

## Estructura del proyecto

- `Psb1.html`  
  Página principal con el formulario y la lógica de cálculo (JavaScript embebido).

- `Psb1.css`  
  Estilos del sitio (header, tipografías, espaciados, etc.).

- `logoHan.png`  
  Imagen usada en el encabezado (logo).

- `Evidencia.png`  
  Evidencia/captura del proyecto (ideal para la sección de imágenes del README).

- `README.md`  
  Documentación del proyecto.

---

## Lenguajes utilizados
- **HTML**: estructura del formulario y contenido.
- **CSS**: estilos visuales.
- **JavaScript** (inline dentro de `Psb1.html`): lógica de cálculo y validación básica del envío del formulario.

---

## ¿Cómo funciona la cotización?

En `Psb1.html`, la función `calculos()`:
1. Toma los valores capturados (días, noches, transporte y extras).
2. Calcula:
   - Costo por día y por noche
   - Suma costo del transporte (si se selecciona)
   - Suma costos extra (si se activan los checkboxes)
3. Muestra el total en una alerta.

### Costos usados en el cálculo (constantes)
- Día: 250
- Noche: 250
- Transporte:
  - Autobús: 500
  - Tren: 1000
  - Avión: 5000
- Extras:
  - Desayuno: 200
  - Comida: 500
  - Cena: 450

---

## Requisitos
No requiere instalación ni dependencias.
Solo necesitas un navegador web (Chrome, Edge, Firefox, etc.).

---

## Uso
1. Descarga o clona el repositorio.
2. Abre `Psb1.html` en tu navegador.
3. Completa el formulario.
4. Presiona **Cotizar** para ver el total.

---

## Sección de imágenes

### Evidencia del proyecto
Puedes mostrar la captura incluida en el repositorio:

![Evidencia](Evidencia.png)

### Logo utilizado
![Logo](logoHan.png)

> Si quieres agregar más imágenes después, puedes crear una carpeta `images/` y referenciarlas así:
> `![Descripción](images/mi-imagen.png)`

---

## Autor
Código hecho por **Itzel Monroy**.

---
