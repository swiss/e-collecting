_[Deutsche Version](#d-0)_

## Boîte morphologique : Paramètre 16 - Retrait d’un objet soumis au vote populaire

Conformément à la loi, les initiatives populaires sont portées par des comités d’initiative. Pendant la phase de récolte, ceux-ci peuvent décider de suspendre la récolte et de ne pas déposer les déclarations de soutien recueillies. Sur le site Internet de la Chancellerie fédérale, ces initiatives figurent dans la chronologie des initiatives populaires avec la mention « retirée ».

La question se pose de savoir comment mettre en œuvre concrètement le retrait dans le cadre de la récolte électronique de signatures. L’arrêt de la récolte et la cessation de la réception de nouvelles déclarations de soutien sont en principe simples à réaliser sur le plan technique. D’un point de vue technique, la suppression des déclarations de soutien déjà déposées soulève également peu de questions.

En revanche, il reste à déterminer si, après le retrait, toutes les informations relatives à la récolte doivent être supprimées du système ou si l’initiative retirée doit rester visible en tant que telle.

Si la récolte disparaît du système, aucune nouvelle attestation de soutien ne peut être reçue. Si une liste des objets soumis au vote populaire en cours est affichée dans le système, la récolte est retirée de cette liste (voir [Paramètre 2 – Présentation des objets soumis au vote populaire en cours](https://github.com/swiss/e-collecting/issues/15)).
Si des données relatives aux récoltes électroniques sont publiées (voir [Paramètre 5 – Affichage du nombre de signatures recueillies à ce jour](https://github.com/swiss/e-collecting/issues/18)), les chiffres concernant l’initiative retirée ne sont plus affichés. Si les informations sont conservées, elles restent en revanche visibles dans le système de récolte électronique et sur l’interface utilisateur, et l’initiative populaire est signalée comme « retirée ».

Quelle que soit la variante choisie, la pratique actuelle de la Chancellerie fédérale concernant la présentation des initiatives populaires retirées sur son site Internet reste inchangée. L’initiative continue de figurer dans la chronologie des initiatives populaires avec la mention « retirée », accompagnée des informations de fond pertinentes déjà disponibles.

Les questions abordées dans ce paramètre ont également été traitées dans une proposition alternative de paramètre (voir [NEU Parameter N-23-2 - Formeller Rückzug einer Initiative](https://github.com/swiss/e-collecting/issues/40)). La Chancellerie fédérale a adapté et complété cette proposition pour la présente publication.

**La discussion sur l'architecture de base a lieu [ici](https://github.com/swiss/e-collecting/issues/FIXME).**


```mermaid
block
  block
    columns 5
    t1["Paramètres"]
    t2["Variantes"]:4
    d["Paramètre 16
    Retrait d’un objet
    soumis au vote
    populaire"]
    a1["Variante 1:
    Lorsqu’une initiative
    populaire est retirée,
    toutes les informa-
    tions et données 
    relatives à la ré-
    colte de signatures
    sont supprimées du
    système de récolte
    électronique. Sur le
    site Internet de la
    Chancellerie fédérale,
    l’initiative continue
    de figurer dans la
    chronologie et est
    signalée comme 
    « retirée »."]
    a2["Variante 2:
    Lorsqu’une initiative
    populaire est retirée,
    les informations ainsi
    que le nombre total de
    déclarations de sou-
    tien déposées restent
    visibles sur l’inter-
    face utilisateur du 
    système de récolte 
    électronique. L’ini-
    tiative est signalée
    comme « retirée », 
    tandis que les décla-
    rations de soutien 
    individuelles sont 
    supprimées. Sur le 
    site Internet de la
    Chancellerie fé-
    dérale, l’initiative
    continue de figurer
    dans la chronologie
    et est signalée 
    comme « retirée »."]
    a3["&nbsp;"]
    a4["&nbsp;"]
    style t1 fill:#a8d5ff,stroke-width:0px
    style t2 fill:#a8d5ff,stroke-width:0px
    style d fill:#a8d5ff,stroke-width:0px,text-valign:top
    style a1 fill:#cdedff,stroke-width:0px
    style a2 fill:#cdedff,stroke-width:0px
    style a3 fill:#cdedff,stroke-width:0px
    style a4 fill:#cdedff,stroke-width:0px
    style a5 fill:#cdedff,stroke-width:0px
  end
```

## <a name="d-0"> Morphologischer Kasten: Parameter 16 - Rückzug eines Volksbegehrens

Hinter Volksinitiativen stehen gemäss Gesetz Initiativkomitees. Während der Sammelphase können diese entscheiden, die Sammlung zu sistieren und die gesammelten Unterstützungsbekundungen nicht einzureichen. Auf der Webseite der Bundeskanzlei sind sie in der Chronologie der Volksinitiativen als «zurückgezogen» aufgeführt. 
Es stellt sich die Frage, wie der Rückzug bei E-Collecting praktisch umgesetzt wird. Die Sammlung zu stoppen und keine weiteren Unterstützungsbekundungen entgegenzunehmen, ist technisch grundsätzlich unkompliziert. Auch die Löschung der bereits geleisteten Unterstützungsbekundungen wirft technisch gesehen wenige Fragen auf.

Offen ist hingegen, ob nach dem Rückzug sämtliche Informationen zur Sammlung aus dem System entfernt werden oder ob die zurückgezogene Initiative weiterhin als solche sichtbar bleibt.

Verschwindet die Sammlung, werden keine neuen Unterstützungsbekundungen mehr entgegengenommen. Ist im System eine Liste von laufenden Volksbegehren sichtbar, verschwindet die Sammlung von dieser Liste (siehe [Parameter 2 – Darstellung laufender Volksbegehren](https://github.com/swiss/e-collecting/issues/15)). 
Werden Daten zu elektronischen Sammlungen publiziert (siehe [Parameter 5 – Anzeige der Anzahl bisher gesammelter Unterschriften](https://github.com/swiss/e-collecting/issues/18)), werden die Zahlen zur zurückgezogenen Initiative nicht mehr angezeigt. Bei einem Verbleib der Informationen bleiben diese hingegen im E-Collecting-System und auf der Benutzeroberfläche sichtbar, die Volksinitiative wird als «zurückgezogen» gekennzeichnet.

Unabhängig von der gewählten Ausprägung bleibt die bisherige Praxis der Bundeskanzlei zur Darstellung zurückgezogener Volksinitiativen auf ihrer Website unverändert. Die Initiative wird weiterhin in der Chronologie der Volksinitiativen als «zurückgezogen» aufgeführt, zusammen mit den bisherigen relevanten inhaltlichen Informationen.

Die Fragen in diesem Parameter wurden auch in einem alternativen Parameter-Vorschlag (siehe [NEU Parameter N-23-2 - Formeller Rückzug einer Initiative](https://github.com/swiss/e-collecting/issues/40)) thematisiert. Die Bundeskanzlei hat den Vorschlag für die vorliegende Veröffentlichung angepasst und ergänzt.

**Die Diskussion über die Grundarchitektur findet [hier](https://github.com/swiss/e-collecting/issues/FIXME) statt.**

```mermaid
block
  block
    columns 5
    t1["Parameter"]
    t2["Ausprägungen"]:4
    d["Parameter 16
    Rückzug eines 
    Volksbegehrens"]
    a1["Ausprägung /
    Umsetzungsvariante 1:
    Wird eine Volksini-
    tiative zurückgezogen,
    werden sämtliche In-
    formationen und Daten
    zur Unterschriften-
    sammlung im E-Collec-
    ting-System gelöscht.
    Auf der Website der
    Bundeskanzlei bleibt
    die Initiative in der
    Chronologie aufgeführt
    und wird als «zurück-
    gezogen» gekenn-
    zeichnet."]
    a2["Ausprägung /
    Umsetzungsvariante 2:
    Wird eine Volksini-
    tiative zurückgezogen,
    bleiben die Informa-
    tionen sowie die 
    Gesamtzahl der ein-
    gereichten Unter-
    stützungsbekundungen
    auf der Benutzerober-
    fläche des E-Collec-
    ting-Systems sichtbar.
    Die Initiative wird 
    als «zurückgezogen»
    gekennzeichnet, die 
    einzelnen Unter-
    stützungsbekundungen
    werden gelöscht.
    Auf der Website der
    Bundeskanzlei bleibt
    die Initiative in
    der Chronologie 
    aufgeführt und wird
    als «zurückgezogen»
    gekennzeichnet."]
    a3["&nbsp;"]
    a4["&nbsp;"]
    style t1 fill:#a8d5ff,stroke-width:0px
    style t2 fill:#a8d5ff,stroke-width:0px
    style d fill:#a8d5ff,stroke-width:0px,text-valign:top
    style a1 fill:#cdedff,stroke-width:0px
    style a2 fill:#cdedff,stroke-width:0px
    style a3 fill:#cdedff,stroke-width:0px
    style a4 fill:#cdedff,stroke-width:0px
    style a5 fill:#cdedff,stroke-width:0px
  end
```
