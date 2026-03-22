# Hotel-Management-System---Database-Project
Proiectul reprezintă o soluție completă de baze de date pentru gestionarea activității unui lanț hotelier. Obiectivul principal este monitorizarea operațiunilor interne, de la administrarea resurselor umane și a camerelor, până la evidența rezervărilor și facturarea serviciilor către clienți.

Concepte utilizate:
- SGBD: Oracle SQL
- Modelare conceptuală: Realizarea diagramei Entity-Relationship (ERD) pentru definirea entităților și a relațiilor
- Normalizare: Aplicarea formelor normale pentru eliminarea redundanței și optimizarea stocării
- Limbaj SQL:
  - Data Definition Language: crearea tabelelor, constrângeri de integritate, validări
  - Data Manipulation Language:
    - gestiunea datelor: utilizarea comenzilor INSERT pentru popularea bazei de date, UPDATE pentru modificarea statusului unei camere și DELETE pentru anulări;
    - join-uri: extragerea informațiilor corelate (ex: numele clientului alături de detaliile camerei rezervate);
    - funcții de agregare: calcularea veniturilor totale per perioadă folosind SUM, COUNT și AVG;
    - grupări și filtrări: utilizarea clauzelor GROUP BY și HAVING.

Funcționalități și rezultate:
- Managementul rezervărilor: automatizarea verificării disponibilității camerelor;
- Profilul clientului: istoric complet al vizitelor și preferințelor, utile pentru strategii de fidelizare;
- Integritate: constrângeri stricte care previn erorile de tip "double booking" (rezervarea aceleiași camere de două ori).
