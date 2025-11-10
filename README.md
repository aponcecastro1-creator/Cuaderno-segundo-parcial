<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cuaderno Digital Ecommerce - IPN ESCA</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Playfair+Display:wght@700&display=swap');

        body {
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        .page {
            width: 21cm; /* A4 width */
            min-height: 29.7cm; /* A4 height */
            margin: 1cm auto;
            background: beige; /* Changed to beige */
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            padding: 2cm;
            box-sizing: border-box;
            page-break-after: always; /* Force page break after each .page */
        }
        .page:last-of-type {
            page-break-after: avoid; /* No page break after the last page */
        }
        h1, h2, h3, h4 {
            font-family: 'Playfair Display', serif;
            color: #000; /* Titles are now black */
            margin-bottom: 0.5em;
        }
        h1 { font-size: 2.5em; text-align: center; }
        h2 { font-size: 2em; border-bottom: 2px solid #ccc; padding-bottom: 0.3em; margin-top: 1.5em; }
        h3 { font-size: 1.5em; margin-top: 1em; }
        h4 { font-size: 1.2em; margin-top: 0.8em; }
        p, ul, ol, table {
            margin-bottom: 1em;
            font-size: 0.95em;
        }
        ul {
            list-style-type: disc;
            margin-left: 1.5em;
        }
        ol {
            list-style-type: decimal;
            margin-left: 1.5em;
        }
        .cover-page {
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            align-items: center;
            text-align: center;
            height: 100%;
            padding-top: 5cm;
            padding-bottom: 5cm;
        }
        .cover-page .logos {
            display: flex;
            justify-content: space-between;
            width: 100%;
            margin-bottom: 3cm;
        }
        .cover-page .logos img {
            width: 150px; /* Adjust as needed */
            height: auto;
        }
        .cover-page .main-title {
            font-size: 3.5em;
            font-family: 'Playfair Display', serif;
            color: #000; /* Main title black */
            margin-bottom: 0.5em;
        }
        .cover-page .subtitle {
            font-size: 1.8em;
            color: #000; /* Subtitle black */
            margin-bottom: 0.3em;
        }
        .cover-page .author {
            font-size: 1.3em;
            color: #555;
            margin-top: 2cm;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 1.5em 0;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
            font-weight: bold;
            color: #333;
        }
        tr:nth-child(even) {
            background-color: #f9f9f9;
        }
        .example {
            font-style: italic;
            color: #666;
            margin-left: 1em;
            font-size: 0.9em;
        }
        .highlight {
            font-weight: bold;
            color: #e74c3c; /* Keep highlights distinct if needed */
        }
        .reference-list {
            list-style-type: none;
            padding-left: 0;
            font-size: 0.85em;
            color: #7f8c8d;
            margin-top: 1.5em;
        }
        .reference-list li {
            margin-bottom: 0.5em;
            text-indent: -2em; /* Hanging indent */
            padding-left: 2em;
        }

        /* Adjusted background headers for translated titles */
        .background-image-header {
            background-image: url('https://via.placeholder.com/1200x200/2c3e50/ffffff?text=Fondo+XaaS'); /* Placeholder image */
            background-size: cover;
            background-position: center;
            color: white;
            padding: 3em 0;
            text-align: center;
            margin-bottom: 2em;
        }
        .background-image-header h1 {
            color: white;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }
        .background-image-header p {
            color: white;
            font-size: 1.2em;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.5);
        }
        /* Specific header for Responsive vs Adaptive */
        .header-responsive-adaptive {
            background-image: url('https://via.placeholder.com/1200x200/8e44ad/ffffff?text=Diseño+Web+Adaptativo+vs+Responsivo'); /* Placeholder image */
            background-size: cover;
            background-position: center;
            color: white;
            padding: 3em 0;
            text-align: center;
            margin-bottom: 2em;
        }
        .header-responsive-adaptive h1 {
            color: white;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
            font-size: 2.8em;
        }
        .header-responsive-adaptive p {
            color: white;
            font-size: 1.1em;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.5);
        }

        /* Adjustments for images from OCR */
        .ocr-image {
            width: 150px; /* Example size, adjust as needed */
            height: auto;
            vertical-align: middle;
        }
        .cover-ipn-logo {
            float: left;
            margin-right: 20px;
        }
        .cover-esca-logo {
            float: right;
            margin-left: 20px;
        }
    </style>
