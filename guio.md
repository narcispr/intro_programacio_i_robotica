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

**Slide 1 — Títol general**  
**Títol a pantalla:** *Com pensen els ordinadors i com aprenen els robots*  
**Missatge clau:** “La informàtica no és només pantalles: és una manera d’entendre i transformar el món.”  
**Guió oral:** Presenta’t en primera persona: ets professor d’Enginyeria Informàtica especialitzat en robòtica, treballes a la universitat, i avui vens a explicar-los per què saber pensar com un informàtic ajuda a fer coses reals.  
**Visual suggerit:** una foto teva o del laboratori, més una mini-col·lecció de robot, ordinador i entorn marí.  
**Referència visual:** pàgina del centre i canal CIRS UdG. citeturn10search16turn0search2

**Slide 2 — Pregunta d’entrada**  
**Títol a pantalla:** *On hi ha informàtica al teu dia?*  
**Missatge clau:** “Més llocs dels que sembla.”  
**Guió oral:** Demana que aixequin la mà si han fet servir un mòbil, un rellotge, una consola, un cotxe, un semàfor, una rentadora o un GPS avui o aquesta setmana. No expliquis encara res tècnic: només obre la curiositat.  
**Visual suggerit:** collage gran d’objectes quotidians.  
**Referència conceptual:** els dispositius digitals es poden entendre amb el model entrada–procés–sortida i els sistemes encastats són la base de moltes aplicacions modernes. citeturn15view5turn20view2turn20view0

**Slide 3 — Programari dins dels objectes**  
**Títol a pantalla:** *Molts objectes tenen “cervell digital”*  
**Missatge clau:** “No tot és una web o un videojoc.”  
**Guió oral:** Explica que molts objectes tenen petits ordinadors o microcontroladors a dins. No cal dir “embedded systems” en gran; si ho dius, immediatament tradueix-ho per “ordinadors petits dins d’un objecte”.  
**Visual suggerit:** diagrama d’un objecte quotidià amb sensors, botons, pantalla i motor.  
**Referència visual:** Arduino descriu els seus dispositius i programari com a tecnologies que interactuen amb el món físic; TI parla de microcontroladors i processadors per a aplicacions encastades i edge AI. citeturn20view0turn20view2turn20view3

**Slide 4 — Exemples molt concrets**  
**Títol a pantalla:** *Cotxes, rellotges, electrodomèstics, joguines…*  
**Missatge clau:** “Molts aparells reben dades, processen i responen.”  
**Guió oral:** Fes quatre exemples ràpids: un rellotge rep tocs i mostra informació; una rentadora llegeix botons i sensors; un cotxe usa sensors i control; un semàfor canvia segons regles i temps.  
**Visual suggerit:** quatre fotos grans, una paraula cada una: *entrades*, *procés*, *sortida*, *acció*.  
**Referència conceptual:** a KS2, Teach Computing presenta entrada, procés i sortida com a conceptes fonamentals de tots els dispositius digitals. citeturn15view5turn19search7

**Slide 5 — El programari també dissenya i organitza**  
**Títol a pantalla:** *I el programari també crea el món abans que existeixi*  
**Missatge clau:** “No només controla objectes: també ajuda a dissenyar, simular i decidir.”  
**Guió oral:** Aquí introdueix la idea que la informàtica també serveix per dibuixar edificis, analitzar dades científiques, planificar rutes, organitzar hospitals o estudiar el medi ambient. No intentis demostrar cada sector; el punt és que el programari ajuda altres professions.  
**Visual suggerit:** una combinació de mapa digital, gràfic científic i model 3D.  
**Referència conceptual:** ISTE i Raspberry Pi remarquen que el pensament computacional i la computació s’apliquen més enllà de la classe d’informàtica i travessen disciplines. citeturn15view2turn15view3turn23view4

**Slide 6 — Saber programar és una competència transversal**  
**Títol a pantalla:** *Programar és una supereina*  
**Missatge clau:** “T’ajuda a automatitzar, provar idees i entendre millor la tecnologia.”  
**Guió oral:** Formula-ho així: “No tothom ha de ser programador professional, però entendre una mica de programació et dona poder per crear, provar, automatitzar i preguntar millor.”  
**Visual suggerit:** una graella de professions: ciència, medicina, educació, art, enginyeria.  
**Referència conceptual:** ISTE presenta el pensament computacional com una alfabetització essencial per a tots els estudiants i útil per dissenyar solucions en totes les disciplines. citeturn15view3turn23view4

