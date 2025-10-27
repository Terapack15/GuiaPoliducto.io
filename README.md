<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guía para Optimizar tu Sistema de Riego con Poliducto</title>
    <style>
        :root {
            --azul: #1e5b9e;
            --naranja: #ff7b25;
            --blanco: #ffffff;
            --gris-claro: #f5f5f5;
            --azul-claro: #e8f1fc;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: var(--gris-claro);
            color: #333;
            line-height: 1.6;
            font-size: 16px;
        }
        
        header {
            background-color: var(--azul);
            color: var(--blanco);
            padding: 1.5rem 1rem;
            text-align: center;
            position: relative;
        }
        
        h1 {
            font-size: 1.8rem;
            margin-bottom: 1rem;
            line-height: 1.3;
        }
        
        .subtitulo {
            font-size: 1rem;
            max-width: 800px;
            margin: 0 auto;
            padding: 0 0.5rem;
            line-height: 1.5;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 1.5rem 1rem;
        }
        
        .paso {
            background-color: var(--blanco);
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            margin-bottom: 1.5rem;
            overflow: hidden;
            transition: transform 0.3s ease;
        }
        
        .paso:hover {
            transform: translateY(-3px);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.15);
        }
        
        .paso-header {
            background-color: var(--naranja);
            color: var(--blanco);
            padding: 1.2rem;
            display: flex;
            align-items: center;
        }
        
        .numero-paso {
            background-color: var(--blanco);
            color: var(--naranja);
            width: 2.2rem;
            height: 2.2rem;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            margin-right: 0.8rem;
            flex-shrink: 0;
        }
        
        .paso-header h2 {
            font-size: 1.4rem;
            line-height: 1.3;
        }
        
        .paso-contenido {
            padding: 1.2rem;
        }
        
        .paso-contenido h3 {
            color: var(--azul);
            margin: 1.2rem 0 0.5rem;
            font-size: 1.2rem;
            line-height: 1.4;
        }
        
        .paso-contenido p, .paso-contenido ul {
            margin-bottom: 1rem;
        }
        
        .paso-contenido ul {
            padding-left: 1.2rem;
        }
        
        .paso-contenido li {
            margin-bottom: 0.5rem;
            line-height: 1.5;
        }
        
        .resumen {
            background-color: var(--azul);
            color: var(--blanco);
            padding: 1.5rem;
            border-radius: 8px;
            margin-top: 1.5rem;
        }
        
        .resumen h2 {
            text-align: center;
            margin-bottom: 1.2rem;
            font-size: 1.5rem;
        }
        
        .resumen ul {
            max-width: 600px;
            margin: 0 auto 1.5rem;
        }
        
        .resumen li {
            margin-bottom: 0.8rem;
            line-height: 1.5;
        }
        
        footer {
            background-color: var(--azul);
            color: var(--blanco);
            text-align: center;
            padding: 1.5rem;
            margin-top: 1.5rem;
            font-size: 0.9rem;
        }
        
        .consejo-movil {
            display: none;
            background-color: var(--azul-claro);
            padding: 0.8rem;
            border-radius: 6px;
            margin: 1rem 0;
            font-size: 0.9rem;
            border-left: 4px solid var(--naranja);
        }
        
        /* Media Queries para tablets y escritorio */
        @media (min-width: 768px) {
            header {
                padding: 2.5rem 1rem;
            }
            
            h1 {
                font-size: 2.5rem;
            }
            
            .subtitulo {
                font-size: 1.2rem;
            }
            
            .container {
                padding: 2rem 1.5rem;
            }
            
            .paso {
                margin-bottom: 2rem;
            }
            
            .paso-header {
                padding: 1.5rem;
            }
            
            .numero-paso {
                width: 2.5rem;
                height: 2.5rem;
                font-size: 1.2rem;
            }
            
            .paso-header h2 {
                font-size: 1.8rem;
            }
            
            .paso-contenido {
                padding: 1.5rem;
            }
            
            .paso-contenido h3 {
                font-size: 1.3rem;
            }
            
            .resumen {
                padding: 2rem;
            }
            
            .resumen h2 {
                font-size: 1.8rem;
            }
            
            footer {
                padding: 2rem;
            }
        }
        
        /* Media Queries para pantallas grandes */
        @media (min-width: 1024px) {
            .container {
                padding: 2.5rem 2rem;
            }
            
            .paso-contenido {
                padding: 2rem;
            }
        }
        
        /* Estilos para mejorar la legibilidad en móviles */
        @media (max-width: 767px) {
            .consejo-movil {
                display: block;
            }
            
            .paso-header {
                padding: 1rem;
            }
            
            .paso-header h2 {
                font-size: 1.3rem;
            }
            
            .paso-contenido {
                padding: 1rem;
            }
            
            .paso-contenido h3 {
                font-size: 1.1rem;
            }
            
            body {
                font-size: 15px;
            }
        }
        
        /* Mejoras de accesibilidad */
        @media (prefers-reduced-motion: reduce) {
            .paso {
                transition: none;
            }
            
            .paso:hover {
                transform: none;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Guía de 5 Pasos para Optimizar tu Sistema de Riego con Poliducto</h1>
        <p class="subtitulo">Aprende cómo ahorrar agua y mejorar la eficiencia de tu sistema de riego siguiendo estos pasos prácticos</p>
    </header>
    
    <div class="container">
        <div class="consejo-movil">
            <strong>Consejo:</strong> Desliza hacia arriba y abajo para navegar por la guía completa. Toca en cada paso para ver más detalles.
        </div>
        
        <div class="paso">
            <div class="paso-header">
                <div class="numero-paso">1</div>
                <h2>Diagnóstico y Auditoría del Sistema Actual</h2>
            </div>
            <div class="paso-contenido">
                <p><strong>Objetivo:</strong> Identificar fugas, ineficiencias y puntos de mejora.</p>
                
                <h3>Revisión Visual</h3>
                <p>Recorre toda la línea de poliducto. Busca grietas, cortes, abolladuras o conexiones flojas que causen fugas. El poliducto es durable, pero no es inmune a daños mecánicos.</p>
                
                <h3>Chequeo de Presión</h3>
                <p>Usa un manómetro para verificar que la presión de trabajo sea la adecuada para el tipo de emisores que uses (aspersores, goteo, etc.). Una presión excesiva causa neblina, evaporación y desgaste prematuro. Una presión baja resulta en un riego desigual.</p>
                
                <h3>Evaluación de Emisores</h3>
                <p>Comprueba que todos los aspersores o goteros estén funcionando y no obstruidos. Un emisor tapado significa una planta sin agua, mientras que uno que libera de más es un desperdicio.</p>
                
                <h3>Prueba de Uniformidad</h3>
                <p>Coloca pluviómetros o recipientes iguales a lo largo de la zona de riego y enciende el sistema por un tiempo determinado. Mide el agua en cada uno. Si hay una variación mayor al 10%, tu sistema es desigual.</p>
            </div>
        </div>
        
        <div class="paso">
            <div class="paso-header">
                <div class="numero-paso">2</div>
                <h2>Diseño Estratégico y Zonificación</h2>
            </div>
            <div class="paso-contenido">
                <p><strong>Objetivo:</strong> Dividir el riego por tipos de plantas y necesidades hídricas.</p>
                
                <h3>Separación por Zonas (Sectorización)</h3>
                <p>No riegues todo al mismo tiempo. Crea zonas independientes para:</p>
                <ul>
                    <li><strong>Césped:</strong> Necesita riego frecuente y uniforme.</li>
                    <li><strong>Arbustos y Setos:</strong> Requieren menos frecuencia pero mayor volumen.</li>
                    <li><strong>Árboles y Plantas Nativas:</strong> Suelen necesitar riegos profundos y espaciados.</li>
                    <li><strong>Huerto:</strong> Requiere un riego más preciso y constante.</li>
                </ul>
                
                <h3>Elección del Emisor Correcto</h3>
                <p>Acopla el emisor a la zona.</p>
                <p><strong>Riego por Goteo con Poliducto:</strong> Ideal para hileras de plantas, arbustos, árboles y huertos. Lleva el agua directamente a la raíz, minimizando la evaporación y las malas hierbas. Es donde se consigue el mayor ahorro.</p>
                <p><strong>Aspersores:</strong> Reservados para grandes áreas de césped.</p>
                
                <h3>Actualiza el Diseño</h3>
                <p>Si tu sistema es antiguo, rediseña las líneas de poliducto para que se adapten mejor a la zonificación actual.</p>
            </div>
        </div>
        
        <div class="paso">
            <div class="paso-header">
                <div class="numero-paso">3</div>
                <h2>Modernización con Componentes de Alta Eficiencia</h2>
            </div>
            <div class="paso-contenido">
                <p><strong>Objetivo:</strong> Reemplazar componentes obsoletos por tecnología que maximice el ahorro.</p>
                
                <h3>Instalar Válvulas de Zona Automatizadas</h3>
                <p>Controlan el flujo de agua a cada zona de manera independiente y programable.</p>
                
                <h3>Invertir en un Controlador (Programador) Inteligente</h3>
                <p>Este es el corazón del ahorro. Busca modelos con:</p>
                <ul>
                    <li><strong>Control por Evapotranspiración (ET):</strong> Ajusta el riego automáticamente basándose en datos climáticos en tiempo real (temperatura, humedad, viento, radiación solar).</li>
                    <li><strong>Conectividad WiFi:</strong> Permite controlar y ajustar el riego desde tu teléfono, incluso recibir alertas por fugas.</li>
                    <li><strong>Compatibilidad con Sensores de Lluvia y Humedad:</strong> Estos sensores evitan el riego cuando ha llovido o cuando el suelo ya está húmedo, eliminando el riego superfluo.</li>
                </ul>
                
                <h3>Emisores de Bajo Flujo</h3>
                <p>Para riego por goteo, utiliza cintas de goteo o goteros integrados en el poliducto de caudal preciso y autocompensante (mantienen el mismo caudal aunque varíe la presión).</p>
            </div>
        </div>
        
        <div class="paso">
            <div class="paso-header">
                <div class="numero-paso">4</div>
                <h2>Instalación y Mantenimiento Correcto del Poliducto</h2>
            </div>
            <div class="paso-contenido">
                <p><strong>Objetivo:</strong> Garantizar la longevidad del sistema y prevenir pérdidas.</p>
                
                <h3>Instalación Profunda o Superficial Correcta</h3>
                <p>Si lo entierras, hazlo a la profundidad adecuada para protegerlo de daños y de los rayos UV. Si es superficial, asegúrate de que esté bien sujeto con fijaciones para poliducto.</p>
                
                <h3>Conexiones de Calidad</h3>
                <p>Utiliza accesorios (codos, tes, conectores) específicos para poliducto y del mismo diámetro. Evita las fugas en las uniones usando juntas tóricas o sellador de roscas para tubería (nunca para las de goteo).</p>
                
                <h3>Mantenimiento Periódico</h3>
                <ul>
                    <li><strong>Limpieza de Filtros:</strong> Lava los filtros de la sistema principal con regularidad para evitar obstrucciones en los emisores.</li>
                    <li><strong>Lavado de Líneas:</strong> Periódicamente, abre los extremos de las líneas de poliducto para dejar correr el agua y expulsar sedimentos.</li>
                    <li><strong>Inspección Post-Temporada:</strong> Revisa el sistema después del invierno o periodos de inactividad.</li>
                </ul>
            </div>
        </div>
        
        <div class="paso">
            <div class="paso-header">
                <div class="numero-paso">5</div>
                <h2>Monitoreo, Ajuste y Mejora Continua</h2>
            </div>
            <div class="paso-contenido">
                <p><strong>Objetivo:</strong> Afinar el sistema para lograr la máxima eficiencia.</p>
                
                <h3>Ajusta la Programación por Estaciones</h3>
                <p>No riegues igual en primavera, verano y otoño. Reduce significativamente la frecuencia y duración del riego en las estaciones más frescas y lluviosas.</p>
                
                <h3>Riega en el Momento Óptimo</h3>
                <p>Programa el riego para las primeras horas de la mañana. Se reduce la evaporación por el viento y el sol, y se previenen enfermedades fúngicas.</p>
                
                <h3>Auditoría Anual</h3>
                <p>Realiza una revisión completa al menos una vez al año, repitiendo algunos puntos del Paso 1 para asegurarte de que todo funcione como el primer día.</p>
                
                <h3>Interpreta los Datos</h3>
                <p>Usa la información de tu controlador inteligente y sensores para tomar decisiones basadas en datos, no en suposiciones.</p>
            </div>
        </div>
        
        <div class="resumen">
            <h2>Resumen del Ahorro del 20%</h2>
            <p><strong>¿De dónde sale ese ahorro?</strong></p>
            <ul>
                <li>~5%: Eliminación de fugas y reparación de emisores defectuosos.</li>
                <li>~5%: Sectorización y uso de riego por goteo (menor evaporación).</li>
                <li>~10%: Programador inteligente con sensor de lluvia/humedad y riego en horarios óptimos.</li>
            </ul>
            <p style="margin-top: 1.5rem; text-align: center;">Al seguir estos pasos, no solo estarás ahorrando un recurso vital y reduciendo tu factura de agua, sino que también estarás promoviendo un cultivo o jardín más sano, gracias a un riego más preciso y adecuado a sus necesidades.</p>
        </div>
    </div>
    
    <footer>
        <p>Guía para Optimizar tu Sistema de Riego con Poliducto</p>
    </footer>
</body>
</html>
