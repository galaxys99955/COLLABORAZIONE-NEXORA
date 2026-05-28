# Game Design Document

> Versione: 0.1  
> Stato: Pre-produzione  
> Owner: Narrativa  
> Ultimo aggiornamento: 2026-05-28

## Indice
- [1. Stato decisioni](#1-stato-decisioni)
- [2. Obiettivo del documento](#2-obiettivo-del-documento)
- [3. High concept](#3-high-concept)
- [4. Visione](#4-visione)
- [5. Fantasy del giocatore](#5-fantasy-del-giocatore)
- [6. Premessa narrativa](#6-premessa-narrativa)
- [7. Protagonista](#7-protagonista)
- [8. Guida iniziale](#8-guida-iniziale)
- [9. Struttura del gameplay](#9-struttura-del-gameplay)
- [10. Combattimento](#10-combattimento)
- [11. Carte](#11-carte)
- [12. Cristalli rituali](#12-cristalli-rituali)
- [13. Demo](#13-demo)
- [14. Dilemmi del giocatore](#14-dilemmi-del-giocatore)
- [15. Mondo di gioco](#15-mondo-di-gioco)
- [16. Personaggi principali](#16-personaggi-principali)
- [17. Reparti](#17-reparti)
- [18. UI e flow](#18-ui-e-flow)
- [19. Questioni aperte](#19-questioni-aperte)
- [20. Rischi](#20-rischi)
- [21. Priorità immediate](#21-priorità-immediate)

## 1. Stato decisioni

| Tema | Stato | Owner |
|---|---|---|
| Tono narrativo weird-dark-creepy | Approvato | Narrativa |
| Protagonista fisso nella demo | Approvato | Team |
| Bases come guida tutorial | Approvato | Narrativa |
| Carte usate solo nei duelli | Approvato | Team |
| Duello rituale light o esteso | Da decidere | Programmazione |
| Numero definitivo cristalli | Da decidere | Narrativa + Design |
| Sottrazione post-duello | Da testare | Design + Programmazione |

## 2. Obiettivo del documento

Questo documento definisce la visione condivisa del progetto per tutti i reparti del team.

Serve a chiarire concept, tono, struttura narrativa, loop di gioco, contenuti della demo, bisogni produttivi e questioni ancora aperte.

Le decisioni finali sulle meccaniche di gameplay avanzate restano in capo al reparto programmazione e game design tecnico.

## 3. High concept

Gioco action con raccolta di creature e carte, ambientato in un oltretomba mitologico fratturato da un Cataclisma.

Il giocatore interpreta un vivente trascinato per errore nel regno dei morti. Per tornare alla vita deve esplorare una regione infernale, affrontare creature ostili, raccogliere cristalli rituali e sfidare altri viventi in duelli con carte.

## 4. Visione

Il progetto unisce tre componenti principali:
- Esplorazione action PvE.
- Raccolta di ricompense, creature, oggetti e carte.
- Duelli rituali contro altri viventi.

L'identità del gioco deve essere:
- Weird.
- Dark ma non oppressivo in modo continuo.
- Creepy.
- Mitologico.
- Leggermente ironico nei dialoghi della guida.

Il tono non deve essere tragico puro. L'obiettivo è creare inquietudine, fascinazione e mistero, lasciando spazio a personaggi memorabili e a una narrazione più strana che disperata.

## 5. Fantasy del giocatore

Il giocatore non sta semplicemente combattendo mostri. Sta cercando di sopravvivere da vivente in un luogo in cui non dovrebbe esistere, recuperando abbastanza potere e abbastanza risorse rituali da guadagnarsi il ritorno alla vita.

La fantasia centrale è:
- Essere un intruso nel regno dei morti.
- Cacciare creature e reliquie utili.
- Costruire un potere rituale personale.
- Sfidare altri viventi per accelerare la fuga.

## 6. Premessa narrativa

Un Cataclisma ha lacerato il velo tra il mondo dei vivi e quello dei morti. Il risultato è una frattura dell'ordine cosmico: anime dislocate, mostri inquieti, presenze fuori posto e viventi trascinati accidentalmente nell'aldilà.

Per contenere il caos, Ade ha inizialmente chiuso ogni passaggio tra i regni. Tuttavia questa soluzione non può durare: impedire troppo a lungo il normale ciclo della morte rischia di generare uno squilibrio ancora peggiore.

Per questo viene stabilito un compromesso. I viventi possono tentare di tornare alla vita, ma solo se contribuiscono a ripristinare l'ordine dell'oltretomba.

Per farlo devono:
- Recuperare anime e presenze fuori posto.
- Ottenere i cristalli rituali necessari ad attivare il portale dei regni.

## 7. Protagonista

### Stato attuale
Per la demo il protagonista è fisso.

### Motivazione produttiva
Questa scelta riduce la complessità iniziale e consente di concentrare lo sforzo su:
- Atmosfera.
- Combat feel.
- Flow della demo.
- Identità del mondo.
- Primo set di contenuti.

### Possibile estensione futura
La personalizzazione estetica del personaggio può essere introdotta più avanti, idealmente in open beta multiplayer o in una fase successiva del progetto.

## 8. Guida iniziale

### Bases
Bases è un gatto psicopompo molto loquace. Accompagna il protagonista nei primi passi, spiega le regole del mondo e funziona come tutorial NPC.

### Funzioni narrative
- Introduce il setting.
- Spiega le regole dell'oltretomba.
- Fornisce obiettivi chiari al giocatore.
- Può comparire in momenti successivi per chiarimenti o spiegazioni.

### Funzioni tonali
- Alleggerisce il tono più cupo senza spezzarlo.
- Rende la lore più digeribile.
- Offre carattere e riconoscibilità all'apertura della demo.

### Nota di setting
Bases va trattato come personaggio originale dell'ambientazione, con richiami a figure psicopompe classiche e a simboli felini mitologici. Le figure psicopompe più tipiche nelle tradizioni di riferimento sono Hermes e Caronte per l'ambito greco e Anubi per quello egizio, mentre Bastet è utile soprattutto come influenza iconografica felina più che come modello psicopompo diretto.

## 9. Struttura del gameplay

### 9.1 Core loop
- Il giocatore esplora la mappa.
- Incontra o intercetta mostri presenti nella zona.
- Si attiva il combattimento action.
- In caso di vittoria ottiene ricompense.
- Tra le ricompense possono esserci materiali, oggetti, carte e in alcuni casi cristalli.
- Le carte raccolte vengono aggiunte al pool del giocatore.
- Il giocatore può affrontare un altro vivente in un duello rituale.
- Vincendo un duello può ottenere una carta o un cristallo dall'avversario.

### 9.2 Meta loop
- Espandere la collezione di carte.
- Ottenere tutti i cristalli richiesti.
- Sbloccare nuove possibilità di progressione.
- Raggiungere il portale dei regni.
- Nelle versioni future, completare contenuti endless e multiplayer.

## 10. Combattimento

### 10.1 PvE action
Il PvE action è il cuore del loop di raccolta. Serve a sostenere ritmo, controllo del personaggio, tensione immediata e reward flow.

#### Obiettivi del sistema nella demo
- Essere leggibile.
- Essere rapido.
- Offrire ricompense chiare.
- Generare desiderio di continuare a esplorare.

#### Nota
Le carte non si usano nel combattimento action.

### 10.2 Duello rituale
Le carte vengono usate solo nei duelli tra viventi.

#### Nella demo
- Solo scontri contro NPC viventi.

#### In futuro
- Scontri PvP reali.
- Possibile modalità arena o open area.

#### Direzioni possibili per il sistema
- Sistema leggero, basato su incastri, posizionamento e combinazioni, in stile Triple Triad.
- Sistema più ampio, con evocazioni, distruzione di unità e danno diretto all'avversario.

#### Suggerimento narrativo-produttivo
Per la demo è consigliato un sistema più leggero e leggibile. Un sistema esteso tipo LCG con deck personalizzabili è interessante, ma molto più costoso da bilanciare e da presentare bene in UI.

## 11. Carte

La collezione di carte è un'astrazione ludica. Non è necessario che ogni carta venga giustificata come oggetto fisico realistico del mondo.

### Funzione
- Formalizzare il potere acquisito dal giocatore.
- Trasformare ricompense e creature in strumenti competitivi.
- Creare un secondo layer di progressione distinto dal PvE.

### Direzione consigliata
LCG leggero, con pool comune e possibilità future di deck personalizzati, ma con complessità contenuta nella demo.

## 12. Cristalli rituali

I cristalli sono il requisito principale per attivare il ritorno alla vita. Sono manifestazioni di traumi, emozioni estreme o squilibri spirituali generati dal Cataclisma.

### Direzione attuale
L'idea più forte è usare cristalli distinti e simbolici, invece di risorse generiche.

### Possibili modelli
- Cinque cristalli emotivi.
- Quattro cristalli basati sugli umori ippocratici, più una quinta pietra legata alla vita.

### Suggerimento consigliato
La soluzione "quattro umori + pietra della vita" è molto forte sul piano simbolico e visivo.

### Esempio
- Cristallo della Bile Nera.
- Cristallo della Bile Gialla.
- Cristallo del Sangue.
- Cristallo del Flegma.
- Pietra della Vita.

## 13. Demo

### Obiettivo della demo
Validare atmosfera, combat feel, raccolta reward e identità del duello rituale.

### Scope iniziale
- Una sola area giocabile.
- Un protagonista fisso.
- Una guida iniziale.
- Combattimento solo contro NPC.
- Duelli rituali solo contro NPC viventi.
- Sistema di raccolta carte già presente.
- Possibilità di sottrarre una carta o un cristallo al perdente.

### Contenuti minimi consigliati
- 1 area principale.
- 1 hub o punto sicuro.
- 1 tutorial iniziale.
- 3 famiglie di mostri.
- 1 mini-boss o guardiano.
- 1 piccolo pool di carte.
- 1 o 2 NPC viventi sfidabili.

## 14. Dilemmi del giocatore

Le scelte devono essere significative e non apparenti.

### Dilemmi principali
- Continuare il farming PvE o rischiare un duello.
- Conservare una carta rara o metterla in gioco nel rituale.
- Cercare un cristallo in esplorazione o rubarlo a un rivale.
- Affrontare un NPC vivente forte per accelerare la progressione o rimandare.

## 15. Mondo di gioco

L'oltretomba non è uniforme. La regione iniziale deve richiamare il Tartaro per tono, peso e atmosfera, ma senza essere una copia letterale del mito classico.

### Caratteristiche della zona iniziale
- Cupa.
- Rituale.
- Deformata dal Cataclisma.
- Ricca di tracce di anime, rovine, presenze e simboli.

### Regole del mondo
- I viventi presenti nell'aldilà sono anomalie.
- Le anime fuori posto sono un problema reale.
- I cristalli sono residui spirituali concreti.
- I duelli rituali sono una forma riconosciuta di contesa.

## 16. Personaggi principali

| Personaggio | Ruolo |
|---|---|
| Protagonista | Vivente trascinato nell'aldilà. |
| Bases | Guida tutorial, commentatore e ponte con la lore. |
| Ade | Autorità distante che impone le regole del ritorno. |
| Viventi rivali | Competitor per cristalli, carte e uscita dal regno. |
| Creature e spettri | Nemici, ostacoli e fonti di ricompensa. |

## 17. Reparti

### 17.1 Narrativa
- Lore sintetica del Cataclisma.
- Dialoghi di Bases.
- Profilazione dei viventi rivali.
- Naming definitivo dei cristalli.
- Definizione del tono testuale.

### 17.2 Art
- Concept della zona demo.
- Character concept di Bases.
- Famiglie mostruose iniziali.
- Iconografia dei cristalli.
- Template delle carte.
- Prime interfacce del duello.

### 17.3 Programmazione
- Movimento del personaggio.
- Spawn dei mostri.
- Trigger di combattimento.
- Sistema reward.
- Pool carte del giocatore.
- Duello rituale contro NPC.
- Sistema di vincita e sottrazione.

### 17.4 Audio
- Ambience della zona.
- SFX dei mostri.
- SFX reward.
- Identità sonora dei cristalli.
- Sonorità rituali del duello.

## 18. UI e flow

HUD, controlli e menu vanno trattati come flow distinti e leggibili.

### Flow minimo consigliato
- Intro narrativa.
- Tutorial con Bases.
- Esplorazione.
- Incontro mostro.
- Combattimento action.
- Reward screen.
- Collezione carte.
- Duello rituale.
- Premio o sottrazione post-duello.

## 19. Questioni aperte

- Forma definitiva del duello rituale.
- Numero finale dei cristalli.
- Regole esatte della sottrazione post-duello.
- Ruolo effettivo di Ade nella demo.
- Presenza o meno di un'agenda nascosta di Bases.
- Struttura finale del pool carte nella demo.

## 20. Rischi

- Il duello rituale può diventare troppo ambizioso troppo presto.
- La demo rischia di voler mostrare troppi sistemi insieme.
- Il tono weird-dark può collassare se i dialoghi diventano troppo ironici o troppo solenni.
- La meccanica di sottrazione può risultare frustrante se non ben calibrata.

## 21. Priorità immediate

### Narrative
- Scrivere premessa breve.
- Definire voce di Bases.
- Definire naming dei cristalli.

### Design
- Scegliere il modello del duello rituale per la demo.
- Definire la posta in gioco del duello.
- Definire il numero iniziale di carte.

### Art
- Fare concept sheet della zona iniziale.
- Disegnare Bases.
- Definire moodboard dei cristalli.

### Programmazione
- Verificare fattibilità del loop completo demo.
- Stimare costo del duello rituale light vs esteso.
- Definire struttura dati minima per carte, cristalli e reward.
