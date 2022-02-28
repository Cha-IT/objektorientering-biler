# Innlevering: Objektorientert programmering - Biler

I denne oppgaven skal du pøve deg på objektorientert programmering. Du skal lage en klasse, og objekter. Vi skal bruke biler som eksempel.

## Oppgave 1: Lag en klasse og objekter
1. Lag en klasse som heter **Bil**. I constructoren angir du objektvariablene **regnr**, **merke**, **modell**, **aar**, **farge**, **toppfart** og **fart** (fart angir hastigheten bilen har akkurat nå).
2. Lag tre **Bil**-objekter og legg inn valgfrie verdier i objektvariablene (f.eks. _"AA12345", "Ford", "Mustang Mach-e", "2021", "Svart", 230, 0_).

## Oppgave 2: Lag metoder til klassen Bil
1. Lag en metode som heter gass() i klassen **Bil**. Denne metoden skal øke farten (dvs objektvariabelen **fart**) med 10. Farten skal ikke kunne overstige toppfarten til bilen.
2. Lag en metode som heter brems() i klassen **Bil**. Denne metoden skal redusere farten med 10. Farten skal ikke kunne bli mindre enn 0.

## Oppgave 3: "Kjør" bilene
Lag et program (nettside) med bilde av de tre bilene du la inn i oppgave 1-2. Over hvert av bildene skal det stå info om bilen (regnr, merke, modell, aar, farge), og under bildet skal det stå hastighet. Under hastigheten skal det være en knapp for "Gass" og en knapp for "Brems" (seks knapper til sammen). Disse knappene skal oppdatere hastigheten ved hjelp av metodene gass og brems, slik at man til en hver tid skal kunne se hvor fort hver bil kjører.

## EKSTRA - Oppgave 4: Håndbremse
Lag en knapp under hver bil for "Håndbremse". Denne knappen skal fungere slik at hvis håndbremsen er på blir farten satt til 0, og det skal ikke være mulig å øke farten så lenge håndbremsen er på. Bruk metoder for å få til dette.
