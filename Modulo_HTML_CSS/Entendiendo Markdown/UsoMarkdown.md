# 📝 Estructuras Comunes en Markdown

## 1. Títulos y Subtítulos (Cabezeras)

 ###### Markdown usa *#* para representar niveles de títulos. Puedes tener hasta 6 niveles.


```html
<div style="border:1px solid #ccc; border-radius:5px; width: fit-content; font-family: monospace;">

  <div style="background: #ddd; padding: 4px 10px; border-bottom: 1px solid #ccc;">
    markdown
  </div>

  <pre style="margin: 0; padding: 10px;">
      
# Título Principal (H1)
## Subtítulo (H2)
### Sección (H3)
#### Subsección (H4)
##### Detalle (H5)
###### Nota (H6)
      
  </pre>

</div>

```

###### Ideal para estructurar el documento jerárquicamente.


---


## 2. 🖋️ Estilo de texto

```html
<div style="border:1px solid #ccc; border-radius:5px; width: fit-content; font-family: monospace;">

  <div style="background: #ddd; padding: 4px 10px; border-bottom: 1px solid #ccc;">
    markdown
  </div>

  <pre style="margin: 0; padding: 10px;">
      
*Texto en cursiva*  
**Texto en negrita**  
***Texto en cursiva y negrita***  
~~Texto tachado~~
      
  </pre>

</div>

```

###### **Uso**: Para resaltar partes importantes o indicar algo eliminado/corregido.


---


## 3. ✅ Listas
### 🔹Listas con viñetas

```html
<div style="border:1px solid #ccc; border-radius:5px; width: fit-content; font-family: monospace;">

  <div style="background: #ddd; padding: 4px 10px; border-bottom: 1px solid #ccc;">
    markdown
  </div>

  <pre style="margin: 0; padding: 10px;">
      
- Elemento 1
- Elemento 2
  - Sub-elemento
      
  </pre>

</div>


```


### 🔹Listas numeradas

```html
<div style="border:1px solid #ccc; border-radius:5px; width: fit-content; font-family: monospace;">

  <div style="background: #ddd; padding: 4px 10px; border-bottom: 1px solid #ccc;">
    markdown
  </div>

  <pre style="margin: 0; padding: 10px;">
      
1. Paso uno
2. Paso dos
   1. Subpaso
      
  </pre>

</div>

```

###### **Uso**: Para enumerar o listar elementos u órdenes.


---


## 4. 💬 Citas y Entradillas con Bloques 

```html
<div style="border:1px solid #ccc; border-radius:5px; width: fit-content; font-family: monospace;">

  <div style="background: #ddd; padding: 4px 10px; border-bottom: 1px solid #ccc;">
    markdown
  </div>

  <pre style="margin: 0; padding: 10px;">
      
> Esta es una cita textual o una advertencia general.
> Puede tener varias líneas.
      
  </pre>

</div>

```

###### **Uso**: Para agregar comentarios, citas o instrucciones importantes.


---


## 5. 💻 Bloques de Código

### 📦 En línea:

```html
<div style="border:1px solid #ccc; border-radius:5px; width: fit-content; font-family: monospace;">

  <div style="background: #ddd; padding: 4px 10px; border-bottom: 1px solid #ccc;">
    markdown
  </div>

  <pre style="margin: 0; padding: 10px;">
      
Usa la función `getCafeById()` para obtener un café específico.
      
  </pre>

</div>

```

## 📋 En bloque:

```html
<div style="border:1px solid #ccc; border-radius:5px; width: fit-content; font-family: monospace;">

  <div style="background: #ddd; padding: 4px 10px; border-bottom: 1px solid #ccc;">
    markdown
  </div>

  <pre style="margin: 0; padding: 10px;">
      
```java
public Cafe getCafeById(int id) {
return cafeRepository.findById(id);
      
}
```  </pre>

</div>

```

###### **Uso**: Para insertar código fuente o comandos.
###### Soporta lenguajes como: **java**, **javascript**, **bash**, **json**, **python**, **html**, etc.


---


## 6. 📊 Tablas

