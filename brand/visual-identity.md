# Guía de Identidad Visual de Bakan

## Visión General de la Marca
Bakan es una plataforma de pago seguro (escrow) que actúa como intermediario confiable entre compradores y vendedores en redes sociales. Nuestra promesa es eliminar la desconfianza de las transacciones persona a persona con una experiencia clara, moderna y empática.

**Personalidad de la marca**: segura, transparente, moderna, empática y resolutiva.

**Tono de voz**: directo, cálido y tranquilizador. Comunicamos con claridad y sin tecnicismos innecesarios.

---

## Paleta Cromática Corporativa
| Uso | Nombre | Hex | Descripción |
| --- | --- | --- | --- |
| Primario (CTAs y elementos de marca) | Azul Profundo | `#1D16F2` | Genera confianza, soporte para acciones de alto impacto. |
| Secundario (Botones secundarios, enlaces) | Azul Brillante | `#0554F2` | Resalta interacciones secundarias manteniendo coherencia. |
| Acento (Fondos sutiles, iconos) | Azul Claro | `#056CF2` | Añade frescura y profundidad a superficies suaves. |
| Fondo principal | Gris Suave | `#F2F2F2` | Descanso visual, se combina con blancos para jerarquía. |
| Base neutra | Blanco | `#FFFFFF` | Espacio negativo, base de tarjetas, componentes. |
| Éxito y confianza | Verde Éxito | `#27AE60` | Confirmaciones, estados positivos, mensajes de garantía. |
| Texto principal | Negro Profundo | `#1A1A1A` | Lectura óptima en cuerpos de texto y titulares. |

**Reglas de color**
- Mantener contraste mínimo AA (WCAG 2.1) con textos sobre fondos claros. Ejemplo: texto `#1A1A1A` sobre `#FFFFFF` o `#F2F2F2`.
- Reservar `#1D16F2` para CTA primario, enlaces clave y elementos de identidad (logotipo, highlights).
- `#27AE60` únicamente para estados de confirmación y mensajes de seguridad. Nunca usar como color de CTA principal.
- Utilizar degradados suaves entre `#0554F2` y `#056CF2` solo para fondos hero o gráficos decorativos.

---

## Tipografía
- **Primaria:** Inter (regular, medium, semibold, bold).
- **Alternativa:** Poppins cuando Inter no esté disponible.

**Jerarquía recomendada**
- H1: Inter Bold 48px / tracking -1% / color `#1A1A1A`.
- H2: Inter Semibold 32px / tracking -0.5% / color `#1A1A1A`.
- H3: Inter Medium 24px / color `#1A1A1A`.
- Body Large: Inter Regular 18px / interlineado 150% / color `#1A1A1A`.
- Body Base: Inter Regular 16px / interlineado 150% / color `#1A1A1A`.
- Labels & Buttons: Inter SemiBold 16px / uppercase opcional con tracking +2%.
- Captions & ayudas visuales: Inter Regular 14px / color `#0554F2` para enlaces, `#6E6E6E` (derivado de `#1A1A1A` al 60% de opacidad) para anotaciones.

**Buenas prácticas**
- Evitar más de dos pesos tipográficos en un mismo componente.
- Usar mayúsculas solo en botones principales y etiquetas pequeñas.

---

## Estilo Visual
- **Estética:** Flat 2.0 con sombras suaves (0 12px 32px rgba(5, 84, 242, 0.12)) y bordes redondeados (16px estándar).
- **Iconografía:** Preferencia por iconos claymorphism con luces suaves desde la esquina superior izquierda. Alternativamente, iconos duotone con líneas de 3px usando `#1D16F2` y `#0554F2`.
- **Ilustraciones:** Personajes simplificados y geométricos que representen compradores y vendedores diversos. Integrar elementos de pago, escudos, candados suaves, y trazos fluidos.
- **Fotografía:** Cuando se use, aplicar overlay azul (`rgba(29, 22, 242, 0.6)`) para mantener consistencia.

---

## Componentes UI Clave
### Barra de navegación
- Fondo `#FFFFFF` con sombra sutil (0 8px 24px rgba(5, 108, 242, 0.08)).
- Logotipo a la izquierda, CTA "Crear transacción segura" (`#1D16F2`) a la derecha.
- Links secundarios en `#0554F2` con estado hover `#056CF2`.

### Tarjetas de Resumen de Transacción
- Fondo `#FFFFFF`, borde 1px `rgba(5, 108, 242, 0.12)`, radio 24px.
- Icono clay central sobre círculo en `#F2F2F2`.
- Título H3, monto en Inter Semibold 20px, badge de estado en `#27AE60` (texto en blanco) o `#1D16F2` para "En revisión".

