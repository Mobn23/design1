Kmom05
===

Här ska jag analysera tre olika webbplatser:
<ol>
    <li><a href="https://www.chalmers.se" class="fk-link">Chalmers</a></li>
    <li><a href="https://www.bth.se" class="fk-link">BTH</a></li>
    <li><a href="https://www.gu.se" class="fk-link">Göteborgs universitet</a></li>
</ol>
Urval 

***Chalmers*** Det är en av bästa svergies universitet webbplats så tänkte jag att det är en intressant val att man få se på och analysera.

***BTH*** Mitt högskola så visst ska jag analysera dess webbplats för att jag nyficken på.

***GU*** Det är en annan universitet så har vi nu 3 olika universitet som kan man jämföra.

Metod
För alla tre webbplatser använde jag mig inspect dev tool (Network) och PageSpeed Insights. Inom PageSpeed Insights så kan man helt enkelt klistra in URL och få resultat, och med inspect dev tool (Network) så kan man kolla på Network och varje gång man refresh så får man en ny load (ladningstid) och där kan man se andra info som resourcer och total size.   

Resultat   
<div class="screenshots">
    <img src="../content/analysis/img/bth.png">
    <img src="../content/analysis/img/chalmers.png">
    <img src="../content/analysis/img/gu.png">
</div>
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQLwYrD_VmFXqQTMgWsFb-l7wqiA6dL5e7_lf7MHM89h-NNNlp72-gudyYBHZRGRtd7b41Cj0IekKva/pubhtml?widget=true&amp;headers=false" class="schedule"></iframe>   

Analys   

Laddningstid (Genomsnitt av 3 mätningar):

Chalmers: 593 ms
BTH: 695 ms
GU: 749 ms
Laddade Resurser (Genomsnitt av 3 mätningar):

Chalmers: 3,07 MB
BTH: 5,13 MB
GU: 2,33 MB
Total Sidstorlek (Genomsnitt av 3 mätningar):

Chalmers: 1,2 MB
BTH: 1,83 MB
GU: 1,19 MB
Vanliga Förbättringsområden:
BTH verkar ha den längsta laddningstiden och den högsta mängden laddade resurser. Att optimera bilder, skript och andra tillgångar kan hjälpa till att minska både laddningstid och resursförbrukning.

GU har den lägsta laddningstiden och resursförbrukningen. Det tyder på effektiv resurshantering. Det är dock viktigt att utvärdera om ytterligare optimering är möjlig utan att kompromissa med användarupplevelsen.

Överväg att implementera tekniker som lazy loading för bilder, optimera och komprimera bilder samt minimera användningen av externa skript, Css och Html för att förbättra den övergripande prestandan.

Rankning:
GU: Denna webbplats presterade konsekvent bra över alla mätvärden och visade den lägsta laddningstiden och resursförbrukningen.

Chalmers: Trots att laddningstiderna är relativt låga är resursförbrukningen måttlig. Det finns utrymme för förbättring av resursoptimiseringen.

BTH: Denna webbplats visade den högsta laddningstiden och resursförbrukningen, vilket indikerar områden där optimering kan vara nödvändig.

Absolut Laddningstidsgräns:
laddningstidsgräns 800 ms som jag anser vara "snabb" för en webbplats. Om laddningstid under 800 ms är snabb:
Chalmers: Snabb
BTH: Inte Snabb (kräver förbättring)
GU: Mycket Snabb
Generell Uppfattning:
Baserat på de tillhandahållna mätvärdena framstår GU som den övergripande vinnaren, med snabbare laddningstider och effektiv resurshantering. Chalmers presterar rimligt bra, medan BTH kan dra nytta av optimeringsåtgärder.
Sammanfattningsvis, med tanke på laddningstid, resursförbrukning och total sidstorlek, verkar GU vara den mest optimerade och effektiva bland de tre webbplatserna.   

Referenser

**Chalmers**. Uppdaterad 30 november 2023, 18:07Publicerad 14 december 2022, 12:50
**BTH**. Sidan senast uppdaterad: 30 augusti 2022
**GU**. Senast ändrad 16 januari 2024

Övrigt
Jag jobbade ensam på.
Mitt namn: **Mohamed Bnshi**
Akronym: **Mobn23**