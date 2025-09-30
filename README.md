# 🚀 Formulario de Selección de Astronautas

## 🪐 Contexto
La **Agencia Espacial Internacional** busca valientes candidatos para la **Misión Marte 2030**.  
Este proyecto consiste en un **formulario web interactivo** que valida los datos de los aspirantes, mostrando mensajes de error personalizados y cambiando el estilo visual de los campos según su validez.


## 📋 Requisitos del Formulario

Cada campo tiene reglas de validación estrictas:

1. **Nombre completo** (texto)  
   - Obligatorio.  
   - Al menos 3 caracteres.  

2. **Correo de contacto** (email)  
   - Obligatorio.  
   - Formato válido.  

3. **Código de seguridad** (password)  
   - Obligatorio.  
   - Al menos 8 caracteres.  
   - Debe incluir una **mayúscula**, un **número** y un **símbolo especial** (`!@#$%&*`).  

4. **Edad** (number)  
   - Obligatoria.  
   - Entre **25 y 50 años**.  

5. **Especialidad** (radio)  
   - Opciones: **Piloto, Ingeniero, Médico, Científico**.  
   - Obligatorio seleccionar una.  

6. **Planeta de origen** (select)  
   - Obligatorio.  
   - No se acepta la opción vacía.  

7. **Fecha de disponibilidad para despegar** (date)  
   - Obligatoria.  
   - Debe ser una **fecha futura**.  

8. **Nivel de condición física** (range 1–10)  
   - Obligatorio.  
   - Valor mínimo aceptado: **7**.  

9. **Expediente médico** (file)  
   - Obligatorio.  
   - Debe ser un archivo en formato **PDF**.  

10. **Comentarios adicionales** (textarea)  
    - Opcional.  
    - Si se completa, debe tener **mínimo 10 caracteres**.  

11. **Acepto los riesgos de la misión** (checkbox)  
    - Obligatorio.  


## 🎨 Estilos y Validaciones

- **Campos válidos:** borde y fondo en **verde**.  
- **Campos inválidos:** borde y fondo en **rojo**.  
- **Mensajes de error temáticos**, por ejemplo:  
  - "Acceso denegado"  
  - "Selecciona tu planeta de origen"  

✅ Si todos los campos son correctos, se muestra el mensaje:  
**"Todo ha sido correcto."**


## ⚙️ Tecnologías sugeridas

- **HTML5** → estructura del formulario.  
- **CSS3** → estilos dinámicos (verde/rojo).  
- **JavaScript** → validaciones personalizadas en tiempo real.  


## 🚀 Cómo probarlo

1. Clona este repositorio o descarga los archivos.  
2. Abre el archivo `index.html` en tu navegador.  
3. Completa el formulario con distintos valores para comprobar las validaciones.  
## ✨ Autor
Ejercicio creado como práctica de **formularios web con validación**.  
