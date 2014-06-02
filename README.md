stolperstein-page
=================
##Mehrsprachigkeit
Um die Hauptseite zu ändern, muss die Datei in `/_layouts/main.html` editiert werden. Viele Dinge habe sind bereits mehrsprachig (Deutsch und Englisch). Um weitere Informationen hinzuzufügen oder um bereits bestehende Abschnitte zu ändern, muss das folgende Schema beachtet werden: 

```
{% case page.lang %}{% when 'en' %}Englischer Text{% else %}Deutscher Text{% endcase %}
```
Das Schema kann auch in HTML-Tags übernommen werden, um beispielsweise Bilder für verschiedene Sprachen anzubieten.