**Slide 7 — Què és el pensament computacional**  
**Títol a pantalla:** *Quatre idees per resoldre problemes*  
**Missatge clau:** “Descompondre, buscar patrons, abstraure i fer passos.”  
**Guió oral:** Dona una definició minimalista: és una manera de resoldre problemes perquè una persona o una màquina els pugui seguir.  
**Visual suggerit:** quatre icones simples i recurrents per a tota la presentació.  
**Referència conceptual:** ISTE resumeix el pensament computacional en descomposició, reconeixement de patrons, abstracció i algoritmes; el K–12 CS Framework l’associa a formular problemes i dissenyar algoritmes que un ordinador pot executar. citeturn15view3turn16view4

**Slide 8 — Mini activitat de classe**  
**Títol a pantalla:** *Repte: com explicaries “fer un entrepà” a un robot?*  
**Missatge clau:** “Si no ets precís, el robot s’equivoca.”  
**Guió oral:** Demana 4 o 5 instruccions del públic i juga a ser un robot massa literal. Aquesta slide és important perquè prepara la idea de programa com a seqüència precisa.  
**Visual suggerit:** dibuix molt simple d’un robot davant d’un entrepà.  
**Referència pedagògica:** els enfocaments unplugged i de discussió guiada són centrals als materials de Code.org i CS Unplugged per introduir conceptes de computació sense començar per sintaxi. citeturn16view3turn0search3

**Slide 9 — Què és la informàtica**  
**Títol a pantalla:** *Informàtica = treballar amb informació*  
**Missatge clau:** “Capturar, guardar, transformar i usar informació.”  
**Guió oral:** No facis una definició acadèmica. Digues: “La informàtica tracta de com representem informació i com fem que les màquines la transformin.”  
**Visual suggerit:** una cadena: informació → dades → programa → resultat.  
**Referència conceptual:** Computer Science Field Guide introdueix la representació de dades justament des de la idea que els ordinadors treballen amb informació. citeturn28view0turn15view8

**Slide 10 — Què poden ser dades**  
**Títol a pantalla:** *Text, imatges, so, números, sensors*  
**Missatge clau:** “Tot això són dades.”  
**Guió oral:** Mostra que el mateix ordinador pot tractar paraules, fotos, música i mesures d’un sensor, perquè tot es representa internament d’alguna manera.  
**Visual suggerit:** cinc icones amb exemples molt recognoscibles.  
**Referència conceptual:** la guia de representació de dades descriu documents, imatges, vídeos, so, fulls de càlcul i bases de dades com a informació que l’ordinador ha de representar internament. citeturn28view0

**Slide 11 — Per què 1 i 0**  
**Títol a pantalla:** *Els ordinadors fan servir dos estats*  
**Missatge clau:** “Per això parlem de 1 i 0.”  
**Guió oral:** Explica-ho amb metàfores de llum encesa/apagada o interruptor sí/no. No entris en electrònica. L’objectiu és que entenguin “dues opcions”.  
**Visual suggerit:** interruptor, LED o targetes binàries.  
**Referència conceptual:** CS Unplugged explica que els sistemes digitals representen informació amb el sistema binari, amb només dos dígits, 0 i 1. citeturn14view3turn0search0

**Slide 12 — Exemple de text**  
**Títol a pantalla:** *Una lletra també es pot convertir en nombres*  
**Missatge clau:** “Text → codi numèric → bits.”  
**Guió oral:** Fes **un sol exemple**, no una taula llarga. Per exemple: “A → 65 → 01000001”. El que importa no és memoritzar-ho, sinó veure el camí.  
**Visual suggerit:** animació de tres passos, amb una sola lletra gran.  
**Referència conceptual:** Code.org introdueix ASCII com a sistema per representar lletres i paraules, i CS Field Guide explica que cada caràcter rep un nombre que després es representa en binari. citeturn26search1turn15view7turn26search2

