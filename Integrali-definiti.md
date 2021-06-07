# Integrali definiti

## Integrale definito

> Un integrale definito viene rappresentato nel seguente modo:
> 
> <code>&int;<sub><i>a</i></sub><sup><i>b</i></sup> &fnof;(<i>x</i>) <i>dx</i></code>.
> - *a* e *b* sono gli **estremi di integrazione**:
>   - *a* è l'**estremo inferiore**
>   - *b* è l'**estremo superiore**
> - *&fnof;*(*x*) è detta **funzione integranda**

### Proprietà dell'integrale definito

***Nota:** le funzioni devono essere continue nell'intervallo [a;b] perché queste proprietà siano verificate.*

#### Additività dell'integrale rispetto all'intervallo di integrazione

<code>&int;<sub><i>a</i></sub><sup><i>c</i></sup> &fnof;(<i>x</i>) <i>dx</i> = &int;<sub><i>a</i></sub><sup><i>b</i></sup> &fnof;(<i>x</i>) <i>dx</i> + &int;<sub><i>b</i></sub><sup><i>c</i></sup> &fnof;(<i>x</i>) <i>dx</i></code>.

#### Integrale della somma di funzioni

<code>&int;<sub><i>a</i></sub><sup><i>b</i></sup> [&fnof;(<i>x</i>) + <i>g</i>(<i>x</i>)] <i>dx</i> = &int;<sub><i>a</i></sub><sup><i>b</i></sup> &fnof;(<i>x</i>) <i>dx</i> + &int;<sub><i>a</i></sub><sup><i>b</i></sup> <i>g</i>(<i>x</i>) <i>dx</i></code>.

#### Integrale del prodotto di una costante per una funzione

<code>&int;<sub><i>a</i></sub><sup><i>b</i></sup> <i>k</i> &sdot; &fnof;(<i>x</i>) <i>dx</i> = <i>k</i> &sdot; &int;<sub><i>a</i></sub><sup><i>b</i></sup> &fnof;(<i>x</i>) <i>dx</i></code>.

#### Confronto tra gli integrali di due funzioni

Se <code>&fnof;(<i>x</i>) &le; <i>g</i>(<i>x</i>)</code>

<code>&int;<sub><i>a</i></sub><sup><i>b</i></sup> &fnof;(<i>x</i>) <i>dx</i> &le; &int;<sub><i>a</i></sub><sup><i>b</i></sup> <i>g</i>(<i>x</i>) <i>dx</i></code>.

#### Integrale del valore assoluto di una funzione

<code>|&int;<sub><i>a</i></sub><sup><i>b</i></sup> &fnof;(<i>x</i>) <i>dx</i>| &le; &int;<sub><i>a</i></sub><sup><i>b</i></sup> |&fnof;(<i>x</i>)| <i>dx</i></code>.

#### Integrale di una funzione costante

<code>&int;<sub><i>a</i></sub><sup><i>b</i></sup> <i>k</i> <i>dx</i> = <i>k</i> &sdot; (<i>b</i> - <i>a</i>)</code>.

### Teorema della media

> **`TEOREMA`**
> 
> Se *&fnof;*(*x*) è una funzione continua in un intervallo [*a*;*b*], esiste almeno un punto *z* dell'intervallo tale che:
> 
> <code>&int;<sub><i>a</i></sub><sup><i>b</i></sup> &fnof;(<i>x</i>) <i>dx</i> = (<i>b</i> - <i>a</i>) &sdot; &fnof;(<i>z</i>)</code>, con *z* &isin; [*a*;*b*].
> - *&fnof;*(*z*) è detto **valore medio**

#### Interpretazione geometrica

Con il teorema della media si trova il punto *z* per cui il rettangolo di base <code>(<i>b</i> - <i>a</i>)</code> e di altezza <code><i>&fnof;</i>(<i>z</i>)</code> abbia la stessa area del *trapezoide* della funzione originale.

## Teorema fondamentale del calcolo integrale

### Funzione integrale

> **`DEFINIZIONE`**
> 
> <code><i>F</i>(<i>x</i>) = &int;<sub><i>a</i></sub><sup><i>x</i></sup> &fnof;(<i>t</i>) <i>dt</i></code>.

### Teorema fondamentale

> **`TEOREMA`**
> 
> **Teorema fondamentale del calcolo integrale**
> 
> Se una funzione *&fnof;*(*x*) è continua in [*a*;*b*], allora esiste la derivata della sua funzione integrale:
> 
> <code><i>F</i>(<i>x</i>) = &int;<sub><i>a</i></sub><sup><i>x</i></sup> &fnof;(<i>t</i>) <i>dt</i></code>
> 
> per ogni punto *x* dell'intervallo [*a*;*b*] ed è uguale a *&fnof;*(*x*), cioè:
> 
> <code><i>F'</i>(<i>x</i>) = &fnof;(<i>x</i>)</code>,
> 
> ovvero *F*(*x*) è una primitiva di *&fnof;*(*x*).

## Calcolo delle aree di superfici piane

## Calcolo dei volumi

## Integrali impropri
