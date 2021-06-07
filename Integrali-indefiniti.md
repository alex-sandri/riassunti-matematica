# Integrali indefiniti

## Integrale indefinito

### Primitive

> **`DEFINIZIONE`**
> 
> Una funzione *F(x)* è una **primitiva** della funzione *&fnof;(x)* definita nell'intervallo [*a*;*b*] se *F(x)* è derivabile in tutto [*a*;*b*] e la sua derivata è *&fnof;(x)*:
> 
> *`F'(x) = f(x)`*

> **`TEOREMA`**
> 
> Se *F(x)* è una primitiva di *&fnof;(x)*, allora le funzioni *F(x) + c*, con *c* numero reale qualsiasi, sono **tutte** e **sole** le primitive di *&fnof;(x)*.
> 
>> `Interpretazione geometrica`
>> 
>> Questo vuol dire che tutte le primitive di *&fnof;(x)*, dette **curve integrali**, **differiscono per una costante** *c*.

### Integrale indefinito

> **`DEFINIZIONE`**
> 
> L'**integrale indefinito** di una funzione *&fnof;(x)* è l'insieme di tutte le primitive *F(x) + c* di *&fnof;(x)*, con *c* numero reale qualunque.
> 
> Si indica con <code>&int;<i>&fnof;(x) dx</i></code>.
> 
> - *&fnof;(x)* si dice **funzione integranda**
> - *x* si dice **variabile di integrazione**
> - La primitiva *F(x)* che si ottiene per *c = 0* si dice **primitiva fondamentale**

> **`DEFINIZIONE`**
> 
> Una funzione che ammette una primitiva (e quindi infinite primitive) si dice **integrabile**

> **`TEOREMA`**
> 
> **Condizione sufficiente di integrabilità**
> 
> Se una funzione è continua in [*a*;*b*], allora ammette primitive nello stesso intervallo.

### Proprietà dell'integrale indefinito

> **`PROPRIETÀ`**
> 
> **Prima proprietà di linearità**
> 
> L'integrale indefinito di una somma di funzioni integrabili è uguale alla somma degli integrali indefiniti delle singole funzioni:
> 
> <code>&int;[<i>&fnof;(x) + g(x)</i>] <i>dx</i> = &int;<i>&fnof;(x) dx</i> + &int;<i>g(x) dx</i></code>

> **`PROPRIETÀ`**
> 
> **Seconda proprietà di linearità**
> 
> L'integrale del prodotto di una costante per una funzione integrabile è uguale al prodotto della costante per l'integrale della funzione:
> 
> <code>&int;<i>k &sdot; &fnof;(x) dx</i> = <i>k</i> &sdot; &int;<i>&fnof;(x) dx</i></code>

## Integrali indefiniti immediati

