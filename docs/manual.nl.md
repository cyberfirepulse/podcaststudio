# Podcast Studio — handleiding v1.48.1

## 01. Snel een eerste podcast maken
Begin op het tabblad Tekst. Plak een kort verhaal of importeer een tekstbestand. Ga naar Stemmen en kies de spraakengine. Piper gebruikt lokale stemmodellen, Edge werkt online en Mijn stem gebruikt je eigen lokale stemomgeving.

Kies bij Audio en uitvoer een MP3-bestandsnaam. Muziek, sfeergeluid en een hoes zijn optioneel. Begin met een korte tekst en zonder achtergrondgeluid: zo kun je uitspraak en tempo beoordelen. Klik Audiopreview voor een voorbeeld. Klik Genereer MP3 voor de volledige aflevering.

Tijdens het maken blijven voortgang en bediening bovenaan zichtbaar. Wacht op de gereedmelding en controleer het uitvoerbestand. Bewaar je project via Project > Project opslaan. Een MP3 bevat het eindgeluid; een project bewaart de tekst en instellingen waarmee je verder kunt werken.

## 02. Projecten opslaan, openen en herstellen
Gebruik Ctrl+S om een project op te slaan en Ctrl+O om er een te openen. Een project bevat tekst, instellingen en verwijzingen naar gekozen bestanden. Alleen een tekstbestand bewaren is daarom niet hetzelfde als een project bewaren.

De toepassing bewaart ook sessie-instellingen automatisch. Gebruik daarnaast bewust een eigen projectbestand voor belangrijke afleveringen. Controleer na het openen of modellen, muziek, hoes en stemopnamen nog op hun oorspronkelijke plaats staan. Verplaats je die bestanden, dan moet je ze opnieuw aanwijzen.

Gebruik Projectpakket voor een verplaatsbare kopie met beschikbare bronbestanden en audiotakes. De afleveringenbibliotheek is handig voor je werkoverzicht; een volledige reservekopie maak je met een projectpakket en een kopie daarvan op een andere schijf.

## 03. Teksteditor en opmaak
De kleine pictogrammen bieden onder meer openen, opslaan, ongedaan maken, knippen, kopiëren, plakken, zoeken, lettergebruik, koppen, lijsten en uitlijning. Houd de muis boven een pictogram voor uitleg. Het menu Tekst biedt extra bewerkingen zoals spaties opschonen en afgebroken regels samenvoegen.

Selecteer eerst het fragment dat je wilt bewerken. Ctrl+Z maakt tekstwijzigingen ongedaan, Ctrl+Y herhaalt ze en Ctrl+F opent zoeken en vervangen. Ctrl+B en Ctrl+I voegen opmaakmarkeringen toe. Opmaak is bedoeld voor de tekststructuur; vet of cursief garandeert geen hoorbare nadruk in de stem.

Controleer Voorleestekst bekijken om te zien wat voor de spraak wordt voorbereid. Maak een preview na grotere wijzigingen. Verwijder niet zomaar alle lege regels: alineagrenzen helpen bij de opbouw en pauzes van het verhaal.

## 04. Tekst scannen, kleuren en tekstwizard
Scan tekst zoekt aandachtspunten zoals lange zinnen, verwijzingen en onjuiste markeringen. De kleuren onderscheiden verteller, citaat, bijbelverwijzing, kop, opmaak, aandachtspunt en markeerfout. Een oranje aandachtspunt is een suggestie om te beoordelen, geen verplichte correctie.

Met Volgend aandachtspunt spring je door de gevonden plaatsen. Tekstkleuren kun je uitschakelen zonder de tekst te veranderen. De tekstwizard helpt bij het voorbereiden van de voorleestekst. Bekijk voorgestelde wijzigingen en gebruik de aanwezige herstelmogelijkheden wanneer het resultaat niet past.

Een scan begrijpt niet automatisch de volledige emotie of bedoeling van je verhaal. Lees de overgang tussen alinea's zelf na en luister naar een preview. Namen, afkortingen, getallen en citaten verdienen vaak extra aandacht. Bewaar vóór grote bewerkingen een projectversie.

## 05. Spraakengine kiezen: Piper, Edge of Mijn stem
Piper werkt offline zodra het programma en de modellen geïnstalleerd zijn. Kies een passend Nederlands of ander taalmodel. Het karakter en de natuurlijkheid hangen sterk af van het gekozen model; dezelfde tekst kan met een andere stem heel anders klinken.

Edge TTS gebruikt een online spraakdienst. Een Edge-stem wordt niet als offline model gedownload. Internet en een werkende Edge TTS-installatie zijn nodig. De toepassing kan hiervoor een andere lokale Python-installatie gebruiken dan waarmee de GUI draait.

Mijn stem gebruikt een afzonderlijke lokale stemomgeving met modellen en een stemvoorbeeld. Dit vraagt meer rekenkracht dan Piper. Een eerdere succesvolle stemopname betekent niet dat de benodigde modellen of runtime op een andere computer ook aanwezig zijn. Vergelijk engines met dezelfde korte tekst en hetzelfde ongeveer gewenste tempo.

## 06. Piper-stemmen kiezen en downloaden
Open Stemmen kiezen / downloaden. Zoek een stem in de catalogus, download de benodigde bestanden en wijs het model aan als hoofdverteller of bijbelstem. Een Piper-model bestaat doorgaans uit een .onnx-bestand met de bijbehorende .onnx.json-configuratie. Houd die bij elkaar.

Controleer het pad naar het Piper-programma als de stem niet start. Het stemmodelpad is iets anders dan het programmapad. Gebruik Installatie controleren voor informatie over de aanwezige onderdelen. Downloaden vereist internet; de spraak kan daarna lokaal werken.

De catalogus is geen garantie dat elke stem even natuurlijk of geschikt voor elke taal is. Beluister een korte test voordat je een lange aflevering maakt. Bewaar gebruikte modellen op een vaste plaats en raadpleeg de informatie/licentie van de betreffende stem wanneer je deze gebruikt of verspreidt.

## 07. Twee stemrollen en bijbelcitaten
De hoofdverteller gebruikt het bovenaan gekozen model. Voor bijbelcitaten kun je een tweede Piper-model en een apart tempo kiezen. Markeer een geselecteerd fragment met de citaatknop of gebruik [bijbel]tekst[/bijbel]. Een groter-dan-teken aan het begin van een regel kan ook een citaat aangeven.

Houd begin- en eindmarkeringen in balans. Gebruik de tekstscan om markeerfouten op te sporen. Bij Edge wordt de gekozen Edge-stem gebruikt met het tempo van de betreffende rol; twee Piper-modellen betekenen niet automatisch twee verschillende Edge-stemmen.

Luister naar de overgang tussen verteller en citaat. Een lager tempo voor een citaat kan helpen, maar een groot tempo- of volumeverschil kan storend zijn. Stemklank gelijkmaken kan nieuwe takes met gelijkmatiger volume maken. Vastgezette fragmenten worden daarbij overgeslagen.

## 08. Tempo, pauzes en natuurlijk vertellen
Bij de roltempo's betekent 1 normaal. Een waarde onder 1 maakt de spraak rustiger; boven 1 sneller. Pas in kleine stappen aan. Te langzaam spreken kan onnatuurlijk en vermoeiend worden. Beoordeel altijd een stukje lopend verhaal in plaats van één losse zin.

Met automatisch natuurlijk vertellen worden samenhangende passages voorbereid en alinea's zoveel mogelijk als een geheel aangeboden. De spraakengine bepaalt een deel van de pauzes binnen de passage; de alineapauze regelt de ruimte tussen grotere delen. Losse korte invoerregels kunnen de samenhang verstoren.

