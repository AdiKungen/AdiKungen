# Cześć, jestem Adrian!

Jestem programistą skupiającym się na tworzeniu skalowalnych aplikacji internetowych, architekturze systemów backendowych oraz inżynierii danych i systemach biometrycznych. 

Lubię eksplorować różnorodne ekosystemy technologiczne od aplikacji korporacyjnych w Javie/Kotlinie, przez web development (Vue.js, PHP, Three.js), aż po analitykę danych i uczenie maszynowe w Pythonie.

---

## Stack technologiczny

- **Języki:** Java 17+, PHP 8, JavaScript (ES6+), Python 3, SQL, Kotlin
- **Web & Frontend:** Vue.js 3, Three.js / WebGL, HTML5/CSS3, Bootstrap 3/5, Vite
- **Backend & Enterprise:** Jakarta EE (JSF, PrimeFaces, EJB, JPA/Hibernate), WildFly, Apache, Medoo
- **Data Science & ML:** Scikit-learn, Imbalanced-learn, Pandas, NumPy, Plotly, Streamlit
- **Bazy danych & Cloud:** MySQL / MariaDB, Google Firebase (Firestore, Auth, Hosting)
- **Mobile & Desktop:** JavaFX 21, Scene Builder, Android SDK, Data Binding
- **Narzędzia & Metodyki:** Git, GitHub, Gradle, Node.js, XAMPP, Eclipse, Visual Studio Code, Android Studio

---

# Wybrane projekty

## Web Development & Frontend

### [Musicker - Webowa Wypożyczalnia Muzyki](https://github.com/AdiKungen/Projekt_PBAW_Budny_Adrian_PAW3)
`PHP 8` | `Amelia Framework (MVC)` | `MySQL / MariaDB` | `Medoo ORM` | `Smarty` | `Bootstrap 3`

Webowa platforma subskrypcyjna typu *pay-per-time* realizująca model czasowego licencjonowania utworów audio. System oferuje 4-stopniowy model ról (RBAC), odtwarzacz HTML5 Audio API, panel weryfikacji płatności dla pracowników oraz mechanizm automatycznego blokowania odtwarzania po upływie wykupionego limitu czasowego.