**Slide 13 — Exemple d’imatge en blanc i negre**  
**Títol a pantalla:** *Una imatge pot ser una graella*  
**Missatge clau:** “Cada quadret és un píxel.”  
**Guió oral:** Mostra una cara o un cor de 8×8. Explica que si només hi ha blanc o negre, cada píxel pot ser un 0 o un 1.  
**Visual suggerit:** una icona pixelada gran amb la seva matriu al costat.  
**Referència conceptual:** CS Unplugged i Code.org fan servir exactament aquesta idea per introduir representació d’imatges; Code.org mostra formats molt simples amb amplada, alçada i bits per píxel. citeturn14view4turn16view1turn16view0

**Slide 14 — Exemple d’imatge en color**  
**Títol a pantalla:** *En color, cada píxel guarda més informació*  
**Missatge clau:** “Una barreja de vermell, verd i blau.”  
**Guió oral:** No facis 24 bits en profunditat. Només digues que, en moltes pantalles, cada píxel guarda tres quantitats: vermell, verd i blau.  
**Visual suggerit:** tres barres RGB i un quadrat de color resultant.  
**Referència conceptual:** Computer Science Field Guide explica la representació RGB i que sovint el color d’un píxel es construeix combinant tres valors, habitualment 8 bits per canal. citeturn15view6

**Slide 15 — Les instruccions també són dades**  
**Títol a pantalla:** *Un programa també és informació*  
**Missatge clau:** “Les ordres i les dades es poden guardar en binari.”  
**Guió oral:** Aquesta és una slide molt elegant per passar de “dades” a “programa”: tant una foto com un programa es poden guardar i transmetre perquè, al final, també són bits.  
**Visual suggerit:** una capsa amb dues etiquetes: *foto* i *programa*, totes dues entrant a memòria.  
**Referència conceptual:** Computer Science Field Guide remarca que tant les instruccions d’un programa com les dades es poden representar en el mateix format binari. citeturn15view8

**Slide 16 — Les peces bàsiques d’un programa**  
**Títol a pantalla:** *Quatre peces bàsiques*  
**Missatge clau:** “Fer passos, repetir, decidir i guardar valors.”  
**Guió oral:** Presenta les quatre peces en paraules molt planes: seqüència, bucles, condicionals i variables. Pots afegir entrada/sortida com a marc: “rebo informació, faig coses, retorno un resultat”.  
**Visual suggerit:** quatre mini diagrames amb fletxes i un exemple quotidià.  
**Referència conceptual:** els cursos elementals de Code.org introdueixen seqüències, bucles, esdeveniments, condicionals i variables progressivament; Teach Computing treballa entrada–procés–sortida com a fonament. citeturn16view3turn15view5

**Slide 17 — Una mateixa tasca, diverses maneres de programar**  
**Títol a pantalla:** *La mateixa idea es pot expressar de maneres diferents*  
**Missatge clau:** “Canvia el format, no el repte.”  
**Guió oral:** Anuncia que ara veureu diferents maneres d’explicar a una màquina què ha de fer. Aquesta slide prepara la comparació Scratch / codi / IA.  
**Visual suggerit:** un únic repte al centre i tres fletxes sortint cap a *blocs*, *text* i *aprendre*.  
**Referència conceptual:** l’ensenyament de programació per a joves sovint passa de blocs a text i, al mateix temps, els materials actuals d’IA afegeixen enfocaments guiats per dades. citeturn14view2turn23view2

**Slide 18 — Programació visual en blocs**  
**Títol a pantalla:** *Scratch: programar encaixant peces*  
**Missatge clau:** “És visual i molt bona per començar.”  
**Guió oral:** Has de dir explícitament que ells això ja ho coneixen, però que avui ho fareu servir com a primer llenguatge per pensar.  
**Visual suggerit:** captura d’un petit programa Scratch amb moviment, repetició i condició molt simples.  
**Referència visual:** Scratch es descriu com un llenguatge de blocs amb una interfície visual simple per crear històries, jocs i animacions. citeturn5search3turn14view1

**Slide 19 — El mateix en text**  
**Títol a pantalla:** *El mateix programa, escrit amb paraules*  
**Missatge clau:** “Python o pseudocodi expressen les mateixes idees.”  
**Guió oral:** Mostra dues o tres línies curtes. Per exemple, `for`, `if`, `move`. Aquí l’objectiu és que vegin la correspondència entre blocs i text, no ensenyar sintaxi real.  
**Visual suggerit:** pantalla dividida: Scratch a l’esquerra, pseudocodi/Python a la dreta.  
**Referència conceptual:** Raspberry Pi té un curs específic per ajudar a transferir les habilitats de Scratch a Python i destaca que els aprenents poden reciclar el pensament i les estructures apreses amb blocs. citeturn14view2

