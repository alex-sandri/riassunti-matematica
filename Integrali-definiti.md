# Integrali definiti

## Integrale definito

> Un integrale definito viene rappresentato nel seguente modo:
> 
> <code>&int;<sub><i>a</i></sub><sup><i>b</i></sup> <i>&fnof;</i>(<i>x</i>) <i>dx</i></code>.
> - *a* e *b* sono gli **estremi di integrazione**:
>   - *a* è l'**estremo inferiore**
>   - *b* è l'**estremo superiore**
> - *&fnof;*(*x*) è detta **funzione integranda**

### Proprietà dell'integrale definito

***Nota:** le funzioni devono essere continue nell'intervallo [a;b] perché queste proprietà siano verificate.*

#### Additività dell'integrale rispetto all'intervallo di integrazione

<code>&int;<sub><i>a</i></sub><sup><i>c</i></sup> <i>&fnof;</i>(<i>x</i>) <i>dx</i> = &int;<sub><i>a</i></sub><sup><i>b</i></sup> <i>&fnof;</i>(<i>x</i>) <i>dx</i> + &int;<sub><i>b</i></sub><sup><i>c</i></sup> <i>&fnof;</i>(<i>x</i>) <i>dx</i></code>.

#### Integrale della somma di funzioni

<code>&int;<sub><i>a</i></sub><sup><i>b</i></sup> [<i>&fnof;</i>(<i>x</i>) + <i>g</i>(<i>x</i>)] <i>dx</i> = &int;<sub><i>a</i></sub><sup><i>b</i></sup> <i>&fnof;</i>(<i>x</i>) <i>dx</i> + &int;<sub><i>a</i></sub><sup><i>b</i></sup> <i>g</i>(<i>x</i>) <i>dx</i></code>.

#### Integrale del prodotto di una costante per una funzione

<code>&int;<sub><i>a</i></sub><sup><i>b</i></sup> <i>k</i> &sdot; <i>&fnof;</i>(<i>x</i>) <i>dx</i> = <i>k</i> &sdot; &int;<sub><i>a</i></sub><sup><i>b</i></sup> <i>&fnof;</i>(<i>x</i>) <i>dx</i></code>.

#### Confronto tra gli integrali di due funzioni

Se <code><i>&fnof;</i>(<i>x</i>) &le; <i>g</i>(<i>x</i>)</code>

<code>&int;<sub><i>a</i></sub><sup><i>b</i></sup> <i>&fnof;</i>(<i>x</i>) <i>dx</i> &le; &int;<sub><i>a</i></sub><sup><i>b</i></sup> <i>g</i>(<i>x</i>) <i>dx</i></code>.

#### Integrale del valore assoluto di una funzione

<code>|&int;<sub><i>a</i></sub><sup><i>b</i></sup> <i>&fnof;</i>(<i>x</i>) <i>dx</i>| &le; &int;<sub><i>a</i></sub><sup><i>b</i></sup> |<i>&fnof;</i>(<i>x</i>)| <i>dx</i></code>.

#### Integrale di una funzione costante

<code>&int;<sub><i>a</i></sub><sup><i>b</i></sup> <i>k</i> <i>dx</i> = <i>k</i> &sdot; (<i>b</i> - <i>a</i>)</code>.

### Teorema della media

> **`TEOREMA`**
> 
> Se *&fnof;*(*x*) è una funzione continua in un intervallo [*a*;*b*], esiste almeno un punto *z* dell'intervallo tale che:
> 
> <code>&int;<sub><i>a</i></sub><sup><i>b</i></sup> <i>&fnof;</i>(<i>x</i>) <i>dx</i> = (<i>b</i> - <i>a</i>) &sdot; <i>&fnof;</i>(<i>z</i>)</code>, con *z* &isin; [*a*;*b*].
> - *&fnof;*(*z*) è detto **valore medio**

#### Interpretazione geometrica

Con il teorema della media si trova il punto *z* per cui il rettangolo di base <code>(<i>b</i> - <i>a</i>)</code> e di altezza <code><i>&fnof;</i>(<i>z</i>)</code> abbia la stessa area del *trapezoide* della funzione originale.

## Teorema fondamentale del calcolo integrale

### Funzione integrale

> **`DEFINIZIONE`**
> 
> <code><i>F</i>(<i>x</i>) = &int;<sub><i>a</i></sub><sup><i>x</i></sup> <i>&fnof;</i>(<i>t</i>) <i>dt</i></code>.

### Teorema fondamentale

