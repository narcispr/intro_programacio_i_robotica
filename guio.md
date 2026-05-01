# Guió recercat per a una presentació de 6è sobre pensament computacional i informàtica

## Criteris de redisseny

La teva idea original és bona i, amb pocs canvis, pot quedar molt més clara per a alumnat d’11–12 anys. El patró que es repeteix als materials més sòlids per a primària i primers cursos de secundària és aquest: començar amb exemples molt propers, introduir una sola idea tècnica cada vegada, alternar “prediu què passarà” amb revelació, i fer servir visuals i activitats curtes en lloc de definicions llargues. Això és coherent amb Code.org per a primària, Scratch, CS Unplugged, la pedagogia de Raspberry Pi i els materials de Day of AI i Experience AI. citeturn14view0turn14view1turn0search3turn16view7turn16view6turn14view5

La correcció més important és terminològica i narrativa. Jo **no** presentaria Scratch com a “programació declarativa”; és millor parlar de **programació visual en blocs**. Els materials oficials de Scratch el descriuen com una interfície visual de blocs, i els currículums primers de Code.org per a aquestes edats insisteixen en seqüències, bucles, esdeveniments, condicionals i variables, que és exactament el llenguatge que ells poden entendre i reutilitzar després. citeturn14view1turn16view3

També et recomano una altra correcció conceptual: a la part d’IA, en lloc de posar “prompts / vibe coding” al mateix nivell que els paradigmes clàssics, funciona millor explicar **tres maneres de dir-li a un ordinador què ha de fer**: amb **regles escrites per humans**, amb **molts exemples de dades**, o amb **proves i recompenses**. Els materials de Day of AI, Experience AI i Raspberry Pi distingeixen clarament entre enfocaments basats en regles i enfocaments guiats per dades, i AlphaZero és un exemple molt net per explicar aprenentatge per reforç. Els prompts poden aparèixer, però com a eina nova que ajuda a treballar amb IA generativa, no com a fil central de tota la secció. citeturn15view1turn14view5turn23view2turn14view6

El fil conductor que lliga molt bé tota la sessió és aquest: **“Veiem el món, el convertim en dades, escrivim o aprenem instruccions, i finalment un sistema actua.”** Aquest fil et permet passar de mòbils i rellotges a bits, de bits a programes, dels programes a IA, i de la IA a la robòtica submarina sense salts bruscos. A més, encaixa amb la idea d’entrada–procés–sortida que els materials de computing per a aquestes edats tracten com a fonamental per entendre què és un dispositiu digital. citeturn15view5turn20view0turn28view0

## Estructura recomanada

Jo reorganitzaria la sessió en tres blocs principals, més la part de robòtica i el tancament pràctic. La presentació completa quedaria amb **38 diapositives**. Els **blocs inicials** ocuparien aproximadament **30 minuts**; la part sobre la teva feina i els vídeos, **10–20 minuts**; i el bloc final amb el robot, **20 minuts**. Aquesta càrrega és realista si les diapositives tenen poc text, grans visuals i preguntes curtes a l’aula. L’estil recomanat és visual, amb màxim una idea central per slide, i amb petites pauses de predicció, tal com suggereixen PRIMM, el treball amb exemples resolts i la reducció de càrrega cognitiva. citeturn23view3turn28view5turn28view6

Per a la **segona IA** que hagi de generar el PPTX o el BEAMER, les regles globals haurien de ser aquestes. Cada diapositiva ha de tenir un **títol molt curt**, una **frase clau** de no més d’una línia, un **visual dominant**, i com a molt **tres paraules o etiquetes auxiliars**. Les diapositives on hi hagi codi han de mostrar **fragments mínims** i amb grans tipografies. Les diapositives amb preguntes han de tenir l’espai visual perquè el grup pugui pensar abans de revelar la resposta. Aquest enfocament és coherent amb l’èmfasi de Code.org en slide decks guiades i de Raspberry Pi en lectura de codi abans d’escriure’l. citeturn14view0turn23view3turn28view6

També et recomano que la presentació reutilitzi quatre icones al llarg de tota la sessió: **descompondre**, **buscar patrons**, **abstraure** i **fer passos**. ISTE i el K–12 CS Framework presenten aquestes idees com a nuclis molt recognoscibles del pensament computacional, i et serviran com a “cola” conceptual entre la part més quotidiana, la part de dades i la part de programació. citeturn15view3turn16view4

