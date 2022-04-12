---
title: Unser Ausbildungsangebot
layout: page
description: Unser Ausbildungsangebot
---

Die Ausbildung zur Tuina-Therapeutin und zum Tuina-Therapeuten ist in 6 Teile gegliedert und wird mit einem Prüfungsseminar abgeschlossen.

In den einzelnen Teilen lernen Sie alle Grundlagen der Tuina-Therapie, die klinische Untersuchung und Erstellung eines Therapieplans bei verschiedenen Syndromen. In den praktischen Unterrichtseinheiten werden die verschiedenen Techniken vermittelt und geübt.

Die Ausbildung ist sehr praxisorientiert. Körperkontakt zwischen den Teilnehmern ist im Rahmen der Ausbildung unumgänglich.




{% assign currentEvent = site.data.upcomingEvents.first %}
{% if site.data.upcomingEvents %}

Die kommenden Ausbildungstermine sind:

<h2><a href="{{ currentEvent.url }}">{{ currentEvent.start }}</a></h2>
<p><strong>{{ currentEvent.location }}</strong></p>
<p>{{ currentEvent.content }}</p>

{% else %}

Wir planen aktuell wieder eine neue Ausbildungsreihe zu starten. Konkrete Termine wurden noch nicht fixiert, bei Interesse an der Ausbildung bitten wir Sie uns per E-Mail zu schreiben, dann informieren wir Sie sobald neue Termine verfügbar sind.

{% endif %}
