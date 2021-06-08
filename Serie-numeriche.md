# Serie numeriche

## Che cos'è una serie numerica

> **`DEFINIZIONE`**
> 
> Data una successione di numeri *a*<sub>1</sub>, *a*<sub>2</sub>, *a*<sub>3</sub>, ..., *a*<sub>n</sub>, ..., la **serie numerica**
> 
> <pre><code><sub> +&infin;</sub>
>  &sum; <i>a<sub>n</sub></i>
> <sup> <i>n</i>=1</sup>
> </code></pre>
> 
> si ottiene considerando la successione:
> 
> *s*<sub>1</sub> = *a*<sub>1</sub>\
> *s*<sub>2</sub> = *a*<sub>1</sub> + *a*<sub>2</sub>\
> *s*<sub>3</sub> = *a*<sub>1</sub> + *a*<sub>2</sub> + *a*<sub>3</sub>\
> ...\
> *s*<sub>n</sub> = *a*<sub>1</sub> + *a*<sub>2</sub> + *a*<sub>3</sub> + ... + *a*<sub>n</sub>\
> ...
> 
> - I numeri *a*<sub>1</sub>, *a*<sub>2</sub>, *a*<sub>3</sub>, ... sono i **termini** della serie
> - *a*<sub>n</sub> è il **termine generale**
> - Le somme *s*<sub>1</sub>, *s*<sub>2</sub>, *s*<sub>3</sub>, ..., *s*<sub>n</sub>, ... sono le **somme parziali** o **ridotte** della serie
> - *s*<sub>n</sub> è la **ridotta *n*-esima** o **ridotta di ordine *n***

## Serie convergenti, divergenti, indeterminate

A seconda del comportamento, una serie può essere *convergente*, *divergente* o *indeterminata*. Questo comportamento è detto **carattere** della serie.

### Serie convergente

> **`DEFINIZIONE`**
> 
> Una **serie**
> 
> <pre><code><sub> +&infin;</sub>
>  &sum; <i>a<sub>n</sub></i>
> <sup> <i>n</i>=1</sup>
> </code></pre>
> 
> è **convergente** se la successione delle sue ridotte ha un limite finito, cioè se
> 
> <pre><code>
>  lim <i>s<sub>n</sub></i> = <i>s</i>, <i>s</i> &isin; &Ropf;
> <sup> <i>n</i>->+&infin;</sup>
> </code></pre>
> 
> Il numero *s* è la **somma** (o **valore**) della serie.

### Serie divergente

> **`DEFINIZIONE`**
> 
> Una **serie**
> 
> <pre><code><sub> +&infin;</sub>
>  &sum; <i>a<sub>n</sub></i>
> <sup> <i>n</i>=1</sup>
> </code></pre>
> 
> è:
> - **divergente positivamente** se la successione delle sue ridotte ha limite +&infin;, ossia
> 
>   <pre><code>
>    lim <i>s<sub>n</sub></i> = +&infin;
>   <sup> <i>n</i>->+&infin;</sup>
>   </code></pre>
> - **divergente negativamente** se la successione delle sue ridotte ha limite -&infin;, ossia
> 
>   <pre><code>
>    lim <i>s<sub>n</sub></i> = -&infin;
>   <sup> <i>n</i>->+&infin;</sup>
>   </code></pre>

### Serie indeterminata

> **`DEFINIZIONE`**
> 
> Una **serie**
> 
> <pre><code><sub> +&infin;</sub>
>  &sum; <i>a<sub>n</sub></i>
> <sup> <i>n</i>=1</sup>
> </code></pre>
> 
> è **indeterminata** se la successione delle sue ridotte è indeterminata, cioè se non è né convergente né divergente.

### Serie geometrica

> **`DEFINIZIONE`**
> 
> Chiamiamo **serie geometrica** di ragione *q* la serie:
> 
> <pre><code><sub> +&infin;</sub>
>  &sum; <i>q<sup>n</sup></i> = 1 + <i>q</i> + <i>q</i><sup>2</sup> + <i>q</i><sup>3</sup> + ... + <i>q<sup>n</sup></i> + ...
> <sup> <i>n</i>=0</sup>
> </code></pre>
> 
> **Converge** se -1 < *q* < 1, con somma: 1 &divide; (1- *q*)\
> **Diverge** se *q* &ge; 1\
> **Indeterminata** se *q* &le; -1

