_[Deutsche Version](#d-0)_

## Boîte morphologique : Paramètre 17 - Émission d’une confirmation de réception de l’attestation de soutien

Lors de la récolte de signatures sur papier, les personnes qui signent ne reçoivent pas de confirmation individuelle indiquant quand et pour quel objet soumis au vote populaire elles ont signé. 
Ils peuvent toutefois, en vertu de leur droit d'accès, demander à l'autorité compétente chargée de la tenue du registre des électeurs de leur indiquer s'ils figurent parmi les signataires d'une initiative populaire donnée. Dans le système de la récolte électronique de signatures, la réception d’une attestation de soutien pourrait être confirmée électroniquement sans grande difficulté.

Une telle confirmation peut prendre différentes formes : elle peut être affichée uniquement sur l’interface utilisateur immédiatement après le dépôt ou faire également l’objet d’une publication.

Concernant la publication : Le document de travail « Paramètres de l’architecture de base » décrit la possibilité d’utiliser un identifiant de suivi (tracker ID) anonyme. Cette idée est étroitement liée à la confirmation de réception décrite ici et permettrait de publier les identifiants de suivi pris en compte lors du décompte. Chaque personne ayant apporté son soutien pourrait ainsi vérifier si sa signature a été comptabilisée.

Il convient également de tenir compte du fait que des confirmations pourraient être être utilisées pour démontrer à des tiers qu’une attestation de soutien a été déposée. 

Les questions abordées dans ce paramètre ont également été traitées dans une proposition alternative de paramètre ([NEU Parameter N-19 - Empfangsbestätigung](https://github.com/swiss/e-collecting/issues/34)). La Chancellerie fédérale a adapté et complété cette proposition pour la présente publication.


**La discussion sur l'architecture de base a lieu [ici](https://github.com/swiss/e-collecting/issues/49).**


```mermaid
block
  block
    columns 5
    t1["Paramètres"]
    t2["Variantes"]:4
    d["Paramètre 17
    Émission d’une
    confirmation de
    réception de 
    l’attestation de
    soutien"]
    a1["Variante 1:
    Le système de ré-
    colte électronique
    n’émet aucune con-
    firmation de ré-
    ception de 
    l’attestation de
    soutien déposée."]
    a2["Variante 2:
    La réception de
    l’attestation de
    soutien est 
    confirmée 
    immédiatement 
    après son dépôt
    sur l’interface
    utilisateur du 
    système de récolte
    électronique. La
    confirmation ne 
    peut pas être 
    enregistrée 
    séparément."]
    a3["Variante 3:
    Le système de 
    récolte électro-
    nique émet une 
    confirmation de 
    réception 
    électronique 
    pouvant être en-
    registrée et 
    comportant un 
    identifiant de 
    suivi (tracker ID)
    anonyme. Cette 
    confirmation peut
    être conservée en
    dehors du système 
    pendant une durée 
    librement choisie.
    Une éventuelle cer-
    tification 
    ultérieure est 
    affichée sur l’inter-
    face utilisateur. 
    Les identifiants de
    suivi publiés per-
    mettent de vérifier
    si l’attestation de
    soutien a été prise
    en compte lors du
    décompte."]
    a4["&nbsp;"]
    style t1 fill:#a8d5ff,stroke-width:0px
    style t2 fill:#a8d5ff,stroke-width:0px
    style d fill:#a8d5ff,stroke-width:0px,text-valign:top
    style a1 fill:#cdedff,stroke-width:0px
    style a2 fill:#cdedff,stroke-width:0px
    style a3 fill:#cdedff,stroke-width:0px
    style a4 fill:#cdedff,stroke-width:0px
  end
```

## <a name="d-0"> Morphologischer Kasten: Parameter 17 - Ausstellung einer Empfangsbestätigung der Untertstützungsbekundung 

Bei der Unterschriftensammlung auf Papier erhalten die unterzeichnenden Personen keine individuelle Empfangsbestätigung darüber, wann und für welches Volksbegehren sie unterschrieben haben. Sie können jedoch gestützt auf ihr Auskunftsrecht bei der zuständigen stimmregisterführenden Stelle Auskunft darüber verlangen, ob sie für ein bestimmtes Volksbegehren als unterzeichnende Person hinterlegt sind. Im E-Collecting-System könnte der Eingang einer Unterstützungsbekundung mit wenig Aufwand unmittelbar elektronisch bestätigt werden.

Eine solche Bestätigung kann unterschiedlich ausgestaltet sein: Sie kann lediglich unmittelbar nach der Einreichung auf der Benutzeroberfläche angezeigt oder auch publiziert werden. 

Zur Publikation: Im Arbeitsdokument «Parameter Grundarchitektur» wird die Möglichkeit einer anonymen Tracker-ID beschrieben. Diese Idee ist eng mit der hier beschriebenen Empfangsbestätigung verbunden und würde es erlauben, bei der Zählung die berücksichtigten Tracker-IDs öffentlich anzuzeigen. Damit könnte jede unterstützende Person nachvollziehen, ob ihre Unterschrift mitgezählt wurde.

Neben diesen Überlegungen ist zu berücksichtigen, dass Bestätigungen verwendet werden könnten, um die Abgabe einer Unterstützungsbekundung gegenüber Dritten zu belegen. 

Die Fragen in diesem Parameter wurden auch in einem alternativen Parameter-Vorschlag ([NEU Parameter N-19 - Empfangsbestätigung](https://github.com/swiss/e-collecting/issues/34)) thematisiert. Die Bundeskanzlei hat den Vorschlag für die vorliegende Veröffentlichung angepasst und ergänzt.

**Die Diskussion über die Grundarchitektur findet [hier](https://github.com/swiss/e-collecting/issues/49) statt.**


```mermaid
block
  block
    columns 5
    t1["Parameter"]
    t2["Ausprägungen"]:4
    d["Parameter 17
    Ausstellung einer
    Empfangsbestätigung
    der Untertstützungs-
    bekundung"]
    a1["Ausprägung /
    Umsetzungsvariante 1:
    Das E-Collecting-
    System stellt keine
    Empfangsbestätigung
    für die eingereichte
    Unterstützungsbe-
    kundung aus."]
    a2["Ausprägung /
    Umsetzungsvariante 2:
    Der Eingang der Unter-
    stützungsbekundung 
    wird unmittelbar nach
    der Einreichung auf 
    der Benutzeroberfläche
    des E-Collecting-
    Systems bestätigt.
    Die Bestätigung kann
    nicht separat ge-
    speichert werden."]
    a3["Ausprägung /
    Umsetzungsvariante 3:
    Das E-Collecting-
    System stellt eine 
    elektronisch speicher-
    bare Empfangsbestä-
    tigung mit einer ano-
    nymen Tracker-ID aus.
    Die Bestätigung kann 
    ausserhalb des Systems
    für eine frei wählbare
    Dauer aufbewahrt 
    werden. Eine all-
    fällige nachträgliche
    Bescheinigung wird auf
    der Benutzeroberfläche
    angezeigt. Die ver-
    öffentlichten 
    Tracker-IDs ermöglichen
    es, die Berücksich-
    tigung der Unter-
    stützungsbekundung bei
    der Zählung zu über-
    prüfen."]
    a4["&nbsp;"]
   style t1 fill:#a8d5ff,stroke-width:0px
    style t2 fill:#a8d5ff,stroke-width:0px
    style d fill:#a8d5ff,stroke-width:0px,text-valign:top
    style a1 fill:#cdedff,stroke-width:0px
    style a2 fill:#cdedff,stroke-width:0px
    style a3 fill:#cdedff,stroke-width:0px
    style a4 fill:#cdedff,stroke-width:0px
  end
```
