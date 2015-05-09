## Techniki Internetowe, 14/15

> *Uważaj na człowieka, którego nie interesują szczegóły.*
>
> — William Feather

Terminy rozliczenia się z projektów:

* ***zaliczenie***: **ISODate("2015-03-28T10:00:00.000Z")**<br>
  nierozliczenie się z projektu w terminie powoduje obniżenie oceny
* ***egzamin***: **ISODate("2015-05-12T12:00:00.000Z")**<br>
  nierozliczenie się z projektu w terminie oznacza ocenę ndst
  z egzaminu; na egzamin poprawkowy zostaną wyznaczone nowe projekty

Projekty tworzymy w repozytoriach Git na *GitHub* lub *Bitbucket*.
Projekt na egzamin umieszczamy w repozytorium prywatnym.
W repozytoriach nie powinno być śmieci, np. plików backup edytora.


### Zaliczenie

1\. Zapoznajemy się z notacjami:

* [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) –
  Github-flavored
* [reStructuredText Primer](http://sphinx-doc.org/rest.html)
* [AsciiDoc](http://www.methods.co.nz/asciidoc/); zob. też
  [Pro Git Book, ed. 2](https://github.com/progit/progit2)

Korzystając z jednej z tych notacji przygotować:

* tabelkę porównującą te notacje; przepisać tę tabelkę w *czystym* HTML5
* przygotować tabelkę z programem MŚ w Falun 2015 lub programu TV z jednego dnia

W których z tych notacji można wpisywać wzory w notacji LaTeX? (zob. na przykład
[Math in reStructuredText with LaTeX](http://stackoverflow.com/questions/3610551/math-in-restructuredtext-with-latex)).

2\. [GitHub Pages](https://pages.github.com).
Przygotować responsywne *user* lub *project site* korzystające
z jednego z frameworków:

* [Foundation](http://foundation.zurb.com)
* [Bootstrap](http://getbootstrap.com)

Na stronach wstawić mapkę korzystającą [Leaflet](http://leafletjs.com/)
oraz użyć kilku *web components* z biblioteki [Polymer](https://www.polymer-project.org).

----

Pull requests z linkami do projektów na zaliczenie i egzamin należy wpisać
w pliku [laboratoria.md](laboratoria.md).


### Egzamin

1\. Przygotować prostą aplikację WWW korzystając z frameworka [Meteor](https://www.meteor.com/).
Do kodu *JavaScript* dopisać testy (co najmniej kilkanaście).
Testy podłączyć do platformy [Travis](https://travis-ci.com/plans) (wybrać FREE plan).

2\. Przygotować pokaz slajdów w [Reveal.js](http://lab.hakim.se/reveal-js/)
szczegółowo opisujący jak wdrożyć [przykładową aplikację Meteor](https://www.meteor.com/install)
na zewnętrznym serwerze
[Digital Ocean](http://devo.ps/blog/deploy-your-meteor-apps-on-digital-ocean-in-5-minutes/)
lub [Heroku](http://ondrej-kvasnovsky.blogspot.com/2013/05/how-to-deploy-meteor-on-heroku-with.html).

Po instalacji frameworka [Meteor](https://www.meteor.com/install)
listę przykładowych aplikacji wypisze to polecenie:
```console
$ meteor create --list
```

Użyteczne linki:

- [Meteor](https://www.meteor.com/)
- David Turnbull.
  [Your First Meteor Application](http://meteortips.com/book/) –
  a Complete Beginner’s Guide to the Meteor JavaScript Framework
- [Discover Meteor](http://book.discovermeteor.com/)
  ([polskie tłumaczenie](http://pl.discovermeteor.com/))


## 2015 → ∞

### JavaScript

[JavaScript in 2015](http://glenmaddern.com/articles/javascript-in-2015)
([YouTube](https://www.youtube.com/watch?v=iukBMY4apvI)).

- Marijn Haverbeke.
  [Eloquent JavaScript](http://eloquentjavascript.net/) –
- Kyle Simpson.
  [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS) – book series
- Nicholas C. Zakas.
  [Understanding ECMAScript 6](https://leanpub.com/understandinges6/read/)
- John Resig.
  [Learning Advanced JavaScript](http://ejohn.org/apps/learn/)
- [JavaScript reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference) –
  Mozilla Developer Network (MDN)

ES6+

- Sindre Sorhus.
  [ES.next showcase](https://github.com/sindresorhus/esnext-showcase)
- Matt Greer.
  [JavaScript Promises ... In Wicked Detail](http://mattgreer.org/articles/promises-in-wicked-detail/)
- Aidan Feldman.
  [Advanced JavaScript](http://advanced-js.github.io/deck/)


### WebComponents

- [WebComponents.org](http://webcomponents.org/) – a place to discuss
  and evolve Web Component best-practices
- Dominic Cooney.
  [Shadow DOM 101](http://www.html5rocks.com/en/tutorials/webcomponents/shadowdom/)


### CSS

- [Less](http://lesscss.org)
- [Sass](http://sass-lang.com)


### Git + Docker

- [Pro Git Book](http://git-scm.com/book/en/v2)
- [Docker](http://www.docker.com/) –  Build, Ship and Run Any App, Anywhere


### Różne rzeczy

- [GitHub Flavored Markdown](http://guides.github.com/overviews/mastering-markdown/) +
  [Mastering Markdown](http://guides.github.com/overviews/mastering-markdown/)
- [Mapping geoJSON files on GitHub](https://help.github.com/articles/mapping-geojson-files-on-github)