El millor tancament és exactament el que proposes, però amb una reformulació més neta: **“El mateix repte del robot, quatre maneres d’ensenyar-li.”** Això converteix l’últim bloc en una recapitulació de tota la xerrada. A més, connecta molt bé amb recursos actuals d’IA i robòtica educativa que ja mostren aprenentatge per demostració, aprenentatge per reforç i sistemes oberts com SO-100/LeRobot. citeturn24view1turn24view4turn23view0

## Guió detallat dels blocs inicials

**Titol slide 1 — Títol general**  
**Subtítol:** *Com pensen els ordinadors/robots*  
**Missatge clau:** “La informàtica no son només pantalles: és una manera d’entendre i transformar el món.”  
**Guió oral:** Presenta’t en primera persona: ets professor d’Enginyeria Informàtica especialitzat en robòtica, treballes a la universitat, i avui vens a explicar-los per què saber pensar com un informàtic ajuda a fer coses reals.  
**Visual suggerit:** foto jo i nens i foto g1000_barco.  


**Titol slide 2 — Pregunta d’entrada**  
**Subtítol:** *On apareix la "informàtica" al teu dia?*  
**Missatge clau:** “Més llocs dels que sembla.”  
**Guió oral:** Demana que aixequin la mà si han fet servir un mòbil, un rellotge, una consola, un cotxe, un semàfor, una rentadora o un GPS avui o aquesta setmana. No expliquis encara res tècnic: només obre la curiositat.  


**Titol slide 3 — Programari dins dels objectes**  
**Subtítol:** *Com pense els objectes: el “cervell digital”*  
**Missatge clau:** Els objectes no pensen com nosaltres sinó que executen una serie d'instruccions.  
**Guió oral:** Explica que molts objectes tenen petits ordinadors o microcontroladors a dins que els permeten executar seqüencies de dades que algú ha programat.  
**Visual suggerit:** ascensor, rentadora, web, consola, semaàor

**Titol slide 4 — Exemples molt concrets**  
**Subtítol:** *Com pense els objectes: el “cervell digital” II*  
**Missatge clau:** “Molts aparells reben dades, processen i responen.”  
**Guió oral:** un ascensor rep botons i controla motors porta i canviar de pis, una rentadora llegeix botons i sensors (humitat) i controla entrada aigua motors, ...; un semàfor canvia segons regles i temps.  
**Visual suggerit:** quatre fotos grans, una paraula cada una: *entrades*, *procés*, *sortida*, *acció*.  


**Titol slide 5 — Els programes que "fan coses"**  
**Subtítol:** *Els programes no només es troben dins de determinats objectes sinó que també serveixen per crear-ne*  
**Missatge clau:** “No només controlen objectes: també ajuden a dissenyar, simular i decidir.”  
**Guió oral:** Aquí introdueix la idea que la informàtica també serveix per dibuixar edificis, analitzar dades científiques, planificar rutes, organitzar hospitals o estudiar el medi ambient. No intentis demostrar cada sector; el punt és que el programari ajuda altres professions.  
**Visual suggerit:** imatge dun sistema CAD, gràfic científic i model 3D.  


**Titol slide 6 — Saber programar és una competència transversal**  
**Subtítol:** *Programar és una supereina*  
**Missatge clau:** “T’ajuda a automatitzar, provar idees i entendre millor la tecnologia.”  
**Guió oral:** Formula-ho així: “No tothom ha de ser programador professional, però entendre una mica de programació et dona poder per crear, provar, automatitzar i preguntar millor.”  
**Visual suggerit:** una graella de professions: cièntific, metge, mestre, artiste, enginyer.  

**Titol slide 7 — Què és Què és el pensament computacional**  
**Subtítol:** *El pensament computacional*  
**Missatge clau:** “és una manera de resoldre problemes perquè una persona o una màquina els pugui seguir: Descompondre, buscar patrons, abstraure i fer passos.”  
**Guió oral:** Dona una definició minimalista: és una manera de resoldre problemes perquè una persona o una màquina els pugui seguir.  
**Visual suggerit:** imatge computational thinking  


