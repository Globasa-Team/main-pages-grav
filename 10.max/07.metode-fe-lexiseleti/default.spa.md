---
title: 'Metodología de desarrollo léxico'
---

## Metodología de desarrollo léxico del Globasa

**Paso Preliminar**: Antes de apresurarse a expandir el diccionario de Globasa con una nueva palabra raíz, determine si la palabra deseada puede expresarse potencialmente a través de una palabra raíz ya establecida o mediante un método de formación de palabras (mediante afijos o palabras compuestas). Con base en esa determinación, decida si propone o no una nueva palabra raíz.

**Metodología en tres partes:**

(1) Establecer la fuente etimológica de la palabra

(2) Determinar la semántica de la palabra

(3) Determinar la forma exacta (letras) de la palabra

## Establecimiento de la fuente etimológica

### Advertencias

Las siguientes advertencias deben tenerse en cuenta durante el proceso de selección de fuentes. Siempre que sea necesario, se debe hacer un esfuerzo para adaptar las formas de las palabras en función de las advertencias a continuación utilizando la fuente etimológica más internacional. Sin embargo, si esto no es posible, se debe utilizar una fuente internacional menos amplia.

- _Nunca_ adopte pares mínimos con _v_ y _w_, _s_ y _z_, o con _m_ y _n_ en posición final de palabra

- A menos que no haya absolutamente ninguna otra opción y se haya investigado a fondo por posibles problemas con las palabras adjuntas, _nunca_ adopte pares mínimos con más/menos una consonante o vocal al principio/final de las palabras.

- Siempre que sea posible, evitar parejas mínimas con _l_ y _r_, _b_ y _p_, _f_ y _p_, _c_ y _j_, _c_ y _x_, _h_ y _r_ o pares mínimos con más/menos una vocal al principio/final de las palabras.

- Siempre que sea posible, evitar _cualquier_ par mínimo: Siempre que haya más de una opción de _forma de palabra_ más o menos igual, elegir la forma que no crea un par mínimo.

