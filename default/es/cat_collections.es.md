Esta sección describe cómo catalogar tipos especiales de fuentes: volúmenes compuestos, _contrafacta_, compilaciones, parodias, materiales mixtos (ítems manuscritos e impresos que se almacenan juntos), música en periódicos, música en publicaciones no musicales, tratados y arreglos para piano.

### Catalogación de colecciones

En RISM, se entiende como _colección_ tanto a un manuscrito que ha sido concebido intencionalmente como conjunto o antología de obras múltiples, como también a un ítem sencillo que contiene dos o más piezas separadas. Esto último implica que, en caso de que un manuscrito de una sonata para piano, por ejemplo, incluya un borrador de una fuga justo al final, RISM lo catalogará como una colección con un registro madre para el documento en general y entradas individuales para la sonata y la fuga.

Al catalogar colecciones, tenga en cuenta que:

1. La entrada principal de la colección (registro madre) debe contener información que aplique a toda la colección.
2. Cualquier información que sea relevante sólo para algunas secciones de la colección debe ser registrada en la entrada individual.

Si las obras de la colección son de distintos compositores o presentan diferente plantilla/orgánico, tipo de fuente, etc., no ingrese estos datos en el registro madre.

En el caso de colecciones compuestas por obras muy similares entre sí, es una buena estrategia crear una primera entrada con todos los datos correspondientes a una obra y usar la función “Duplicar” para copiar el registro. Luego, para los registros siguientes sólo restará cambiar campos tales como el título y el número de páginas.

Los registros madre de colección no pueden albergar registros madre de colección de manuscritos. En su lugar, trabaje con una estructura menos jerarquizada, con registros individuales y explique la conformación u organización del ítem en una nota.

### Catalogación de volúmenes compuestos

Un **Volumen compuesto** es un volumen integrado por documentos que fueron creados por separado y encuadernados juntos posteriormente, usualmente por un propietario o una institución. Hay otros nombres para este tipo de volúmenes: _bound-with, Sammelband,&nbsp;_volumen de encuadernador, volumen de colector.&nbsp;En este conjunto se incluyen tanto los volúmenes en los que una suma de ítems impresos fue encuadernada en conjunto, como también aquellos en los que piezas impresas aparecen encuadernadas junto a manuscritos.

Hay dos maneras de señalar la presencia de volúmenes compuestos. La primera y más simple consiste en dar a los ítems la misma signatura; también resulta útil una nota de encuadernación. La segunda forma consiste en utilziar la plantilla para volúmenes compuestos.

El registro de volúmen compuesto sirve como medio para vincular los ítems en un único registro, proveyendo, de esa manera, al usuario un panorama conveniente de todos los contenidos de un volumen encuadernado.

Es conveniente que los registros de volúmenes compuestos sean simples. Tal como con los registros madre de colección, la información consignada en el registro de volumen compuesto debería aplicar a todos los componentes del volumen, teniendo en cuenta que la información detallada en relación con la música corresponde a los registros bibliográficos respectivos. No cree registros separados para múltiples volúmenes compuestos que van juntos, tales como un conjunto de libros de partes ecuadernados por tipo de voz; es mejor que se los describa en el mismo registro. En muchos casos, deberá dejar muchos campos en blanco.

Con este tipo de documentos, deberá vincular&nbsp;tanto ítems manuscritos como impresos al registro de volumen compuesto; en cada caso el procedimiento es diferente.

1. Primero, cree el registro para el volumen compuesto, guárdelo y anote el número de RISM.
2. Para los manuscritos: en el modo de edición del registro de su manuscrito, vaya al campo **Registro madre (773)**. Haga click en el segundo botón (lupa de la derecha) para buscar el volúmen compuesto.
3. Para la música impresa: en el registro de ejemplar correspondiente a la copia de su repositorio, busque el campo **Encuadernado con (973)** y haga click en la lupa. Encuentre el registro del volúmen compuesto y selecciónelo.

### Catalogación de&nbsp;_contrafacta_

Los&nbsp;_Contrafacta&nbsp;_(sing.&nbsp;_Contrafactum_)_&nbsp;_son piezas vocales en las cuales se reemplaza el texto sin realizar cambios significativos a la música, como en el caso de las obras seculares cuyo texto es reemplazado por uno sacro, o viceversa. La derivación es casi mecánica; hay poca creatividad en juego de parte del arreglador, aunque se plantea un cambio significativo en el propósito musical de la pieza (por ejemplo, el desplazamientpo de un contexto teatral a otro religioso).  
  
Por favor, nótese que RISM diferencia a los&nbsp;_contrafacta&nbsp;_de&nbsp;la parodia y las misas de parodia, las cuales, por lo general, involucran una transformación más significativa del material musical.  
  