### Serie telescopica

> **`DEFINIZIONE`**
> 
> Una **serie telescopica** è una serie in cui il termine generale si può scrivere come differenza fra due termini consecutivi di una successione.

## Criterio generale di convergenza

> **`TEOREMA`**
> 
> **Condizione necessaria di convergenza**
> 
> Se una serie è convergente, il suo termine generale *a*<sub><i>n</i></sub> tende a 0 per *n* -> +&infin;:
> 
> <pre><code>
>  lim <i>a<sub>n</sub></i> = 0
> <sup> <i>n</i>->+&infin;</sup>
> </code></pre>

## Serie a termini positivi

> **`TEOREMA`**
> 
> **Convergenza o divergenza della serie a termini positivi**
> 
> Una serie a termini positivi (oppure non negativi) o è convergente o è divergente positivamente.

### Criteri di convergenza

#### Criterio del confronto

> **`TEOREMA`**
> 
> **Criterio del confronto o di Gauss**
> 
> Se una serie a termini non negativi ammette una serie maggiorante convergente, allora è convergente; se ammette una serie minorante divergente, allora è divergente.

#### Criterio del confronto asintotico

> **`TEOREMA`**
> 
> **Criterio del confronto asintotico**
> 
> Date le serie
> 
> <pre><code><sub> +&infin;</sub>
>  &sum; <i>a<sub>n</sub></i>
> <sup> <i>n</i>=1</sup>
> </code></pre>
> 
> e
> 
> <pre><code><sub> +&infin;</sub>
>  &sum; <i>b<sub>n</sub></i>
> <sup> <i>n</i>=1</sup>
> </code></pre>
> 
> entrambe a termini positivi, se esiste finito il limite
> 
> <pre><code>
>  lim (<i>a<sub>n</sub></i> &divide; <i>b<sub>n</sub></i>) = <i>l</i> &ne; 0
> <sup> <i>n</i>->+&infin;</sup>
> </code></pre>
> 
> allora le due serie hanno lo stesso carattere.

#### Criterio del rapporto

> **`TEOREMA`**
> 
> **Criterio del rapporto o di d'Alembert**
> 
> Data una serie
> 
> <pre><code><sub> +&infin;</sub>
>  &sum; <i>a<sub>n</sub></i>
> <sup> <i>n</i>=1</sup>
> </code></pre>
> 
> a termini positivi tale che esiste il limite
> 
> <pre><code>
>  lim (<i>a<sub>n+1</sub></i> &divide; <i>a<sub>n</sub></i>) = <i>l</i>
> <sup> <i>n</i>->+&infin;</sup>
> </code></pre>
> 
> - **Converge** se *l* < 1
> - **Diverge** se *l* > 1 o *l* = +&infin;
> - **Il criterio è inconcludente** se *l* = 1

#### Criterio della radice

> **`TEOREMA`**
> 
> **Criterio della radice o di Cauchy**
> 
> Data una serie
> 
> <pre><code><sub> +&infin;</sub>
>  &sum; <i>a<sub>n</sub></i>
> <sup> <i>n</i>=1</sup>
> </code></pre>
> 
> a termini positivi tale che esiste il limite
> 
> <pre><code>     <sub><i>n __</i></sub>
>  lim &radic;<i>a<sub>n</sub></i> = <i>l</i>
> <sup> <i>n</i>->+&infin;</sup>
> </code></pre>
> 
> - **Converge** se *l* < 1
> - **Diverge** se *l* > 1 o *l* = +&infin;
> - **Il criterio è inconcludente** se *l* = 1

### Serie armonica di ordine *&alpha;*

> **`DEFINIZIONE`**
> 
> La **serie armonica di ordine *&alpha;*** è una serie del tipo:
> 
> <pre><code><sub> +&infin;</sub>
>  &sum; (1 &divide; <i>n<sup>&alpha;</sup></i>)
> <sup> <i>n</i>=1</sup>
> </code></pre>
> 
> con *&alpha;* &isin; ℝ
> 
> - **Converge** se *&alpha;* > 1
> - **Diverge** se *&alpha;* &le; 1

## Serie a termini di segno qualunque

### Serie a termini di segno alterno

> **`DEFINIZIONE`**
> 
> Una **serie a termini di segno alterno** è una serie in cui i termini di posto dispari sono positivi e quelli di posto pari sono negativi o viceversa.

### Convergenza assoluta
