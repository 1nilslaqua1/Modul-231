**Warum ist Hash sicher?**
-Das System sieht nie dein echtes Passwort

-Ein Angreifer kann aus dem Hash nicht zurückrechnen, was du eingegeben hast

-Schon eine kleine Änderung („Katze“ statt „katze“) ergibt einen komplett anderen Hash

**Hash**
-Ein hash reagiert nur auf sich selbst positiv. Er erkennt bei einer Passworteingabe ob es der Selbe Hash ist wie er selbst.
Der Hash wird logischerweise beim einrichten des PC's erstellt.

-Smoothie Beispiel: Alle Früchte werden gleichzeitig gemixt: es entsteht ein Smoothie (Hash).
Wenn man nun einen zweiten Smoothie dazu giessen will, erkennt er nicht die Zutaten, er erkennt nur, dass er gleich schmeckt.

-Beim Besuchen einer Webseite wird ein Hash für den Browser erstellt, aus ganz vielen, detaillierten Daten, die sich immer irgendwie unterscheiden.
Bei einem späteren besuch wird der Hash überprüft und somit bekommt man Zugang auf die Webseite.

**Merksatz:**
Hash = Fingerabdruck.
Er erkennt nicht den Inhalt – nur, ob zwei Fingerabdrücke identisch sind.