**Slide 20 — Per què el text és tan habitual**  
**Títol a pantalla:** *Per què tanta gent programa amb text?*  
**Missatge clau:** “És compacte, flexible i molt potent.”  
**Guió oral:** Digues que el text és més habitual en entorns professionals perquè permet projectes grans, còpia fàcil, versions, fitxers i més control. No cal entrar en editors ni eines.  
**Visual suggerit:** una lupa sobre unes poques línies de codi gran i llegible.  
**Referència conceptual:** Raspberry Pi presenta la transició a Python com el pas natural després dels blocs, i Scratch destaca el valor d’una entrada inicial sense sintaxi complicada. citeturn14view1turn14view2

**Slide 21 — Programació clàssica**  
**Títol a pantalla:** *Manera 1: escriure les regles*  
**Missatge clau:** “La persona decideix els passos.”  
**Guió oral:** Aquesta és la forma clàssica: jo escric les regles, l’ordinador les executa. Reforça que aquí podem seguir el flux pas a pas.  
**Visual suggerit:** diagrama simple: humà → regles → ordinador → resultat.  
**Referència conceptual:** Raspberry Pi descriu aquest enfocament com a rule-driven o CT 1.0, amb el focus posat en crear algoritmes. citeturn23view2

**Slide 22 — Aprenentatge supervisat**  
**Títol a pantalla:** *Manera 2: ensenyar amb molts exemples*  
**Missatge clau:** “Li mostrem dades i etiquetes.”  
**Guió oral:** Posa un exemple proper: fotos de peixos/plàstics, o dibuixos de gat/gos. La màquina no rep totes les regles una per una; aprèn patrons a partir d’exemples.  
**Visual suggerit:** Teachable Machine o Quick, Draw!, amb dues classes i exemples.  
**Referència visual:** Day of AI i Experience AI fan servir exemples reals, datasets i eines com Teachable Machine per introduir l’aprenentatge supervisat; Quick, Draw! és un exemple molt intuïtiu de sistema que aprèn a reconèixer dibuixos a partir de grans conjunts de dades. citeturn15view0turn15view1turn25search0turn28view4

**Slide 23 — Aprenentatge per reforç**  
**Títol a pantalla:** *Manera 3: provar moltes vegades i rebre punts*  
**Missatge clau:** “Si ho fa bé, recompensa; si no, torna a provar.”  
**Guió oral:** Explica-ho com un videojoc: el robot prova, s’equivoca, torna a provar i va buscant més punts.  
**Visual suggerit:** una fletxa amb intents repetits cap a un objectiu o un tauler d’escacs.  
**Referència conceptual:** DeepMind explica AlphaZero com un sistema que, donades només les regles del joc, va aprendre jugant contra si mateix milions de vegades per maximitzar la probabilitat de guanyar; NVIDIA descriu RL per a robots exactament com maximitzar recompenses mitjançant interacció repetida amb l’entorn. citeturn14view6turn23view0

**Slide 24 — I la IA generativa?**  
**Títol a pantalla:** *Avui també podem treballar parlant amb una IA*  
**Missatge clau:** “Un prompt pot ajudar, però no substitueix entendre el problema.”  
**Guió oral:** Aquí jo evitaria la paraula “vibe coding” a la pantalla. Diria: “Ara hi ha eines que et poden ajudar si expliques bé què vols, però després cal revisar, provar i corregir.”  
**Visual suggerit:** persona → prompt → IA → esborrany → comprovació humana.  
**Referència conceptual:** Code.org i UNESCO insisteixen que l’ús educatiu de la IA generativa ha de ser responsable, crític i amb validació humana; Day of AI se centra a entendre, qüestionar i utilitzar la IA de manera responsable. citeturn29view0turn16view6turn7search2

