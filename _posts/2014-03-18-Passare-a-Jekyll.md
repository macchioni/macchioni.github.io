---
author: leibniz
comments: true
date: 2014-03-18
layout: post
comments: True
title: Perché passare a Jekyll (versione lunga)
categories:
- blog
tags:
- wordpress
- jekyll
- github
---


Avevo promesso di spiegare in maniera più esaustiva il passaggio da [Wordpress](https://wordpress.org) a [Jekyll](http://jekyllrb.com/). Cioè dal cms più completo in circolazione a quello più essenziale. Naturalmente è una scelta che forse andrà bene per me e potrebbe essere sbagliatissima per voi, ma è la risposta lato software/design a una certa sofferenza della classica struttura dei blog. Una forma diversa che segue l'evoluzione dell'internet, la diffusione del mobile e la necessità di layout più liquidi. In termini meno noiosi (spero), lo racconto qui sotto. 

###Il designer miope ci vede benissimo   
Circa un anno e mezzo fa, non ricordo più come ma potrebbe essere colpa di [Eio](https://friendfeed.com/eio/0d27e21f/web-design-manifesto-2012-jeffrey-zeldman), mi imbatto in 
[questo post di Jeffrey Zeldman](http://www.zeldman.com/2012/05/18/web-design-manifesto-2012/) scritto in un corpo enorme. 

> I love seeing my words this big. It encourages me to write better and more often.

Scrivere in un carattere grande mi invoglia a farlo meglio e più spesso, dice. Ma vale anche per la lettura: [Readability](https://www.readability.com/), [Instapaper](https://www.instapaper.com/) e persino il "reader mode" di Safari su iOS7 hanno dimostrato che i testi sul web sono scritti troppo piccoli. Vanno reimpaginati per facilitarne la lettura. Su schermi di quattro pollici come sui tablet o sui desktop. La [riforma grafica](http://www.nytimes.com/redesign/) del New York Times nel 2014 va esattamente in questa direzione. I blog e i siti più attenti stanno già seguendo. I nuovi temi di Wordpress ormai seguono i dettami del [design responsivo](https://it.wikipedia.org/wiki/Responsive_Web_Design). Ma per cambiare davvero, qui ho deciso di stare fermo. O meglio di essere statico.

###Blog like a hacker   
Una volta deciso di riportare al centro il testo e limitare i bling-bling, prima o poi guardi Wordpress e finisci per chiederti: ma a me serve davvero questo [enorme pannello di controllo](http://en.support.wordpress.com/dashboard/)? Se vuoi linkare qualcosa prima degli altri, taggarlo bene, seguire le statistiche, collegare tutto ai social, scrivere in mobilità, fare backup, seguire le regole SEO, Worpress fa tutto più che bene. Vuoi una soluzione più agile? C'è Tumblr. Però non ho scelto nemmeno quello. Il cambio di paradigma vero è un salto nel passato: un blog statico. Ovvero:

- un post = un file
- velocità di caricamento
- praticamente solo codice

È una scelta per post più lunghi, pensati. Non per il modello "rassegna stampa" che una volta poteva andare bene, ma che ora è superato in velocità dai social. Fate conto che sia l'equivalente di quella che è in fotografia la differenza tra un'ottica fissa e un teleobiettivo: un equipaggiamento che ti costringe a trovare il tuo punto di vista, invece di permetterti potenzialmente tutto e - così facendo - complicare le cose. Insomma, il [blogging like a hacker](http://tom.preston-werner.com/2008/11/17/blogging-like-a-hacker.html) pensiero.

La scelta è caduta su [Jekyll](http://jekyllrb.com/), un sistema che ho provato sporadicamente per alcuni mesi abbinandolo all'hosting di [Github](https://github.com) e che aveva un'unica grande pecca: i temi. Almeno finché [Mark Otto](https://twitter.com/mdo) non ha messo a disposizione [Poole](https://github.com/poole/poole).

> _The Strange Case of Dr. Jeykll and Mr. Hyde_ tells the story of a lawyer investigating the connection of two persons, Dr. Henry Jekyll and Mr. Edward Hyde. Chief among the novel's supporting cast is a man by the name of Mr. Poole, Dr. Jekyll's loyal butler. [Poole](https://github.com/poole/poole) is the butler for [Jekyll](http://jekyllrb.com/), the static site generator.

Quello che vedete qui è la variante [Hyde](http://hyde.getpoole.com/), che poi  è la traduzione in jekyllesco di vari temi di [Medium](https://medium.com/) e di [Svbtle](https://svbtle.com/magazine). Niente di male perché piacciono moltissimo entrambi.


###Scrivere è programmare   
Per usare [Jekyll](http://jekyllrb.com/) basta avere qualcosa da scrivere. Ma, al contrario dei vari editor [WYSIWYG
](https://it.wikipedia.org/wiki/WYSIWYG), ogni post è una pagina di "codice", scritta in [Markdown](http://daringfireball.net/projects/markdown/), ovvero il linguaggio di quel partigiano Apple oltre ogni limite che si chiama [John Gruber](http://daringfireball.net/).

> Markdown is a text-to-HTML conversion tool for web writers. Markdown allows you to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML).

Tradotto: Markdown, all'inizio non sembra, ma alla lunga è puro genio. Metà dei problemi delle redazioni del mondo sparirebbero in un istante se i giornalisti abbandonassero i vari word processor millefunzioni e scrivessero in Markdown, magari appoggiandosi a editor essenziali come [Byword](http://bywordapp.com/), [nvALT](http://brettterpstra.com/projects/nvalt/) o software ancora più basic come [Ommwriter](http://www.ommwriter.com/). Markdown è così semplice che permette di formattare usando pochi simboli davanti alle parole: asterischi, underscore, trattini, cancelletti, segno maggiore/minore e parentesi. Ed è talmente veloce che, quando Bloom ha creato l'app diario più popolare su iOS, cioè [DayOne](http://dayoneapp.com/), l'ha resa compatibile con Markdown. Mica per caso.

Ecco, questo è grosso modo il motivo per cui questo blog è così. Ci sono cose da migliorare e funzioni da attivare (per lo più seguendo [questo tutorial](http://joshualande.com/2014/02/03/jekyll-github-pages-poole/) di Joshua Lande). Più i soliti refusi. E ora:

`git commit -a`

{% include twitter_plug.html %}