### Botones
| Tipo | Fondo | Texto | Borde | Hover |
| --- | --- | --- | --- | --- |
| Primario | `#1D16F2` | `#FFFFFF` | none | `#0554F2` | 
| Secundario | `#FFFFFF` | `#0554F2` | 2px `#0554F2` | `#F2F6FF` |
| Fantasma | transparente | `#0554F2` | none | `rgba(5, 84, 242, 0.16)` |
| Éxito | `#27AE60` | `#FFFFFF` | none | `#219653` |

### Formularios
- Campos con fondo `#FFFFFF`, borde 1px `rgba(5, 84, 242, 0.12)`, radio 12px.
- Estado foco: borde 2px `#0554F2`, sombra interna suave.
- Mensajes de error en `#D14343`, texto 14px, icono de alerta en estilo duotone.

### Modales
- Fondo `#FFFFFF`, radio 32px, padding 48px.
- Header con icono clay, contenido centrado.
- CTA principal `#1D16F2`, secundario `#FFFFFF` borde `#0554F2`.

---

## Sistema de Iconos
- Construidos en un grid de 24x24 px.
- Sombras suaves (0 8px 16px rgba(5, 84, 242, 0.15)).
- Iluminación desde arriba izquierda. Destacados en `#FFFFFF` y sombras en `rgba(26, 26, 26, 0.12)`.
- Mantener coherencia en grosor y curvatura.

---

## Layout & Espaciado
- Grilla base de 8px.
- Secciones clave con padding vertical 96px en desktop, 64px en mobile.
- Hero principal dividido en 12 columnas con imagen/ilustración a la derecha y texto + CTA a la izquierda.
- Uso extensivo de espacio negativo; mantener densidad mínima de 40% whitespace en hero y testimoniales.

---

## Microinteracciones
- Transiciones suaves de 200ms (cubic-bezier 0.4, 0, 0.2, 1).
- Feedback inmediato en estados de carga: barras progresivas en `#0554F2` sobre fondo `#F2F2F2`.
- Confirmaciones muestran card con icono check en `#27AE60` y texto "Tu pago está protegido".

---

## Sonido y Haptics (opcional móvil)
- Vibración suave (50ms) al completar transacción.
- Sonido de confirmación minimal en nota D mayor, volumen bajo.

---

## Accesibilidad
- Contraste mínimo AA en todos los textos.
- Tamaño de toque mínimo 48px.
- Indicadores de foco visibles: contorno `#056CF2` 2px.
- Textos alternativos en imágenes e iconos clave.

---

## Aplicaciones Clave
### Landing Page
1. Hero con título "Protege tus compras en redes sociales" (H1) + CTA primario.
2. Paso a paso en 3 tarjetas con iconos clay.
3. Testimonios con avatars circulares y fondo `#FFFFFF`.
4. Sección FAQ sobre `#F2F2F2` con acordeones `#FFFFFF`.

### App Web
- Dashboard con métricas destacadas en tarjetas minimalistas.
- Historial de transacciones con badges por estado.
- Panel lateral con accesos rápidos.

### Redes Sociales
- Templates cuadrado (1080x1080) y story (1080x1920).
- Uso de tipografía Bold para titulares y duotone azul para iconos.

### Emailing
- Header azul `#1D16F2`, contenido sobre blanco.
- Botones de acción en `#0554F2`.
- Sección de seguridad con icono de escudo en `#27AE60`.

---

## Mensajería Clave
- CTA primario: "Protege tu compra ahora".
- Beneficio principal: "Tu dinero se libera solo cuando todo esté bien".
- Copy tranquilizador: "Somos tu intermediario confiable en Facebook, Instagram y WhatsApp".

---

## Checklist de Implementación Rápida
1. Aplicar paleta azul + blancos, reservando verde solo para estados positivos.
2. Usar Inter/Poppins, manteniendo jerarquía clara y legible.
3. Iconos clay o duotone coherentes con sombras suaves.
4. Componentes con bordes redondeados y sombras moderadas.
5. Priorizar accesibilidad: contraste, foco visible, feedback inmediato.

---

## Recursos Sugeridos
- Librería de iconos: [Phosphor Icons](https://phosphoricons.com/) (adaptar grosor a 3px).
- Mockups 3D suaves: [LS Graphics Clay Mockups](https://www.ls.graphics/freebies).
- Tipografía Inter: [Google Fonts](https://fonts.google.com/specimen/Inter).