Gebruik de vertel-/overgangencontrole waar beschikbaar om omliggende passages samen te beluisteren en pauzes te beoordelen. Na tekst-, stem- of taalwijzigingen kan een eerder vertelplan ongeldig worden. Een tekstscan kan de structuur verbeteren, maar geeft geen gegarandeerde menselijke intonatie. Kies liever een natuurlijk model dan extreme tempo-instellingen.

## 09. Je eigen stem opnemen en gebruiken
Open Mijn stem opnemen en kies de juiste microfoon. Spreek in een stille, niet-galmende ruimte met je gewone accent, volume en ritme. Begin direct met spreken. De opname stopt na de gekozen duur; je kunt zelf eerder stoppen met de aanwezige bediening.

Beluister de opname, stop het afspelen en neem opnieuw op wanneer nodig. Je kunt ook een bestaand audiobestand laden en een bruikbaar deel uitsnijden. Gebruik de expliciete knop om deze stem toe te passen en de wizard af te ronden. Alleen een opname beluisteren is niet hetzelfde als deze selecteren voor de podcast.

Een helder voorbeeld zonder muziek, echo, andere sprekers of overbelasting helpt. Gebruik de opnamecontrole voor niveau en stilte. Je lokale stemmodel kan uitspraak of accent anders invullen dan jijzelf; de opname en instellingen beïnvloeden dat, maar exacte gelijkenis is niet gegarandeerd.

## 10. Stemklank, hoogte, warmte en opnamecontrole
De stemregelaars bieden tempo en, afhankelijk van de engine, nabewerking zoals toonhoogte, warmte en helderheid. Bij de eigen stem zijn er ook modelinstellingen voor expressie en stemtrouw. Verander één instelling tegelijk en vergelijk hetzelfde tekstfragment. Een opgeslagen stemprofiel helpt om een goede combinatie terug te vinden.

Toonhoogte verandert de klankhoogte; warmte beïnvloedt het lage gebied en helderheid het hoge gebied. Grote wijzigingen kunnen juist kunstmatig klinken. Deze regelaars herstellen geen accent en voegen geen volwaardig menselijk acteerwerk toe.

Publiceren > Stemopname controleren meet duur, gemiddelde sterkte, piek en aandeel stilte. De controle beoordeelt geen ruis, galm of stemgelijkenis. Stemklank gelijkmaken maakt nieuwe audiotakes met gezamenlijke klankcorrectie en spraaknormalisatie. Originelen blijven bewaard. Exporteer daarna de montage opnieuw om de veranderingen in de MP3 te horen.

## 11. Nederlands, Engels en uitspraakwoordenboek
De interfacetaal en spraaktaal zijn verschillende keuzes. Taal / Language verandert de bediening na herstart; je artikel wordt niet vertaald. Kies voor gesproken tekst een engine/model dat de gewenste taal ondersteunt.

Bij de eigen stem kun je Nederlandse en Engelse passages aangeven met [nl]tekst[/nl] en [en]text[/en]. Gebruik dit bijvoorbeeld voor een hele Engelse passage of een Engels citaat. Een enkel Engels woord in Nederlandse tekst kan nog steeds Nederlands klinken, afhankelijk van de engine en context.

Het uitspraakwoordenboek legt gerichte vervangingen vast. Gebruik Opslaan om regels te bewaren en controleer een preview. Vermijd brede regels die onbedoeld delen van andere woorden vervangen. Accentletters horen als normale letters verwerkt te worden; voeg niet voor ieder woord met een accent een regel toe. Controleer bij vreemde tekens eerst het bronbestand en de UTF-8-verwerking.

## 12. Preview, voortgang, pauzeren en stoppen
Audiopreview maakt een kort voorbeeld met de beschikbare preview-instellingen en achtergrondlagen. Bij selectie-/cursorpreview wordt het gekozen tekstdeel gebruikt. Controleer goed welk deel je beluistert voordat je het met een volledige export vergelijkt.

Genereer MP3 maakt de volledige aflevering. De eerste eigen-stemgeneratie kan langer duren door het laden van modellen. Voortgang of een activiteitssignaal geeft aan dat de toepassing bezig is. Pauzeer generatie onderbreekt het werk bij een controlepunt; het is geen sample-nauwkeurige pauzeknop voor een lopende modelberekening.

Stop generatie annuleert werk waar de onderliggende bewerking dit toelaat. Een lopende proces- of netwerkstap kan nog tijd nodig hebben. Stop geluid stopt afspelen. Een gestopte preview betekent niet automatisch dat een aparte generatie ook is geannuleerd. Wacht op de statusmelding voordat je een nieuwe taak start.

## 13. Muziek, sfeergeluid, fades en volume
Kies optioneel muziek en sfeergeluid bij Audio en uitvoer. Stel de lagen zacht genoeg in om de stem verstaanbaar te houden. Negatievere dB-waarden maken de betreffende laag zachter. Luister ook op een koptelefoon en bij laag afspeelvolume.

Muziekverlaging tijdens spraak kan de achtergrond laten terugnemen wanneer er gesproken wordt. Normalisatie helpt het eindniveau beheersen, maar herstelt geen vervormde bronopname. Begin met een rustige achtergrond en voeg pas daarna extra sfeer toe.

Fade-in en fade-out maken begin en einde van achtergrondlagen geleidelijk. Deze instellingen zijn niet bedoeld om de stem af te knippen. Wijzigingen bij een bestaande aflevering vragen een nieuwe montage-export. Voor een preview en eind-MP3 kunnen lengte en context verschillen: controleer ook het volledige begin en einde van de uiteindelijke MP3.

## 14. MP3, hoes en afleveringsgegevens
Kies een duidelijke uitvoerlocatie met de extensie .mp3. Controleer titel, podcastnaam, maker, nummer en beschrijving. Kies een hoesafbeelding wanneer je een afbeelding bij het audiobestand wilt. De uiteindelijke zichtbaarheid van de hoes hangt ook af van de speler en het publicatieplatform.

Publicatiegegevens en export bevat een Opslaan-knop en een bewerkbaar veld voor beschrijving/shownotes. Tekstopzet invoegen gebruikt koppen of een kort tekstfragment; dit is geen automatisch inhoudelijk geschreven samenvatting. Lees de tekst na en voeg zelf bijvoorbeeld bronnen of verwijzingen toe.

Een publicatiepakket bevat de MP3, eventuele hoes, metadata en shownotes plus losse ondertitel-/hoofdstukbestanden. Het is bedoeld voor publiceren, niet als volledige bewerkbare projectreservekopie. Wanneer de montage gewijzigd is, exporteer eerst opnieuw naar MP3 voordat je het publicatiepakket maakt.

## 15. Audiotijdlijn, takes en vastzetten
Na een volledige generatie kun je de audiotijdlijn openen. De blokken tonen rol, duur, pauze en geselecteerde take. Beluister een blok, maak extra takes en kies de versie die het best aansluit. Sommige engines leveren bij herhaling vrijwel hetzelfde geluid.

Een gekozen take of aangepaste pauze verandert eerst de montagekeuze. Maak daarna een nieuwe montage-MP3 om het resultaat te horen buiten de tijdlijn. De montagegeschiedenis heeft eigen ongedaan-maken/opnieuw-bediening; dit is iets anders dan Ctrl+Z voor de artikeltekst.