- Siempre que sea posible, evitar palabras monosílabas y palabras de más de tres sílabas: Siempre que haya más de una opción de _fuente_ más o menos igual, elegir la fuente de dos o tres sílabas, o añadir una vocal [_a posteriori_](/pimpan-swal/metode-fe-lexiseleti#a_posteriori) para producir una palabra de dos sílabas. Además, tenga en cuenta que Globasa prefiere las palabras de tres sílabas a las de dos sílabas.

- Siempre que sea posible, evitar palabras que parezcan llevar afijos: Siempre que haya más de una opción de _forma de palabra_ más o menos igual, elegir la forma que no parezca llevar afijos.

### Algoritmo de selección de fuente

- Verifique los siguientes idiomas en fuentes en línea como Google Translate, [Wiktionary](https://www.wiktionary.org/) y Wikipedia, y use diccionarios impresos como apoyo en caso de duda.: inglés, francés, alemán, ruso, español, mandarín, japonés, coreano, vietnamita, hindi, télugu, árabe, swahili, persa, turco, indonesio, filipino. También puede probar la aplicación [Globasa Etymology Helper](https://globasa-etymology-helper.glitch.me/).

    - Seleccione la fuente con la mayor cantidad de familias lingüísticas representadas.
        - El inglés, el francés, el alemán, el ruso y el español se consideran una sola familia.
        - El indonesio y filipino pertenecen a la misma familia.
        - El mandarín, coreano, japonés, vietnamita, hindi, télugu, árabe, swahili, persa y turco pertenecen a diferentes familias.

    - En caso de empate en el número de familias representadas, el orden de prioridad para la selección de la fuente es el siguiente:
        - Dos o más de los idiomas asiáticos: mandarín, japonés, coreano, vietnamita
        - Árabe, compatible con cualquier otro idioma o idiomas (persa o swahili, por ejemplo)
        - Hindi, compatible con cualquier otro idioma o idiomas (télugu, indonesio o cualquier idioma europeo, por ejemplo)
        - Idiomas europeos, compatibles con cualquier otro idioma o idiomas (indonesio, filipino o turco, por ejemplo)
        - persa y turco

    - Si no hay concordancia, haz una búsqueda más exhaustiva con otras clases de palabra o con sinónimos.

    - Si aún no hay acuerdo, elija la fuente más adecuada en función del siguiente orden de prioridad.
        - indonesio _y_ filipino
        - árabe
        - swahili
        - mandarín
        - hindi

    - Tenga en cuenta que las advertencias anteriores siempre prevalecen sobre las pautas de selección de fuentes.

## Determinar la semántica de la palabra

En este paso, se debe determinar si la nueva palabra raíz será una palabra sustantivo/verbo o una palabra adj/adv. Otras consideraciones deben ser si la nueva palabra raíz denotará una persona o una herramienta, o si la palabra que denota una persona o una herramienta se derivará de la nueva palabra raíz.

- La clase de palabra generalmente se determina por la que parece ser más útil (es decir, la que se usa con más frecuencia en la práctica).

- En algunos casos, la clase de palabra que parece más útil no está bien respaldada por los idiomas de origen, en cuyo caso, la clase de palabra se selecciona en función de la mayor compatibilidad en los idiomas de origen.

- En algunos casos, se selecciona la clase de palabra que se usa con menos frecuencia para acomodar mejor las palabras derivadas. Por ejemplo, Globasa tiene **termo** (_calor_) como sustantivo, en lugar de algo como **_garme_** (_caliente_) para usar fácilmente **termo** en palabras científicas compuestas como _termodinámica_, así como para derivar más fácilmente palabras como **termodo** (_calentado_), a diferencia de **_garmegido_**.

- En el caso de palabras que denotan personas, existen pautas específicas para determinar la palabra raíz. Algunas palabras que denotan profesiones se derivan con **-yen** o **-kef**, mientras que otras son palabras raíz. Las palabras derivadas que denotan profesiones se derivan de palabras raíz que denotan _verbo/práctica_, _equipo_ o _establecimiento_ (pero no la _oficina del profesional_). De lo contrario, la palabra que denota una profesión suele ser una palabra raíz: **biskopo** (obispo), etc.

    - _verbo/practica_
        - **ato** (acto) -- **atoyen** (actor)
        - **medis** (medicina) -- **medisyen** (médico)
        - **injeneri** (ingeniería) -- **injeneriyen** (ingeniero)
        - **arkitetur** (arquitectura) -- **arkiteturyen** (arquitecto)
        - **jasusi** (espionaje) -- **jasusiyen** (espía)
    
    -	_equipo_
        - **polisi** (policía) -- **polisiyen** (oficial de policía)
        - **askeri** (ejército) -- **askeriyen** (soldado)
        - **senato** (senado) -- **senatoyen** (senador)
 
    - _establecimiento_
        - **banko** (banco) -- **bankoyen** (banquero)
        - **eskol** (escuela) -- **eskolkef** (director)
        
    - _oficina del profesional_
        - **sekretari** (secretario) -- **sekretaridom** (secretaría)

## Determinar la forma exacta de la palabra

- Aplicar las advertencias anteriores.

- Intente encontrar un término medio al crear una mezcla entre las palabras en los distintos idiomas. Sin embargo, tenga en cuenta que las palabras provenientes de idiomas europeos tienden a favorecer la ortografía (consulte los detalles a continuación). Se debe hacer un esfuerzo para mantener las mezclas lo más naturales posible. Es decir, debería haber una diferencia de un solo fonema con respecto a la forma de cualquier lengua natural. Una diferencia de dos fonemas también es aceptable si los fonemas se aproximan a los de cualquier lengua natural.

- Se debe hacer un esfuerzo para evitar palabras sustantivo/verbo que comiencen con las sílabas _le-_, _xa-_, _nun-_, _ger-_, _be-_ y _du-_ para evitar confusiones con las partículas verbales.

- Seleccionar consonantes y vocales que sean las menos comunes en Globasa.
    - Si todo lo demás es más o menos igual, elija _e_ en vez de _a_, _e_ en vez de _i_, _o_ en vez de cualquier otra vocal excepto _u_ (_u_ sobre _o_).
    - Si todo lo demás es más o menos igual, elige _m_ en vez de _n_, _l_ en vez de _r_, _h_ en vez de _k_, _g_ en vez de _k_, _d_ en vez de _t_, _p_ en vez de _b_.
    - Sin embargo, siendo todo lo demás más o menos igual, elige _s_ en vez de _z_ y _w_ en vez de _v_. <a id="a_posteriori"></a>

- Las raíces de las palabras en Globasa tienden a terminar en una vocal, preferiblemente una vocal _a posteriori_ que se encuentra en al menos uno de los principales idiomas o familias de idiomas.

    - Ejemplos de vocales finales _a posteriori_: palabras en español que terminan en _-o_ o _-a_, palabras en swahili que terminan en _-i_ o _-u_, o palabras en japonés que terminan en _-u_.
    - [Advertencias](https://www.reddit.com/r/Globasa/comments/phwnv1/naturalistic_final_vowels_to_add_or_not_to_add/):
        - Advertencia 1: Si la palabra constara de cuatro o más sílabas, no se agrega la vocal si hay al menos un idioma que tenga la palabra terminada en consonante: [**estrutur**](https://menalari.globasa.net/spa/lexi/estrutur), etc.
            - Sin embargo, los sustantivos/verbos que terminan en _-ation/-ate_ en inglés siempre agregan **-a** en Globasa, independientemente de la longitud de la palabra: [**diskrimina**](https://menalari.globasa.net/spa/lexi/diskrimina), etc.
            - Además, las palabras que terminan en _-ia/-io_ en español, en _-aire/-oire_ en francés y en _-y_ en inglés suelen terminar en **-i** en Globasa independientemente de la longitud de la palabra: **ordinari**, **teritori**, **sekretari**, etc.
        - Advertencia 2: En unas pocas palabras seleccionadas y muy comunes, no se agrega una vocal final para mantener la palabra en dos sílabas: **eskol**, **alim**, **muhim**, etc. Esto ahora es una advertencia cerrada, ya que se han agregado todas las palabras suficientemente comunes.
        - Advertencia 3: Si la etimología de una palabra incluye ocho o más idiomas y la palabra en cuestión termina en consonante, la palabra en Globasa _no_ agrega una vocal final. Por ejemplo, ver [**tufan**](https://menalari.globasa.net/spa/lexi/tufan) y [**salun**](https://menalari.globasa.net/spa/lexi/salun). Comparar con [**safe**](https://menalari.globasa.net/spa/lexi/safe), [**taru**](https://menalari.globasa.net/spa/lexi/taru ) y [**jusu**](https://menalari.globasa.net/spa/lexi/jusu).

    - Una vocal _a priori_ sólo debe agregarse si la última consonante es una que las reglas fonotácticas no permiten en la posición final de palabra (_b, c, d, g, h, j, k, p, t, v, z_) o para crear una palabra de dos sílabas si la palabra de origen consta de una sílaba (por ejemplo, consulte [**pole**](https://menalari.globasa.net/spa/lexi/pole), que agrega **-e** para evitar pares mínimos con **bol** y **pul**). Para seleccionar una vocal _a priori_, utilice las siguientes pautas:

        - Indoeuropeo (romance, eslavo, germánico, hindi, persa): **-i** para verbos ingleses, de lo contrario **-e**.
        - Todos los demás (mandarín, japonés, coreano y vietnamita; árabe; indonesio y filipino): **-u**.
       
- Se añade la vocal inicial _a posteriori_ o _a priori_ **e-** a grupos de consonantes iniciales no permitidos por la fonotáctica de Globasa: **espageti**, **Esrilanka**, **Exkiperi**, etc.

### Palabras provenientes de idiomas europeos

- Las palabras provenientes de idiomas europeos tienden a favorecer la ortografía tanto de consonantes como de vocales.

- Las consonantes ⟨c⟩, ⟨g⟩ y ⟨s⟩, en particular, se mantienen intactas si existe al menos una lengua europea que las pronuncie como /tʃ/, /g/ y /s/ respectivamente: **centro**, **geo**, **visita**, etc.

- Esta regla general es especialmente importante cuando se trata de la forma en que se traducen las vocales en idiomas que han tomado prestadas palabras europeas a través del inglés. Por ejemplo, la palabra para _ron_ se traduce como /ram/ en muchos idiomas, como una aproximación del inglés /rʌm/. A pesar de que esta /a/ es más frecuente, Globasa conserva ⟨u⟩ en la ortografía original: **rum**.

- Las palabras que terminan en [_-tion_ o _-(s)sion_](https://www.reddit.com/r/Globasa/comments/qey694/revised_proposal_syon_si_or_null/) en inglés y sus equivalentes en otros idiomas se representan de la siguiente forma: las palabras de dos sílabas terminan en **-syon**; las palabras más largas terminan en **-si**. Sin embargo, los verbos que terminan en _-ate_ en inglés no llevan ni _-syon_ ni _-si_, y simplemente terminan en **-a**.

### Palabras provenientes del inglés

Las palabras que provienen principalmente del inglés se representan en Globasa según la siguiente regla general: si un fonema en inglés se puede representar fielmente con el inventario de Globasa, se favorece la pronunciación. De lo contrario, la forma de la palabra en Globasa favorece la ortografía inglesa. Advertencias: /oʊ/, como en _post_, _note_ y _boat_, se convierte en ⟨o⟩; /ʊ/, como en _foot_, se convierte en ⟨u⟩; /z/ como en _visit_ permanece como ⟨s⟩. Para ilustrar mejor:

- Se favorece la ortografía de las llamadas vocales _cortas_ así como de las vocales simples reducidas a /ə/: **Alaska**, **Nevada**, **Misisipi**, **Boston**, **Konetikut**, etc.

- Se favorece la ortografía de ⟨er⟩, ⟨ir⟩ y ⟨ur⟩ pronunciados como /ɜr/: **hamburger** (hamburguesa), **hamuster** (hámster), **eskirti** (falda), etc.

- Se favorece la ortografía de ⟨au⟩: **Awgusta** (Augusta)

- La pronunciación tiene la preferencia en la mayoría de los grupos de vocales: **Finiks** (Phoenix), **Wudrow** (Woodrow), **Tenesi** (Tennessee)

- Se favorece la pronunciación para ⟨are⟩: **Delawer** (Delaware)

- Se favorece la pronunciación de las llamadas vocales _largas_, a excepción de la _o larga_, en cuyo caso se favorece la ortografía: **beykon** (bacon), **eskeyti** (skate), **Aydaho** (Idaho), **Yuta** (Utah); _o larga_: **Ohayo** (Ohio), etc.

- Se favorece la pronunciación de la mayoría de las consonantes, excepto _s_ cuando se pronuncia como /z/, en cuyo caso se favorece la ortografía: **Misuri** (Missouri)

### Palabras provenientes del mandarín

Las palabras provenientes del mandarín generalmente se mezclan con sus respectivas formas en japonés, coreano y vietnamita. Por lo general, se hace un intento de simplificar la fonotáctica del mandarín cuando lo admiten los otros idiomas de Asia oriental, en particular el japonés.

- La sílaba _-ang_ del Pinyin a menudo se convierte en ⟨o⟩ en Globasa, como en japonés.

- Las combinaciones de consonante más semivocal a menudo se reducen a la consonante.

- Asimismo, los diptongos suelen reducirse a una vocal simple.

### Palabras provenientes del árabe

- El diptongo /au̯/ a menudo se reduce a ⟨o⟩, como se ve en swahili o persa: **soti**, etc.

- El diptongo /aj/ en ocasiones se reduce a ⟨e⟩, como se ve en swahili: **rehani**, etc.

- A menos que haya una opción naturalista diferente respaldada por el persa, el swahili, el turco, el indonesio o el hindi, las palabras sustantivo/verbo provenientes del árabe generalmente terminan en **-u**, como podemos ver el tiempo presente de los [verbos en árabe](https://www.reddit.com/r/Globasa/comments/py1a17/final_vowels_added_based_recently_established/).