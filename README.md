# LandofLords
## Note
Tessere quadrate da 2x2 celle con diversi biomi per cella (pianura, monti, colline, acqua)
Una capitale
Risorse: Popolazione | Ricerca | Materiali
Centri: Accampamento | Villaggio | Paese | Città (livello 1-2-3-4)
La capitale produce un numerod i risorse pari al suo livello distribuiti tra popolazione/ricerca/materiali ogni turno.
I Centri producono 1 risorsa a livello 1-2-3 e 2 risorse a livello 4

## Mondo
### Mappa:
La mappa del territorio è composta da **Tessere quadrate** ognuno suddivisa in 2x2 **celle**. Ogni cella rappresenta uno dei 3 **Biomi**:
- **Pianura**: il Bioma più semplice che non comporta nessun bonus/malus
- **Acqua**: non è possibile costruire o espandersi su questa cella. Le unità non possono attraversarla.
- **Monti**: non è possibile costruire o espandersi su questa cella. Il movimento su di essa conta come *2 celle* (la Esploratori non può attraversarla).

## Costruzione
### Centri:
I Centri abitati sono di 4 tipi, 1 per livello:
1. Insediamento
2. Villaggio
3. Borgo
4. Città

Oppure, più semplicemente, Centri di Lv1, Lv2, Lv3 e Lv4.  
Il *livello* del Centro indica:
- Il numero di Tessere che controlla e su cui può costruire *Fattorie*
- Il **Bonus di Difesa** fornito sul territorio controllato
- A livello 4 un Centro produce *2* Risorse anziché 1.

#### Capitale
La propria capitale è considerata sempre un Centro ma con delle meccaniche aggiuntive.
Il livello della Capitale determina il livello massimo di tutti gli altri centri in proprio possesso. Nessun Centro può essere di livello più alto della propria Capitale.
La Capitale produce 1 risorsa per livello (a livello 3 produrrà 3 risorse anziché una come gli altri Centri) ed ha un Bonus difesa incrementato di 1 (+2 a Lv1, +3 Lv2,...).

### Fondare un nuovo Centro
Gli **Eploratori** possono fondare un nuovo centro nella casella su cui stanno al costo di 2 Risorse. L'esploratore morirà.
Non è possibile fondare un Centro in una tessera in cui è presente un altro Centro.


### Espandere i propri Centri
Un Centro controlla la tessera su cui è costruito. Se almeno una delle celle con cui è a contatto non presenta altri centri, può espandersi. Posizionare un nuovo segnalino su quella cella. Un Insediamento controlla 1 tessera. Un Villaggio ne controlla 2, un Borgo 3 ed una Città 4.
Il costo dell'espansione varia a seconda del livello:
- 1->2: 4 Risorse 
- 2->3: 8 Risorse 
- 3->4: 12 Risorse

Il costo d'espansione della capitale invece:
1->2: 4 Risorse + 1 Ricerca
2->3: 8 Risorse + 2 Ricerca
3->4: 12 Risorse + 3 Ricerca

### Le Strutture
Le Strutture sono costruzioni di supporto edificabili in una cella libera su una tessera controllata da un proprio Centro.  
Le Strutture disponibili sono:
- **Fattoria**: +1 Risorse/Turno. Costo: 3 Risorse. Edificabile solo su **Pianure**.
- **Miniera**: +1 Risorse/Turno. Costo: 4 Risorse. Edificabile solo su **Montagne**. Le proprie unità potranno muoversi su quella cella ignorando il malus di movimento dato dal Bioma.


## Militare

### Unità:

| Unità        | Livello           | Costo  |
| ------------- |:-------------:| :-----:|
| Esploratori      | 1 | 2 Risorse | 
| Guerrieri      | 2 |   5 Risorse |
| Cavalleria | 3 |    8 Risorse |
| Generale | 4 |    11 Risorse |

Le unità hanno diverse caratteristiche:
- **Movimento** (M): ogni unità può muoversi di un numero di celle pari al suo livello ogni turno. (NB. i movimenti sulle montagne valgono il doppio, impedendo alla Esploratori di attraversarle.)
- **Valore di Combattimento** (VC): il Valore di Combattimento di ogni unità è pari al suo livello + i bonus dati dalla ricerca militare.



## Ricerca:
La ricerca permette di migliorare le proprie conoscenze e tecnologie. Ogni ricerca presenta 4 livelli e partono tutte a 0. Il costo per ogni livello è:

| LV | Pt. Ricerca |
| :--: | :--: |
| 1  | 1 ![ricerca](imgs/ricerca.png)|
| 2  | 2 |
| 3  | 3 |
| 4  | 4 |

La ricerca si divide in tre campi:
- Militare: 
  - Esploratore
  - Guerriero 
  - Cavaliere 
  - Generale
  - Ogni livello di ricerca aumenta di 1 il Valore di combattimento della relativa unità

> Industriale: Campi | Miniere | Porti | Strade
	- Il numero di fattorie costruibili è pari al numero di accampamenti + il livello della ricerca dei Campi
	- Il numero di Miniere costruibili è pari al livello di Miniere
	- Il numero di Porti 
	- Le proprie truppe si muovono di un numero di passi bonus pari al livello di Strade all'interno dei propri territori.

# Fasi del turno:
> Riscossione risorse: +1 Risorsa per ogni livello della capitale. +1 Risorsa per ogni Centro.
> Conversione: Per ogni risorsa acquisita si convertono in Popolazione/Materiali/Ricerca a piacimento
> Riscossione Materiali: +1 Materiale per ogni Miniera/Fattoria
> Ricerca: puoi spendere punti Ricerca
> Espansione: Puoi espandere fino ad un tuo Centro
> Militare: puoi creare un unità di qualunque tipo in una cella libera in una tessera che controlli (cella libera = in cui non sono presenti unità amiche o nemiche)
> [RELIGIONE?]
> Movimento: puoi far muovere un qualunque numero di Unità
> Combattimento: se terminata la fase di movimento una o più delle tue unità si trova in una cella adiacente ad un'altra unità nemica, un suo Centro o una sua struttura, puoi Combattere.

# Combattimento
Durante il combattimento ci saranno degli Attaccanti (le unità del giocatore di turno) e dei difensori (quelli di proprietà degli altri giocatori
> Ogni unità attaccante ha un Valore di Combattimento (VC) che è pari al suo livello + bonus Ricerca Militare. Il VC del difensore invece è:
	- Per le Strutture è pari al Bonus Difesa del Centro a cui sono collegate.
	- Per le Città è pari al loro Bonus