Vastzetten beschermt de goedgekeurde voiceclip en pauze tegen vervanging. Wil je die wijzigen, geef het blok eerst vrij. Achtergrondmuziek en eindnormalisatie kunnen bij een latere export nog veranderen. Als je de tekst van een vastgezet fragment wijzigt, moet je de bescherming bewust opnieuw beoordelen. Controleer overgangen, niet alleen de losse takes.

## 16. Hoofdstukken, ondertitels en promotieclips
Voeg in de tijdlijn een hoofdstuktitel toe bij een fragment. Leegmaken verwijdert de markering. Exporteer hoofdstukken en ondertitels voor de huidige gekozen takes. Hoofdstukken worden als apart JSON-bestand opgeslagen; ze worden niet automatisch in alle spelers of MP3's zichtbaar.

SRT en VTT volgen de bloktijden. De verdeling binnen een langer tekstblok is geschat, niet woordnauwkeurig uitgelijnd. Controleer en corrigeer ondertitels voordat je ze publiceert, vooral bij afwijkende uitspraak of tekstbewerkingen.

Promotieclip maken exporteert 1 tot 120 seconden vanaf een opgegeven begintijd. Kies MP3 of een MP4 met hoesafbeelding. Er komt een los SRT-bestand bij; tekst is niet ingebrand in de video. Kies een afgerond fragment en luister naar het begin en einde. Voor de volledige aflevering gebruik je de gewone MP3-export.

## 17. Eindcontrole en begeleid afronden
Eindcontrole audio zoekt lange stiltes, mogelijke oversturing en, waar blokken beschikbaar zijn, grote niveauverschillen. Klik een gevonden luisterpunt aan om het omliggende geluid te horen. Een melding is een aanleiding om te luisteren, geen bewijs dat je podcast onbruikbaar is.

De controle begrijpt geen inhoud, uitspraakbedoeling of passende emotie. Loop ook zelf begin, midden, einde, citaten en lastige namen na. Controleer op herhalingen, afgebroken zinnen en overgangen na een takewisseling.

Begeleid afronden geeft zes praktische stappen met vinkjes. Deze worden met het project bewaard en betekenen dat jij het onderdeel hebt gecontroleerd. Ze worden niet automatisch ingevuld als garantie van kwaliteit. Exporteer na aanpassingen opnieuw en bewaar de uiteindelijke projectversie vóór uploaden.

## 18. Bibliotheek, templates en projectpakketten
Afleveringenbibliotheek bewaart projectmomentopnamen, montagegegevens en een kopie van de eind-MP3. Je kunt op titel zoeken, een project openen en de status bijhouden. Verwijderen uit de lijst verwijdert de bijbehorende bestanden niet.

Stemclips en andere bronnen blijven in de bibliotheek verwijzingen naar bestaande bestanden. Verwijder die dus niet zomaar. Gebruik een projectpakket als je de aflevering wilt verplaatsen met beschikbare modellen, stemopnamen, muziek, hoes en takes. Software-installaties, licenties en de eigen-stemruntime worden niet automatisch meegeleverd.

Afleveringstemplates bewaren vaste keuzes zoals stemmen, tempo, muziek, hoes, podcastnaam en intro/outro. Ze vervangen niet automatisch je artikeltekst of uitvoerpad. Geef templates herkenbare namen. Test een nieuwe intro of outro met een preview en controleer de aansluitingen in de volledige aflevering.

## 19. Publiceren en podcastplatforms
Open Publiceren > Uploaden naar podcast-host. De lijst geeft per bestemming aan wat hier mogelijk is. Een host bewaart je audiobestanden en levert doorgaans een RSS-feed. Luisterplatforms nemen de aflevering via die feed over nadat je de show hebt aangemeld.

Transistor heeft een directe koppeling: vul show-ID/slug en API-sleutel in, upload als concept en controleer dit op het dashboard. Publiceren vraagt een afzonderlijke bevestiging. De API-sleutel blijft in het geheugen van dat venster. Bij een onbekende uitkomst blokkeert de toepassing automatische herhaling om dubbele concepten te voorkomen; controleer dan het dashboard.

Voor andere hosts maak je een publicatiepakket en upload je via hun website. De platformlijst bevat website- en instructieknoppen. Sla je bestemming en eigen RSS-feed op bij het project; gebruik RSS-feed kopiëren voor de aanmelding. Alleen een bestemming kiezen publiceert niets. Accounts, voorwaarden en beschikbaarheid worden door het platform bepaald.

## 20. Thema's, vensters en interfacetaal
Open Weergave > Layout en kleurthema. Kies uit zestien paletten met een eigen kleurvoorbeeld: Parel & blauw, Nachtblauw, Honing & papier, Lagune, Bosavond, Hoog contrast, Lavendel, Perzikbloesem, Rozenkwarts, Salietuin, Zomerlucht, Duin & heide, Koraal & zee, Pruimenavond, Petrolstudio en Cacao & koper. Klik Toepassen bij het gewenste voorbeeld. De lijst kun je naar beneden schuiven. De verandering wordt meteen toegepast op de toepassingsvensters. Je voorkeur wordt lokaal bewaard voor een volgende start en verandert je tekst of steminstellingen niet.

Vensterranden, systeemmeldingen en Windows-bestandsdialogen volgen de Windows-instellingen. De thema's veranderen kleuren en leesbaarheid; ze verplaatsen geen bediening. Je kunt hoofdvenster en veel hulpvensters groter maken en beschikbare deelvensters verslepen.

Grotere letters en Kleinere letters onder Weergave veranderen de editorweergave. Taal / Language kiest Nederlands of Engels; herstart om alle bestaande labels consequent te laten omschakelen. Dit vertaalt geen podcasttekst en verandert niet de spraaktaal. F1 opent deze doorzoekbare handleiding. Je kunt de handleiding ook als tekst/Markdown opslaan.

## 21. Problemen oplossen
Geen geluid: controleer uitvoerbestand, gekozen afspeelapparaat, Windows-volume en of een preview klaar is. Verkeerde stem: controleer de actieve engine, roltoewijzing en of je een oude MP3 beluistert. Montagewijzigingen hoor je pas na opnieuw exporteren.

Piper start niet: controleer het programmapad én model met bijbehorende configuratie. Edge geeft een online fout: controleer internet en gebruik Edge TTS installeren / bijwerken. Een HTTP 403 komt van de online dienst en wordt niet opgelost met een ander Piper-model. Installeer een ontbrekend onderdeel via de daarvoor bedoelde bediening.

Vreemde accentletters of UTF-8-fouten: controleer de bron en gebruik de recente versie; verwijder niet standaard alle accenten. Eigen stem is traag: model laden en genereren vragen tijd en geheugen. Test een korte passage. Bij een fout bewaar je project en noteer de volledige melding, actieve engine en het tekstfragment. Vermijd steeds opnieuw starten zolang de vorige taak nog bezig is.

## 22. Sneltoetsen en zorgvuldig bewaren
Ctrl+O: project openen. Ctrl+S: project opslaan. Ctrl+Z / Ctrl+Y: tekstbewerking ongedaan maken / opnieuw. Ctrl+F: zoeken en vervangen. Ctrl+B / Ctrl+I: opmaakmarkeringen. F1: handleiding. De menu's en pictogramtips tonen aanvullende functies.

Bewaar tekst en instellingen als project; de eind-MP3 is een ander bestand. Bewaar bij belangrijke afleveringen ook een projectpakket. Controleer een pakket door het in een andere map te openen voordat je oude bronnen verwijdert.

De gekozen online engine of publicatiehost ontvangt tekst/audio wanneer jij die functie gebruikt. Een lokale Piper- of eigen-stemgeneratie gebruikt de aanwezige lokale modellen. Een projectpakket kan persoonlijke stemopnamen en teksten bevatten. Kies bewust waar je het bewaart of deelt. De licentie van de toepassing en de voorwaarden van stemmen, muziek en platforms blijven afzonderlijke zaken.


