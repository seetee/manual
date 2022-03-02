<header style="float:right;">
  <img src="https://app.tcstenungsund.se/themes/tcapp/images/tc-s-trans.svg" style="width:5em;" />
</header>

# Webbutveckling 2: Drupal sub-theme

*Med hjälp av kunskaper du redan har, som exempelvis CSS, Bootstrap, Docker och Drupal, skall du nu skapa ditt första sub-theme till Drupal. Verktygen du använder är Docker, Drupal 9 och Bootstrap 5 Barrio.*

## Förutsättningar

Enskild uppgift.

### Resurser
* [Drupal 8 Beginner](https://www.youtube.com/playlist?list=PLpVC00PAQQxHzlDeQvCNDKkyKRV1G3_vT)
* ["How to Create a Sub Theme in Drupal 8 or 9"](https://youtu.be/hPXUn_D2-lE)
* ["How to Convert an HTML Template to a Drupal 8 Theme"](https://youtu.be/xdifbN3y5hU)
* [Barrio Installation](https://www.drupal.org/docs/8/themes/barrio-bootstrap-4-drupal-89-theme/bootstrap-barrio-installation/installation)
* [Creating a custom Barrio sub-theme manually](https://www.drupal.org/docs/8/themes/barrio-bootstrap-4-drupal-89-theme/bootstrap-barrio-installation/creating-a-custom-barrio-sub-theme#s-create-manually)
* [Drupal.org Theming Drupal](https://www.drupal.org/docs/theming-drupal)
* [docker-compose.yml (version 2.0)](https://raw.githubusercontent.com/seetee/docker/version2.0/drupal/docker-compose.yml)

## Uppgiftsbeskrivning

##### Planering

Bestäm ett syfte för sidan (business objective), samt några Call to Actions. Definiera färgschema, typsnitt samt bildspråk. Leta upp bilder och ikoner du har laglig rätt att använda i projektet. Skapa wireframes, moodboards och liknande om det behövs. Inkludera bakgrundsbilder/mönster, subtila strukturer, typsnitt, färger och allt annat du lärt dig när det gäller att bygga en webbplats.

##### Infrastruktur

Installera Docker och Drupal. Följ instruktionen i ["Workspace Setup"](https://raw.githubusercontent.com/seetee/manual/master/weuweb02/src/weuweb02_-_workspace_setup.pdf).

Installera temat [Barrio](https://www.drupal.org/project/bootstrap_barrio)  samt modulen [Devel](https://www.drupal.org/project/devel). Hitta även minst 1 modul till som du kan använda för att visa upp någonting coolt på förstasidan av din webbplats. Generera exempeldata med Devel.

##### Skapa ditt sub-theme

Följ de officiella instruktionerna och skapa ett eget sub-theme till Barrio.

För att skriva CSS, skapa dokumentet style.css i katalogen CSS i din sub-theme-katalog. Högerklicka sedan i webbläsaren på det element du vill ändra och välj "Inspect Element". Konstruera en selektor av klasser och element, till exempel ".region-secondary-menu h2" för att ändra underrubriken över sekundärmenyn. Lägg till selektorn och skriv dina CSS-regler ditt CSS-dokument.

> Tips! Ändra inga färger i inställningarna för ditt sub-theme i Drupal. Då uppstår det en konflikt med ditt CSS-dokument.

Kontrollera sådant som kontrast och [A11y](https://developer.mozilla.org/en-US/docs/Web/Accessibility).

##### Överkurs

Siktar du på högre betyg, skapa en egen template-fil för förstasidan av din site. (Detta innebär att du kommer i kontakt med både [YAML](https://en.wikipedia.org/wiki/YAML) och [Twig](https://en.wikipedia.org/wiki/Twig_(template_engine))).

<div style="page-break-after: always;">&nbsp;</div>

## Förväntat resultat

Ett komplett, snyggt och funktionellt sub-theme till Drupal. Det skall gå att installera på en annan Drupal-instans, och inte direkt vara igenkänningsbart som Drupal.

### Vilka filer?

En 7z-fil med din kompletta sub-theme-katalog så som den sett ut om den tankats ned från drupal.org.

Ett screenshot av förstasidan på din site.

### Var skall de lämnas in?

På vår lärplattform [It's Learning](https://stenungsund.itslearning.com/) finns ett kursrum med samma namn som den här kursen, under *Innehåll* / *Inlämningar* hittar du en inlämningskatalog med samma namn som den här uppgiften.

---

<footer style="columns: 2">
  <p>Detta dokument är licenserat under Creative Commons BY-SA. Bilder och fotografier tillhör respektive upphovsman, och befinner sig inte nödvändigtsvis under en Creative Commons-licens.</p>
  <p>Dokumentet är skapat och uppdaterat av Kenneth Frantzen (@seetee på GitHub).</p>
</footer>