**Wersja demonstracyjna (Live Demo):** [musicker.freedev.app](https://musicker.freedev.app/public) *(Konta testowe: `user` / `user123`, `worker` / `worker123`, `admin` / `admin123`)*

<p align="center">
  <img src="https://raw.githubusercontent.com/AdiKungen/Projekt_PBAW_Budny_Adrian_PAW3/main/docs/screenshots/home.png" alt="Musicker" width="700">
</p>

---

### [System Zarządzania Inwentarzem (_ang._ Shop Inventory Manager)](https://github.com/AdiKungen/Projekt_PWAG_Budny_Adrian_PAW3)
`Vue.js 3` | `Firebase Auth` | `Cloud Firestore` | `Bootstrap 5` | `Vite`

Aplikacja SPA do ewidencjonowania zasobów sprzętowych i zarządzania dokumentacją zewnętrzną (faktury, gwarancje). Implementuje autoryzację opartą na tokenach, kontrolę dostępu z podziałem na role (RBAC), ochronę tras (`navigation guards`) oraz automatyczne śledzenie historii modyfikacji rekordów.

**Wersja demonstracyjna (Live Demo):** [system-inwentarz.web.app](https://system-inwentarz.web.app/) *(Konto testowe: `user@user.com` / `user123`, `admin@admin.com` / `admin123`)*

<p align="center">
  <img src="https://raw.githubusercontent.com/AdiKungen/Projekt_PWAG_Budny_Adrian_PAW3/main/docs/screenshots/inventory-admin.png" alt="Shop Inventory Manager" width="700">
</p>

---

### [Block Fall 3D - Webowa gra zręcznościowa](https://github.com/AdiKungen/Projekt_IAM_Budny_Adrian_PAW3)
`JavaScript (ES6+)` | `Three.js` | `WebGL` | `Vite` | `HTML5 / CSS3`

Trójwymiarowa reinterpretacja klasycznej gry zręcznościowej przenosząca tradycyjne mechaniki układania bloków w przestrzeń WebGL o wymiarach 5 × 12 × 5. Projekt implementuje autorski, trójosiowy model detekcji kolizji, dynamiczną pętlę renderowania sceny, manipulację bryłami w czasie rzeczywistym oraz progresywny wzrost poziomu trudności.

**Wersja demonstracyjna (Live Demo):** [adikungen.github.io](https://adikungen.github.io/Projekt_IAM_Budny_Adrian_PAW3/)

<p align="center">
  <img src="https://raw.githubusercontent.com/AdiKungen/Projekt_IAM_Budny_Adrian_PAW3/main/docs/gifs/demo.gif" alt="Block Fall 3D Demo" width="700">
</p>

---

## Backend & Architektura Korporacyjna / JVM

### [Aplikacja do utworzenia profilu biometrycznego z cech wyznaczonych na podstawie aktywności użytkownika (KDA)](https://github.com/AdiKungen/Aplikacja_Magisterska_Budny_Adrian_MUI1)
`Java 17` | `JavaFX 21` | `FXML` | `CSS` | `Scene Builder`

Aplikacja badawcza zrealizowana w ramach pracy inżynierskiej i magisterskiej, służąca do tworzenia profilu biometrycznego użytkownika na podstawie dynamiki pisania na klawiaturze (_ang._ Keystroke Dynamics). Składa się z modularnego potoku analitycznego realizującego: wstępne filtrowanie szumu pomiarowego, ekstrakcję zależności czasowych, eliminację wartości odstających oraz wyliczanie wielowymiarowych wektorów cech biometrycznych.

<p align="center">
  <img src="https://raw.githubusercontent.com/AdiKungen/Aplikacja_Magisterska_Budny_Adrian_MUI1/main/docs/gifs/demo.gif" alt="KDA Demo" width="700">
</p>

---

### [Booker - System Wypożyczalni Książek](https://github.com/AdiKungen/Projekt_JPDSI2_Budny_Adrian_PAW3)
`Java 17` | `Jakarta EE 10` | `JSF (PrimeFaces 13)` | `EJB 3.x` | `JPA / Hibernate` | `WildFly` | `MariaDB`

Trójwarstwowa aplikacja korporacyjna (EAR) do zarządzania wypożyczalnią książek oparta na bezstanowych ziarnach sesyjnych (`@Stateless`), integracji JPA z bazą relacyjną oraz dynamicznym interfejsie PrimeFaces. Obsługuje koszyk wypożyczeń z konfigurowalnym czasem najmu, leniwe ładowanie katalogu (`LazyDataModel`) oraz moduł pracowniczy z automatyczną kalkulacją kar za nieterminowe zwroty.

<p align="center">
  <img src="https://raw.githubusercontent.com/AdiKungen/Projekt_JPDSI2_Budny_Adrian_PAW3/main/docs/gifs/demo.gif" alt="Booker Demo" width="700">
</p>

---

## Data Science & Machine Learning

### [Biometric Classifier - Narzędzie do analizy i klasyfikacji danych biometrycznych](https://github.com/AdiKungen/Projekt_WZKKDB_Budny_Adrian_MUI1)
`Python 3.13` | `Streamlit` | `Scikit-learn` | `Imbalanced-learn` | `Pandas` | `Plotly Express`

Interaktywne narzędzie analityczne wspierające przejście przez kompletny cykl uczenia maszynowego (_ang._ ML pipeline) bez pisania kodu. Umożliwia zaawansowany preprocessing danych (imputacja braków, normalizacja, resampling za pomocą `SMOTE`, `ADASYN`, `TomekLinks`), trójwymiarową redukcję wymiarowości `PCA 3D` oraz jednoczesne benchmarkowanie skuteczności klasyfikatorów (`Random Forest`, `k-NN`, `SVM`).

**Wersja demonstracyjna (Live Demo):** [biometric-classifier.streamlit.app](https://biometric-classifier.streamlit.app/) *(Dane testowe: [`demo-data/data.csv`](https://github.com/AdiKungen/Projekt_WZKKDB_Budny_Adrian_MUI1/blob/main/demo-data/data.csv))*

<p align="center">
  <img src="https://raw.githubusercontent.com/AdiKungen/Projekt_WZKKDB_Budny_Adrian_MUI1/main/docs/screenshots/single_classification.png" alt="Biometric Classifier" width="700">
</p>

---

## Aplikacje Mobilne

### [Asystent Tempa Biegu - Narzędzie do kontroli i stabilizacji prędkości z wykorzystaniem GPS](https://github.com/AdiKungen/Projekt_PAM_Budny_Adrian_PAW3)
`Kotlin` | `Android SDK (API 19–34)` | `Data Binding` | `LocationManager` | `Haptics / ToneGenerator`

Aplikacja mobilna wspierająca biegaczy w utrzymaniu stałego tempa poprzez sensoryczny feedback (sygnały dźwiękowe i wibracje) bez konieczności patrzenia na ekran. Wyposażona w algorytm odrzucania anomalii i zakłóceń GPS (*anti-teleportation filter*), 3-sekundowy bufor stabilizacyjny eliminujący fałszywe alerty oraz pełną optymalizację zużycia baterii w cyklu życia aktywności.

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
