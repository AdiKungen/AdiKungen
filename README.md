# Cześć, jestem Adrian! 👋

Jestem programistą skupiającym się na tworzeniu skalowalnych aplikacji internetowych, architekturze systemów backendowych oraz inżynierii danych i systemach biometrycznych. 

Lubię eksplorować różnorodne ekosystemy technologiczne od aplikacji korporacyjnych w Javie/Kotlinie, przez web development (Vue.js, PHP, Three.js), aż po analitykę danych i uczenie maszynowe w Pythonie.

---

## Stack technologiczny

- **Języki:** Java 17+, Kotlin, Python 3, JavaScript (ES6+), PHP 8, SQL
- **Web & Frontend:** Vue.js 3, Three.js / WebGL, HTML5/CSS3, Bootstrap 3/5, Vite
- **Backend & Enterprise:** Jakarta EE (JSF, PrimeFaces, EJB, JPA/Hibernate), WildFly, Apache, Medoo
- **Data Science & ML:** Scikit-learn, Imbalanced-learn, Pandas, NumPy, Plotly, Streamlit
- **Bazy danych & Cloud:** MySQL / MariaDB, Google Firebase (Firestore, Auth, Hosting)
- **Mobile & Desktop:** Android SDK, Data Binding, JavaFX 21, Scene Builder

---

## Wybrane projekty

### Web Development & Frontend

