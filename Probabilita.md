# Probabilità

## Eventi

> **`DEFINIZIONE`**
> 
> - Un **esperimento aleatorio** è un fenomeno di cui non riusciamo a prevedere il risultato con certezza.
> - L'insieme *U* di tutti i possibili risultati di un esperimento si chiama **spazio campionario** o **universo**.
> - Un **evento** è un qualunque sottoinsieme dello spazio campionario; un evento formato formato da un singolo risultato dell'esperimento è detto **evento elementare**.

## Concezione classica della probabilità

> **`DEFINIZIONE`**
> 
> La **probabilità** di un evento *E* è il rapporto fra il numero dei casi favorevoli *f* e quello dei casi possibili *u* quando sono tutti ugualmente possibili.
> 
> <code><i>p</i>(<i>E</i>) = <i>f</i> &divide; <i>u</i></code>.
> 
> - 0 &le; *p*(E) &le; 1
> - Se *f* = *u*, l'evento è **certo**
> - Se *f* = 0, l'evento è **impossibile**

> **`DEFINIZIONE`**
> 
> L'**evento contrario** *Ē* si verifica se e solo se non si verifica *E*.
> 
> <code><i>p</i>(<i>Ē</i>) = 1 - <i>p</i>(<i>E</i>)</code>.

## Somma logica di eventi

> **`DEFINIZIONE`**
> 
> Dati due eventi *E₁* ed *E₂* di uno stesso spazio campionario:
> - L'**evento unione** o **somma logica** è l'evento *E₁* &cup; *E₂* che si verifica quando è verificato *almeno* uno degli eventi.
> - L'**evento intersezione** o **prodotto logico** è l'evento *E₁* &cap; *E₂* che si verifica quando sono verificati *entrambi* gli eventi.

> **`DEFINIZIONE`**
> 
> Due eventi *E₁* ed *E₂*, relativi allo stesso spazio campionario, sono **incompatibili** se il verificarsi di uno esclude il verificarsi contemporaneo dell'altro, cioè *E₁* ∩ *E₂* = &empty;. In caso contrario sono **compatibili**.

> **`TEOREMA`**
> 
> La **probabilità della somma logica di due eventi** *E₁* ed *E₂* è uguale alla somma delle loro probabilità diminuita della probabilità del loro evento intersezione:
> 
> <code><i>p</i>(<i>E₁</i> &cup; <i>E₂</i>) = <i>p</i>(<i>E₁</i>) + <i>p</i>(<i>E₂</i>) - <i>p</i>(<i>E₁</i> &cap; <i>E₂</i>)</code>.
> 
> In particolare, se gli eventi sono *incompatibili*:
> 
> <code><i>p</i>(<i>E₁</i> &cup; <i>E₂</i>) = <i>p</i>(<i>E₁</i>) + <i>p</i>(<i>E₂</i>)</code>.

## Probabilità condizionata

> **`DEFINIZIONE`**
> 
> Dati due eventi *E₁* ed *E₂*, con *p*(*E₂*) &ne; 0, si chiama **probabilità condizionata** di *E₁* rispetto a *E₂*, e si indica con *p*(*E₁* \| *E₂*), la probabilità che si verifichi *E₁* nell'ipotesi che *E₂* sia verificato.
> 
> - Se *p*(*E₁*) < *p*(*E₁* \| *E₂*), gli eventi sono *dipendenti* e *correlati positivamente*
> - Se *p*(*E₁*) = *p*(*E₁* \| *E₂*), gli eventi sono *indipendenti*
> - Se *p*(*E₁*) > *p*(*E₁* \| *E₂*), gli eventi sono *dipendenti* e *correlati negativamente*

> **`TEOREMA`**
> 
> La probabilità condizionata di un evento *E₁* rispetto a un evento *E₂*, non impossibile, è:
> 
> <code><i>p</i>(<i>E<sub>1</sub></i> | <i>E<sub>2</sub></i>) = <i>p</i>(<i>E<sub>1</sub></i> &cap; <i>E<sub>2</sub></i>) &divide; <i>p</i>(<i>E<sub>2</sub></i>)</code>, con *p*(*E₂*) &ne; 0.

## Prodotto logico di eventi

> **`TEOREMA`**
> 
> La **probabilità del prodotto logico di due eventi** *E₁* ed *E₂* è uguale al prodotto della probabilità dell'evento *E₁* per la probabilità dell'evento *E₂* nell'ipotesi che *E₁* si sia verificato:
> 
> <code><i>p</i>(<i>E<sub>1</sub></i> &cap; <i>E<sub>2</sub></i>) = <i>p</i>(<i>E<sub>1</sub></i>) &sdot; <i>p</i>(<i>E<sub>2</sub></i> | <i>E<sub>1</sub></i>)</code>.
> 
> In particolare, nel caso di eventi *indipendenti*:
> 
> <code><i>p</i>(<i>E<sub>1</sub></i> &cap; <i>E<sub>2</sub></i>) = <i>p</i>(<i>E<sub>1</sub></i>) &sdot; <i>p</i>(<i>E<sub>2</sub></i>)</code>.

Nel caso di tre eventi la formula diventa:

<code><i>p</i>(<i>E<sub>1</sub></i> &cap; <i>E<sub>2</sub></i> &cap; <i>E<sub>3</sub></i>) = <i>p</i>(<i>E<sub>1</sub></i>) &sdot; <i>p</i>(<i>E<sub>2</sub></i> | <i>E<sub>1</sub></i>) &sdot; <i>p</i>(<i>E<sub>3</sub></i> | (<i>E<sub>1</sub></i> &cap; <i>E<sub>2</sub></i>))</code>.

### Problema delle prove ripetute

> **`TEOREMA`**
> 
> **Schema delle prove ripetute (o di Bernoulli)**
> 
> Dato un esperimento aleatorio ripetuto nelle stesse condizioni *n* volte e indicato con *E* un evento che rappresenta il successo dell'esperimento e ha probabilità costante *p* di verificarsi e probabilità *q* = 1 - *p* di non verificarsi, la probabilità di ottenere *k* successi su *n* prove è:
> 
> <code><i>p</i><sub>(<i>k</i>,<i>n</i>)</sub> = <i>C<sub>n,k</sub></i> &sdot; <i>p<sup><i>k</i></sup></i> &sdot; <i>q<sup><i>n - k</i></sup></i></code>.

## Teorema di Bayes

### Se l'evento deve accadere: la disintegrazione

> **`FORMULA`**
> 
> Un evento *E* si può esprimere come unione di eventi composti a due a due incompatibili nel seguente modo:
> 
> *E* = (*E* &cap; *E₁*) &cup; (*E* &cap; *E₂*) &cup; ... &cup; (*E* &cap; *Eₙ*), dove *E₁*, *E₂*, ..., *Eₙ* costituiscono una *partizione* dello spazio campionario *U*, cioè sono eventi:
> - Non vuoti
> - Incompatibili a due a due
> - Tali che la loro unione è uguale a *U*
> 
> <code><i>p</i>(<i>E</i>) = <i>p</i>(<i>E<sub>1</sub></i>) &sdot; <i>p</i>(<i>E</i> | <i>E<sub>1</sub></i>) + <i>p</i>(<i>E<sub>2</sub></i>) &sdot; <i>p</i>(<i>E</i> | <i>E<sub>2</sub></i>) + ... + <i>p</i>(<i>E<sub>n</sub></i>) &sdot; <i>p</i>(<i>E</i> | <i>E<sub>n</sub></i>)</code>.

### Se l'evento è accaduto: teorema di Bayes
