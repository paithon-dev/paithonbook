# Benvenuto in Paithon Book! 🤗

---
```{epigraph}
Gli artisti comprendono che i matematici hanno un modo tutto loro di guardare il mondo, che può far loro percepire le cose in modo diverso.

-- Marcus du Sautoy
```
---

Addentrarsi le prime volte nel mondo del Machine Learning e dell'Intelligenza Artificiale con Python può sembrare una sfida complessa, ma con la giusta guida può diventare un viaggio affascinante e gratificante. Paithon Book è qui per rendere questo percorso più semplice e accessibile, offrendo risorse chiare e pratiche, tutte in italiano, per chiunque voglia imparare, indipendentemente dal proprio livello di partenza.

Non troverai un approccio accademico rigoroso in queste pagine, ma piuttosto una guida intuitiva che ti aiuterà a comprendere meglio i concetti chiave e ad applicarli nei tuoi progetti. Questo libro è perfetto per chi ha una mente curiosa e una passione per la tecnologia. Troverai anche riferimenti a risorse aggiuntive per approfondire ulteriormente gli argomenti trattati.

Questa versione online del libro **è gratuita** ed **in continuo aggiornamento** per stare al passo con le recenti innovazioni nel campo. Aggiorno regolarmente il contenuto con nuove sezioni, argomenti ed esempi in Python. 

---

## Livelli di Complessità

Il libro presenterà due livelli di complessità: **Elementare** e **Superiore**:

- *Elementare*: Questo livello si impegna a spiegare i concetti nel modo più semplice e accessibile possibile. È ideale per chi è alle prime armi negli argomenti trattati nel libro.

- *Superiore*: Il livello "Superiore" approfondisce i concetti in modo più formale e dettagliato. Si presume che il lettore abbia una comprensione di base consolidata e sia pronto per esplorare aspetti più complessi.

Alternare la lettura tra questi due livelli di complessità può favorire una comprensione più approfondita degli argomenti, permettendo al lettore di costruire gradualmente la propria conoscenza e competenza nel campo del machine learning.

Ad esempio di seguito, sarà descritta la funzione ReLU nelle due modalità:

````{tab} Elementare

Immagina di avere un controllo, denominato $f(x)$, per il trasferimento di una somma di denaro $x$ in Euro (€). Se il valore della transazione è positivo, $x > 0$, il filtro $f(x)$ permette il passaggio esattamente di $x$ €. Se la transazione ha un valore negativo o zero, il controllo blocca la transazione e restituisce $0$, evitando così prelievi non autorizzati dal conto del destinatario. In altre parole, la funzione ReLU permette il passaggio di una quantità uguale a quella in ingresso solo se quest'ultima è positiva, altrimenti blocca completamente il passaggio (restituendo zero).

Esempi:

$
\begin{align*}
x &= 10, & f(x) &= 10 \\
x &= -3, & f(x) &= 0 \\
\end{align*}
$

````

````{tab} Superiore

La funzione di attivazione ReLU (Rectified Linear Unit) è definita come:

$$
f(x) = x^+ = \max(0, x)
$$


Questa funzione può anche essere definita "a tratti" (*piecewise*) nel seguente modo:

$$
f(x) = \begin{cases}
    x & \text{se } x > 0, \\
    0 & \text{altrimenti}.
\end{cases}
$$

Questa funzione prende un input $x$ e restituisce $x$ se $x$ è positivo; altrimenti, restituisce zero. \
La ReLU è ampiamente utilizzata nelle reti neurali perché introduce una non linearità essenziale com una derivata costante per valori positivi e negativi di $x$, il che rende più efficiente il calcolo del *backpropagation* durante la fase di addestramento.

````

---

## Supporta il progetto

Ogni progetto ha bisogno di supporto per crescere e migliorare. I progetti open source come questo si basano sul sostegno e l'entusiasmo della comunità. Se questo libro ti è stato utile o credi nel suo valore, ecco come puoi mostrarmi il tuo apprezzamento:

- Metti una ⭐ e condividi il progetto GitHub [Paithon Book](https://github.com/paithon-it/paithonbook)
- Supporta il progetto per contribuire al suo sviluppo ❤️ <span style="display: inline-block; vertical-align: middle;">
    <script type="text/javascript" src="https://cdnjs.buymeacoffee.com/1.0.0/button.prod.min.js" data-name="bmc-button" data-slug="paithon.it" data-color="#e392fe" data-emoji="🔋"  data-font="Cookie" data-text="Ricarica la mia energia" data-outline-color="#000000" data-font-color="#000000" data-coffee-color="#FFDD00" ></script>
</span>

- Aiutaci a scoprire errori e migliorare il progetto aprendo un Issue tramite le pagine del sito.
- Invia i tuoi feedback ✉ a *info@paithon.it*. Saranno utilizzati esclusivamente per migliorare e arricchire il libro.

---