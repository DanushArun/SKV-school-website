# S.K. Velayutham School Website

A single-page English/Tamil school website for S.K. Velayutham Higher Secondary School,
Kurinjipadi. The repository contains the page, school imagery and design/release notes.

## Page structure

The page introduces the school, education stages, sports and academics, campus/events,
facilities, admissions and contact information. English and Tamil strings are embedded
alongside the corresponding UI elements.

## Preview locally

```bash
git clone https://github.com/DanushArun/SKV-school-website.git
cd SKV-school-website
python3 -m http.server 8080
```

Open `http://localhost:8080`. There is no dependency installation or build step.
Remote scripts, fonts and other externally linked resources still need network access.

## Repository map

- [index.html](index.html): markup, styling references and page behavior.
- [images](images): school photographs and logo.
- [REDESIGN.md](REDESIGN.md): design notes.
- [PRODUCTION_READY.md](PRODUCTION_READY.md): recorded release notes.

## Publishing and evidence

Serve the static files through a static host. Review Tamil/English switching, navigation,
mobile layout and enquiry behavior in a browser before releasing an edit.
School history, admissions dates and institutional claims are content supplied by the site;
this documentation review does not independently verify them.

Tracked files and local preview instructions were reviewed. No browser acceptance test or
live deployment check was performed. The repository has no backend application or automated
test suite, so an enquiry form UI alone is not proof of delivered admissions enquiries.
