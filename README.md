# Handschrift-Erkennung

Pfade sind eine besondere Art von Abbildungen in der Mathematik. Alles was nur einen festen Anfangs- und Endzeitpunkt hat, können wir in irgendeiner Form als einen Pfad auffassen. Dementsprechend groß ist die Menge an Beispielen. Ob wir eine Linie zeichnen, die Frequenzen eines Tonsignals messen oder ein Video analysieren, all diese Aktionen lassen sich durch Pfade modellieren. Komplexe Probleme lassen sich so auf das Problem reduzieren, Pfade und ihre Eigenschaften genauer verstehen zu können. Ziel dieser Arbeit ist es, eine algebraische Invariante für Pfade zu definieren, um sie darüber zu untersuchen - die sogenannte *Signatur*.

Die Betrachtung von Pfaden über deren Signatur ist deutlich intuitiver, als den Pfad einfach in allen möglichen Punkten auszuwerten. Ein Beispiel: Wenn wir einen Film betrachten und beschreiben wollen, worum es in diesem geht, würde auch niemand auf die Idee kommen zu sagen, wie die einzelnen Bilder zu einem bestimmten Zeitpunkt aussehen. Stattdessen würde man zuerst die grobe Handlung und deren Verlauf erklären und danach erst auf Einzelheiten eingehen. Genau das ist die Idee hinter der Signatur. Die ersten Koeffizienten dieser Invariante sollen den Pfad in seinen groben Zügen charakterisieren und je mehr Koeffizienten wir dazunehmen, desto spezifischer soll die Charakterisierung werden.

Zuerst erforscht wurde die Signatur von dem chinesischen Mathematiker Kuo-Tsai Chen zu Beginn des 20. Jahrhunderts, ursprünglich zur Untersuchung von Differentialgleichungen. Die Definition benötigt das Konzept von Pfadintegralen, worum es im ersten Kapitel dieser Arbeit gehen wird. Danach betrachten wir, wie man die Signatur eines Pfades berechnet und erforschen erste Eigenschaften. 

Damit alle unsere bis dahin angestellten Rechnungen funktionieren und die Signatur wohldefiniert ist, benötigen wir, dass der zu untersuchende Pfad nicht zu stark oszilliert. In den 90er Jahren gelang es Terry Lyons, der zur Zeit Professor der Mathematik an der Universität Oxford ist, das Konzept der Signatur auf eine viel größere Klasse von Pfaden anzuwenden, den rauen Pfaden. Sie werden genutzt um komplexe Bewegungen, die fast nirgendwo differenzierbar sind zu studieren. 

Einer der ersten Erfolge der Signatur in der "echten Welt" gelang dem Mathematiker Benjamin Graham. Dieser nahm im Jahr 2013 erfolgreich an der ICDAR teil, indem er ein Programm schrieb, das gezeichnete chinesische Schriftzeichen erkennen soll. Dazu verwendete unter anderem die Signatur. Wie man so etwas genau umsetzt, behandeln wir hier exemplarisch für das Erkennen der Zahlen von 0 bis 9.

<img src="GridSkizze.jpg" height="402pt">

