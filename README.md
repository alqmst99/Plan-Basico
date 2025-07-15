** Proyecto: Landing Page – Plan Básico**_
** Desarrollado por**: FSTail Solution**
** Repositorio**: alqmst99.github.io/Plan-Basico**

##Objetivo
Esta landing está pensada para brindar presencia online rápida y segura a emprendedores, marcas personales o profesionales independientes. Aunque es un sitio estático, se aplicaron medidas esenciales para garantizar una experiencia segura para el usuario y proteger la integridad del sitio.

**Diseñar e implementar una landing **liviana, accesible y responsive** que:
- Muestre quién sos y qué hacés
- Permita contactarte directamente
- Funcione en celulares, tablets y PCs
- Cargue rápido y sin distracciones

---

## Tecnologías utilizadas

- **HTML5**
- **CSS3**
- [RemixIcon](https://remixicon.com/) vía CDN (jsDelivr)
- Hosting gratuito y seguro con **GitHub Pages**

---

## Estructura del proyecto

Plan-Basico/
├── index.html
├── style.css
├── /Assets
│ └── /img
│ └── logo.jpg
├── README.md

---

## Contenido del sitio

### Header
Menú fijo con scroll suave a secciones internas.

### Banner (Inicio)
Llamado claro con texto promocional y botón directo a WhatsApp.

### Servicios
Tres tarjetas que explican los pilares del plan básico:
- Desarrollo Web Personalizado
- Presencia Digital Estratégica
- Tu Web, Tu Estilo, Tu Ritmo

### 🔹 Contacto
Íconos directos a WhatsApp e Instagram.

### Footer
Derechos reservados y accesos a medios de contacto.

---

##  Responsividad

El sitio es totalmente responsive y se adapta a:
-  Escritorio
-  Celulares
-  Tablets

>  Adaptación garantizada hasta resolución mínima de 320px.

---

## Seguridad Aplicada
| Medida                              | Detalles                                                                                                                                                            |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **HTTPS activo**                    | El sitio está alojado en GitHub Pages, que fuerza el uso de HTTPS cifrado. Esto protege la navegación y mejora el SEO.                                              |
| **Enlaces externos protegidos**     | Todos los `<a target="_blank">` usan `rel="noopener noreferrer"` para prevenir ataques de [tabnabbing](https://owasp.org/www-community/attacks/Reverse_Tabnabbing). |
| **Sin formularios inseguros**       | No se incluyen formularios de contacto que puedan ser vulnerables a ataques como XSS o spam.                                                                        |
| **Eliminación de correos visibles** | El email de contacto no se incluye en el HTML para evitar que bots lo capturen y lo usen para spam. Se prioriza el contacto por WhatsApp.                           |
| **Sin scripts de terceros**         | No se utilizan scripts externos que puedan generar vulnerabilidades. Todo el contenido es estático y local, salvo los íconos.                                       |
| **CDN confiable**                   | Se utiliza jsDelivr para cargar RemixIcon de forma segura. Se mantiene para performance, aunque puede reemplazarse por íconos locales si se desea máxima seguridad. |
| **Código limpio y validado**        | Se corrigieron etiquetas mal cerradas para asegurar una estructura HTML semántica y libre de errores.                                                               |


### Alcance de seguridad
Este plan no incluye formularios, backends, bases de datos ni sistemas de autenticación, por lo tanto:

No requiere medidas de protección contra inyecciones, CSRF o SQLi.

No necesita captcha ni validaciones de input.

Recomendaciones futuras (para planes superiores)
Uso de formularios con validación frontend + backend.

Integración de CAPTCHA invisible.

Protección avanzada mediante políticas CSP, X-Frame-Options, etc.

Política de privacidad y términos legales.

### Contacto seguro
El contacto se establece exclusivamente mediante:

**WhatsApp Directo**: Click para abrir chat

**Instagram**: @fstailsolution

**Licencia y propiedad**
Este sitio fue desarrollado por FSTail Solution. Todos los derechos reservados.
El contenido gráfico, textual y funcional está protegido.
Su modificación sin consentimiento puede constituir una infracción.
