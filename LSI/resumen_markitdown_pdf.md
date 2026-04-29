# Resumen detallado de los PDF de LSI procesados con MarkItDown

## Método usado

Los PDF se han convertido a Markdown con MarkItDown usando soporte explícito para PDF:

```bash
uvx --from 'markitdown[pdf]' markitdown 'LSI/Título1,2y3.pdf'
uvx --from 'markitdown[pdf]' markitdown 'LSI/Título7.pdf'
```

Los dos documentos son extractos del texto consolidado del BOE de la Ley de Propiedad Intelectual. La extracción es buena, aunque conserva saltos de línea y alguna fragmentación típica del OCR/conversión de PDF.

## Qué contiene cada PDF

### Título7.pdf

Contiene:

- El cierre del régimen de obras audiovisuales: artículos 91 a 94.
- El Título VII, Programas de ordenador: artículos 95 a 104.
- El comienzo del Libro Segundo, Título I, sobre artistas intérpretes o ejecutantes: artículos 105 a 108.

### Título1,2y3.pdf

Contiene:

- El final del artículo 102 y los artículos 103 y 104, todavía dentro del régimen de programas de ordenador.
- El Libro Segundo completo desde el Título I hasta el Título IV en este fragmento:
  - Título I: artistas intérpretes o ejecutantes, artículos 105 a 113.
  - Título II: productores de fonogramas, artículos 114 a 119.
  - Título III: productores de grabaciones audiovisuales, artículos 120 a 125.
  - Título IV: entidades de radiodifusión, artículos 126 a 127.

## Solapamiento entre ambos PDF

Los documentos se solapan. El segundo PDF ya incluye desde los artículos 103 y 104 y empieza además el Título I del Libro Segundo con los artículos 105 a 108. El primero continúa ese mismo bloque y lo desarrolla completo hasta el artículo 127.

En la práctica:

- Para programas de ordenador, el documento clave es Título7.pdf.
- Para derechos afines del Libro Segundo, el documento más completo es Título1,2y3.pdf.

## Síntesis jurídica de fondo

### 1. Obras audiovisuales: cierre del régimen específico

#### Artículo 91. Aportación insuficiente de un autor

- Si un autor no completa su aportación por negativa injustificada o por fuerza mayor, el productor puede usar la parte ya realizada.
- Debe respetar los derechos del autor sobre esa parte.
- Puede haber indemnización si procede.

Idea clave: la producción audiovisual no queda paralizada automáticamente por el incumplimiento o la imposibilidad de uno de los autores.

#### Artículo 92. Versión definitiva y modificaciones

- La obra audiovisual se considera terminada cuando queda fijada la versión definitiva pactada entre director-realizador y productor.
- Cualquier modificación posterior necesita autorización previa de quienes acordaron esa versión definitiva.
- En obras destinadas esencialmente a radiodifusión se presume autorizada la adaptación técnica estrictamente necesaria para la emisión, salvo pacto en contrario.

Idea clave: se protege la integridad de la versión final, pero se admite cierta flexibilidad técnica en el entorno de la radiodifusión.

#### Artículo 93. Derecho moral y destrucción del soporte original

- El derecho moral de los autores solo se ejerce sobre la versión definitiva.
- Se prohíbe destruir el soporte original de esa versión definitiva.

Idea clave: la ley vincula la protección moral al resultado final cerrado, no a estados intermedios del proceso creativo.

#### Artículo 94. Obras radiofónicas

- Las reglas del título se aplican, en lo pertinente, a las obras radiofónicas.

Idea clave: hay una extensión analógica del régimen audiovisual a la creación radiofónica.

### 2. Programas de ordenador: núcleo normativo más importante

Este bloque es probablemente el más relevante si el interés del material es tecnología, software o derechos digitales.

#### Artículo 95. Régimen jurídico

- Los programas de ordenador tienen un régimen especial propio.
- En lo no previsto expresamente, se aplica supletoriamente la Ley de Propiedad Intelectual general.

Idea clave: el software no se trata exactamente igual que otras obras; tiene reglas específicas.

#### Artículo 96. Objeto de la protección