**Titol slide 8 — Mini activitat de classe**  
**Subtítol:** *Repte: com explicaries “fer un entrepà” a un robot?*  
**Missatge clau:** “Si no ets precís, el robot s’equivoca.”  

**Visual suggerit:** dibuix molt simple d’un robot davant d’un entrepà.  


**Titol slide 9 — Què és la informàtica**  
**Subtítol:** *Informàtica = treballar amb informació/dades*  
**Missatge clau:** “Capturar, guardar, transformar i usar informació.”  
**Guió oral:** No facis una definició acadèmica. Digues: “La informàtica tracta de com representem informació i com fem que les màquines la transformin.”  
**Visual suggerit:** una cadena: informació → dades → programa → resultat.  


**Titol slide 10 — Què entenem per informació o dades**  
**Subtítol:** *Què entenem per informació o dades?*  
**Missatge clau:** “Tot això són dades: Text, imatges, so, números, sensors”  
**Visual suggerit:** cinc icones amb exemples molt recognoscibles.  


**Titol slide 11 — Per què 1 i 0**  
**Subtítol:** *Els ordinadors representen totes les dades en dos estats; 1 i 0*  
**Missatge clau:** “Per això parlem de 1 i 0.”  
**Guió oral:** Explica-ho amb metàfores de llum encesa/apagada o interruptor sí/no. No entris en electrònica. L’objectiu és que entenguin “dues opcions”.  
**Visual suggerit:** interruptor, LED o targetes binàries.  

**Titol slide 12 — Exemple de text**  
**Subtítol:** *Una lletra també es pot convertir en nombres*  
**Missatge clau:** “Text → codi numèric → bits.”  
**Guió oral:** Fes **un sol exemple**, no una taula llarga. Per exemple: “A → 65 → 01000001”. El que importa no és memoritzar-ho, sinó veure el camí.  
**Visual suggerit:** animació de tres passos, amb una sola lletra gran.  


**Titol slide 13 — Exemple d’imatge en blanc i negre**  
**Subtítol:** *Una imatge pot ser una graella*  
**Missatge clau:** “Cada quadret és un píxel.”  
**Guió oral:** Mostra una cara o un cor de 8×8. Explica que si només hi ha blanc o negre, cada píxel pot ser un 0 o un 1.  
**Visual suggerit:** una icona pixelada gran amb la seva matriu al costat.  


**Titol slide 14 — Exemple d’imatge en color**  
**Subtítol:** *En color, cada píxel guarda més informació*  
**Missatge clau:** “Una barreja de vermell, verd i blau.”  
**Guió oral:** No facis 24 bits en profunditat. Només digues que, en moltes pantalles, cada píxel guarda tres quantitats: vermell, verd i blau.  
**Visual suggerit:** tres barres RGB i un quadrat de color resultant.  


**Titol slide 15 — Les instruccions també són dades**  
**Subtítol:** *Un programa també son dades/informació*  
**Missatge clau:** “Les ordres (instruccions) també es poden guardar en binari. Però a més, els ordinadors les "entenen" i les poden executar”  
**Guió oral:** Aquesta és una slide molt elegant per passar de “dades” a “programa”: tant una foto com un programa es poden guardar i transmetre perquè, al final, també són bits.  
**Visual suggerit:** una capsa amb dues etiquetes: *foto* i *programa*, totes dues entrant a memòria.  


**Titol slide 16 — Les peces bàsiques d’un programa**  
**Subtítol:** *Les peces bàsiques d’un programa*  
**Missatge clau:** “Els ordinadors només entenen ordres molt bàsiques com per exemple: fer operacions matemàtiques, repetir, evaluar condicions (>, <, =, ...) o guardar/llegir valors.”  
**Visual suggerit:** els blocs d'scratch que fan aquestes operacions.  


**Titol slide 17 — Diverses maneres de programar**  
**Subtítol:** *Es pot programar la mateixa idea de maneres diferents*  
**Missatge clau:** “A l'hora de fer un programa podem utilitzar diferent llenguatges (igual que hi ha diferents llengues) i aquests poden ser molt diferents entre sí.”  
**Visual suggerit:** La paraula Hola escrita en català, Anglès, Àrab, Xinès, Korea i en llengua de signes catalana o española

