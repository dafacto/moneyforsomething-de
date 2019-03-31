---
layout: page
permalink: /brokerages/
title: Brokerages
---

{% for brokerage in site.data.brokerages %}

<a href="{{ brokerage.url }}"><strong>{{ brokerage.name }}</strong></a> ({{ brokerage.country }})<br>
{{ brokerage.description }}

{% endfor %}

**Editieren**

Speziell für Deutschland gibe es z.b. noch als reine Online Broker:

- die Onvista Bank (https://www.onvista-bank.de/)
- Flatex (https://www.flatex.de/)

Und als komplette Lösungen mit Konto, Kreditkarte und Depot:

- DKB (https://www.dkb.de/)
- Comdirekt (https://www.comdirect.de/)
- Consorsbank (https://www.consorsbank.de/home)
- ING (https://www.ing-diba.de/)