```html
<div style="border:1px solid #ccc; border-radius:5px; width: fit-content; font-family: monospace;">

  <div style="background: #ddd; padding: 4px 10px; border-bottom: 1px solid #ccc;">
    markdown
  </div>

  <pre style="margin: 0; padding: 10px;">
      
| ID | Nombre   | Precio |
|----|----------|--------|
| 1  | Espresso | 2.50   |
| 2  | Latte    | 3.00   |
      
```  </pre>

</div>

```

###### **Uso**: Para presentar datos tabulados.


--- 


## 7. 🔗 Enlaces y Referencias

```html
<div style="border:1px solid #ccc; border-radius:5px; width: fit-content; font-family: monospace;">

  <div style="background: #ddd; padding: 4px 10px; border-bottom: 1px solid #ccc;">
    markdown
  </div>

  <pre style="margin: 0; padding: 10px;">
      
[Ir a Google](https://www.google.com)
[Ver API](#título-principal)
      
```  </pre>

</div>

```

###### **Uso**: Para enlazar documentos externos o secciones internas.


---


## 8. 🖼️  Imágenes

```html
<div style="border:1px solid #ccc; border-radius:5px; width: fit-content; font-family: monospace;">

  <div style="background: #ddd; padding: 4px 10px; border-bottom: 1px solid #ccc;">
    markdown
  </div>

  <pre style="margin: 0; padding: 10px;">
      
![Texto alternativo](https://example.com/imagen.png)
      
```  </pre>

</div>

```

###### **Uso**: Para ilustrar con imágenes (diagramas, logos, ejemplos, etc).


---


## 9. 🧱 Separadores

```html
<div style="border:1px solid #ccc; border-radius:5px; width: fit-content; font-family: monospace;">

  <div style="background: #ddd; padding: 4px 10px; border-bottom: 1px solid #ccc;">
    markdown
  </div>

  <pre style="margin: 0; padding: 10px;">
      
---
      
```  </pre>

</div>

```

###### **Uso**: Para dividir secciones o dar un respiro visual.


---


## 10. ✅ Checklist (Tareas)

```html
<div style="border:1px solid #ccc; border-radius:5px; width: fit-content; font-family: monospace;">

  <div style="background: #ddd; padding: 4px 10px; border-bottom: 1px solid #ccc;">
    markdown
  </div>

  <pre style="margin: 0; padding: 10px;">
      
- [x] Conectar a la base de datos
- [ ] Crear documentación Markdown
- [ ] Validar API
      
```  </pre>

</div>

```

###### **Uso**: Ideal para seguimiento de tareas o estados.


---


## 📁 Ejemplo de archivo Markdown generado desde API

```html
<div style="border:1px solid #ccc; border-radius:5px; width: fit-content; font-family: monospace;">

  <div style="background: #ddd; padding: 4px 10px; border-bottom: 1px solid #ccc;">
    markdown
  </div>

  <pre style="margin: 0; padding: 10px;">
      
# Documentación de la API de Café ☕

## 📌 Endpoints

### 🔹 GET /cafes
> Obtiene todos los cafés registrados en el sistema.

### 🔹 POST /cafes
> Crea un nuevo café. Asegúrate de enviar un objeto válido.

## 📦 Modelo de Datos

```json
{
  "id": 1,
  "nombre": "Espresso",
  "origen": "Colombia",
  "precio": 2.5
}
      
```  </pre>

</div>

```

### ✅ Tareas pendientes
- Conectar base de datos [si]
- Agregar validaciones [no]
- Publicar documentación [no]


---


## 11. ☕ Emojis (GitHub, VSCode)

###### Puedes usar emojis con dos puntos:

```html
<div style="border:1px solid #ccc; border-radius:5px; width: fit-content; font-family: monospace;">

  <div style="background: #ddd; padding: 4px 10px; border-bottom: 1px solid #ccc;">
    markdown
  </div>

  <pre style="margin: 0; padding: 10px;">
      
:smile: :rocket: :coffee: :warning: :x:
      
```  </pre>

</div>

```

###### Ejemplo visual: 😄 🚀 ☕ ⚠️ ❌


---


## 12. 🧪 HTML embebido

###### Markdown permite HTML en línea: 

```html
<div style="border:1px solid #ccc; border-radius:5px; width: fit-content; font-family: monospace;">

  <div style="background: #ddd; padding: 4px 10px; border-bottom: 1px solid #ccc;">
    markdown
  </div>

  <pre style="margin: 0; padding: 10px;">
      
<b>Texto en negrita</b>
<i>Texto en cursiva</i>
<mark>Texto resaltado</mark>
<sup>superíndice</sup> y <sub>subíndice</sub>
      
```  </pre>

</div>

```

###### ⚠️ Algunos renderizadores (como GitHub) limitan etiquetas HTML por seguridad.


---


## 13. 🧭 Índices simulados (usando enlaces internos)

```html
<div style="border:1px solid #ccc; border-radius:5px; width: fit-content; font-family: monospace;">

  <div style="background: #ddd; padding: 4px 10px; border-bottom: 1px solid #ccc;">
    markdown
  </div>

  <pre style="margin: 0; padding: 10px;">
      
- [1. Títulos](#1--encabezados-títulos)
- [2. Estilo](#2--estilo-de-texto)
      
```  </pre>

</div>

```

###### Al hacer clic en el enlace, te lleva a esa sección del documento.


---


## 14. 🔁 Escapando caracteres especiales

###### Para mostrar símbolos especiales:

```html
<div style="border:1px solid #ccc; border-radius:5px; width: fit-content; font-family: monospace;">

  <div style="background: #ddd; padding: 4px 10px; border-bottom: 1px solid #ccc;">
    markdown
  </div>

  <pre style="margin: 0; padding: 10px;">
      
\* no será cursiva \*  
\# no será un título  
\` no será código
      
```  </pre>

</div>

```


---


## 15. 🧩 Comentarios invisibles (no visibles en el render)

```html
<div style="border:1px solid #ccc; border-radius:5px; width: fit-content; font-family: monospace;">

  <div style="background: #ddd; padding: 4px 10px; border-bottom: 1px solid #ccc;">
    markdown
  </div>

  <pre style="margin: 0; padding: 10px;">
      
<!-- Este comentario no se verá en la vista final -->
      
```  </pre>

</div>

```


---


## 16. 📦 Inclusión de archivos (GitHub-flavored Markdown)

```html
<div style="border:1px solid #ccc; border-radius:5px; width: fit-content; font-family: monospace;">

  <div style="background: #ddd; padding: 4px 10px; border-bottom: 1px solid #ccc;">
    markdown
  </div>

  <pre style="margin: 0; padding: 10px;">
      
![Diagrama](./img/diagrama.png)  
[Ver otro archivo](./otro.md)
      
```  </pre>

</div>

```

###### Sólo funciona en visores con acceso a esos archivos (repositorios, etc).


---


## 17. 📜 Citas literales y anidación

```html
<div style="border:1px solid #ccc; border-radius:5px; width: fit-content; font-family: monospace;">

  <div style="background: #ddd; padding: 4px 10px; border-bottom: 1px solid #ccc;">
    markdown
  </div>

  <pre style="margin: 0; padding: 10px;">
      
> Primer nivel de cita
>> Segundo nivel
>>> Tercer nivel
      
```  </pre>

</div>

```


---


## 18. ⌨️ Atajo de teclado

###### Existen un gran número de atajos de teclado afines a todos los programas. Son los siguientes:
```html
<div style="border:1px solid #ccc; border-radius:5px; width: fit-content; font-family: monospace;">

  <div style="background: #ddd; padding: 4px 10px; border-bottom: 1px solid #ccc;">
    markdown
  </div>

  <pre style="margin: 0; padding: 10px;">

<!-- 📋 Funciones básicas -->
Presiona `Ctrl + C` para copiar.
Presiona `Ctrl + V` para pegar.
Presiona Ctrl + Z para deshacer.
Presiona Ctrl + Y para rehacer.
Presiona Ctrl + A para seleccionar todo.
Presiona Ctrl + S para guardar.
Presiona Ctrl + P para imprimir.

<!-- 🗂 Navegación y ventanas  -->
Presiona `Alt + Tab` para cambiar entre ventanas abiertas.
Presiona `Alt + F4` para cerrar la ventana activa.
Presiona `Windows + D` para mostrar el escritorio.
Presiona `Windows + E` para abrir el explorador de archivos.
Presiona `Windows + L` para bloquear el equipo.
Presiona `Windows + R` para abrir la ventana Ejecutar.
Presiona `Ctrl + Esc` para abrir el menú de inicio.
Presiona `Windows + Tab` para ver todas las ventanas abiertas (Vista de tareas).

<!-- 📝 Edición de texto  --> 
Presiona `Ctrl + B` para poner en negrita.
Presiona `Ctrl + I` para poner en cursiva.
Presiona `Ctrl + U` para subrayar.
Presiona `Ctrl + ←` para mover el cursor una palabra a la izquierda.
Presiona `Ctrl + →` para mover el cursor una palabra a la derecha.
Presiona `Ctrl + Shift + ↑` para seleccionar líneas hacia arriba.
Presiona `Ctrl + Shift + ↓` para seleccionar líneas hacia abajo.

<!-- 🔎 Búsqueda y navegación  --> 
Presiona `Ctrl + F` para buscar.
Presiona `Ctrl + H` para reemplazar.
Presiona `Ctrl + G` para ir a una línea específica (en editores de texto).
Presiona `F3` para buscar siguiente coincidencia.
Presiona `Shift + F3` para buscar coincidencia anterior.

<!-- 🌐 Navegadores web --> 
Presiona `Ctrl + T` para abrir una nueva pestaña.
Presiona `Ctrl + W` para cerrar la pestaña actual.
Presiona `Ctrl + Shift + T` para reabrir la última pestaña cerrada.
Presiona `Ctrl + Tab` para cambiar a la siguiente pestaña.
Presiona `Ctrl + Shift + Tab` para cambiar a la pestaña anterior.
Presiona `Ctrl + L` para seleccionar la barra de direcciones.
Presiona `F5` para recargar la página.
Presiona `Ctrl + F5` para recargar sin usar caché.

<!-- 💻 Consola y terminal -->   
Presiona `Ctrl + Shift + C` para copiar en terminal.
Presiona `Ctrl + Shift + V` para pegar en terminal.
Presiona `Ctrl + L` para limpiar la consola.
Presiona `Ctrl + D` para cerrar sesión (en algunas terminales).
Presiona `Ctrl + A` para ir al inicio de la línea.
Presiona `Ctrl + E` para ir al final de la línea.

<!-- 🖼️ Capturas de pantalla -->   
 Presiona `PrtSc` para capturar toda la pantalla.
Presiona `Alt + PrtSc` para capturar la ventana activa.
Presiona `Windows + Shift + S` para capturar una parte de la pantalla.
Presiona `Windows + PrtSc` para guardar automáticamente la captura.
      
      
```  </pre>

</div>

```

### 🧠 18.1 Atajos de teclado específicos (adicionales por programa)

###### Cada programa (como Word, Photoshop, VS Code, Excel, etc.) tiene sus propios atajos además de los estándar del sistema operativo. 
###### Aquí se muestran algunos de ellos de forma específica a cada programa en unión a todos los atajos anteriores afines a todos los programas.

```html
<div style="border:1px solid #ccc; border-radius:5px; width: fit-content; font-family: monospace;">

  <div style="background: #ddd; padding: 4px 10px; border-bottom: 1px solid #ccc;">
    markdown
  </div>

  <pre style="margin: 0; padding: 10px;">

<!-- 📝 En Microsoft Word -->
Presiona `Ctrl + Enter` para insertar un salto de página.
Presiona `Ctrl + 1` para interlineado simple.
Presiona `Ctrl + 2` para interlineado doble.

<!-- 🧮 En Excel  -->
Presiona `Ctrl + Shift + $` para aplicar formato de moneda.
Presiona `F2` para editar la celda activa.
Presiona `Ctrl + ;` para insertar la fecha actual.

<!-- 🧑‍💻 En Visual Studio Code  --> 
Presiona `Ctrl + ñ` para abrir la terminal integrada.
Presiona `Ctrl + /` para comentar una línea.
Presiona `Ctrl + P` para buscar archivos rápidamente.

<!-- 📷 En Photoshop  --> 
Presiona `Ctrl + J` para duplicar la capa.
Presiona `Ctrl + T` para transformación libre.
Presiona `Ctrl + Alt + Z` para deshacer múltiples veces.

      
```  </pre>

</div>

```


### 18.3 Atajos de teclado para GitHub 

###### Estos atajos van a funcionar cuando esté en [Haz clic aquí] (github.com)