# Lern-Bericht
Maria-Nives Gallo

## Einleitung
Bilder auf einer Web Applikation zeigen mit JSF

## Was habe ich gelernt?

Ich habe gelernt Bilder auf einer Web Applikation zu darstellen mit JSF. Ebenso kann man die Bilder als Link benutzen um z.B. Seite zu wechseln.

## Beschreibung

✍️ Verwenden Sie drei verschiedene Medien, um zu zeigen, was Sie gelernt haben. Zum Beispiel:

``` Java
<h:form>
            <h:commandLink action="eye.xhtml" value="#{manageBeanAvatar.setSkin("d")}"/>     
            <h:graphicImage library="images" name="d.png" />
            <h:commandLink action="eye.xhtml" value="#{manageBeanAvatar.setSkin("h")}"/>     
            <h:graphicImage library="images" name="h.png" />
        </h:form>
```


## Verifikation

Wie man auf dem Code sehen kann, wird mit graphicImage aus der Library images das bild d.png ausgewählt und auf der Seite dargestellt. 
Mit commandLink wird das Bild zu einem Link gemacht, dass auf die Seite "eye.xhtml" weitergeleitet wird.
Ebenso kann man auf dem Bild sehen wie dies auf der Website dann aussieht.

# Reflektion zum Arbeitsprozess

👍 Ich konnte anhand den Aufträgen von den vorherigen Aufgaben diesen Auftrag gut lösen und immer wieder ein wenig "spicken".

👎 Ich war sehr langsam beim Fehler finden und diese zu korrigieren

**VBV**: ✍️ Mehr mit debugger Arbeiten, Fehlermeldungen besser analysieren und somit die Fehler schneller finden und beheben.
