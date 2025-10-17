# Diagramma di flusso per calcolo MCD e mcm

flowchart TB
  A["Scomposizione in fattori primi di ogni numero"]
  A --> B["MCD<br/><i>Moltiplica i fattori comuni.<br/>Prendi l’esponente più piccolo.</i>"]
  A --> C["mcm<br/><i>Moltiplica fattori comuni e non comuni.<br/>Tra gli uguali, prendi l’esponente maggiore.</i>"]
  B --> D(("Valido per due o più numeri"))
  C --> D
