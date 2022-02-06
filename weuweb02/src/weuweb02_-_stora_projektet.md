<header style="float:right;">
  <img src="https://app.tcstenungsund.se/themes/tcapp/images/tc-s-trans.svg" style="width:5em;" />
</header>

# Webbutveckling 2: Stora projektet

*Nu är det dags att tillämpa kunskaper från både Webbutveckling 1 och 2. I en stor grupp skall ni samarbeta och omvandla en gammal och "mindre snygg" webbplats till en modern och lättnavigerad produkt Det skall finnas tydlig och tilltalande dokumentation, ett Drupal subtheme baserat på Bootstrap och såklart en färdig webbplats.*

## Förutsättningar

Gruppuppgift.

### Resurser

* [Docker](https://www.docker.com/) tillsammans med filen [docker-compose.yml v.2.0](https://github.com/seetee/docker/tree/version2.0/drupal)
* [Trello](https://trello.com/)
* [GitHub](https://github.com/)
* [HTTrack](https://www.httrack.com/)
* En editor som [Atom](https://atom.io/), [VSCodium](https://vscodium.com/) eller [Notepad++](https://notepad-plus-plus.org/)

## Uppgiftsbeskrivning

##### Ansvarsområden

I denna uppgift skall alla delta i att skriva kod, bidra med dokumentation och idéer. Men ni har också ett specifikt ansvarsområde som ni fått er tilldelade. Det innebär inte att ni endast skall göra det som ingår i ansvarsområdet, eller att endst ni skall göra uppgifter som faller under ansvarsområdet. Vad det innebär är att du bär ansvaret. Det är du som kommer få skulden om uppgiften inte utförs.

Ansvarsområdena är Arbetsledare, Gitmaster, Dokumentation, Data, Designsystem, Infrastruktur.

##### Regelbundna uppgifter

Börja varje lektion med en 5-10 minuter lång snabbgenomgång av hur arbetsläget ser ut. Låt var och en svara kort (c:a 1 mening) på frågorna "Vad gjorde jag förra gången?", "Vad skall jag göra idag?" och "Vilka problem ser jag?".

Varannan vecka skickar Dokumentationsansvariga in en rapport på It's där de kort redogör för vilka uppgifter som slutförts under de senaste fjorton dagarna, samt om det finns några problem som hindrar att gruppens arbete går vidare.

##### Större moment

Uppdatera (eventuellt gör om) logotypen.

Bestäm färgschema, typografi och liknande.

Skapa ett design system.

Gör en sitemap. Basera denna på den gamla sidans innehåll, fast ta hänsyn till nya content types och taxonomier.

> Tips! Ni behöver inte en "Hem"-länk eller en "Om oss"-sida. Denna informationen kan med fördel visas för besökaren genom att de först hamnar på en nyhetssida och att webbplatsen har en informativ footer.

Ta fram en Bootstrap 5 Theme-fil.

Bygg ett Drupal Bootstrap 5 (Barrio) subtheme.

Använd [YAML](https://en.wikipedia.org/wiki/YAML) och [Twig](https://en.wikipedia.org/wiki/Twig_(template_engine) för att skapa väl integrerade template-filer till webbplatsen. Förstasidan skall ha en egen template-fil, men det är upp till er vilka övriga sidor som behöver det.

Konfigurera Drupal med korrekta content types, taxonomier och liknande.

Migrera data från den gamla webbplatsen till er nya.

<div style="page-break-after: always;">&nbsp;</div>

## Förväntat resultat

En layoutmässigt och grafiskt tilltalande dokumentation som beskriver färger, typsnitt, logotyper och andra grundkomponenter ni använder till sidan.

En .7z-fil som innehåller ett installeringsbart subtheme.

Komplett sida.

Alla skall ha bidragit till ert repocitory med vettiga commits, samt hanterat minst ett innehållsrikt kort på Trello i veckan.


### Vilka filer?

En 7z-fil med din kompletta subtheme-katalog så som den sett ut om den tankats ned från drupal.org.

Ett screenshot av förstasidan på din site.

### Var skall de lämnas in?

På vår lärplattform [It's Learning](https://stenungsund.itslearning.com/) finns ett kursrum med samma namn som den här kursen, under *Innehåll* / *Inlämningar* hittar ni en inlämningskatalog med samma namn som den här uppgiften.

---

<footer style="columns: 2">
  <p>Detta dokument är licenserat under Creative Commons BY-SA. Bilder och fotografier tillhör respektive upphovsman, och befinner sig inte nödvändigtsvis under en Creative Commons-licens.</p>
  <p>Dokumentet är skapat och uppdaterat av Kenneth Frantzen (@seetee på GitHub).</p>
</footer>