**Slide 25 — Petita slide d’alerta responsable**  
**Títol a pantalla:** *La IA és potent, però no és màgia*  
**Missatge clau:** “Aprèn de dades, pot fallar i cal comprovar-la.”  
**Guió oral:** Aquesta slide ha de durar poc. Tres idees: pot equivocar-se, pot heretar problemes de les dades, i les persones continuem sent responsables del resultat.  
**Visual suggerit:** un semàfor amb tres icones: *ajuda*, *error*, *comprova*.  
**Referència conceptual:** Day of AI inclou biaix i justícia com a parts centrals de l’alfabetització en IA; UNESCO proposa un enfocament humà i adequat a l’edat per a l’ús educatiu de la IA generativa. citeturn15view0turn29view0

## Guió del bloc de robòtica submarina

**Slide 26 — Què faig jo**  
**Títol a pantalla:** *Jo treballo amb robots submarins*  
**Missatge clau:** “La informàtica també serveix per explorar i actuar sota l’aigua.”  
**Guió oral:** Fes el pas natural: “Tot el que hem vist fins ara —dades, sensors, programes, decisions— és exactament el que necessitem perquè un robot funcioni.”  
**Visual suggerit:** imatge gran del Girona I-AUV o SPARUS II.  
**Referència visual:** CIRS descriu la seva recerca al voltant de control, simulació, navegació i construcció de robots submarins; el Girona I-AUV i SPARUS II tenen pàgines específiques amb imatges i descripció clara. citeturn14view7turn14view8turn14view9

**Slide 27 — Per què robots sota l’aigua**  
**Títol a pantalla:** *Per què no hi baixen sempre persones?*  
**Missatge clau:** “Perquè hi ha llocs difícils, cars o perillosos.”  
**Guió oral:** Explica tres motius infantils però seriosos: profunditat, visibilitat, temps sota l’aigua i seguretat.  
**Visual suggerit:** foto de profunditat / estructura submarina / mar tèrbol.  
**Referència conceptual:** CIRS presenta aquests robots per a inspecció, monitoratge, exploració i intervenció en entorns difícils i sovint perillosos per a humans. citeturn21search5turn10search4

**Slide 28 — Què “té” un robot submarí**  
**Títol a pantalla:** *Ulls, orelles, cervell i braços*  
**Missatge clau:** “Càmeres, sonar, sensors, control i, a vegades, manipuladors.”  
**Guió oral:** Tradueix tecnologia a metàfores: càmera = ulls; sonar = “veure amb ones”; sensors = sentir el món; propulsors = moure’s; braços = actuar.  
**Visual suggerit:** esquema annotat d’un AUV.  
**Referència conceptual:** SPARUS II incorpora càmera i sonar per mapatge i inspecció; Girona I-AUV se centra en manipulació amb braços i en intervenció precisa. citeturn14view8turn14view9

**Slide 29 — Què podem fer amb aquests robots**  
**Títol a pantalla:** *Ciència, arqueologia, energia i ecologia*  
**Missatge clau:** “La robòtica submarina ajuda a conèixer i cuidar el mar.”  
**Guió oral:** Dona quatre exemples ràpids: mapar el fons, inspeccionar estructures, estudiar hàbitats marins, documentar restes arqueològiques.  
**Visual suggerit:** una diapositiva amb quatre quadrants i una imatge per àrea.  
**Referència conceptual:** les aplicacions i projectes de CIRS inclouen arqueologia submarina, energia offshore, observació d’hàbitats i restauració amb IA integrada. citeturn21search2turn21search1turn23view6turn21search0

**Slide 30 — Vídeo recomanat de mapatge o inspecció**  
**Títol a pantalla:** *Vídeo: el robot crea un mapa 3D*  
**Missatge clau:** “Primer mira, després entén.”  
**Guió oral:** Abans del vídeo, formula una pregunta: “Quines dades creieu que està recollint?”  
**Vídeos recomanats del teu canal:** *Inspection of an Underwater Structure using Point Cloud SLAM with an AUV and a Laser Scanner* o *Underwater Pose SLAM using GMM Scan Matching for a Mechanical Profiling Sonar*.  
**Visual suggerit:** fotograma del vídeo + tres icones: sonar, trajectòria, mapa.  
**Referència de vídeo:** resultats de SLAM, inspecció i reconstrucció 3D del canal CIRS UdG. citeturn27search9turn27search2

