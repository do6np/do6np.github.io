---
title: 'Apple Carplay und Co. für Volvo C70'
date: 2024-02-29 18:00:08
excerpt: Nachrüstung von Apple Carplay bzw. Android Auto und DAB+ für Volvo C70 2006 2007 2008 2009 2010 2011 2012 2013 und andere Fahrzeuge.
---

"Man kann ein Auto nicht wie ein menschliches Wesen behandeln. Ein Auto braucht Liebe." ([Walter Röhrl](https://de.wikipedia.org/wiki/Walter_R%C3%B6hrl))

## Alter Schwede!

Du hast Dich auch schon gefragt, wie Du Deinen Volvo C70 mit Apple Carplay oder DAB+ ausstatten kannst? Dann bist Du wohl über eine Suchmaschine auf diese Seite gestoßen, denn ansonsten interessiert das vermutlich keine Sau!

Du hast einen anderen Schweden, z.B. einen V40 aus der gleichen Epoche? Dann ist manches, das ich hier zusammengetragen habe, vfür Dich vermutlich trotzdem interessant, nur die Links stimmen dann teilweise wohl nicht 1:1.

Ach so - bevor mich jemand an den Marterpfahl stellt: Das hier sind meine persönlichen Recherchen. Ich bin absoluter Laie und kann nur das wiedergeben, was ich glaube verstanden zu haben. Sämtliche Beschwerden gerne an Volvo, den Freundlichen, euren Nachbarn oder wen ihr sonst damit nerven möchtet, danke!

## Generationenkonflikt

Für die erste Generation des C70 ab 1998 ist die Sache ziemlich einfach, da hier nahezu beliebige Doppel-DIN-Radios verbaut werden können, wie man sie auf dem Zubehörmarkt von billig bis sehr gut in Hülle und Fülle finden kann. Wer sein Radio nicht tauschen möchte, kann vielleicht auch mit einem speziellen Bluetooth-Adapter glücklich werden[^1]. Weiter werde ich auf dieses Modell nicht eingehen.

Beim C70 Typ M (ab 2005 bzw. 2006) nimmt das Radio hingegen eine zentrale Rolle, z.B. zur Anzeige der Klimasteuerung, ein, so dass ein Austausch nicht mehr so leicht fällt, selbst wenn es von der Größe her passen würde. Wie schließe ich also mein Smartphone an und wie kann ich die Installation irgendwie auf das nächste Level heben? Vorweg: Die Sache ist leider nicht ganz einfach und kaum ohne Nachteile zu realisieren. Ich liste daher hier einmal kurz die Ergebnisse meiner Recherchen auf. Vielleicht hilft es ja jemandem...

## Wieso, weshalb, warum

Wer noch ganz am Anfang steht und sich erst einmal grundsäztlich darüber informieren möchte, was technisch möglich ist, sollte sich den Artikel von TechStage[^2] durchlesen. Dort kommen zwar keine Schweden vor, die prinzipiellen Möglichkeiten und Einschränkungen werden aber schon einmal ganz gut zusammengefasst.

Anschließend werden wir uns mit den Fragen beschäftigen, wie ist die Technik im C70 II aufgebaut und welche Anschlussmöglichkeiten gibt es? Was für Dich dann die richtige Lösung ist, musst Du selbst entscheiden.

### Sounds like Volvo

Zu Beginn sollten wir uns einmal die Frage stellen: Welches Soundsystem ist in unserem C70 eigentlich verbaut? Um dies zweifelsfrei herauszufinden, müssen wir lediglich unser Radio einschalten. Zeigt das Radio beim Einschalten nur ein Fahrzeugsymbol an und gibt sich nicht namentlich zu erkennen, schämt es sich offenbar ein wenig, weil es sich um das Standardsystem Performance handelt. Wir haben also eher die Holzklasse verbaut. Anderenfalls wird es sich beim Einschalten mit seinem Produktnamen (High Performance Sound oder Premium Sound) zu erkennen geben.

### Auxilium

Die größeren Soundsysteme im C70 verfügen zumeist über eine Aux-Buchse[^3]. Diese ist dafür gedacht, beliebige Tonquellen an das Soundsystem anzuschließen. Die Buchse (oder der Eingang) befindet sich, soweit ich recherchieren konnte, entweder am hinteren Ende des Fachs in der Mittelkonsole unter der Abdeckung oder hinter dem Wasserfall (das ist die schwebende Radiokonsole).

#### Mit Draht

Wer Aux hat, der hat's gut, denn dort lässt sich im einfachsten Fall ein Kabel anschließen, um den Sound des Smartphones auf die Anlage zu übertragen. Für das iPhone gibt es entsprechende Adapterkabel[^4], bei den Android-Geräten reicht ein einfachstes Kabel mit 3,5-mm-Klinkensteckern an beiden Enden.

#### Ohne Draht

Wem eine Klangübertragung reicht, wer es jedoch lieber kabellos hätte, für den bieten eBay und Co. eine riesige Auswahl von Bluetooth-Empfängern. Prinzipiell kann man hier nicht so viel falsch machen, allerdings ist ein niedriger Preis zumeist nicht unbedingt ein Zeichen für gute Klangqualität. Auch wird bei Billigprodukten über häufige Verbindungsabbrüche berichtet oder der Adapter vergisst immer wieder die Paarung. Wichtig ist in jedem Fall, dass der Empfänger per USB betrieben werden kann, da sich dann mit Hilfe eines kleinen Steckers die benötigten 5 V Spannung einfach aus der Zigarettenanzünderbuchse in der Mittelkonsole gewinnen lassen. Adapter "Zigarettenanzünder auf USB-Buchse" gibt es im Netz wirklich wie Katzenbilder am Meer.

Bei der Klangübertragung sollte man sich bei Bluetooth etwas Mühe geben. Bluetooth 5.x darf es mittlerweile schon sein, bei den Kompressionsverfahren kommt es auf das Endgerät an. Für Androiden sollte man ein Modul wählen, dass den Codec aptX[^5][^6] unterstützt. Für Äpfel ist dies uninteressant, da es diesen Codec hier nicht gibt. Für Apple-User wäre daher einzig der AAC-Codec von Interesse. Was es mit diesen Codecs auf sich hat, wird z.B. hier[^7] erklärt. Leider habe ich bislang keine vernünftig wirkende Lösung für AAC im Auto gefunden. Falls hier jemand eine Idee hat, freue ich mich über einen Hinweis! Ansonsten kann ich nur einen aus meiner Sicht ordentlichen Kompromiss anbieten[^8]. Richtig gut wären die Receiver, die es für den Home-Hifi-Bereich gibt, aber ich war bislang zu faul, mich um die Wandlung von 12 V auf irgendwas spezielles mit Hohlstecker zu bemühen. Auch hier wären gute Tipps gefragt!

### Take the MOST of it

MOST hat in diesem Fall nichts mit Äpfeln zu tun, sondern steht für "Media Oriented Systems Transport"[^9]. Es handelt sich dabei, ganz grob gesagt, um einen Standard, mit Hilfe dessen Fahrzeughersteller Multimediadaten in ihren Fahrzeugen übertragen. So können im Auto z.B. über diesen Lichtwellenleiterstandard Radio, Endstufe oder CD-Wechsler verbunden werden. MOST ist daher neben Aux der zweite, profewssionellere Weg, um die eigenen Inhalte in das Fahrzeugsystem einzuspeisen. Dies zunächst nur als Erklärung, wie einige der im Folgenden vorgestellten Lösungen mit dem Soundsystem verbunden werden.

### Wechselwirkungen

Für spätere Überlegungen könnte es wichtig sein zu wissen, ob das Radio über einen CD-Einschub (Single CD) verfügt oder ein 6-fach-CD-Wechsler verbaut ist. Zu Systemen mit Navigationsfunktion kann ich leider mangels Erfahrung nichts beitragen, würde aber vermuten, dass das im Folgenden Geschriebene dort ebenfalls Gültigkeit besitzt.

## Nachrüstlösungen

Nachdem wir die technischen Basics besprochen haben, kommen wir jetzt mal zu den möglichen Lösungen mit etwas Aufwand. Diejenigen mit weniger Aufwand folgen weiter unten.

### Bluepower

Unter dem Namen "VOLVO C30/S40/V50/C70 HEADUNIT ANDROID 12" bietet die schwedesche Firma BP2 AUTOMOTIVE offenbar bereits seit einigen Jahren einen Ersatz für das originale Entertainment-System an[^10]. Schwedescher Ersatz für ein Schwedenauto? Klingt irgendwie erst mal gut. Auch die Webseite macht soweit einen guten Eindruck: Neben dem korrekten Fahrzeugmodell kann auch die jeweilige Hifi-Ausstattungsvariante gewählt werden. Der Aux-Anschluss findet Berücksichtigung und DAB+ und Carplay können auf Wunsch gleich mitbestellt werden.

Weniger vertrauenserweckend ist da schon der zum Zeitpunkt der Erstellung dieses Beitrags zu lesende Hinweis: "Version 2024, only available for pre-order." und "Delivery time 12-16 weeks." Vor einigen Wochen sollte man sich allerdings noch "upbucklen", so dass zumindest eine Entwicklung sichtbar ist. Mit der Lieferung scheint das aber ohnehin so eine Sache zu sein. Häufig liest man in den Foren darüber, dass die Lieferung, wenn sie denn mal kommt, unvollständig sei und mehrfach Teile nachgefordert hätten werden müssen. Dies hätte dann wiederum mehrere Wochen bis Monate gedauert. Kundenfreundlicher Support scheint im Land des Kneckebrots bei diesem Lieferanten insgesamt eher kleingeschrieben zu werden, kurze Antworten per Mail sind wohl das Maximum dessen, was der geneigte Kunde erwarten darf. Ist der Service nicht wie gewünscht, sollte zumindest die Anleitung hoher Qualität sein; leider scheint aber auch das nicht zuzutreffen. In einigen Berichten ist zumindest von veralteten Anleitungen zu lesen, die nicht mehr dem tatsächlichen Stand entsprächen.

Fairerweise muss man allerdings auch anmerken, dass sich viele der zu findenden Berichte auf ältere Versionen dieses oder ähnlicher Produkte für andere Volvo-Modelle beziehen, die teilweise noch mit Windows CE oder noch viel älteren Android-Versionen ausgestattet waren. Bei denjenigen, bei denen das System erfolgreich installiert werden konnte, scheint die Leistung durchwachsen zu sein. Prinzipiell scheint es wohl zu funktionieren - am Ende des Tages haben wir es ja auch nur mit einem Android-Tablet mit etwas Schnickschnack zu tun. Schade eigentlich, dass diese Lösung trotz guter Vorbereitung (passender Bildschirm etc.) wohl auf der Software-Seite nicht 100% zu Ende gedacht zu sein scheint.

Ich habe diese Lösung für mich leider ausgeschlossen, auch wenn sie eigentlich wohl ideal gewesen wäre. Ich habe einfach aktuell nicht die Zeit, mich mit einer nicht von Anfang an stabilen Lösung zu beschäftigen. Wer ein wenig Risiko gehen mag und technisch beschlagen genug ist, um auch mal einen Lötkolben in die Hand zu nehmen, kann am Ende vielleicht Spaß damit haben? Wer weiß.

### TAFFIO

Mit 750 Euro dürfte die Lösung des Real Media Shop aus Neuss[^11] die teuerste sein, dafür kommt sie direkt aus Deutschland und sieht auf den ersten Blick auch nicht so schlecht aus. Zwar haben wir es mit dem ordentlich veralteten Android 10 zu tun, aber mit Carplay, FSE und auf Wunsch auch DAB+ scheint erst einmal alles an Bord zu sein, was wir uns so wünschen könnten.

Aber auch bei diesem Exemplar (gefunden nur für andere Volvo-Modelle) fällt die Bilanz in den Foren leider durchwachsen aus. Von "guter Kundenservice" bis "China-Schrott" reicht hier die Bandbreite. Laut einem Foreneintrag bestreitet der Shop, dass das Gerät in China gefertigt wird und vielleicht sogar gewisse Änlichkeiten mit denjenigen Geräten aufweist, die sich bei Ali, Amazon und Co. finden lassen. Dazu passt natürlich auch der Hinweis auf der Webseite: "Unverbindliche Preisempfehlung des Herstellers: 900,00 €". Also, was sagt TAFFIO denn dazu? Nun ja, dafür müssten wir diesen Hersteller erst einmal finden, aber eine Webseite scheint er nicht zu haben, zumindest konnte ich diese nicht finden. Das macht die Sache jetzt auf den ersten Blick nicht unbedingt direkt glaubwürdiger... Auch die im Netz zu findenden Youtube-Videos[^12] stammen vom Real Media Shop, der Hersteller hat sich also offenbar gut versteckt, um es vorsichtig zu formulieren.

### Navtool

Unter dem etwas sperrigen Produktnamen "NAVTOOL 5.0-APPLE-CARPLAY" vermarktet dieses amerikanische Unternehmen eine Box, die diverse Video- und Audioeingänge bereitstellt[^13]. Zum Einsatz kommt hier MOST, wie oben beschrieben. Neben theoretisch vier Kameras (oder anderen Bildquellen wie DVD) kann hierüber auch Carplay realisiert werden, indem das iPhone ebenfalls (mittels entsprechendem Kabel von Lightning auf HDMI) als Bildquelle angeschlossen wird. Die Übertragung des Audiosignals erfolgt mittels des Aux-Eingangs des C70. Das System kann mit und ohne installiertem Navigationssystem im C70 eingesetzt werden.

Das Angebot macht einen strukturierten Eindruck, die benötigten Kabel werden als Paket angeboten und die Anleitung auf der Website wirkt stimmig. Erfahrungen mit unserem Schweden konnte ich nicht finden; allerdings gab es eine positive Besprechung in einem Saab-Forum und das ist ja zumindest sowas wie die erweiterte Verwandtschaft (jaja, ich höre schon euren Widerspruch). Vorteil gegenüber anderen Lösungen scheint zu sein, dass der Einbau relativ plug 'n play ist und die einzige Herausforderung sein dürfte, die benötigten 12 V Stromversorgung zum Gerät zu bekommen. Dafür erhält man im besten Fall auch ein Bild, so dass man den Apfel nicht nur zum Musikhören, sondern insbesondere auch zur Navigation verwenden kann. Mit Hilfe der ebenfalls von diesem, aber auch anderen Lieferanten angebotenen Dongles sollte es auf Wunsch ebenfalls möglich sein, kabelloses Carplay zu realisieren. Für den Fall, dass das Fahrzeug nämlich bereits über Carplay verfügt, dieses jedoch nur mittels Lightning-Kabel realisiert wurde, werden diverse Bluetooth-Dongle angeboten. Wenn diese bei VW, MB und Co. funktionieren, sollte das eigentlich auch im C70 klappen. Erfahrung ist hier allerdings Fehlanzeige.

Hinderungsgrund zum Kauf könnte der nicht gerade kleine Kaufpreis verbunden mit der Tatsache sein, dass es keinen europäischen Importeur zu geben scheint und somit im Fall von Reklamationen oder dem Wunsch nach Produktrückgabe ein gewisses Risiko besteht. Zudem muss die Ware natürlich verzollt werden, so dass die anfallende Umsatzsteuer zu berücksichtigen ist - was die Sache jetzt nicht gerade billiger macht.

### GROM

Wieder mal ein amerikanischer Hersteller, auch wieder mit MOST, aber diesmal mit anderem Konzept. Der GROM-Adapter[^14], hier in der Single-CD-Version, wird anstelle des CD-Laufwerks oder 6-Fach-CD-Wechslers (Achtung, eigener Artikel) an die Anlage des C70 angeschlossen. Dadurch erhält man einerseits einen USB-Anschluss, über den man das iPhone anschließen und laden könnte. Spannender wird die Sache aus meiner Sicht, wenn man andererseits das iPhone per Bluetooth mittels des A2DP-Protokolls verbindet, weil man hierüber eine einigermaßen brauchbare Audioübertragung sicherstellen kann. Spotify, Deezer, Apple Music oder was auch immer ihr bevorzugt wäre okay, IDAGIO wäre wohl eher zum Weglaufen. Auch eine Freisprecheinrichtung ließe sich damit realisieren (siehe auch Zubehör). Verzichten muss man hingegen auf echtes Carplay - hier bliebe nur die Montage des iPhones mittels einer Halterung, z.B. an den Lüftungsschlitzen, und die Akustik käme dann über die Anlage. Dafür gibt es einen Aux-Anschluss für weitere Projekte gratis. Interessant dürfte diese Variante insbesondere für diejenigen sein, die Musik auf ihrem iPhone gespeichert haben, dann gibt es sogar ein wenig Steuerung über die Lenkradfernbedienung.

In diversen Volvo-Foren wird positiv über das Funktionieren dieser Lösung berichtet. Ein Schnapper ist allerdings auch sie nicht, beim Import aus den USA bleibt zudem der Zoll und alles andere, was ich zum Navtool bereits geschrieben habe. Es scheint auch mindestens eine Bezugsquelle in Deutschland[^15] zu geben, aber dazu kann ich überhaupt keine Auskünfte geben.

## Plug 'n Play

Wer basteln schon im Kindergarten doof fand, sucht vermutlich eher etwas zum "einfachen Anschließen". Auch dazu gäbe es Lösungen, deren Installation freilich Geschmackssache ist.

### Multimedia

Neben Navis zum Nachrüsten, die man in den vergangenen Jahren gefühlt deutlich seltener sieht als früher, gibt es etwas ähnliches auch für Wireless und Wired Apple CarPlay sowie Android Auto mit und ohne Schnur. Hierbei wird ein Touchscreen oben auf das Armaturenbrett gesezt oder an die Windschutzscheibe geklemmt (was ich nicht empfehlen würde) und kann dann von dort aus die Infos des Smartphones anzeigen. Teilweise haben diese Kisten sogar einen internen Lautsprecher, diese taugen aber einzig zur Wiedergabe von Navigationshinweisen und natürlich nicht für Musik. Deshalb wäre es angezeigt, den Bildschirm entweder per Klinkenkabel mit der Aux-Buchse des Fahrzeugs zu verbinden oder dafür wiederum einen Bluetooth-Empfänger zu nutzen. In letzterem Fall müsste man darauf achten, dass das Gerät Dual-Bluetooth unterstützt, was teilweise der Fall ist.

Typische Vertreter dieser Gattung sind die CPM-Serie von Ampire[^16] oder die zahlreichen Geräte von Carpuride[^17]. Auch Dashcam und Rückfahrkamera werden teilweise gleich mitgelifert, ebenso Mikrofone fürs freie Reden während der Fahrt. Das Netz ist voll von China-Krachern in diesem Bereich; ob es hier wirklich qualitativ hochwertige Vertreter gibt, wäre zu prüfen.

### DAB

Keine Angst, kein Pils. Wenn es nur ums Digitalradio geht, könnte das DAB+A von Dension[^18] noch eine Alternative sein. Es kann entweder über den Aux in der Mittelkonsole angeschlossen oder als FM-Sender durch das Radio empfangen werden, gesteuert wird entweder über eine App auf dem Apfel oder eine Fernbedienung mit Stationstasten. Kaufen kann man das Ganze zur Abwechselung auch mal bei bekannten deutschen Online-Shops. Könnte sich also tatsächlich mal um was Seriöses handeln.

Je nach Örtlichkeit und Umgebung sollte man sich allerdings Gedanken darüber machen, wie gut der DAB+-Empfang ist und welcher Aufwand ggf. für eine zusätzliche Antenne getrieben werden muss. Aber auch dafür gibt es manigfaltige Lösungen, hier ist die Suchmaschine des Vertrauens gefragt.

Übrigens hat Grom theoretisch auch eine DAB+-Ergänzung, leider aber nicht für unser Fahrzeug. Hätte ja klappen können...

Ganz freaky könnte man vielleicht auch eine DAB+U-Lösung von Dension mit einem Grom-USB-Adapter koppeln? Aber das ist dann wieder eine andere Geschichte, lassen wir das.

## Quellen

[^1]: [A2DP Bluetooth Interface Volvo 8Pin DIN CD-Wechsler von ACV](https://shop.acvgmbh.de/de/a2dp-bluetooth-interface-volvo-8pin-din-cd-wechsler--4909.html) 
[^2]: [Auto nachrüsten: Apple Carplay, Android Auto, DAB+ & Co. für Gebrauchtwagen. In: TechStage.de](https://www.techstage.de/ratgeber/auto-nachruesten-apple-carplay-android-auto-dab-und-co-fuer-gebrauchtwagen/lz02blh)
[^3]: [Beschreibung AUX-Eingang. In: Wikipedia](https://de.wikipedia.org/wiki/AUX-Eingang)
[^4]: [Lightning auf 3,5 mm Audiokabel (1,2 m) – Schwarz - Apple (DE)](https://www.apple.com/de/shop/product/MR2C2ZM/A/lightning-auf-35-mm-audiokabel-12-m-schwarz)
[^5]: [Bescrheibung aptX. In: Wikipedia](https://de.wikipedia.org/wiki/AptX)
[^6]: [APTX Bluetooth Standard. In: Bonsaimachos - HiFi - Stereo - Audio](https://www.bonsaimachos.de/aptx-bluetooth-standard-cd-flac-wav-drahtlos.html)
[^7]: [Bluetooth Codecs: aptX, AAC, SBC und Co. erklärt. In: HIFI.DE](https://hifi.de/ratgeber/bluetooth-sbc-aac-aptx-40695)
[^8]: [Universeller A2DP Bluetooth Receiver von Ampire Electronics](https://www.ampire.de/Bluetooth-Receiver.htm?SessionId=&a=catalog&p=3459)
[^9]: [MOST-Bus. In: Wikipedia](https://de.wikipedia.org/wiki/MOST-Bus)
[^10]: [Bluepower BLP-990A](https://www.bluepower.se/en/product/audio-video/car-stereo/custom-players/volvo-c30s40v50c70-headunit-android-71.html)
[^11]: [TAFFIO TJ-S40 für Volvo S40 C30 C70 V50 (04-13) 10.25" Touchscreen Android Navi GPS](https://www.realmediashop.de/Fuer-Volvo-S40-C30-C70-V50-04-13-1025-Touchscreen-Android-Navi-GPS-Carplay)
[^12]: [Real Media Shop bei Youtube](https://www.youtube.com/@realmediashop)
[^13]: [VOLVO C70 2006 2007 ... 2013 NAVIGATION VIDEO INTERFACE with BUILT-IN HD SMARTPHONE MIRRORING via HDMI](https://www.navtool.com/volvo-c70-2006-2013-apple-carplay.aspx)
[^14]: [GROM-MST4 USB car adapter kit](https://gromaudio.com/store/most_adapters/volvo-s40-c30-c70-v50-single-cd-06-12--android-iphone-usb-bluetooth-adapter-kit-optofiber.html)
[^15]: [Grom MOST Multimedia MST4-VOLS6 iPod Android AUX Kit - Volvo](https://maxxcount.de/grom-mst4-vols6o4-android-usb-iphone-ipod-interface-aux-bluetooth-optional-fuer-volvo-s40-s60-v50-2006-2012-xc90-2007-2013-mit-6-fach-cd-wechsler.html)
[^16]: [Nachrüstung von Apple CarPlay und für Android Auto - Ampire Electronics](https://www.ampire.de/smartphone.htm?SessionId=&a=catalog&p=59734), [Carplay-Monitore Ampire CPM-Serie](https://www.ampire.de/CarplayMonitor.htm?SessionId=&a=catalog&p=2964)
[^17]: [Auto-Stereoanlagen von Carpuride](https://carpuride.com/de/collections/automotive-smart-stereo)
[^18]: [Dension DAB+A](https://www.dension.com/product/car-handsfree-and-multimedia/daba/)
