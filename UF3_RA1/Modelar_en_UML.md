*1 Modelar en UML**

L’objectiu d’aquesta activitat és practicar i conèixer com representar utilitzant diagrama de classes de UML diferent informació. Modelar en UML la informació rellevant que s’exposa en els dominis següents tot dibuixant el diagrama estàtic de les classes conceptuals del domini, les associacions entre les classes, els rols de les associacions, i les restriccions d'integritat textual (RIT).

Feu les suposicions addicionals que considereu raonables dins el context.

1. En una acadèmia els professors fan classe als alumnes matriculats de manera que tot professor fa classe almenys a un alumne i tot alumne rep classe d'un únic professor

   ![1](/home/dani/Descargas/UF3_RA1/paradigm/img/1.png)

2.  Els professors d'un centre poden ser o no tutors d'un alumne, en qualsevol cas els alumnes solament podran tenir un únic tutor

   ![2](/home/dani/Descargas/UF3_RA1/paradigm/img/2.png)

3. En un comerç, un client compra diversos productes, i un producte pot ser comprat per diversos clients

   ![3](/home/dani/Descargas/UF3_RA1/paradigm/img/3.png)

4. Representa la relació entre Persones i els seus pares

   ![4](/home/dani/Descargas/UF3_RA1/paradigm/img/4.png)

5. En una carrera de relleus, representar la relació donar el relleu entre atletes(per calcular les cardinalidades màxima i mínima hauràs de tenir en compte si es tracta del primer,  l'últim o el 2º o 3º)

   ![5](/home/dani/Descargas/UF3_RA1/paradigm/img/5.png)

6. Una empresa està composta per diversos departaments dels quals es desitja
   emmagatzemar la seva no, nom i localitat. Els empleats han d'estar assignats a un
   departament i es guardaran les seves dades noemprat, cognom, salari.A més, cada
   empleat té un cap (Nota: s'ha suposat que un departament pot no tenir empleats)

   ![6](/home/dani/Descargas/UF3_RA1/paradigm/img/6.png)

7. Es desitja construir una bd per mantenir informació sobre els equips i partits de la lliga.
   Un equip té un cert no de jugadors (Aneu_jugador, dades personals) i no tots participenen cada partit. Volem registrar a més per cada partit, quins jugadors juguen, la data i
   l'hora del partit, resultats de les trobades i les posicions on juguen.

   ![7](/home/dani/Descargas/UF3_RA1/paradigm/img/7.png)

8. En una empresa, per a cadascun dels seus empleats, es guarden les dades dels seus
   fills. Representa aquesta relació fent les suposicions que creguis convenients

   ![8](/home/dani/Descargas/UF3_RA1/paradigm/img/8.png)

9. Es desitja dissenyar una BD per a una Universitat que contingui informació sobre
   carreres i assignatures que es poden estudiar. A més s'inclourà la informació dels
   alumnes matriculats en les corresponents assignatures i les qualificacions que obtenen
   en les assignatures en les quals estan matriculats. Nota: suposar que una assignatura
   solament pot pertànyer a una carrera.

   ![9](/home/dani/Descargas/UF3_RA1/paradigm/img/9.png)

10. Exercici: calcula la cardinalitat de la següent relació ternària

    ![10](/home/dani/Descargas/UF3_RA1/paradigm/img/10.png)

**2 Representar les relacions anteriors amb Visual Paradigm
Utilitzeu el popular software CASE Visual Paradigm CE per representar les relacions vistes
en l’exercici anterior. Heu de modelar correctament les funcions, accions i els atributs de cada entitat
( classe).**

1. Descarregueu i instal.leu Visual Paradigm CE.



   ![installacio1](/home/dani/Descargas/UF3_RA1/paradigm/img/installacio1.png)

   ![installaciio2](/home/dani/Descargas/UF3_RA1/paradigm/img/installaciio2.png)

   ![installacio3](/home/dani/Descargas/UF3_RA1/paradigm/img/installacio3.png)

2. Representar les relacions de l’exercici anterior.

3. Proveu de generar un codi Java per les relacions que heu dissenyat.

   > S'ha de anara a tools, code, instant generator, selleccionar totes les classes que vols generar el codi, seleccionar el llenguatge a dalt a la esquerra , sellecciones el path i clicar a generate i si tens les classes correctament et genera el codi al path escollit.

   ![11](/home/dani/Descargas/UF3_RA1/paradigm/img/11.png)

   ![12](/home/dani/Descargas/UF3_RA1/paradigm/img/12.png)

   ![13](/home/dani/Descargas/UF3_RA1/paradigm/img/13.png)

4. Documenteu i expliqueu de forma adient els processos que heu seguit.

   > Primer crees la classe, seguidament sel·lecciones aquesta cliques intro i aqui tens totes les pocions per a tributs, metodes, ...

**3 Representar les relacions anteriors utilitzant Papyrus
Utilitzeu el popular software IDE Eclipse, proporciona un plugin anomenat Papyrus per fer
diagrama de classes.**

1. Descarregueu i instal.leu Eclipse per desenvolupadors JAVA.
2. Instal.leu el plugin Papyrus.
3. Proveu de generar un codi Java per les relacions que heu dissenyat.
4. Documenteu i expliqueu de forma adient els processos que heu seguit.