## 23. Menu-indeling en updates
De menubalk volgt de werkvolgorde. Project bevat opslaan, openen, bibliotheek,
templates en projectpakketten. Tekst bevat bewerken plus de submenu's Opmaak en
Tekst voorbereiden. Stemmen bevat modellen, eigen opname, profielen, klank en
uitspraak. Audio bevat achtergrondlagen, fades en luisteren. Productie bevat
genereren, hervatten, vertelcontrole, tijdlijn, eindcontrole en begeleid afronden.
Publiceren bevat afleveringsgegevens, promotieclips en de platformkeuze.
Weergave bevat thema's, tekstweergave en Taal / Language. Licentie en
installatiecontrole vind je onder Help.

Help > Zoeken naar updates opent het updatevenster. Vul een officiële
HTTPS-updatebron in en kies Updatebron opslaan. Controleren leest het versieoverzicht
op die locatie. Een nieuwere versie krijgt een Downloadpagina openen-knop. Die
opent alleen na jouw klik in de browser. De app installeert of vervangt niets.
Sluit de oude versie en bewaar je project voordat je een nieuwe versie gebruikt.

De standaardupdatebron is https://raw.githubusercontent.com/cyberfirepulse/podcaststudio/main/update.json. Deze werkt zodra de beheerder daar het updatebestand en de bijbehorende release heeft gepubliceerd. De bron is vooraf ingevuld; een eerder opgeslagen afwijkend adres blijft behouden. Een mislukte verbinding betekent niet dat je de nieuwste versie hebt.
Het voorbeeldbestand podcast_update_manifest.example.json is voor de beheerder:
publiceer een JSON met product PodcastStudio, version, channel stable,
download_url en optionele notes op je eigen HTTPS-updateadres. Bij een nieuwere
versie moet download_url een werkelijke HTTPS-downloadlink zijn. Je kunt een
lokaal JSON-bestand controleren met Lokaal updatebestand; dat is geen online check.
Gebruik niet het CAMT-updatebestand: dat hoort bij een ander product.


## 24. Eerder opgenomen preken en podcasts bewerken
Open Project > Bestaande opname importeren. Kies je WAV, MP3, FLAC, M4A of OGG.
De toepassing kopieert het bronbestand naar een eigen werkmap; je oorspronkelijke
opname wordt niet bewerkt. De eerste keer kies je Eenmalig installeren / model
downloaden. Dit vraagt internet voor software en het gekozen model. Daarna blijven
de audio en herkenning lokaal: netwerkverkeer is bij de herkenning geblokkeerd.

Kies Nederlands (nl), Engels (en) of automatische taalherkenning (auto). Het
meertalige small-model is een praktische eerste keuze; tiny is kleiner en sneller
maar kan meer fouten maken. Medium vraagt meer tijd en opslag. CPU is de standaard
zonder extra GPU-bibliotheken. Kies cuda voor je NVIDIA-kaart wanneer CUDA 12 en
cuDNN 9 beschikbaar zijn. De toepassing kan de DLL's van de bestaande eigen-
stemomgeving gebruiken. Een fout over GPU-bibliotheken kun je omzeilen door CPU
te kiezen. Transcriptie en eigen-stemgeneratie gebruiken aparte omgevingen.

Klik Opname transcriberen. Tijdens het verwerken zie je de activiteit en, zodra
passages gereed zijn, hoeveel minuten zijn verwerkt. Stop annuleert de herkenning;
een afgebroken transcriptie moet opnieuw gestart worden. Er worden geen opnamen
verstuurd. De eerste installatie en modeldownload kunnen wel tijd kosten.

Het bewerkingsvenster toont tijdcodes in de oorspronkelijke opname en per passage
de herkende en bewerkte tekst. Klik een rij en luister naar het origineel of de
gekozen audio. Pas rechts de tekst aan en klik Tekst opslaan. Een tekstcorrectie
kan alleen een herkenningsfout herstellen: het oorspronkelijke geluid verandert
hierdoor niet. Bij het wisselen van passages en sluiten wordt de huidige tekst
ook bewaard. Scan passage markeert aandachtspunten; via Tekst naar hoofdeditor
kun je de volledige tekst met alle bestaande tekstgereedschappen bewerken. Het
huidige editorproject wordt eerst als reservekopie opgeslagen.

Wil je andere woorden horen, kies vooraf de gewenste stem bij Stemmen en klik
Opnieuw inspreken voor de geselecteerde passage. Maximaal 600 tekens per
vervanging. De rest van je preek behoudt de originele opname. De stem kan qua
klank en opnamekwaliteit afwijken: luister naar de overgang. Er worden kleine
randfades toegevoegd tegen klikjes en omliggende stiltes worden zo veel mogelijk
behouden. Er is geen garantie op een onhoorbare overgang of exact gelijke duur.
Gebruik originele audio schakelt terug zonder de bewerkte tekst te wissen.
Deze passage weglaten sluit het hele passage-interval uit de nieuwe montage;
het verwijdert niets uit het bronbestand. Dit is geen fijnmazige waveform-editor.

Exporteer bewerkte MP3 maakt een nieuwe MP3 met de gekozen originele en nieuwe
passages plus losse SRT/VTT en montagegegevens. Achtergrondlagen uit de gewone
studio worden hierbij niet nogmaals toegevoegd: je opname kan al muziek bevatten.
Na vervanging of weglaten verschuiven latere tijden in de export. De tijdcodes in
het bewerkingsvenster blijven bij de bron horen; exportondertitels volgen de nieuwe
montage. Timing binnen een passage blijft geschat. Na export kun je verder in de
audiotijdlijn. Voor opnieuw inspreken van bronpassages gebruik je deze opnamebewerker.

Project > Opnamebewerking hervatten opent je laatste opnameproject. Het pad wordt
ook met je gewone project opgeslagen. Bewaar een Projectpakket om het opnameproject,
de gekopieerde bron en beschikbare vervangende audio mee te nemen naar een andere
map of computer. Alleen tekst exporteren is daarvoor niet genoeg. Herkenning is
geen garantie van correcte spelling, citaten of namen: lees de tekst na en luister
bij twijfel terug. Sprekers worden niet automatisch onderscheiden.


Onderbroken modeldownload: ontvangen delen blijven bewaard. Klik opnieuw op installeren om te hervatten. Laat de map PodcastStudio_Transcriptie staan.


## 25. Je podcast rechtstreeks opnemen
Open Audio > Podcast live opnemen. Dit is een volledige opnamefunctie, los van
het korte stemvoorbeeld voor stemklonen. Kies de gewenste microfoon uit de lijst.
Microfoons vernieuwen haalt de ingangen opnieuw op zonder een opname te starten.
Als de software ontbreekt, klik Microfoonsoftware installeren. Deze kleine
installatie vraagt internet; voor opnemen is geen spraakmodel of internet nodig.
De bestaande eigen-stemomgeving kan als microfoonruntime worden gebruikt.

In het leesvenster staat een kopie van de tekst uit de hoofdeditor. Je kunt daar
scrollen en tijdelijk aanpassen terwijl je inspreekt. Deze kopie vervangt niet je
opgeslagen hoofdtekst. Bewaar belangrijke tekstwijzigingen in de hoofdeditor.
Start opname opent de microfoon. De tijdteller toont de opgenomen audiolengte en
de meter geeft het ingangsniveau aan. Bij een hoog niveau of gemelde onderbreking
verschijnt een melding. Controleer de juiste microfoon en spreekvolume.

