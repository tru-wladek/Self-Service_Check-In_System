## **Wstęp**  
Nazywam się Władek i w tej prezentacji przedstawię Państwu swój **model systemu samoobsługowej odprawy pasażerskiej**. Model ten stworzyłem **w ramach mojej pracy inżynierskiej** na uczelni. W prezentacji skupię się na najważniejszych etapach projektu, aby nie było konieczności czytania pełnej wersji opracowania, która liczy ponad 100 stron :smiley:.  

---

## **Dlaczego ten projekt?**  
Podczas pracy na lotnisku wielokrotnie **wykonywałem monotonne czynności** związane z obsługą pasażerów, takie jak drukowanie kart pokładowych czy nadawanie bagażu do luku. W pewnym momencie zrozumiałem cały proces i przestałem się rozwijać, nie zdobywałem nowych umiejętności. **To zmotywowało mnie** do stworzenia **systemu, który zautomatyzuje podstawowe oraz bardziej złożone czynności** związane z odprawą pasażerów.  

---

## **Jaki jest główny cel?**  
Głównym celem projektu było **zaprojektowanie modelu systemu** samoobsługowej odprawy pasażerów, **dostosowanego do specyfiki Lotniska Chopina oraz potrzeb podróżnych**. Po wdrożeniu system działałby w pełni autonomicznie, zwiększając efektywność odprawy i minimalizując konieczność interwencji personelu. Pozwoliłoby to obniżyć koszty operacyjne oraz zwiększyć satysfakcję pasażerów dzięki szybszej obsłudze biletowo-bagażowej.  

---

## **Jakie było moje podejście?**  
Każdy projekt wymaga jasno określonych zadań, które prowadzą do realizacji głównego celu.  

### **1. Identyfikacja kluczowych funkcji po przeprowadzeniu benchmarkingu**  
Przeanalizowałem dostępne systemy typu DCS (*Departure Control System*), aby zrozumieć, jakie funkcje są standardowo wykorzystywane w operacjach lotniczych. Szczególnie skupiłem się na rozwiązaniach oferowanych przez firmę Amadeus.

### **2. Zrozumienie preferencji użytkowników poprzez ankietę**  
Po określeniu pełnego zakresu możliwych funkcjonalności systemu musiałem zidentyfikować te, które są najbardziej pożądane przez pasażerów Lotniska Chopina. W tym celu przeprowadziłem ankietę wśród 50 osób.  

### **3. Analiza preferencji i wybór kluczowych funkcji**  
Na podstawie wyników badań określiłem, które funkcjonalności są najistotniejsze, a które można pominąć. Wykorzystałem kilka narzędzi analitycznych, takich jak:  
- **Metoda MaxDiff**  
- **Scenariusze użytkowania**  
- **Model Kano** (który, okazał się najbardziej efektywny)  

Z ponad 50 funkcji wybrałem **14 kluczowych dla pasażerów** oraz **8 niezbędnych do operacyjnego działania systemu**.  

---

## **Modelowanie systemu**  
W tej części pozwolę, aby diagramy mówiły same za siebie.  

### **Diagramy UML**
- Diagram przypadków użycia (poziom 1)
![UD-1](https://github.com/user-attachments/assets/3fbfb689-546a-4eac-abff-d74ac7f7cf31)
- Diagram przypadków użycia (poziom 2)
![UD-2](https://github.com/user-attachments/assets/aec16cbe-20c2-44e4-b9a7-361039ae9637)
- Diagram klas (struktura systemu)  
![CLD](https://github.com/user-attachments/assets/4e029995-2282-4e0f-8d74-3403369a30cd)

### **Diagramy BPMN**  
  - Proces Wyszukiwania Rezerwacji 
![BPMN-proces_znalezienia_rezrwacji](https://github.com/user-attachments/assets/c4005864-2519-4cc0-bffc-978524780183)
  - Proces Weryfikacji Pasażera
![BPMN-proces-weryfikacji](https://github.com/user-attachments/assets/5cf51f6d-5928-4070-8013-78ea1b3aef8e)
  - Proces Nadania Bagażu
![BPMN-proces_nadania_bagazu](https://github.com/user-attachments/assets/8feec437-b3e5-41aa-a93b-133544bf8886)
  - Proces Przydzielenia Miejsca w Samolocie
![BPMN-proces_wyboru-miejsc](https://github.com/user-attachments/assets/e739f922-fa67-41f0-9b46-133ab79905e3)
  - Proces Zmiany Lotu
![BPMN-proces-zmiany-lotu](https://github.com/user-attachments/assets/1b28fa10-62ac-4fe1-9dd4-f6f72a8a827f)

---

## **Narzędzia i technologie**  
W projekcie wykorzystałem następujące narzędzia:  
- **LucidChart** – do tworzenia diagramów UML i BPMN  
- **MS Office (Excel, Word)** – do analizy danych i dokumentacji  
- **Google Forms** – do przeprowadzania ankiet  
- **Figma** – do projektowania prototypu interfejsu
- i inne

---  

## **Największe wyzwania:**  
1. **Branżowa specyfika** – Pomimo praktycznego doświadczenia, musiałem zgłębić procesy obsługi pasażerów realizowane przez firmy handlingowe.  
2. **Ankiety** – Pierwsza wersja ankiety miała błędną strukturę, przez co pasażerowie zaznaczali niemal każdą funkcję jako "najbardziej przydatną". Aby uzyskać bardziej precyzyjne wyniki, musiałem opracować nową metodologię badań, z wykorzystaniem odpowiednich metod badawczych.
3. **Organizacja pracy** – Ustalony deadline wymagał ode mnie efektywnego zarządzania czasem oraz priorytetyzacji kluczowych etapów projektu. Początkowo było to wyzwaniem, ale ostatecznie udało się dopracować skuteczny plan działania. 

## **Czego się nauczyłem?**  
1. **Prowadzenia badań ankietowych** – W szczególności stosowania badań pilotażowych, aby wcześniej wykryć błędy w pytaniach.  
2. **Lepszej organizacji pracy** – Skupiłem się na priorytetowych zadaniach, zamiast tracić czas na te najłatwiejsze.  
3. **Myślenia analitycznego i biznesowego** – Zrozumiałem, jak rozwiązania IT mogą usprawniać procesy biznesowe w branży lotniczej.  
4. **Zastosowania metod analitycznych** – W praktyce wykorzystałem m.in. analizę SWOT, Metodę MaxDiff oraz Model Kano.  

---

## **Podsumowanie**  

Kilkumiesięczna praca w końcu przyniosła efekty: **model systemu został poprawnie opracowany**, jest zwięzły oraz zawiera dodatkowy element – **prototyp interfejsu**, który odzwierciedla ekrany w najważniejszych procesach dla pasażera. Został pozytywnie oceniony przez **Mgr inż. Alinę Stasiecką** oraz **dr inż. Pawła Drogiego**.