**Titol slide 18 — Programació visual en blocs**  
**Subtítol:** *Scratch: programar encaixant peces*  
**Missatge clau:** “És visual i molt bona per començar.”  
**Guió oral:** Has de dir explícitament que ells això ja ho coneixen, però que avui ho fareu servir com a primer llenguatge per pensar.  
**Visual suggerit:** captura d’un petit programa Scratch amb moviment, repetició i condició molt simples.  

**Titol slide 19 — Llenguatges d'alt nivell**  
**Subtítol:** *Escrivim el programa amb instruccions similars a les nostres paraules*  
**Missatge clau:** “Expressen les mateixes idees de condició, repetició, operacions... de l'scratch però utilitzant paraules clau.”  
**Visual suggerit:** pantalla dividida: Scratch a l’esquerra, pseudocodi/Python a la dreta.  

**Titol slide 20 — Llenguatges d'alt nivell**  
**Subtítol:** *El més popular?*  
**Missatge clau:** “És compacte, flexible i molt potent. Hi ha dotzenes de llenguatges de programació diferents!”  
**Visual suggerit:** un mateix programa (ex: for i in 10; si i % 2 == 0; print(i)) en C++, Python, Javascript, ... 


**Titol slide 21 — Programació clàssica**  
**Subtítol:** *Tant en la programació de blocs com utilitzant llenguatges d'alt nvell, el/la programador/a decideix les instruccions a executar*  
**Missatge clau:** “La persona decideix els passos/regles i la màquina els executa.”  
**Visual suggerit:** diagrama simple: humà → regles → ordinador → resultat.  

**Titol slide 22 — Vibe Coding**  
**Subtítol:** *Avui també podem treballar parlant amb una IA (I la IA generativa?)*  
**Missatge clau:** “I una de les coses que sap fer molt bé la IA és programar amb llenguatges d'alt nivel.
**Visual suggerit:** persona → prompt → IA → esborrany → comprovació humana.  

**Titol slide 23 — Petita slide d’alerta responsable**  
**Subtítol:** *La IA és potent, però no és màgia*  
**Missatge clau:** “Aprèn de dades, pot fallar i cal comprovar-la. Tant si la feu servir per fer texts com per programar s'ha de vigilar molt que fa!”  
**Visual suggerit:** un text i un programa  

**Titol slide 24 — Aprenentatge màquina**  
**Subtítol:** *Una altre manera de programar és possible?s*  
**Missatge clau:** “Sí! En alguns porcessos podem ensenyar milions de dades etiquetades a l'ordinador i ell podràs extreue un model (programa). --> Aprenentatge supervisat”  
**Visual suggerit:** dibuixos de gat/gos..  

**Titol slide 25 — Aprenentatge màquina II**  
**Subtítol:** *Una altre manera és deixa a l'ordinador provar moltes vegades una tasca i rebre punts si ho fa bé --> aprenentatge per reforç*  
**Missatge clau:** “Si ho fa bé, recompensa (+1); si no càstig (-1), torna a provar.”  
**Visual suggerit:** esquema cíclic agent -> acció --> tasca --> recompensa --> agent .  





## Guió del bloc de robòtica submarina

**Titol slide 26 — COm és la meva feina?**  
**Subtítol:** *A part de fer classes, jo treballo amb robots submarins*  
**Missatge clau:** “La robòtica no només és sciencia i ficció sinó que ens ajuda a realitzar moltes tasques.”  
**Visual suggerit:** descarrega imatge de un robot industrial i un robot tipus roomba (aspirador).  

**Titol slide 27 — Per què volem robots sota l’aigua**  
**Subtítol:** *Per què és un lloc difícil d'accedir-hi, perillos i enorme (si ho em d'inspeccionar zones manualment tardarem molt").*  
**Visual suggerit:** posa una imatge de: foto de profunditat o estructura submarina o mar tèrbol.  

**Titol slide 28 — Què “té” un robot submarí**  
**Subtítol:** *Ulls --> cameres, orelles -> sonar, cervell --> Ordinadors i braços --> manipuladors*  
**Visual suggerit:** guarda espai per una imatge, pots fer 2 columnes una amb el text i l'altre la deixes buida per la imatge.  

**Titol slide 29 — Què podem fer amb aquests robots**  
**Subtítol:** *Ciència, arqueologia, energia, ecologia...*  
**Missatge clau:** “La robòtica submarina ajuda a conèixer i cuidar el mar.”  
**Visual suggerit:** una diapositiva amb quatre quadrants i una imatge per àrea.  

