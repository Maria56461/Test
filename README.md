# First Homework for the Programming Paradigms course

## Supermarket 
#### Această temă implementează în Racket fluxul clienților la casele dintr-un supermarket. Fiecare casă are un timp de procesare al celor aflați la coadă, un index unic, un exit time (timpul până la ieșirea primului client) și are stocate numele tuturor persoanelor care așteaptă la casa respectivă. Persoanele sunt distribuite la casele cu timp de procesare minim. Casele pot fi de două tipuri: fast-counters (case pentru maxim ITEMS produse) și slow-counters (case fără restricții). Casele pot avea întârzieri (delay). La nevoie, se pot adăuga noi case. O coadă de persoane este reprezentată printr-o structură de tip "queue". Există 4 tipuri de cereri care trebuie executate. În funcție de numărul de minute trecute de la ultima cerere, starea caselor se actualizează periodic corespunzător. Coada este implementată ca o colecție de două stive. Stiva left este reprezentată ca un flux. 
