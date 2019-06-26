# kata-Japanese-Romaji-to-Hiragana-Converter
 ん に ち は!  Esta か た (kata) es para traducir romaji, o japonés escrito en caracteres latinos, en hiragana, un conjunto de caracteres japoneses que se utiliza para deletrear fonéticamente palabras nativas en japonés (entre otras cosas). No necesitas ningún conocimiento previo de japonés para completar este た - ¡Tú puedes hacerlo! ん ば っ て!

Fundamentos de Hiragana
1. Hay 46 símbolos hiragana básicos, como se ve en la tabla a continuación. Debe leerse de derecha a izquierda.
https://upload.wikimedia.org/wikipedia/commons/thumb/2/28/Table_hiragana.svg/768px-Table_hiragana.svg.png

Hay algunos hiragana que no siguen el patrón, a saber, shi, chi, tsu, fu y n.

2. Hay 25 hiragana adicionales que se crean al agregar una marca diacrítica como la voz ゛ y la semi voz ゜, como se ve a continuación. Observa que ji no sigue el patrón.

                       a		   i		    u		   e		    o
    
       g:	が	ga	      ぎ	gi      ぐ	gu	     げ	ge	     ご	go

       z:	ざ	za	      じ	ji	     ず	zu	     ぜ	ze	     ぞ	zo

       d: だ	da					                       で	de	     ど	do

       b:	ば	ba	       び	bi	    ぶ	bu	     べ	be 	    ぼ	bo

       p:	ぱ	pa	       ぴ	pi	    ぷ	pu	     ぺ	pe	     ぽ	po
       
3. Además, los caracteres pequeños permiten que todos los usuarios de código tengan き ゅ (kyu). Son, ゅ y ょ, que se pueden agregar después de ciertos caracteres para transcribir sílabas contratadas. Observa que ja, ju y jo no siguen el patrón general.

                       a		  u	    	 o
       ky:	きゃ	kya	きゅ	kyu	きょ	kyo

       sh:	しゃ	sha	しゅ	shu	しょ	sho

       ch:	ちゃ	cha	ちゅ	chu	ちょ	cho
       
       ny:	にゃ	nya	にゅ	nyu	にょ	nyo

       hy:	ひゃ	hya	ひゅ	hyu	ひょ	hyo

       my:	みゃ	mya	みゅ	myu	みょ	myo

       ry:	りゃ	rya	りゅ	ryu	りょ	ryo

       gy:	ぎゃ	gya	ぎゅ	gyu	ぎょ	gyo

       j:	じゃ	ja	じゅ	ju	じょ	jo

       by:	びゃ	bya	びゅ	byu	びょ	byo

       py:	ぴゃ	pya	ぴゅ	pyu	ぴょ	pyo
       

4. Por último, se utiliza un pequeño っ para transcribir la primera de las dos consonantes consecutivas. Por ejemplo, sakka se escribe como さ っ か.
Además, cuando hay dos ns consecutivos, el primero no se escribe con el pequeño. Está escrito con n / ん. Por ejemplo, konnichiha se escribe como ん に ち.


El reto: 
Escribe una función, romajiToHiragana, que toma una cadena romaji y devuelve una cadena hiragana.

Se ha proporcionado un mapa llamado hiragana con claves romaji y valores hiragana, que contiene todo de las tablas anteriores. La clave del pequeño っ es tsuSmall.

Se ha proporcionado un mapa llamado hiragana con claves romaji y valores hiragana, que contiene todo de las tablas anteriores. La clave del pequeño es tsuSmall.


Notas: 

Supongamos que nya, nyu y nyo siempre se escribirán como に ゃ, に ゅ y に ょ, y nunca como ん や, etc.

Si bien se proporcionan todas las sílabas concatenadas, se puede acceder a ゃ, ゅ y ょ individualmente con yaSmall, yuSmall y yoSmall, respectivamente.

este es el link de CodeWars de la kata: https://www.codewars.com/kata/5be0c8601b109ad2450000a5  

Happy coding! :)
