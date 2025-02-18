# SKT nga UNO Robotics

**SKT** është një zgjidhje IoT nga **UNO Robotics** e cila mundëson kontrollin dhe grumbullimin e të dhënave në fusha të ndryshme. Deri tani është testuar dhe implementuar matja e temperaturës dhe lagështirës së një dhome, temperatura e një objekti (si p. sh. një tubi kaldaje), rryma elektrike dhe tymi. SKT është gjithmonë në zhvillim për të plotësuar çdo kërkesë.

[![SKT Dokumentimi](https://img.shields.io/badge/Repository-SKT-green)](https://github.com/UNO-Robotics-AL/SKT)

---

## Tabela e Përmbajtjes

1. [Përshkrim i Përgjithshëm](#përshkrim-i-përgjithshëm)
2. [Veçoritë Kyçe](#veçoritë-kyçe)
3. [Sensorët dhe Protokollet](#sensorët-dhe-protokollet)
4. [Projekte të Zbatuara](#projekte-të-zbatuara)
5. [Mbledhja dhe Përpunimi i të Dhënave](#mbledhja-dhe-përpunimi-i-të-dhënave)
6. [Instalimi dhe Mirëmbajtja](#instalimi-dhe-mirëmbajtja)
7. [Përmirësimet në të Ardhmen](#përmirësimet-në-të-ardhmen)
8. [Kontaktet dhe Mbështetja](#kontaktet-dhe-mbështetja)

---

## Përshkrim i Përgjithshëm

SKT është një produkt i plotë IoT i projektuar për zgjidhje me rendiment të lartë, lehtësisht i zgjerueshëm dhe i zbatueshëm. Fillimisht u projektua vetëm për matje të kaldajave dhe çillerave (temperaturat), por gjithashtu i janë shtuar dhe këto matje:

- **Temperatura dhe Lagështira e Dhomës**
- **Temperatura e Objekteve** (p. sh. tubat e kaldajës)
- **Rrymë Elektrike**
- **Dallues Tymi** (alarm zjarri)

Teksa vazhdojmë punën për të sjellë risi, do të shtojmë sensorët dhe matjet e mundshme që të plotësojmë kërkesat e klientëve. SKT është i përshtatshëm dhe për vende të largëta (p. sh. vendet malore), pasi përdor LoRa për të radiokomunikuar në distanca të mëdha dhe 4G (me kartë SIM) -- duke shfrytëzuar MQTT për lidhjen dhe dërgimin e të dhënave në ThingSpeak.

---

## Veçoritë Kyçe

- **Kontroll në Kohë Reale:**  
  Grumbullimi i të dhënave në kohë reale dhe paraqitja e tyre në ThingSpeak.

- **Ndërlidhje të Përparuara:**  
  - **LoRa:** mundëson komunikimin në distanca të mëdha edhe në mjedise të vështira për radiokomunikim.
  - **Lidhje 4G (me kartë SIM):** mundëson lidhjen në Internet në vende të largëta.

- **Komunikim i Sigurtë dhe me Rendiment:**  
  Përdoret **MQTT** për dërgim të dhënash në mënyrë të sigurtë dhe pa ngarkesë.

- **Analizë e Thelluar e të Dhënave:**  
  Shfrytëzohet platforma ThingSpeak për paraqitjen grafike të të dhënave, analizimi i tyre dhe njoftimet ose alarmet e nevojshme.

- **Zgjidhje të Posaçme:**  
  SKT është projektuar për t'u përshtatur me kërkesa specifike dhe me sensorë të ndryshëm.

---

## Sensorët dhe Protokollet

SKT deri në këtë çast mbështet këto lloje sensorësh:

- **Sensorë Analogë**
- **Sensorë Digjitalë**
- **Sensorë I2C**
- **Sensorë 1-Wire**

*Në përmirësimet e mëtejshme të produktit është në vëmendje shtimi i protokolleve të sensorëve që mund të përdoren me SKT.*

---

## Projekte të Zbatuara

SKT nuk është vetëm koncept - është zbatuar në projekte ekzistuese. Ne kemi kanale publike në ThingSpeak të cilat afishojnë të dhëna nga disa prej projekteve të instaluara. Nëse juve ju intereson matja e kaldajave, matjet mjedisore ose zbatime të tjera specifike, projektet e zbatuara vërtetojnë cilësinë që ka SKT.

*Nëse dëshironi, ne mund të ju mundësojmë qasje për kanalet tona publike të ThingSpeak ose një listë vendesh ku është instaluar.*

---

## Mbledhja dhe Përpunimi i të Dhënave

SKT përdor platformën [ThingSpeak](https://thingspeak.com/) për të arritur:

- **Paraqitje Grafike në Kohë Reale:**  
  Grafikë sipas kërkesës për të dhënat.

- **Analizim i Thelluar:**  
  Analizime të dhënash në MATLAB dhe mundësi integrimi me API.

- **Dërgim i Sigurtë të Dhënash:**  
  I bazuar në MQTT, SKT arrin një dërgim të dhënash të sigurtë dhe të besueshëm.

- **Aplikacioni në Zhvillim:**  
  Gjithashtu po ndërtojmë një aplikacion për telefona dhe për kompjutera, që do të marrë të dhënat nga ThingSpeak dhe do ta bëjë akoma më të personalizuar SKT-në.

---

## Instalimi dhe Mirëmbajtja

Deri më tani, instalimi kryhet vetëm nga personeli i UNO Robotics për të patur një saktësi më të lartë. Teknikët tanë të specializuar merren që nga projektimi dhe deri te zbatimi i projektit.

- **Instalim Profesional:**  
  Ne merremi me çdo hallkë të projektit, në mënyrë që integrimi i tij me sistemet ekzistuese të mos ketë probleme.
  
- **Zgjidhje të Posaçme, sipas Kërkesës:**  
  Na kontaktoni që të bisedojmë për zgjidhjet e mundshme dhe sensorëve sipas nevojës që keni.

---

## Përmirësimet në të Ardhmen

Disa nga përmirësimet që po punojmë t'i shtojmë:

- **Aplikacioni për Telefona dhe Kompjutera:**  
  Ndërfaqe më e personalizuar për përdoruesin dhe veçori të shtuara.

- **Zgjerimi i Protokolleve të Sensorëve:**  
  Do të shtojmë protokollet që SKT mund të përdorë, që do të shtojë numrin dhe llojin e sensorëve që mund të lidhen.

- **Përmirësimi i Sigurisë dhe Analizimit:**  
  Enkriptimi i të dhënave, dallimi automatik i anomalive dhe metoda analitike të tjera janë në punë e sipër për t'u shtuar.

- **Zbatimi në Fusha të Tjera:**  
  Vazhdimi i instalimeve në fusha të ndryshme në mënyrë që SKT të ketë më shumë horizonte përdorimi.

---

## Kontaktet dhe Mbështetja

Për pyetje, kërkesa apo interesim për SKT ju lutemi na kontakoni në adresat:

- **GitHub:**  
  [Krijoni një "issue"](https://github.com/UNO-Robotics-AL/SKT/issues)

- **Email:**  
  [info@uno-robotics.com](mailto:info@uno-robotics.com)

- **Faqja Zyrtare e Internetit:**  
  *www.uno-robotics.com*


---

**Përfundimi:**  
SKT nga UNO Robotics ofron një zgjidhje IoT të testuar dhe të sigurtë, e përshtatshme për shumë përdorime të ndryshme në mjedise të brendshme, të jashtme etj. Duke shfrytëzuar teknologji të përparuara si LoRa, 4G, MQTT dhe organizimin e të dhënave nëpërmjet ThingSpeak, SKT është mirëprojektuar për t'u zgjeruar sipas nevojës duke ruajtur sigurinë dhe besueshmërinë e sistemit. Mos ngurroni të na kontaktoni për çdo pyetje rreth SKT.