Pauzeren sluit de pauzetijd uit van de opname; Hervatten neemt weer verder op.
Stop en bewaar rondt het WAV-bestand af. Er wordt rechtstreeks naar schijf geschreven,
zodat lange opnamen niet helemaal in het werkgeheugen hoeven te passen. Bij een
normale stop blijft de opname automatisch in de werkmap staan. Een periodiek
bijgewerkte WAV-header beperkt schade bij een onverwachte onderbreking, maar een
stroomstoring kan nog recent geluid verliezen. Maak altijd zelf een reservekopie.
Per opname geldt maximaal vier uur of eerder de WAV-formaatlimiet.

Beluister speelt de opname af; Stop afspelen stopt alleen het afspelen. Opslaan
als WAV kopieert naar een eigen bestandsnaam. Opslaan als MP3 maakt een MP3 zonder
extra muziek of stemgeneratie. Met Deze opname bewerken open je de importfunctie
met deze WAV al ingevuld. Daar kun je transcriberen en passages bewerken zoals
in onderwerp 24. Opnemen en spraakklonen zijn dus verschillende handelingen.

Sluit het opnamevenster pas na Stop en bewaar. Als je de hele app tijdens opname
sluit, vraagt die eerst of de opname moet worden gestopt en bewaard. Je laatste
opnamepad wordt onthouden en kan met een projectpakket worden meegenomen.
Opnameknoppen zijn getest met een gesimuleerde microfoon; controleer bij je eerste
gebruik ook een korte opname met je eigen apparaat en de Windows-microfoonrechten.

De modeldownload toont nu ontvangen MB en automatische verbindingspogingen.
Nieuwe pogingen gebruiken verse downloadverzoeken. Het volledige small-model is
op deze computer gedownload, op bestandsintegriteit gecontroleerd en gebruikt
voor een echte offline Nederlandse herkenningstest op NVIDIA.


## 26. Equalizer, laagfilter en spraakcompressie
Open Audio > Equalizer en spraakdynamiek. De zes banden liggen bij 100, 250, 700,
1800, 4000 en 9000 Hz, van lage tot hoge tonen. Elke band kan van -12 tot +12 dB.
Begin rond 1 tot 3 dB. Een teveel aan lage tonen kan wollig worden; veel hoge tonen
kunnen scherpe s-klanken benadrukken. De presets Neutraal, Warme verteller,
Heldere spraak, Zacht en rustig, Compacte radiostem en Minder wollig zijn
startpunten. Pas ze aan op je opname en luidsprekers.

Equalizer inschakelen bepaalt of de bewerking actief is. Alles neutraal zet
banden en opties terug en schakelt uit. Het 80 Hz-laagfilter kan gerommel verminderen,
maar verwijdert geen willekeurige ruis of galm. Zachte spraakcompressie verkleint
niveauverschillen met vaste, rustige instellingen; een compressor herstelt geen
vervormde opname. Voorversterking bepaalt het niveau vóór de bewerking. Laat wat
ruimte wanneer je banden versterkt. De eindlimiter blijft overbelasting beperken.

Alleen stem bewerkt het spraakkanaal vóór achtergrondmuziek wordt toegevoegd.
Volledige eindmix bewerkt ook muziek en sfeer. Een geïmporteerde opname kan al
muziek bevatten: dat zit dan in hetzelfde kanaal en kan niet door EQ gescheiden
worden. Normalisatie na de EQ kan het gemiddelde niveau weer gelijk trekken.
De toonhoogte en snelheid worden door deze equalizer niet veranderd.

Kies een audiobestand en begintijd voor een voorbeeld van maximaal 15 seconden.
Vergelijk Zonder en Met bewerking. Een beschikbare onbewerkte montage-WAV wordt
bij voorkeur als bron gebruikt. Bij een los bestand wordt altijd dat hele
signaal bewerkt, ongeacht de scopekeuze. Een eerder bewerkte MP3 opnieuw bewerken
stapelt de effecten; kies bij voorkeur een onbewerkte bron.

Opslaan bewaart de instellingen bij je project en, indien aanwezig, bij de huidige
montage. Exporteer die daarna opnieuw naar MP3. Een open audiotijdlijn neemt de
instellingen ook over. Montage-undo/redo herstelt de EQ van de montage; open het
EQ-venster en sla op wanneer je die keuze ook voor volgende generaties wilt gebruiken.
Afleveringstemplates bewaren de EQ eveneens. Audiobestand met EQ exporteren maakt
een nieuwe MP3 zonder de bron te overschrijven. Voor live opnamen blijft de ruwe
WAV onbewerkt; Opslaan als MP3 gebruikt de opgeslagen EQ. De transcriptiemontage
neemt de huidige EQ bij export mee. Er is geen rechtstreekse microfoonmonitoring
met effecten: dit is nabewerking, niet live meeluisteren.


## 27. De grafische equalizer bedienen
De vernieuwde equalizer volgt het kleurontwerp met een vloeiende curve en zes
gekleurde punten. Sleep een punt verticaal om die band te versterken of te
verminderen. De frequenties blijven vast op 100, 250, 700, 1800, 4000 en 9000 Hz.
De bijbehorende velden veranderen mee; je kunt ook rechtstreeks een dB-waarde
invoeren. Dubbelklik een geselecteerd punt om die band op nul te zetten. Met de
pijltoetsen omhoog/omlaag wijzig je het geselecteerde punt in stappen van 0,5 dB.

De curve is de gecombineerde respons van de EQ-banden, geen bewegend spectrum
van het geluid. Een punt kan door overlappende banden iets anders liggen dan de
waarde van zijn eigen veld. Laagfilter, voorversterking en compressie worden niet
in die bandcurve meegerekend. EQ-verwerking gebruikt 44,1 kHz voor een consistente
weergave en uitvoer. Je kunt de equalizer uitschakelen om deze bewerking te omzeilen.

Kies het luisterbestand en de begintijd en klik Afspelen. De balk toont het
voorbeeld tot maximaal 15 seconden. Klik Origineel of Met EQ om op dezelfde
luisterpositie te vergelijken. Je kunt pauzeren/hervatten of in de balk springen.
Een bestaande vergelijking wordt uit de luistercache hergebruikt. Wanneer je een
band wijzigt, stopt het voorbeeld: klik opnieuw op Afspelen om de nieuwe instelling
te beluisteren. Dit is geen real-time microfoonmonitor.

Een handmatig gewijzigd preset wordt Aangepast. Alles neutraal zet de opties
terug. Opslaan en toepassen bewaart de instellingen en markeert de montage voor
nieuwe export. Je oorspronkelijke opname blijft bewaard. De bestaande MP3 wordt
pas aangepast wanneer je die opnieuw exporteert. Met MP3 exporteren kun je het
gekozen audiobestand rechtstreeks als een nieuwe bewerkte MP3 opslaan.

## 28. Stem, ruimte en geluidseffecten (v1.44)
Open Audio > Stem, ruimte en geluidseffecten. De ronde draaiknoppen reageren op verticaal slepen, het muiswiel en pijltjestoetsen. Dubbelklik herstelt de standaardwaarde. Je kunt ook exact een getal invullen.

**Passage afstellen:** kies een bestaand audiofragment uit de montage. Regel tempo, toonhoogte, warmte, helderheid, volume en de pauze erna. Beluister het origineel en de afstelling, klik daarna Op deze passage toepassen. Dit maakt een nieuwe take; de bron blijft intact. Opnieuw afstellen gebruikt dezelfde oorspronkelijke bron om opstapeling van effecten te voorkomen. Het gaat om het hele gekozen audioblok, niet om een willekeurige selectie woorden. Zet een goedgekeurde take vast in de tijdlijn. Exporteer daarna de montage opnieuw.