Preste atención a&nbsp;los siguientes campos al catalogar&nbsp;_contrafacta._&nbsp;A continuación se usará como ejemplo el ID de RISM n.° 300234487, un&nbsp;_contrafactum_  
sacro de un aria de la ópera&nbsp;_Il Bellerofonte_, de Josef Mysliveček.

**Compositor/autor (100)**  
Registre el compositor de la música original.

- Mysliveček, Josef

**Título uniforme (240)**  
Utilice el título uniforme de la pieza original. Puede seleccionar el calificador&nbsp; **Extractos&nbsp;** en el subcampo&nbsp; **Tipo especial de fuente,&nbsp;** de ser necesario. No use el calificador&nbsp; **Arreglo**.

- _Il Bellerofonte.&nbsp;_Extractos

**Título alternativo (730)**  
Si la pieza con&nbsp;_contrafactum_&nbsp;presenta un título uniforme nuevo y distintivo, regístrelo en este campo. No ingrese incipits literarios en este campo.

**Descriptores (650)**  
Agregue al menos 3 descriptores (o más, si es necesario), en el siguiente orden:  
_Contrafacta_  
Género actual (= género del contrafactum)  
Género original

- _Contrafacta_
- _Sacred songs_
- _Operas_

**Descripción sumaria (520)**  
Añada una descripción breve en inglés que explique la situación, como un servicio a otros usuarios de RISM.

- _Sacred contrafactum of an aria from Mysliveček's opera Il Bellerofonte._  
(Contrafactum sacro de un aria de la ópera Il Bellerofont, de Mysliveček)

**Idioma del texto (041)**  
Complete cada uno de estos dos campos:  
Idioma del texto (041 $a): correspondiente al texto actual del&nbsp;_contrafactum_.  
Idioma del texto original (041 $h): correspondiente a la pieza original.

- Idioma del texto: Latín
- Idioma del texto original: Italiano

**Íncipit literario (031 $t)**  
Se registrarán los dos íncipits literarios (use el + para añadir una nueva línea).  
Íncipit literario del texto actual (_contrafactum_)  
Íncipit literario del texto&nbsp;original, si se lo conoce, entre corchetes.

- Alma redemptoris mater, quae pervia caeli
- [Giusti dei che ben vedete]

**Otros campos**

Todos los otros campos, tales como la festividad litúrgica y la plantilla/orgánico, deben referir a la fuente que se cataloga, esto es, al&nbsp;_contrafactum&nbsp;_mismo, y no a la obra original en el cual se basa.

### Catalogación de compilaciones

Las compilaciones constituyen obras nuevas e independientes hechas a partir de partes de una o más obras que también pueden incluir material nuevo. Con frecuencia, la obra resultante es de un género diferente al de las partes que la componen, como cuando las arias o dúos de una ópera se convierten en una cantata, o los extractos de una ópera se convierten en una suite instrumental. Esto también incluye los pasticcios. Si bien la frontera entre una compilación y un pasticcio no siempre es clara, los pasticcios pueden ser caracterizados generalmente por uno de estos rasgos: 1) arias, duetos o partes más grandes de obras dramáticas que se adaptan a un nuevo libreto; 2) varias obras independientes que se combinan para crear una nueva obra; o 3) composiciones colaborativas concebidas como tales desde el principio.&nbsp;

Las compilaciones se pueden cargar en un solo registro, o bien como colecciones.&nbsp;

Al catalogar compilaciones, tenga en cuenta los siguientes campos:

**Compositor/Autor (100)**  
El compositor es, en todos los casos, **Compilations** (Compilaciones).&nbsp;

**Nombre personal adicinal (700)**  
El nombre del compilador puede ser añadido con la función **Editor**.

En el caso de las compilaciones, registre a cada compositor/a del material original con función **Referencia cruzada de compositor** , y a cada compositor/a del nuevo material con la función **Co-compositor**.&nbsp;

En el caso de los pasticcios, no registre compositoras/es como Referencias cruzadas de compositor. En su lugar, cargue a cada compositor/a como **Co-compositor**.

**Título estandarizado (240)**  
Introduzca el título estandarizado de la fuente en cuestión. Para los pasticcios, añada seleccione **Extractos** o **Arreglo** según corresponda.&nbsp;

**Código de idioma (041)**  
Para el campo **Idioma del texto** , introduzca el idioma de la fuente en cuestión. Si corresponde, se puede introducir el idioma de la obra original en **Idioma del texto original**.

**Descriptor (650)**  
El primer descriptor debe ser **Compilations** (Compilaciones) y/o **Pasticcios**. El segundo corresponde al género de la fuente en cuestión. En el caso de los extractos, se puede añadir el género del extracto. Otra opción es **Collaborative compositions** (Composiciones colaborativas).

