# O analiză comparativă a metodelor de testare pentru sistemele Internet-of-Things

Sistemele IoT sunt eterogene, distribuite și complexe datorită interconectării unui număr mare de componente hardware și software. În lucrarea de față, am argumentat că aceste caracteristici cresc dificultatea testării aspectelor funcționale și nefuncționale, testarea reprezentând un subiect de interes atât pentru cercetători, cât și pentru dezvoltatorii industriali. 

În urma analizei literaturii de specialitate, am constatat lipsa unor repere obiective de comparare și analiză a tehnicilor de testare, fiecare publicație utilizând propriile aplicații, dispozitive și metrici pentru evaluare. Astfel, reproducerea și compararea rezultatelor este dificilă.

Pentru a depăși acest obstacol, am construit o suită open-source de aplicații, care să modeleze cât mai bine caracteristicile unui sistem IoT real, suita mimând o rețea a unei locuințe inteligente. Pentru a asigura caracterul eterogen, dar și comunicarea complexă, aplicațiile au fost construite de multiple entități independente (echipe de studenți, autorul prezentei lucrări, dezvoltatori independenți) și apoi integrate în fluxuri de automatizare care implică angrenarea mai multor aplicații. Suita conține o serie de defecte (bugs) naturale sau injectate artificial, din clase variate. Am prezentat clasificarea acestora atât raportat la sisteme de categorisire standard, precum Common Weakness Enumeration (CWE), dar și folosind o ierarhie proprie bazată pe nivelul de interconectare la care se manifestă defectul.

Utilizând suita construită, am efectuat experimente demonstrative, folosind diferite tehnici de testare, cum ar fi testare funcțională manuală, analiză statică a codului sursă, \textit{fuzzing} și verificare formală. În urma experimentelor, am tras concluzia că realizarea suitei de aplicații este relevantă pentru analiza și îmbunătățirea practicilor de testare existente și că este necesară încurajarea creării de medii de test publice.

O parte din rezultatele prezentate în această lucrare au fost deja publicate în articolul realizat de \fullcite{Cristea2022}.

Îi mulțumesc domnului profesor Alin Ștefănescu pentru sprijinul fără de care realizarea acestei lucrări nu ar fi fost posibilă. Le mulțumesc, de asemenea, domnului profesor Ciprian Păduraru și doctorandului Rareș Cristea pentru sfaturile oferite și colaborarea din timpul activității mele de cercetare.