- <code>&int;[<i>&fnof;</i>(<i>x</i>)]<sup><i>a</i></sup><i>&fnof;</i>'(<i>x</i>) <i>dx</i> = [<i>&fnof;</i>(<i>x</i>)]<sup><i>a</i> + 1</sup> &divide; (<i>a</i> + 1) + <i>c</i></code>, con *a* &ne; -1
- <code>&int;[<i>&fnof;'</i>(<i>x</i>)</i> &divide; <i>&fnof;</i>(<i>x</i>)] <i>dx</i> = ln|<i>&fnof;</i>(<i>x</i>)| + <i>c</i></code>
- <code>&int;<i>&fnof;'</i>(<i>x</i>)a<sup><i>&fnof;</i>(<i>x</i>)</sup> <i>dx</i> = (<i>a<sup><i>&fnof;</i>(<i>x</i>)</sup></i> &divide; <i>ln <i>a</i></i>) + <i>c</i></code>
- <code>&int;[<i>&fnof;'</i>(<i>x</i>) &divide; (<i>k</i><sup>2</sup> + [<i>&fnof;</i>(<i>x</i>)]<sup>2</sup>) <i>dx</i> = (1/<i>k</i>) arctan (<i>&fnof;</i>(<i>x</i>) &divide; <i>k</i>) + <i>c</i></code>

## Integrazione per sostituzione

1. Si pone *t* = *g(x)*
2. Si calcola il differenziale *dt*, oppure si calcola *x* e il suo differenziale *dx*
3. Si sostituisce nell'integrale dato, in modo da ottenere un integrale nella variabile *t*
4. Si calcola, se possibile, l'integrale rispetto a *t*
5. Si ritorna alla variabile *x* e si ottiene quindi il risultato cercato

> **`ESEMPIO`**
> 
> <code>&int;[<i>3 &divide; &radic;(<i>x</i> + 2)] dx</i></code>
> 
> 1. <code>&int;[<i>3 &divide; &radic;(<i>x</i> + 2)] dx</i></code>
> 2. <code><i>t</i> = &radic;(<i>x</i> + 2)</code>
> 3. <code><i>dt</i> = (1/2) &sdot; (<i>x</i> + 2)<sup>-(1/2)</sup> <i>dx</i></code>
> 4. <code>&int;[<i>3 &divide; &radic;(<i>x</i> + 2)] dx</i></code>
> 5. <code>2 &sdot; &int;[<i>3 &divide; (2 &sdot; &radic;(<i>x</i> + 2))] dx</i></code>
> 6. <code>6 &sdot; &int;[<i>1 &divide; (2 &sdot; &radic;(<i>x</i> + 2))] dx</i></code>
> 7. <code>6 &sdot; &int;<i>dt</i></code>
> 8. <code>6 &sdot; <i>t</i> + <i>c</i></code>
> 9. <code>6 &sdot; &radic;(<i>x</i> + 2) + <i>c</i></code>

## Integrazione per parti

> **`FORMULA`**
> 
> <code>&int;<i>&fnof;(x) &sdot; g'(x) dx</i> = <i>&fnof;(x) &sdot; g(x)</i> - &int;<i>&fnof;'(x) &sdot; g(x) dx</i></code>
> 
> - *&fnof;(x)* viene chiamato **fattore finito**
> - *g'(x)* viene chiamato **fattore differenziale**

## Integrazione di funzioni razionali fratte

### Il numeratore è la derivata del denominatore

*INTEGRALE IMMEDIATO*

### Il denominatore è di primo grado

*INTEGRALE IMMEDIATO*

### Il denominatore è di secondo grado

<code>&int; [(<i>px</i> + <i>q</i>) &divide; (<i>ax</i><sup>2</sup> + <i>bx</i> + <i>c</i>)] <i>dx</i></code>

I seguenti casi valgono se e solo se il grado del numeratore è **minore** di quello del denominatore.

#### Il discriminante è positivo: &#8710; > 0

Si cercano i valori *A* e *B* che rendono vera l'identità:

<code>(<i>px</i> + <i>q</i>) &divide; (<i>ax</i><sup>2</sup> + <i>bx</i> + <i>c</i>) = [<i>A</i> &divide; <i>a</i>(<i>x</i> - <i>x</i><sub>1</sub>)] + [<i>B</i> &divide; (<i>x</i> - <i>x</i><sub>2</sub>)]</code>

#### Il discriminante è nullo: &#8710; = 0

Si cercano i valori *A* e *B* che rendono vera l'identità:

<code>(<i>px</i> + <i>q</i>) &divide; (<i>ax</i><sup>2</sup> + <i>bx</i> + <i>c</i>) = [<i>A</i> &divide; <i>a</i>(<i>x</i> - <i>x</i><sub>1</sub>)] + [<i>B</i> &divide; (<i>x</i> - <i>x</i><sub>1</sub>)<sup>2</sup>]</code>

#### Il discriminante è negativo: &#8710; < 0

##### *p* = 0

Si tenta di portare l'integrale nella forma:

<code>&int;[<i>&fnof;'</i>(<i>x</i>) &divide; (<i>k</i><sup>2</sup> + [<i>&fnof;</i>(<i>x</i>)]<sup>2</sup>) <i>dx</i> = (1/<i>k</i>) arctan (<i>&fnof;</i>(<i>x</i>) &divide; <i>k</i>) + <i>c</i></code>

##### *p* &ne; 0

*NON VERRÀ RIPORTATO*
