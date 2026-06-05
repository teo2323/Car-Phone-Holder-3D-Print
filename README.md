# Sistem de suport suport telefon, cu prindere de tip mengina pentru autoturism Suzuki Jimny
**Autor:** Cotofan Teodor Dumitru

## 📱 Descriere Proiect
Acesta este un suport de telefon complet printabil 3D, proiectat cu un mecanism auto-blocant acționat exclusiv de forța gravitațională. Inițial gândit pentru a fi integrat și montat ferm pe un Suzuki Jimny (2012), designul este versatil și extrem de robust.

Când telefonul este așezat pe suportul inferior, greutatea sa împinge o cremalieră în jos. Prin intermediul unui sistem mecanic (*Rack and Pinion*), mișcarea liniară este transformată în mișcare de rotație pentru două roți dințate. Acestea închid brațele laterale, fixând telefonul instantaneu ca într-o menghină.Suportul propriu-zsi este conectat la menghina prin introducerea unul suport care la baza este un paralalelipiped dreptunghic cu colturile rotunjite,intr-un holder, care este prins de menghina.

## ⚙️ Specificații Tehnice & Modelare (Fusion 360)

Proiectul a fost modelat parametric, respectând principii inginerești pentru mișcare mecanică fluidă:
* **Mecanism Cremalieră - Roți Dințate (Spur Gears):**
  * Modul (M): 1.5
  * Număr dinți (Z): 18
  * Unghi de presiune (Pressure Angle): 20°
  * Distanță precisă între centrele axelor: 50 mm
* **Sistem de Prindere (Menghină):**
  * Utilizează un șurub de forță cu **filet Trapezoidal (TR10 x 2)**. Acest profil (similar cu ACME) oferă o suprafață de contact lată, ideală pentru a rezista forțelor mari de strângere fără a foarfeca straturile de plastic printate 3D.
* **Cinematică & Fizică:** Ansamblul este validat digital folosind *Motion Links*, limite de glisare (*Slider Joints*) și *Contact Sets* pentru a simula coliziunea fizică la fixarea telefonului.

## 🖨️ Recomandări pentru Printare 3D
Sistemul include deja toleranțe calculate la nivel de zecime de milimetru pentru a asigura un montaj direct, fără prea multă șlefuire:
* **Toleranțe Filet:** Șurubul trapezoidal are un offset de `-0.15mm` pe flancuri pentru înșurubare fină.
* **Toleranțe Angrenaj:** Roțile dințate includ un *backlash* de `0.15mm`.
* **Cromatică Recomandată:** Pentru a evidenția aspectul tehnic al mecanismului, recomand folosirea unei palete de culori contrastante. O combinație excelentă este **Negru și Galben** (stil BVB) – carcasă și menghină din plastic mat negru, iar componentele mobile (cremalieră, roți, brațe) din plastic galben.

## 🎥 Demonstrații Video (Simulare Cinematică)

Puteți vizualiza funcționarea exactă a fiecărui mecanism în videoclipurile de mai jos (randări direct din mediul de simulare):

1. [**Mișcare Telefon - Cremalieră - Brațe**](https://youtu.be/_VF9lgzNgNs) 
   *Demonstrează cum forța de apăsare pe cremalieră acționează roțile dințate și închide brațele de fixare.*
2. [**Mișcare de Înfiletare a Șurubului Trapezoidal**](https://youtu.be/GT4BGNl51mE) 
   *Simularea cinematică a strângerii șurubului de forță în gaura menghinei (pas respectat 1:1).*
3. [**Prinderea Suportului de Menghină**](https://youtu.be/W7AA8FZHkoI) 
   *Culisarea pe axa verticală (Slider Joint) pentru reglarea panoului principal în suportul menghinei.*

---
*Proiect modelat integral în Autodesk Fusion 360.*
