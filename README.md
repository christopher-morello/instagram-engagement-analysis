# instagram-engagement-analysis
Analisi dei dati di Instagram utilizzando Python. 
Include visualizzazioni, analisi delle metriche di engagement e raccomandazioni per ottimizzare la strategia di pubblicazione.

Il progetto esamina dati dell'intero anno 2024 per fornire insights actionable sulla strategia di content marketing.

## Obiettivi

- Identificare i formati di contenuto più performanti
- Analizzare l'impatto della durata dei Reel sull'engagement
- Determinare i migliori orari e giorni di pubblicazione
- Studiare le correlazioni tra metriche di engagement e reach
- Fornire raccomandazioni data-driven per l'ottimizzazione della strategia

## Requisiti Tecnici

Python: 3.10.18
Librerie principali:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy`
- `statsmodels`

## Fonte Dati
I dati sono stati estratti da Meta Business Suite e successivamente anonimizzati per garantire la privacy. Il dataset include metriche complete per tutto l'anno 2024.

## Metriche Analizzate

- **Engagement**: like, commenti, condivisioni, salvataggi
- **Reach**: copertura e impression
- **Engagement Rate**: Calcolato come rapporto tra interazioni totali e reach
- **Performance temporali**: Analisi per giorni della settimana e orari
- **Formato contenuti**: Reel, caroselli, post singoli
- **Durata contenuti**: analisi specifica per i reel

## Visualizzazioni Incluse

- Grafici temporali per trend di engagement
- Heatmap per performance per giorno/ora
- Grafici a barre per confronto tra formati
- Analisi correlazionale tra metriche

## Visualizzazioni Dashboard su Tableau
<div class='tableauPlaceholder' id='viz1755353722191' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;An&#47;AnalisiInstagram&#47;Formatodipubblicazione&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='AnalisiInstagram&#47;Formatodipubblicazione' /><param name='tabs' value='yes' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;An&#47;AnalisiInstagram&#47;Formatodipubblicazione&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='it-IT' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1755353722191');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='850px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='850px';} else { vizElement.style.width='100%';vizElement.style.height='1300px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

## Principali Insight
1. Durata dei reel
- I reel con durata superiore ai 120 secondi sono il formato preferito dagli utenti. La durata media attuale è di 58 secondi, ma contenuti più lunghi mostrano performance superiori.
2. Timing ottimale
- I contenuti pubblicati la sera, specialmente nel weekend, ottengono i migliori risultati. Il martedì registra il più basso tasso di coinvolgimento.
3. Formato contenuti
- I caroselli riducono l'engagement complessivo. Nei mesi dove questo formato è predominante si osserva un calo significativo del coinvolgimento.
4. Importanza dei salvataggi
- I salvataggi mostrano la correlazione più forte con la copertura (0.73), indicando che Instagram privilegia i contenuti salvati dagli utenti. Rappresentano inoltre la metrica di interazione più alta.
5. Engagement vs copertura
- La correlazione tra copertura ed engagement rate è praticamente inesistente (-0.08), dimostrando che maggiore visibilità non garantisce automaticamente un tasso di interazione più alto.
## Raccomandazioni

- Aumentare la durata dei Reel: Sperimentare contenuti oltre i 2 minuti, particolarmente adatti per contenuti educativi
- Ridurre l'uso dei caroselli: Limitare questo formato dato il suo impatto negativo sull'engagement
Ottimizzare il timing: Concentrare i contenuti migliori nelle serate del weekend

**Strategiche**

- Focus sui contenuti salvabili: creare guide, tutorial, liste e contenuti educativi che stimolino i salvataggi
- Prioritizzare l'engagement sulla reach: sviluppare contenuti che stimolino commenti e condivisioni attraverso domande aperte e call-to-action mirate

## Contributi
I contributi sono benvenuti. Per modifiche sostanziali, aprire prima una issue per discutere i cambiamenti proposti.
## Licenza
Questo progetto è distribuito sotto licenza MIT. Vedere il file LICENSE per maggiori dettagli.
## Autore
Christopher Morello

>_Analisi basata su dati Instagram del 2024, elaborati attraverso tecniche di data science per fornire insights actionable sulla strategia di content marketing._