> **`TEOREMA`**
> 
> **Teorema fondamentale del calcolo integrale**
> 
> Se una funzione *&fnof;*(*x*) è continua in [*a*;*b*], allora esiste la derivata della sua funzione integrale:
> 
> <code><i>F</i>(<i>x</i>) = &int;<sub><i>a</i></sub><sup><i>x</i></sup> <i>&fnof;</i>(<i>t</i>) <i>dt</i></code>
> 
> per ogni punto *x* dell'intervallo [*a*;*b*] ed è uguale a *&fnof;*(*x*), cioè:
> 
> <code><i>F'</i>(<i>x</i>) = <i>&fnof;</i>(<i>x</i>)</code>,
> 
> ovvero *F*(*x*) è una primitiva di *&fnof;*(*x*).

### Calcolo dell'integrale definito

> **`FORMULA`**
> 
> **Formula di Leibniz-Newton**
> 
> L'integrale definito di una funzione continua *&fnof;*(*x*) è uguale alla differenza tra i valori assunti da una qualunque primitiva &phi;(*x*) di *&fnof;*(*x*) rispettivamente nell'estremo superiore di integrazione e nell'estremo inferiore:
> 
> <code>&int;<sub><i>a</i></sub><sup><i>b</i></sup> <i>&fnof;</i>(<i>x</i>) <i>dx</i> = &phi;(<i>b</i>) - &phi;(<i>a</i>)</code>.
> 
> Di solito si sceglie la primitiva corrispondente a *c* = 0.
> 
> Si può indicare in modo sintetico:
> 
> <code>&phi;(<i>b</i>) - &phi;(<i>a</i>) = [&phi;(<i>x</i>)]<sub>a</sub><sup>b</sup></code>.

## Calcolo delle aree di superfici piane

> **`REGOLA`**
> 
> **Area della superficie delimitata dai grafici di due funzioni**
> 
> Siano *&fnof;*(*x*) e *g*(*x*) due funzioni continue definite nello stesso intervallo [*a*;*b*], con *&fnof;*(*x*) &ge; *g*(*x*), per ogni *x* in [*a*;*b*], i cui grafici racchiudano una superficie; allora l'area *S* della superficie è data da:
> 
> <code><i>S</i> = &int;<sub><i>a</i></sub><sup><i>b</i></sup> [<i>&fnof;</i>(<i>x</i>) - <i>g</i>(<i>x</i>)] <i>dx</i></code>.

## Calcolo dei volumi

### Rotazione intorno all'asse *x*

> **`DEFINIZIONE`**
> 
> Dato il trapezoide esteso all'intervallo [*a*;*b*], delimitato dal grafico della funzione *y* = *&fnof;*(*x*) (positiva o nulla), dall'asse *x* e dalle rette *x* = *a* e *x* = *b*, il **volume del solido di rotazione** che si ottiene ruotando il trapezoide intorno all'asse *x* di un giro completo è:
> 
> <code><i>V</i> = &pi; &sdot; &int;<sub><i>a</i></sub><sup><i>b</i></sup> <i>&fnof;</i><sup>2</sup>(<i>x</i>) <i>dx</i></code>.

### Rotazione intorno all'asse *y*

> **`DEFINIZIONE`**
> 
> Dato il trapezoide delimitato dal grafico della funzione *x* = *&fnof;*(*y*) (positiva o nulla), dall'asse *y* e dalle rette *y* = *a* e *y* = *b*, il valore del volume del solido di rotazione che si ottiene ruotando il trapezoide intorno all'asse *y* di un giro completo è il numero espresso dal seguente integrale:
> 
> <code><i>V</i> = &pi; &sdot; &int;<sub><i>a</i></sub><sup><i>b</i></sup> <i>&fnof;</i><sup>2</sup>(<i>y</i>) <i>dy</i></code>.

## Integrali impropri

### Integrale di una funzione con un numero finito di punti di discontinuità in [*a*;*b*]

> Se una funzione *&fnof;*(*x*) è continua nell'intervallo \[*a*;*b*\[, ovvero non è continua solo in *b*, allora si può costruire la funzione integrale
> 
> <code><i>F</i>(<i>z</i>) = &int;<sub><i>a</i></sub><sup><i>z</i></sup> <i>&fnof;</i>(<i>x</i>) <i>dx</i></code>
> 
> in cui *z* è un punto qualsiasi dell'intervallo \[*a*;*b*\[ e:
> - Se esiste finito il limite
> 
>   lim *F*(*z*)\
>   <sup><i>z</i>-><i>b<sup>-</sup></i></sup>

### Integrale di una funzione in un intervallo illimitato
