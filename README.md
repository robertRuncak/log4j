# Základne fakty

**Log4shell** je niekoľko súvisiacich zraniteľností nachádzajúcich sa v knižnici **log4j** verzie 2. **Log4j2** je softvér určený na logovanie teda vytváranie záznamov. Predmetom záujmu je verzia 2, staršia verzia **Log4j** verzie 1 obsahuje iné vážne zraniteľnosti. Netreba zabúdať nato, že logovanie je dôležité a priam vyžadované zákonom a vyhláškou o bezpečnostných opatreniach podľa zákona o kybernetickej bezpečnosti (362/2018) a nie je z pohľadu legislatívy jednoduché ho vypnúť.

Zraniteľné sú rôzne systémy:
* Frontend - Middleware - Backend
* Klientské aplikácie
* Hardvérové zariadenia

Na zvládnutie zraniteľnosti je odporúčané:
* Identifikácia všetkého zraniteľného softvéru a hardvéru aj takého, ktorý nie je dostupný z Internetu
  * z katalógu aktív
  * skenovaním serverov a pracovných staníc
  * skenovaním siete
  * detailnými dopytmi na subdodávateľov
* Prioritizácia
  * postupovať z kritických prvkov infraštruktúry na menej kritické ako napr. systémy dostupné z internetu, servery, pracovné stanice.
  * vyradenie zastaralých prvkov, ktoré nie je možné alebo vhodné aktualizovať
* Aktualizácia na verziu, ktorá nie je považovaná za zraniteľnú
* Validácia funkčnosti aktualizácie