**Ruimte en echo:** kies droge studio, warme huiskamer, kleine zaal, auditorium, kerk of echo. Regel hoeveelheid, grootte en nagalmduur. Dit simuleert een ruimte; het verwijdert geen bestaande galm. Een bescheiden hoeveelheid werkt doorgaans beter voor spraak. De nagalm stopt bij het afleveringseinde.

**Geluidseffecten:** kies deurbel, grindpad of passerende auto, of laad je eigen WAV/MP3. De meegeleverde geluiden zijn synthetische voorbeelden. Voor realistische omgevingen kun je eigen opnamen gebruiken. Stel starttijd, duur, volume, stereopositie en fades in. Links naar rechts en rechts naar links laten het geluid bewegen. Klik Invoegen / bijwerken, daarna Opslaan. Maximaal 32 geluiden. Bij gekozen passage vult de huidige begintijd van dat audioblok in. De tijden blijven vaste seconden: controleer ze opnieuw na wijzigingen in tempo of montage.

Voorbeeld eerste 15 seconden gebruikt het aangegeven voorbeeldbestand; het speelt niet automatisch een opnieuw opgebouwde montage. Kies bij voorkeur een droge bron, anders kunnen eerder ingemengde effecten dubbel klinken. Audiobestand met effecten exporteren maakt een nieuwe MP3. Opgeslagen effecten komen ook mee bij het genereren en exporteren van de montage. Gebruik Project > Opslaan voor een benoemd project en een projectpakket om bronbestanden mee te nemen. Dit is nabewerking; er is geen live microfoonmonitor met effecten.

## 29. Sporenmixer en volumelijnen (v1.45)
Open Audio > Sporenmixer en volumelijnen. Je stem staat bovenaan. Voeg muziek en geluiden als eigen gekleurde sporen toe. Nieuwe geluiden spelen standaard één keer. Elk extra spoor bevat één audiobestand; meerdere geluiden kun je op afzonderlijke sporen plaatsen. De stem volgt de huidige takes uit je montage. Voor een losse opname kies je Stembron. De totale mix eindigt tegelijk met de stem.

Vink Sporenmixer gebruiken in eindmix aan. Deze vervangt dan de oude muziek-, sfeer- en losse geluidenmix om dubbele audio te voorkomen. Ruimte-effecten voor de stem en de bestaande equalizer blijven actief. Automatisch muziekverlagen uit de oude achtergrondmix wordt hier vervangen door je handmatige volumelijnen. Bestaande achtergrond overnemen kopieert bestaande muziek/sfeer en geluidscues naar sporen. Controleer die kopie: panning en fades uit de oude geluidscues worden niet overgenomen. Oude achtergrondmuziek behoudt bij deze import het herhalen.

**Start en duur:** kies een spoor en regel Start, Bronbegin en Duur. Duur is in seconden; zonder Herhalen wordt nooit langer afgespeeld dan de beschikbare bron. Sleep een gekleurd blok horizontaal om het te verplaatsen; sleep de rechterrand om de duur aan te passen. Spoor bijwerken verwerkt de velden. Afspelen en Opslaan verwerken de velden van het geselecteerde spoor ook. Kies Herhalen alleen wanneer een kort geluid echt moet doorlopen, bijvoorbeeld regen. Een deurbel hoeft meestal maar één keer.

**Volume over tijd:** Spoorvolume dB regelt het hele spoor. Dubbelklik op het gekleurde blok voor een volumepunt. Sleep de punten omhoog/omlaag voor volume en links/rechts voor tijd. Rechtsklik verwijdert een punt. Je kunt ook exacte tijd en dB invullen met Punt toevoegen / bijwerken. De puntvolumes worden bij het spoorvolume opgeteld. Tussen de punten verlopen de overgangen vloeiend in dB. Vóór het eerste en na het laatste punt blijft de dichtstbijzijnde waarde gelden. De tijd van de punten telt vanaf het begin van het spoor. Punten voorbij het huidige spoor-einde blijven bewaard maar zijn pas hoorbaar als het spoor weer langer wordt.

Voorbeeld: zet muziek op -12 dB, maak punten op 0 seconden met 0 dB, 5 seconden met -18 dB en 20 seconden met -18 dB. De muziek daalt dan tijdens de eerste vijf seconden van -12 naar -30 dB. Voeg aan het eind twee punten toe om uit te faden. -60 dB is bijna stil; Dempen schakelt het spoor volledig uit.

**Beluisteren:** Beluister dit spoor speelt alleen het gekozen spoor met zijn afstelling. Solo laat bij gezamenlijk afspelen alleen de gemarkeerde sporen horen. Dempen heeft voorrang op Solo. Klik in de tijdliniaal of typ de Afspeelkop-tijd en kies Afspelen vanaf afspeelkop voor de hele mix. De mix wordt eerst voorbereid; dit is geen directe live mengtafel. Bij aanpassingen stopt de preview: klik opnieuw Afspelen. Stop beëindigt het geluid. De volumelijnen en export gebruiken dezelfde verwerking. Sterke piekbegrenzing of eindnormalisatie kan de uiteindelijke luidheid beïnvloeden.

Opslaan bewaart sporen, punten en het aan/uit-vinkje in de montage en de huidige instellingen. Gebruik daarnaast Project opslaan voor een benoemd project en Projectpakket voor een kopie inclusief bronbestanden. Mix exporteren maakt een nieuwe MP3; ook een nieuwe montage-export gebruikt opgeslagen volumelijnen. De stemopname en geïmporteerde bronbestanden blijven intact. Maximaal 32 extra sporen en 100 punten per spoor. Wijzigingen in spreektempo veranderen de lengte van de stem; controleer daarna je vaste spoortijden.

**Geluiden eerst horen:** in Audio > Stem, ruimte en geluidseffecten staat nu Geluid vooraf beluisteren. Deze knop gebruikt een apart, hoorbaar voorbeeldniveau, onafhankelijk van het lage achtergrondvolume. Afstelling beluisteren gebruikt juist jouw volume, duur, fades en stereokeuze. Het voorbeeld is maximaal vijftien seconden. Als zelfs het voorafvoorbeeld stil blijft, controleer de Windows-volumemixer en de gekozen luidspreker/koptelefoon. Grindpad is een synthetisch demonstratiegeluid van zes seconden.

## 30. Eén werkruimte met ingebouwde panelen (v1.46)
De belangrijkste gereedschappen openen nu in het hoofdvenster. Tekst/Stemmen/Audio en uitvoer blijven linksboven. Stem en effecten, equalizer, opname, transcriptbewerking en help openen rechts als tabbladen. Passages en takes en de Sporenmixer openen onderaan. Zo kun je tekst, een stemeffect en de montage tegelijk zien. Het gaat om vaste dockgebieden met tabbladen; je kunt de panelen in deze versie nog niet losmaken en vrij naar andere docks slepen.

Sleep de scheidingslijn tussen links/rechts of tussen boven/onder om meer ruimte te geven. De verhoudingen worden met de instellingen opgeslagen. Weergave > Werkruimte herstellen zet de verdeling terug. Een groot gereedschap kan horizontale en verticale schuifbalken hebben: hiermee bereik je ook de bediening die buiten het zicht valt. De afspeel-, stop-, opslag- en exportknoppen van de mixer staan vast onderaan het paneel.