- Se protege cualquier secuencia de instrucciones o indicaciones destinada a ser utilizada en un sistema informático para realizar una función o tarea o producir un resultado.
- Se incluyen también la documentación preparatoria, la documentación técnica y los manuales de uso.
- Solo se protege si el programa es original, entendido como creación intelectual propia de su autor.
- La protección alcanza cualquier forma de expresión del programa, sus versiones sucesivas y programas derivados.
- Quedan excluidas las creaciones destinadas a producir efectos nocivos en un sistema informático.
- Si el programa forma parte de una patente o modelo de utilidad, puede coexistir con protección de propiedad industrial.
- No se protegen por derecho de autor las ideas y principios subyacentes, incluidas las bases conceptuales de las interfaces.

Idea clave: la ley protege la expresión del software, no las ideas abstractas que hay detrás.

#### Artículo 97. Titularidad de los derechos

- Es autor quien crea el programa, individual o colectivamente, salvo los supuestos de persona jurídica admitidos por la ley.
- En obra colectiva, salvo pacto en contrario, la titularidad corresponde a quien la edita y divulga bajo su nombre.
- En programas creados en colaboración, los derechos son comunes a los coautores en la proporción que determinen.
- En software creado por trabajador asalariado en el ejercicio de sus funciones o siguiendo instrucciones del empresario, los derechos de explotación corresponden al empresario, salvo pacto en contrario.

Idea clave: en software laboral la regla por defecto favorece claramente al empleador.

#### Artículo 98. Duración de la protección

- Si el autor es persona natural, la duración sigue el régimen general aplicable en la ley.
- Si el autor es persona jurídica, la duración es de setenta años desde el 1 de enero del año siguiente a la divulgación lícita o, si no la hay, a la creación.

#### Artículo 99. Contenido de los derechos de explotación

El titular puede autorizar o prohibir:

- La reproducción total o parcial, incluso para uso personal, tanto permanente como transitoria.
- La traducción, adaptación, arreglo o cualquier transformación, y la reproducción de sus resultados.
- Cualquier forma de distribución pública, incluido el alquiler.

También fija dos reglas importantes:

- La cesión de uso se presume no exclusiva e intransferible, salvo prueba en contrario.
- La primera venta en la Unión Europea agota el derecho de distribución sobre esa copia, salvo el control del alquiler posterior.

Idea clave: el software tiene un derecho de explotación muy intenso, pero la distribución se agota con la primera venta dentro de la UE.

#### Artículo 100. Límites a los derechos de explotación

Es uno de los artículos más relevantes del conjunto.

- No requiere autorización la reproducción o transformación necesaria para el uso legítimo del programa conforme a su finalidad, incluida la corrección de errores, salvo pacto contractual en contrario.
- La copia de seguridad necesaria para el uso no puede prohibirse por contrato.
- El usuario legítimo puede observar, estudiar o verificar el funcionamiento del programa para conocer las ideas y principios implícitos, siempre que lo haga durante operaciones que tiene derecho a realizar.
- Se permite la reproducción del código y la traducción de su forma cuando sea indispensable para obtener la información necesaria para la interoperabilidad con un programa independiente, pero solo si se cumplen requisitos estrictos:
  - Debe hacerlo un usuario legítimo o persona autorizada.
  - La información necesaria no debe estar ya disponible de forma fácil y rápida.
  - Los actos deben limitarse a las partes necesarias para la interoperabilidad.
- La información obtenida por descompilación para interoperabilidad:
  - Solo puede usarse para lograr esa interoperabilidad.
  - Solo puede comunicarse a terceros cuando sea necesario para ese mismo fin.
  - No puede usarse para desarrollar ni comercializar un programa sustancialmente similar ni para otros actos infractores.
- La excepción no puede interpretarse de forma que perjudique injustificadamente los intereses legítimos del titular ni la explotación normal del programa.

Idea clave: la ley admite ingeniería inversa limitada para interoperabilidad, pero la encierra en una excepción muy tasada.

#### Artículo 101. Protección registral

- Los programas, sus versiones sucesivas y los programas derivados pueden inscribirse en el Registro de la Propiedad Intelectual.
- La consulta pública de determinados elementos se remite al desarrollo reglamentario.

#### Artículo 102. Infracción de los derechos

Se consideran infractores, sin autorización del titular:

