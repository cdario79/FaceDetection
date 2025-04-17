# Sistema di Face Detection per una Fotocamera Digitale

## Contesto del Progetto

La **ProCam S.p.A.** è pronta a lanciare una nuova fotocamera digitale compatta, accessibile e pensata per i giovani appassionati di fotografia.  
L'obiettivo principale del prodotto è **facilitare l'esperienza di scatto**, in particolare per i **selfie con una o più persone**.

## Sfida

Sei stato assunto come **Data Scientist** per sviluppare un **sistema di rilevamento volti nelle immagini**, che aiuterà i tecnici a **ottimizzare automaticamente le impostazioni della fotocamera** durante i selfie.

Il tuo compito è realizzare una **pipeline** che:

- Identifichi i volti presenti nelle immagini
- Restituisca le **coordinate dei bounding box** dove i volti sono individuati
- Restituisca una **lista vuota** se non ci sono volti

> Si tratta di un problema di *Computer Vision*, più precisamente di **Face Detection**.

---

## Requisiti del Progetto

### Obiettivo

Costruire un sistema di **rilevamento dei volti** utilizzando **Scikit-learn**.  
La pipeline deve essere in grado di:

- Prendere un’immagine in ingresso  
- Restituire una lista di coordinate dei bounding box dove sono presenti volti  
- Restituire una lista vuota se nell’immagine non ci sono volti

### Limitazioni

- **Dataset**:  
  Non ti viene fornito un dataset. Devi cercare un dataset adatto in rete o, in mancanza di alternative, costruirlo tu stesso.
  
- **Modelli pre-addestrati**:  
  Non è consentito utilizzare modelli pre-addestrati. Il modello di Face Detection dovrà essere **addestrato da zero con Scikit-learn**.
  
- **Risorse di calcolo**:  
  Lavorerai su un sistema con **capacità di calcolo limitate**. Il modello dovrà essere ottimizzato per utilizzare poche risorse.
  
- **Documentazione**:  
  La soluzione deve essere **ben documentata**.  
  Ogni decisione adottata (scelta degli algoritmi, preprocessamento, tecniche di ottimizzazione) dovrà essere **spiegata**.  
  Inoltre, ogni **risorsa esterna** utilizzata (paper accademici, articoli di blog, codice GitHub) dovrà essere **citata**.

---

## Ricerca Bibliografica

Poiché **non ti vengono fornite indicazioni dettagliate sull'implementazione**, è essenziale condurre un'approfondita **ricerca bibliografica** per identificare le soluzioni migliori.  
Dovrai **analizzare approcci già esistenti** e **adattarli alle limitazioni del progetto**.

---

## Supporto

Il progetto è complesso e richiede competenze avanzate in **Computer Vision** e **Machine Learning**.  
Se dovessi incontrare difficoltà durante lo sviluppo, potrai sempre contare sul **supporto dei tuoi coach** nella *Classe Virtuale di Machine Learning su Discord*.

---

## Conclusione

La realizzazione di un sistema di rilevamento volti con **risorse limitate** e **senza dataset preconfezionato** è una **sfida** che richiede una forte capacità di **problem-solving** e **adattamento**.  

Una pipeline **ben ottimizzata e documentata** non solo contribuirà al successo del lancio del prodotto **ProCam**, ma rappresenterà anche un **passo significativo nella tua crescita professionale** come Data Scientist.

---

## Modalità di Consegna

🔗 Link pubblico a **notebook di Google Colab**
