---
layout: page
status: publish
published: true
title: Greenshot hjelp
author:
  display_name: greenshot
  login: admin
  email: greenshot-developers@lists.sourceforge.net
  url: http://getgreenshot.org/
author_login: admin
author_email: greenshot-developers@lists.sourceforge.net
author_url: http://getgreenshot.org/
wordpress_id: 542
wordpress_url: http://getgreenshot.org/?page_id=542
date: !binary |-
  MjAxMi0wOS0xNiAwODo0NDoxMSArMDIwMA==
date_gmt: !binary |-
  MjAxMi0wOS0xNiAwNjo0NDoxMSArMDIwMA==
categories: []
tags: []
comments: []
---
<p><small>Version 1.0.2 RC2 - Norsk omsetjing av Ivar Barstad</small></p>
<h2>Innhald</h2>
<ol>
<li><a href="#screenshot">Ta eit skjermknips</a></li>
<ol>
<li><a href="#capture-region">Knips område</a></li>
<li><a href="#capture-last-region">Knips siste område</a></li>
<li><a href="#capture-window">Knips vindauge</a></li>
<li><a href="#capture-fullscreen">Knips fullskjerm</a></li>
<li><a href="#capture-ie">Knips Internet Explorer</a></li>
</ol>
<li><a href="#editor">Å bruke knipsfiksaren</a></li>
<ol>
<li><a href="#editor-shapes">Teikne former</a></li>
<li><a href="#editor-text">Leggje til tekst</a></li>
<li><a href="#editor-highlight">Markering</a></li>
<li><a href="#editor-obfuscate">Sensurering</a></li>
<li><a href="#editor-crop">Skjere skjermknipset</a></li>
<li><a href="#editor-adding-graphics">Setje grafikk inn i skjermknips</a></li>
<li><a href="#editor-reuse-elements">Gjenbruk av teikna element</a></li>
<li><a href="#editor-export">Eksportere skjermknipset</a></li>
</ol>
<li><a href="#settings">Innstillingsdialogen</a></li>
<ol>
<li><a href="#settings-general">Generelle innstillingar</a></li>
<li><a href="#settings-capture">Knipsinnstillingar</a></li>
<li><a href="#settings-output">Ut-innstillingar</a></li>
<li><a href="#settings-printer">Utskriftsinnstillingar</a></li>
</ol>
<li><a href="#help">Lyst til å hjelpe?</a></li>
<ol>
<li><a href="#help-donate">Vurder ein donasjon</a></li>
<li><a href="#help-spread">Spre ryktet</a></li>
<li><a href="#help-translate">Send inn omsetjing</a></li>
</ol>
</ol>
<p>	<a name="screenshot"></a></p>
<h2>Ta eit skjermknips</h2>
<p>
		Du kan knipse ein del av skjermen ved å bruke <kbd>Print</kbd>-tasten<br />
		eller ved å høgreklikke Greenshot-ikonet i varselfeltet nedst til høgre.<br><br />
		Det er fleire måtar å knipse skjermen på:
	</p>
<p>	<a name="capture-region"></a></p>
<h3>Knips område<kbd>Print</kbd></h3>
<p>
		Områdeknipsing let deg ta bilde av ein del av skjermen.<br><br />
		Etter at du har stara områdemodus vil du sjå eit kryss som syner musposisjonen<br />
		på skjermen. Klikk og hald inne venstre musknapp og teikn eit rektangel<br />
		rund den delen av skjermen du ønskjer å knipse. Når du slepp musknappen<br />
		blir det grøne området knipsa.
	</p>
<p class="hint">
		Du kan bruke <kbd>Mellomrom</kbd>-tasten for å bytte mellom områdemodus og<br />
		<a href="#capture-window">vindaugknipsing</a>.
	</p>