#### [System Zarządzania Inwentarzem (_ang._ Shop Inventory Manager)](https://github.com/AdiKungen/Projekt_PWAG_Budny_Adrian_PAW3)
> **Aplikacja SPA do ewidencjonowania zasobów sprzętowych z kontrolą uprawnień (RBAC).**
- **Tech Stack:** `Vue.js 3` `Firebase Auth` `Cloud Firestore` `Bootstrap 5` `Vite`
- **O projekcie:** System zarządzania inwentarzem magazynowym i dokumentacją zewnętrzną (faktury, gwarancje). Posiada autoryzację opartą o tokeny, strażników tras (`navigation guards`) oraz mechanizm audytu zmian (`serverTimestamp`).
- **[Wypróbuj wersję demonstracyjną na żywo](https://system-inwentarz.web.app/)** *(Demo: `user@user.com` / `user123`)*

<p align="center">
  <img src="https://raw.githubusercontent.com/AdiKungen/Projekt_PWAG_Budny_Adrian_PAW3/main/docs/screenshots/inventory-admin.png" alt="Shop Inventory Manager" width="700">
</p>

---

#### [Block Fall 3D - Webowa gra zręcznościowa](https://github.com/AdiKungen/Projekt_IAM_Budny_Adrian_PAW3)
> **Trójwymiarowa gra logiczno-zręcznościowa w przestrzeni WebGL inspirowana klasycznym Tetrisem.**
- **Tech Stack:** `JavaScript (ES6+)` `Three.js` `WebGL` `Vite` `HTML5/CSS3`
- **O projekcie:** Przeniesienie klasycznej mechaniki układania spadających bloków w siatkę trójwymiarową $5 \times 12 \times 5$. Implementacja wieloosiowego modelu kolizji, dynamicznej pętli renderowania, manipulacji bryłami w przestrzeni oraz progresywnego poziomu trudności.
- **[Zagraj na żywo w przeglądarce](https://adikungen.github.io/Projekt_IAM_Budny_Adrian_PAW3/)**

<p align="center">
  <img src="https://raw.githubusercontent.com/AdiKungen/Projekt_IAM_Budny_Adrian_PAW3/main/docs/gifs/demo.gif" alt="Block Fall 3D Demo" width="700">
</p>

---

#### [Musicker - Webowa Wypożyczalnia Muzyki](https://github.com/AdiKungen/Projekt_PBAW_Budny_Adrian_PAW3)
> **Platforma subskrypcyjna typu pay-per-time z wbudowanym odtwarzaczem audio.**
- **Tech Stack:** `PHP 8` `Amelia Framework (MVC)` `MySQL` `Medoo ORM` `Smarty` `Bootstrap 3`
- **O projekcie:** Serwis umożliwiający czasowe licencjonowanie utworów muzycznych. Zawiera wielopoziomowy model ról (Gość, Użytkownik, Pracownik, Administrator), panel weryfikacji wpłat oraz mechanizm automatycznego wygaszania dostępu po upływie wykupionego czasu.
- **[Wypróbuj wersję demonstracyjną na żywo](https://musicker.freedev.app/public)** *(Demo: `user` / `user123`)*

<p align="center">
  <img src="https://raw.githubusercontent.com/AdiKungen/Projekt_PBAW_Budny_Adrian_PAW3/main/docs/screenshots/shop.png" alt="Musicker" width="700">
</p>

---

### Backend & Architektura Korporacyjna / JVM

#### [Booker - System Wypożyczalni Książek](https://github.com/AdiKungen/Projekt_JPDSI2_Budny_Adrian_PAW3)
> **Trójwarstwowa platforma korporacyjna EAR do zarządzania obiegiem woluminów.**
- **Tech Stack:** `Java 17` `Jakarta EE 10` `JSF (PrimeFaces 13)` `EJB 3.x` `JPA / Hibernate` `WildFly` `MariaDB`
- **O projekcie:** Architektura korporacyjna oparta na bezstanowych ziarnach sesyjnych (`@Stateless`), leniwym ładowaniu danych (`LazyDataModel`) oraz zachowywaniu stanu widoku. Oferuje pełny cykl życia wypożyczeń: koszyk ze zmiennym zakresem dni, moduł rozliczania zwrotów z naliczaniem kar za opóźnienia oraz administrację kontami.

<p align="center">
  <img src="https://raw.githubusercontent.com/AdiKungen/Projekt_JPDSI2_Budny_Adrian_PAW3/main/docs/gifs/demo.gif" alt="Booker Demo" width="700">
</p>

---

#### [Aplikacja do utworzenia profilu biometrycznego z cech wyznaczonych na podstawie aktywności użytkownika (KDA)](https://github.com/AdiKungen/Aplikacja_Magisterska_Budny_Adrian_MUI1)
> **Narzędzie analityczne do weryfikacji tożsamości na podstawie dynamiki pisania na klawiaturze.**
- **Tech Stack:** `Java 17` `JavaFX 21` `FXML` `CSS` `Eclipse IDE`
- **O projekcie:** Zaawansowana aplikacja badawcza zrealizowana w ramach pracy inżynierskiej i magisterskiej na Uniwersytecie Śląskim. Obejmuje modularny *pipeline analityczny*: wstępną filtrację szumu i ekstrakcję cech czasowych (`Keystroke Dynamics`), usuwanie wartości odstających oraz wyliczanie wektorów cech na potrzeby systemów ciągłej autentykacji użytkownika.

<p align="center">
  <img src="https://raw.githubusercontent.com/AdiKungen/Aplikacja_Magisterska_Budny_Adrian_MUI1/main/docs/gifs/demo.gif" alt="KDA Profiler Demo" width="700">
</p>

---

### Data Science & Machine Learning

#### 🔬 [Biometric Classifier - Narzędzie do analizy i klasyfikacji danych biometrycznych](https://github.com/AdiKungen/Projekt_WZKKDB_Budny_Adrian_MUI1)
> **Interaktywna platforma analityczna wspierająca pełny pipeline uczenia maszynowego.**
- **Tech Stack:** `Python 3.13` `Streamlit` `Scikit-learn` `Imbalanced-learn` `Pandas` `Plotly Express`
- **O projekcie:** Narzędzie typu no-code/low-code do analizy danych tabelarycznych i biometrycznych. Automatyzuje proces imputacji braków, standaryzacji, zaawansowanego równoważenia klas decyzyjnych (`SMOTE`, `ADASYN`, `TomekLinks`), redukcji wymiarowości (`PCA 2D/3D`) oraz równoległego benchmarkowania modeli (`Random Forest`, `k-NN`, `SVM`).
- **[Wypróbuj wersję demonstracyjną na żywo](https://biometric-classifier.streamlit.app/)**

<p align="center">
  <img src="https://raw.githubusercontent.com/AdiKungen/Projekt_WZKKDB_Budny_Adrian_MUI1/main/docs/screenshots/pca_3d.png" alt="Biometric Classifier" width="700">
</p>

---

### Aplikacje Mobilne (Android)

#### [Asystent Tempa Biegu - Narzędzie do kontroli i stabilizacji prędkości z wykorzystaniem GPS](https://github.com/AdiKungen/Projekt_PAM_Budny_Adrian_PAW3)
> **Narzędzie telemetryczne GPS wspierające stabilizację tempa i prędkości treningowej.**
- **Tech Stack:** `Kotlin` `Android SDK (API 19–34)` `Data Binding` `LocationManager` `Haptics / ToneGenerator`
- **O projekcie:** Aplikacja czasu rzeczywistego ostrzegająca biegacza o wypadnięciu ze zdefiniowanego korytarza prędkości za pomocą dźwięków i wibracji. Wyposażona w algorytmy filtrujące anomalie i zakłócenia sygnału satelitarnego (*anti-teleportation filter*), 3-sekundowy bufor stabilizujący oraz mechanizm oszczędzania energii w cyklu życia aktywności.

<p align="center">
  <img src="https://raw.githubusercontent.com/AdiKungen/Projekt_PAM_Budny_Adrian_PAW3/main/docs/gifs/demo.gif" alt="Asystent Tempa Biegu Demo" width="600">
</p>

---

## Kontakt ze mną

- **LinkedIn:** [https://www.linkedin.com/in/adrian-budny-354568244/](https://www.linkedin.com/in/adrian-budny-354568244/)
- **E-mail:** [a.budny@onet.pl](mailto:a.budny@onet.pl)

<!--
**AdiKungen/AdiKungen** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