**Titol slide 30 — Algunes coses que hem fet nosaltres**  
**Subtítol:**   
**Vídeos recomanats del teu canal:** linjs als videos: *Inspection of an Underwater Structure using Point Cloud SLAM with an AUV and a Laser Scanner* o *Underwater Pose SLAM using GMM Scan Matching for a Mechanical Profiling Sonar*. *Autonomous Underwater Intervention, Docking and Intervention*, *Autonomous Cooperative Underwater Object Assembly* o *I-AUV Recovering a Black Box*.   estan tots al canal https://www.youtube.com/@cirsudg



## Guió del bloc final amb el robot

**Titol slide 32 — El repte final comú**  
**Subtítol:** *Un mateix repte per a quatre maneres d’ensenyar un robot*  
**Missatge clau:** “Anar a un punt, agafar un objecte i deixar-lo a un altre lloc.”  
**Guió oral:** Explica que **no canvia el problema**, només canvia la manera de donar coneixement al robot. Aquesta és la slide-pont més important de tota la presentació.  
**Visual suggerit:** esquema de taula amb punt A, objecte i punt B.  
**Referència conceptual:** connecta el bloc final amb les tres grans vies que ja has introduït: regles, demostració i aprenentatge. citeturn23view2turn23view0turn24view4

**Titol slide 33 — Mètode 1: blocs**  
**Subtítol:** *Manera A: blocs*  
**Missatge clau:** “Arrossego peces que diuen què ha de fer.”  
**Guió oral:** Mostra un programa mínim amb peces tipus `anar a`, `baixar`, `tancar pinça`, `pujar`, `anar a`, `obrir pinça`.  
**Visual suggerit:** pseudo-Scratch o editor per blocs molt net.  
**Missatge pedagògic:** Fes-los predir l’ordre correcte abans de revelar-lo.  
**Referència conceptual:** Scratch i els currículums elementals mostren que la programació per blocs és una entrada natural per aprendre seqüències, repeticions i decisions. citeturn14view1turn16view3

**Titol slide 34 — Mètode 2: codi imperatiu**  
**Subtítol:** *Manera B: codi textual*  
**Missatge clau:** “El mateix, però escrit.”  
**Guió oral:** Proposa un pseudocodi curt amb `moveJ`, `open_gripper`, `close_gripper` i, si vols, un únic `if object_detected`. Evita un `for` si no aporta res al repte; si el poses, que sigui perquè realment repeteix una comprovació.  
**Visual suggerit:** codi molt curt, màxim 8 línies, tipus gran.  
**Referència conceptual:** el pas de Scratch a Python és un patró educatiu consolidat i la sintaxi textual permet expressar les mateixes estructures amb més flexibilitat. citeturn14view2

**Titol slide 35 — Mètode 3: ensenyar per demostració**  
**Subtítol:** *Manera C: jo ho faig una vegada i el robot ho repeteix*  
**Missatge clau:** “L’ensenyem amb una demostració.”  
**Guió oral:** Aquí faria una correcció important a la teva redacció: digues **“demostració i replay de trajectòries”**, no “VLA”, perquè en la demo que proposes realment el robot repetirà trajectòries enregistrades, no un model generalista visió-llenguatge-acció. Si vols mencionar el paral·lelisme modern, pots dir-ho a la nota oral, però a la slide no.  
**Visual suggerit:** braç guia/leader i braç follower, o una línia temporal de posicions enregistrades.  
**Referència conceptual:** la documentació de SO-100/LeRobot treballa explícitament amb braços leader/follower, calibració compartida i tutorials d’imitation learning; al teu propi context, CIRS també ha mostrat arquitectura d’aprenentatge per demostració per a AUVs d’intervenció. citeturn24view1turn24view4turn27search17