- Quienes realicen los actos del artículo 99.
- Quienes distribuyan copias ilegítimas sabiendo o pudiendo presumir su ilicitud.
- Quienes posean con fines comerciales copias ilegítimas.
- Quienes comercialicen instrumentos destinados exclusivamente a suprimir o neutralizar protecciones técnicas del programa.

Idea clave: la infracción no se limita a copiar; incluye tráfico comercial y herramientas de elusión.

#### Artículo 103. Medidas de protección

- El titular puede ejercitar acciones y procedimientos generales de defensa previstos en la ley y solicitar medidas cautelares conforme a la Ley de Enjuiciamiento Civil.

#### Artículo 104. Salvaguardia de otras normas

- Este título no excluye otras protecciones concurrentes: patentes, marcas, competencia desleal, secretos comerciales, protección de semiconductores u obligaciones.

Idea clave: el software puede quedar cubierto por varias capas normativas a la vez.

### 3. Artistas intérpretes o ejecutantes

#### Ámbito general

El Título I del Libro Segundo protege a quienes interpretan o ejecutan obras, no a los autores de la obra en sí. Incluye expresamente a directores de escena y de orquesta.

#### Artículos 105 a 109. Derechos patrimoniales básicos

- Derecho exclusivo de autorizar la fijación de las actuaciones.
- Derecho exclusivo de autorizar la reproducción de esas fijaciones.
- Derecho exclusivo de autorizar la comunicación pública, con especial atención a la puesta a disposición del público en línea.
- Derecho exclusivo de distribución de las fijaciones.
- Estos derechos pueden transferirse, cederse o licenciarse en los casos previstos.
- La autorización debe constar por escrito.

El texto añade varios matices de gran importancia:

- Si el artista celebra contrato con productor de fonogramas o grabaciones audiovisuales, se presume cedido el derecho de puesta a disposición del público, salvo pacto en contrario.
- Aun así, conserva un derecho irrenunciable a remuneración equitativa cuando esa puesta a disposición se realiza.
- Los usuarios de fonogramas y determinadas grabaciones audiovisuales utilizados en actos de comunicación pública deben pagar remuneración equitativa.
- La gestión efectiva de estas remuneraciones se articula a través de entidades de gestión.
- En distribución, el derecho se agota con la primera venta en la UE.
- Se definen separadamente alquiler y préstamo.
- Aunque el derecho de alquiler puede presumirse cedido al productor, el artista conserva remuneración equitativa irrenunciable.

Idea clave: el sistema combina cesiones presuntas amplias con núcleos de remuneración irrenunciable para los intérpretes.

#### Artículo 110. Contrato de trabajo o arrendamiento de servicios

- Si la interpretación se realiza en el marco de un contrato laboral o de servicios, se presume que empresario o arrendatario adquieren los derechos de reproducción y comunicación pública deducibles de la naturaleza del contrato.
- Esa presunción no afecta a ciertos derechos de remuneración del artículo 108.
- La remuneración pactada queda sujeta al régimen general de remuneración del artículo 47.
- Se extienden a intérpretes y ejecutantes el derecho de revocación y las obligaciones de información del cesionario previstas en la normativa más reciente.

Idea clave: la ley favorece la explotación empresarial de la interpretación, pero mantiene ciertas salvaguardas económicas y de transparencia.

#### Artículo 110 bis. Cesión al productor de fonogramas

Es uno de los artículos más específicos y materialmente relevantes del bloque.

- Si, transcurridos cincuenta años desde la publicación o comunicación lícita, el fonograma deja de explotarse de forma suficiente, el artista puede resolver el contrato de cesión con el productor.
- El productor tiene un plazo de un año desde la notificación para reactivar la explotación suficiente.
- Este derecho de resolución es irrenunciable.
- Si el contrato establecía remuneración única, el artista tiene derecho además a una remuneración anual adicional a partir de ese momento.
- El deudor debe destinar a esa remuneración el 20 por ciento de determinados ingresos brutos de explotación.
- Quedan excluidas del cálculo ciertas cantidades, como copia privada y alquiler de fonogramas.
- Los deudores están obligados a facilitar información anual a la entidad de gestión para asegurar el pago.
- Si el artista tenía derecho a pagos periódicos, no pueden descontarse anticipos ni deducciones contractuales una vez cumplidos los cincuenta años.

