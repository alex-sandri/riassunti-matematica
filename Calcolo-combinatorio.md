# Calcolo combinatorio

## Disposizioni

### Disposizioni semplici

> **`DEFINIZIONE`**
> 
> Le **disposizioni semplici** di *n* elementi di classe *k* (con 0 < *k* &le; *n*) sono tutti i gruppi di *k* elementi scelti fra gli *n*, che differiscono per *almeno un elemento o per l'ordine* con cui gli elementi sono collocati:
> 
> <code><i>D<sub>n,k</sub></i> = <i>n</i> &sdot; (<i>n</i> - 1) &sdot; (<i>n</i> - 2) &sdot; (<i>n</i> - 3) &sdot; ... &sdot; (<i>n</i> - <i>k</i> + 1)</code>, con *n*, *k* &isin; &Nopf; e 0 < *k* &le; *n*.
> 
>> **`ESEMPIO`**
>> 
>> <code><i>D<sub>7,3</sub></i> = 7 &sdot; 6 &sdot; 5</code>.

### Disposizioni con ripetizione

> **`DEFINIZIONE`**
> 
> Le **disposizioni con ripetizione** di *n* elementi distinti di classe *k* (con *k* numero naturale qualunque non nullo) sono tutti i gruppi di *k* elementi, anche ripetuti, scelti fra gli *n*, che differiscono per *almeno un elemento o per il loro ordine*:
> 
> <code><i>D'<sub>n,k</sub></i> = <i>n<sup>k</sup></i></code>.
> 
>> **`ESEMPIO`**
>> 
>> <code><i>D'<sub>22,2</sub></i> = 22<sup>2</sup> = 484</code>.

## Permutazioni

### Permutazioni semplici

> **`DEFINIZIONE`**
> 
> Le **permutazioni semplici** di *n* elementi distinti sono tutti i gruppi formati dagli *n* elementi, che differiscono per il loro *ordine*:
> 
> <code><i>P<sub>n</sub></i> = <i>n</i>! = <i>n</i> &sdot; (<i>n</i> - 1) &sdot; (<i>n</i> - 2) &sdot; ... &sdot; 3 &sdot; 2 &sdot; 1</code>, con *n* &ge; 2.
> 
>> **`ESEMPIO`**
>> 
>> <code><i>P<sub>6</sub></i> = 6! = 6 &sdot; 5 &sdot; 4 &sdot; 3 &sdot; 2 &sdot; 1 = 720</code>.

### Permutazioni con ripetizione

> **`DEFINIZIONE`**
> 
> Le **permutazioni con ripetizione** di *n* elementi, di cui *h*, *k*, ... ripetuti, sono tutti i gruppi formati dagli *n* elementi, che differiscono per l'*ordine* in cui si presentanto gli elementi distinti e la *posizione* che occupano gli elementi ripetuti:
> 
> <code><i>P<sub>n</sub><sup>(<i>h</i>,<i>k</i>,...)</sup></i> = <i>n</i>! &divide; (<i>h</i>! &sdot; <i>k</i>! &sdot; ...)</code>.
> 
>> **`ESEMPIO`**
>> 
>> <code><i>P<sub>5</sub><sup>(2)</sup></i> = 5! &divide; 2! = (5 &sdot; 4 &sdot; 3 &sdot; 2 &sdot; 1) &divide; 2 = 60</code>.

## Combinazioni

### Combinazioni semplici

> **`DEFINIZIONE`**
> 
> Le **combinazioni semplici** di *n* elementi distinti di classe *k* (con 0 < *k* &le; *n*) sono tutti i gruppi di *k* elementi, scelti fra gli *n*, che differiscono per almeno un elemento (ma non per l'ordine):
> 
> <code><i>C<sub>n,k</sub></i> = <i>D<sub>n,k</sub></i> &divide; <i>P<sub>k</sub></i></code>, con *k* &le; *n*.
> 
>> **`ESEMPIO`**
>> 
>> <code><i>C<sub>5,2</sub></i> = (5 &sdot; 4) &divide; 2! = 10</code>.

### Combinazioni con ripetizione

> **`DEFINIZIONE`**
> 
> Le **combinazioni con ripetizione** di *n* elementi distinti di classe *k* (con *k* numero naturale qualunque non nullo) sono tutti i gruppi di *k* elementi che si possono formare, nei quali:
> - Ogni elemento può essere ripetuto al massimo fino a *k* volte
> - Non interessa l'ordine con cui gli elementi si presentano
> - È diverso il numero di volte col quale un elemento compare
> 
> <code><i>C'<sub>n,k</sub></i> = <i>C<sub>n+k-1,k</sub></i></code>.
> 
>> **`ESEMPIO`**
>> 
>> <code><i>C'<sub>2,4</sub></i> = <i>C<sub>2+4-1,4</sub></i> = <i>C<sub>5,4</sub></i> = 5</code>.
