﻿---
isChild: true
---

## Namespaces {#namespaces_title}

Kao što je gore navedeno, PHP zajednica se sastoji od mnogo programera koji stvaraju gomilu koda. To znači da kod jedne 
biblioteke verovatno koristi isto ime klase kao neka druga biblioteka. Kada se obe biblioteke koriste u istom namespace,
dolazi do kolizije i problema.

_Namespaces_ rešavaju ovaj problem. Kako je i opisano u PHP reference manualu, namespaces se mogu uporediti sa 
direktorijumima operativnog sistema koji _namespace_ fajlove; dva istoimena fajla mogu postojati istovremeno u 
različitim direktorijumima. Isto tako, dve PHP klase istog imena mogu postojati u različitim PHP namespaces. Vrlo 
jednostavno.

Važno je da namespace vaš kod da bi drugi developeri mogli da ga koriste bez straha od kolizije sa drugim bibliotekama.

Jedan način na koji se preporučuje korišćenje namespaces je dat u glavnim crtama u [PSR-0][psr0], čiji je cilj da pruži 
standarizovanu konvenciju za fajlove, klase i namespace da bi omogućio postojanje plug-and-play koda.

* [Pročitajte o Namespaces][namespaces]
* [Pročitajte o PSR-0][psr0]

[namespaces]: http://php.net/manual/en/language.namespaces.php
[psr0]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md
