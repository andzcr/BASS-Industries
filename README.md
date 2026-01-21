## ✨ Live Preview: The BASS Industries Experience

![Video Live-Preview](https://github.com/andzcr/BASS-Industries/blob/main/bass-preview.gif?raw=true)

---

### Despre acest concept

Acesta nu este un simplu site de prezentare. Este un **concept digital imersiv** creat pentru o firmă de arhitectură high-end. Obiectivul a fost traducerea esteticii "brutalist luxury" într-o experiență web fluidă. Am vrut ca utilizatorul să simtă calitatea și greutatea brandului prin fiecare interacțiune, nu doar să citească despre ea.

Am evitat framework-urile JS complexe (precum React) și am mizat pe o abordare "vanilla" puternic optimizată, lăsând librăriile specializate să se ocupe de mișcare și feeling.

### Ce se întâmplă "sub capotă"?

Iată o descriere a sistemelor și funcțiilor pe care le-am implementat în cod:

**1. "Feeling-ul" Premium (Smooth Scrolling & Cursor)**
Primul lucru pe care îl vei simți este scroll-ul. Am integrat **Lenis** pentru a elimina acel scroll sacadat standard al browserului, înlocuindu-l cu o mișcare fluidă, inerțială, care dă o senzație de "greutate" premium paginii.

Experiența este completată de un **cursor personalizat**. Acesta folosește un `mix-blend-mode` pentru a rămâne vizibil pe orice fundal (inversând culorile) și își schimbă starea dinamic – crescând subtil – ori de câte ori treci peste un element interactiv (butoane, linkuri, carduri), ghidând vizual utilizatorul.

**2. Motorul de Animații (GSAP Power)**
Aproape tot ce mișcă pe site este propulsat de **GSAP (GreenSock)** și pluginul său **ScrollTrigger**. Nu sunt doar animații de dragul animației, ci sunt gândite să dezvăluie conținutul pe măsură ce explorezi:

* **Secțiunea Reviews Orizontală:** Probabil cea mai complexă parte tehnică. Când ajungi la secțiunea de testimoniale, ScrollTrigger "agață" pagina (`pin: true`) și transformă scroll-ul tău vertical într-o mișcare orizontală fluidă printre cardurile de review-uri.
* **Parallax și Adâncime:** Imaginile proiectelor nu sunt statice. Au un efect subtil de parallax vertical, mișcându-se cu o viteză diferită față de restul paginii pentru a crea o senzație de adâncime 3D.
* **Statistici Dinamice:** Numerele din secțiunea "Despre" nu apar pur și simplu; ele se incrementează animat (count-up) exact în momentul în care intră în ecranul utilizatorului.

**3. Sistemul de Teme (Dark/Light Mode)**
Am construit un sistem robust de theming bazat direct pe **Variabile CSS** native. Asta înseamnă că schimbarea între modul Dark și Light (butonul din dreapta jos) este instantanee și foarte performantă, afectând simultan culorile de fundal, textele, accentele și chiar intensitatea efectelor de "sticlă" (glassmorphism) de pe bara de navigație.

**4. Design și Structură (Tailwind & Semantic HTML)**
Structura de bază este HTML5 semantic curat. Pentru stilizare, am folosit **Tailwind CSS** pentru rapiditate în layout și responsiveness, dar l-am combinat cu mult CSS custom pentru efectele specifice – cum ar fi acele borduri "curgătoare" cu gradient de pe cardurile de servicii sau efectul de dezvăluire a footer-ului la finalul paginii.