Klik opnieuw op het menu van de mixer, equalizer, effecten of passages om het bestaande tabblad naar voren te halen; die panelen worden niet dubbel geopend. Paneel sluiten sluit alleen dat gereedschap. Sla je wijzigingen eerst op. Opnieuw openen gebruikt opgeslagen instellingen; onopgeslagen wijzigingen van een gesloten paneel worden niet automatisch teruggehaald. Tijdens een lopende audiobewerking wacht je met sluiten tot die klaar is. Voor live opnemen moet je eerst Stop en bewaar kiezen. Bestandskeuzes, bevestigingen en enkele kleinere hulpprogramma's blijven losse dialoogvensters.

## 31. De werkruimte van v1.47: sporen, draaiknoppen en 8-bands EQ

### Beginnen en overzicht
Bij het starten opent de nieuwe sporenwerkruimte. Je kunt hem ook openen via Audio > Sporenmixer en volumelijnen. Tekst blijft links, het geselecteerde fragment of spoor verschijnt rechts, en één tijdlijn staat onderaan. Equalizer, effecten en de normale audiotijdlijn verwijzen naar deze werkruimte. Takes en hoofdstukken (geavanceerd) bewaart de oudere gedetailleerde montagefuncties.

De vier horizontale banen zijn Stem (groenblauw), Muziek (paars), Sfeer (oker) en Effecten (koraal). Muziek, sfeer en effecten kunnen elk meerdere fragmenten bevatten; fragmenten op dezelfde baan worden opgeteld als ze overlappen. Klik op een baankop voor instellingen van het hele spoor. Klik op een gekleurd fragment voor de instellingen van dat fragment. Die twee niveaus tellen op: -6 dB fragment plus -12 dB spoor betekent -18 dB vóór de eindbegrenzing.

Alles passend toont alle fragmenten van begin tot eind binnen de beschikbare breedte. Het past de schaal automatisch aan als het venster groter of kleiner wordt. De spoorkoppen blijven vast links staan. +/− of de zoomschuif vergroten het detail rond de afspeelkop; Zoom op selectie richt zich op het gekozen fragment. Ctrl+muiswiel zoomt; het gewone muiswiel scrolt verticaal. In detailweergave verschijnt de horizontale schuifbalk. De roze lijn is de afspeelkop: klik in de tijdliniaal om die te verplaatsen. Het eindresultaat eindigt bij het einde van de stem, ook wanneer een achtergrondfragment verder doorloopt.

### Audio toevoegen en fragmenten bewerken
Gebruik Muziek +, Sfeer + of Effect + voor een eigen WAV/MP3/FLAC/M4A/OGG. Nieuwe fragmenten beginnen bij de afspeelkop, met herhalen uitgeschakeld. De aanvankelijke duur wordt beperkt tot de resterende vertelduur. Via Geluidenbibliotheek kun je de voorbeelden eerst apart beluisteren en daarna toevoegen. Die voorafpreview heeft een zelfstandig hoorbaar niveau; een zacht mixvolume maakt hem niet onhoorbaar. De meegeleverde deurbel, grind en auto zijn synthetische voorbeelden, geen veldopnamen.

Sleep een muziek-/geluidsblok horizontaal om het te verplaatsen. Sleep de rechterrand om de duur te wijzigen. Start, Bronbegin en Duur rechts geven exacte seconden. Bronbegin kiest waar je in het oorspronkelijke bestand begint. Zonder Herhalen stopt een bron vanzelf wanneer het bestand op is, ook als je een langere blokduur invult. Herhalen laat een korte bron doorlopen tot de ingestelde duur. Infaden en Uitfaden werken per fragment of per spoor. Verwijder fragment verwijdert alleen het geselecteerde muziek-/geluidsblok, niet het bronbestand.

M en S in de spoorkop betekenen Dempen en Solo. Je kunt meerdere sporen solo zetten. Dempen heeft voorrang. Het instellingenpaneel heeft ook fragmentniveau voor muziek en effecten. De geluidsknoppen zijn compact en hebben herkenbare kleuren. Draaiknoppen werken met verticaal slepen, muiswiel, pijltjestoetsen en exact getal invoeren; dubbelklikken herstelt hun standaardwaarde.

### Stempassages
De stem bestaat uit je bestaande montagepassages en takes. Selecteren in de tijdlijn laat de instellingen rechts zien en markeert de tekst wanneer de passage letterlijk in het artikel staat. Een tekstselectie die binnen een bestaande passage valt, selecteert die hele audiopassage. Dit knipt geen nieuwe woordgrenzen: bewerking is op het niveau van de gekozen passage.

Tempo, toonhoogte, warmte, helderheid, volume, stereopositie en pauze erna zijn beschikbaar. Bronbegin en Duur kunnen de passage inkorten. Toepassen maakt een nieuwe take; het origineel blijft beschikbaar. Opnieuw afstellen gebruikt de oorspronkelijke bron van die afstelling, zodat vertragen of EQ niet per ongeluk opstapelt. Vastgezette passages moeten eerst worden vrijgegeven via Takes en hoofdstukken. Verslepen van een stemblok verandert de passagevolgorde; hoofdstukken blijven bij hun passage. Geef vastgezette passages vrij voordat je de volgorde wijzigt. Veranderingen in duur of volgorde kunnen achtergrondtijden beïnvloeden: controleer ze opnieuw.

Stem laden importeert een eigen opname als één nieuwe passage in een aparte montage, met een lokale WAV-werkkopie. Het origineel wordt niet overschreven. De tekst van die ene passage is aanvankelijk de bestandsnaam; gebruik de bestaande transcriptiefunctie om gesproken inhoud naar bewerkbare tekst om te zetten.

### Volume- en stereoautomatisering
Kies Volumelijn of Stereolijn boven de tijdlijn. Dubbelklik in een baan/fragment om een punt toe te voegen. Sleep de punten horizontaal voor tijd en verticaal voor niveau. Rechtsklik verwijdert een punt. Punt (s), Waarde en Punt bewaren bieden exacte invoer. Voor volume is de waarde dB (-60 tot +12); voor stereo is -1 links, 0 midden en +1 rechts.

Spoorpunten gebruiken afleveringstijd; fragmentpunten tellen vanaf het begin van dat fragment. Een stempassage selecteren en dubbelklikken op de lijn bewerkt de globale stembaan. Puntvolumes tellen bij het vaste volume op. Tussen punten loopt het niveau vloeiend in dB; vóór/na de punten blijft de dichtstbijzijnde waarde gelden. -60 dB is bijna stil; Dempen is volledig stil. Voor stereo schuift de positie vloeiend tussen links en rechts.

Voorbeeld voor muziek: zet het spoor op -12 dB. Maak punten op 0 s / 0 dB, 5 s / -18 dB, 25 s / -18 dB en 30 s / 0 dB. Daarmee daalt muziek tijdens de introductie en komt die aan het eind terug. Zachter bij spraak verlaagt daarnaast de achtergrond automatisch bij een hoorbare stem. Muziekverlaging dB regelt de sterkte van die reactie; het is geen gegarandeerde exacte dB-afname. Voor de meest voorspelbare regeling gebruik je deze functie op het volledige muziekspoor.

### Acht parametrische EQ-banden
Open het tabblad 8-bands EQ rechts. De EQ hoort bij de huidige selectie: een spoor, een muziek-/geluidsfragment of een stempassage. Elke selectie heeft eigen instellingen. EQ inschakelen bedient de volledige EQ; Band actief bedient alleen de gekozen band.