**Descripción sumaria (520)**  
Utilice este campo para describir la naturaleza de la fuente en general.  
[N. del T.: recuerde que este campo debe estar en inglés]  
_Ejemplo_:  
Act 1 by Amadei, act 2 by Bononcini, overture and act 3 by Händel [= Acto 1 de Amadei, acto 2 de Bononcini, obertura y acto 3 de Händel]

**Título alternativo (730)**  
Escriba el título uniforme de la(s) pieza(s) original(es), seleccionando **Extractos** o **Arreglo** según corresponda. También puede introducir títulos _ossia_.

**Catálogo de obras (690)**  
Puede introducir el número de catálogo de obras tanto para la compilación como para las obras originales.&nbsp;

**Incipit literario (031)**  
Introduzca el texto de la fuente en cuestión. También puede introducir el texto original entre corchetes, si lo conoce.&nbsp;

**Nota general (500)**  
Utilice siempre una nota para aclaraciones, especialmente si se trata de obras de compositores distintos. Esto asegura que los compositores se correspondan con las obras utilizadas en la compilación.&nbsp;

**Nota sobre ocasión de interpetación (518)**  
Las interpretaciones deben ser señaladas sólo en la medida en que se relacionen con la compilación misma.

**Ejemplos de compilaciones:**

230001408: Cantata hecha de arias de ópera con recitativos de nueva composición

702000623: Suite hecha de partes de una ópera

700007222: Varias obras de un mismo compositor utilizadas para crear una nueva cantata

702000642, 702000643: Varias obras de varios compositores utilizadas para crear una nueva suite

452505748: Un ópera pasticcio que consiste en 3 actos de 3 compositores diferentes

### Catalogación de Parodias

Una parodia es una composición basada en material preexistente que da lugar a una nueva obra. En el siglo XIX, el término adquiere un sesgo satírico.&nbsp;&nbsp;

El registro 150205470 será usado como ejemplo.

&nbsp;

#### Compositor (100)

Introduzca el compositor de la música para la fuente en cuestión.

- Weyse, Christoph Ernst Friedrich

#### Nombre personal adicional (700)  

Introduzca el compositor del material preexistente y seleccione la función Referencia cruzada de compositor.

- Rossini, Gioachino

#### Título uniforme (240)  

Introduzca el título uniforme de la fuente en cuestión.

- Dannemark hellige lyd

#### Título adicional (730)  

Introduzca el título del material preexistente. Seleccion Extractos según corresponda. No utilice Arreglos o Variaciones.

- Tancredi. Extractos

#### Descriptor (650)  

Introduzca **Parodies** (Parodias) como primer Descriptor. Registre el género de la fuente en cuestión como segundo descriptor, y el género del material preexistente como tercer descriptor.

- Parodias
- Himnos nacionales
- Ópera

#### Código de idioma (041)  

Introduzca el idioma de la fuente en cuestión en el campo Idioma del texto. Introduzca el idioma del material preexistente en el campo Idioma del texto original.

- Danés
- Italiano

#### Incipits literarios (031)  

Introduzca el incipit literario de la fuente en cuestión. También puede introducir el texto original entre corchetes, si lo conoce.&nbsp;

- Dannemark hellige lyd
- [Di tanti palpiti]

#### Otros campos  

Todos los demás campos, como la información sobre las interpretaciones, deben referirse únicamente a la fuente en cuestión.

### **Catalogación de materiales mixtos (manuscritos e ítems impresos que se conservan juntos)**

No es extraño que manuscritos e impresos correspondientes a una misma música se encuentren agrupados en la misma carpeta o bajo la misma signatura: por ejemplo, una partitura impresa con particellas manuscritas, o un grupo de particellas impresas junto con otras manuscritas.

Idealmente, el material impreso debería catalogarse en un registro separado, dado que es posible que otros repositorios tengan copias de la misma edición. Cree un registro para el item impreso, añada sus registros de ejemplar y, en adición,&nbsp;cree otro registro para los materiales manuscritos. Incluya referencias cruzadas de manera que el usuario pueda comprender las existencias del repositorio. [Nota de traducción: la referencia cruzada va en una Nota General (500)]

Ejemplo: el registro con ID de RISM 280000006 refiere a 4 particellas manuscritas de una overtura. El 990055636 es un registro para las particellas impresas. El repositorio ha hañadido sus registros de ejemplar a esas particellas. Una nota en cada registro remite al usuario al otro material.

No siempre es factible crear dos registros: quizá su ítem impreso no contiene información suficiente como para crear un registro adecuado. En tales casos, proceda de la siguiente manera: catalogue su material usando una plantilla de manuscrito. En la sección de la descripción material, describa los materiales de un tipo (por ejemplo, los materiales manuscritos). Luego añada un grupo de material adicional, y describa los materiales del otro tipo (por ejemplo, los impresos).

