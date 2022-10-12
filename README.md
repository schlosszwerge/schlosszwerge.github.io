# Internetauftritt des Vereins - Die Schlosszwerge e.V.

[![pages-build-deployment](https://github.com/schlosszwerge/schlosszwerge.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/schlosszwerge/schlosszwerge.github.io/actions/workflows/pages/pages-build-deployment)
[![Jekyll](https://img.shields.io/badge/jekyll-%3E%3D%203.7-blue.svg)](https://jekyllrb.com/)
[![Ruby gem](https://img.shields.io/gem/v/minimal-mistakes-jekyll.svg)](https://rubygems.org/gems/minimal-mistakes-jekyll)
[![Tip Me via PayPal](https://img.shields.io/badge/PayPal-tip%20me-green.svg?logo=paypal)](https://www.paypal.me/Lenhardt1987)

[Minimal Mistakes Jekyll theme](https://mmistakes.github.io/minimal-mistakes/)

# Inhalt

**Links:**
* [Git-Ccheatsheet](http://git-cheatsheet.com/)
* [Markdown](https://www.markdownguide.org/cheat-sheet/)

## Neue Seite anlegen

Im Ordner **_pages** die entsprechende Seite im [Markdown](https://www.markdownguide.org/cheat-sheet/) format erstellen. 

Die Seite dann unter [_data/navigation.yml](_data/navigation.yml) einbinden.

## Neuen Blog Post anlegen

Im Ordner **_posts** eine neue Blogseite wie in den vorhandenen Beispielen erstellen. Die Seite wird dann automatisch nach dem Commit/Push veröffentlicht.

## Inhalt veröffentlichen

Nach dem erstellen des Inhalts muss dieser innerhalb der Git-Struktur hochgeladen werden.

### Dateien zu neuem Commit hinzufügen
`git add -A`

### Commit mit Nachricht erstellen
`git commit -m "Neuer Inhalt"`

### Inhalt hochladen
`git push`

Status: https://github.com/schlosszwerge/schlosszwerge.github.io/actions