**Titol slide 36 — Mètode 4: aprenentatge per reforç**  
**Subtítol:** *Manera D: el deixem provar en simulació*  
**Missatge clau:** “Rep punts quan s’acosta a l’objectiu.”  
**Guió oral:** Aquesta és la forma més “màgica” per a ells, així que cal dir-la amb una sola frase: “No li diem exactament què fer; només com saber si va millor o pitjor.”  
**Visual suggerit:** simulació amb marcador de recompensa que puja quan l’efector s’acosta o pressiona correctament.  
**Referència conceptual:** NVIDIA descriu RL com aprenentatge que maximitza una recompensa després de moltes interaccions; AlphaZero és un exemple canònic de sistema que aprèn així a partir de les regles i d’assaig i error. citeturn23view0turn14view6

**Titol slide 37 — Comparar les quatre maneres**  
**Subtítol:** *Què guanyem i què perdem en cada mètode?*  
**Missatge clau:** “No hi ha una sola manera bona; depèn del problema.”  
**Guió oral:** Compara-les amb llenguatge molt senzill. Blocs: molt clar. Codi: més potent. Demostració: ràpida per copiar un moviment. Reforç: bo quan el problema és difícil d’escriure a mà però costós d’entrenar.  
**Visual suggerit:** quatre columnes amb “fàcil d’entendre”, “precís”, “flexible”, “aprèn sol”.  
**Referència conceptual:** els materials actuals d’educació en programació i IA insisteixen en distingir entre solucions guiades per algorismes i solucions guiades per dades o retroalimentació. citeturn23view2turn15view1

**Titol slide 38 — Tancament**  
**Subtítol:** *Idees finals*  
**Missatge clau:** “Pensar de manera computacional et permet entendre i construir coses noves.”  
**Guió oral:** Tanca amb tres frases: la informàtica és a tot arreu; els ordinadors treballen amb dades; i programar és una manera d’explicar idees a màquines perquè facin feina útil.  
**Visual suggerit:** muntatge final que uneixi dispositius, bits, Scratch, IA i robot submarí.  
**Referència conceptual:** aquesta síntesi recull exactament el recorregut que segueixen els recursos educatius de CS per a joves i la teva pròpia pràctica en robòtica. citeturn14view0turn15view3turn10search4

## Banc de visuals i limitacions

Perquè la segona IA no s’hagi d’inventar res, aquest seria el **banc mínim de visuals externs** que jo faria servir. Per a la part “software a tot arreu”, el millor punt de partida és el material de **Teach Computing** sobre dispositius digitals i el d’**Arduino** sobre electrònica i programari que interactuen amb el món físic. Per a “pensament computacional”, les referències més netes són **ISTE**, **K–12 CS Framework** i la síntesi de **Raspberry Pi** sobre CT més enllà de la programació. Per a representació de dades, les peces més útils són **CS Unplugged** per al binari i la imatge, **Code.org Pixelation** per a la idea de format simple, i **Computer Science Field Guide** per a text, color i el fet que les instruccions també es poden guardar com a dades. Per a IA, els visuals més clars són **Teachable Machine / Quick, Draw!**, **Day of AI**, **Experience AI**, **AlphaZero** i, si vols una slide de prudència, **UNESCO**. Per a robòtica, el cos central hauria de sortir del **web de CIRS** i del **canal CIRS UdG**. citeturn15view5turn20view0turn15view3turn16view4turn15view2turn14view3turn14view4turn16view1turn15view7turn15view8turn25search0turn28view4turn15view0turn14view5turn14view6turn29view0turn14view7turn27search6

Si vols donar una instrucció operativa molt clara a la segona IA, pots afegir aquesta frase al prompt de generació: **“Cada diapositiva ha de portar una nota de ponent breu, una proposta de visual i la font concreta del visual; les cites es poden posar a notes o al peu, no cal carregar la part principal amb text.”** Aquesta manera de treballar és coherent amb els repositoris educatius que ofereixen slide decks, lesson plans i recursos visuals ja preparats per docents. citeturn14view0turn14view5

La principal limitació de la recerca és tècnica: el navegador no ha permès inspeccionar amb comoditat tots els detalls interns del canal de YouTube, de manera que els **títols de vídeos recomanats** s’han triat a partir dels resultats de cerca accessibles i de les pàgines de CIRS que els enllacen, no d’una revisió exhaustiva de totes les llistes del canal. També hi ha recursos educatius molt bons en PDF o entorns interactius que aquí s’han resumit en la seva versió textual o visual més bàsica per mantenir el guió compacte i fàcil d’editar. citeturn27search6turn27search3turn27search4turn27search9turn31view0