<p class="hint">
		Om du ønskjer å ta bilde av eit nøyaktig område, kan det ofte vera lettare<br />
		å angje eit litt større område enn du ønskjer, for så å <a href="#editor-crop">skjera til</a><br />
		bildet i Greenshot sin knipsfiksar.
	</p>
<p>	<a name="capture-last-region"></a></p>
<h3>Knips siste område <kbd>Shift</kbd> + <kbd>Print</kbd></h3>
<p>
		Om du alt har knipsa eit <a href="#capture-region">område</a> eller <a href="#capture-window">vindauge</a><br />
		tidlegare, kan du knipse same område/vindauge på nytt med dette valet.
	</p>
<p>	<a name="capture-window"></a></p>
<h3>Knips vindauge <kbd>Alt</kbd> + <kbd>Print</kbd></h3>
<p>
		Knipsar det aktive vindauget (vanlegvis det som ligg fremst).
	</p>
<p class="hint">
		Under <a href="#settings">Innstillingar</a> er det mogeleg å skru på<br />
		interaktivt val av vindauge, i kontrast til standardfunksjonen som knipsar det<br />
		aktive vindauget. Om dette er skrudd på, kan ein velje eit vindauge ved å<br />
		klikke på det. (Greenshot markerar området på same måte som i <a href="#capture-region">områdemodus</a>).<br><br />
		Om du ønskjer å knipse eit dotterelement (f.eks. innhaldet på ei nettside<br />
		utan rulleområde og menyar eller ei enkeltramme på ein nettstad som nyttar rammer,<br />
		kan du halde muspeikaren over vindauget og trykkje <kbd>PgDown</kbd>-tasten. Etter<br />
		dette kan du velje dotterelementa du ønskjer å knipse.
	</p>
<p class="hint">
		Om du ønskjer å knipse høgreklikkmenyar, stiller ting seg annleis: Snøggtasten for<br />
		å knipse vindauge vil ta bort menyen, og Greenshot sin eigen høgreklikkmeny vil<br />
		openbart gje same resultat. Om du ønskjer å knipse ein slik meny, gjer du det enkelt<br />
		ved å aktivere områdeknipsing med <kbd>Print</kbd>-tasten, og deretter bytte til<br />
		vindaugemodus med <kbd>Mellomrom</kbd>.
	</p>
<p>	<a name="capture-fullscreen"></a></p>
<h3>Knips fullskjerm <kbd>Control</kbd> + <kbd>Print</kbd></h3>
<p>
		Denne funksjonen tar eit bilde heile skjermen<br />
		(den aktive skjermen i fleirskjermoppsett).
	</p>
<p>	<a name="capture-ie"></a></p>
<h3>Knips Internet Explorer <kbd>Control</kbd> + <kbd>Shift</kbd> + <kbd>Print</kbd></h3>
<p>
		Med denne funksjonen kan du enkelt ta eit skjermbilde av ei open nettside i<br />
		Internet Explorer. Bruk Greenshot sin høgreklikkmeny for å velje IE-fane, eller<br />
		bruk snøggtasten for å knipse den aktive fana.
	</p>
<p>	<a name="editor"></a></p>
<h2>Å bruke knipsfiksaren</h2>
<p>
		Greenshot har eit innebygd, enkelt bilderedigeringsprogram (knipsfiksaren)<br />
		som har kjekke funksjonar for å notere eller teikne på eit skjermbilde.<br />
		Du kan òg markere eller sensurere delar av skjermknipset.
	</p>
<p class="hint">
		Greenshot sin knipsfiksar kan brukast til meir enn bare skjermknips;<br />
		du kan òg opne bildefiler frå disk eller frå utklyppstavla. Høgreklikk<br />
		Greenshot-ikonet i varselfeltet nedst til høgre og vel høvesvis<br />
		<em>Opne bilde frå fil</em> eller <em>Opne bilde frå utklyppstavle</em>.
	</p>
<p>	<!-- This has been changed in 1.0, if I'm not mistaken?</p>
<p class="hint">
		Standardinnstillinga er å opne knipsfiksaren for kvart bilde som blir knipsa.<br />
		Om du ikkje ønskjøer å bruke denne funksjonen kan du endre dette under<br />
		<a href="#settings">Innstillingar</a>.
	</p>
<p>	-->	</p>
<p>	<a name="editor-shapes"></a></p>
<h3>Teikne former</h3>
<p>
		Vel ei av teikneverktøya frå verktøypaletten på venstre side av knipsfiksaren<br />
		eller frå <em>Objekt</em>-menyen. Dei ymse verktøya har òg snøggtastar for å<br />
		effektivisere prosessen.<br><br />
		Dei ymse formene er: Rektangel <kbd>R</kbd>, ellipse <kbd>E</kbd>, line <kbd>L</kbd>,<br />
		pil <kbd>A</kbd> og frihandsline <kbd>F</kbd>.<br><br />
		Klikk og hald inne venstre museknapp for å teikne inn posisjon og storleik på<br />
		forma du ønskjer å teikne. Slepp musetasten når du er ferdig.
	</p>
<p>
		Du kan flytte eller endre storleik på eksisterande objekt med peikarverktøyet <kbd>Esc</kbd>.<br><br />
		Det finst visse val for dei ymse verktøya som endrar utsjånaden deira<br />
		(f.eks. linebreidde, linefarge og fyllfarge). Du kan endre desse eigenskapane<br />
		for eit eksisterande objekt, men også for det neste objektet du teiknar etter<br />
		å ha valt eit teikneverktøy.
	</p>
<p class="hint">
		Du kan redigere fleire objekt på same tid! For å velje fleire objekt, hald inne<br />
		<kbd>Shift</kbd>-tasten medan du vel objekta.
	</p>
<p class="hint">
		Om du ønskjer å teikne eit kvadrat eller ein sirkel, gjer du dette ved å halde<br />
		inne <kbd>Shift</kbd>-tasten medan du teiknar. Gjer du det same med line- eller<br />
		pilverktøyet, vil du teikne i vinkelretningar runda av til næraste 15°.<br />
		Du kan òg bruke <kbd>Shift</kbd> for å skalere eit objekt proporsjonalt.
	</p>
<p class="hint">
		Når du teiknar eller skalerar eit objekt kan du halde nede <kbd>Ctrl</kbd>-tasten<br />
		for å arbeide ut frå objektets midtpunkt, eksempelvis vil eit objekt som blir<br />
		forstørra vekse både med og mot muspekaren, forankra i midtpunktet.<br />
		(Dette er veldig nyttig om du til dømes ønskjer å teikne ei ellipse<br />
		rundt eit element på skjermknipset.)
	</p>
<p>	<a name="editor-text"></a></p>
<h3>Leggje til tekst</h3>
<p>
		Tekstverktøyet <kbd>T</kbd> minner mykje om dei andre <a href="#editor-shapes">formverktøya</a>.<br />
		Du teiknar opp ein tekstboks i ønskt storleik og skriv så inn teksten.<br />
		Dobbeltklikk boksen for å redigere eksisterande tekst.
	</p>
<p>	<a name="editor-highlight"></a></p>
<h3>Markering</h3>
<p>
		Med markeringsverktøyet <kbd>H</kbd> kan du definere eit markeringsområde<br />
		på same måte som du ville ha teikna ei <a href="#editor-shapes">form</a>.<br><br />
		På knappen lengst til venstre på verktøylina på toppen kan du bytte mellom<br />
		fleire forskjellige markeringstyper:
	</p>
<ul>
<li><em>Marker tekst</em>: Markerar tekst i ein ljos farge, som ein markørpenn</li>
<li><em>Marker område</em>: Framhevar det valte området ved å gjera utsida uskarp<a href="#hint-blur">*</a> og mørk</li>
<li><em>Gråtone</em>: Framhevar det valte området ved å konvertere utsida til gråtonar</li>
<li><em>Forstørr</em>: Forstørrar det valte området</li>
</ul>
<p>	<a name="editor-obfuscate"></a></p>
<h3>Sensurering</h3>
<p>
		Om skjermknipset inneheld sensitiv data, t.d. kontonummer, namn, passord eller<br />
		andlet kan det vera lurt å sensurere bildet. Bruk sensureringsverktøyet <kbd>O</kbd><br />
		på same måte som <a href="#editor-highlight">markeringsverktøyet</a>.<br><br />
		Dei forskjellige sensureringsmåtane er:
	</p>
<ul>
<li><em>Pikseler</em>: Aukar pikselstorleiken i merkt område</li>
<li><em>Gjer uskarpt</em><a href="#hint-blur">*</a>: Gjer eit område uskarpt</li>
</ul>
<p>	<a name="hint-blur"></a></p>
<p class="hint">
		* Avhengig av kor kraftig datamaskina di er, kan Greenshot sin knipsfiksar<br />
		oppføre seg treigt når ein nyttar uskarp-funskjonen. Om du syns at programmet<br />
		reagerar seint etter å ha aktivert funksjonen, prøv å skru ned <em>Kvalitet på<br />
		førehandssyning</em> på verktøylina eller minsk verdien for <em>Uskarp-radius</em>.<br><br />
		Om uskarp-ytelsen framleis er plagsom, bør du vurdere pikseler-effekten i staden.
	</p>
<p>	<a name="editor-crop"></a></p>
<h3>Skjere skjermknipset</h3>
<p>
		Om du bare treng ein del av skjermbildet du har knipsa, kan du bruke<br />
		skjereverktøyet <kbd>C</kbd> for å kutte det til ønskt storleik.<br><br />
		Teikn eit rektangel for å markere området du ønskjer å halde fram med,<br />
		du kan òg endre storleiken på dette området som med andre objekt..<br><br />
		Når du er nøgd med utklyppet, trykk <em>Stadfest</em>-knappen eller <kbd>Enter</kbd>.<br />
		Du kan avbryte operasjonen ved å trykkje <em>Avbryt</em> eller <kbd>Esc</kbd>.
	</p>
<p class="hint">
		<em>Auto-skjer</em>: Om du vil klyppe vekk ein einsfarga kant rundt skjermknipset,<br />
		kan du bruke <em>Auto-skjer</em> frå <em>Rediger</em>-menyen. Greenshot vel då<br />
		automatisk området du vil skjera vekk.
	</p>
<p>	<a name="editor-adding-graphics"></a></p>
<h3>Setje grafikk inn i skjermknips</h3>
<p>
		Du kan enkelt leggje til grafikk og bilde i eit skjermknips ved å dra bildefiler<br />
		inn i knipsfiksaren (dra-og-slepp). Du kan òg leggje til knips av andre vindauge<br />
		ved å bruke <em>Sett inn vindauge</em> frå <em>Rediger</em>-menyen. Du vil då<br />
		få opp ei liste over tilgjengelege vindauge som kan importerast.
	</p>
<p>	<a name="editor-reuse-elements"></a></p>
<h3>Gjenbruk av teikna element</h3>
<p>
		Om du ønskjer å gjere den same eller liknande jobben på fleire skjermknips<br />
		(t.d. eit tekstfelt med nettlesartype og versjon, eller sensurering av det<br />
		same elementet på fleire knips) kan du enkelt bruke objekt på nytt.<br><br />
		Vel <em>Lagre objekt til fil</em> frå <em>Objekt</em>-menyen for å lagre<br />
		det eksisterande sett av objekt for seinare bruk. Ein kan då enkelt bruke<br />
		<em>Last inn objekt...</em> for å importere objekta til eit anna skjermknips.
	</p>
<p>	<a name="editor-export"></a></p>
<h3>Eksportere skjermknipset</h3>
<p>
		Når du er ferdig med å redigere skjermknipset i knipsefiksaren, kan du eksportere<br />
		resultatet på fleire måtar. Du finn dei ymse vala på <em>Fil</em>-menyen, den øvste<br />
		knapperada eller via snøggtastar:
	</p>
<ul>
<li><em>Lagre</em> <kbd>Control</kbd> + <kbd>S</kbd>: Lagrar bildet til ei fil, og overskriv førre utgåve om du bare har gjort endringar</li>
<li><em>Lagre som...</em> <kbd>Control</kbd> + <kbd>Shift</kbd> + <kbd>S</kbd>: Let deg alltid velje kor du vil lagre fila, også når du alt har lagra ho før</li>
<li><em>Kopier knips til utklyppstavla</em> <kbd>Control</kbd> + <kbd>Shift</kbd> + <kbd>C</kbd>: Gjer knipset tilgjengeleg for andre Windows-program via <em>Lim inn</em>-funksjonen</li>
<li><em>Skriv ut...</em> <kbd>Control</kbd> + <kbd>P</kbd>: Sender skjermknipset til ein skrivar</li>
<li><em>Send med e-post</em> <kbd>Control</kbd> + <kbd>E</kbd>: Lagar ein ny melding i standard e-postprogram og legg knipset som eit vedlegg</li>
</ul>
<p class="hint">
		Når du har lagra bildefila frå knipsfiksaren, kan du enkelt kopiere filplasseringa<br />
		til utklyppstavla eller opne mappa i utforskaren ved å høgreklikke på <em>statuslina</em><br />
		nedst i programmet.
	</p>
<p>	<a name="settings"></a></p>
<h2>Innstillingsdialogen</h2>
<p>	<a name="settings-general"></a></p>
<h3>Generelle innstillingar</h3>
<ul>
<li><em>Språk</em>: Språket du ønskjer å bruke i Greenshot.<br><br />
			Du kan laste ned tilleggsspråk <a target="_blank" href="/downloads/">her</a>. </li>
<li><em>Start Greenshot med systemet</em>: Aktiverar Greenshot når Windows startar</li>
<li><em>Snøggtastar</em>: Redigerar snøggtastane knytt til skjermknipsing</li>
<li><em>Bruk systemets standardproxy</em>: Om dette er huka av, vil Greenshot bruke systemet sin proxyserver for å sjå etter oppdateringar.</li>
<li><em>Oppdateringsfrekvens</em>: Greenshot kan sjå om nye utgåver er tilgjengelege på verdsveven. Her vel du kor ofte dette skal skje, eller du kan stoppe kontrollen ved å velje 0 dagar.</li>
</ul>
<p>	<a name="settings-capture"></a></p>
<h3>Knipsinnstillingar</h3>
<ul>
<li><em>Knips muspeikaren</em>: Vel om du vil ha muspeikaren med i skjermknipset.<br />
				Peikaren blir lagt til som eit eige objekt som du kan skalere og flytte i knipsfiksaren.</li>
<li><em>Spel av lukkarlyd</em>: Høyrleg indikasjon på at skjermknipset blir tatt.</li>
<li><em>Syn varsel</em>: Skrur av og på varsel<br />
	<!--- What kind of notifications? The en-US help file isn't clear on this, in fact it doesn't mention the notifications at all! --></p>
<li><em>Forseinking før skjermknips</em>: Her kan du leggje til ei forseinking<br />
				mellom stadfesting og tidspunktet skjermknipset blir tatt.</li>
<li><em>Bruk interaktiv vindaugsknipsing</em>: Aktiverar mogelegheiten for å velje<br />
				vindauge som knipsast, i kontrast til standardvalet som automatisk knipsar<br />
				det aktive vindauget. Sjå <a href="#capture-window">vindaugsknipsing</a>.</li>
<li>
			<em>Vindaugsstil</em>: Om du nyttar Windows Vista eller 7 med eit Aero-tema<br />
			(gjennomsynlege element) kan du velje korleis element som er synleg <em>gjennom</em><br />
			vindauget blir knipsa.</p>
<ul>
<li><em>Automatisk</em>: Let Greenshot avgjere gjennomsynlegheit.</li>
<li><em>Som synt</em>: Gjennomsynlege rammer blir knipsa nett som på skjermen.</li>
<li><em>Bruk standardfarge</em>: Gjev ein svart bakgrunn bak gjennomsynlege områda.</li>
<li><em>Use custom color</em>: Gjev ein eigendefinert farge bak dei gjennomsynlege områda.</li>
<li><em>Hald på gjennomsynlegheit</em>: Gjennomsynlege område blir knipsa utan bakgrunn,<br />
						og blir synt med ein rutete bakgrunn i knipsfiksaren. Mønsteret blir ikkje<br />
						synleg i utfila. Utfila må lagrast i PNG-format for å halde på gjennomsynlegheita.</li>
</ul>
</li>
<li><em>Internet Explorer-knipsing</em>: Gjer klart for enkel knipsing frå Internet Explorer.</li>
<li><em>Tilpass knipsfiksaren til utklyppsstorleiken</em>: Endrar storleiken på knipsfiksaren i høve til skjermknipset.</li>
</ul>
<p>	<a name="settings-output"></a></p>
<h3>Utformat-innstillingar</h3>
<ul>
<li><em>Lagringsplassering</em>: Angjev standardmappa skjermknips blir lagra i.</li>
<li><em>Regel for filnamn</em>: Definerer ein regel for automatiske filnamn ved direktelagring.<br />
				Klikk <em>?</em>-knappen for å få ei oversikt over gyldige felt.</li>
<li><em>Kopier filplasseringa til utklyppstavla kvar gong eit bilde blir lagra</em>:<br />
				Når du lagrar eit bilde frå Greenshot vil mappe- og filnamn bli kopiert til<br />
				utklyppstavla, og kan enkelt limast inn i andre program for lett tilgang.</li>
<li><em>JPEG-kvalitet</em>: Avgjer vektinga mellom filstorleik og kvalitet når du<br />
				lagrar bilde i JPEG-format. Standardkomprimering er 80%.</li>
<li><em>Syn kvalitetsdialog kvar gong eit bilde blir lagra</em>: Gjer det mogeleg å<br />
				velje komprimering ved kvar lagring.</li>
<li><em>Reduser totalt fargetal til maksimum 256</em>: Vil alltid lagre JPEG-bildet<br />
				med maksimum 256 fargar (8-bit). Dette vil ofte redusere kvaliteten.</li>
</ul>
<p>	<a name="settings-output"></a></p>
<h3>Målinnstillingar</h3>
<ul>
<li><em>Dynamisk målveljar</em>: Syner ein meny rett etter knipset er tatt,<br />
				der du sjølv kan velje kor du vil nytte skjermknipset.</li>
<li><em>Andre mål</em>: Om den dynamiske målveljaren er deaktivert kan du velje ein<br />
				eller fleire målprogram eller -funksjonar som blir brukt til å ta imot<br />
				eller vidareformidle skjermknipset. Om du kryssar av for fleire mål<br />
				vil Greenshot jobbe seg nedover lista og eksportere til alle måla.</li>
</ul>
<p>	<a name="settings-printer"></a></p>
<h3>Utskriftsinnstillingar</h3>
<ul>
<li><em>Forminsk bildet til arkstorleiken</em>: Om skjermknipset skulle vera større<br />
		enn arket som er valt, skalerer Greenshot ned bildet så det passar innanfor margane.</li>
<li><em>Forstørr bildet til arkstorleiken</em>: Om bildet er mindre enn arket, vil<br />
				Greenshot skalere bildet til å fylle heile arket proporsjonalt.</li>
<li><em>Roter bildet til arkretninga</em>: Snur bilde i breiddeformat på høgkant.</li>
<li><em>Sentrer bildet på arket</em>: Plasserar bildet på midten av arket.</li>
<li><em>Skriv ut dato/tid som botntekst</em>: Dato og tidspunkt for utskrift blir<br />
				plassert nedst på arket.</li>
<li><em>Skriv ut med inverterte fargar</em>: Skriv ut bildet som eit negativ.<br />
				Spesielt nyttig for t.d. kvit tekst på svart bakgrunn (for å spare blekk/toner).</li>
<li><em>Skriv ut i gråtonar</em>: Utskrifta blir skrive ut i gråtonar uavhengig av<br />
				skrivar- og originalinnstilingar.</li>
</ul>
<p>	<a name="settings-plugins"></a></p>
<h3>Tilleggsinnstillingar</h3>
<p>
		Syner ei liste over installerte tillegg. Vel eit tillegg frå lista og klikk<br />
		<em>Konfigurer</em> for å justere tilleggspesifikke innstillingar.
	</p>
<p>	<a name="help"></a></p>
<h2>Lyst til å hjelpe?</h2>
<p>
		I augneblinken treng me ikkje hjelp i utviklinga. Det er likevel fleire ting<br />
		du kan gjere for å støtte opp rundt Greenshot og utviklarane.<br />
		På førehand takk! :)
	</p>
