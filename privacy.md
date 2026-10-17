---
layout: default
title: Privacy / Personvern
---

# Privacy policy / Personvernerklæring

[English](#english) · [Norsk nynorsk](#nynorsk)

<div lang="en" markdown="1">

## English {#english}

**Publication draft — not ready to publish.** Before publication, add the developer/controller’s legal name and contact details, effective date and public policy URL. Confirm the legal bases, support-mail retention and the hosting provider’s practices. Remove this notice only after completing that review.

Effective date: to be supplied before publication.<br>
Developer and controller for Ferjo: to be supplied.<br>
Privacy and support contact: to be supplied.

### What Ferjo does

Ferjo displays ferry timetables and service messages. It has no user accounts, advertising or analytics SDKs. There is no developer-operated server receiving your favourites or location in the current application. Some information leaves your device when the app or its widgets contact external services.

### Information on your device

Ferjo stores favourites, preferences and the identifier of the automatically selected favourite locally. The app and widgets share relevant settings and timetable caches through an Apple App Group. Cached schedules include terminal identifiers, service dates, departure information and fetch times. Search text is matched against the local route catalogue. Ferjo does not persist your GPS coordinates or a location history.

Preferences and favourites remain until changed or removed. Timetable records are usable for up to seven days after retrieval, with a limit of 120 records and a service-date window from yesterday through 14 days ahead. Pruning occurs when cache data is written; expired files may remain longer when the app is unused. Temporary location, driving estimates and service-message caches are held in memory. System backups may retain application data according to your Apple settings.

### Optional location

With your permission, Ferjo uses location to show nearby connections, automatically select your nearest favourite and estimate driving time to a terminal. Nearby selection happens on your device. The selected favourite identifier, rather than your coordinates, is shared with widgets. A timetable request can still reveal which terminal interests you.

For driving estimates, Apple Maps receives your starting location and the terminal destination through MapKit. Ferjo requests location while in use; it does not implement background location tracking. You can deny or revoke access in iOS Settings and continue browsing timetables and choosing favourites manually. Location-based features will be unavailable or use their existing fallback behaviour.

### Entur

The app and widgets send HTTPS requests directly to Entur for timetables and service messages. These requests contain stop identifiers, dates and query parameters, and identify the application as `ferjo-ios`. Ferjo does not include GPS coordinates, an account identifier or the complete favourites list. Entur also receives network metadata, including your IP address.

Entur’s API terms state that it logs IP addresses, request paths and the application-identification header for operations and security. Entur AS controls these logs and normally keeps them for 14 months, with longer retention for security or incident investigations. See [Entur’s API terms](https://developer.entur.no/terms-of-service) and [privacy information](https://om.entur.no/personvern/), including how to contact its data protection officer.

### Apple services and external links

Core Location supplies location according to your device permissions. Apple Maps processes driving-time requests. If you choose directions, Ferjo opens Apple Maps with the destination. Apple controls its own processing and retention; see [Apple Maps and privacy](https://www.apple.com/legal/privacy/data/en/apple-maps/).

External links open only when you choose them. The destination website or application may receive network metadata and apply its own privacy practices. This policy does not promise that external providers keep no information.

### Deleting data and your choices

You can remove favourites in Ferjo and change preferences in Settings. To remove the installed app’s local data, use Delete App in iOS Settings, rather than Offload App, which retains data. Shared-container and backup copies are managed by iOS; removing a widget alone does not erase favourites. Manage backups separately in your Apple settings. Deleting Ferjo does not delete logs already retained by Entur or Apple.

### Contact and privacy rights

A developer contact for questions or requests concerning Ferjo’s processing must be supplied before publication; no contact address is configured yet. If you contact support, the recipient receives the message and contact information you choose to provide. The support channel and its retention policy must be finalised before publication. Depending on applicable law, you may request access, correction, erasure or restriction, object to processing, or request portability. You may also complain to your data protection authority, such as Norway’s Datatilsynet. Requests concerning Entur’s independent logs should be directed to Entur.

This policy will be updated when Ferjo’s practices change. The published version will show its effective date.

### This website

This static website is hosted on GitHub Pages. Its source adds no analytics, tracking scripts or cookies. GitHub documents that Pages logs and stores visitors’ IP addresses for security, including when visitors are not signed in. Hosting is therefore not a promise that no information is collected. GitHub controls its own retention and processing; see [GitHub Pages data collection](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages#data-collection) and the [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). This site has no support form; contacting support will use the channel supplied before publication.

</div>

<div lang="nn" markdown="1">

## Norsk nynorsk {#nynorsk}

**Utkast — ikkje klart for publisering.** Før publisering må det juridiske namnet og kontaktopplysningane til utviklaren/den behandlingsansvarlege, datoen erklæringa gjeld frå og den offentlege nettadressa fyllast inn. Avklar behandlingsgrunnlag, lagringstid for førespurnader til brukarstøtte og praksisen til nettleverandøren. Fjern denne merknaden først når gjennomgangen er fullført.

Gjeld frå: må fyllast inn før publisering.<br>
Utviklar og behandlingsansvarleg for Ferjo: må fyllast inn.<br>
Kontakt for personvern og brukarstøtte: må fyllast inn.

### Kva Ferjo gjer

Ferjo viser ferjeruter og driftsmeldingar. Appen har ingen brukarkontoar, reklame eller analyse-SDK-ar. Den noverande appen sender ikkje favorittane eller posisjonen din til ein tenar driven av utviklaren. Nokre opplysningar forlèt eininga når appen eller widgetane kontaktar eksterne tenester.

### Opplysningar på eininga di

Ferjo lagrar favorittar, innstillingar og identifikatoren til den automatisk valde favoritten lokalt. Appen og widgetane deler relevante innstillingar og mellomlagra rutetider gjennom ei Apple-appgruppe. Mellomlagra rutetider inneheld kaiidentifikatorar, datoar, avgangsinformasjon og tidspunkt for henting. Søketekst vert samanlikna med den lokale rutekatalogen. Ferjo lagrar ikkje GPS-koordinatane dine eller ein posisjonshistorikk på disk.

Innstillingar og favorittar vert verande til dei vert endra eller fjerna. Mellomlagra rutetider kan brukast i opptil sju dagar etter henting, med ei grense på 120 oppføringar og datoar frå i går til 14 dagar fram i tid. Opprydding skjer når nye data vert lagra; utgåtte filer kan liggje lenger når appen ikkje vert brukt. Mellombels posisjon, køyretidsestimat og driftsmeldingar vert haldne i minnet. Systemet sine tryggingskopiar kan innehalde appdata i samsvar med Apple-innstillingane dine.

### Valfri posisjonstilgang

Med løyve frå deg brukar Ferjo posisjonen til å vise samband i nærleiken, velje den næraste favoritten automatisk og rekne ut køyretida til ein ferjekai. Utvalet av nære samband skjer på eininga. Widgetane får identifikatoren til den valde favoritten, ikkje koordinatane dine. Ein førespurnad om rutetider kan likevel vise kva kai du er interessert i.

For køyretidsestimat får Apple Kart startposisjonen din og ferjekaien som reisemål gjennom MapKit. Ferjo ber om posisjon medan appen er i bruk; appen sporar ikkje posisjonen i bakgrunnen. Du kan avslå eller trekkje tilbake tilgangen i iOS-innstillingane og framleis sjå rutetider og velje favorittar manuelt. Posisjonsbaserte funksjonar vert då utilgjengelege eller brukar dei eksisterande reservevala.

### Entur

Appen og widgetane sender HTTPS-førespurnader direkte til Entur for rutetider og driftsmeldingar. Førespurnadene inneheld stoppidentifikatorar, datoar og søkjeparameter, og identifiserer appen som `ferjo-ios`. Ferjo legg ikkje ved GPS-koordinatar, ein kontoidentifikator eller heile favorittlista. Entur får òg nettverksmetadata, mellom anna IP-adressa di.

API-vilkåra til Entur seier at IP-adresser, førespurnadsstiar og appidentifikatoren vert logga for drift og tryggleik. Entur AS er ansvarleg for desse loggane og lagrar dei normalt i 14 månader, med lengre lagring ved tryggleiks- eller hendingsundersøkingar. Sjå [API-vilkåra til Entur](https://developer.entur.no/terms-of-service) og [personverninformasjonen](https://om.entur.no/personvern/), som òg forklarer korleis du kontaktar personvernombodet.

### Apple-tenester og eksterne lenkjer

Core Location gjev posisjon i samsvar med løyva på eininga. Apple Kart handsamar førespurnader om køyretid. Når du vel vegvising, opnar Ferjo Apple Kart med reisemålet. Apple styrer si eiga handsaming og lagring; sjå [Apple Kart og personvern](https://www.apple.com/legal/privacy/data/en/apple-maps/).

Eksterne lenkjer vert berre opna når du vel dei. Nettstaden eller appen du opnar, kan få nettverksmetadata og ha eigne personvernreglar. Denne erklæringa lovar ikkje at eksterne leverandørar ikkje lagrar opplysningar.

### Sletting og vala dine

Du kan fjerne favorittar i Ferjo og endre vala dine i Innstillingar. Bruk Slett app i iOS-innstillingane for å fjerne lokale data frå den installerte appen, ikkje Fjern app utan å slette data. iOS styrer kopiar i delte lagringsområde og tryggingskopiar; å fjerne berre ein widget slettar ikkje favorittane. Administrer tryggingskopiar separat i Apple-innstillingane. Sletting av Ferjo slettar ikkje loggar som Entur eller Apple allereie har lagra.

### Kontakt og personvernrettar

Ein utviklarkontakt for spørsmål eller førespurnader om Ferjo si handsaming må opplysast før publisering; inga kontaktadresse er sett opp enno. Kontaktar du brukarstøtte, får mottakaren meldinga og kontaktopplysningane du vel å sende. Kontaktkanalen og lagringstida må avklarast før publisering. Etter gjeldande lov kan du ha rett til innsyn, retting, sletting, avgrensing, å protestere mot handsaming eller å få utlevert opplysningar. Du kan òg klage til personvernstyresmakta, til dømes Datatilsynet i Noreg. Førespurnader om Entur sine eigne loggar bør rettast til Entur.

Erklæringa vert oppdatert når praksisen til Ferjo endrar seg. Den publiserte utgåva vil vise datoen ho gjeld frå.

### Denne nettstaden

Denne statiske nettstaden ligg på GitHub Pages. Kjeldekoden legg ikkje til analyseverktøy, sporingsskript eller informasjonskapslar. GitHub opplyser at Pages loggar og lagrar IP-adressene til vitjande for tryggleiksføremål, òg når dei ikkje er innlogga. Dette er difor ikkje ein lovnad om at ingen opplysningar vert samla inn. GitHub styrer si eiga lagring og handsaming; sjå [datainnsamling på GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages#data-collection) og [personvernerklæringa til GitHub](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). Nettstaden har ikkje noko kontaktskjema; brukarstøtte vil bruke kontaktkanalen som må opplysast før publisering.

</div>