### **Catalogación de música publicada en periódicos**

Existen dos maneras de catalogar periódicos que contienen música: como colección o como obra individual. En cada caso, el título del periódico, con el número de edición y el año, se registran en el campo&nbsp;**Título adicional (730).**&nbsp;

Las&nbsp; **Colecciones&nbsp;** resultan&nbsp;apropiadas en los casos en los que el periódico consiste en su mayor parte de música y el ítem fue reunido y preservado en su totalidad. Los registros de ejemplar se añaden al nivel de la colección. Se crean entradas individuales para cada pieza de la edición.

_Ejemplo_:  
1001097294: Edición de enero (año preciso incierto) de la&nbsp;_Kleine Pianoforte-Bibliothek_, que contiene 5 piezas. Hay un registro madre para la colección y cinco entradas individuales, una para cada pieza.&nbsp;

Las&nbsp; **Piezas individuales&nbsp;** pueden resultar apropiadas en los casos en los que las obras fueron incluidas como inserciones o agregados en periódicos no especializados (es decir, sin foco en lo musical). Frecuentemente, este tipo de ítem se conserva por fuera de su contexto de publicación.

_Ejemplos_:&nbsp;&nbsp;  
991018149: "The Pantheon" publicado en&nbsp;_The Lady's Magazine_, Agosto de 1784  
990042111: "L'amour folâtrant l'autre jour" publicado en&nbsp;_Nouveau Mercure galant_, Mayo de 1679

###   
**Catalogación de música presente en publicaciones no-musicales**  

RISM también incluye música presente en publicaciones impresas que fueron concebidas como documentos fundamentalmente no musicales. El foco de RISM, no obstante, se ubica sobre la música

_Ejemplo_:&nbsp;  
990026614: 3 canciones de John Isaac Hawkins que fueron incluidas en&nbsp;_Discourse introductory to a course of lectures on the science of nature&nbsp;_(1800), de Charles Willson Peale.  
**Compositor/Autor (100)**: el compositor de la música.  
**Nombre personal adicional (700)**: el autor del libro, con la indicación&nbsp; **other**  
**Título en fuente (diplomático) (245)**: título del libro  
**Título uniforme (240)**: un título uniforme que siga las reglas de RISM, en este caso&nbsp; **_3 Songs&nbsp;_** (tres canciones)  
**Decripción física (300)**: una descripción correspondiente a la música, por ejemplo,&nbsp; **1 score: 5 p.&nbsp;&nbsp;**  
  
Luego se pueden crear las entradas individuales para cada pieza, siguiendo las reglas normales de RISM.

### Catalogación de tratados

Cuanto se catalogan tratados, el campo **Formato, extensión (300 $a)** debe incluir, por lo general, **_text document_** (documento de texto)&nbsp;como formato.

Entre los descriptores apropiados para tratados aparecen los siguientes casos:

- **Treatises** [Tratados]
- **Writings&nbsp;** [Escritos]
- **Music theory&nbsp;** [Teoría musical]
- **Theory of harmony&nbsp;** [Teoría de la armonía]
- **Tutors (inst.).** [Tutores instrumentales].&nbsp;Incluye métodos y escuelas.
- **Tutors (voc.).**&nbsp;[Tutores vocales]. Incluye métodos y escuelas.
- **Contrapuntal studies (inst./voc.).&nbsp;**[Estudios de contrapunto (instrumentales/vocales)].&nbsp;
- **Solfeggios (voc.)&nbsp;**[Solfeos (vocales)]&nbsp;
- **Solfeggios (inst.)&nbsp;**[Solfeos (instrumentales)]
- **Scales (inst./voc.)&nbsp;**[Escalas (instrumentales/vocales)]

Pueden agregarse descriptores adicionales.

### Catalogación de arreglos para piano

Especifique los arreglos para piano del siguiente modo:

- En el campo **Título** **uniforme (240)**:
  - Seleccione **Arreglo** en el subcampo **Mención de arreglo.**
  - En **Resumen de plantilla/orgánico** , ingrese la plantilla/orgánico del arreglo, por ej. **pf** o **V, pf**. No ingrese la plantilla/orgánico de la obra original.
- En el campo **Plantilla/orgánico total (594),** ingrese la plantilla/orgánico total correspondiente al **arreglo**. No ingrese los datos correspondientes a la obra original.
- En el campo **Descripción física (300)** registre el formato como **_keyboard score_** (partitura de teclado) si se trata de una reducción para piano, o **_vocal score_** (partitura vocal) si la reducción es para voz y piano.