<p>	<a name="help-donate"></a></p>
<h3>Vurder ein donasjon</h3>
<p>
		Me legg ned mykje arbeid i Greenshot, og brukar mykje tid på å utvikle eit godt<br />
		stykke open kjeldekode utan kostnad for sluttbrukaren. Om programmet gjer deg<br />
		meir produktiv, sparar deg eller selskapet ditt for mykje tid og pengar eller<br />
		du rett og slett likar ideen om open kjeldekode er du velkomen til å ære innsatsen<br />
		vår med ein donasjon.<br><br />
		På heimesida vår finn du informasjon om korleis du kan støtte utviklarane:<br><br />
		<a target="_blank" href="/support/">http://getgreenshot.org/support/</a>
	</p>
<p>	<a name="help-spread"></a></p>
<h3>Spre ryktet</h3>
<p>
		Om du likar Greenshot, syt for at andre får greie på det! Fortel vener, kollegaer og<br />
		fygljarar på sosiale media om Greenshot!<br><br />
		Gje tilbakemelding på Greenshot på relevante programvaresider eller legg ei<br />
		lenkje til nettsida vår (http://getgreenshot.org) på bloggen eller heimesida di.
	</p>
<p>	<a name="help-translate"></a></p>
<h3>Send inn omsetjing</h3>
<p>
		Er ikkje Greenshot tilgjengeleg på ditt føretrekte språk? Om du kjenner deg<br />
		i stand til å omsetje programmet er du meir enn velkomen!<br />
		Om du er registrert på sourceforge.net kan du sende inn omsetjingar til vår<br />
		<a target="_blank" href="https://sourceforge.net/tracker/?group_id=191585&atid=1368020">omsetjings-tracker</a>.<br><br />
		Kontroller fyrst om det alt finst ei omsetjing på<br />
		<a target="_blank" href="/downloads/">nedlastingssida</a>.<br />
		Sjekk òg <a href="https://sourceforge.net/tracker/?group_id=191585&atid=1368020">omsetjings-trackeren</a>,<br />
		då den kan innehalde ein omsetjing under arbeid eller diskusjon.<br><br />
		Ver merksam på at me bare tilbyr omsetjingar på nedlastingssida vår om den har<br />
		blitt sendt inn gjennom ein sourceforge.net-konto. Sidan me sannsynlegvis ikkje<br />
		forstår omsetjinga di er det fint om andre sourceforge-brukarar kan kontakte deg<br />
		om endringar eller forbetringar i samband med til dømes nye programversjonar.
	</p>