</head>
<body>

    <!-- Page 1: Portada -->
    <div class="page cover-page">
        <div class="logos">
            <img src="https://images.seeklogo.com/logo-png/48/3/ipn-politecnico-logo-png_seeklogo-488802.png" alt="Logo IPN" class="ocr-image cover-ipn-logo">
            <img src="https://images.seeklogo.com/logo-png/35/2/esca-politecnico-logo-png_seeklogo-356182.png" alt="Logo ESCA" class="ocr-image cover-esca-logo">
        </div>
        <div style="clear: both;"></div>
        <h1 class="main-title">IPN</h1>
        <h2 class="subtitle">Escuela Superior de Comercio y Administración Santo Tomás</h2>
        <h3 class="subtitle">Cuaderno Digital Ecommerce</h3>
        <h4 class="subtitle">Segundo Parcial</h4>
        <p class="author">Ponce Castro Axel Armando</p>
    </div>

    <!-- Page 2: Jerarquía Visual - Introducción y Elementos Clave -->
    <div class="page">
        <h1>JERARQUÍA VISUAL</h1>
        <p>Ponce Castro Axel Armando</p>

        <h2>¿Qué es la Jerarquía Visual?</h2>
        <p>La <span class="highlight">jerarquía visual</span> es el principio del diseño que organiza los elementos para mostrar su orden de importancia. Influye en el orden en que el ojo humano percibe lo que ve. Una jerarquía visual efectiva permite a los espectadores comprender fácilmente la información presentada. Al manipular las señales visuales, puedes dirigir la atención del usuario a áreas específicas de tu diseño y comunicar tu mensaje de forma eficaz. En esencia, es una hoja de ruta visual que guía al espectador a través del contenido.</p>

        <h2>Elementos Clave de la Jerarquía Visual</h2>

        <h3>1. Tamaño:</h3>
        <p>Los elementos más grandes captan la atención primero. Utiliza el tamaño para destacar la información más importante. Una imagen grande o un titular llamativo dominarán la página.</p>
        <p class="example">Ejemplo: Un botón de 'Comprar ahora' grande y brillante.</p>

        <h3>2. Color y Contraste:</h3>
        <p>Los colores brillantes y los altos contrastes atraen la mirada. Utiliza un color destacado para llamar la atención sobre un elemento específico.</p>
        <p class="example">Ejemplo: Usar un color rojo brillante para un llamado a la acción sobre un fondo neutro.</p>

        <h3>3. Espacio en Blanco (Espacio Negativo):</h3>
        <p>El espacio en blanco alrededor de un elemento lo aísla y lo hace más notorio. No tengas miedo de dejar espacio vacío.</p>
        <p class="example">Ejemplo: Dejar un amplio espacio alrededor de un logo para que destaque.</p>

        <h3>4. Posición:</h3>
        <p>Los elementos ubicados en la parte superior o central de la página generalmente reciben más atención. La regla general es que los elementos que están en la parte superior o izquierda de la pantalla se ven primero.</p>
        <p class="example">Ejemplo: Colocar un titular importante en la parte superior central de una página web.</p>
    </div>

    <!-- Page 3: Jerarquía Visual - Continuación y Conclusión -->
    <div class="page">
        <h2>Elementos Clave de la Jerarquía Visual (Continuación)</h2>

        <h3>5. Tipografía:</h3>
        <p>El tipo de letra, su tamaño, peso y estilo influyen en la legibilidad y el impacto visual. Usa fuentes diferentes para crear jerarquía.</p>
        <p class="example">Ejemplo: Utilizar una fuente grande y en negrita para los títulos y una fuente más pequeña y clara para el cuerpo del texto.</p>

        <h3>6. Repetición y Consistencia:</h3>
        <p>Repetir ciertos elementos de diseño ayuda a crear una apariencia cohesiva y refuerza la jerarquía. La consistencia en el uso de elementos visuales (colores, fuentes, estilos) contribuye a una mejor comprensión.</p>
        <p class="example">Ejemplo: Utilizar el mismo estilo de botón en toda una página web.</p>

        <h3>7. Dirección Visual:</h3>
        <p>Las líneas y las formas pueden dirigir la mirada del espectador hacia un punto focal específico. La dirección puede ser implícita (a través de la colocación de elementos) o explícita (a través de flechas o líneas).</p>
        <p class="example">Ejemplo: Utilizar una flecha para guiar al usuario hacia un botón de compra.</p>

        <h3>8. Textura y Profundidad:</h3>
        <p>Utilizar texturas o crear una sensación de profundidad puede agregar interés visual y ayudar a destacar ciertos elementos. Sombras, degradados y patrones sutiles pueden lograr este efecto.</p>
        <p class="example">Ejemplo: Usar una sombra sutil detrás de un botón para que parezca que está "levantado" de la página.</p>

        <h2>Principios Fundamentales para la Jerarquía Visual</h2>

        <h3>1. La Proporción Áurea:</h3>
        <p>Esta proporción matemática (aproximadamente 1.618) se encuentra en la naturaleza y se considera estéticamente agradable. Utilízala para determinar el tamaño y la ubicación de los elementos en tu diseño.</p>
        <p class="example">Aplicación: Divide tu diseño siguiendo la proporción áurea para crear un equilibrio armonioso.</p>

        <h3>2. La Regla de los Tercios:</h3>
        <p>Divide tu diseño en nueve partes iguales con dos líneas horizontales y dos verticales. Coloca los elementos importantes en las intersecciones de estas líneas para crear puntos focales visualmente atractivos.</p>
        <p class="example">Aplicación: Coloca el punto focal de una imagen en una de las intersecciones para atraer la atención.</p>

        <h2>Conclusión</h2>
        <p>La jerarquía visual es una herramienta poderosa para guiar a los usuarios a través de tu diseño y comunicar tu mensaje de manera efectiva. Al comprender y aplicar los principios y elementos mencionados, puedes crear diseños más impactantes y fáciles de entender. Experimenta con diferentes técnicas y encuentra lo que funciona mejor para tu proyecto. ¡Buena suerte!</p>

        <h3>Referencias de Jerarquía Visual:</h3>
        <ul class="reference-list">
            <li>Lidwell, W., Holden, K., & Butler, J. (2010). *Universal Principles of Design*. Rockport Publishers.</li>
            <li>Norman, D. A. (2013). *The Design of Everyday Things: Revised and Expanded Edition*. Basic Books.</li>
            <li>Wong, W. (1993). *Principles of Form and Design*. Van Nostrand Reinhold.</li>
        </ul>
    </div>

    <!-- Page 4: Understanding Aspect Ratio - Introducción y Plataformas -->
    <div class="page">
        <div class="background-image-header">
            <h1>COMPRENDIENDO LA RELACIÓN DE ASPECTO</h1>
            <p>Una guía para las proporciones de imagen</p>
        </div>

        <h2>¿Qué es la Relación de Aspecto?</h2>
        <p>La <span class="highlight">relación de aspecto</span> es la proporción entre el ancho y el alto de una imagen o video. Se expresa como dos números separados por dos puntos, por ejemplo, 16:9. El primer número representa el ancho y el segundo el alto. Entender y utilizar correctamente la relación de aspecto es crucial para que tus diseños se vean perfectos en cualquier plataforma, evitando distorsiones o recortes no deseados.</p>

        <h2>La Importancia en Diferentes Plataformas</h2>
        <p>Cada plataforma y dispositivo tiene relaciones de aspecto preferidas. Ignorar esto puede resultar en imágenes recortadas, estiradas o con barras negras antiestéticas. Adaptar la relación de aspecto asegura una presentación óptima en cada contexto.</p>

        <h3>Horizontal o Panorámica (16:9)</h3>
        <p>Ideal para videos y pantallas grandes como televisores y monitores de computadora. Ofrece una visualización inmersiva y es el estándar para contenido de video en línea.</p>

        <h3>Cuadrada (1:1)</h3>
        <p>Común en redes sociales como Instagram (originalmente) e iconos. Transmite simetría y equilibrio, aunque está menos extendida actualmente.</p>

        <h3>Vertical o Retrato (9:16 y 4:5)</h3>
        <p>Optimizada para dispositivos móviles y publicaciones verticales en plataformas como Instagram Stories, TikTok y Pinterest. Maximiza el espacio en pantalla en dispositivos móviles.</p>

        <h3>Otros formatos.</h3>
        <p>Existen muchas otras relaciones de aspecto, como 3:2, 21:9, etc. Cada una está adaptada a usos concretos, y es importante conocerlas para elegir la más adecuada.</p>

        <h2>Diseño Adaptativo (Responsive Design)</h2>
        <p>El diseño adaptativo es la clave para asegurar que tus imágenes se vean bien en cualquier dispositivo. Se trata de crear diseños flexibles que se ajusten automáticamente al tamaño de la pantalla.</p>
    </div>

    <!-- Page 5: Understanding Aspect Ratio - Dirección de Arte Adaptativa y Resumen -->
    <div class="page">
        <h2>Diseño Adaptativo (Responsive Design) (Continuación)</h2>
        <p>Un ejemplo es usar unidades relativas, como porcentajes, en lugar de píxeles fijos. Esto permite que las imágenes se escalen proporcionalmente. Las <span class="highlight">imágenes flexibles</span> se redimensionan automáticamente según el contenedor en el que se encuentran.</p>

        <h2>Dirección de Arte Adaptativa</h2>
        <p>La <span class="highlight">dirección de arte adaptativa</span> va un paso más allá. Implica crear <span class="highlight">diferentes versiones</span> de una misma imagen, optimizadas para distintos tamaños de pantalla. Por ejemplo, se puede tener una versión completa para pantallas grandes y una versión simplificada para móviles, enfocándose en los elementos más importantes.</p>

        <h2>En Resumen</h2>
        <p>Dominar la relación de aspecto, el diseño adaptativo y la dirección de arte es esencial para crear contenido visualmente atractivo y efectivo en el panorama digital actual. Al comprender cómo funcionan estos conceptos, podrás optimizar tus diseños para cualquier plataforma y dispositivo, garantizando una experiencia de usuario impecable.</p>

        <h3>Referencias de Relación de Aspecto y Diseño Adaptativo:</h3>
        <ul class="reference-list">
            <li>W3C. (s.f.). *Responsive Web Design*. Recuperado de <a href="https://www.w3.org/standards/webdesign/">https://www.w3.org/standards/webdesign/</a></li>
            <li>Smashing Magazine. (s.f.). *Responsive Web Design: What It Is And How To Use It*. Recuperado de <a href="https://www.smashingmagazine.com/responsive-web-design-guidelines/">https://www.smashingmagazine.com/responsive-web-design-guidelines/</a></li>
            <li>Google Developers. (s.f.). *Images for responsive design*. Recuperado de <a href="https://developers.google.com/web/fundamentals/design-and-ui/responsive/images">https://developers.google.com/web/fundamentals/design-and-ui/responsive/images</a></li>
        </ul>
    </div>

    <!-- Page 6: Comparativa de Plataformas (Tabla 1) -->
    <div class="page">
        <h2>Comparativa de Plataformas</h2>
        <table>
            <thead>
                <tr>
                    <th>Plataforma</th>
                    <th>Modelo</th>
                    <th>Target</th>
                    <th>Ventajas</th>
                    <th>Costos y Planes</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>WordPress</td>
                    <td>CMS (Sistema de Gestión de Contenido)</td>
                    <td>Blogs, sitios web personales y PYMES</td>
                    <td>Alta personalización, gran comunidad, miles de plugins y temas, escalable.</td>
                    <td>Gratuito (software), alojamiento y dominio son costos externos. Existen planes de alojamiento gestionado.</td>
                </tr>
                <tr>
                    <td>GIMP</td>
                    <td>Editor de imágenes</td>
                    <td>Diseñadores gráficos, fotógrafos</td>
                    <td>Edición avanzada de imágenes, retoque fotográfico, herramientas de diseño gráfico.</td>
                    <td>Gratuito (software), no hay costos directos asociados.</td>
                </tr>
                <tr>
                    <td>LibreOffice</td>
                    <td>Suite ofimática</td>
                    <td>Usuarios domésticos, estudiantes, PYMES</td>
                    <td>Procesador de texto, hojas de cálculo, presentaciones, base de datos.</td>
                    <td>Gratuito (software), no hay costos directos asociados.</td>
                </tr>
                <tr>
                    <td>Mozilla Firefox</td>
                    <td>Navegador web</td>
                    <td>Usuarios de internet en general</td>
                    <td>Privacidad y seguridad, extensiones, personalización, rápido y eficiente.</td>
                    <td>Gratuito (software), no hay costos directos asociados.</td>
                </tr>
                <tr>
                    <td>Audacity</td>
                    <td>Editor de audio</td>
                    <td>Músicos, podcasters, editores de audio</td>
                    <td>Grabación y edición de audio, efectos de sonido, eliminación de ruido.</td>
                    <td>Gratuito (software), no hay costos directos asociados.</td>
                </tr>
                <tr>
                    <td>Nextcloud</td>
                    <td>Nube personal/empresarial</td>
                    <td>Usuarios, empresas, instituciones</td>
                    <td>Almacenamiento y sincronización de archivos, colaboración, calendarios, contactos.</td>
                    <td>Gratuito (software), costos de alojamiento propio o planes de proveedores.</td>
                </tr>
                <tr>
                    <td>Odoo</td>
                    <td>ERP/CRM</td>
                    <td>PYMES, grandes empresas</td>
                    <td>Gestión empresarial integral (ventas, contabilidad, inventario, proyectos).</td>
                    <td>Edición comunitaria gratuita, planes empresariales con más funciones y soporte (costos variables).</td>
                </tr>
                <tr>
                    <td>Moodle</td>
                    <td>Plataforma e-learning</td>
                    <td>Instituciones educativas, empresas</td>
                    <td>Creación de cursos online, gestión de estudiantes, evaluaciones, foros.</td>
                    <td>Gratuito (software), costos de alojamiento y desarrollo personalizado.</td>
                </tr>
                <tr>
                    <td>Linux (Ubuntu)</td>
                    <td>Sistema operativo</td>
                    <td>Desarrolladores, usuarios avanzados</td>
                    <td>Estabilidad, seguridad, personalización, gran variedad de software gratuito.</td>
                    <td>Gratuito (sistema operativo), no hay costos directos asociados.</td>
                </tr>
                <tr>
                    <td>GitLab</td>
                    <td>DevOps Platform</td>
                    <td>Desarrolladores, equipos de TI</td>
                    <td>Control de versiones, CI/CD, gestión de proyectos, seguridad de código.</td>
                    <td>Edición comunitaria gratuita, planes de pago para funciones empresariales y soporte (costos variables).</td>
                </tr>
            </tbody>
        </table>
    </div>

    <!-- Page 7: Comparativa de Plataformas (Tabla 2) -->
    <div class="page">
        <h2>Comparativa de Plataformas (Continuación)</h2>
        <table>
            <thead>
                <tr>
                    <th>Plataforma</th>
                    <th>Modelo</th>
                    <th>Target</th>
                    <th>Ventajas</th>
                    <th>Costos y Planes</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>CRMify</td>
                    <td>Suscripción</td>
                    <td>Equipos de ventas pequeños</td>
                    <td>Gestión de clientes, seguimiento de leads, automatización de ventas.</td>
                    <td>Básico: $29/mes, Pro: $79/mes, Enterprise: $199/mes. Prueba gratuita de 14 días.</td>
                </tr>
                <tr>
                    <td>TaskFlow</td>
                    <td>Freemium</td>
                    <td>Equipos de proyectos</td>
                    <td>Colaboración en tiempo real, gestión de tareas, seguimiento de progreso.</td>
                    <td>Gratuito (funciones básicas), Premium: $10/usuario/mes, Business: $25/usuario/mes.</td>
                </tr>
                <tr>
                    <td>DesignVault</td>
                    <td>Suscripción</td>
                    <td>Diseñadores gráficos</td>
                    <td>Librería de activos, herramientas de edición en la nube, colaboración creativa.</td>
                    <td>Personal: $15/mes, Equipo: $49/mes (hasta 5 usuarios), Empresa: $120/mes (más de 5 usuarios).</td>
                </tr>
                <tr>
                    <td>HRConnect</td>
                    <td>Suscripción</td>
                    <td>PYMES</td>
                    <td>Gestión de personal, nóminas, seguimiento de asistencia.</td>
                    <td>Pequeña Empresa: $50/mes (hasta 10 empleados), Crecimiento: $150/mes (hasta 50 empleados), Corporativo: Precios personalizados.</td>
                </tr>
                <tr>
                    <td>LearnSphere</td>
                    <td>Suscripción</td>
                    <td>Instituciones educativas</td>
                    <td>Creación y gestión de cursos online, seguimiento del aprendizaje.</td>
                    <td>Básico: $99/mes (hasta 100 estudiantes), Profesional: $249/mes (hasta 500 estudiantes), Enterprise: Precios personalizados.</td>
                </tr>
                <tr>
                    <td>MarketReach</td>
                    <td>Suscripción</td>
                    <td>Pequeños negocios</td>
                    <td>Automatización de marketing, email marketing, gestión de redes sociales.</td>
                    <td>Starter: $39/mes, Avanzado: $99/mes, Ilimitado: $249/mes.</td>
                </tr>
                <tr>
                    <td>CodeCloud</td>
                    <td>Freemium</td>
                    <td>Desarrolladores</td>
                    <td>Control de versiones en la nube, entornos de desarrollo colaborativos.</td>
                    <td>Gratuito (repositorios públicos), Pro: $7/usuario/mes, Equipo: $21/usuario/mes.</td>
                </tr>
                <tr>
                    <td>DataInsights</td>
                    <td>Suscripción</td>
                    <td>Analistas de datos</td>
                    <td>Visualización de datos, informes personalizables, integración con múltiples fuentes.</td>
                    <td>Estándar: $75/mes, Premium: $199/mes (incluye soporte prioritario), Corporativo: Precios personalizados.</td>
                </tr>
                <tr>
                    <td>SecureGuard</td>
                    <td>Suscripción</td>
                    <td>Empresas de todos los tamaños</td>
                    <td>Ciberseguridad, monitoreo de amenazas, copias de seguridad automáticas.</td>
                    <td>Esencial: $49/mes (5 dispositivos), Negocio: $149/mes (20 dispositivos), Elite: $399/mes (50+ dispositivos).</td>
                </tr>
                <tr>
                    <td>EventEase</td>
                    <td>Suscripción</td>
                    <td>Organizadores de eventos</td>
                    <td>Gestión de registros, venta de entradas, marketing de eventos.</td>
                    <td>Básico: $20/evento + 2% de comisión, Pro: $99/mes (eventos ilimitados) + 1% de comisión, Enterprise: Precios personalizados.</td>
                </tr>
            </tbody>
        </table>
        <h3>Referencias de Plataformas y Herramientas:</h3>
        <ul class="reference-list">
            <li>WordPress.org. (s.f.). *About WordPress*. Recuperado de <a href="https://wordpress.org/about/">https://wordpress.org/about/</a></li>
            <li>GIMP. (s.f.). *About GIMP*. Recuperado de <a href="https://www.gimp.org/about/">https://www.gimp.org/about/</a></li>
        </ul>
    </div>

    <!-- Page 8: Modelos de Servicio y Despliegue en la Nube -->
    <div class="page">
        <h1>Modelos de Servicio y Despliegue en la Nube</h1>
        <h2>Comparativa de modelos (tabla)</h2>
        <p>Ponce Castro Axel Armando<br>Escuela Superior de Comercio y Administración Santo Tomás<br>Marketing Digital IPN</p>

        <table>
            <thead>
                <tr>
                    <th>Modelo</th>
                    <th>Definición Breve</th>
                    <th>Ventajas</th>
                    <th>Desventajas</th>
                    <th>Ejemplo Real</th>
                    <th>Tendencia / Uso</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>XaaS</td>
                    <td>Todo servicio de TI vía la nube, bajo demanda (SaaS, PaaS, IaaS, etc.).</td>
                    <td>Máxima flexibilidad y escalabilidad. Enfoque en el negocio. Pago por uso.</td>
                    <td>Dependencia del proveedor e internet. Variabilidad de costos.</td>
                    <td>HPE GreenLake</td>
                    <td>Tendencia dominante; suscripción para casi todo.</td>
                </tr>
                <tr>
                    <td>SaaS</td>
                    <td>Software listo para usar alojado y gestionado por el proveedor.</td>
                    <td>Cero mantenimiento. Despliegue rápido. Bajo costo inicial. Acceso web.</td>
                    <td>Personalización limitada. Control mínimo de infraestructura y datos.</td>
                    <td>Shopify; Salesforce</td>
                    <td>Dominio en apps empresariales y e-commerce. Suscripción es la norma.</td>
                </tr>
                <tr>
                    <td>PaaS</td>
                    <td>Entorno completo en la nube para desarrollar, ejecutar y gestionar apps.</td>
                    <td>Enfoque en el código. Mayor velocidad de desarrollo.</td>
                    <td>Control limitado de SO/hardware. Posibles restricciones de lenguaje.</td>
                    <td>AWS Elastic Beanstalk; Heroku</td>
                    <td>Uso común para desarrollo ágil y microservicios.</td>
                </tr>
                <tr>
                    <td>IaaS</td>
                    <td>Recursos virtualizados de cómputo, almacenamiento y redes.</td>
                    <td>Máximo control de SO y apps. Flexibilidad y escalabilidad bajo demanda.</td>
                    <td>Gestión y seguridad a cargo del usuario. Requiere conocimientos.</td>
                    <td>AWS; Microsoft Azure; Google Compute Engine</td>
                    <td>Base para e-commerce personalizado y big data; uso masivo.</td>
                </tr>
                <tr>
                    <td>Open Source</td>
                    <td>Código fuente disponible; puede ser on-premise o en la nube.</td>
                    <td>Sin licencias. Alta personalización. Comunidad de soporte.</td>
                    <td>Soporte y mantenimiento recaen en el usuario.</td>
                    <td>WooCommerce; PrestaShop</td>
                    <td>Muy usado para alta personalización; migrando a la nube (IaaS).</td>
                </tr>
                <tr>
                    <td>On-premise</td>
                    <td>Software e infraestructura instalados en las instalaciones de la empresa.</td>
                    <td>Control total de seguridad y datos. Cumple regulaciones.</td>
                    <td>Alto CAPEX. Mantenimiento y actualizaciones a cargo propio. Menor escala.</td>
                    <td>Data Center privado de retail</td>
                    <td>Uso en declive; se mantiene en sectores regulados.</td>
                </tr>
            </tbody>
        </table>

        <h2>Mapa Cualitativo: Control, Flexibilidad, Personalización</h2>
        <p>Valores cualitativos: Alto, Medio o Bajo</p>
        <table>
            <thead>
                <tr>
                    <th>Modelo</th>
                    <th>Control</th>
                    <th>Flexibilidad</th>
                </tr>
            </thead>
            <tbody>
                <tr><td>XaaS</td><td>Bajo</td><td>Alto</td></tr>
                <tr><td>SaaS</td><td>Bajo</td><td>Alto</td></tr>
                <tr><td>PaaS</td><td>Medio</td><td>Alto</td></tr>
                <tr><td>IaaS</td><td>Alto</td><td>Alto</td></tr>
                <tr><td>Open Source</td><td>Alto</td><td>Alto</td></tr>
                <tr><td>On-premise</td><td>Muy alto</td><td>Bajo-Medio</td></tr>
            </tbody>
        </table>

        <h3>Referencias de Modelos Cloud:</h3>
        <ul class="reference-list">
            <li>Amazon Web Services (AWS). (s. f.). *Modelos de servicio en la nube | Tipos de cloud computing*. Recuperado de <a href="https://aws.amazon.com/es/types-of-cloud-computing/">https://aws.amazon.com/es/types-of-cloud-computing/</a></li>
            <li>Bismart. (s. f.). *10 tendencias clave en migración cloud para 2023*. Recuperado de <a href="https://blog.bismart.com/top-10-tendencias-migracion-cloud-2023/">https://blog.bismart.com/top-10-tendencias-migracion-cloud-2023/</a></li>
            <li>Google Cloud. (s. f.). *PaaS, IaaS, SaaS y CaaS: ¿en qué se diferencian?* Recuperado de <a href="https://cloud.google.com/learn/paas-vs-iaas-vs-saas?hl=es">https://cloud.google.com/learn/paas-vs-iaas-vs-saas?hl=es</a></li>
            <li>Hostinger. (s. f.). *WooCommerce vs Shopify: ¿Cuál plataforma es mejor para tu tienda online?* Recuperado de <a href="https://www.hostinger.com/es/tutoriales/woocommerce-vs-shopify-en-cual-crear-tienda-online">https://www.hostinger.com/es/tutoriales/woocommerce-vs-shopify-en-cual-crear-tienda-online</a></li>
            <li>IBM. (s. f.). *Diferencias entre IaaS, PaaS y SaaS*. Recuperado de <a href="https://www.ibm.com/mx-es/topics/iaas-paas-saas">https://www.ibm.com/mx-es/topics/iaas-paas-saas</a></li>
        </ul>
    </div>

    <!-- Page 9: XaaS (Anything as a Service) - Introducción y Ventajas -->
    <div class="page">
        <div class="background-image-header">
            <h1>XAAS (TODO COMO SERVICIO)</h1>
            <p>Una visión general de los modelos</p>
        </div>

        <h2>¿Qué es XaaS?</h2>
        <p><span class="highlight">XaaS</span>, o Anything as a Service (Todo como un Servicio), es un término general que engloba una amplia gama de servicios ofrecidos a través de la nube. En lugar de adquirir y mantener hardware y software localmente, las empresas pueden acceder a estos recursos bajo demanda, pagando solo por lo que utilizan. XaaS representa una evolución en la forma en que las organizaciones consumen tecnología, permitiéndoles ser más ágiles, flexibles y eficientes.</p>

        <h3>XaaS abarca numerosas categorías, entre las que se incluyen:</h3>
        <ul>
            <li><span class="highlight">SaaS (Software as a Service):</span> Aplicaciones accesibles a través de internet (ej., Salesforce, Google Workspace).</li>
            <li><span class="highlight">PaaS (Platform as a Service):</span> Plataformas para desarrollar, ejecutar y gestionar aplicaciones (ej., AWS Elastic Beanstalk, Google App Engine).</li>
            <li><span class="highlight">IaaS (Infrastructure as a Service):</span> Acceso a recursos informáticos como servidores, almacenamiento y redes (ej., Amazon Web Services, Microsoft Azure).</li>
            <li><span class="highlight">DaaS (Desktop as a Service):</span> Escritorios virtuales alojados en la nube.</li>
            <li><span class="highlight">DRaaS (Disaster Recovery as a Service):</span> Soluciones de recuperación ante desastres basadas en la nube.</li>
        </ul>

        <h2>Ventajas de XaaS</h2>
        <p>El modelo XaaS ofrece numerosas ventajas para las empresas:</p>
        <ul>
            <li><span class="highlight">Reducción de costos:</span> Elimina la necesidad de invertir en infraestructura costosa y personal especializado.</li>
            <li><span class="highlight">Escalabilidad:</span> Permite aumentar o disminuir los recursos según las necesidades del negocio.</li>
            <li><span class="highlight">Flexibilidad:</span> Facilita la adaptación a los cambios del mercado y la adopción de nuevas tecnologías.</li>
            <li><span class="highlight">Accesibilidad:</span> Permite acceder a los servicios desde cualquier lugar y en cualquier momento.</li>
            <li><span class="highlight">Mantenimiento simplificado:</span> El proveedor se encarga del mantenimiento y las actualizaciones.</li>
        </ul>
    </div>

    <!-- Page 10: XaaS vs. On-Premise vs. Open Source y Conclusión -->
    <div class="page">
        <h1>XaaS vs. On-Premise vs. Open Source</h1>

        <h3>XaaS (Todo como un Servicio)</h3>
        <ul>
            <li>Servicios ofrecidos a través de la nube.</li>
            <li>Pago por uso.</li>
            <li>Proveedor gestiona la infraestructura y el software.</li>
            <li>Escalable y flexible.</li>
        </ul>

        <h3>On-Premise (Local)</h3>
        <ul>
            <li>Infraestructura y software alojados en las instalaciones de la empresa.</li>
            <li>Inversión inicial alta.</li>
            <li>Empresa responsable del mantenimiento y las actualizaciones.</li>
            <li>Mayor control sobre los datos.</li>
        </ul>

        <h3>Open Source (Código Abierto)</h3>
        <ul>
            <li>Software con código fuente disponible para su modificación y distribución.</li>
            <li>Puede ser alojado localmente o en la nube.</li>
            <li>Requiere conocimientos técnicos para su implementación y mantenimiento.</li>
            <li>Ofrece gran flexibilidad y personalización.</li>
        </ul>

        <h2>Conclusión</h2>
        <p>XaaS representa una alternativa atractiva para las empresas que buscan optimizar sus recursos, reducir costos y mejorar su agilidad. Aunque On-Premise y Open Source siguen siendo opciones válidas para ciertos escenarios, XaaS ofrece una combinación única de flexibilidad, escalabilidad y facilidad de uso que lo convierte en una opción cada vez más popular.</p>

        <h3>Referencias de XaaS:</h3>
        <ul class="reference-list">
            <li>Gartner, Inc. (s.f.). *Gartner Glossary: Anything-as-a-Service (XaaS)*. Recuperado el 14 de octubre de 2025, de <a href="https://www.gartner.com/en/information-technology/glossary/xaas-anything-as-a-service">https://www.gartner.com/en/information-technology/glossary/xaas-anything-as-a-service</a></li>
        </ul>
    </div>

    <!-- Page 11: Responsive vs. Adaptive Web Design - Introducción -->
    <div class="page">
        <div class="header-responsive-adaptive">
            <h1>DISEÑO WEB RESPONSIVO VS. ADAPTATIVO</h1>
            <p>Comprendiendo las diferencias clave</p>
        </div>

        <h2>¿Qué es el Diseño Web Responsivo?</h2>
        <p>El <span class="highlight">diseño web responsivo</span> es un enfoque de diseño web que busca que las páginas web se vean bien en <span class="highlight">todos</span> los dispositivos, desde ordenadores de escritorio hasta teléfonos móviles y tabletas. Esto se logra utilizando <span class="highlight">CSS media queries</span> para adaptar el diseño según el tamaño de la pantalla y la resolución del dispositivo. Un sitio web responsivo utiliza una única base de código que se adapta dinámicamente.</p>
        <p>En esencia, un sitio web responsivo fluye y se reorganiza para ajustarse al espacio disponible. Esto significa que los elementos como texto, imágenes y menús se redimensionan y se reposicionan automáticamente para proporcionar la mejor experiencia de usuario posible en cualquier dispositivo.</p>

        <h3>Aquí hay tres ejemplos de diseño web responsivo en acción:</h3>
        <ul>
            <li><span class="highlight">Dropbox:</span> El sitio web de Dropbox se adapta perfectamente a diferentes tamaños de pantalla, manteniendo la legibilidad y la usabilidad en todos los dispositivos.</li>
            <li><span class="highlight">Shopify:</span> La plataforma de comercio electrónico Shopify ofrece una experiencia consistente en escritorio y móvil, facilitando la gestión de tiendas online desde cualquier lugar.</li>
            <li><span class="highlight">Slack:</span> La interfaz de Slack se ajusta de forma inteligente a diferentes pantallas, permitiendo una comunicación fluida y eficiente tanto en ordenadores como en dispositivos móviles.</li>
        </ul>

        <h2>¿Qué es el Diseño Web Adaptativo?</h2>
        <p>El <span class="highlight">diseño web adaptativo</span>, por otro lado, implica la creación de <span class="highlight">múltiples versiones</span> de un sitio web, cada una optimizada para una categoría específica de dispositivos (por ejemplo, escritorio, tableta, móvil). Cuando un usuario accede al sitio web, el servidor detecta el tipo de dispositivo y sirve la versión apropiada.</p>
        <p>A diferencia del diseño responsivo, el diseño adaptativo no se basa en un único diseño flexible. En cambio, utiliza una serie de diseños estáticos predefinidos.</p>

        <h3>Aquí hay tres ejemplos de diseño web adaptativo:</h3>
        <ul>
            <li><span class="highlight">Amazon (versiones antiguas):</span> Aunque actualmente Amazon utiliza un diseño mayormente responsivo, en el pasado utilizaba un enfoque adaptativo con versiones separadas para móvil y escritorio.</li>
        </ul>
    </div>

    <!-- Page 12: Responsive vs. Adaptive Web Design - Continuación y Conclusión -->
    <div class="page">
        <h2>¿Qué es el Diseño Web Adaptativo? (Continuación)</h2>
        <ul>
            <li><span class="highlight">Wikipedia (versión móvil):</span> La versión móvil de Wikipedia es un ejemplo de diseño adaptativo, con una interfaz simplificada y optimizada para dispositivos móviles.</li>
            <li><span class="highlight">Algunos bancos (versiones antiguas):</span> Algunos bancos todavía utilizan diseños adaptativos para sus sitios web, ofreciendo versiones separadas para escritorio y móvil, aunque la tendencia es hacia el diseño responsivo.</li>
        </ul>

        <h2>Tabla Comparativa: Responsivo vs. Adaptativo</h2>

        <h3>Diseño Web Responsivo</h3>
        <ul>
            <li>Un único diseño adaptable.</li>
            <li>Utiliza <span class="highlight">media queries</span> de CSS.</li>
            <li>Más flexible y fácil de mantener.</li>
            <li>Mejor para SEO (un solo URL).</li>
            <li>Requiere más planificación inicial.</li>
            <li>Carga inicial potencialmente más lenta.</li>
        </ul>

        <h3>Diseño Web Adaptativo</h3>
        <ul>
            <li>Múltiples diseños estáticos.</li>
            <li>Detección del dispositivo en el servidor.</li>
            <li>Menos flexible, mantenimiento más complejo.</li>
            <li>Potenciales problemas de SEO (URLs duplicados).</li>
            <li>Puede ser más rápido para implementar inicialmente.</li>
            <li>Carga inicial más rápida (diseños optimizados).</li>
        </ul>

        <h2>Conclusión</h2>
        <p>Tanto el diseño web responsivo como el adaptativo buscan ofrecer una experiencia de usuario óptima en diferentes dispositivos. Sin embargo, el diseño responsivo, con su flexibilidad y facilidad de mantenimiento, se ha convertido en el enfoque <span class="highlight">predominante</span> en la industria. La elección entre uno u otro dependerá de las necesidades y recursos específicos de cada proyecto, pero la tendencia actual favorece claramente al diseño responsivo.</p>

        <h3>Referencias de Diseño Web Responsivo y Adaptativo:</h3>
        <ul class="reference-list">
            <li>Marcotte, E. (2011). *Responsive Web Design*. A Book Apart.</li>
            <li>Shapira, A., & Levy, O. (2012). *Adaptive Web Design: Crafting Rich Experiences with Progressive Enhancement*. New Riders.</li>
            <li>Nielsen Norman Group. (s.f.). *Responsive Web Design*. Recuperado de <a href="https://www.nngroup.com/articles/responsive-web-design-definition/">https://www.nngroup.com/articles/responsive-web-design-definition/</a></li>
        </ul>
    </div>

</body>
</html>
