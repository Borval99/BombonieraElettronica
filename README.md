# BombonieraElettronica

## Descrizione

BombonieraElettronica è una bomboniera realizzata in occasione della tesi di Laurea Magistrale in Ingegneria Elettronica.

Il dispositivo è basato su un circuito stampato (PCB) che integra una semplice logica elettronica per la generazione di un effetto luminoso.

---

## Funzionamento

La bomboniera è dotata di un **interruttore touch**, integrato nel cappello di laurea, che consente di attivare e disattivare il circuito.

Il sistema di illuminazione è realizzato tramite un **multivibratore astabile a BJT**, che genera un segnale oscillante utilizzato per pilotare 5 Led gialli.

Il risultato è un gioco di luci intermittente.

L’alimentazione è fornita da una **batteria CR2032**, rendendo il dispositivo compatto e autonomo. La durata da spento è stimata di circa 2 Anni.

---

## Immagini

<div>
  <img src="Immagini/Front.jpg" height="250">
  <img src="Immagini/Back.jpg" height="250">
  <img src="Immagini/Light.jpg" height="250">
</div>

---

## Struttura della repository

### /Bomboniera_Tesi

Contiene il progetto elettronico completo realizzato in KiCad:

* schema elettrico
* layout del PCB

---

### /LTspice

Contiene le simulazioni dei circuiti sviluppati:

* modelli del multivibratore astabile
* analisi del comportamento del circuito

---

## Note

Il progetto ha finalità celebrative e dimostrative, unendo elementi simbolici della laurea con una semplice implementazione elettronica.