Idea clave: se introduce una corrección protectora a largo plazo frente a cesiones antiguas o económicamente agotadoras para el intérprete.

#### Artículo 111. Representación del colectivo

- Cuando varios artistas participan colectivamente en una misma actuación, deben designar representante por acuerdo mayoritario y por escrito.
- La obligación no alcanza a solistas ni a directores de orquesta o de escena.

#### Artículo 112. Duración

- Regla base: cincuenta años desde el 1 de enero del año siguiente a la interpretación o ejecución.
- Si la grabación se publica o comunica lícitamente al público por medio distinto del fonograma, el plazo corre desde ese acto y sigue siendo de cincuenta años.
- Si la publicación o comunicación se produce en fonograma, la duración sube a setenta años.

#### Artículo 113. Derechos morales

- Derecho irrenunciable e inalienable al reconocimiento del nombre, salvo que la forma de utilización justifique la omisión.
- Derecho a oponerse a deformaciones o atentados contra la actuación que lesionen prestigio o reputación.
- Para doblar la actuación en su propia lengua hace falta autorización expresa del artista durante toda su vida.
- Tras su muerte, ciertos legitimados pueden ejercer esos derechos sin límite temporal.

Idea clave: el estatuto del intérprete no es solo económico; conserva una dimensión moral fuerte, especialmente en reconocimiento e integridad.

### 4. Productores de fonogramas

#### Artículo 114. Definiciones

- Fonograma: fijación exclusivamente sonora de una ejecución u otros sonidos.
- Productor: quien impulsa y asume la responsabilidad de la primera fijación.

#### Artículos 115 a 117. Derechos patrimoniales

- Derecho exclusivo de reproducción.
- Derecho exclusivo de comunicación pública en la puesta a disposición del público.
- Derecho exclusivo de distribución.
- Importación y exportación con fines de comercialización incluidas en la distribución.
- Definición legal de alquiler y préstamo.
- Agotamiento del derecho de distribución tras primera venta en la UE.

Además:

- Los usuarios de fonogramas usados para comunicación pública deben pagar remuneración equitativa y única a productores y artistas, con reparto igualitario en defecto de acuerdo.
- La recaudación y distribución se canaliza a través de entidades de gestión.

#### Artículo 118. Legitimación activa

- Tanto el productor como el cesionario pueden ejercitar acciones por infracción de los derechos de reproducción y distribución.

#### Artículo 119. Duración

- Cincuenta años desde la grabación.
- Si hay publicación lícita dentro de ese plazo, la duración pasa a setenta años desde la primera publicación.
- Si no hay publicación pero sí comunicación lícita al público, también pasa a setenta años desde esa primera comunicación.

Idea clave: el productor fonográfico tiene una protección patrimonial fuerte y estrechamente asociada a la explotación comercial del fonograma.

### 5. Productores de grabaciones audiovisuales

#### Artículo 120. Definiciones

- Grabación audiovisual: fijación de plano o secuencia de imágenes, con o sin sonido, aunque no llegue a ser obra audiovisual en sentido estricto.
- Productor: quien toma la iniciativa y asume la responsabilidad de la grabación.

#### Artículos 121 a 124. Derechos

- Derecho exclusivo de reproducción del original y sus copias.
- Derecho de autorizar la comunicación pública.
- Derecho exclusivo de distribución del original y las copias.
- Derecho sobre alquiler y préstamo, con las exclusiones legales correspondientes.
- Derecho de explotación sobre las fotografías realizadas durante el proceso de producción de la grabación audiovisual.

También se prevé:

- Obligación de pagar remuneración a artistas y productores cuando determinadas grabaciones se utilicen en actos de comunicación pública.
- Gestión de esa remuneración a través de entidades de gestión.
- Agotamiento de la distribución con la primera venta en la UE.

#### Artículo 125. Duración

- Cincuenta años desde el 1 de enero del año siguiente a la realización.
- Si se divulga lícitamente dentro de ese plazo, cuenta desde la divulgación.