**Slide 31 — Vídeo recomanat d’intervenció o manipulació**  
**Títol a pantalla:** *Vídeo: el robot no només mira, també actua*  
**Missatge clau:** “Quan el robot manipula, la dificultat puja molt.”  
**Guió oral:** Abans del vídeo, digues: “Ara ja no es tracta només de saber on és; també ha de tocar, agafar o connectar.”  
**Vídeos recomanats del teu canal:** *Autonomous Underwater Intervention, Docking and Intervention*, *Autonomous Cooperative Underwater Object Assembly* o *I-AUV Recovering a Black Box*.  
**Visual suggerit:** fotograma amb braç robòtic o docking panel.  
**Referència de vídeo:** vídeos del canal CIRS UdG sobre docking, intervenció, assemblatge i recuperació d’objectes. citeturn27search4turn27search3turn27search11

## Guió del bloc final amb el robot

**Slide 32 — El repte final comú**  
**Títol a pantalla:** *Un mateix repte per a quatre maneres d’ensenyar un robot*  
**Missatge clau:** “Anar a un punt, agafar un objecte i deixar-lo a un altre lloc.”  
**Guió oral:** Explica que **no canvia el problema**, només canvia la manera de donar coneixement al robot. Aquesta és la slide-pont més important de tota la presentació.  
**Visual suggerit:** esquema de taula amb punt A, objecte i punt B.  
**Referència conceptual:** connecta el bloc final amb les tres grans vies que ja has introduït: regles, demostració i aprenentatge. citeturn23view2turn23view0turn24view4

**Slide 33 — Mètode 1: blocs**  
**Títol a pantalla:** *Manera A: blocs*  
**Missatge clau:** “Arrossego peces que diuen què ha de fer.”  
**Guió oral:** Mostra un programa mínim amb peces tipus `anar a`, `baixar`, `tancar pinça`, `pujar`, `anar a`, `obrir pinça`.  
**Visual suggerit:** pseudo-Scratch o editor per blocs molt net.  
**Missatge pedagògic:** Fes-los predir l’ordre correcte abans de revelar-lo.  
**Referència conceptual:** Scratch i els currículums elementals mostren que la programació per blocs és una entrada natural per aprendre seqüències, repeticions i decisions. citeturn14view1turn16view3

**Slide 34 — Mètode 2: codi imperatiu**  
**Títol a pantalla:** *Manera B: codi textual*  
**Missatge clau:** “El mateix, però escrit.”  
**Guió oral:** Proposa un pseudocodi curt amb `moveJ`, `open_gripper`, `close_gripper` i, si vols, un únic `if object_detected`. Evita un `for` si no aporta res al repte; si el poses, que sigui perquè realment repeteix una comprovació.  
**Visual suggerit:** codi molt curt, màxim 8 línies, tipus gran.  
**Referència conceptual:** el pas de Scratch a Python és un patró educatiu consolidat i la sintaxi textual permet expressar les mateixes estructures amb més flexibilitat. citeturn14view2

**Slide 35 — Mètode 3: ensenyar per demostració**  
**Títol a pantalla:** *Manera C: jo ho faig una vegada i el robot ho repeteix*  
**Missatge clau:** “L’ensenyem amb una demostració.”  
**Guió oral:** Aquí faria una correcció important a la teva redacció: digues **“demostració i replay de trajectòries”**, no “VLA”, perquè en la demo que proposes realment el robot repetirà trajectòries enregistrades, no un model generalista visió-llenguatge-acció. Si vols mencionar el paral·lelisme modern, pots dir-ho a la nota oral, però a la slide no.  
**Visual suggerit:** braç guia/leader i braç follower, o una línia temporal de posicions enregistrades.  
**Referència conceptual:** la documentació de SO-100/LeRobot treballa explícitament amb braços leader/follower, calibració compartida i tutorials d’imitation learning; al teu propi context, CIRS també ha mostrat arquitectura d’aprenentatge per demostració per a AUVs d’intervenció. citeturn24view1turn24view4turn27search17

