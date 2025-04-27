# Carbono Secundario - Aplicación Educativa Interactiva

![Captura de pantalla de la aplicación](https://ejemplo.com/ruta-a-imagen.jpg)

## 📚 Descripción

Aplicación web interactiva para el estudio de los carbonos secundarios en química orgánica, con visualizaciones 3D, gráficos comparativos y contenido educativo completo.

## 🚀 Características principales

- 🌐 **Visualización 3D interactiva** de estructuras moleculares
- 📊 **Gráficos comparativos** de propiedades físico-químicas
- 🔍 **6 secciones temáticas** organizadas
- 📱 **Diseño completamente responsivo**
- ♿ **Accesibilidad mejorada**

## 🛠 Tecnologías utilizadas

| Tecnología | Uso |
|------------|-----|
| HTML5 | Estructura semántica |
| CSS3 | Estilos y diseño responsive |
| JavaScript | Lógica e interacciones |
| Three.js | Visualización 3D |
| Chart.js | Gráficos y datos |
| Font Awesome | Iconografía |

## 🏁 Empezar

### Requisitos
- Navegador moderno (Chrome, Firefox, Edge, Safari)
- Conexión a Internet (para CDNs)

### Instalación
```bash
git clone https://github.com/tu-usuario/carbono-secundario.git
cd carbono-secundario




# Manual de Uso: Aplicación de Estudio del Carbono Secundario

## 🌟 Introducción
Esta aplicación web interactiva está diseñada para facilitar el aprendizaje sobre los carbonos secundarios en química orgánica mediante visualizaciones 3D, gráficos comparativos y contenido educativo estructurado.

## 🖥 Interfaz Principal
![Diagrama de interfaz](https://ejemplo.com/interfaz.jpg)

La aplicación tiene dos áreas principales:
1. **Panel de navegación izquierdo**: Menú con 6 secciones temáticas
2. **Área de contenido derecho**: Muestra dinámicamente la sección seleccionada

## 🧭 Navegación Básica
| Acción | Método |
|--------|--------|
| Cambiar sección | Clic en botones del menú |
| Acceso rápido | Teclas 1-6 (1=Definición, 2=Estructura, etc.) |
| Scroll vertical | Rueda del mouse o gesto táctil |

## 🕹 Modelo 3D Interactivo
**Controles principales**:

**Atajos de teclado**:
- `R`: Resetear vista
- `+/-`: Control de zoom

## 📊 Uso de Gráficos
El gráfico radar compara propiedades entre carbonos:

![Leyenda gráfico](https://ejemplo.com/leyenda-grafico.jpg)

1. **Interpretación**:
   - Cada eje representa una propiedad diferente
   - Área mayor = Mayor intensidad de propiedades

2. **Interacción**:
   - Hover sobre puntos muestra valores exactos
   - Click en leyendas muestra/oculta categorías

## 📱 Uso en Móviles
### Diferencias clave:
- Menú se convierte en acordeón superior
- Gestos táctiles para modelo 3D:
  - Un dedo: Rotar
  - Dos dedos: Zoom/pan

## 🛠 Solución de Problemas
| Problema | Solución |
|----------|----------|
| Modelo no carga | 1. Verificar WebGL (webglreport.com)<br>2. Actualizar navegador |
| Gráficos rotos | 1. Desactivar bloqueadores<br>2. Recargar sin cache (Ctrl+F5) |
| Lento en móviles | 1. Reducir zoom en modelos<br>2. Usar modo avión para solo contenido |

## 💡 Consejos Avanzados
1. **Modo pantalla completa**: F11 durante visualización 3D
2. **Exportar datos**: Ctrl+P para tablas comparativas
3. **Navegación rápida**: 
   ```javascript
   // En consola del navegador
   mostrarSeccion('aplicaciones'); // Salta a sección