Idea clave: la ley distingue claramente entre obra audiovisual y simple grabación audiovisual, pero dota a esta última de un paquete propio de derechos conexos.

### 6. Entidades de radiodifusión

#### Artículo 126. Derechos exclusivos

Las entidades de radiodifusión pueden autorizar o prohibir:

- La fijación de sus emisiones o transmisiones.
- La reproducción de esas fijaciones.
- La puesta a disposición del público de las fijaciones.
- La retransmisión por cualquier procedimiento técnico.
- La comunicación pública de sus emisiones en lugares de acceso pagado.
- La distribución de las fijaciones.

Reglas complementarias importantes:

- Las empresas de distribución por cable no tienen el derecho de fijación cuando solo retransmiten emisiones ajenas.
- El derecho de distribución también se agota con la primera venta en la UE.
- Los conceptos de emisión, transmisión y retransmisión se conectan expresamente con el artículo 20 de la ley.

#### Artículo 127. Duración

- Cincuenta años desde el 1 de enero del año siguiente a la primera emisión o transmisión.

Idea clave: la radiodifusión recibe un haz autónomo de derechos sobre la señal emitida, distinto del de autores, intérpretes o productores.

## Ideas transversales que se repiten en ambos PDF

### Protección en capas

El material deja claro que un mismo objeto puede acumular varias capas de protección:

- Autoría sobre la obra.
- Derechos de intérpretes o ejecutantes.
- Derechos del productor fonográfico o audiovisual.
- Derechos de entidades de radiodifusión.
- Eventualmente patentes, marcas, secretos comerciales u otras figuras en el caso del software.

### Cesión amplia, pero con límites irrenunciables

La ley permite muchas cesiones o presunciones de cesión, sobre todo en entornos industriales, laborales o de producción. Sin embargo, preserva varios núcleos duros:

- Remuneraciones equitativas irrenunciables.
- Derechos morales.
- Derechos de información o resolución en escenarios concretos.
- Límites de uso legítimo en software.

### Agotamiento en la Unión Europea

Aparece repetidamente la regla de agotamiento tras la primera venta en la UE en distribución de copias, aunque normalmente se mantiene aparte el control del alquiler.

### Importancia de las entidades de gestión

Muchas remuneraciones no se reclaman directamente por el titular individual, sino a través de entidades de gestión, que negocian, recaudan y reparten.

## Qué es lo más importante si tu foco es informática o software

Si el objetivo del estudio es tecnología, lo más valioso del conjunto está en los artículos 95 a 104:

- El software se protege por derecho de autor, pero solo en su expresión original.
- Las ideas, principios e interfaces en su dimensión conceptual no quedan apropiadas por esa vía.
- En software laboral, la explotación pertenece por defecto al empresario.
- El usuario legítimo puede corregir errores, hacer copia de seguridad, estudiar el programa y, en ciertos casos, descompilar para interoperabilidad.
- La excepción de interoperabilidad es estrecha y finalista: sirve para compatibilidad, no para clonar el programa.
- La infracción incluye tanto la copia como la comercialización de copias ilícitas o herramientas de neutralización de protecciones.

## Observaciones sobre calidad de la extracción

- La conversión de MarkItDown ha sido suficiente para recuperar prácticamente todo el contenido textual.
- Hay algunos cortes de línea internos y separación irregular de palabras, pero no impiden el análisis.
- Los encabezados de página del BOE y las marcas de página permanecen en el texto extraído.
- Los dos PDF no son autónomos entre sí; están recortados desde puntos distintos del mismo cuerpo legal.

## Conclusión operativa

Los PDF no son apuntes ni material doctrinal, sino extractos normativos directos. El contenido principal puede resumirse así:

- Se cierra el régimen de obras audiovisuales.
- Se regula en detalle el estatuto jurídico del software.
- Se desarrolla el bloque de derechos afines: intérpretes, productores de fonogramas, productores de grabaciones audiovisuales y entidades de radiodifusión.

Si hubiera que priorizar para estudio:

1. Artículos 95 a 104, por su relevancia para programas de ordenador.
2. Artículos 105 a 113, por el régimen económico y moral de intérpretes y ejecutantes.
3. Artículos 114 a 127, para entender la arquitectura de derechos conexos y de explotación industrial.