De grafiek toont de berekende gecombineerde filterrespons, geen live spectrum. Klik op een van de acht punten of de knoppen 1–8. Sleep het punt horizontaal voor frequentie en verticaal voor versterking. De drie ronde knoppen bedienen Frequentie (20–20.000 Hz), Versterking (-18 tot +18 dB) en Q (0,15–18). Kleine Q is breed, grote Q is smal. Het muiswiel op de grafiek verandert Q van de geselecteerde band.

Per band zijn beschikbaar: Bel, Lage shelf, Hoge shelf, Laag-af en Hoog-af. Bel versterkt/verzwakt rondom één frequentie; shelves veranderen het lage/hoge gebied geleidelijk. Laag-af verwijdert het lage gebied, Hoog-af het hoge. Bij afsnijfilters kies je 12, 24 of 48 dB per octaaf. Hun gainknop verandert de afsnijding niet; frequentie, Q en steilheid bepalen die. Dezelfde filtercoëfficiënten worden voor grafiek en audio gebruikt.

Presets zijn een beginpunt. Je kunt ze aanpassen en met Preset bewaren onder een eigen naam opslaan. Zonder EQ en Met EQ beluisteren de gekozen selectie met alle overige bewerkingen gelijk. Gelijk luistervolume A/B past beide voorbeelden aan naar hetzelfde luidheidsdoel, zodat harder niet automatisch beter lijkt. De voorbeelden starten opnieuw bij het begin van de selectie; het aangepaste luistervolume verandert je exportinstellingen niet. Op zeer korte of stille fragmenten kan een luidheidsvergelijking minder betekenisvol zijn.

Bestaande zesbands-EQ-instellingen worden bij de eerste overstap naar de nieuwe werkruimte vertaald naar zes van de acht parametrische banden. De oude algemene ruisfilter-/compressie-instellingen blijven als aparte verwerking behouden. Die horen niet bij de nieuwe EQ-curve. Pas een oude projectkopie bij voorkeur eerst toe op een kort fragment en vergelijk het geluid.

### Ruimte, preview en bewaren
Het tabblad Ruimte heeft Galm, Ruimtegrootte, Nagalm en Echo en presets van droog tot kerk. Het voegt een ruimte toe en verwijdert geen bestaande galm. De staart eindigt bij het einde van het fragment of de aflevering. Gebruik voor verstaanbare spraak bescheiden waarden.

▶ speelt de mix vanaf de afspeelkop, Ⅱ pauzeert/hervat en ■ stopt. ▶ Fragment speelt de geselecteerde passage, clip of baan afzonderlijk. De mix wordt vooraf berekend; dit is geen live microfoonmonitor. Aanpassingen stoppen de preview zodat je geen verouderde afstelling blijft horen. Klik daarna opnieuw op Afspelen. Bij inhoudelijke audio-aanpassingen wordt Mixer actief ingeschakeld; je kunt hem zelf uitzetten om de nieuwe mix te omzeilen. Een selectievoorbeeld kan onafhankelijk daarvan zijn eigen afstelling laten horen.

Opslaan bewaart de sporen, punten, EQ, fragmentinstellingen en werkruimte. Gewijzigde stempassages worden daarbij als nieuwe takes toegepast. Project opslaan (Ctrl+S) bewaart ook nog niet toegepaste passage-instellingen; die worden bij de eerstvolgende montage-export toegepast. Maak een benoemd project en gebruik Projectpakket als ook de bronnen mee moeten. Export MP3 maakt een nieuwe eindmix met metadata en eventuele hoes. Een bronbestand kan niet als uitvoernaam worden gebruikt. Ook de gewone montage-export gebruikt opgeslagen instellingen. Niet opgeslagen wijzigingen worden bij sluiten van de werkruimte gevraagd; bij sluiten van de app blijven ze in het automatische herstelproject bewaard.

De sporenmixer vervangt de oude muziek-/sfeermix wanneer hij actief is, om dubbel geluid te voorkomen. Oude instellingen zijn bij de eerste import meegenomen waar mogelijk. Controleer tijden na tempo- of montagewijzigingen. De grafische stijl volgt het kleur- en indelingsconcept van de mock-up, binnen de bestaande Windows/Tk-interface.

## 32. Projectbeheer en ondersteuning (v1.48.1)

Project > Nieuw project (Ctrl+N) begint met lege tekst en een lege montage. Stemmodellen, eigen-stemreferenties en algemene voorkeuren blijven beschikbaar. Muziek, sfeer, hoes, oude uitvoer en projectgegevens worden losgekoppeld; de bronbestanden zelf worden niet verwijderd.

Ctrl+S bewaart het geopende project op dezelfde locatie. Bij een naamloos project kies je eerst een bestandsnaam. Project > Project opslaan als (Ctrl+Shift+S) maakt een apart projectbestand en werkt verder in die kopie. Bronmedia blijven verwijzingen; een zelfstandige kopie met beschikbare bronnen maak je met Projectpakket exporteren.

Een sterretje in de titel en de statusregel tonen niet-opgeslagen wijzigingen. De statusregel toont ook de volledige projectlocatie. Vóór nieuw, openen en afsluiten kun je kiezen: Ja om op te slaan, Nee om wijzigingen niet in het projectbestand te bewaren, of Annuleren om te blijven. Een naam kiezen en dat venster annuleren breekt de projectwisseling ook af.

Recent geopende projecten bewaart maximaal twaalf projectlocaties. Een ontbrekende vermelding kan uit de lijst worden verwijderd zonder bronbestanden te wissen. De afleveringenbibliotheek is daarnaast beschikbaar.

Automatisch opslaan is een herstelvoorziening en vervangt bewust opslaan niet. Bij een afwijkende eerdere sessie biedt de app herstel van de sessie, openen van het laatst opgeslagen project of leeg beginnen. Bij een naamloze sessie kun je herstellen of leeg beginnen. Herstellen overschrijft het eerder opgeslagen project niet. Kies daarna zelf Opslaan of Opslaan als.

Project > Ontbrekende projectbestanden herstellen toont ontbrekende verwijzingen. Wijs een bestand opnieuw aan of zoek in een map naar unieke gelijke bestandsnamen. Fragmenttijden, EQ, effecten en volumepunten blijven behouden. Gelijknamige dubbelen moet je zelf aanwijzen. Kies bij een ONNX-stem ook de map met het bijbehorende .onnx.json-bestand. Sla het aangepaste project daarna op.

Help > Over Podcast Studio toont versie, build, uitgever en contact. Help > Contact en ondersteuning bevat cyberfirepulse@gmail.com en de GitHub-productpagina. Probleem melden maakt een bewerkbaar rapport met algemene systeem- en versiegegevens, zonder automatisch tekst, opnamen, bronpaden of licentiesleutels toe te voegen. Bekijk het voor je het opslaat of een e-mail opstelt. Er wordt niets automatisch verzonden.

Help > Licentiegegevens toont de editie, laatste status, geldigheidsdatums indien opgegeven, installatie-ID en controlegegevens. De klantversie gebruikt echte licentiecontrole; zonder passende activatie blijven je tekst en projecten bereikbaar, maar kunnen gelicentieerde productieopties geblokkeerd zijn. Gebruiksvoorwaarden en Privacy en online diensten zijn apart bereikbaar vanuit Help.

Lokale spraak en online spraak zijn verschillende routes. Edge verstuurt tekst naar de spraakdienst; publiceren verstuurt gekozen uitvoer naar de host. Downloaden, updates en activatie gebruiken internet. Lees het privacyoverzicht voor je persoonlijke inhoud deelt. Voor een update is een bereikbaar, geldig updatebestand van de uitgever nodig; de app toont een fout als de bron ontbreekt en vervangt zichzelf niet stilzwijgend.