**Slide 36 — Mètode 4: aprenentatge per reforç**  
**Títol a pantalla:** *Manera D: el deixem provar en simulació*  
**Missatge clau:** “Rep punts quan s’acosta a l’objectiu.”  
**Guió oral:** Aquesta és la forma més “màgica” per a ells, així que cal dir-la amb una sola frase: “No li diem exactament què fer; només com saber si va millor o pitjor.”  
**Visual suggerit:** simulació amb marcador de recompensa que puja quan l’efector s’acosta o pressiona correctament.  
**Referència conceptual:** NVIDIA descriu RL com aprenentatge que maximitza una recompensa després de moltes interaccions; AlphaZero és un exemple canònic de sistema que aprèn així a partir de les regles i d’assaig i error. citeturn23view0turn14view6

**Slide 37 — Comparar les quatre maneres**  
**Títol a pantalla:** *Què guanyem i què perdem en cada mètode?*  
**Missatge clau:** “No hi ha una sola manera bona; depèn del problema.”  
**Guió oral:** Compara-les amb llenguatge molt senzill. Blocs: molt clar. Codi: més potent. Demostració: ràpida per copiar un moviment. Reforç: bo quan el problema és difícil d’escriure a mà però costós d’entrenar.  
**Visual suggerit:** quatre columnes amb “fàcil d’entendre”, “precís”, “flexible”, “aprèn sol”.  
**Referència conceptual:** els materials actuals d’educació en programació i IA insisteixen en distingir entre solucions guiades per algorismes i solucions guiades per dades o retroalimentació. citeturn23view2turn15view1

**Slide 38 — Tancament**  
**Títol a pantalla:** *Idees finals*  
**Missatge clau:** “Pensar de manera computacional et permet entendre i construir coses noves.”  
**Guió oral:** Tanca amb tres frases: la informàtica és a tot arreu; els ordinadors treballen amb dades; i programar és una manera d’explicar idees a màquines perquè facin feina útil.  
**Visual suggerit:** muntatge final que uneixi dispositius, bits, Scratch, IA i robot submarí.  
**Referència conceptual:** aquesta síntesi recull exactament el recorregut que segueixen els recursos educatius de CS per a joves i la teva pròpia pràctica en robòtica. citeturn14view0turn15view3turn10search4

## Banc de visuals i limitacions

Perquè la segona IA no s’hagi d’inventar res, aquest seria el **banc mínim de visuals externs** que jo faria servir. Per a la part “software a tot arreu”, el millor punt de partida és el material de **Teach Computing** sobre dispositius digitals i el d’**Arduino** sobre electrònica i programari que interactuen amb el món físic. Per a “pensament computacional”, les referències més netes són **ISTE**, **K–12 CS Framework** i la síntesi de **Raspberry Pi** sobre CT més enllà de la programació. Per a representació de dades, les peces més útils són **CS Unplugged** per al binari i la imatge, **Code.org Pixelation** per a la idea de format simple, i **Computer Science Field Guide** per a text, color i el fet que les instruccions també es poden guardar com a dades. Per a IA, els visuals més clars són **Teachable Machine / Quick, Draw!**, **Day of AI**, **Experience AI**, **AlphaZero** i, si vols una slide de prudència, **UNESCO**. Per a robòtica, el cos central hauria de sortir del **web de CIRS** i del **canal CIRS UdG**. citeturn15view5turn20view0turn15view3turn16view4turn15view2turn14view3turn14view4turn16view1turn15view7turn15view8turn25search0turn28view4turn15view0turn14view5turn14view6turn29view0turn14view7turn27search6

Si vols donar una instrucció operativa molt clara a la segona IA, pots afegir aquesta frase al prompt de generació: **“Cada diapositiva ha de portar una nota de ponent breu, una proposta de visual i la font concreta del visual; les cites es poden posar a notes o al peu, no cal carregar la part principal amb text.”** Aquesta manera de treballar és coherent amb els repositoris educatius que ofereixen slide decks, lesson plans i recursos visuals ja preparats per docents. citeturn14view0turn14view5

La principal limitació de la recerca és tècnica: el navegador no ha permès inspeccionar amb comoditat tots els detalls interns del canal de YouTube, de manera que els **títols de vídeos recomanats** s’han triat a partir dels resultats de cerca accessibles i de les pàgines de CIRS que els enllacen, no d’una revisió exhaustiva de totes les llistes del canal. També hi ha recursos educatius molt bons en PDF o entorns interactius que aquí s’han resumit en la seva versió textual o visual més bàsica per mantenir el guió compacte i fàcil d’editar. citeturn27search6turn27search3turn27search4turn27search9turn31view0