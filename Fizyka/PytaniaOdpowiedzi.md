# Fizyka Pytania:

## Część 1

### 1. Obliczyć siłę działającą między dwoma ładunkami $5 \times 10^{-5} C$ odległymi o $3$ metry

Do obliczenia siły działającej między dwoma ładunkami elektrycznymi możemy użyć prawa Coulomba. Prawo Coulomba opisuje siłę elektrostatyczną między dwoma punktowymi ładunkami elektrycznymi i jest wyrażone wzorem:

$F = k_e \frac{q_1 q_2}{r^2}$

gdzie:

-$F$ to siła elektrostatyczna, -$k_e$ to stała elektrostatyczna (Coulomba), której wartość wynosi$k_e \approx 8.9875 \times 10^9 \, \text{N} \cdot \text{m}^2 / \text{C}^2$, -$q_1$ i$q_2$ to wartości ładunków elektrycznych, -$r$ to odległość między ładunkami.

W naszym przypadku:

-$q_1 = q_2 = 5 \times 10^{-5} \, \text{C}$, -$r = 3 \, \text{m}$.

Podstawiając te wartości do wzoru, obliczamy siłę$F$:

$F = k_e \frac{q_1 q_2}{r^2}$

$F = 8.9875 \times 10^9 \, \frac{(5 \times 10^{-5}) (5 \times 10^{-5})}{3^2}$

Obliczamy:

$F = 8.9875 \times 10^9 \, \frac{(25 \times 10^{-10})}{9}$

$F = 8.9875 \times 10^9 \, \frac{25 \times 10^{-10}}{9}$

$F = 8.9875 \times 10^9 \times 2.7778 \times 10^{-11}$

$F = 249.6525 \times 10^{-2}$

$F = 2.496525$

Zatem siła działająca między tymi dwoma ładunkami wynosi około$2.50 \, \text{N}$.

### 2. Sa dwa ładunki $3 \times 10^{-7} C$ i $5 \times 10^{-7} C$ odległe o metr. W ktorym miejscu natężenie pola elektrycznego będzie wynosić zero.

Aby znaleźć punkt, w którym natężenie pola elektrycznego wynosi zero między dwoma ładunkami$q_1 = 3 \times 10^{-7} \, \text{C}$ i$q_2 = 5 \times 10^{-7} \, \text{C}$ oddalonymi od siebie o$1 \, \text{m}$, musimy znaleźć miejsce, w którym pola elektryczne wytwarzane przez te ładunki się znoszą.

### Kroki rozwiązania:

1. **Zdefiniuj układ współrzędnych:**
   Umieśćmy ładunek$q_1$ w punkcie$x = 0$ i ładunek$q_2$ w punkcie$x = 1 \, \text{m}$. Szukamy punktu$x$ na osi$x$, gdzie natężenie pola elektrycznego$E$ wynosi zero.

2. **Natężenie pola elektrycznego:**
   Natężenie pola elektrycznego wytwarzane przez ładunek$q_1$ w odległości$x$ wynosi:

$$
 E_1 = \frac{q_1}{4 \pi \epsilon_0 x^2}
$$

Natężenie pola elektrycznego wytwarzane przez ładunek$q_2$ w odległości$1 - x$ wynosi:

$$
 E_2 = \frac{q_2}{4 \pi \epsilon_0 (1 - x)^2}
$$

3. **Warunek równowagi:**
   Pola elektryczne będą się znosić, gdy$E_1 = E_2$. Stąd:

$$
 \frac{q_1}{4 \pi \epsilon_0 x^2} = \frac{q_2}{4 \pi \epsilon_0 (1 - x)^2}
$$

4. **Uprość równanie:**

$$
 \frac{q_1}{x^2} = \frac{q_2}{(1 - x)^2}
$$

Podstawiając wartości$q_1 = 3 \times 10^{-7} \, \text{C}$ i$q_2 = 5 \times 10^{-7} \, \text{C}$:

$$
 \frac{3 \times 10^{-7}}{x^2} = \frac{5 \times 10^{-7}}{(1 - x)^2}
$$

5. **Rozwiąż równanie:**

$$
 \frac{3}{x^2} = \frac{5}{(1 - x)^2}
$$

Krzyżowo mnożąc:

$$
 3 (1 - x)^2 = 5 x^2
$$

$$
 3 (1 - 2x + x^2) = 5 x^2
$$

$$
 3 - 6x + 3x^2 = 5x^2
$$

$$
 3 - 6x + 3x^2 - 5x^2 = 0
$$

$$
 3 - 6x - 2x^2 = 0
$$

$$
 2x^2 + 6x - 3 = 0
$$

6. **Rozwiąż równanie kwadratowe:**
   Równanie kwadratowe$2x^2 + 6x - 3 = 0$ możemy rozwiązać stosując wzory kwadratowe:

$$
 x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

gdzie$a = 2$,$b = 6$,$c = -3$.

$$
 x = \frac{-6 \pm \sqrt{6^2 - 4 \cdot 2 \cdot (-3)}}{2 \cdot 2}
$$

$$
 x = \frac{-6 \pm \sqrt{36 + 24}}{4}
$$

$$
 x = \frac{-6 \pm \sqrt{60}}{4}
$$

$$
 x = \frac{-6 \pm 2\sqrt{15}}{4}
$$

$$
 x = \frac{-3 \pm \sqrt{15}}{2}
$$

Wartości$x$ muszą być rzeczywiste i leżeć w przedziale$[0, 1]$.

$$
 x = \frac{-3 + \sqrt{15}}{2} \approx \frac{-3 + 3.87}{2} \approx \frac{0.87}{2} \approx 0.435
$$

### Wniosek:

Natężenie pola elektrycznego będzie wynosić zero w punkcie$x \approx 0.435 \, \text{m}$ od ładunku$3 \times 10^{-7} \, \text{C}$, czyli$0.565 \, \text{m}$ od ładunku$5 \times 10^{-7} \, \text{C}$.

### 3. Jak daleko trzeba umieścić dwa protony by siła między nimi była równa sile przeyciągania grawitacyjnego protonu na Ziemi.

Aby znaleźć odległość, na jaką musimy umieścić dwa protony, aby siła elektrostatyczna między nimi była równa sile przyciągania grawitacyjnego działającej na proton na powierzchni Ziemi, musimy porównać dwie siły:

1. **Siła elektrostatyczna między dwoma protonami:**

$F_e = k \frac{e^2}{r^2}$

gdzie:

-$k$ to stała elektrostatyczna (Coulomba),$k \approx 8.99 \times 10^9 \, \text{N} \cdot \text{m}^2 / \text{C}^2$, -$e$ to ładunek elementarny,$e \approx 1.6 \times 10^{-19} \, \text{C}$, -$r$ to odległość między protonami.

2. **Siła grawitacyjna działająca na proton na powierzchni Ziemi:**

$F_g = m_p g$

gdzie:

-$m_p$ to masa protonu,$m_p \approx 1.67 \times 10^{-27} \, \text{kg}$, -$g$to przyspieszenie ziemskie,$g \approx 9.8 \, \text{m/s}^2$.

Naszym celem jest znalezienie$r$, dla którego$F_e = F_g$.

Zatem:

$k \frac{e^2}{r^2} = m_p g$

Rozwiązując dla$r$:

$r^2 = k \frac{e^2}{m_p g}$
$r = \sqrt{k \frac{e^2}{m_p g}}$

Podstawiamy wartości:

$k \approx 8.99 \times 10^9 \, \text{N} \cdot \text{m}^2 / \text{C}^2$
$e \approx 1.6 \times 10^{-19} \, \text{C}$
$m_p \approx 1.67 \times 10^{-27} \, \text{kg}$
$g \approx 9.8 \, \text{m/s}^2$

Obliczamy:

$r = \sqrt{8.99 \times 10^9 \cdot \frac{(1.6 \times 10^{-19})^2}{1.67 \times 10^{-27} \cdot 9.8}}$

Najpierw obliczamy wyrażenie pod pierwiastkiem:

$\frac{(1.6 \times 10^{-19})^2}{1.67 \times 10^{-27} \cdot 9.8} = \frac{2.56 \times 10^{-38}}{1.6366 \times 10^{-26}} \approx 1.564 \times 10^{-12}$

Teraz mnożymy przez$k$:

$8.99 \times 10^9 \cdot 1.564 \times 10^{-12} \approx 14.048$

I obliczamy pierwiastek kwadratowy:

$r = \sqrt{14.048} \approx 3.75 \, \text{m}$

Zatem odległość, na jaką musimy umieścić dwa protony, aby siła elektrostatyczna między nimi była równa sile przyciągania grawitacyjnego działającej na proton na powierzchni Ziemi, wynosi około 3.75 metra.

### 4. Obliczyć siłę działającą na dipol elektryczny zbudowany z ładunków$+10^{-6} C$ i$-10^{-6} C$ odległych o centymetr w polu o natężeniu$10^3 V/m$

Aby obliczyć siłę działającą na dipol elektryczny, użyjemy wzoru na moment dipolowy i związaną z nim siłę.

Moment dipolowy dla dwóch punktowych ładunków$q$ i$-q$ o odległości$d$ można zapisać jako:
$$ p = q \cdot d$$
gdzie:

-$q$ to wartość ładunku ($q = 10^{-6}$ C), -$d$ to odległość między ładunkami ($d = 0.01$ m).

Moment dipolowy wynosi:
$p = (10^{-6} \text{ C}) \times 0.01 \text{ m} = 10^{-8} \text{ C} \cdot \text{m}$

Siła działająca na dipol elektryczny w jednorodnym polu elektrycznym można obliczyć ze wzoru:
$F = pE$
gdzie:

-$F$ to siła, -$p$ to moment dipolowy, -$E$ to natężenie pola elektrycznego.

Podstawiając wartości, otrzymujemy:
$F = (10^{-8} \text{ C} \cdot \text{m}) \times 10^3 \text{ V/m} = 10^{-5} \text{ N}$

Siła działająca na dipol elektryczny zbudowany z ładunków$+10^{-6}$ C i$-10^{-6}$ C, odległych o 1 centymetr w polu o natężeniu$10^3$ V/m, wynosi$10^{-5}$

### 5. Znaleźć prędkość protonu po przebyciu 20 metrów w jednorodnym polu o natężeniu 15V/cm, jeżeli na początku był w spoczynku

Aby znaleźć prędkość protonu po przebyciu 20 metrów w jednorodnym polu elektrycznym o natężeniu 15 V/cm, możemy zastosować zasady dynamiki i energii.

Najpierw przeliczmy natężenie pola elektrycznego z V/cm na V/m:
$15 \text{ V/cm} = 1500 \text{ V/m}$

Pole elektryczne wywołuje siłę na protonie, którą można obliczyć za pomocą wzoru:
$F = qE$
gdzie:

-$q$ to ładunek protonu ($q = 1.6 \times 10^{-19} \text{ C}$ ), -$E$ to natężenie pola elektrycznego ($E = 1500 \text{ V/m}$ ).

Obliczmy siłę działającą na proton:
$F = 1.6 \times 10^{-19} \text{ C} \times 1500 \text{ V/m} = 2.4 \times 10^{-16} \text{ N}$

Następnie użyjemy drugiej zasady dynamiki Newtona:
$F = ma$
gdzie:

-$m$ to masa protonu ($m = 1.67 \times 10^{-27} \text{ kg}$ ),
-$ a$ to przyspieszenie protonu.

Obliczmy przyspieszenie:
$a = \frac{F}{m} = \frac{2.4 \times 10^{-16} \text{ N}}{1.67 \times 10^{-27} \text{ kg}} \approx 1.44 \times 10^{11} \text{ m/s}^2$

Proton startuje z prędkością początkową$v_0 = 0$ i przebywa drogę$s = 20 \text{ m}$. Użyjemy równania kinematycznego do obliczenia prędkości końcowej:

$v^2 = v_0^2 + 2as$

$v^2 = 0 + 2 \times 1.44 \times 10^{11} \text{ m/s}^2 \times 20 \text{ m}$

$v^2 = 2 \times 1.44 \times 10^{11} \times 20$

$v^2 = 5.76 \times 10^{12}$

$v = \sqrt{5.76 \times 10^{12}}$

$v \approx 2.4 \times 10^6 \text{ m/s}$

Prędkość protonu po przebyciu 20 metrów w jednorodnym polu elektrycznym o natężeniu 15 V/cm wynosi około:

$2.4 \times 10^6 \text{ m/s}$.

### 6. Wykazać, że jednorodnie naładowana kula wytwarza pole identyczne z polem wytwarzanym przez ładunek punktowy umieszczony w jej środku, Określić wartość tego ładunku.

Aby wykazać, że jednorodnie naładowana kula wytwarza pole identyczne z polem wytwarzanym przez ładunek punktowy umieszczony w jej środku, możemy skorzystać z twierdzenia Gaussa. Załóżmy, że mamy kulkę o promieniu R i ładunku Q, oraz że wewnątrz kuli jest umieszczony ładunek punktowy q.

Zgodnie z twierdzeniem Gaussa, pole elektryczne E w dowolnym punkcie wewnątrz kuli jednorodnie naładowanej jest proporcjonalne do gęstości ładunku ρ w danym punkcie i odległości od środka kuli. W przypadku kuli E można wyrazić jako:

$E = k ⋅ Q_wewn / r^2$

gdzie:

-$k$ to stała elektrostatyczna$(8.9875 × 10^9 N·m^2/C^2)$, -$Q_{wewn}$ to ładunek znajdujący się wewnątrz kuli, -$r$ to odległość od środka kuli.

Dla kuli o promieniu$R$ i ładunku$Q$,$Q_{wewn} = Q$.

Natomiast pole elektryczne wytwarzane przez punktowy ładunek$q$ w odległości r od niego wynosi:

$E' = k ⋅ q / r^2$

Jeśli pole elektryczne wytworzone przez jednorodnie naładowaną kulę w punkcie, który jest w odległości r od jej środka, jest takie samo jak pole wytworzone przez ładunek punktowy q w punkcie, który jest w odległości r od środka kuli, to muszą zachodzić równości:

$E = E'$

$k ⋅ Q / r^2 = k ⋅ q / r^2$

Zatem:

$Q = q$

Oznacza to, że ładunek wewnętrzny kuli jest równy ładunkowi punktowemu umieszczonemu w jej środku.

### 7. Wykazać, że na bryle zbudowanej z przewodnika ładunek zbiera się na ostrzach.

Aby wykazać, że ładunek na przewodniku zbiera się na ostrzach, można posłużyć się zasadami elektrostatyki. Kluczowym pojęciem jest tutaj gęstość powierzchniowa ładunku oraz pojęcie potencjału elektrostatycznego.

1. **Równanie Laplace'a i równanie Poissona**:
   Potencjał elektrostatyczny$\phi$ w próżni spełnia równanie Laplace'a:

$$
 \nabla^2 \phi = 0
$$

W przypadku, gdy ładunek jest obecny w objętości, równanie Laplace'a zamienia się na równanie Poissona:

$$
 \nabla^2 \phi = -\frac{\rho}{\epsilon_0}
$$

gdzie$\rho$ jest gęstością ładunku w objętości, a$\epsilon_0$ to przenikalność elektryczna próżni.

2. **Warunki brzegowe**:
   Dla przewodnika, potencjał elektrostatyczny na powierzchni musi być stały, ponieważ przewodnik w stanie równowagi elektrostatycznej nie ma wewnętrznych różnic potencjału. Stąd wynika, że na powierzchni przewodnika:

$$
 \phi = \text{const}
$$

3. **Pole elektryczne i gęstość powierzchniowa ładunku**:
   Pole elektryczne$\mathbf{E}$ jest związane z potencjałem przez:

$$
 \mathbf{E} = -\nabla \phi
$$

Gdy pole elektryczne jest prostopadłe do powierzchni przewodnika, gęstość powierzchniowa ładunku$\sigma$ jest związana z polem elektrycznym tuż przy powierzchni przez:

$$
 \mathbf{E} = \frac{\sigma}{\epsilon_0} \hat{n}
$$

gdzie$\hat{n}$ to wektor normalny do powierzchni.

4. **Krzywizna powierzchni a koncentracja ładunku**:
   Przyjrzyjmy się teraz geometrii powierzchni przewodnika. Pole elektryczne przy powierzchni przewodnika jest bardziej intensywne w miejscach, gdzie powierzchnia ma większą krzywiznę (czyli jest bardziej ostra). Można to formalnie wyjaśnić przez rozważenie krzywizny i analizy potencjału elektrycznego w pobliżu takich miejsc.

5. **Pojęcie krzywizny powierzchni**:
   Krzywizna powierzchni w punkcie jest opisana przez promienie krzywizny w dwóch głównych kierunkach:$\frac{1}{R_1}$ i$\frac{1}{R_2}$. W miejscach ostrych promienie krzywizny są małe, a zatem wartości$\frac{1}{R_1}$ i$\frac{1}{R_2}$ są duże.

6. **Zależność pola elektrycznego od krzywizny**:
   W miejscach o dużej krzywiźnie, pole elektryczne jest bardziej intensywne, ponieważ linie pola zbiegają się bardziej stromo. To oznacza, że gęstość powierzchniowa ładunku$\sigma$ będzie większa w tych miejscach, ponieważ:

$$
 \sigma = \epsilon_0 E
$$

gdzie$E$ jest większe tam, gdzie krzywizna jest większa.

7. **Wniosek**:
   W konsekwencji, ładunek zbiera się na ostrzach przewodnika, ponieważ tam pole elektryczne jest najsilniejsze ze względu na dużą krzywiznę powierzchni. Ostrza powodują lokalne zwiększenie gęstości powierzchniowej ładunku, co wynika bezpośrednio z rozkładu pola elektrycznego i zasad elektrostatyki.

Tak więc, używając pojęć potencjału elektrostatycznego, pola elektrycznego oraz krzywizny powierzchni, można wykazać, że ładunek na przewodniku zbiera się na ostrzach.

### 8. Wykazać, że potencjał na powierzchni bryły zbudowanej z przewodnika po pewnym czasi dąży do stałego rozkładu

Aby wykazać, że potencjał na powierzchni bryły zbudowanej z przewodnika po pewnym czasie dąży do stałego rozkładu, można skorzystać z kilku podstawowych własności przewodników oraz zasad elektrostatyki. Rozważmy następujące kroki:

1. **Początkowy rozkład ładunku i potencjału:**

   - Zakładamy, że przewodnik jest w stanie nierównowagi elektrostatycznej, czyli istnieją różnice potencjałów na jego powierzchni oraz przepływ ładunków wewnątrz przewodnika.

2. **Właściwości przewodnika:**

   - W przewodniku, ładunki swobodne mogą się poruszać. W odpowiedzi na różnice potencjałów, ładunki będą przemieszczać się z obszarów o wyższym potencjale do obszarów o niższym potencjale.
   - Proces ten będzie trwał do momentu, aż osiągnie się równowagę elektrostatyczną.

3. **Zasada równowagi elektrostatycznej:**

   - W stanie równowagi elektrostatycznej wewnątrz przewodnika nie ma przepływu prądu, czyli pole elektryczne wewnątrz przewodnika jest zerowe.
   - Ponieważ pole elektryczne jest gradientem potencjału, zerowe pole elektryczne implikuje, że potencjał jest stały wewnątrz przewodnika.
   - Na powierzchni przewodnika, potencjał również musi być stały, aby nie istniał przepływ prądu, co wynika z ciągłości pola elektrycznego.

4. **Mechanizm osiągania równowagi:**

   - Ładunki swobodne będą się przemieszczać, aż zrównają potencjały na całej powierzchni przewodnika.
   - Jeśli początkowo potencjały różnią się na powierzchni przewodnika, przepływ ładunków spowoduje, że różnice te będą maleć w czasie, aż osiągną jednorodny rozkład.

5. **Formalne uzasadnienie:**

   - Można skorzystać z równania ciągłości oraz równań Maxwella, aby opisać dyfuzję ładunków na powierzchni przewodnika.
   - Równanie dyfuzji ładunku$ \frac{\partial \sigma}{\partial t} = D \nabla^2 \sigma$, gdzie$ \sigma$ jest powierzchniową gęstością ładunku, a$ D$ jest współczynnikiem dyfuzji, opisuje proces wyrównywania się rozkładu ładunku.
   - W stanie stacjonarnym$\frac{\partial \sigma}{\partial t} = 0$, co implikuje, że$ \nabla^2 \sigma = 0$, czyli$\sigma$ jest stałe na powierzchni przewodnika.

6. **Podsumowanie:**
   - Potencjał na powierzchni przewodnika dąży do stałego rozkładu, ponieważ przewodniki dążą do równowagi elektrostatycznej, w której potencjał jest jednorodny.
   - Mechanizm ruchu ładunków swobodnych pod wpływem różnic potencjałów zapewnia, że ostatecznie potencjał na powierzchni przewodnika staje się stały.

W ten sposób dowodzimy, że potencjał na powierzchni przewodnika dąży do jednorodnego rozkładu w czasie.

### 9. Mamy dwie kule z przewodnika p promieniach$r= 5cm$ i$R= 40cm$. jedną z nich naładowano ładunkiem$10^{-6} C$ a następnie obie zetknięto. Obliczyć ładunek na każdej z kul

Aby obliczyć ładunek na każdej z kul po ich zetknięciu, możemy skorzystać z zasady zachowania ładunku oraz własności elektrostatycznych przewodników w równowadze.

### Dane:

- Kula mniejsza (1):$r = 5 \text{ cm} = 0,05 \text{ m}$
- Kula większa (2):$R = 40 \text{ cm} = 0,40 \text{ m}$
- Ładunek początkowy na jednej z kul:$Q_0 = 1 \times 10^{-6} \text{ C}$

### Proces:

1. **Zasada zachowania ładunku:**
   Całkowity ładunek w systemie przed zetknięciem jest równy całkowitemu ładunkowi w systemie po zetknięciu:

$$
 Q\_{\text{całk}} = Q_1 + Q_2 = 1 \times 10^{-6} \text{ C}
$$

gdzie$Q_1$ i$Q_2$ to ładunki na mniejszej i większej kuli po zetknięciu.

2. **Warunek równowagi:**
   Po zetknięciu, potencjały obu kul będą równe, ponieważ ładunki będą się przemieszczać aż do momentu wyrównania potencjałów. Potencjał na powierzchni przewodnika kuli o promieniu$r$ i ładunku$Q$ wynosi:

$$
 V = \frac{Q}{4 \pi \epsilon_0 r}
$$

gdzie$\epsilon_0$ jest przenikalnością elektryczną próżni.

Ponieważ potencjały muszą być równe:

$$
 V_1 = V_2
$$

czyli:

$$
 \frac{Q_1}{4 \pi \epsilon_0 r} = \frac{Q_2}{4 \pi \epsilon_0 R}
$$

Po uproszczeniu:

$$
 \frac{Q_1}{r} = \frac{Q_2}{R}
$$

$$
 Q_1 R = Q_2 r
$$

$$
 Q_2 = \frac{R}{r} Q_1
$$

$$
 Q_2 = \frac{0,40 \text{ m}}{0,05 \text{ m}} Q_1
$$

$$
 Q_2 = 8 Q_1
$$

3. **Łączne ładunki:**

$$
 Q_1 + Q_2 = 1 \times 10^{-6} \text{ C}
$$

Wstawiając$Q_2 = 8 Q_1$:

$$
 Q_1 + 8 Q_1 = 1 \times 10^{-6} \text{ C}
$$

$$
 9 Q_1 = 1 \times 10^{-6} \text{ C}
$$

$$
 Q_1 = \frac{1 \times 10^{-6} \text{ C}}{9}
$$

$$
 Q_1 = \frac{1}{9} \times 10^{-6} \text{ C}
$$

$$
 Q_1 \approx 1.11 \times 10^{-7} \text{ C}
$$

Teraz obliczamy$Q_2$:

$$
 Q_2 = 8 Q_1
$$

$$
 Q_2 = 8 \times 1.11 \times 10^{-7} \text{ C}
$$

$$
 Q_2 \approx 8.89 \times 10^{-7} \text{ C}
$$

Wynik:

- Ładunek na mniejszej kuli po zetknięciu:$Q_1 \approx 1.11 \times 10^{-7} \text{ C}$
- Ładunek na większej kuli po zetknięciu:$Q_2 \approx 8.89 \times 10^{-7} \text{ C}$

### 10. Znaleźć wzór na potencjał naładowanej nieskończenie długiej nici

Aby znaleźć wzór na potencjał naładowanej nieskończenie długiej nici (czyli naładowanego przewodzącego drutu), możemy użyć teorii elektrostatyki. Zakładamy, że drut ma jednorodną liniową gęstość ładunku$\lambda$ (ładunek na jednostkę długości).

### 1. Wprowadzenie współrzędnych:

Rozważmy nieskończenie długi, prosty drut, który jest naładowany z liniową gęstością ładunku$\lambda$. Wybieramy układ współrzędnych cylindrycznych$(r, \phi, z)$, gdzie drut leży wzdłuż osi$z$, a$r$ jest odległością od drutu.

### 2. Prawo Gaussa:

Aby znaleźć pole elektryczne$E$ w odległości$r$ od drutu, możemy użyć prawa Gaussa. Rozważmy walec o promieniu$r$ i wysokości$L$ symetrycznie otaczający drut. Zgodnie z prawem Gaussa:

$$
\oint_{\partial V} \mathbf{E} \cdot d\mathbf{A} = \frac{Q_{\text{inside}}}{\epsilon_0}
$$

gdzie$Q_{\text{inside}} = \lambda L$ jest całkowitym ładunkiem wewnątrz walca.

### 3. Symetria problemu:

Ze względu na symetrię, pole elektryczne$\mathbf{E}$ jest skierowane promieniście (od drutu) i ma jednakową wartość na powierzchni walca:

$$
E(r) \cdot 2 \pi r L = \frac{\lambda L}{\epsilon_0}
$$

Uproszczając, otrzymujemy:

$$
E(r) = \frac{\lambda}{2 \pi \epsilon_0 r}
$$

### 4. Potencjał elektryczny:

Potencjał elektryczny$V(r)$ w punkcie odległym o$r$ od drutu można znaleźć, integrując pole elektryczne wzdłuż promienia od$r_0$ do$r$:

$$
V(r) - V(r_0) = - \int_{r_0}^{r} E(r') \, dr'
$$

$$
V(r) - V(r_0) = - \int_{r_0}^{r} \frac{\lambda}{2 \pi \epsilon_0 r'} \, dr'
$$

### 5. Obliczenie całki:

$$
V(r) - V(r_0) = - \frac{\lambda}{2 \pi \epsilon_0} \int_{r_0}^{r} \frac{1}{r'} \, dr'
$$

$$
V(r) - V(r_0) = - \frac{\lambda}{2 \pi \epsilon_0} \left[ \ln r' \right]_{r_0}^{r}
$$

$$
V(r) - V(r_0) = - \frac{\lambda}{2 \pi \epsilon_0} (\ln r - \ln r_0)
$$

$$
V(r) - V(r_0) = - \frac{\lambda}{2 \pi \epsilon_0} \ln \left( \frac{r}{r_0} \right)
$$

### 6. Ustalanie punktu odniesienia:

Zazwyczaj potencjał jest mierzony względem nieskończoności, gdzie$V(\infty) = 0$. Jednak dla nieskończenie długiego drutu nie możemy tego użyć bezpośrednio, ponieważ$\ln(\infty)$ nie jest zdefiniowane. Możemy jednak przyjąć potencjał w punkcie$r_0$ jako punkt odniesienia:

$$
V(r) = V(r_0) - \frac{\lambda}{2 \pi \epsilon_0} \ln \left( \frac{r}{r_0} \right)
$$

### Ostateczny wzór:

Wybierając$r_0$ jako punkt odniesienia, możemy uprościć wzór:

$$
V(r) = - \frac{\lambda}{2 \pi \epsilon_0} \ln \left( \frac{r}{r_0} \right)
$$

Ten wzór opisuje potencjał elektryczny w odległości$r$ od nieskończenie długiej nici naładowanej ładunkiem o liniowej gęstości$\lambda$.

### 11. Znaleźć odpowiednik$\epsilon_0$ dla grawitacji

W elektrodynamice$\epsilon_0$ jest przenikalnością elektryczną próżni ($\epsilon_0$), która jest stałą fundamentalną opisującą, jak pole elektryczne oddziałuje z próżnią. Analogicznie, w grawitacji mamy stałą grawitacyjną$G$, która opisuje siłę przyciągania między masami. Poszukujemy odpowiednika$\epsilon_0$ w kontekście grawitacyjnym, który odnosiłby się do pola grawitacyjnego.

### 1. Prawa elektrostatyki i grawitacji:

- **Prawo Coulomba** w elektrostatyce:

$$
 F = \frac{1}{4\pi\epsilon_0} \frac{q_1 q_2}{r^2}
$$

gdzie$F$ jest siłą między dwoma ładunkami$q_1$ i$q_2$ oddalonymi od siebie o odległość$r$.

- **Prawo grawitacji Newtona**:
  $$
   F = G \frac{m_1 m_2}{r^2}
  $$
  gdzie$F$ jest siłą między dwoma masami$m_1$ i$m_2$ oddalonymi od siebie o odległość$r$.

### 2. Porównanie obu praw:

W obu przypadkach, siła jest odwrotnie proporcjonalna do kwadratu odległości i proporcjonalna do iloczynu odpowiednich wielkości (ładunków lub mas). Stałe$\frac{1}{4\pi\epsilon_0}$ i$G$ pełnią podobne role w swoich odpowiednich prawach.

### 3. Stała grawitacyjna$G$:

Stała grawitacyjna$G$ ma wartość:

$$
G \approx 6.67430 \times 10^{-11} \text{ m}^3 \text{ kg}^{-1} \text{ s}^{-2}
$$

### 4. Odpowiednik$\epsilon_0$ dla grawitacji:

Aby znaleźć bezpośredni odpowiednik$\epsilon_0$ w grawitacji, możemy przeanalizować struktury wzorów. W elektrostatyce,$\epsilon_0$ jest przenikalnością elektryczną próżni. W analogii grawitacyjnej, możemy zdefiniować stałą przenikalności grawitacyjnej$\epsilon_g$ w następujący sposób:

Porównując formuły sił:

$$
F_e = \frac{1}{4 \pi \epsilon_0} \frac{q_1 q_2}{r^2}
$$

$$
F_g = G \frac{m_1 m_2}{r^2}
$$

Możemy zdefiniować:

$$
\frac{1}{4 \pi \epsilon_g} = G
$$

Stąd:

$$
\epsilon_g = \frac{1}{4 \pi G}
$$

### 5. Obliczenie wartości$\epsilon_g$:

Podstawiając wartość$G$:

$$
\epsilon_g = \frac{1}{4 \pi \times 6.67430 \times 10^{-11} \text{ m}^3 \text{ kg}^{-1} \text{ s}^{-2}}
$$

$$
\epsilon_g \approx \frac{1}{8.37758 \times 10^{-10} \text{ m}^3 \text{ kg}^{-1} \text{ s}^{-2}}
$$

$$
\epsilon_g \approx 1.1927 \times 10^9 \text{ m}^{-3} \text{ kg} \text{ s}^2
$$

### 6. Wniosek:

Odpowiednikiem$\epsilon_0$ dla grawitacji jest stała$\epsilon_g$, gdzie:

$$
\epsilon_g = \frac{1}{4 \pi G}
$$

Stała ta pełni podobną rolę w grawitacji jak$\epsilon_0$ w elektrostatyce, opisując, jak pole grawitacyjne oddziałuje z próżnią.

### 12. Znaleźć potencjał dla nieskończonej naładowanej płaszczyzny

Aby znaleźć potencjał elektryczny wytworzony przez nieskończenie naładowaną płaszczyznę o jednorodnej gęstości powierzchniowej ładunku$\sigma$, musimy najpierw znaleźć pole elektryczne, a następnie obliczyć potencjał poprzez całkowanie pola elektrycznego.

### 1. Pole elektryczne:

Dla nieskończonej płaszczyzny o jednorodnej gęstości powierzchniowej ładunku$\sigma$, pole elektryczne jest jednorodne i skierowane prostopadle do powierzchni płaszczyzny. Zgodnie z prawem Gaussa, dla płaszczyzny o jednorodnej gęstości ładunku:

$$
E = \frac{\sigma}{2 \epsilon_0}
$$

Pole elektryczne$E$ jest stałe i skierowane prostopadle do płaszczyzny.

### 2. Potencjał elektryczny:

Potencjał elektryczny$V$ w odległości$z$ od płaszczyzny można znaleźć poprzez całkowanie pola elektrycznego wzdłuż osi$z$. Zakładamy, że płaszczyzna leży w płaszczyźnie$z = 0$ i pole elektryczne jest skierowane wzdłuż osi$z$.

$$
E = -\frac{dV}{dz}
$$

Stąd, potencjał w odległości$z$ od płaszczyzny (zakładając, że potencjał w punkcie odniesienia$z_0$ jest$V(z_0)$) wynosi:

$$
V(z) - V(z_0) = - \int_{z_0}^{z} E \, dz'
$$

Podstawiając wartość pola elektrycznego$E$:

$$
V(z) - V(z_0) = - \int_{z_0}^{z} \frac{\sigma}{2 \epsilon_0} \, dz'
$$

$$
V(z) - V(z_0) = - \frac{\sigma}{2 \epsilon_0} \int_{z_0}^{z} dz'
$$

$$
V(z) - V(z_0) = - \frac{\sigma}{2 \epsilon_0} (z - z_0)
$$

$$
V(z) = V(z_0) - \frac{\sigma}{2 \epsilon_0} (z - z_0)
$$

### 3. Ustalanie punktu odniesienia:

Aby uprościć wzór, możemy wybrać punkt odniesienia w$z_0 = 0$, czyli na samej płaszczyźnie, gdzie$V(z_0) = V_0$. Wtedy wzór na potencjał staje się:

$$
V(z) = V_0 - \frac{\sigma}{2 \epsilon_0} z
$$

W szczególnym przypadku, jeżeli przyjmiemy, że potencjał na płaszczyźnie wynosi zero ($V_0 = 0$), wzór na potencjał przyjmuje postać:

$$
V(z) = - \frac{\sigma}{2 \epsilon_0} z
$$

### Ostateczny wzór:

Potencjał elektryczny$V(z)$ w odległości$z$ od nieskończenie naładowanej płaszczyzny o jednorodnej gęstości powierzchniowej ładunku$\sigma$ wynosi:

$$
V(z) = - \frac{\sigma}{2 \epsilon_0} z
$$

Ten wzór zakłada, że potencjał na płaszczyźnie ($z = 0$) jest równy zero.

### 13. znaleźć potencjał od ładunków$q_1 = 3* 10^{-5} C$,$5* 10^{-5} C$ i$8*10^{-5} C$ w punkcie odległym od tych ładunków odpowiednio o 3,4 i 5 metrów

Aby znaleźć potencjał elektryczny$V$ w punkcie odległym o odpowiednie odległości od kilku ładunków, korzystamy z zasady superpozycji. Potencjał elektryczny wytworzony przez pojedynczy ładunek punktowy$q_i$ w odległości$r_i$ jest dany wzorem:

$$
V_i = \frac{q_i}{4 \pi \epsilon_0 r_i}
$$

Stała elektrostatyczna$\frac{1}{4 \pi \epsilon_0}$ wynosi w przybliżeniu$9 \times 10^9 \, \text{N} \cdot \text{m}^2 \cdot \text{C}^{-2}$.

### Dane:

-$q_1 = 3 \times 10^{-5} \, \text{C}$ w odległości$r_1 = 3 \, \text{m}$ -$q_2 = 5 \times 10^{-5} \, \text{C}$ w odległości$r_2 = 4 \, \text{m}$ -$q_3 = 8 \times 10^{-5} \, \text{C}$ w odległości$r_3 = 5 \, \text{m}$

### Obliczenia potencjałów:

1. **Potencjał$V_1$ wytworzony przez$q_1$:**

$$
 V_1 = \frac{q_1}{4 \pi \epsilon_0 r_1} = \frac{3 \times 10^{-5}}{4 \pi \epsilon_0 \cdot 3} = \frac{3 \times 10^{-5}}{3} \cdot \frac{1}{4 \pi \epsilon_0} = 3 \times 10^{-6} \cdot 9 \times 10^9 = 27 \times 10^3 \, \text{V} = 27000 \, \text{V}
$$

2. **Potencjał$V_2$ wytworzony przez$q_2$:**

$$
 V_2 = \frac{q_2}{4 \pi \epsilon_0 r_2} = \frac{5 \times 10^{-5}}{4 \pi \epsilon_0 \cdot 4} = \frac{5 \times 10^{-5}}{4} \cdot \frac{1}{4 \pi \epsilon_0} = 1.25 \times 10^{-5} \cdot 9 \times 10^9 = 11.25 \times 10^4 \, \text{V} = 112500 \, \text{V}
$$

3. **Potencjał$V_3$ wytworzony przez$q_3$:**
   $$
    V_3 = \frac{q_3}{4 \pi \epsilon_0 r_3} = \frac{8 \times 10^{-5}}{4 \pi \epsilon_0 \cdot 5} = \frac{8 \times 10^{-5}}{5} \cdot \frac{1}{4 \pi \epsilon_0} = 1.6 \times 10^{-5} \cdot 9 \times 10^9 = 14.4 \times 10^4 \, \text{V} = 144000 \, \text{V}
   $$

### Potencjał całkowity$V$:

Sumujemy potencjały wytworzone przez wszystkie trzy ładunki:

$$
V = V_1 + V_2 + V_3
$$

Podstawiając wartości:

$$
V = 27000 \, \text{V} + 112500 \, \text{V} + 144000 \, \text{V}
$$

$$
V = 27000 + 112500 + 144000 = 283500 \, \text{V}
$$

### Ostateczny wynik:

Potencjał w punkcie odległym odpowiednio o 3, 4 i 5 metrów od ładunków$3 \times 10^{-5} \, \text{C}$,$5 \times 10^{-5} \, \text{C}$ oraz$8 \times 10^{-5} \, \text{C}$ wynosi:

$$
V = 283500 \, \text{V}
$$

### 13. Zneleźć potencjał od ładunków$q*1 = 3 * 5^{-5} C$,$5 *  10^{-5}C$ i$8 * 10^{-5}C$ w punkcie odległym od tych ładunków odpowiednio o 1,4 i 5 mentrów

Aby znaleźć potencjał elektryczny w punkcie odległym od kilku ładunków punktowych, należy skorzystać z wzoru na potencjał elektryczny wytwarzany przez pojedynczy ładunek:

$V = \frac{k \cdot q}{r}$

gdzie:

-$V$ to potencjał elektryczny, -$k$ to stała Coulomba ($k \approx 8.99 \times 10^9 \, \text{N} \cdot \text{m}^2 \cdot \text{C}^{-2}$), -$q$ to ładunek, -$r$ to odległość od ładunku do punktu, w którym mierzymy potencjał.

Dla wielu ładunków potencjał w punkcie jest sumą potencjałów od każdego z ładunków:

$V = V_1 + V_2 + V_3 + \ldots$

Mamy trzy ładunki:

1.$q_1 = 3 \times 10^{-5} \, \text{C}$ odległy o$r_1 = 3 \, \text{m}$ 2.$q_2 = 5 \times 10^{-5} \, \text{C}$ odległy o$r_2 = 4 \, \text{m}$ 3.$q_3 = 8 \times 10^{-5} \, \text{C}$ odległy o$r_3 = 5 \, \text{m}$

Potencjały od poszczególnych ładunków w punkcie obliczamy jako:

$V_1 = \frac{8.99 \times 10^9 \cdot 3 \times 10^{-5}}{3}$
$V_2 = \frac{8.99 \times 10^9 \cdot 5 \times 10^{-5}}{4}$
$V_3 = \frac{8.99 \times 10^9 \cdot 8 \times 10^{-5}}{5}$

Obliczmy te wartości krok po kroku:

1.$V_1 = \frac{8.99 \times 10^9 \cdot 3 \times 10^{-5}}{3} = 8.99 \times 10^9 \cdot 10^{-5} = 8.99 \times 10^4 \, \text{V}$

2.$V_2 = \frac{8.99 \times 10^9 \cdot 5 \times 10^{-5}}{4} = 8.99 \times 10^9 \cdot \frac{5 \times 10^{-5}}{4} = 1.12375 \times 10^5 \, \text{V}$

3.$V_3 = \frac{8.99 \times 10^9 \cdot 8 \times 10^{-5}}{5} = 8.99 \times 10^9 \cdot \frac{8 \times 10^{-5}}{5} = 1.4384 \times 10^5 \, \text{V}$

Sumując te wartości, otrzymujemy:

$V = 8.99 \times 10^4 + 1.12375 \times 10^5 + 1.4384 \times 10^5 = 3.46115 \times 10^5 \, \text{V}$

Zatem potencjał w punkcie wynosi$3.46115 \times 10^5 \, \text{V}$.

### 14. Znaleźć potencjał dipola o ładunku$3 * 10^{-5} C$ i rozsuniętych o 1cm w odległości 10cm i 10cm od obu ładunków

Aby znaleźć potencjał dipola w punkcie odległym o 10 cm od obu ładunków dipola, musimy wziąć pod uwagę położenie i wartości ładunków oraz odległość punktu obserwacji od każdego z tych ładunków.

Dipol składa się z dwóch ładunków o tej samej wartości, ale przeciwnych znakach, oddalonych od siebie o pewną odległość$d$. W naszym przypadku:

- Wartość ładunku każdego z ładunków to$q = 3 \times 10^{-5}$C
- Odległość między ładunkami to$d = 1$cm$= 0.01$m

Załóżmy, że ładunki są rozmieszczone wzdłuż osi x, z ładunkiem dodatnim w$(x = +d/2)$i ładunkiem ujemnym w$(x = -d/2)$. Punkt, w którym chcemy obliczyć potencjał, znajduje się w odległości 10 cm od obu ładunków.

### Krok 1: Wyznaczenie odległości od punktu do każdego z ładunków

Punkt P znajduje się 10 cm od obu ładunków, co oznacza, że leży na symetralnej odcinka łączącego ładunki dipola. Oznacza to, że tworzy trójkąt równoramienny z ramionami długości 10 cm.

### Krok 2: Wyznaczenie potencjałów od poszczególnych ładunków

Potencjał elektrostatyczny w punkcie$P$od ładunku$q$znajduje się z równania:
$V = \frac{1}{4 \pi \epsilon_0} \frac{q}{r}$

Dla każdego z ładunków potencjał będzie:

$V_+ = \frac{1}{4 \pi \epsilon_0} \frac{q}{10 \text{ cm}} = \frac{1}{4 \pi \epsilon_0} \frac{3 \times 10^{-5} \text{ C}}{0.1 \text{ m}}$

$V_- = \frac{1}{4 \pi \epsilon_0} \frac{-q}{10 \text{ cm}} = \frac{1}{4 \pi \epsilon_0} \frac{-3 \times 10^{-5} \text{ C}}{0.1 \text{ m}}$

### Krok 3: Sumowanie potencjałów

Ponieważ mamy dwa potencjały, jeden dodatni i jeden ujemny, które są symetryczne, sumujemy je:

$V = V_+ + V_-$

### Krok 4: Obliczenia

Najpierw obliczamy wartość stałej:

$\frac{1}{4 \pi \epsilon_0} = 9 \times 10^9 \, \text{N m}^2/\text{C}^2$

Następnie obliczamy wartość potencjału:

$V_+ = 9 \times 10^9 \times \frac{3 \times 10^{-5}}{0.1}$

$V_- = 9 \times 10^9 \times \frac{-3 \times 10^{-5}}{0.1}$

Ponieważ potencjały się znoszą:

$V = 0$

### Ostateczny wynik

Potencjał w punkcie oddalonym o 10 cm od obu ładunków dipola wynosi 0.

To wynika z symetrii i faktu, że znajdujemy się dokładnie na symetralnej odcinka łączącego oba ładunki dipola, co powoduje, że wpływ obu ładunków się znosi.

### 15. Obliczyć ładunek zgromadzony w kondensatorze o pojemności 10 mF jeżeli został naładowany do potencjału$3 * 10^4 V$.

Ładunek zgromadzony w kondensatorze można obliczyć używając wzoru:

$Q = C \cdot V$

gdzie:

-$Q$ to ładunek, -$C$ to pojemność kondensatora, -$V$ to potencjał, do którego został naładowany kondensator.

Dane:

-$C = 10 \, \mu\text{F} = 10 \times 10^{-6} \, \text{F}$ -$V = 3 \times 10^4 \, \text{V}$

Podstawiając dane do wzoru:

$Q = (10 \times 10^{-6} \, \text{F}) \cdot (3 \times 10^4 \, \text{V})$

$Q = 10 \times 10^{-6} \times 3 \times 10^4$

$Q = 30 \times 10^{-2}$

$Q = 0.3 \, \text{C}$

Zatem ładunek zgromadzony w kondensatorze wynosi$0.3 \, \text{C}$(kulombów).

### 16. Kondensator o pojemności 20 pF (pikofarad) został naładowany do potencjału 30 V. Taktując jego okładki jak punktu (pomijając ich rozmiary) obliczyć pracę potrzebną do rozsunięcia okładek na odległość 1 metra. Przyjąć, że początkowo odległość między okładkami wynosiła 1mm.

Aby obliczyć pracę potrzebną do rozsunięcia okładek kondensatora z 1 mm do 1 metra, musimy zrozumieć, jak zmienia się energia potencjalna elektryczna w kondensatorze, gdy zmieniamy jego geometrię. W szczególności interesuje nas zmiana pojemności kondensatora w zależności od odległości między okładkami i wynikająca z tego zmiana energii zgromadzonej w kondensatorze.

Kondensator płaski, gdzie odległość między okładkami$d$ jest znacznie mniejsza niż wymiary okładek, ma pojemność opisaną wzorem:
$C = \frac{\varepsilon_0 \varepsilon_r A}{d}$
gdzie:

-$\varepsilon_0$ - przenikalność elektryczna próżni ($\varepsilon_0 \approx 8.85 \times 10^{-12} \, \text{F/m}$), -$\varepsilon_r$ - względna przenikalność dielektryka między okładkami (dla próżni$\varepsilon_r = 1$), -$A$ - powierzchnia okładek, -$d$ - odległość między okładkami.

Zadanie mówi nam, że pojemność początkowa wynosi$C_0 = 20 \, \text{pF}$ (20 pikofaradów) i początkowa odległość między okładkami wynosi$d_0 = 1 \, \text{mm} = 1 \times 10^{-3} \, \text{m}$.

Pojemność kondensatora można również wyrazić jako:
$C = \frac{Q}{V}$
gdzie:

-$Q$ - ładunek zgromadzony na okładkach, -$V$ - napięcie między okładkami.

Ponieważ$Q = C_0 \cdot V$ i$V = 30 \, \text{V}$:
$Q = 20 \times 10^{-12} \, \text{F} \times 30 \, \text{V} = 600 \times 10^{-12} \, \text{C}$

Energia zgromadzona w kondensatorze wynosi:
$E = \frac{1}{2} C V^2$

Zmiana odległości między okładkami spowoduje zmianę pojemności. Jeśli rozsuniemy okładki na odległość$d = 1 \, \text{m}$, nowa pojemność będzie:
$C_1 = \frac{\varepsilon_0 A}{1 \, \text{m}}$

Przyjmując, że$\varepsilon_0$ i$A$ są takie same, stosunek pojemności jest odwrotnie proporcjonalny do stosunku odległości:
$\frac{C_0}{C_1} = \frac{d_1}{d_0} = \frac{1 \, \text{m}}{1 \times 10^{-3} \, \text{m}} = 1000$
$C_1 = \frac{C_0}{1000} = \frac{20 \times 10^{-12} \, \text{F}}{1000} = 20 \times 10^{-15} \, \text{F} = 20 \, \text{fF}$

Nowa energia zgromadzona w kondensatorze po rozsunięciu okładek:
$E_1 = \frac{1}{2} C_1 V^2 = \frac{1}{2} \times 20 \times 10^{-15} \, \text{F} \times (30 \, \text{V})^2 = \frac{1}{2} \times 20 \times 10^{-15} \times 900$
$E_1 = \frac{1}{2} \times 18 \times 10^{-12} = 9 \times 10^{-12} \, \text{J} = 9 \, \text{pJ}$

Energia początkowa:
$E_0 = \frac{1}{2} \times 20 \times 10^{-12} \, \text{F} \times (30 \, \text{V})^2 = \frac{1}{2} \times 20 \times 10^{-12} \times 900$
$E_0 = \frac{1}{2} \times 18 \times 10^{-9} = 9 \times 10^{-9} \, \text{J} = 9 \, \text{nJ}$

Praca potrzebna do rozsunięcia okładek:
$W = E_0 - E_1 = 9 \, \text{nJ} - 9 \, \text{pJ} = 9 \times 10^{-9} \, \text{J} - 9 \times 10^{-12} \, \text{J}$
$W \approx 8.999991 \, \text{nJ}$

Ostatecznie, praca potrzebna do rozsunięcia okładek wynosi około 9 nJ.

### 17. W przestrzeni o rozmiarach 3 x 4 x 2 metra rozciąga się pole elektryczne o natężeniu$10^3C/cm$. Obliczyć energię zawartą w polu.

Aby obliczyć energię zawartą w polu elektrycznym, możemy skorzystać ze wzoru na gęstość energii w polu elektrycznym. Gęstość energii $u$ w polu elektrycznym jest dana wzorem:

$u = \frac{1}{2} \varepsilon_0 E^2$

gdzie:

- $\varepsilon_0$ to przenikalność elektryczna próżni ($\varepsilon_0 \approx 8.854 \times 10^{-12} \, \text{F/m}$)
- $E$ to natężenie pola elektrycznego

Natężenie pola elektrycznego $E$ podane jest w jednostkach C/cm, co odpowiada$10^3 \, \text{C/m}$(ponieważ 1 cm = 0.01 m).

Najpierw przeliczmy natężenie pola elektrycznego na jednostki SI:

$E = 10^3 \, \text{C/cm} = 10^3 \times 10^2 \, \text{C/m} = 10^5 \, \text{C/m}$

Teraz możemy obliczyć gęstość energii $u$ :

$u = \frac{1}{2} \varepsilon_0 E^2$
$u = \frac{1}{2} \times 8.854 \times 10^{-12} \, \text{F/m} \times (10^5 \, \text{C/m})^2$
$u = \frac{1}{2} \times 8.854 \times 10^{-12} \times 10^{10}$
$u = \frac{1}{2} \times 8.854 \times 10^{-2}$
$u = 4.427 \times 10^{-2} \, \text{J/m}^3$

Teraz, aby obliczyć całkowitą energię zawartą w polu elektrycznym, musimy pomnożyć gęstość energii przez objętość przestrzeni, w której pole elektryczne jest obecne.

Objętość przestrzeni $V$ jest dana przez:

$V = 3 \, \text{m} \times 4 \, \text{m} \times 2 \, \text{m} = 24 \, \text{m}^3$

Całkowita energia $U$ to:

$U = u \times V$
$U = 4.427 \times 10^{-2} \, \text{J/m}^3 \times 24 \, \text{m}^3$
$U = 1.06248 \, \text{J}$

Zatem energia zawarta w polu elektrycznym wynosi około 1.06248 J.

### 18. Obliczyć opór walcowatego przewodnika ze srebra o promieniu 1 mm i długości 2 m

Aby obliczyć opór walcowatego przewodnika ze srebra, należy skorzystać ze wzoru na opór elektryczny:

$R = \rho \frac{L}{A}$

gdzie:

- $R$ to opór przewodnika,
- $\rho$ to rezystywność materiału (dla srebra $\rho \approx 1.59 \times 10^{-8} \ \Omega \cdot m$),
- $L$
  to długość przewodnika,
- $A$ to pole przekroju poprzecznego przewodnika.

Promień $r$ przewodnika wynosi 1 mm, czyli 0.001 m.

Pole przekroju poprzecznego $A$ walcowego przewodnika można obliczyć ze wzoru na pole koła:

$A = \pi r^2$

Podstawmy wartości:

$A = \pi (0.001 \ \text{m})^2$
$A = \pi \times 0.000001 \ \text{m}^2$
$A = 3.14159 \times 10^{-6} \ \text{m}^2$

Długość przewodnika $L$ wynosi 2 m.

Teraz możemy obliczyć opór $R$ :

$R = \rho \frac{L}{A}$
$R = 1.59 \times 10^{-8} \ \Omega \cdot m \times \frac{2 \ \text{m}}{3.14159 \times 10^{-6} \ \text{m}^2}$

Obliczmy to krok po kroku:

$\frac{2}{3.14159 \times 10^{-6}} \approx 636619.772$
$R = 1.59 \times 10^{-8} \times 636619.772 \approx 1.012 \times 10^{-2} \ \Omega$

Czyli opór przewodnika ze srebra o promieniu 1 mm i długości 2 m wynosi około$0.01012 \ \Omega$.

### 19. Przyjęto, że aby nie było ryzyka awarii przewodnik w pewnym urządzeniu wymagającym prądu 30 A nie może wydzielać więcej energii niż 15W/m. Oblicz średnicę przewodnika jeżeli mozna go wykona jedynie ze stali.

Aby obliczyć średnicę przewodnika wykonanego ze stali, musimy wziąć pod uwagę kilka parametrów, takich jak rezystywność stali oraz wzór na moc wydzielaną w przewodniku. Oto kroki do wykonania obliczeń:

1. **Dane:**

   - Prąd $I = 30 \, \text{A}$
   - Maksymalna moc na metr $P = 15 \, \text{W/m}$
   - Rezystywność stali $\rho = 1.25 \times 10^{-7} \, \Omega \cdot \text{m}$

2. **Wzory:**

   - Moc wydzielana w przewodniku: $P = I^2 R$
   - Rezystancja przewodnika na jednostkę długości: $R = \frac{\rho L}{A}$, gdzie:
     - $L$ to długość przewodnika (w naszym przypadku $L = 1 \, \text{m}$),
     - $A$ to pole przekroju poprzecznego przewodnika.

   Dla okrągłego przewodnika o średnicy $d$:

   - $A = \pi \left(\frac{d}{2}\right)^2 = \frac{\pi d^2}{4}$

3. **Obliczenia:**

   - Moc na jednostkę długości wynosi: $P = I^2 R$
   - Rezystancja na jednostkę długości: $R = \frac{\rho}{A} = \frac{\rho}{\frac{\pi d^2}{4}} = \frac{4\rho}{\pi d^2}$
   - Z tego wynika: $P = I^2 \cdot \frac{4\rho}{\pi d^2}$

4. **Podstawienie danych:**

   - $P = 15 \, \text{W/m}$
   - $I = 30 \, \text{A}$
   - $\rho = 1.25 \times 10^{-7} \, \Omega \cdot \text{m}$

   Podstawiając do wzoru:

   $
   15 = 30^2 \cdot \frac{4 \cdot 1.25 \times 10^{-7}}{\pi d^2}
  $

5. **Rozwiązanie równania:**

   $
   15 = 900 \cdot \frac{5 \times 10^{-7}}{\pi d^2}
  $

   $15 = \frac{4.5 \times 10^{-4}}{\pi d^2}$

   $15 \pi d^2 = 4.5 \times 10^{-4}$

   $\pi d^2 = \frac{4.5 \times 10^{-4}}{15}$

   $\pi d^2 = 3 \times 10^{-5}$

   $d^2 = \frac{3 \times 10^{-5}}{\pi}$

   $d^2 = \frac{3 \times 10^{-5}}{3.14159}$

   $d^2 \approx 9.55 \times 10^{-6}$

   $d \approx \sqrt{9.55 \times 10^{-6}}$

   $d \approx 3.09 \times 10^{-3} \, \text{m}$

   $d \approx 3.09 \, \text{mm}$

Tak więc średnica przewodnika powinna wynosić około 3.09 mm.

### 20. Połączono trzy przewodniki, srebrny o śrenicy jednego milimetra i długości 20cm, miedziany o średnicy 1,5 mm i długości 25cm i aluminiowy o długości 15cm i średnicy 2mm. Zkaładając, że złącza nie wnoszą oporu oblicz opór tak stworzonego kabla

Aby obliczyć opór całkowity przewodów połączonych szeregowo, musimy najpierw obliczyć opór każdego z przewodów z osobna, a następnie zsumować te opory.

Opór przewodnika można obliczyć za pomocą wzoru:

$R = \rho \frac{L}{A}$

gdzie:

- $R$ to opór przewodnika,
- $\rho$ to opór właściwy materiału przewodnika,
- $L$ to długość przewodnika,
- $A$ to pole przekroju poprzecznego przewodnika.

Pole przekroju poprzecznego $A$ jest dane przez wzór na pole koła:

$A = \pi \left( \frac{d}{2} \right)^2 = \frac{\pi d^2}{4}$

Najpierw znajdźmy opory właściwe dla poszczególnych materiałów:

- Srebro ($\rho_{\text{Ag}}$): około $1.59 \times 10^{-8} \, \Omega \cdot m$
- Miedź ($\rho_{\text{Cu}}$): około $1.68 \times 10^{-8} \, \Omega \cdot m$
- Aluminium ($\rho_{\text{Al}}$): około $2.82 \times 10^{-8} \, \Omega \cdot m$

Teraz obliczymy opór każdego przewodu.

### Przewód srebrny

1. Średnica: $d_{\text{Ag}} = 1 \, mm = 0.001 \, m$
2. Długość: $L_{\text{Ag}} = 20 \, cm = 0.2 \, m$
3. Pole przekroju:
   $A_{\text{Ag}} = \frac{\pi (0.001)^2}{4} = 7.85 \times 10^{-7} \, m^2$
4. Opór:
   $R_{\text{Ag}} = 1.59 \times 10^{-8} \frac{0.2}{7.85 \times 10^{-7}} = 4.05 \times 10^{-3} \, \Omega$

### Przewód miedziany

1. Średnica: $d_{\text{Cu}} = 1.5 \, mm = 0.0015 \, m$
2. Długość: $L_{\text{Cu}} = 25 \, cm = 0.25 \, m$
3. Pole przekroju:
   $A_{\text{Cu}} = \frac{\pi (0.0015)^2}{4} = 1.77 \times 10^{-6} \, m^2$
4. Opór:
   $R_{\text{Cu}} = 1.68 \times 10^{-8} \frac{0.25}{1.77 \times 10^{-6}} = 2.37 \times 10^{-3} \, \Omega$

### Przewód aluminiowy

1. Średnica: $d_{\text{Al}} = 2 \, mm = 0.002 \, m$
2. Długość: $L_{\text{Al}} = 15 \, cm = 0.15 \, m$
3. Pole przekroju:
   $A_{\text{Al}} = \frac{\pi (0.002)^2}{4} = 3.14 \times 10^{-6} \, m^2$
4. Opór:
   $R_{\text{Al}} = 2.82 \times 10^{-8} \frac{0.15}{3.14 \times 10^{-6}} = 1.35 \times 10^{-3} \, \Omega$

### Sumaryczny opór przewodów połączonych szeregowo

$R_{\text{całkowity}} = R_{\text{Ag}} + R_{\text{Cu}} + R_{\text{Al}} = 4.05 \times 10^{-3} + 2.37 \times 10^{-3} + 1.35 \times 10^{-3} = 7.77 \times 10^{-3} \, \Omega$

Tak więc, całkowity opór stworzonego kabla wynosi $7.77 \times 10^{-3} \, \Omega$.

### 21. - 25 N/A

### 26. Obliczyć pole magnetyczne wiedząc, że elektron o energii 100 eV po okręgu o promieniu 30cm

Aby obliczyć pole magnetyczne, przy którym elektron o energii 100 eV porusza się po okręgu o promieniu 30 cm, możemy użyć zasady ruchu cząstki naładowanej w polu magnetycznym. Skorzystamy ze wzoru opisującego równowagę sił w ruchu jednostajnym po okręgu.

### Kroki do rozwiązania:

1. **Oblicz prędkość elektronu:**
   Energia kinetyczna elektronu jest dana wzorem:
   $
   E_k = \frac{1}{2} m v^2
  $
   gdzie:

   - $E_k$ to energia kinetyczna,
   - $m$ to masa elektronu ($9.10938356 \times 10^{-31}$ kg),
   - $v$ to prędkość elektronu.

   Przekształcamy wzór, aby wyliczyć prędkość $v$:
   $
   v = \sqrt{\frac{2 E_k}{m}}
  $

2. **Przelicz energię z elektronowoltów na dżule:**
   1 eV = $1.602176634 \times 10^{-19}$ J, więc:
   $
   E_k = 100 \times 1.602176634 \times 10^{-19} \text{ J}
  $

3. **Oblicz siłę Lorentza:**
   Siła Lorentza, która działa na elektron poruszający się w polu magnetycznym, jest równa sile dośrodkowej:
   $F = qvB = \frac{mv^2}{r}$
   gdzie:

   - $q$ to ładunek elektronu ($1.602176634 \times 10^{-19}$ C),
   - $r$ to promień okręgu (0.3 m),
   - $B$ to natężenie pola magnetycznego.

4. **Przekształć wzór i oblicz natężenie pola magnetycznego $B$:**
   $
   B = \frac{mv}{qr}
  $

### Obliczenia:

1. Obliczamy prędkość $v$:

   $$
   E_k = 100 \times 1.602176634 \times 10^{-19} \text{ J} = 1.602176634 \times 10^{-17} \text{ J}
   $$

   $$ v = \sqrt{\frac{2 \times 1.602176634 \times 10^{-17}}{9.10938356 \times 10^{-31}}} $$
   $$ v \approx \sqrt{\frac{3.204353268 \times 10^{-17}}{9.10938356 \times 10^{-31}}} \approx \sqrt{3.517292 \times 10^{13}} \approx 5.93 \times 10^6 \text{ m/s} $$

2. Obliczamy natężenie pola magnetycznego $B$:
   $$
   B = \frac{9.10938356 \times 10^{-31} \times 5.93 \times 10^6}{1.602176634 \times 10^{-19} \times 0.3}
   $$
   $$B \approx \frac{5.3996477 \times 10^{-24}}{4.806529902 \times 10^{-20}}$$
   $$B \approx 1.123 \times 10^{-4} \text{ T}$$

### Wynik:

Natężenie pola magnetycznego wynosi około $1.123 \times 10^{-4} \text{ T}$ (tesla).

### 27. Obliczyć prąd płynący w długim przewodniku jeżeli w wyniku oddziaływania z innym równoległym przewodnikiem odległym o 2cm w którym płynie 12A na metr tego przewodnika działa siłą 10^-6 A.

Do obliczenia prądu płynącego w długim przewodniku możemy skorzystać z prawa Ampère'a, które opisuje siłę magnetyczną między dwoma równoległymi przewodnikami. Wzór na siłę na jednostkę długości między dwoma równoległymi przewodnikami jest dany przez:

$F = \frac{\mu_0 I_1 I_2}{2\pi d}$

gdzie:

- $F$ to siła na jednostkę długości,
- $\mu_0$ to przenikalność magnetyczna próżni ($\mu_0 = 4\pi \times 10^{-7} \, \text{H/m}$),
- $I_1$ i $I_2$ to prądy płynące w przewodnikach,
- $d$ to odległość między przewodnikami.

Z treści zadania wiemy, że:

- $F = 10^{-6} \, \text{N/m}$,
- $d = 0.02 \, \text{m}$,
- $I_2 = 12 \, \text{A}$.

Chcemy obliczyć $I_1$.

Podstawmy znane wartości do wzoru i rozwiążmy równanie dla $I_1$:

$10^{-6} = \frac{4\pi \times 10^{-7} \times I_1 \times 12}{2\pi \times 0.02}$

Uprośćmy równanie:

$10^{-6} = \frac{2 \times 10^{-6} \times I_1 \times 12}{0.02}$

$10^{-6} = \frac{24 \times 10^{-6} \times I_1}{0.02}$

Przekształćmy równanie:

$10^{-6} = 1.2 \times 10^{-6} \times I_1$

Podzielmy obie strony równania przez $1.2 \times 10^{-6}$:

$I_1 = \frac{10^{-6}}{1.2 \times 10^{-6}}$

$I_1 = \frac{1}{1.2}$

$I_1 = \frac{5}{6}$

$I_1 \approx 0.833 \, \text{A}$

Zatem prąd płynący w długim przewodniku wynosi około $0.833 \, \text{A}$.

### 28. Obliczyć pole B na powierzchni okrągłego pręta o promieniu centymetra jeżeli w tym pręcie płynie prąd o natężeniu 60A

Aby obliczyć pole magnetyczne $B$ na powierzchni okrągłego pręta o promieniu 1 cm, przez który płynie prąd o natężeniu 60 A, należy skorzystać z prawa Ampère'a, które mówi, że pole magnetyczne wokół prostego przewodnika z prądem jest dane wzorem:

$B = \frac{\mu_0 I}{2 \pi r}$

gdzie:

- $B$ to natężenie pola magnetycznego,
- $\mu_0$ to przenikalność magnetyczna próżni ($\mu_0 \approx 4\pi \times 10^{-7} \, \text{H/m}$),
- $I$ to natężenie prądu,
- $r$ to odległość od przewodnika (w tym przypadku jest to promień pręta).

Podstawmy dane do wzoru:

- $I = 60 \, \text{A}$,
- $r = 1 \, \text{cm} = 0,01 \, \text{m}$.

Obliczmy $B$:

$B = \frac{4\pi \times 10^{-7} \times 60}{2 \pi \times 0,01}$

Proste działania matematyczne prowadzą do:

$B = \frac{4 \pi \times 10^{-7} \times 60}{2 \pi \times 0,01} = \frac{240 \pi \times 10^{-7}}{2 \pi \times 0,01}$

Skoncentrujmy się na skracaniu i uproszczeniu:

$B = \frac{240 \pi \times 10^{-7}}{2 \pi \times 0,01} = \frac{240 \times 10^{-7}}{2 \times 0,01} = \frac{240 \times 10^{-7}}{0,02} = 240 \times 10^{-7} \times 50$

Kontynuując:

$B = 240 \times 50 \times 10^{-7} = 12000 \times 10^{-7} = 1,2 \times 10^{-3} \, \text{T}$

Tak więc, pole magnetyczne $B$ na powierzchni okrągłego pręta wynosi $1,2 \times 10^{-3} \, \text{T}$ lub 1,2 mT.

### 29. W dwu równoległych przewodnikach płyną prądy 5 i 8 A. W jakich odległościach od tych przewodników jest linia o B=0. W którą stronę muszą płynąć prądy by mogło się to wydarzyć.

Aby znaleźć odległości od przewodników, w których pole magnetyczne wynosi zero, musimy zastosować prawo Biota-Savarta oraz zasadę superpozycji pól magnetycznych.

Pole magnetyczne $B$ wytwarzane przez prostoliniowy przewodnik z prądem $I$ w odległości $r$ od przewodnika jest dane wzorem:
$B = \frac{\mu_0 I}{2 \pi r}$
gdzie:

- $\mu_0$ jest przenikalnością magnetyczną próżni ($\mu_0 \approx 4 \pi \times 10^{-7} \, \text{N/A}^2$),
- $I$ jest natężeniem prądu,
- $r$ jest odległością od przewodnika.

Przyjmijmy, że mamy dwa równoległe przewodniki, przez które płyną prądy $I_1 = 5 \, \text{A}$ i $I_2 = 8 \, \text{A}$. Rozważmy przypadek, w którym prądy płyną w przeciwnych kierunkach, co umożliwia wystąpienie punktu, gdzie całkowite pole magnetyczne wynosi zero.

1. **Kierunki prądów:**

   Aby mogło dojść do sytuacji, gdzie pole magnetyczne $B = 0$, prądy muszą płynąć w przeciwnych kierunkach. Dzięki temu pola magnetyczne wytwarzane przez prądy będą mogły się znosić.

2. **Położenie punktu $B = 0$:**

   Załóżmy, że przewodniki znajdują się w odległości $d$ od siebie. Punkt, w którym pole magnetyczne wynosi zero, znajdzie się w odległości $x$ od przewodnika z prądem $I_1$ (5 A) i w odległości $d - x$ od przewodnika z prądem $I_2$ (8 A).

   W punkcie, gdzie pole magnetyczne wynosi zero, muszą się równać moduły pól magnetycznych wytwarzanych przez oba przewodniki:
   $$\frac{\mu_0 I_1}{2 \pi x} = \frac{\mu_0 I_2}{2 \pi (d - x)}$$
   Po uproszczeniu i wyeliminowaniu wspólnych czynników mamy:
   $$\frac{I_1}{x} = \frac{I_2}{d - x}$$
   $$5 \left( d - x \right) = 8x$$
   $$5d - 5x = 8x$$
   $$5d = 13x$$
   $$x = \frac{5d}{13}$$

   Zatem odległość od przewodnika z prądem 5 A wynosi:
   $x = \frac{5d}{13}$

   Odległość od przewodnika z prądem 8 A wynosi:
   $d - x = d - \frac{5d}{13} = \frac{8d}{13}$

3. **Podsumowanie:**

   - Prądy muszą płynąć w przeciwnych kierunkach.
   - Punkt, w którym pole magnetyczne wynosi zero, znajduje się w odległości $\frac{5d}{13}$ od przewodnika z prądem 5 A i $\frac{8d}{13}$ od przewodnika z prądem 8 A.

### 30. W solenoidzie o 100 zwojach na centymetr powstało pole magnetyczne o indukcji 0,3T. Jaki prąd wskarze doprowadzający prąd do tego solenoidu

Aby znaleźć prąd, który płynie przez solenoid, możemy skorzystać z wzoru na pole magnetyczne wewnątrz solenoidu:

$B = \mu_0 \cdot n \cdot I$

gdzie:

- $B$ to indukcja magnetyczna (0,3 T w naszym przypadku),
- $\mu_0$ to przenikalność magnetyczna próżni ($\mu_0 \approx 4 \pi \times 10^{-7} \, \text{H/m}$),
- $n$ to liczba zwojów na metr,
- $I$ to natężenie prądu.

Z danych mamy:

- liczba zwojów na centymetr: 100 zwojów/cm,
- przeliczamy na metry: 100 zwojów/cm = 10000 zwojów/m.

Podstawiamy wartości do wzoru:

$0,3 \, \text{T} = (4 \pi \times 10^{-7} \, \text{H/m}) \cdot (10000 \, \text{zwojów/m}) \cdot I$

Rozwiązujemy równanie dla $I$:

$I = \frac{0,3 \, \text{T}}{4 \pi \times 10^{-7} \, \text{H/m} \cdot 10000 \, \text{zwojów/m}}$

Obliczamy:

$I = \frac{0,3}{4 \pi \times 10^{-7} \times 10000}$

$I = \frac{0,3}{4 \pi \times 10^{-3}}$

$I = \frac{0,3}{0,004 \pi}$

$I = \frac{0,3}{0,012566}$

$I \approx 23,87 \, \text{A}$

Natężenie prądu w solenoidzie wynosi około 23,87 A.

### 31. Z pola o indukcji 0,7 tesli wyciągnięto w ciągu 0.1 sekundy pętlę kala o powierzchni 0.4m^2. Jakie napięcie wskarze woltomierz przypięty na końcach tej pętli.

Aby obliczyć napięcie, które wskaże woltomierz, możemy skorzystać z prawa Faradaya o indukcji elektromagnetycznej. Prawo to mówi, że siła elektromotoryczna (SEM) $\mathcal{E}$ indukowana w pętli jest równa zmianie strumienia magnetycznego przechodzącego przez tę pętlę w jednostce czasu:

$\mathcal{E} = -\frac{\Delta \Phi_B}{\Delta t}$

gdzie:

- $\Phi_B$ to strumień magnetyczny,
- $\Delta \Phi_B$ to zmiana strumienia magnetycznego,
- $\Delta t$ to czas, w którym następuje zmiana.

Strumień magnetyczny $\Phi_B$ jest dany wzorem:

$\Phi_B = B \cdot A \cdot \cos \theta$

gdzie:

- $B$ to indukcja magnetyczna,
- $A$ to powierzchnia pętli,
- $\theta$ to kąt między wektorem indukcji magnetycznej a normalną do powierzchni pętli. Zakładamy, że $\theta = 0$, czyli wektor indukcji jest prostopadły do powierzchni pętli, co upraszcza wzór do:

$\Phi_B = B \cdot A$

W naszym przypadku, początkowy strumień magnetyczny wynosi:

$\Phi_{B1} = B \cdot A = 0.7 \, \text{T} \cdot 0.4 \, \text{m}^2 = 0.28 \, \text{Wb}$

Po wyciągnięciu pętli z pola magnetycznego, końcowy strumień magnetyczny wynosi 0 Wb (ponieważ pętla znajduje się poza polem magnetycznym):

$\Phi_{B2} = 0 \, \text{Wb}$

Zmiana strumienia magnetycznego jest więc:

$\Delta \Phi_B = \Phi_{B2} - \Phi_{B1} = 0 \, \text{Wb} - 0.28 \, \text{Wb} = -0.28 \, \text{Wb}$

Czas, w którym następuje ta zmiana, wynosi:

$\Delta t = 0.1 \, \text{s}$

Teraz możemy obliczyć siłę elektromotoryczną:

$\mathcal{E} = -\frac{\Delta \Phi_B}{\Delta t} = -\frac{-0.28 \, \text{Wb}}{0.1 \, \text{s}} = 2.8 \, \text{V}$

Zatem woltomierz wskaże napięcie 2.8 V.

### 32. Pręt metalowy porusza się w polu o idukcji 0,2T z mrędkością 100 m/s tak, że zarówno pręt jak i jego prędkość są prostopadłe do siebiei do pola do linii pola. Co wskazałby amperomierz zapięty do końców tgeo pręta jeżeli byłby połączony szeregowo z opornikiem 2 omy

Aby obliczyć prąd, jaki popłynie przez obwód składający się z pręta poruszającego się w polu magnetycznym, musimy najpierw wyznaczyć siłę elektromotoryczną (SEM) indukowaną w pręcie. Następnie użyjemy prawa Ohma do obliczenia prądu. Oto kroki:

1. **Obliczenie siły elektromotorycznej (SEM)**:
   Siła elektromotoryczna $\mathcal{E}$ indukowana w pręcie poruszającym się w polu magnetycznym jest dana wzorem:
   $
   \mathcal{E} = B \cdot v \cdot l
  $
   gdzie:

   - $B$ to indukcja pola magnetycznego (w Teslach),
   - $v$ to prędkość pręta (w metrach na sekundę),
   - $l$ to długość pręta (w metrach).

   Zakładamy, że długość pręta wynosi $l$.

2. **Obliczenie prądu**:
   Korzystając z prawa Ohma, prąd $I$ w obwodzie wynosi:
   $$
   I = \frac{\mathcal{E}}{R}
   $$
   gdzie:
   - $\mathcal{E}$ to siła elektromotoryczna,
   - $R$ to opór obwodu (w omach).

Zakładając, że długość pręta wynosi $l = 1 \, \text{m}$ (ponieważ nie została podana, przyjmujemy typową wartość dla ułatwienia obliczeń), mamy:

$$
\mathcal{E} = B \cdot v \cdot l = 0.2 \, \text{T} \cdot 100 \, \text{m/s} \cdot 1 \, \text{m} = 20 \, \text{V}
$$

Następnie, opór całego obwodu wynosi $2 \, \Omega$.

$$
I = \frac{\mathcal{E}}{R} = \frac{20 \, \text{V}}{2 \, \Omega} = 10 \, \text{A}
$$

Zatem amperomierz wskazałby prąd o wartości 10 amperów.

### 33. prostopadle do ramki o bokach 2 i 5 dcm zmienia się pole B. Jaki prąd wskaże ampermierz na tej ramce jeżeli jej opór wynosi 0.5 oma

Aby obliczyć prąd w ramce, musimy wykorzystać prawo Faradaya dotyczące indukcji elektromagnetycznej oraz prawo Ohma. Oto kroki, które należy podjąć:

1. **Obliczenie zmiany strumienia magnetycznego (ΔΦ):**

   $$
   \Delta \Phi = B \cdot A
   $$

   gdzie $B$ to zmiana indukcji magnetycznej, a $A$ to pole powierzchni ramki.

2. **Obliczenie pola powierzchni ramki (A):**
   Ramka ma boki o długości 2 dcm i 5 dcm (1 decymetr = 0,1 metra):

   $$
   A = 2 \, \text{dcm} \times 5 \, \text{dcm} = 0,2 \, \text{m} \times 0,5 \, \text{m} = 0,1 \, \text{m}^2
   $$

3. **Zastosowanie prawa Faradaya:**
   Indukowana siła elektromotoryczna (SEM) wynosi:

   $$
   \mathcal{E} = -\frac{\Delta \Phi}{\Delta t}
   $$

   gdzie $\Delta \Phi = \Delta B \cdot A$, a $\Delta t$ to czas, w którym zachodzi zmiana pola magnetycznego.

4. **Zastosowanie prawa Ohma do obliczenia prądu (I):**
   $$
   I = \frac{\mathcal{E}}{R}
   $$
   gdzie $R$ to opór ramki.

Podsumowując, jeśli znamy wartości $\Delta B$ i $\Delta t$, możemy obliczyć indukowaną SEM, a następnie prąd.

Przykład:
Załóżmy, że zmiana indukcji magnetycznej $\Delta B$ wynosi 0,1 T (Tesla) i zachodzi w czasie $\Delta t = 1$ sekundy:

1. Zmiana strumienia magnetycznego:

   $$
   \Delta \Phi = \Delta B \cdot A = 0,1 \, \text{T} \times 0,1 \, \text{m}^2 = 0,01 \, \text{Wb}
   $$

2. Indukowana SEM:

   $$
   \mathcal{E} = -\frac{\Delta \Phi}{\Delta t} = -\frac{0,01 \, \text{Wb}}{1 \, \text{s}} = -0,01 \, \text{V}
   $$

3. Prąd w ramce:
   $$
   I = \frac{\mathcal{E}}{R} = \frac{0,01 \, \text{V}}{0,5 \, \Omega} = 0,02 \, \text{A} = 20 \, \text{mA}
   $$

Zatem prąd wskaże ampermierz wynosi $20 \, \text{mA}$.

### 34. Rowerzysta jadący z prędkością 10 m/s napędza dynamo umożliwiający świecenie żarówki o mocy 5 W. Zakładając sprawność układu wytwarzakjącego prąd na 10% obiicz siłę hamującą rowerzystę.

Aby obliczyć siłę hamującą rowerzystę spowodowaną pracą dynama, musimy najpierw zrozumieć, ile energii zużywa dynamo i jak to przekłada się na pracę wykonaną przez rowerzystę. Następnie obliczymy siłę potrzebną do wygenerowania tej energii przy zadanej prędkości.

1. **Moc żarówki i sprawność układu:**

   Moc żarówki wynosi $P = 5 \, \text{W}$.

   Sprawność układu wynosi $\eta = 10\% = 0.1$.

   To oznacza, że tylko 10% energii generowanej przez dynamo jest wykorzystywane przez żarówkę, a reszta jest tracona. Stąd całkowita moc generowana przez dynamo wynosi:

$$P_{\text{dynamo}} = \frac{P}{\eta} = \frac{5 \, \text{W}}{0.1} = 50 \, \text{W}$$

2. **Prędkość rowerzysty:**

   Prędkość rowerzysty wynosi$v = 10 \, \text{m/s}$.

3. **Obliczenie siły hamującej:**

   Moc jest definiowana jako praca wykonana w jednostce czasu. Możemy to również wyrazić jako iloczyn siły i prędkości:

$$P_{\text{dynamo}} = F \cdot v$$

Gdzie: -$P_{\text{dynamo}}$to moc generowana przez dynamo, -$F$to siła hamująca, -$v$to prędkość rowerzysty.

Z powyższego równania możemy obliczyć siłę hamującą:

$$F = \frac{P_{\text{dynamo}}}{v}$$

Podstawiając znane wartości:

$$F = \frac{50 \, \text{W}}{10 \, \text{m/s}} = 5 \, \text{N}$$

Zatem siła hamująca rowerzystę wynosi $5 \, \text{N}$.

### 35. Oblicz energię zawartą w pomieszczeniu 2x4x2 m wypełnionym polem B o wartości 2 T.

Aby obliczyć energię zgromadzoną w pomieszczeniu wypełnionym polem magnetycznym, należy skorzystać z wzoru na energię pola magnetycznego w danym obszarze. Energia$E$pola magnetycznego w objętości$V$jest dana wzorem:

$$E = \frac{B^2 V}{2 \mu_0}$$

gdzie: -$B$to natężenie pola magnetycznego (w teslach, T), -$V$to objętość pomieszczenia (w metrach sześciennych, m³), -$\mu_0$to przenikalność magnetyczna próżni, która wynosi$\mu_0 = 4 \pi \times 10^{-7} \, \text{H/m}$.

Najpierw obliczmy objętość pomieszczenia:

$$V = 2 \, \text{m} \times 4 \, \text{m} \times 2 \, \text{m} = 16 \, \text{m}^3$$

Następnie podstawiamy wartości do wzoru na energię:

$$E = \frac{(2 \, \text{T})^2 \times 16 \, \text{m}^3}{2 \times 4 \pi \times 10^{-7} \, \text{H/m}}$$

Obliczmy krok po kroku:

1. $$B^2 = (2 \, \text{T})^2 = 4 \, \text{T}^2$$

2. $$\frac{B^2}{2 \mu_0} = \frac{4 \, \text{T}^2}{2 \times 4 \pi \times 10^{-7} \, \text{H/m}} = \frac{4 \, \text{T}^2}{8 \pi \times 10^{-7} \, \text{H/m}}$$
3. $$\frac{4 \, \text{T}^2}{8 \pi \times 10^{-7} \, \text{H/m}} = \frac{4}{8 \pi \times 10^{-7}} \, \text{T}^2 / \text{H/m} = \frac{1}{2 \pi \times 10^{-7}} \, \text{T}^2 / \text{H/m}$$
4. $$\frac{1}{2 \pi \times 10^{-7}} \approx \frac{1}{6.28 \times 10^{-7}} \approx 1.59 \times 10^6 \, \text{J/m}^3$$

Następnie obliczamy całkowitą energię dla objętości$V$:

$$E = 1.59 \times 10^6 \, \text{J/m}^3 \times 16 \, \text{m}^3$$

$$E = 25.44 \times 10^6 \, \text{J}$$

Zatem energia zgromadzona w pomieszczeniu wynosi około $25.44 \times 10^6 \, \text{J}$, czyli $25.44 \, \text{MJ}$.

### 36. Oblicz jaką moc może osiągnąć wiatrak o długuści śmigła 30 m. Przyjmij prędkość wiatru 20 m/s i sprawność turbiny 50 %. Oblicz siłę działającą na wiatrak.

Aby obliczyć moc, jaką może osiągnąć wiatrak oraz siłę działającą na wiatrak, musimy skorzystać z kilku wzorów i założeń.

### Moc generowana przez wiatrak

Moc dostępna w strumieniu wiatru może być obliczona za pomocą wzoru:
$$P_{wiatru} = \frac{1}{2} \cdot \rho \cdot A \cdot v^3$$

gdzie:

- $\rho$ to gęstość powietrza (przyjmujemy $\rho = 1.225 \, \text{kg/m}^3$ na poziomie morza),
- $A$ to powierzchnia przekroju, przez który przechodzi wiatr,
- $v$ to prędkość wiatru.

Powierzchnia przekroju to powierzchnia koła o promieniu równym długości śmigła:
$$A = \pi \cdot r^2$$
gdzie $r = 30 \, \text{m}$.

Podstawiając:
$$A = \pi \cdot (30 \, \text{m})^2 = \pi \cdot 900 \, \text{m}^2 \approx 2827.43 \, \text{m}^2$$

Prędkość wiatru $v$ wynosi 20 m/s.

Podstawiając wszystkie wartości do wzoru na moc:
$$P_{wiatru} = \frac{1}{2} \cdot 1.225 \, \text{kg/m}^3 \cdot 2827.43 \, \text{m}^2 \cdot (20 \, \text{m/s})^3$$

Obliczmy teraz moc wiatru:
$$P_{wiatru} = \frac{1}{2} \cdot 1.225 \cdot 2827.43 \cdot 8000$$
$$P_{wiatru} \approx \frac{1}{2} \cdot 1.225 \cdot 2827.43 \cdot 8000$$
$$P_{wiatru} \approx 13823208 \, \text{W}$$
$$P_{wiatru} \approx 13.823 \, \text{MW}$$

### Moc osiągana przez wiatrak

Sprawność turbiny wynosi 50%, więc moc generowana przez turbinę $P_{turbiny}$ to:
$$P_{turbiny} = 0.5 \cdot P_{wiatru}$$
$$P_{turbiny} = 0.5 \cdot 13.823 \, \text{MW}$$
$$P_{turbiny} \approx 6.9115 \, \text{MW}$$

### Siła działająca na wiatrak

Aby obliczyć siłę działającą na wiatrak, możemy skorzystać z zasady zachowania pędu i wzoru na siłę:
$$F = \dot{m} \cdot v$$
gdzie $\dot{m}$ to strumień masy powietrza przepływający przez powierzchnię $A$, który można wyrazić jako:
$$\dot{m} = \rho \cdot A \cdot v$$

Podstawiając wartości:
$$\dot{m} = 1.225 \, \text{kg/m}^3 \cdot 2827.43 \, \text{m}^2 \cdot 20 \, \text{m/s}$$
$$\dot{m} \approx 1.225 \cdot 2827.43 \cdot 20$$
$$\dot{m} \approx 69293.15 \, \text{kg/s}$$

Siła:
$$F = \dot{m} \cdot v$$
$$F \approx 69293.15 \, \text{kg/s} \cdot 20 \, \text{m/s}$$
$$F \approx 1385863 \, \text{N}$$

Podsumowując:

- Moc osiągana przez wiatrak wynosi około $6.9115 \, \text{MW}$.
- Siła działająca na wiatrak wynosi około $1385863 \, \text{N}$.

### 37. Oblicz gęstość zwojów solenoidu o indukcyjności 15 henrów jeżeli dłgość solenoidu wynosi 30cm a przekrój $40cm^2$.

Aby obliczyć gęstość zwojów ($n$) solenoidu, możemy użyć wzoru na indukcyjność solenoidu. Indukcyjność $L$ solenoidu wyrażona jest wzorem:

$L = \frac{\mu_0 \cdot n^2 \cdot A \cdot l}{l}$

gdzie:

- $L$ to indukcyjność (15 H),
- $\mu_0$ to przenikalność magnetyczna próżni ($4\pi \times 10^{-7}$ H/m),
- $n$ to liczba zwojów na metr (gęstość zwojów),
- $A$ to pole przekroju poprzecznego solenoidu (40 cm^2 = 0.004 m^2),
- $l$ to długość solenoidu (30 cm = 0.3 m).

Podstawiając te wartości do wzoru, otrzymujemy:

$L = \mu_0 \cdot n^2 \cdot A \cdot l$

Przekształćmy wzór, aby wyznaczyć $n$:

$n^2 = \frac{L}{\mu_0 \cdot A \cdot l}$
$n = \sqrt{\frac{L}{\mu_0 \cdot A \cdot l}}$

Podstawmy wartości:

$n = \sqrt{\frac{15}{4\pi \times 10^{-7} \cdot 0.004 \cdot 0.3}}$

Obliczmy teraz wartość:

$n = \sqrt{\frac{15}{4\pi \times 10^{-7} \cdot 0.0012}}$
$n = \sqrt{\frac{15}{1.50796 \times 10^{-9}}}$
$n = \sqrt{9.947 \times 10^9}$
$n \approx 99735$

Gęstość zwojów wynosi około 99735 zwojów na metr.

### 38. Oblicz długość fali emitowanej przez obwód o samoindukcji 20 H i pojemności 5 mF.

Aby obliczyć długość fali emitowanej przez obwód rezonansowy o samoindukcji$L$i pojemności$C$, należy najpierw obliczyć częstotliwość rezonansową tego obwodu. Częstotliwość rezonansowa$f$dla obwodu RLC (gdy rezystancja$R$jest pomijalna) jest dana wzorem:

$$f = \frac{1}{2\pi \sqrt{LC}}$$

gdzie: -$L$to indukcyjność, -$C$to pojemność.

Po obliczeniu częstotliwości możemy obliczyć długość fali$\lambda$przy użyciu prędkości światła$c$:

$$\lambda = \frac{c}{f}$$

Przyjmując, że prędkość światła$c$wynosi około$3 \times 10^8 \text{ m/s}$, możemy przystąpić do obliczeń.

1. Obliczenie częstotliwości rezonansowej$f$:

$$L = 20 \text{ H}$$
$$C = 5 \text{ mF} = 5 \times 10^{-3} \text{ F}$$

$$f = \frac{1}{2\pi \sqrt{LC}}$$

Podstawiając wartości:

$$f = \frac{1}{2\pi \sqrt{20 \times 5 \times 10^{-3}}}$$

2. Obliczenie długości fali$\lambda$:

$$\lambda = \frac{c}{f}$$

Przystępujemy do obliczeń krok po kroku.

### Obliczenia

1. Obliczenie częstotliwości rezonansowej:

$$f = \frac{1}{2\pi \sqrt{20 \times 5 \times 10^{-3}}} = \frac{1}{2\pi \sqrt{0.1}} = \frac{1}{2\pi \times 0.3162} \approx \frac{1}{1.986} \approx 0.503 \text{ Hz}$$

2. Obliczenie długości fali:

$$\lambda = \frac{c}{f} = \frac{3 \times 10^8}{0.503} \approx 5.96 \times 10^8 \text{ m}$$

### Wynik

Długość fali emitowanej przez ten obwód wynosi około $5.96 \times 10^8$metrów.

### 39. Ciało nagrzane do temperatury 300K o powierzchni 1 m2 wmituje promieniowanie jak ciało doskonale czarne. Oblicz moc tego promieniowania.

Aby obliczyć moc promieniowania emitowanego przez ciało nagrzane do temperatury $300 \, \text{K}$ i o powierzchni $1 \, \text{m}^2$, możemy skorzystać z prawa Stefana-Boltzmanna. Prawo to wyraża się wzorem:

$$ P = \sigma \cdot A \cdot T^4 $$

gdzie:

- $P$ to moc promieniowania (w watach, W),
- $\sigma$ to stała Stefana-Boltzmanna ($\sigma \approx 5.67 \times 10^{-8} \, \text{W} \cdot \text{m}^{-2} \cdot \text{K}^{-4}$),
- $A$ to powierzchnia ciała (w metrach kwadratowych, m²),
- $T$ to temperatura ciała (w kelwinach, K).

Podstawiając dane:

- $\sigma = 5.67 \times 10^{-8} \, \text{W} \cdot \text{m}^{-2} \cdot \text{K}^{-4}$,
- $A = 1 \, \text{m}^2$,
- $T = 300 \, \text{K}$,

otrzymujemy:

$$ P = 5.67 \times 10^{-8} \cdot 1 \cdot (300)^4 $$

Najpierw obliczmy $(300)^4$:

$$ 300^4 = 300 \times 300 \times 300 \times 300 $$
$$ 300^4 = 90000 \times 90000 $$
$$ 300^4 = 8100000000 $$

Teraz możemy obliczyć moc promieniowania:

$$ P = 5.67 \times 10^{-8} \cdot 8100000000 $$
$$ P = 459.27 \, \text{W} $$

Zatem moc promieniowania emitowanego przez ciało wynosi $459.27 \, \text{W}$.

### 40. Oblicz częstotliwość maksimum promieniowania Słońca. Temperatura Słońca wynosi ok. 6000K.

Aby obliczyć częstotliwość maksimum promieniowania Słońca, możemy skorzystać z prawa przesunięcia Wiena, które dla długości fali określa, że $\lambda_{max} T = b$, gdzie $\lambda_{max}$ to długość fali przy której występuje maksimum promieniowania, $T$ to temperatura ciała, a $b$ to stała Wiena wynosząca około $2.897 \times 10^{-3}$ m·K.

Najpierw obliczymy długość fali $\lambda_{max}$ dla temperatury $T = 6000$ K:

$$
\lambda_{max} = \frac{b}{T}
$$

Podstawiając wartości:

$$
\lambda_{max} = \frac{2.897 \times 10^{-3} \text{ m · K}}{6000 \text{ K}} = 4.828 \times 10^{-7} \text{ m} = 482.8 \text{ nm}
$$

Następnie, aby obliczyć częstotliwość $\nu_{max}$, skorzystamy z zależności między prędkością światła ($c$), długością fali ($\lambda$) i częstotliwością ($\nu$):

$$
c = \lambda \nu
$$

Stąd:

$$
\nu_{max} = \frac{c}{\lambda_{max}}
$$

Podstawiając wartości ($c \approx 3 \times 10^8$ m/s):

$$
\nu_{max} = \frac{3 \times 10^8 \text{ m/s}}{4.828 \times 10^{-7} \text{ m}} \approx 6.21 \times 10^{14} \text{ Hz}
$$

Tak więc, częstotliwość maksimum promieniowania Słońca wynosi około $6.21 \times 10^{14}$ Hz.

# Zadania Teoretyczne

### 1. Na przykładzie pola elektrostatycznego przedstawić pojęcie i własności pola potencjalnego.

### Pojęcie pola potencjalnego

**Pole potencjalne** to pole wektorowe, w którym praca wykonana przez siły pola nad cząstką zależy tylko od początkowego i końcowego położenia cząstki, a nie od drogi, jaką cząstka przebyła. Oznacza to, że w polu potencjalnym można zdefiniować funkcję skalarną zwaną **potencjałem**, której gradient jest równy natężeniu pola.

W kontekście pola elektrostatycznego:

- Pole elektrostatyczne jest przykładem pola potencjalnego.
- Potencjałem elektrostatycznym w danym punkcie jest energia potencjalna jednostkowego ładunku umieszczonego w tym punkcie.

### Własności pola potencjalnego

1. **Praca niezależna od drogi**: W polu potencjalnym, praca wykonana przy przemieszczaniu ładunku z punktu A do punktu B zależy tylko od potencjałów w tych punktach, a nie od drogi, jaką przebył ładunek.

2. **Istnienie funkcji potencjału**: W polu potencjalnym istnieje funkcja skalarna$V(\mathbf{r})$, zwana potencjałem, taka że:

   $$
    \mathbf{E} = -\nabla V
   $$

   gdzie$\mathbf{E}$to natężenie pola, a$\nabla V$to gradient potencjału.

3. **Zachowanie energii**: W polu potencjalnym zachodzi zasada zachowania energii. Energia mechaniczna (suma energii kinetycznej i potencjalnej) cząstki poruszającej się w takim polu pozostaje stała.

4. **Konserwatywność pola**: Pole potencjalne jest polem konserwatywnym, co oznacza, że cyrkulacja pola po dowolnej zamkniętej drodze jest równa zero:
   $$
    \oint \mathbf{E} \cdot d\mathbf{l} = 0
   $$

### Przykład pola elektrostatycznego

Rozważmy pole elektrostatyczne wytwarzane przez punktowy ładunek$q$.

1. **Natężenie pola elektrostatycznego**:
   Natężenie pola elektrostatycznego wytworzonego przez punktowy ładunek$q$w odległości$r$od tego ładunku wynosi:

   $$
    \mathbf{E} = \frac{1}{4 \pi \varepsilon_0} \frac{q}{r^2} \hat{r}
   $$

   gdzie$\hat{r}$to jednostkowy wektor radialny.

2. **Potencjał elektrostatyczny**:
   Potencjał elektrostatyczny wytworzony przez punktowy ładunek$q$w odległości$r$od tego ładunku wynosi:

   $$
    V = \frac{1}{4 \pi \varepsilon_0} \frac{q}{r}
   $$

3. **Związek między natężeniem pola a potencjałem**:
   Natężenie pola elektrostatycznego jest gradientem potencjału z przeciwnym znakiem:

   $$
    \mathbf{E} = -\nabla V
   $$

4. **Praca wykonana przez pole**:
   Praca wykonana przez siły pola elektrostatycznego przy przemieszczaniu ładunku$q_0$z punktu A o potencjale$V_A$do punktu B o potencjale$V_B$wynosi:
   $$
    W = q_0 (V_A - V_B)
   $$
   Jest to zgodne z własnością pola potencjalnego, że praca zależy tylko od potencjałów początkowego i końcowego.

Pole elektrostatyczne jest zatem doskonałym przykładem pola potencjalnego, gdzie można jasno zdefiniować potencjał, a własności tego pola doskonale ilustrują ogólne cechy pól potencjalnych.

### 2. Przedstawić prawo Gaussa. W szczególności przy jego pomocy wyprowadzić praswo Coulomba.

### Prawo Gaussa

Prawo Gaussa, jedno z fundamentalnych praw elektromagnetyzmu, jest jednym z czterech równań Maxwella. Opisuje związek między ładunkiem elektrycznym a polem elektrycznym. Prawo to można wyrazić matematycznie jako:

$\oint_S \mathbf{E} \cdot d\mathbf{A} = \frac{Q_{\text{wew}}}{\epsilon_0}$

gdzie:

- $\mathbf{E}$ to wektor pola elektrycznego,
- $d\mathbf{A}$ to wektor powierzchniowy skierowany na zewnątrz powierzchni zamkniętej $S$,
- $Q_{\text{wew}}$ to całkowity ładunek wewnątrz powierzchni $S$,
- $\epsilon_0$ to przenikalność elektryczna próżni.

Prawo Gaussa stwierdza, że całkowity strumień pola elektrycznego przez zamkniętą powierzchnię jest proporcjonalny do ładunku netto zawartego wewnątrz tej powierzchni.

### Wyprowadzenie prawa Coulomba z prawa Gaussa

Aby wyprowadzić prawo Coulomba z prawa Gaussa, rozważmy punktowy ładunek $Q$ umieszczony w przestrzeni. Wybieramy powierzchnię Gaussa w postaci sfery o promieniu $r$ i środku w punkcie, w którym znajduje się ładunek $Q$.

Z symetrii problemu wiemy, że pole elektryczne $\mathbf{E}$ będzie miało stałą wartość na powierzchni sfery i będzie skierowane radialnie na zewnątrz. Zatem:

$\mathbf{E} = E \hat{r}$

gdzie $E$ jest wielkością pola elektrycznego, a $\hat{r}$ to jednostkowy wektor radialny.

Strumień pola elektrycznego przez powierzchnię sfery wynosi:

$\oint_S \mathbf{E} \cdot d\mathbf{A} = E \oint_S dA = E \cdot 4 \pi r^2$

Zgodnie z prawem Gaussa:

$E \cdot 4 \pi r^2 = \frac{Q}{\epsilon_0}$

Rozwiązując to równanie dla $E$, otrzymujemy:

$E = \frac{Q}{4 \pi \epsilon_0 r^2}$

To jest dokładnie wyrażenie na natężenie pola elektrycznego wytwarzanego przez punktowy ładunek $Q$ w odległości $r$ od ładunku. Zgodnie z definicją pola elektrycznego, jest to zgodne z prawem Coulomba, które stwierdza, że siła między dwoma punktowymi ładunkami $Q_1$ i $Q_2$ oddzielonymi odległością $r$ wynosi:

$F = k_e \frac{Q_1 Q_2}{r^2}$

gdzie $k_e$ to stała elektrostatyczna, równa $\frac{1}{4 \pi \epsilon_0}$.

Zatem prawo Gaussa prowadzi bezpośrednio do prawa Coulomba, co pokazuje, że oba prawa są ze sobą ściśle powiązane i wynikają z fundamentalnych zasad elektromagnetyzmu.

### 3.Przy pomocy prawa Gaussa wyprowadzić natężenie pola w dwu wymiarach (pole od nieskończonej nici).

Prawo Gaussa mówi, że strumień pola elektrycznego przez dowolną zamkniętą powierzchnię jest proporcjonalny do całkowitego ładunku zamkniętego w tej powierzchni. Wzór na prawo Gaussa w elektrodynamice to:

$$
\oint_{\partial V} \mathbf{E} \cdot d\mathbf{A} = \frac{Q_{\text{wewn}}}{\epsilon_0}
$$

gdzie $\mathbf{E}$ to natężenie pola elektrycznego, $d\mathbf{A}$ to wektor powierzchniowy, $Q_{\text{wewn}}$ to całkowity ładunek zamknięty w powierzchni $\partial V$, a $\epsilon_0$ to przenikalność elektryczna próżni.

Rozważmy teraz nieskończoną linię ładunku o liniowej gęstości ładunku $\lambda$ (ładunek na jednostkę długości). Aby wyznaczyć natężenie pola elektrycznego $\mathbf{E}$ w dwu wymiarach za pomocą prawa Gaussa, musimy wybrać odpowiednią powierzchnię gaussowską.

Dla nieskończonej linii ładunku naturalnym wyborem jest cylinder o promieniu $r$ i długości $L$, którego oś pokrywa się z linią ładunku. Cylindryczna symetria powoduje, że pole elektryczne jest skierowane radialnie od linii ładunku i jest jednorodne na powierzchni bocznej cylindra. Powierzchnia boczna cylindra będzie kluczowa, ponieważ na końcach cylindra pole elektryczne będzie symetrycznie przeciwnie skierowane i ich wkład do całkowitego strumienia będzie się znosił.

Rozważmy boczną powierzchnię cylindra:

$$
\oint_{\partial V} \mathbf{E} \cdot d\mathbf{A} = E \cdot (2\pi r L)
$$

gdzie $2\pi r L$ to powierzchnia boczna cylindra o promieniu $r$ i długości $L$.

Całkowity ładunek zamknięty w tej powierzchni gaussowskiej to $\lambda L$, ponieważ długość cylindra wynosi $L$.

Zgodnie z prawem Gaussa:

$$
E \cdot (2\pi r L) = \frac{\lambda L}{\epsilon_0}
$$

Po uproszczeniu otrzymujemy:

$$
E = \frac{\lambda}{2\pi r \epsilon_0}
$$

Zatem natężenie pola elektrycznego w odległości $r$ od nieskończonej linii ładunku wynosi:

$$
\mathbf{E} = \frac{\lambda}{2\pi r \epsilon_0} \hat{r}
$$

gdzie $\hat{r}$ jest jednostkowym wektorem radialnym od linii ładunku na zewnątrz.

Podsumowując, natężenie pola elektrycznego od nieskończonej linii ładunku w dwu wymiarach jest odwrotnie proporcjonalne do odległości od linii i jest dane wzorem:

$$
\mathbf{E} = \frac{\lambda}{2\pi r \epsilon_0} \hat{r}
$$

### 4. Przedstawić pojęcie i własności potencjału pola. Przedstawić związek między potencjałem a natężeniem pola.

### Pojęcie Potencjału Pola

**Potencjał pola** to pojęcie używane w fizyce, które opisuje energię potencjalną jednostkowego ładunku w danym punkcie pola. Potencjał jest skalarną wielkością fizyczną, co oznacza, że ma tylko wartość liczbową bez kierunku. W kontekście elektrycznym, potencjał elektryczny$V$w punkcie to ilość pracy potrzebnej do przemieszczenia jednostkowego ładunku dodatniego z punktu odniesienia (zwykle nieskończoności) do tego punktu w polu elektrycznym.

Matematycznie, potencjał$V$w punkcie można zdefiniować jako:

$$V = \frac{W}{q}$$

gdzie:

- $V$ to potencjał,
- $W$ to praca wykonana nad przemieszczeniem ładunku$q$.

### Własności Potencjału Pola

1. **Skalarność**: Potencjał jest wielkością skalarną, co oznacza, że jest opisywany tylko przez swoją wartość liczbową.
2. **Zależność od pozycji**: Potencjał w polu jest funkcją położenia punktu w przestrzeni.
3. **Relatywność**: Potencjał jest zdefiniowany względem punktu odniesienia. Zwykle wybiera się nieskończoność jako punkt odniesienia, gdzie potencjał przyjmuje wartość zero.
4. **Addytywność**: W przypadku pola elektrycznego od wielu źródeł (ładunków), całkowity potencjał w danym punkcie jest sumą potencjałów od poszczególnych źródeł.

### Związek Między Potencjałem a Natężeniem Pola

Natężenie pola elektrycznego$\mathbf{E}$jest wektorową wielkością opisującą siłę działającą na jednostkowy ładunek w danym punkcie pola. Związek między potencjałem a natężeniem pola elektrycznego jest dany przez gradient potencjału.

Matematycznie, natężenie pola elektrycznego$\mathbf{E}$można wyrazić jako:

$$\mathbf{E} = -\nabla V$$

gdzie:

- $\mathbf{E}$ to wektor natężenia pola elektrycznego,
- $V$ to potencjał elektryczny,
- $\nabla$ to operator gradientu.

Oznacza to, że natężenie pola elektrycznego jest ujemnym gradientem potencjału. Gradient potencjału wskazuje kierunek największej zmiany potencjału, a znak minus oznacza, że natężenie pola wskazuje w kierunku malejącego potencjału.

### Przykład

Rozważmy punktowy ładunek$Q$w przestrzeni. Potencjał$V$w odległości$r$od tego ładunku wynosi:

$$V = \frac{kQ}{r}$$

gdzie$k$jest stałą Coulomba.

Natężenie pola elektrycznego$\mathbf{E}$w odległości$r$od punktowego ładunku wynosi:

$$\mathbf{E} = -\nabla V = -\nabla \left( \frac{kQ}{r} \right) = \frac{kQ}{r^2} \hat{r}$$

gdzie$\hat{r}$jest wektorem jednostkowym w kierunku od ładunku.

### Wnioski

1. Potencjał pola jest skalarną funkcją opisującą energię potencjalną jednostkowego ładunku w punkcie pola.
2. Natężenie pola elektrycznego jest wektorową funkcją opisującą siłę działającą na jednostkowy ładunek.
3. Związek między potencjałem a natężeniem pola jest dany przez gradient potencjału, gdzie natężenie pola jest ujemnym gradientem potencjału.

Ten związek między potencjałem a natężeniem pola pozwala na analizę i obliczenia w kontekście elektrycznym oraz magnetycznym, gdzie pojęcie potencjału i jego gradientu odgrywa kluczową rolę.

### 5. Co rozumiemy pod pojęciem „kwantowanie ładunku” oraz omówić prawo zachowania ładunku.

### Kwantowanie ładunku

Kwantowanie ładunku to zjawisko polegające na tym, że ładunek elektryczny występuje tylko w dyskretnych jednostkach, które są całkowitymi wielokrotnościami elementarnego ładunku, jakim jest ładunek elektronu. Wartość tego elementarnego ładunku wynosi $e \approx 1,602 \times 10^{-19}$kulombów.

Ładunek elektryczny nie występuje w dowolnych ilościach, lecz zawsze w jednostkach będących całkowitymi wielokrotnościami ładunku elementarnego. Oznacza to, że ładunek dowolnego ciała jest równy $Q = n \cdot e$, gdzie$n$jest liczbą całkowitą (może być dodatnia lub ujemna).

Przykłady:

- Ładunek pojedynczego elektronu wynosi $-e$.
- Ładunek pojedynczego protonu wynosi $+e$.
- Ładunek jonów w roztworach elektroliatów jest również całkowitą wielokrotnością $e$.

### Prawo zachowania ładunku

Prawo zachowania ładunku stwierdza, że całkowity ładunek elektryczny w zamkniętym układzie izolowanym pozostaje stały w czasie. Innymi słowy, ładunek elektryczny nie może być ani stworzony, ani zniszczony, może jedynie być przenoszony z jednego miejsca na drugie.

Formułowanie tego prawa można przedstawić na kilka sposobów:

1. **Matematycznie:** Suma ładunków przed jakąkolwiek reakcją jest równa sumie ładunków po tej reakcji.
2. **Fizycznie:** Jeśli w danym obszarze przestrzeni ilość ładunku się zmienia, to musi być to wynikiem przepływu ładunku do tego obszaru lub z tego obszaru.
3. **W równaniach Maxwella:** W wyniku równań Maxwella, równanie ciągłości ładunku mówi o zachowaniu ładunku:

   $\frac{\partial \rho}{\partial t} + \nabla \cdot \mathbf{J} = 0$
   gdzie $\rho$ to gęstość ładunku, a $\mathbf{J}$ to gęstość prądu elektrycznego.

### Przykłady prawa zachowania ładunku:

- **W reakcjach chemicznych:** W elektrolicie, jony mogą reagować ze sobą, ale suma ładunków wszystkich jonów przed i po reakcji jest taka sama.
- **W obwodach elektrycznych:** W każdym węźle obwodu elektrycznego suma prądów wpływających do węzła jest równa sumie prądów wypływających z węzła.
- **W fizyce cząstek elementarnych:** Podczas anihilacji elektronu z pozytonem (antycząstką elektronu), ich ładunki się znoszą, ale całkowity ładunek przed i po reakcji pozostaje stały (wynosi zero).

Podsumowując, kwantowanie ładunku oznacza, że ładunek jest dyskretny, a prawo zachowania ładunku mówi, że całkowity ładunek w izolowanym układzie pozostaje niezmienny. Oba te pojęcia są fundamentami elektromagnetyzmu i fizyki cząstek elementarnych.

### 6. Omówić pojęcie multipoli.

### Multipole w fizyce

Multipole to pojęcie stosowane w fizyce, szczególnie w elektrodynamice i teorii pola, które odnosi się do sposobu opisu rozkładu ładunków lub mas w przestrzeni. Multipole są używane do opisu pola generowanego przez te rozkłady na różnych odległościach od źródła. Podstawowe typy multipoli to monopole, dipole, kwadrupole i wyższe multipole. Oto krótki opis każdego z tych typów:

#### 1. Monopole

- **Monopole** to najprostszy typ multipolu, reprezentujący pojedynczy ładunek punktowy lub masę punktową. W przypadku ładunku elektrycznego monopole to pojedynczy ładunek dodatni lub ujemny.
- Pole generowane przez monopole jest symetryczne kulowo i maleje z kwadratem odległości od źródła (zgodnie z prawem Coulomba).

#### 2. Dipole

- **Dipole** składają się z dwóch ładunków (lub mas) o przeciwnych znakach, oddalonych od siebie o pewną odległość.
- Typowy przykład to dipol elektryczny, złożony z ładunku dodatniego i ujemnego.
- Pole dipola maleje z trzecim potęgiem odległości od źródła i ma bardziej złożoną strukturę przestrzenną niż pole monopola.

#### 3. Kwadrupole

- **Kwadrupole** składają się z czterech ładunków (lub mas) rozmieszczonych w taki sposób, że suma momentów dipolowych jest zerowa, ale istnieje niezerowy moment kwadrupolowy.
- Typowy przykład to dwa dipole ustawione blisko siebie, ale skierowane w przeciwnych kierunkach.
- Pole kwadrupola maleje z piątą potęgiem odległości od źródła.

#### 4. Wyższe multipole

- **Wyższe multipole** to bardziej złożone układy ładunków, które generują pola malejące jeszcze szybciej wraz z odległością. Przykłady to oktupole (trzeciego rzędu) i jeszcze wyższe rzędy multipoli.
- Każdy wyższy multipol wnosi bardziej skomplikowaną strukturę pola, która maleje odpowiednio z większymi potęgami odległości.

#### Zastosowania multipoli

- **Elektrodynamika**: Opis i analiza pól elektromagnetycznych generowanych przez rozkłady ładunków i prądów.
- **Mechanika kwantowa**: Opis rozkładów ładunków w atomach i molekułach, wpływających na ich oddziaływania elektromagnetyczne.
- **Astrofizyka**: Badanie rozkładów mas w układach planetarnych, gwiazdowych i galaktycznych oraz ich wpływ na pola grawitacyjne.
- **Technika**: Projektowanie anten, gdzie różne konfiguracje dipoli i wyższych multipoli mogą być używane do generowania specyficznych wzorców promieniowania.

Multipole są potężnym narzędziem analitycznym, pozwalającym na uproszczenie i zrozumienie złożonych układów fizycznych poprzez analizę ich symetrii i rozkładu w przestrzeni.

### 7. Pojemność elektryczna. Wyprowadzić wzór na pojemność kondensatora płaskiego.

### Wyprowadzenie wzoru na pojemność kondensatora płaskiego:

1. **Definicja pojemności:**

   Pojemność $C$ kondensatora jest zdefiniowana jako stosunek ładunku $Q$ zgromadzonego na jednej z płytek do napięcia $V$ między płytkami:

   $$
    C = \frac{Q}{V}
   $$

2. **Prawo Gaussa:**

   Zakładamy, że kondensator jest naładowany i ładunek $+Q$ znajduje się na jednej płytce, a ładunek $-Q$ na drugiej. Prawo Gaussa dla elektryczności stwierdza, że strumień pola elektrycznego przez zamkniętą powierzchnię jest równy ładunkowi netto zamkniętemu wewnątrz tej powierzchni, podzielonemu przez przenikalność elektryczną próżni $\varepsilon_0$ :

   $$
    \oint_{\partial V} \mathbf{E} \cdot d\mathbf{A} = \frac{Q_{\text{wewn}}}{\varepsilon_0}
   $$

   W przypadku kondensatora płaskiego, rozważmy płytkę ładunku $+Q$ . Pole elektryczne $\mathbf{E}$ jest jednolite i skierowane prostopadle do powierzchni płytki.

3. **Natężenie pola elektrycznego:**

   Zakładamy, że pole elektryczne $\mathbf{E}$ jest jednolite między płytkami kondensatora. Wartość natężenia pola elektrycznego można wyrazić jako:

   $$
    E = \frac{Q}{\varepsilon_0 A}
   $$

   gdzie $A$ jest powierzchnią jednej płytki kondensatora.

4. **Związek między polem elektrycznym a napięciem:**

   Napięcie $V$ między płytkami kondensatora jest związane z polem elektrycznym $E$ oraz odległością $d$ między płytkami:

   $$
    V = E d
   $$

   Podstawiając $E$ z poprzedniego wzoru, otrzymujemy:

   $$
    V = \frac{Q}{\varepsilon_0 A} d
   $$

5. **Pojemność kondensatora:**

   Podstawiając powyższe wyrażenie napięcia $V$ do definicji pojemności, mamy:

   $$
    C = \frac{Q}{V} = \frac{Q}{\frac{Q d}{\varepsilon_0 A}} = \frac{\varepsilon_0 A}{d}
   $$

### Wzór na pojemność kondensatora płaskiego:

$$
C = \varepsilon_0 \frac{A}{d}
$$

gdzie:

- $C$ – pojemność kondensatora,
- $\varepsilon_0$ – przenikalność elektryczna próżni (≈$8.854 \times 10^{-12} \, \text{F/m}$),
- $A$ – powierzchnia jednej z płytek kondensatora,
- $d$ – odległość między płytkami kondensatora.

Jeśli między płytkami znajduje się materiał dielektryczny o przenikalności względnej $\varepsilon_r$ , wzór na pojemność zmienia się na:

$$
C = \varepsilon_0 \varepsilon_r \frac{A}{d}
$$

gdzie $\varepsilon_r$ jest przenikalnością względną materiału dielektrycznego.

### 8. Omówić zasady łączenia kondensatorów

## Omówienie zasad łączenia kondensatorów

Łączenie kondensatorów może być wykonane na dwa główne sposoby: szeregowe i równoległe. Każda z tych metod ma różne efekty na całkowitą pojemność, napięcie oraz inne właściwości układu. Oto szczegółowe omówienie obu metod:

### Łączenie równoległe kondensatorów

1. **Definicja**: Kondensatory są połączone równolegle, gdy ich bieguny dodatnie i ujemne są połączone ze sobą odpowiednio.

2. **Całkowita pojemność ($C_{\text{total}}$)**:

   - Całkowita pojemność jest sumą pojemności wszystkich kondensatorów.
     $$
     C_{\text{total}} = C_1 + C_2 + \cdots + C_n
     $$
     gdzie $C_1, C_2, \ldots, C_n$ to pojemności poszczególnych kondensatorów.

3. **Napięcie ($V$)**:

   - Napięcie przyłożone do układu jest takie samo dla wszystkich kondensatorów.
     $$
     V_{\text{total}} = V_1 = V_2 = \cdots = V_n
     $$

4. **Ładunek ($Q$)**:

   - Ładunek zgromadzony w układzie jest sumą ładunków zgromadzonych na poszczególnych kondensatorach.
     $$
     Q_{\text{total}} = Q_1 + Q_2 + \cdots + Q_n
     $$
     gdzie $Q = C \cdot V$.

5. **Zastosowania**:
   - Zwiększenie całkowitej pojemności.
   - Kondensatory o różnym napięciu roboczym mogą być łączone, jeśli wszystkie są przystosowane do tego samego napięcia.

### Łączenie szeregowe kondensatorów

1. **Definicja**: Kondensatory są połączone szeregowo, gdy biegun dodatni jednego kondensatora jest połączony z biegunem ujemnym następnego kondensatora i tak dalej.

2. **Całkowita pojemność ($C_{\text{total}}$)**:

   - Odwrotność całkowitej pojemności jest sumą odwrotności pojemności poszczególnych kondensatorów.
     $$
     \frac{1}{C_{\text{total}}} = \frac{1}{C_1} + \frac{1}{C_2} + \cdots + \frac{1}{C_n}
     $$
     Stąd:
     $$
     C_{\text{total}} = \left( \sum_{i=1}^{n} \frac{1}{C_i} \right)^{-1}
     $$

3. **Napięcie ($V$)**:

   - Całkowite napięcie przyłożone do układu jest sumą napięć na poszczególnych kondensatorach.
     $$
     V_{\text{total}} = V_1 + V_2 + \cdots + V_n
     $$

4. **Ładunek ($Q$)**:

   - Ładunek na wszystkich kondensatorach jest taki sam.
     $$
     Q_{\text{total}} = Q_1 = Q_2 = \cdots = Q_n
     $$
     gdzie $Q = C \cdot V$.

5. **Zastosowania**:
   - Zwiększenie napięcia roboczego układu (łącząc kondensatory o niskim napięciu roboczym można uzyskać układ działający przy wyższym napięciu).
   - Uzyskanie niższej pojemności, jeśli taka jest potrzebna.

### Porównanie

- **Równoległe**: Zwiększa pojemność, napięcie pozostaje takie samo jak na poszczególnych kondensatorach.
- **Szeregowe**: Zmniejsza pojemność, sumuje napięcia, co pozwala na pracę przy wyższych napięciach.

### Praktyczne wskazówki

- Kondensatory łączone równolegle powinny mieć zbliżone napięcie robocze, aby uniknąć ich uszkodzenia.
- Kondensatory łączone szeregowo powinny mieć zbliżone pojemności, aby napięcia na nich rozkładały się równomiernie.
- W układach wysokiego napięcia często stosuje się równoległe rezystory wyrównawcze (bleeder resistors), aby zapewnić równomierne rozłożenie napięcia na kondensatorach w połączeniach szeregowych.

Łączenie kondensatorów pozwala na dostosowanie parametrów układu do konkretnych wymagań projektowych, zwiększając jego elastyczność i funkcjonalność.

### 9. Prąd elektryczny. Przedstawić definicję i własności

**Definicja Prądu Elektrycznego:**

Prąd elektryczny to uporządkowany ruch ładunków elektrycznych, zazwyczaj elektronów, wzdłuż przewodnika. Jest to jedna z podstawowych wielkości fizycznych w elektrotechnice i elektronice. Prąd elektryczny jest mierzalny i jego natężenie oznaczane jest literą $I$. Jednostką natężenia prądu jest amper (A), nazwany na cześć francuskiego fizyka André-Marie Ampère'a.

**Własności Prądu Elektrycznego:**

1. **Natężenie prądu ($I$):** Jest to ilość ładunku przepływającego przez przekrój poprzeczny przewodnika w jednostce czasu. Wyrażane jest wzorem:
   $$I = \frac{Q}{t}$$
   gdzie$Q$to ładunek elektryczny (w kulombach, C), a$t$to czas (w sekundach, s).

2. **Napięcie ($V$):** Jest to różnica potencjałów elektrycznych między dwoma punktami w obwodzie elektrycznym, która powoduje przepływ prądu. Jednostką napięcia jest wolt (V).

3. **Rezystancja ($R$):** Jest to opór, jaki stawia przewodnik przepływającemu prądowi. Jednostką rezystancji jest om ($\Omega$). Związek między napięciem ($V$), prądem ($I$) i rezystancją ($R$) opisuje prawo Ohma:
   $$V = I \cdot R$$

4. **Moc elektryczna ($P$):** Jest to ilość energii elektrycznej zużywanej lub wytwarzanej w jednostce czasu. Jednostką mocy jest wat (W). Moc można wyrazić wzorami:
   $$P = V \cdot I$$
   lub, używając prawa Ohma:
   $$P = I^2 \cdot R \quad \text{lub} \quad P = \frac{V^2}{R}$$

5. **Prąd stały (DC) i prąd zmienny (AC):** Prąd stały (DC - Direct Current) to prąd, którego kierunek przepływu jest stały w czasie. Prąd zmienny (AC - Alternating Current) to prąd, którego kierunek i wartość zmieniają się cyklicznie w czasie. Przykładem prądu zmiennego jest prąd sinusoidalny używany w domowych instalacjach elektrycznych.

6. **Gęstość prądu ($J$):** Jest to natężenie prądu przepływającego przez jednostkowy przekrój poprzeczny przewodnika. Wyrażana jest wzorem:
   $$J = \frac{I}{A}$$
   gdzie$A$to pole przekroju poprzecznego przewodnika (w metrach kwadratowych,$m^2$).

7. **Nośniki prądu:** W metalach nośnikami prądu są elektrony. W półprzewodnikach nośnikami prądu mogą być elektrony (nośniki większościowe w półprzewodnikach typu n) lub dziury (nośniki większościowe w półprzewodnikach typu p). W elektrolitach prąd jest przenoszony przez jony.

**Podsumowanie:**

Prąd elektryczny jest kluczowym zjawiskiem w wielu dziedzinach nauki i techniki. Rozumienie jego własności oraz praw, które nim rządzą, pozwala na projektowanie i analizę obwodów elektrycznych, a także na rozwijanie technologii opartych na elektryczności.

### 10. Opór elektryczny. Prawo Ohma. Ograniczenia prawa ohma

### Opór elektryczny

**Opór elektryczny** to wielkość fizyczna charakteryzująca zdolność materiału do przeciwdziałania przepływowi prądu elektrycznego. Jest oznaczany symbolem $R$ i mierzy się go w omach $( \Omega$). Wzór na opór elektryczny jest wyrażony jako:

$$R = \frac{U}{I}$$

gdzie: -$U$to napięcie (w woltach, V), -$I$to natężenie prądu (w amperach, A).

### Prawo Ohma

**Prawo Ohma** opisuje zależność między napięciem, natężeniem prądu i oporem w obwodzie elektrycznym. Prawo to stwierdza, że:

$I = \frac{U}{R}$

lub w formie bardziej powszechnie używanej:

$U = I \cdot R$

gdzie: -$U$to napięcie (w woltach, V), -$I$to natężenie prądu (w amperach, A), -$R$to opór elektryczny (w omach,$\Omega$).

Prawo Ohma jest podstawowym prawem w elektrotechnice, stosowanym do analizowania i projektowania obwodów elektrycznych.

### Ograniczenia prawa Ohma

Pomimo szerokiego zastosowania prawa Ohma, istnieją pewne ograniczenia:

1. **Nieliniowe elementy**: Prawo Ohma obowiązuje tylko w przypadku materiałów i elementów liniowych, czyli takich, których opór jest stały niezależnie od natężenia prądu. Przykładem nieliniowych elementów są półprzewodniki, takie jak diody i tranzystory, których charakterystyki$U$-$I$nie są liniowe.

2. **Warunki temperaturowe**: Opór większości materiałów zmienia się wraz z temperaturą. Prawo Ohma w swojej podstawowej formie nie uwzględnia tego efektu. W wysokich temperaturach, przewodniki mogą zmieniać swoje właściwości, co wpływa na ich opór elektryczny.

3. **Materiały nieliniowe**: Niektóre materiały, takie jak termistory czy rezystory nieliniowe, zmieniają swój opór w zależności od parametrów takich jak napięcie, natężenie prądu lub temperatura.

4. **Prąd przemienny (AC)**: Prawo Ohma w swojej prostej formie odnosi się głównie do prądu stałego (DC). W przypadku prądu przemiennego (AC), dodatkowe czynniki, takie jak indukcyjność i pojemność, wpływają na opór (w tym przypadku na impedancję), co komplikuje analizę.

5. **Efekty kwantowe i mikroskopowe**: W skali mikro- i nanometrycznej, zwłaszcza w urządzeniach elektronicznych o bardzo małych rozmiarach, prawo Ohma może nie być dokładne z powodu efektów kwantowych i innych zjawisk fizycznych, które nie są uwzględniane w klasycznym podejściu.

Podsumowując, prawo Ohma jest fundamentem dla zrozumienia obwodów elektrycznych, ale należy pamiętać o jego ograniczeniach i stosować je z uwzględnieniem specyficznych warunków oraz charakterystyki elementów w obwodzie.

### 11. Omówić łączenie oporników

Łączenie oporników jest podstawową koncepcją w elektronice, umożliwiającą kontrolowanie przepływu prądu w obwodach elektrycznych. Oporniki mogą być łączone na dwa główne sposoby: szeregowo i równolegle. Każdy sposób łączenia ma inne właściwości i zastosowania.

### Łączenie szeregowe

W połączeniu szeregowym oporniki są połączone jeden za drugim, tak że ten sam prąd przepływa przez każdy z nich. Wartość całkowitej rezystancji $R_{total}$ w połączeniu szeregowym jest sumą wszystkich pojedynczych rezystancji $R_1, R_2, \ldots, R_n$:

$$ R\_{total} = R_1 + R_2 + \ldots + R_n $$

**Właściwości:**

- Prąd jest taki sam przez wszystkie oporniki.
- Napięcie całkowite rozkłada się na poszczególne oporniki w zależności od ich wartości rezystancji.

**Przykład:**
Jeśli mamy trzy oporniki o wartościach 10 Ω, 20 Ω i 30 Ω połączone szeregowo, całkowita rezystancja wynosi:

$$ R\_{total} = 10 \, \Omega + 20 \, \Omega + 30 \, \Omega = 60 \, \Omega $$

### Łączenie równoległe

W połączeniu równoległym oporniki są połączone w taki sposób, że każdy z nich jest podłączony do tych samych dwóch punktów, a napięcie na każdym oporniku jest takie samo. Wartość całkowitej rezystancji $R_{total}$ w połączeniu równoległym jest odwrotnością sumy odwrotności poszczególnych rezystancji:

$$ \frac{1}{R\_{total}} = \frac{1}{R_1} + \frac{1}{R_2} + \ldots + \frac{1}{R_n} $$

**Właściwości:**

- Napięcie na wszystkich opornikach jest takie samo.
- Całkowity prąd płynący przez obwód jest sumą prądów płynących przez poszczególne oporniki.

**Przykład:**
Jeśli mamy trzy oporniki o wartościach 10 Ω, 20 Ω i 30 Ω połączone równolegle, całkowita rezystancja wynosi:

$$ \frac{1}{R*{total}} = \frac{1}{10 \, \Omega} + \frac{1}{20 \, \Omega} + \frac{1}{30 \, \Omega} $$
$$ \frac{1}{R*{total}} = 0.1 + 0.05 + 0.0333 $$
$$ \frac{1}{R*{total}} = 0.1833 $$
$$ R*{total} \approx 5.45 \, \Omega $$

### Porównanie

- **Łączenie szeregowe** zwiększa całkowitą rezystancję, co powoduje mniejszy przepływ prądu przy danym napięciu.
- **Łączenie równoległe** zmniejsza całkowitą rezystancję, co powoduje większy przepływ prądu przy danym napięciu.

### Zastosowania

- **Łączenie szeregowe** jest często stosowane, gdy chcemy zwiększyć całkowitą rezystancję obwodu lub gdy chcemy, aby prąd przepływał przez wszystkie elementy w obwodzie.
- **Łączenie równoległe** jest używane, gdy chcemy zmniejszyć rezystancję lub rozłożyć napięcie na kilka elementów, aby każdy z nich miał to samo napięcie.

Zrozumienie tych podstawowych sposobów łączenia oporników jest kluczowe do projektowania i analizowania bardziej skomplikowanych obwodów elektrycznych.

### 12. Przemiany energii w obwodach prądu

# Przemiany energii w obwodach prądu

Przemiany energii w obwodach prądu elektrycznego dotyczą transferu i konwersji energii elektrycznej w różne formy, takie jak ciepło, światło, ruch mechaniczny, itp. Zrozumienie tych procesów jest kluczowe dla projektowania i analizowania obwodów elektrycznych oraz urządzeń elektronicznych.

Oto kluczowe przemiany energii w obwodach prądu elektrycznego:

1. **Przemiana energii elektrycznej na ciepło (efekt Joule'a)**:

   - Kiedy prąd elektryczny przepływa przez opornik (rezystor), część energii elektrycznej jest przekształcana w ciepło. Ilość wydzielanego ciepła jest proporcjonalna do kwadratu natężenia prądu i wartości oporu zgodnie z prawem Joule'a: $P = I^2 R$, gdzie $P$ to moc wydzielana w postaci ciepła, $I$ to natężenie prądu, a $R$ to rezystancja.

2. **Przemiana energii elektrycznej na energię mechaniczną (silniki elektryczne)**:

   - W silnikach elektrycznych energia elektryczna jest przekształcana w energię mechaniczną. Prąd płynący przez cewki silnika tworzy pole magnetyczne, które oddziałuje z magnesami lub innymi cewkami, powodując ruch mechaniczny.

3. **Przemiana energii elektrycznej na światło (diody LED, żarówki)**:

   - W diodach elektroluminescencyjnych (LED) energia elektryczna jest przekształcana bezpośrednio na światło. W żarówkach klasycznych część energii elektrycznej przekształcana jest na ciepło, a część na światło.

4. **Przemiana energii elektrycznej na energię chemiczną (akumulatory)**:

   - W akumulatorach energia elektryczna jest przekształcana w energię chemiczną podczas ładowania, a następnie ta energia chemiczna jest przekształcana z powrotem w energię elektryczną podczas rozładowywania.

5. **Przemiana energii chemicznej na energię elektryczną (ogniwa galwaniczne)**:
   - W ogniwach galwanicznych reakcje chemiczne wytwarzają energię elektryczną.

### Prawa i zasady związane z przemianami energii

1. **Prawo Ohma**:

   - Prawo Ohma określa zależność między napięciem ($V$), natężeniem prądu ($I$) i rezystancją ($R$): $V = I \cdot R$.

2. **Prawo Kirchhoffa**:

   - Pierwsze prawo Kirchhoffa (prawo węzłów) mówi, że suma prądów wpływających do węzła jest równa sumie prądów wypływających.
   - Drugie prawo Kirchhoffa (prawo oczek) mówi, że suma napięć w zamkniętym obwodzie (oczku) jest równa zeru.

3. **Prawo Faradaya**:
   - Prawo Faradaya mówi, że zmieniające się pole magnetyczne może indukować siłę elektromotoryczną (SEM) w przewodniku.

### Praktyczne przykłady

1. **Grzałki elektryczne**:

   - Przemieniają energię elektryczną w ciepło, wykorzystywane w urządzeniach takich jak kuchenki elektryczne, żelazka, suszarki do włosów.

2. **Lampy**:

   - Żarówki i lampy fluorescencyjne przekształcają energię elektryczną w światło (i ciepło w przypadku żarówek klasycznych).

3. **Silniki elektryczne**:

   - W wentylatorach, pompach, narzędziach elektrycznych energia elektryczna jest przekształcana w energię mechaniczną.

4. **Akumulatory i baterie**:
   - Magazynują energię chemiczną, którą można przekształcić w energię elektryczną.

Zrozumienie tych podstawowych koncepcji jest kluczowe dla inżynierów elektryków i elektroników, którzy projektują i optymalizują obwody elektryczne do różnych zastosowań.

### 13. Sens siły elektromotorycznej

### Siła elektromotoryczna

**Definicja:**
Siła elektromotoryczna (SEM) to napięcie generowane przez źródło prądu elektrycznego, takie jak bateria, akumulator lub generator, gdy nie przepływa przez nie prąd (obwód jest otwarty). SEM jest często oznaczana symbolem $\mathcal{E}$ lub $E$ i mierzy się ją w woltach (V).

**Zasada działania:**
SEM powstaje na skutek różnicy potencjałów wywołanej przez procesy chemiczne (w bateriach) lub mechaniczne (w generatorach). W bateriach reakcje chemiczne zachodzące na elektrodach powodują separację ładunków, co prowadzi do różnicy potencjałów między nimi. W generatorach zjawiska elektromagnetyczne, takie jak indukcja elektromagnetyczna, generują napięcie.

**Równania:**

- **Prawo Ohma**:
  $$V = IR$$
  Gdzie

  - $V$ to napięcie,
  - $I$ to natężenie prądu, a
  - $R$ to opór.

- **Równanie SEM** w zamkniętym obwodzie:
  $$
  \mathcal{E} = V + Ir
  $$
  Gdzie $\mathcal{E}$ to siła elektromotoryczna, $V$ to napięcie na zewnętrznym obwodzie, $I$ to natężenie prądu, a $r$ to wewnętrzny opór źródła.

**Praktyczne zastosowania:**

- **Baterie i akumulatory**: Dostarczają energii elektrycznej do różnorodnych urządzeń.
- **Generatory**: Wytwarzają prąd w elektrowniach, przekształcając energię mechaniczną na elektryczną.
- **Silniki elektryczne**: Konwertują energię elektryczną z powrotem na mechaniczną.

**Ważne uwagi:**

- **Wewnętrzny opór**: Wszystkie rzeczywiste źródła mają pewien opór wewnętrzny, co powoduje, że napięcie na zaciskach źródła spada, gdy przepływa prąd.
- **Spadek napięcia**: W praktyce, gdy obwód jest zamknięty i przepływa prąd, napięcie na zewnętrznych zaciskach źródła jest mniejsze niż SEM z powodu spadków napięcia na wewnętrznym oporze źródła.

**Różnice między SEM a napięciem:**

- **SEM**: Napięcie, gdy obwód jest otwarty (brak przepływu prądu).
- **Napięcie**: Mierzone napięcie w obwodzie zamkniętym, które może być mniejsze od SEM z powodu spadków napięcia na oporach wewnętrznych i zewnętrznych.

Rozumienie siły elektromotorycznej jest kluczowe dla projektowania i analizy obwodów elektrycznych oraz dla optymalizacji pracy różnych urządzeń elektrycznych i elektronicznych.

### 14. Prawa Kirchoffa

Prawa Kirchhoffa to dwa podstawowe prawa elektrotechniki, które dotyczą obwodów elektrycznych. Sformułowane przez Gustava Kirchhoffa w 1845 roku, umożliwiają analizę prądów i napięć w złożonych obwodach elektrycznych. Oto one:

### Prawo Kirchhoffa prądowe (I prawo Kirchhoffa)

Zwane również prawem węzłów, stwierdza, że suma algebraiczna prądów wpływających do węzła (czyli punktu w obwodzie, gdzie spotyka się kilka przewodów) jest równa sumie algebraicznej prądów wypływających z tego węzła.

Matematycznie można to zapisać jako:
$$\sum_{k=1}^{n} I_k = 0$$
gdzie:

- $I_k$ to prąd k-ty wpływający lub wypływający z węzła,
- n to liczba gałęzi połączonych w węźle.

### Prawo Kirchhoffa napięciowe (II prawo Kirchhoffa)

Zwane również prawem oczek, mówi, że w zamkniętym obwodzie (oczku) suma algebraiczna napięć jest równa zero. Oznacza to, że suma napięć na wszystkich elementach w danym oczku, uwzględniając ich znaki, jest równa zero.

Matematycznie można to zapisać jako:
$$\sum_{k=1}^{m} V_k = 0$$
gdzie:

- $V_k$ to napięcie k-tego elementu w oczku,
- m to liczba elementów w oczku.

### Przykład zastosowania

Wyobraźmy sobie prosty obwód z jednym źródłem napięcia $V$ i trzema rezystorami $R_1$, $R_2$ i $R_3$ połączonymi w trójkąt. Aby obliczyć prądy w tym obwodzie, można zastosować oba prawa Kirchhoffa.

1. **Prawo węzłów**: W węźle gdzie łączą się trzy prądy $I_1$, $I_2$ i $I_3$:
   $$I_1 + I_2 + I_3 = 0$$

2. **Prawo oczek**: Dla trzech oczek w trójkącie możemy zapisać:
   - Oczko 1: $V - I_1R_1 - I_2R_2 = 0$
   - Oczko 2: $V - I_2R_2 - I_3R_3 = 0$
   - Oczko 3: $V - I_1R_1 - I_3R_3 = 0$

Rozwiązując te równania, można znaleźć wartości prądów w każdym z gałęzi obwodu.

Prawa Kirchhoffa są fundamentem do analizy bardziej skomplikowanych obwodów elektrycznych, gdzie występuje wiele źródeł napięcia i różnych elementów obwodu.

### 15. Pole magenetyczne i jego własności. Siła Lorentza

### Pole Magnetyczne i Jego Własności

#### Definicja i Pochodzenie

Pole magnetyczne jest wektorowym polem fizycznym, które opisuje wpływ siły magnetycznej na poruszające się ładunki elektryczne, prądy i materiały magnetyczne. Jest generowane przez:

1. **Ruchome ładunki elektryczne** (np. prąd elektryczny w przewodnikach).
2. **Zjawiska kwantowe** (np. momenty magnetyczne cząsteczek, takich jak elektrony).

Pole magnetyczne może być przedstawione za pomocą linii pola magnetycznego, które wskazują kierunek i siłę pola.

#### Własności Pola Magnetycznego

1. **Kierunek i Wartość**: Kierunek pola magnetycznego w punkcie jest określony przez kierunek siły działającej na północny biegun magnetyczny umieszczony w tym punkcie. Wartość pola magnetycznego jest miarą siły działającej na jednostkowy ładunek poruszający się w polu.

2. **Jednostki**:

   - W układzie SI, jednostką pola magnetycznego jest tesla (T).
   - Inna jednostka to gauss (G), gdzie 1 T = 10,000 G.

3. **Prawo Ampera**: Obiegowe pole magnetyczne wokół przewodnika z prądem jest proporcjonalne do prądu przepływającego przez przewodnik. Wyrażone matematycznie jako:

   $$
   \oint \vec{B} \cdot d\vec{l} = \mu_0 I
   $$

   gdzie $\vec{B}$ to pole magnetyczne, $d\vec{l}$ to element obiegu, $\mu_0$ to przenikalność magnetyczna próżni, a $I$ to prąd.

4. **Indukcja Magnetyczna**: Zjawisko indukcji elektromagnetycznej polega na generowaniu siły elektromotorycznej (SEM) w przewodniku, gdy zmienia się strumień magnetyczny przez powierzchnię obejmowaną przez przewodnik.

### Siła Lorentza

Siła Lorentza opisuje działanie pola elektromagnetycznego na poruszający się ładunek elektryczny. Jest ona sumą dwóch składników: siły elektrycznej i siły magnetycznej.

#### Wyrażenie Matematyczne

Jeśli ładunek $q$ porusza się z prędkością $\vec{v}$ w polu elektrycznym $\vec{E}$ i polu magnetycznym $\vec{B}$, to siła Lorentza $\vec{F}$ jest dana wzorem:

$$
\vec{F} = q (\vec{E} + \vec{v} \times \vec{B})
$$

#### Składniki Siły Lorentza

1. **Siła Elektryczna**: $\vec{F}_E = q \vec{E}$

   - Działa na ładunek niezależnie od jego ruchu.

2. **Siła Magnetyczna**: $\vec{F}_B = q (\vec{v} \times \vec{B})$
   - Jest zależna od prędkości ładunku i pola magnetycznego.
   - Kierunek siły magnetycznej jest prostopadły do płaszczyzny wyznaczonej przez $\vec{v}$ i $\vec{B}$ (prawo lewej dłoni).

#### Zastosowanie Siły Lorentza

1. **Cyclotrony i Synchrotrony**: Urządzenia używane do przyspieszania cząstek naładowanych.
2. **Silniki Elektryczne**: Działają na zasadzie siły magnetycznej działającej na prądy w przewodnikach.
3. **Generatory Elektryczne**: Konwersja energii mechanicznej na energię elektryczną poprzez indukcję magnetyczną.

Podsumowując, pole magnetyczne i siła Lorentza są fundamentalnymi pojęciami w fizyce, kluczowymi dla zrozumienia działania wielu urządzeń elektrycznych i zjawisk przyrodniczych.

### 16. Ruch ładunku w polach elektrycznym i magnetycznym

### Ruch ładunku w polach elektrycznym i magnetycznym

Ruch ładunku w polach elektrycznym i magnetycznym jest fundamentalnym zagadnieniem w fizyce. Oto omówienie podstawowych zasad:

### Pole elektryczne

**Definicja:** Pole elektryczne jest przestrzenią wokół ładunku elektrycznego, w której inne ładunki doświadczają siły elektrostatycznej.

**Siła elektryczna:** Na ładunek $q$ umieszczony w polu elektrycznym $\mathbf{E}$ działa siła elektryczna $\mathbf{F}$ dana wzorem:
$$\mathbf{F} = q \mathbf{E}$$

**Równanie ruchu:** Jeżeli ładunek $q$ ma masę $m$, to jego ruch w polu elektrycznym można opisać równaniem Newtona:
$$m \mathbf{a} = q \mathbf{E}$$
gdzie $\mathbf{a}$ jest przyspieszeniem ładunku.

### Pole magnetyczne

**Definicja:** Pole magnetyczne jest przestrzenią wokół magnesu lub przewodnika z prądem, w której inne ładunki poruszające się doświadczają siły magnetycznej.

**Siła Lorentza:** Na ładunek $q$ poruszający się z prędkością $\mathbf{v}$ w polu magnetycznym $\mathbf{B}$ działa siła Lorentza:
$$\mathbf{F} = q (\mathbf{v} \times \mathbf{B})$$
gdzie $\times$ oznacza iloczyn wektorowy.

### Pole elektryczne i magnetyczne jednocześnie

**Siła Lorentza:** Jeżeli ładunek $q$ porusza się w polu elektrycznym $\mathbf{E}$ i polu magnetycznym $\mathbf{B}$, całkowita siła działająca na ładunek jest sumą sił elektrycznej i magnetycznej:
$$\mathbf{F} = q (\mathbf{E} + \mathbf{v} \times \mathbf{B})$$

**Równanie ruchu:** Równanie ruchu ładunku w polu elektrycznym i magnetycznym jest:
$$m \mathbf{a} = q (\mathbf{E} + \mathbf{v} \times \mathbf{B})$$

### Przykłady zastosowań

1. **Rurka katodowa:** W klasycznym doświadczeniu z rurką katodową, elektrony przyspieszane są przez pole elektryczne, a następnie ich tor jest zakrzywiany przez pole magnetyczne.

2. **Cyklotron:** Cyklotron jest urządzeniem, które wykorzystuje pola elektryczne i magnetyczne do przyspieszania cząstek naładowanych po spiralnych torach.

3. **Spektrometr mas:** W spektrometrach mas ładunki są przyspieszane i zakrzywiane przez pola elektryczne i magnetyczne, co pozwala na rozdzielenie cząstek o różnej masie.

### Tor cząstki w polu magnetycznym

Kiedy ładunek porusza się w jednolitym polu magnetycznym, jego tor jest zakrzywiany w wyniku działania siły Lorentza, co prowadzi do ruchu po okręgu o promieniu $r$ danym wzorem:
$$r = \frac{mv}{qB}$$
gdzie $v$ jest prędkością ładunku prostopadłą do pola magnetycznego, $m$ jest masą ładunku, a $B$ jest indukcją pola magnetycznego.

### Podsumowanie

Ruch ładunku w polach elektrycznym i magnetycznym jest opisany przez prawo Coulomba, równania Newtona i siłę Lorentza. Analiza tych ruchów jest kluczowa w wielu dziedzinach fizyki i inżynierii, od klasycznych układów mechanicznych po nowoczesne akceleratory cząstek.

### 17. Oddziałyanie przewodników z prądem

## Oddziaływanie przewodników z prądem

Oddziaływanie przewodników z prądem to zjawisko fizyczne wynikające z oddziaływania magnetycznego pomiędzy przewodnikami, przez które przepływa prąd elektryczny. Kluczowym elementem tego zjawiska jest fakt, że każdy przewodnik z prądem generuje wokół siebie pole magnetyczne, które może oddziaływać na inne przewodniki.

### Prawo Ampère'a

Prawo Ampère'a jest fundamentalnym prawem elektromagnetyzmu, które opisuje, jak prądy elektryczne generują pola magnetyczne. Zgodnie z tym prawem, linie pola magnetycznego tworzą zamknięte okręgi wokół przewodnika z prądem.

### Siła oddziaływania między dwoma przewodnikami

Dwa równoległe przewodniki z prądem oddziałują na siebie siłą, której wartość można obliczyć na podstawie prawa Biota-Savarta i siły Lorentza. Istnieją dwa główne przypadki:

1. **Prądy płynące w tę samą stronę**: Dwa przewodniki, przez które prąd płynie w tym samym kierunku, przyciągają się.
2. **Prądy płynące w przeciwnych kierunkach**: Dwa przewodniki, przez które prąd płynie w przeciwnych kierunkach, odpychają się.

### Wzór na siłę oddziaływania

Siłę oddziaływania między dwoma równoległymi przewodnikami można wyrazić wzorem:

$$F = \frac{\mu_0 I_1 I_2}{2 \pi d} L$$

gdzie:

- $F$ to siła oddziaływania,
- $\mu_0$ to przenikalność magnetyczna próżni (4π × 10^-7 H/m),
- $I_1$ i $I_2$ to natężenia prądu płynące przez przewodniki,
- $d$ to odległość między przewodnikami,
- $L$ to długość przewodników, przez którą przepływa prąd.

### Praktyczne zastosowania

Oddziaływanie przewodników z prądem jest podstawą działania wielu urządzeń elektrycznych i elektromagnetycznych, takich jak:

- Silniki elektryczne,
- Generatory,
- Elektromagnesy,
- Transformatory.

### Wnioski

Oddziaływanie przewodników z prądem jest jednym z fundamentalnych zjawisk elektromagnetyzmu, które ma szerokie zastosowanie w technologii. Zrozumienie tego zjawiska pozwala na projektowanie i optymalizację urządzeń wykorzystujących prądy elektryczne i pola magnetyczne.

Jeżeli masz jakieś konkretne pytania dotyczące tego tematu, chętnie na nie odpowiem!

### 18. Cyklotron i jego własności. Ruch ładunku w polu magentycznym

# Cyklotron i jego własności. Ruch ładunku w polu magnetycznym

Cyklotron to rodzaj akceleratora cząstek, który wykorzystuje pole magnetyczne i elektryczne do przyspieszania naładowanych cząstek (najczęściej protonów lub jonów) do wysokich energii. Składa się głównie z dwóch półkolistych elektrod zwanych "dee" (od ich kształtu przypominającego literę "D"), umieszczonych w próżniowym pojemniku między biegunami magnesu.

## Własności cyklotronu

1. **Pole magnetyczne**: Stałe pole magnetyczne jest ustawione prostopadle do płaszczyzny ruchu cząstek. Powoduje to, że cząstki poruszają się po spiralnych torach wewnątrz "dee".

2. **Pole elektryczne**: Zmiennie pole elektryczne jest przykładane między "dee", przyspieszając cząstki za każdym razem, gdy przechodzą przez szczelinę między elektrodami.

3. **Częstotliwość cyklotronowa**: Częstotliwość zmiany pola elektrycznego musi być zharmonizowana z ruchem cząstek, co jest określone przez wzór na częstotliwość cyklotronową:

   $$
   f = \frac{qB}{2\pi m}
   $$

   gdzie:

   - $f$ - częstotliwość cyklotronowa,
   - $q$ - ładunek cząstki,
   - $B$ - indukcja magnetyczna,
   - $m$ - masa cząstki.

4. **Promień toru**: Promień toru cząstki zwiększa się wraz z jej prędkością, co powoduje, że cząstki poruszają się po coraz większych spiralach. Promień toru $r$ można obliczyć za pomocą wzoru:
   $$
   r = \frac{mv}{qB}
   $$
   gdzie:
   - $v$ - prędkość cząstki.

## Ruch ładunku w polu magnetycznym

Ruch naładowanej cząstki w jednorodnym polu magnetycznym jest opisany przez siłę Lorentza:

$$
\vec{F} = q(\vec{v} \times \vec{B})
$$

gdzie:

- $\vec{F}$ - siła działająca na cząstkę,
- $q$ - ładunek cząstki,
- $\vec{v}$ - prędkość cząstki,
- $\vec{B}$ - wektor indukcji magnetycznej.

Siła Lorentza działa zawsze prostopadle do kierunku prędkości cząstki, co powoduje zakrzywienie toru ruchu naładowanej cząstki. W efekcie, cząstka porusza się po okręgu (w przypadku jednorodnego pola magnetycznego) lub spirali (jeśli dodatkowo występuje pole elektryczne zmieniające energię cząstki).

## Zastosowania cyklotronu

1. **Badania naukowe**: Cyklotrony są używane do badań struktury jądra atomowego, reakcji jądrowych i produkcji izotopów promieniotwórczych.

2. **Medycyna**: Cyklotrony są wykorzystywane do produkcji radioizotopów stosowanych w diagnostyce i terapii medycznej, np. w tomografii pozytonowej (PET).

3. **Przemysł**: Służą do badań materiałowych, w tym do analizy strukturalnej materiałów i badania defektów w strukturach metalowych.

Cyklotron jest jednym z kluczowych narzędzi w fizyce cząstek, umożliwiającym badanie podstawowych właściwości materii i rozwój nowych technologii w różnych dziedzinach.

### 19. Prawo Apmpere'a

Prawo Ampère'a, inaczej znane jako prawo Ampère'a z poprawką Maxwella, jest jednym z fundamentalnych praw elektromagnetyzmu. Formułuje ono związek między polem magnetycznym a prądem elektrycznym, który je generuje. W swojej ogólnej formie prawo Ampère'a jest zapisywane jako jedno z równań Maxwella:

$$\nabla \times \mathbf{B} = \mu_0 \mathbf{J} + \mu_0 \epsilon_0 \frac{\partial \mathbf{E}}{\partial t}$$

Gdzie:

- $\mathbf{B}$ to pole magnetyczne,
- $\mu_0$ to przenikalność magnetyczna próżni,
- $\mathbf{J}$ to gęstość prądu elektrycznego,
- $\epsilon_0$ to przenikalność elektryczna próżni,
- $\mathbf{E}$ to pole elektryczne,
- $\nabla \times$ to operator rotacji.

W swojej pierwotnej formie (bez poprawki Maxwella) prawo Ampère'a mówiło, że:

$$\oint_{\partial S} \mathbf{B} \cdot d\mathbf{l} = \mu_0 I_{\text{przez } S}$$

Gdzie:

- $\oint_{\partial S}$ oznacza całkowanie po zamkniętej krzywej $\partial S$,
- $\mathbf{B}$ to pole magnetyczne,
- $d\mathbf{l}$ to wektorowy element linii zamkniętej,
- $\mu_0$ to przenikalność magnetyczna próżni,
- $I_{\text{przez } S}$ to całkowity prąd przepływający przez powierzchnię $S$.

Dodanie członu $\mu_0 \epsilon_0 \frac{\partial \mathbf{E}}{\partial t}$ przez Maxwella było kluczowe dla spójności równań elektromagnetycznych i dla opisu zjawisk fal elektromagnetycznych.

Prawo Ampère'a jest fundamentem dla zrozumienia działania elektromagnesów, cewki indukcyjnej i innych urządzeń elektrycznych, które wykorzystują pole magnetyczne generowane przez prąd elektryczny.

### 20. Wytwarzanie pola magnetycznego. Pole wewnątrz solenoidu

## Wytwarzanie pola magnetycznego. Pole wewnątrz solenoidu

Wytwarzanie pola magnetycznego za pomocą solenoidu to klasyczny przykład zastosowania prawa Ampera w elektromagnetyzmie. Solenoid jest cewką o licznych zwojach przewodu, która generuje pole magnetyczne, gdy przepływa przez nią prąd elektryczny. Pola magnetyczne wytwarzane przez solenoid są szczególnie interesujące, ponieważ mogą być dobrze kontrolowane i wykorzystywane w wielu zastosowaniach, takich jak elektromagnesy, transformatory i silniki elektryczne.

### Pole Magnetyczne Wewnątrz Solenoidu

Pole magnetyczne wewnątrz solenoidu (idealnego, czyli o nieskończonej długości) jest jednorodne i można je obliczyć za pomocą następującego wzoru:

$$B = \mu_0 \cdot n \cdot I$$

gdzie:

- $B$ to natężenie pola magnetycznego,
- $\mu_0$ to przenikalność magnetyczna próżni ($\mu_0 = 4\pi \times 10^{-7} \, \text{H/m}$),
- $n$ to liczba zwojów na jednostkę długości (liczba zwojów $N$ podzielona przez długość $L$ solenoidu: $n = \frac{N}{L}$),
- $I$ to prąd elektryczny przepływający przez solenoid.

### Wzór w praktyce

Rozważmy przykład, aby zrozumieć, jak zastosować ten wzór w praktyce. Załóżmy, że mamy solenoid o długości $0.5 \, \text{m}$, z 1000 zwojami, przez który przepływa prąd o natężeniu $2 \, \text{A}$.

1. **Oblicz liczbę zwojów na jednostkę długości:**
   $$n = \frac{N}{L} = \frac{1000}{0.5} = 2000 \, \text{zwojów/m}$$

2. **Zastosuj wzór na pole magnetyczne:**
   $$B = \mu_0 \cdot n \cdot I = (4\pi \times 10^{-7} \, \text{H/m}) \cdot 2000 \cdot 2$$

3. **Wykonaj obliczenia:**
   $$B = 4\pi \times 10^{-7} \cdot 2000 \cdot 2$$
   $$B = 4\pi \times 10^{-7} \cdot 4000$$
   $$B = 16\pi \times 10^{-7}$$
   $$B \approx 50.27 \times 10^{-7} \, \text{T}$$
   $$B \approx 5.027 \times 10^{-6} \, \text{T}$$
   $$B \approx 5.03 \, \mu\text{T}$$

Tak więc, natężenie pola magnetycznego wewnątrz tego solenoidu wynosi około $5.03 \, \mu\text{T}$.

### Uwagi Dodatkowe

- W rzeczywistości solenoidy mają skończoną długość, więc pole magnetyczne na końcach solenoidu nie będzie idealnie jednorodne. W praktyce, dla długich solenoidów te efekty są znikome.
- Jeśli solenoid jest umieszczony w materiale o przenikalności magnetycznej innej niż próżnia, należy użyć odpowiedniej przenikalności $\mu$ zamiast $\mu_0$.

Ten prosty wzór pozwala na szybkie obliczenie pola magnetycznego wewnątrz solenoidu i jest podstawą wielu aplikacji w dziedzinie elektromagnetyzmu.

### 21. Prawo Faraday'a

Prawo Faradaya odnosi się do elektromagnetyzmu i obejmuje dwa podstawowe prawa sformułowane przez Michaela Faradaya w XIX wieku: prawo indukcji elektromagnetycznej oraz prawo elektrolizy.

### Prawo indukcji elektromagnetycznej Faradaya

Prawo to opisuje, jak zmienne pole magnetyczne może indukować pole elektryczne. Mówi ono, że siła elektromotoryczna (SEM) indukowana w zamkniętym obwodzie jest proporcjonalna do szybkości zmiany strumienia magnetycznego przez powierzchnię ograniczoną tym obwodem. Matematycznie można je zapisać jako:

$$\mathcal{E} = -\frac{d\Phi_B}{dt}$$

gdzie:

- $\mathcal{E}$ to siła elektromotoryczna (SEM),
- $\Phi_B$ to strumień magnetyczny,
- $\frac{d\Phi_B}{dt}$ to szybkość zmiany strumienia magnetycznego.

### Prawo elektrolizy Faradaya

Prawo to określa związek między ilością ładunku przepływającego przez elektrolit a ilością wytrąconej substancji chemicznej. Faraday sformułował dwa prawa elektrolizy:

1. **Pierwsze prawo elektrolizy Faradaya**:
   Masa substancji $m$ wytrąconej na elektrodzie jest proporcjonalna do ilości ładunku $Q$ przepływającego przez elektrolit:

   $$m = k \cdot Q$$

   gdzie:

   - $m$ to masa wytrąconej substancji,
   - $k$ to stała elektrochemiczna, zależna od rodzaju substancji.

2. **Drugie prawo elektrolizy Faradaya**:
   Masa substancji $m$ wytrąconej na elektrodzie jest proporcjonalna do jej równoważnika chemicznego $E$ i odwrotnie proporcjonalna do wartości liczby Faradaya $F$:

   $$m = \frac{E \cdot Q}{F}$$

   gdzie:

   - $E$ to równoważnik chemiczny substancji,
   - $F$ to liczba Faradaya, czyli ilość ładunku przypadająca na jeden mol elektronów ($F \approx 96485$ C/mol).

### Zastosowania prawa Faradaya

Prawo Faradaya ma szerokie zastosowanie w różnych dziedzinach:

- **Generatory elektryczne**: Zasada działania generatorów prądu opiera się na indukcji elektromagnetycznej.
- **Transformator**: Działa na zasadzie zmiany napięcia w oparciu o prawo indukcji elektromagnetycznej.
- **Elektroliza**: Wykorzystuje prawa elektrolizy do produkcji metali i innych substancji chemicznych.
- **Silniki elektryczne**: Odwrócenie działania generatora, gdzie prąd elektryczny generuje ruch mechaniczny.

Prawo Faradaya stanowi podstawę dla wielu technologii w energetyce, przemyśle i badaniach naukowych.

### 22. Sens i znaczenie reguły Lenza

## Sens i znaczenie reguły Lenza

Reguła Lenza jest fundamentalnym prawem fizyki, które odnosi się do zjawisk elektromagnetycznych, zwłaszcza do indukcji elektromagnetycznej. Została sformułowana przez niemieckiego fizyka Heinricha Lenza w 1834 roku i jest częścią szerszego prawa Faradaya dotyczącego indukcji elektromagnetycznej.

### Treść reguły Lenza

Reguła Lenza mówi, że:

**Indukowany prąd elektryczny w zamkniętym obwodzie ma taki kierunek, że przeciwdziała przyczynie, która go wywołała.**

### Znaczenie reguły Lenza

1. **Zachowanie energii:** Reguła Lenza jest zgodna z zasadą zachowania energii. Jeżeli prąd indukowany miałby wspierać przyczynę swojego powstawania, prowadziłoby to do powstawania coraz większej ilości energii bez dodatkowego wkładu energii z zewnątrz, co jest niemożliwe.

2. **Oporność wobec zmian:** Reguła Lenza tłumaczy, dlaczego systemy elektromagnetyczne naturalnie sprzeciwiają się nagłym zmianom pola magnetycznego. Indukowany prąd wytwarza pole magnetyczne, które przeciwdziała zmianie zewnętrznego pola magnetycznego.

3. **Zastosowanie praktyczne:** Reguła Lenza jest podstawą działania wielu urządzeń elektrycznych i elektronicznych, takich jak transformatory, silniki elektryczne, generatory, prądnice oraz urządzenia do hamowania elektromagnetycznego.

### Przykłady

1. **Generator prądu:** W generatorze, kiedy wirnik obraca się w polu magnetycznym, zmienia się strumień magnetyczny przez cewkę, co indukuje prąd. Kierunek tego prądu jest taki, że wytwarzane przez niego pole magnetyczne przeciwdziała ruchowi wirnika, czyli działa hamująco.

2. **Hamowanie elektromagnetyczne:** W hamulcach elektromagnetycznych, kiedy metalowy dysk obraca się w polu magnetycznym, indukuje się prąd, który wytwarza pole przeciwdziałające ruchowi dysku, co prowadzi do jego hamowania.

3. **Indukcyjność własna:** W cewkach, gdy prąd przepływający przez cewkę zmienia się, zmienia się również pole magnetyczne wytwarzane przez tę cewkę. To z kolei indukuje prąd, który przeciwdziała zmianie pierwotnego prądu.

### Matematyczna interpretacja

Reguła Lenza jest wyrażona matematycznie przez równanie Faradaya-Lenza:

$$\mathcal{E} = -\frac{d\Phi_B}{dt}$$

gdzie:

- $\mathcal{E}$ to siła elektromotoryczna (SEM) indukowana w obwodzie,
- $\Phi_B$ to strumień magnetyczny,
- znak minus oznacza, że indukowana SEM działa w kierunku przeciwnym do zmiany strumienia magnetycznego.

Reguła Lenza jest kluczowym elementem teorii elektromagnetyzmu i jest niezbędna do zrozumienia i projektowania wszelkich urządzeń, które działają na zasadzie indukcji elektromagnetycznej.

### 23. Wytwarzanie prądu elektrycznego

## Wytwarzanie prądu elektrycznego

Wytwarzanie prądu elektrycznego, czyli generacja energii elektrycznej, jest procesem przekształcania różnych form energii w energię elektryczną. Proces ten może być realizowany na różne sposoby, w zależności od wykorzystywanych źródeł energii i technologii. Oto kilka podstawowych metod wytwarzania prądu elektrycznego:

### 1. Elektrownie cieplne

Elektrownie cieplne wykorzystują ciepło do wytwarzania pary, która napędza turbiny połączone z generatorami elektrycznymi.

#### a. Elektrownie węglowe

Węgiel jest spalany, aby podgrzać wodę w kotle, tworząc parę, która napędza turbiny.

#### b. Elektrownie gazowe

Gaz ziemny jest spalany w turbinach gazowych, które napędzają generatory. Często wykorzystywane są także turbiny parowe w cyklu kombinowanym.

#### c. Elektrownie jądrowe

Ciepło generowane przez reakcje jądrowe (rozszczepienie atomów uranu lub plutonu) jest wykorzystywane do produkcji pary napędzającej turbiny.

### 2. Elektrownie wodne

W elektrowniach wodnych energia potencjalna spiętrzonej wody jest zamieniana na energię kinetyczną, a następnie na energię elektryczną.

#### a. Elektrownie zaporowe

Woda zgromadzona w zaporach przepływa przez turbiny, które generują prąd.

#### b. Elektrownie przepływowe

Woda przepływająca przez rzekę napędza turbiny.

### 3. Elektrownie wiatrowe

Turbiny wiatrowe wykorzystują energię kinetyczną wiatru do obracania łopat, które napędzają generatory elektryczne.

### 4. Elektrownie słoneczne

Elektrownie słoneczne zamieniają energię promieniowania słonecznego na energię elektryczną.

#### a. Fotowoltaika

Panele fotowoltaiczne przekształcają bezpośrednio światło słoneczne w prąd elektryczny za pomocą efektu fotowoltaicznego.

#### b. Systemy termiczne

Kolektory słoneczne skupiają promieniowanie słoneczne, aby podgrzać płyn, który następnie napędza turbiny.

### 5. Elektrownie geotermalne

Wykorzystują ciepło pochodzące z wnętrza Ziemi do wytwarzania pary, która napędza turbiny.

### 6. Elektrownie pływowe i falowe

Wykorzystują energię pływów morskich lub fal do napędzania turbin.

### Zasada działania generatorów elektrycznych

Bez względu na metodę wytwarzania prądu elektrycznego, kluczowym elementem jest generator. Generator działa na zasadzie indukcji elektromagnetycznej, odkrytej przez Michaela Faradaya. Gdy przewodnik (np. cewka) porusza się w polu magnetycznym lub pole magnetyczne wokół przewodnika zmienia się, indukowany jest prąd elektryczny.

### Kroki indukcji elektromagnetycznej:

1. Ruch przewodnika w polu magnetycznym lub zmiana pola magnetycznego.
2. Przewodnik przecina linie pola magnetycznego.
3. Powstaje siła elektromotoryczna (SEM), która generuje przepływ prądu w obwodzie zamkniętym.

### Podsumowanie

Wytwarzanie prądu elektrycznego jest kluczowe dla funkcjonowania współczesnej cywilizacji. Różne metody generacji prądu pozwalają na wykorzystanie różnych źródeł energii, od tradycyjnych paliw kopalnych po odnawialne źródła energii, takie jak wiatr czy słońce. Dążenie do zwiększenia efektywności i zrównoważonego rozwoju w energetyce prowadzi do ciągłego rozwoju nowych technologii i rozwiązań.

### 24. Indukcyjność i jego znaczenie

Indukcyjność to zdolność obwodu elektrycznego do wytwarzania siły elektromotorycznej (SEM) w wyniku zmian prądu przepływającego przez ten obwód. Jest to podstawowe pojęcie w elektrotechnice i fizyce, szczególnie w kontekście obwodów prądu zmiennego (AC) i urządzeń takich jak transformatory, cewki oraz silniki elektryczne. Jednostką indukcyjności jest henr (H), nazwany na cześć amerykańskiego fizyka Josepha Henry'ego.

### Znaczenie indukcyjności:

1. **Magazynowanie energii**: Cewki, które są elementami o dużej indukcyjności, mogą magazynować energię w postaci pola magnetycznego. Jest to kluczowe w wielu zastosowaniach, takich jak przetwornice DC-DC, w których energia jest magazynowana i przenoszona w postaci pola magnetycznego.

2. **Filtrowanie sygnałów**: Indukcyjność jest używana w filtrach do separowania sygnałów o różnych częstotliwościach. Na przykład, filtry dolnoprzepustowe mogą tłumić sygnały o wysokiej częstotliwości, pozwalając na przepływ sygnałów o niskiej częstotliwości.

3. **Transformatory**: Transformatory, które są podstawowymi komponentami w systemach dystrybucji energii elektrycznej, działają dzięki zasadzie indukcji elektromagnetycznej. Indukcyjność pierwotnego i wtórnego uzwojenia pozwala na przekazywanie energii elektrycznej między obwodami przy różnych napięciach.

4. **Obwody rezonansowe**: Indukcyjność jest kluczowym elementem obwodów rezonansowych, które są używane w różnych aplikacjach, od strojników radiowych po wzmacniacze. Rezonans występuje, gdy indukcyjność i pojemność w obwodzie są w takiej relacji, że energia oscyluje między polem elektrycznym a magnetycznym.

5. **Ograniczenie prądu**: Induktory mogą ograniczać prąd w obwodach, zwłaszcza w momencie włączenia zasilania, co jest przydatne w ochronie urządzeń elektronicznych przed przepięciami.

### Podstawowe równania:

1. **Prawa Faradaya**: SEM indukowana w cewce jest równa ujemnej zmianie strumienia magnetycznego przez cewkę:

   $$
   \mathcal{E} = -L \frac{dI}{dt}
   $$

   gdzie $\mathcal{E}$ to SEM, $L$ to indukcyjność, a $\frac{dI}{dt}$ to szybkość zmiany prądu.

2. **Energia zgromadzona w cewce**: Energia $E$ zgromadzona w indukcyjności $L$ przy prądzie $I$ wynosi:
   $$
   E = \frac{1}{2} L I^2
   $$

### Praktyczne zastosowania:

- **Silniki i generatory**: W silnikach elektrycznych i generatorach indukcyjność jest kluczowa dla działania, umożliwiając konwersję energii elektrycznej na mechaniczną i odwrotnie.
- **Zasilacze impulsowe**: W zasilaczach impulsowych indukcyjność pozwala na efektywne przekształcanie napięć.
- **Telekomunikacja**: Filtry indukcyjne są używane do selekcji częstotliwości w odbiornikach radiowych i telewizyjnych.

Rozumienie i wykorzystywanie indukcyjności jest niezbędne w projektowaniu i analizie obwodów elektrycznych i elektronicznych, mając szerokie zastosowanie w nowoczesnych technologiach.

### 25. Indukcyjność solenoidu

Indukcyjność solenoidu (cewki) to miara jego zdolności do magazynowania energii w polu magnetycznym, gdy przepływa przez niego prąd elektryczny. Indukcyjność $L$ solenoidu można wyznaczyć za pomocą poniższego wzoru:

$$L = \mu_0 \cdot \mu_r \cdot \frac{N^2 \cdot A}{l}$$

gdzie:

- $\mu_0$ to przenikalność magnetyczna próżni ($4\pi \times 10^{-7} \, \text{H/m}$),
- $\mu_r$ to względna przenikalność magnetyczna materiału w rdzeniu solenoidu (dla próżni lub powietrza wynosi 1),
- $N$ to liczba zwojów cewki,
- $A$ to pole przekroju poprzecznego cewki ($A = \pi r^2$ dla cewki o przekroju kołowym, gdzie $r$ to promień przekroju poprzecznego),
- $l$ to długość cewki.

Przykład:
Jeśli mamy solenoid o długości 10 cm, promieniu 2 cm, z 500 zwojami i rdzeniem powietrznym (czyli $\mu_r = 1$), to jego indukcyjność można obliczyć następująco:

1. Przekształcamy jednostki do układu SI:

   - długość: $l = 0.1 \, \text{m}$,
   - promień: $r = 0.02 \, \text{m}$.

2. Obliczamy pole przekroju poprzecznego:
   $$A = \pi r^2 = \pi (0.02)^2 \approx 1.25664 \times 10^{-3} \, \text{m}^2.$$

3. Podstawiamy dane do wzoru:
   $$L = 4\pi \times 10^{-7} \cdot 1 \cdot \frac{500^2 \cdot 1.25664 \times 10^{-3}}{0.1}.$$

4. Obliczamy wartość:
   $$L \approx 4\pi \times 10^{-7} \cdot 500^2 \cdot 1.25664 \times 10^{-3} / 0.1$$
   $$L \approx 4\pi \times 10^{-7} \cdot 250000 \cdot 1.25664 \times 10^{-3} / 0.1$$
   $$L \approx 4\pi \times 10^{-7} \cdot 314.16$$
   $$L \approx 4 \times 3.1416 \times 10^{-7} \cdot 314.16$$
   $$L \approx 3.948 \times 10^{-4} \, \text{H}$$
   $$L \approx 0.3948 \, \text{mH}.$$

Tak więc indukcyjność solenoidu wynosi około 0.3948 mH.

Jeżeli masz konkretne parametry swojego solenoidu, mogę obliczyć indukcyjność dla Twojego przypadku.

### 26. Układ drgający. Częstotliwość drgań

Układ drgający (oscylator) to system, który porusza się ruchem drgającym, czyli ruchem periodycznym wokół pewnego stanu równowagi. Częstotliwość drgań (oznaczana literą $f$) to liczba pełnych cykli drgań wykonanych przez układ w jednostce czasu. Częstotliwość jest zazwyczaj wyrażana w hercach (Hz), gdzie 1 Hz odpowiada jednemu cyklowi na sekundę.

Aby obliczyć częstotliwość drgań w różnych typach oscylatorów, stosuje się różne wzory, w zależności od rodzaju oscylatora. Poniżej przedstawione są wzory dla kilku popularnych układów drgających.

### Oscylator harmoniczny prosty (masa na sprężynie)

Dla oscylatora harmonicznego prostego, składającego się z masy $m$ i sprężyny o stałej sprężystości $k$:

$$f = \frac{1}{2\pi} \sqrt{\frac{k}{m}}$$

### Wahadło matematyczne

Dla wahadła matematycznego o długości $L$ i przyspieszeniu grawitacyjnym $g$:

$$f = \frac{1}{2\pi} \sqrt{\frac{g}{L}}$$

### Wahadło fizyczne

Dla wahadła fizycznego, które jest ciałem sztywnym obracającym się wokół osi nieprzechodzącej przez jego środek masy:

$$f = \frac{1}{2\pi} \sqrt{\frac{mgd}{I}}$$

gdzie:

- $m$ to masa ciała,
- $g$ to przyspieszenie grawitacyjne,
- $d$ to odległość od osi obrotu do środka masy,
- $I$ to moment bezwładności ciała względem osi obrotu.

### Drgania elektromagnetyczne (obwód LC)

Dla obwodu LC składającego się z cewki o indukcyjności $L$ i kondensatora o pojemności $C$:

$$f = \frac{1}{2\pi} \sqrt{\frac{1}{LC}}$$

Wszystkie te wzory zakładają, że układ jest idealny (brak tłumienia, strat energii, itp.). W rzeczywistych układach mogą występować dodatkowe czynniki, które wpływają na częstotliwość drgań.

Jeśli masz konkretny typ układu drgającego, którym jesteś zainteresowany, podaj więcej szczegółów, a postaram się pomóc w bardziej szczegółowy sposób.

### 27. Rola pojemności i samoindukcji w obwodach prądu zmiennego

### Pojemność w obwodach prądu zmiennego

Pojemność w obwodach prądu zmiennego jest związana z obecnością kondensatorów. Kondensator składa się z dwóch przewodników oddzielonych dielektrykiem i ma zdolność do gromadzenia ładunku elektrycznego. W obwodach AC, kondensator działa w sposób następujący:

1. **Reaktancja pojemnościowa (X_C)**:
   Reaktancja pojemnościowa jest oporem stawianym przepływowi prądu zmiennego przez kondensator. Jest odwrotnie proporcjonalna do częstotliwości sygnału i pojemności kondensatora:

   $$
   X_C = \frac{1}{\omega C} = \frac{1}{2\pi f C}
   $$

   gdzie $\omega$ to pulsacja (częstotliwość kątowa), $f$ to częstotliwość, a $C$ to pojemność.

2. **Przesunięcie fazowe**:
   W obwodzie zawierającym tylko kondensator, prąd wyprzedza napięcie o kąt 90 stopni. Oznacza to, że maksymalna wartość prądu jest osiągana wcześniej niż maksymalna wartość napięcia.

3. **Zachowanie w obwodach RC**:
   W obwodach RC (rezystor-kondensator), pojemność wpływa na charakterystyki czasowe obwodu, takie jak stała czasowa $\tau = RC$, która określa, jak szybko napięcie na kondensatorze rośnie lub maleje.

### Samoindukcja w obwodach prądu zmiennego

Samoindukcja związana jest z obecnością cewek indukcyjnych w obwodzie. Cewka indukcyjna przeciwdziała zmianom prądu dzięki swojej indukcyjności, co prowadzi do wystąpienia napięcia samoindukcji.

1. **Reaktancja indukcyjna (X_L)**:
   Reaktancja indukcyjna to opór stawiany przepływowi prądu zmiennego przez cewkę. Jest proporcjonalna do częstotliwości sygnału i indukcyjności cewki:

   $$
   X_L = \omega L = 2\pi f L
   $$

   gdzie $L$ to indukcyjność.

2. **Przesunięcie fazowe**:
   W obwodzie zawierającym tylko cewkę, napięcie wyprzedza prąd o kąt 90 stopni. Oznacza to, że maksymalna wartość napięcia jest osiągana wcześniej niż maksymalna wartość prądu.

3. **Zachowanie w obwodach RL**:
   W obwodach RL (rezystor-cewka), indukcyjność wpływa na charakterystyki czasowe obwodu, takie jak stała czasowa $\tau = \frac{L}{R}$, która określa, jak szybko prąd w obwodzie narasta lub maleje.

### Rola w rezonansie

W obwodach RLC (rezystor-cewka-kondensator) pojemność i samoindukcja współdziałają, co może prowadzić do zjawiska rezonansu. Rezonans w obwodach RLC występuje, gdy reaktancja indukcyjna i pojemnościowa są równe co do wartości, ale przeciwnie skierowane. Częstotliwość rezonansowa $f_0$ jest dana wzorem:

$$
f_0 = \frac{1}{2\pi\sqrt{LC}}
$$

W rezonansie, impedancja obwodu jest minimalna i równa rezystancji, co prowadzi do maksymalizacji prądu w obwodzie.

### 28. Wartości skuteczne prądu zmiennego. Moc w obwodach prądu zmiennego

### Wartości skuteczne prądu zmiennego

Wartość skuteczna prądu zmiennego (ang. RMS - Root Mean Square) jest szczególnym rodzajem średniej, która pozwala na określenie "ekwiwalentnej" wartości prądu stałego, która dostarczałaby tę samą ilość energii co dany prąd zmienny.

Wartość skuteczna prądu zmiennego $I_{sk}$ jest definiowana jako pierwiastek z wartości średniej kwadratu prądu zmiennego:

$$I_{sk} = \sqrt{\frac{1}{T} \int_0^T i(t)^2 \, dt} $$

Podobnie dla napięcia zmiennego:

$$U_{sk} = \sqrt{\frac{1}{T} \int_0^T u(t)^2 \, dt} $$

Dla prądu sinusoidalnego o amplitudzie $I_{m}$ wartość skuteczna wynosi:

$$I_{sk} = \frac{I_{m}}{\sqrt{2}} $$

Podobnie dla napięcia sinusoidalnego o amplitudzie $U_{m}$:

$$U_{sk} = \frac{U_{m}}{\sqrt{2}} $$

### Moc w obwodach prądu zmiennego

Moc w obwodach prądu zmiennego jest bardziej złożonym zagadnieniem niż w przypadku prądu stałego. Wyróżniamy trzy podstawowe rodzaje mocy:

1. **Moc czynna (P)** - jest to moc, która jest zamieniana na pracę użyteczną, taką jak ciepło, światło czy mechaniczna praca silnika. Moc czynna jest wyrażana w watach (W):

$$P = U_{sk} I_{sk} \cos \phi $$

gdzie:

- $U_{sk}$ - wartość skuteczna napięcia
- $I_{sk}$ - wartość skuteczna prądu
- $\cos \phi$ - współczynnik mocy, który jest kosinusem kąta fazowego między napięciem a prądem.

2. **Moc bierna (Q)** - jest to moc, która jest wymieniana między źródłem a obciążeniem, ale nie jest zamieniana na pracę użyteczną. Moc bierna jest wyrażana w warach (var):

$$Q = U_{sk} I_{sk} \sin \phi $$

3. **Moc pozorna (S)** - jest to całkowita moc dostarczana do obwodu, łącząca zarówno moc czynną, jak i bierną. Moc pozorna jest wyrażana w woltoamperach (VA):

$$S = U_{sk} I_{sk} $$

Związek między mocą czynną, bierną i pozorną jest przedstawiany za pomocą trójkąta mocy:

$$S = \sqrt{P^2 + Q^2} $$

### Podsumowanie

Wartość skuteczna prądu i napięcia pozwala na proste porównanie prądu zmiennego do prądu stałego pod kątem zdolności do wykonywania pracy. Natomiast analiza mocy w obwodach prądu zmiennego wymaga uwzględnienia zarówno mocy czynnej, biernej, jak i pozornej, co pozwala na pełniejsze zrozumienie działania obwodu i zarządzanie energią w systemie.

### 29. Magnetyczne własności materii diam para i ferro magnetyzm

## Magnetyczne własności materii: diamagnetyzm, paramagnetyzm i ferromagnetyzm

Magnetyczne własności materii można podzielić na trzy główne kategorie: diamagnetyzm, paramagnetyzm i ferromagnetyzm. Każdy z tych stanów charakteryzuje się różnymi reakcjami na zewnętrzne pole magnetyczne oraz wewnętrzną strukturą atomową i elektronową. Oto krótki opis każdej z tych kategorii:

### Diamagnetyzm

**Charakterystyka:**

- Wszystkie materiały wykazują pewien poziom diamagnetyzmu.
- Jest to najsłabsza forma magnetyzmu.
- W obecności zewnętrznego pola magnetycznego, materiały diamagnetyczne tworzą indukowane pole magnetyczne, które przeciwdziała zewnętrznemu polu.
- Moment magnetyczny atomów lub cząsteczek w materiałach diamagnetycznych wynosi zero w nieobecności zewnętrznego pola magnetycznego.

**Przykłady materiałów:**

- Bizmut (Bi)
- Miedź (Cu)
- Złoto (Au)

**Przykład zjawiska:**

- Lewitacja diamagnetyczna, jak w przypadku lewitujących żab w silnym polu magnetycznym.

### Paramagnetyzm

**Charakterystyka:**

- Materiały paramagnetyczne mają niezerowy moment magnetyczny wynikający z niesparowanych elektronów.
- Pod wpływem zewnętrznego pola magnetycznego, momenty magnetyczne wyrównują się w kierunku pola, co powoduje przyciąganie do pola.
- Efekt jest silniejszy niż w przypadku diamagnetyzmu, ale nadal relatywnie słaby.

**Przykłady materiałów:**

- Glin (Al)
- Platyna (Pt)
- Tlen (O₂) w postaci gazowej

**Przykład zjawiska:**

- Przyciąganie paramagnetycznych soli manganu do magnesu.

### Ferromagnetyzm

**Charakterystyka:**

- Materiały ferromagnetyczne mają stałe momenty magnetyczne wynikające z niesparowanych elektronów, które spontanicznie wyrównują się w obszarach zwanych domenami magnetycznymi.
- Te materiały mogą być silnie namagnesowane i utrzymywać magnetyzm nawet po usunięciu zewnętrznego pola magnetycznego.
- Istnieje temperatura zwana temperaturą Curie, powyżej której materiał traci swoje właściwości ferromagnetyczne.

**Przykłady materiałów:**

- Żelazo (Fe)
- Nikiel (Ni)
- Kobalt (Co)

**Przykład zjawiska:**

- Stałe magnesy używane w wielu zastosowaniach, od kompasów po silniki elektryczne.

### Podsumowanie

- **Diamagnetyzm**: Występuje w wszystkich materiałach, najsłabszy efekt, przeciwdziała zewnętrznemu polu magnetycznemu.
- **Paramagnetyzm**: Występuje w materiałach z niesparowanymi elektronami, przyciąga się do zewnętrznego pola magnetycznego.
- **Ferromagnetyzm**: Najsilniejszy efekt, występuje w materiałach z dużą liczbą niesparowanych elektronów, które mogą się samoistnie wyrównać, tworząc silne pole magnetyczne.

Zrozumienie tych właściwości jest kluczowe dla wielu zastosowań w technologii i nauce, od tworzenia nowych materiałów magnetycznych po ich zastosowanie w elektronice, medycynie i przemyśle.

### 30. Prawa Maxwella. Prawo Gaussa dla pola magnetycznego. Prąd przesunięcia

### Prawo Gaussa dla pola magnetycznego

Prawo Gaussa dla pola magnetycznego mówi, że całkowity strumień pola magnetycznego przez dowolną zamkniętą powierzchnię jest równy zero. Matematycznie, prawo to można zapisać jako:

$$\oint_{\partial V} \mathbf{B} \cdot d\mathbf{A} = 0$$

gdzie:

- $\mathbf{B}$ to wektor indukcji magnetycznej (pole magnetyczne),
- $d\mathbf{A}$ to wektor powierzchniowy (wektor normalny do powierzchni $dA$),
- $\partial V$ to powierzchnia zamknięta.

Fizycznie oznacza to, że nie istnieją "magnetyczne ładunki", czyli monopole magnetyczne, a linie pola magnetycznego zawsze tworzą zamknięte pętle.

### Prąd przesunięcia

Prąd przesunięcia został wprowadzony przez Jamesa Clerka Maxwella, aby rozszerzyć prawo Ampere'a i zachować ciągłość prądu elektrycznego w sytuacjach, gdzie nie ma rzeczywistego prądu przewodzenia, na przykład w przypadku zmieniającego się pola elektrycznego między okładkami kondensatora.

Matematycznie prąd przesunięcia jest wyrażony jako:

$$\mathbf{J}_D = \epsilon_0 \frac{\partial \mathbf{E}}{\partial t}$$

gdzie:

- $\mathbf{J}_D$ to wektor gęstości prądu przesunięcia,
- $\epsilon_0$ to przenikalność elektryczna próżni,
- $\mathbf{E}$ to wektor natężenia pola elektrycznego.

Wprowadzenie prądu przesunięcia prowadzi do zmodyfikowanego prawa Ampere'a (zwanego prawem Ampere'a-Maxwella):

$$\oint_{\partial S} \mathbf{B} \cdot d\mathbf{l} = \mu_0 \left( \int_{S} \mathbf{J} \cdot d\mathbf{A} + \epsilon_0 \frac{d}{dt} \int_{S} \mathbf{E} \cdot d\mathbf{A} \right)$$

gdzie:

- $\mu_0$ to przenikalność magnetyczna próżni,
- $d\mathbf{l}$ to wektor długości elementu konturu $\partial S$,
- $S$ to powierzchnia rozpięta na konturze $\partial S$,
- $\mathbf{J}$ to gęstość prądu przewodzenia.

Prąd przesunięcia jest zatem niezbędny do opisania zmiennego pola elektrycznego, które wywołuje zmienne pole magnetyczne, co jest podstawą fal elektromagnetycznych.

### Podsumowanie

- **Prawo Gaussa dla pola magnetycznego**: Całkowity strumień pola magnetycznego przez dowolną zamkniętą powierzchnię jest równy zero, co oznacza brak monopoli magnetycznych.
- **Prąd przesunięcia**: Wprowadzony przez Maxwella dla zachowania ciągłości prądu w zmieniających się polach elektrycznych, szczególnie w miejscach, gdzie nie ma fizycznego przepływu prądu przewodzenia, jak w przypadku kondensatora.

Te koncepcje są kluczowe dla zrozumienia zachowania pól elektromagnetycznych i są fundamentem współczesnej fizyki i technologii elektromagnetycznych.

### 31. Wytwarzanie fal elektromagnetycznych. Rola prędkości światła

## Wytwarzanie fal elektromagnetycznych. Rola prędkości światła

Fale elektromagnetyczne są wytwarzane w wyniku oscylacji ładunków elektrycznych, które tworzą zmienne pole elektryczne i magnetyczne. Te oscylujące pola elektryczne i magnetyczne rozchodzą się w przestrzeni jako fala elektromagnetyczna.

### Proces wytwarzania fal elektromagnetycznych

Fale elektromagnetyczne mogą być generowane na kilka sposobów, z których najczęstsze to:

1. **Oscylatory elektroniczne**: W układach elektronicznych oscylatory wytwarzają zmienne sygnały elektryczne o określonych częstotliwościach, które są następnie przekształcane w fale elektromagnetyczne.
2. **Antena nadawcza**: Prąd przemienny (AC) płynący przez antenę wytwarza zmienne pole elektryczne i magnetyczne. Gdy prąd zmienia kierunek, pola te również zmieniają kierunek, co prowadzi do propagacji fal elektromagnetycznych.

3. **Zjawiska kwantowe**: Emisja promieniowania elektromagnetycznego może zachodzić również na poziomie atomowym, np. w wyniku przejść elektronów między różnymi stanami energetycznymi.

### Rola prędkości światła

Prędkość światła ($c$) odgrywa kluczową rolę w zrozumieniu fal elektromagnetycznych. Jest to fundamentalna stała fizyczna o wartości około $3 \times 10^8$ metrów na sekundę (m/s) w próżni. Prędkość światła ma kilka istotnych ról w kontekście fal elektromagnetycznych:

1. **Propagacja fal**: Fale elektromagnetyczne poruszają się w próżni z prędkością światła. W innych ośrodkach (np. w wodzie, szkle) prędkość ta jest mniejsza i zależy od współczynnika załamania danego materiału.

2. **Zależność częstotliwości i długości fali**: Prędkość światła jest związana z częstotliwością ($f$) i długością fali ($\lambda$) fal elektromagnetycznych za pomocą równania:

   $$
   c = f \cdot \lambda
   $$

   Oznacza to, że dla danej częstotliwości, długość fali jest odwrotnie proporcjonalna do prędkości światła i vice versa.

3. **Einsteinowska teoria względności**: Prędkość światła jest kluczowa w teorii względności Einsteina, która wpływa na nasze zrozumienie czasu, przestrzeni i energii. Energia fotonu (kwantu światła) jest związana z jego częstotliwością za pomocą równania Plancka:
   $$
   E = h \cdot f
   $$
   gdzie $E$ to energia, $h$ to stała Plancka, a $f$ to częstotliwość.

### Przykład: Antena nadawcza

Rozważmy antenę nadawczą, przez którą płynie prąd przemienny. Gdy prąd oscyluje, wytwarza zmienne pole elektryczne i magnetyczne. Te oscylujące pola tworzą falę elektromagnetyczną, która rozchodzi się w przestrzeni. Prędkość, z jaką ta fala się rozprzestrzenia, jest prędkością światła.

Dzięki równaniu $c = f \cdot \lambda$, możemy obliczyć długość fali emitowanej przez antenę, znając częstotliwość oscylacji prądu. Na przykład, dla fali o częstotliwości 1 MHz (megaherc, $1 \times 10^6$ Hz), długość fali w próżni wynosi:

$$
\lambda = \frac{c}{f} = \frac{3 \times 10^8 \, \text{m/s}}{1 \times 10^6 \, \text{Hz}} = 300 \, \text{m}
$$

Podsumowując, prędkość światła jest kluczowa dla zrozumienia właściwości fal elektromagnetycznych, ich propagacji oraz zależności między częstotliwością a długością fali.

### 32. Promieniowanie termiczne. Przyczyny promieniowania ciał nagrzanych

### Promieniowanie termiczne. Przyczyny promieniowania ciał nagrzanych

Promieniowanie termiczne to proces emisji energii w postaci fal elektromagnetycznych przez ciała nagrzane. Zjawisko to wynika z ruchów cząsteczek i atomów w materii, które stają się bardziej intensywne w miarę wzrostu temperatury. Główne przyczyny promieniowania ciał nagrzanych można wyjaśnić w kontekście fizyki klasycznej i mechaniki kwantowej.

### 1. Ruchy cząsteczek i atomów

Każde ciało składa się z cząsteczek i atomów, które są w ciągłym ruchu. Wzrost temperatury oznacza wzrost energii kinetycznej tych cząsteczek i atomów. Gdy cząsteczki te zderzają się ze sobą, mogą emitować energię w postaci fal elektromagnetycznych.

### 2. Zasada promieniowania cieplnego

Promieniowanie termiczne jest bezpośrednio związane z temperaturą ciała. Im wyższa temperatura, tym więcej energii jest emitowane. Każde ciało o temperaturze wyższej od zera bezwzględnego (0 K) emituje promieniowanie termiczne.

### 3. Prawo Plancka

W mechanice kwantowej promieniowanie ciał nagrzanych opisuje prawo promieniowania Plancka, które mówi, że intensywność promieniowania emitowanego przez ciało doskonale czarne (idealny emitent promieniowania) jest funkcją długości fali i temperatury. Prawo to wyraża się wzorem:
$$B(\lambda, T) = \frac{2hc^2}{\lambda^5} \frac{1}{e^{\frac{hc}{\lambda k_B T}} - 1}$$
gdzie:

- $B(\lambda, T)$ – spektaklowa emisyjność ciała doskonale czarnego,
- $h$ – stała Plancka,
- $c$ – prędkość światła w próżni,
- $\lambda$ – długość fali,
- $k_B$ – stała Boltzmanna,
- $T$ – temperatura bezwzględna.

### 4. Prawo Wiena

Prawo Wiena opisuje przesunięcie maksimum intensywności promieniowania w kierunku krótszych fal wraz ze wzrostem temperatury:
$$\lambda_{\text{max}} T = b$$
gdzie:

- $\lambda_{\text{max}}$ – długość fali, przy której intensywność promieniowania jest największa,
- $T$ – temperatura,
- $b$ – stała Wiena (około 2.898 \times 10^{-3} m·K).

### 5. Prawo Stefana-Boltzmanna

Prawo Stefana-Boltzmanna określa całkowitą energię emitowaną przez ciało doskonale czarne na jednostkę powierzchni w jednostce czasu:
$$P = \sigma T^4$$
gdzie:

- $P$ – moc promieniowania na jednostkę powierzchni,
- $\sigma$ – stała Stefana-Boltzmanna,
- $T$ – temperatura bezwzględna.

### 6. Mechanika kwantowa

W kontekście mechaniki kwantowej, promieniowanie termiczne można zrozumieć jako wynik emisji i absorpcji kwantów energii, czyli fotonów. Im wyższa temperatura, tym większa jest średnia energia fotonów emitowanych przez ciało.

### Podsumowanie

Promieniowanie termiczne ciał nagrzanych wynika z ich wewnętrznej energii termicznej, która jest funkcją temperatury. Wzrost temperatury prowadzi do wzrostu energii kinetycznej cząsteczek, co z kolei powoduje emisję promieniowania elektromagnetycznego. Prawo Plancka, prawo Wiena i prawo Stefana-Boltzmanna pozwalają na dokładne opisanie ilościowe i jakościowe tego zjawiska.

### 33. Prawo Stefna-Boltzmana i prawo Wiena

Prawo Stefana-Boltzmana i prawo Wiena są podstawowymi prawami w fizyce opisującymi promieniowanie cieplne ciał doskonale czarnych. Oto omówienie każdego z nich:

### Prawo Stefana-Boltzmana

Prawo Stefana-Boltzmana mówi, że całkowita energia promieniowania emitowana przez jednostkę powierzchni ciała doskonale czarnego jest proporcjonalna do czwartej potęgi jego temperatury absolutnej (w kelwinach). Matematycznie można to wyrazić wzorem:

$$P = \sigma T^4$$

gdzie:

- $P$ - moc promieniowania na jednostkę powierzchni (W/m²),
- $\sigma$ - stała Stefana-Boltzmana, wynosząca $\sigma \approx 5.670 \times 10^{-8} \, \text{W} \cdot \text{m}^{-2} \cdot \text{K}^{-4}$,
- $T$ - temperatura ciała doskonale czarnego w kelwinach (K).

### Prawo Wiena

Prawo Wiena opisuje zależność między temperaturą ciała doskonale czarnego a długością fali, przy której emituje ono najwięcej promieniowania. Wyraża się wzorem:

$$\lambda_{\text{max}} = \frac{b}{T}$$

gdzie:

- $\lambda_{\text{max}}$ - długość fali odpowiadająca maksymalnej emisji (m),
- $b$ - stała Wiena, wynosząca $b \approx 2.898 \times 10^{-3} \, \text{m} \cdot \text{K}$,
- $T$ - temperatura ciała doskonale czarnego w kelwinach (K).

### Przykład zastosowania

Załóżmy, że mamy ciało doskonale czarne o temperaturze 3000 K. Możemy obliczyć moc promieniowania na jednostkę powierzchni oraz długość fali maksymalnej emisji.

1. Moc promieniowania (prawo Stefana-Boltzmana):
   $$P = \sigma T^4 = 5.670 \times 10^{-8} \times (3000)^4 \, \text{W/m}^2$$

2. Długość fali maksymalnej emisji (prawo Wiena):
   $$\lambda_{\text{max}} = \frac{2.898 \times 10^{-3}}{3000} \, \text{m}$$

Policzmy te wartości.

#### Obliczenia:

1. Moc promieniowania:
   $$P = 5.670 \times 10^{-8} \times (3000)^4 \, \text{W/m}^2$$
   $$P \approx 459 \, \text{kW/m}^2$$

2. Długość fali maksymalnej emisji:
   $$\lambda_{\text{max}} = \frac{2.898 \times 10^{-3}}{3000} \, \text{m}$$
   $$\lambda_{\text{max}} \approx 966 \, \text{nm}$$

Tak więc, przy temperaturze 3000 K, ciało doskonale czarne emituje promieniowanie o mocy około 459 kW/m², a długość fali, przy której emisja jest największa, wynosi około 966 nm, co znajduje się w podczerwieni.

### 34. Statystyczna obróbka pomiarów. Przyczyny poglądu o średniej arytmetycznej (metoda najmniejszych kwadratów). Sens innych rodzajów średniej

## Statystyczna obróbka pomiarów. Przyczyny poglądu o średniej arytmetycznej (metoda najmniejszych kwadratów). Sens innych rodzajów średniej

Statystyczna obróbka pomiarów to proces analizy danych zebranych podczas eksperymentów lub badań w celu uzyskania bardziej dokładnych i wiarygodnych wyników. W ramach tego procesu często korzysta się z różnych rodzajów średnich do opisu zbiorów danych. Omówmy więc kilka kluczowych pojęć związanych z tym tematem.

### Średnia arytmetyczna

Średnia arytmetyczna to najprostsza i najczęściej stosowana forma średniej. Jest to suma wszystkich wartości w zbiorze podzielona przez liczbę tych wartości. Wyrażona wzorem:

$$\bar{x} = \frac{1}{n} \sum_{i=1}^{n} x_i$$

gdzie $x_i$ to kolejne wartości w zbiorze danych, a $n$ to liczba tych wartości.

#### Przyczyny popularności średniej arytmetycznej:

1. **Intuicyjność**: Średnia arytmetyczna jest łatwa do zrozumienia i obliczenia.
2. **Własności matematyczne**: Średnia arytmetyczna jest punktem równowagi, wokół którego sumy odchyleń są równe zero.
3. **Metoda najmniejszych kwadratów**: W statystyce i analizie regresji średnia arytmetyczna minimalizuje sumę kwadratów odchyleń (różnic) pomiędzy wartościami rzeczywistymi a średnią. To oznacza, że średnia arytmetyczna jest najlepszym oszacowaniem wartości centralnej w sensie metody najmniejszych kwadratów.

### Metoda najmniejszych kwadratów

Metoda najmniejszych kwadratów (MNK) jest techniką optymalizacyjną stosowaną do dopasowywania modelu matematycznego do zbioru danych. Celem tej metody jest minimalizacja sumy kwadratów różnic (odchyleń) między wartościami obserwowanymi a wartościami przewidywanymi przez model. Formalnie, dla zbioru danych $(x_i, y_i)$ i modelu $y = f(x)$, metoda najmniejszych kwadratów minimalizuje funkcję:

$$S = \sum_{i=1}^{n} (y_i - f(x_i))^2$$

Jeśli model jest liniowy (np. prosta regresji $y = ax + b$), metoda najmniejszych kwadratów prowadzi do wzorów na współczynniki $a$ i $b$, które minimalizują sumę kwadratów odchyleń.

### Inne rodzaje średnich i ich sens

1. **Średnia geometryczna**: Jest to pierwiastek n-tego stopnia z iloczynu wszystkich wartości w zbiorze. Jest bardziej odpowiednia dla danych, które są iloczynami lub mają charakter względny (np. stopy wzrostu). Wyrażona wzorem:

$$\bar{x}_g = \left( \prod_{i=1}^{n} x_i \right)^{\frac{1}{n}}$$

2. **Średnia harmoniczna**: Jest odwrotnością średniej arytmetycznej odwrotności wartości. Stosuje się ją w przypadkach, gdy dane są miarami prędkości lub innych wielkości odwrotnych. Wyrażona wzorem:

$$\bar{x}_h = \frac{n}{\sum_{i=1}^{n} \frac{1}{x_i}}$$

3. **Średnia kwadratowa**: Jest to pierwiastek z średniej arytmetycznej kwadratów wartości. Jest używana w kontekście analizy sygnałów, błędów pomiarowych i zmienności. Wyrażona wzorem:

$$\bar{x}_q = \sqrt{\frac{1}{n} \sum_{i=1}^{n} x_i^2}$$

Każdy z tych rodzajów średnich ma swoje specyficzne zastosowania i sens w zależności od charakterystyki danych i kontekstu analizy. Średnia arytmetyczna jest najbardziej uniwersalna, ale w specyficznych przypadkach inne średnie mogą lepiej oddać centralną tendencję zbioru danych.

### 35. Odchylenie standardowe. Sens odchylenia standardowego i jego związek z rozkładem Gaussa

## Odchylenie standardowe. Sens odchylenia standardowego i jego związek z rozkładem Gaussa

Odchylenie standardowe jest miarą rozproszenia danych wokół średniej arytmetycznej w zestawie danych. Wskazuje, jak bardzo dane wartości różnią się od średniej wartości. Jest to jedna z najważniejszych miar statystycznych, używana do opisu zmienności danych.

### Definicja i Obliczanie Odchylenia Standardowego

Aby obliczyć odchylenie standardowe dla zbioru danych, należy wykonać następujące kroki:

1. **Oblicz średnią (μ):**

   $$
   \mu = \frac{1}{N} \sum_{i=1}^{N} x_i
   $$

   gdzie $x_i$ to poszczególne wartości danych, a $N$ to liczba obserwacji.

2. **Oblicz wariancję (σ²):**
   $$
   \sigma^2 = \frac{1}{N} \sum_{i=1}^{N} (x_i - \mu)^2
   $$
3. **Oblicz odchylenie standardowe (σ):**
   $$
   \sigma = \sqrt{\sigma^2}
   $$

W praktyce często używa się odchylenia standardowego próbki, a nie całej populacji. Wtedy wariancję oblicza się jako:

$$
s^2 = \frac{1}{n-1} \sum_{i=1}^{n} (x_i - \bar{x})^2
$$

gdzie $\bar{x}$ to średnia próbki, a $n$ to liczba obserwacji w próbce.

### Sens Odchylenia Standardowego

Odchylenie standardowe informuje nas o tym, jak bardzo dane wartości są rozproszone wokół średniej.

- **Niskie odchylenie standardowe:** Wartości są blisko średniej, co oznacza, że dane są mniej rozproszone.
- **Wysokie odchylenie standardowe:** Wartości są bardziej rozproszone wokół średniej, co oznacza większą zmienność danych.

### Związek z Rozkładem Gaussa (Rozkładem Normalnym)

Rozkład Gaussa, inaczej nazywany rozkładem normalnym, jest jednym z najważniejszych rozkładów prawdopodobieństwa w statystyce. Wiele zmiennych losowych w przyrodzie i naukach społecznych ma rozkład normalny.

Charakterystyki rozkładu normalnego:

- **Średnia (μ):** Centralna wartość rozkładu.
- **Odchylenie standardowe (σ):** Określa szerokość rozkładu.

W rozkładzie normalnym:

1. **Około 68%** danych leży w przedziale od $\mu - \sigma$ do $\mu + \sigma$.
2. **Około 95%** danych leży w przedziale od $\mu - 2\sigma$ do $\mu + 2\sigma$.
3. **Około 99.7%** danych leży w przedziale od $\mu - 3\sigma$ do $\mu + 3\sigma$.

Odchylenie standardowe w kontekście rozkładu normalnego jest kluczowym parametrem, który określa rozkład wartości wokół średniej. Ma to szerokie zastosowanie w różnych dziedzinach, od analizy wyników testów po modelowanie ryzyka w finansach.

### Podsumowanie

Odchylenie standardowe jest kluczową miarą zmienności, a jego związek z rozkładem normalnym pomaga zrozumieć, jak dane są rozproszone wokół średniej. W praktyce, znajomość odchylenia standardowego umożliwia lepsze zrozumienie struktury danych oraz pozwala na efektywniejsze podejmowanie decyzji na podstawie tych danych.

### 36. Obliczanie błędu pomiaru przey pomocy rózniczki zupełnej

Różniczka zupełna jest używana do oszacowania błędu pomiaru w funkcji wielu zmiennych. Gdy mamy funkcję $f(x_1, x_2, \ldots, x_n)$, której argumenty $x_1, x_2, \ldots, x_n$ mają błędy $\Delta x_1, \Delta x_2, \ldots, \Delta x_n$, możemy oszacować błąd funkcji $\Delta f$ za pomocą różniczki zupełnej. Różniczka zupełna funkcji $f$ wyrażona jest wzorem:

$$\Delta f \approx \sum_{i=1}^n \left| \frac{\partial f}{\partial x_i} \right| \Delta x_i$$

Przykład:

Załóżmy, że mamy funkcję $f(x, y) = x^2 + y^2$ i chcemy oszacować błąd $\Delta f$ przy błędach pomiaru $\Delta x$ i $\Delta y$.

1. Obliczmy pochodne cząstkowe funkcji $f$:

$$\frac{\partial f}{\partial x} = 2x$$
$$\frac{\partial f}{\partial y} = 2y$$

2. Zastosujmy wzór na różniczkę zupełną:

$$\Delta f \approx \left| \frac{\partial f}{\partial x} \right| \Delta x + \left| \frac{\partial f}{\partial y} \right| \Delta y$$
$$\Delta f \approx |2x| \Delta x + |2y| \Delta y$$

Przykład liczbowy:

Załóżmy, że $x = 3$, $y = 4$, $\Delta x = 0.1$ oraz $\Delta y = 0.2$.

$$\Delta f \approx |2 \cdot 3| \cdot 0.1 + |2 \cdot 4| \cdot 0.2$$
$$\Delta f \approx 6 \cdot 0.1 + 8 \cdot 0.2$$
$$\Delta f \approx 0.6 + 1.6$$
$$\Delta f \approx 2.2$$

Błąd pomiaru funkcji $f$ wynosi więc około 2.2.

Jeśli potrzebujesz dokładniejszych obliczeń lub dodatkowych przykładów, chętnie pomogę!

### 37. Sens błędów przypadkowych i błędów grubych. Błąd systematyczny i jego znaczenie

### Sens błędów przypadkowych i błędów grubych. Błąd systematyczny i jego znaczenie

Błędy pomiarowe są nieodłącznym elementem każdej procedury pomiarowej. Można je podzielić na trzy główne kategorie: błędy przypadkowe, błędy grube oraz błędy systematyczne. Każdy z tych typów błędów ma inne źródła i skutki, co ma kluczowe znaczenie dla analizy wyników pomiarów i poprawności przeprowadzanych eksperymentów.

### Błędy przypadkowe

Błędy przypadkowe (random errors) są wynikiem nieprzewidywalnych i losowych fluktuacji, które mogą wpływać na wyniki pomiarów. Mogą one wynikać z:

- Wibracji urządzeń pomiarowych.
- Zmian warunków otoczenia (np. temperatury, ciśnienia).
- Ograniczeń percepcji i reakcji ludzkich (np. błąd odczytu skali).

**Znaczenie błędów przypadkowych**:

- Błędy te powodują rozrzut wyników pomiarów wokół prawdziwej wartości.
- Są one zwykle opisywane za pomocą statystyk (np. odchylenia standardowego).
- Mogą być zredukowane poprzez zwiększenie liczby pomiarów i stosowanie metod statystycznych do uśredniania wyników.

### Błędy grube

Błędy grube (gross errors) są wynikiem rażących błędów ludzkich lub awarii sprzętu pomiarowego. Przykłady błędów grubych obejmują:

- Złe odczytanie wartości z urządzenia pomiarowego.
- Złe zapisanie wyniku.
- Użycie uszkodzonego sprzętu.

**Znaczenie błędów grubych**:

- Prowadzą do skrajnie błędnych wyników, które zazwyczaj znacznie odbiegają od prawdziwej wartości.
- Zwykle są łatwe do wykrycia poprzez sprawdzenie danych i powtórzenie pomiarów.
- Powinny być eliminowane na etapie analizy danych.

### Błędy systematyczne

Błędy systematyczne (systematic errors) są spowodowane przez nieprawidłowości w systemie pomiarowym, które konsekwentnie wpływają na wyniki pomiarów w określony sposób. Przykłady błędów systematycznych obejmują:

- Niewłaściwe skalowanie urządzeń pomiarowych.
- Błędy wynikające z nieodpowiednich warunków kalibracji.
- Stałe wpływy środowiskowe, które nie są brane pod uwagę (np. zawsze obecna temperatura otoczenia).

**Znaczenie błędów systematycznych**:

- Powodują przesunięcie wszystkich wyników pomiarów w określonym kierunku.
- Mogą prowadzić do konsekwentnie błędnych wyników, nawet przy dużej liczbie powtórzeń pomiaru.
- Ich identyfikacja i eliminacja jest kluczowa dla poprawności wyników pomiarów.
- Mogą być skorygowane poprzez kalibrację sprzętu lub uwzględnienie znanych źródeł błędów w analizie danych.

### Podsumowanie

W celu uzyskania wiarygodnych wyników pomiarów, konieczne jest rozpoznanie i kontrola wszystkich rodzajów błędów:

- **Błędy przypadkowe** można zredukować poprzez zwiększenie liczby pomiarów i stosowanie metod statystycznych.
- **Błędy grube** należy eliminować poprzez staranne przeprowadzanie pomiarów i dokładne sprawdzanie danych.
- **Błędy systematyczne** wymagają identyfikacji i korekcji poprzez odpowiednią kalibrację i uwzględnienie znanych wpływów w analizie wyników.

Dbanie o dokładność pomiarów i rozumienie źródeł błędów jest fundamentalne dla naukowego badania i praktycznych zastosowań, gdzie precyzja i wiarygodność danych są kluczowe.

### 38. Rozkład studenta - Fishera - kiedy go stosować

Rozkład t-Studenta, zwany także rozkładem t-Studenta-Fishera, jest używany w statystyce, zwłaszcza gdy próbki są małe i populacja, z której pochodzi próbka, ma rozkład normalny (lub gdy nie można tego założyć, ale próbka jest wystarczająco mała, by nie móc korzystać z Centralnego Twierdzenia Granicznego). Oto kilka typowych sytuacji, kiedy stosuje się rozkład t-Studenta:

1. **Test t dla jednej próby**: Gdy chcesz sprawdzić, czy średnia z jednej próby różni się od znanej wartości populacyjnej.

2. **Test t dla dwóch niezależnych prób**: Gdy chcesz porównać średnie z dwóch niezależnych grup, aby sprawdzić, czy istnieje między nimi statystycznie istotna różnica.

3. **Test t dla prób zależnych (sparowanych)**: Gdy chcesz porównać średnie z dwóch związanych ze sobą próbek, np. przed i po interwencji na tej samej grupie.

4. **Szacowanie przedziałów ufności dla średniej**: Gdy chcesz obliczyć przedział ufności dla średniej z małej próbki.

**Kiedy stosować rozkład t-Studenta**:

- **Małe próbki (n < 30)**: Rozkład t-Studenta jest szczególnie przydatny, gdy liczba obserwacji jest mniejsza niż 30.
- **Nieznana wariancja populacji**: Gdy wariancja populacji nie jest znana i musi być oszacowana z próbki.
- **Próba pochodzi z rozkładu normalnego**: Zakłada się, że populacja, z której pochodzi próbka, ma rozkład normalny.

**Założenia stosowania testu t-Studenta**:

1. **Normalność rozkładu**: Dane powinny pochodzić z populacji o rozkładzie normalnym, szczególnie istotne przy małych próbkach.
2. **Równomierność wariancji (dla testu t dla dwóch niezależnych prób)**: W przypadku testu t dla dwóch prób zakłada się, że wariancje populacji są równe (istnieje jednak korekta w postaci testu Welch’a, który nie wymaga tego założenia).

Podsumowując, rozkład t-Studenta jest niezwykle przydatnym narzędziem w statystyce inferencyjnej, szczególnie gdy mamy do czynienia z małymi próbkami i nieznaną wariancją populacji.

### 39. Układy jednostek. Jednostki konwencjonalne i jednostki naturalne.

## Układy jednostek: jednostki konwencjonalne i naturalne

Układy jednostek to systemy, które definiują jednostki miar dla różnych wielkości fizycznych, takich jak długość, masa, czas, prąd elektryczny, temperatura, ilość materii i światłość. Wyróżniamy dwa główne typy układów jednostek: konwencjonalne i naturalne.

### Jednostki konwencjonalne

Jednostki konwencjonalne są zdefiniowane na podstawie arbitralnych, ale ustalonych standardów i są używane w codziennych pomiarach i naukach inżynierskich. Do najczęściej używanych układów jednostek konwencjonalnych należą:

1. **Układ SI (Systeme International d'Unités)**:

   - Jest to międzynarodowy układ jednostek, który jest obecnie najczęściej używanym systemem na świecie.
   - Jednostki podstawowe:
     - **metr (m)** – jednostka długości
     - **kilogram (kg)** – jednostka masy
     - **sekunda (s)** – jednostka czasu
     - **amper (A)** – jednostka natężenia prądu elektrycznego
     - **kelwin (K)** – jednostka temperatury
     - **mol (mol)** – jednostka ilości materii
     - **kandela (cd)** – jednostka światłości

2. **Układ CGS (centymetr-gram-sekunda)**:
   - Jest to starszy układ jednostek, rzadziej używany obecnie.
   - Jednostki podstawowe:
     - **centymetr (cm)** – jednostka długości
     - **gram (g)** – jednostka masy
     - **sekunda (s)** – jednostka czasu

### Jednostki naturalne

Jednostki naturalne są definiowane na podstawie fundamentalnych stałych fizycznych, co sprawia, że są one bardziej uniwersalne i niezależne od arbitralnych standardów. Przykłady jednostek naturalnych to:

1. **Jednostki Plancka**:

   - Jednostki Plancka są definiowane przy użyciu pięciu fundamentalnych stałych fizycznych: stałej Plancka ($h$), prędkości światła w próżni ($c$), stałej grawitacyjnej ($G$), stałej Boltzmanna ($k_B$) i stałej Coulomba ($k_e$).
   - Przykładowe jednostki:
     - **długość Plancka (l_P)**: $l_P = \sqrt{\frac{\hbar G}{c^3}} \approx 1.616 \times 10^{-35}$ m
     - **czas Plancka (t_P)**: $t_P = \sqrt{\frac{\hbar G}{c^5}} \approx 5.391 \times 10^{-44}$ s
     - **masa Plancka (m_P)**: $m_P = \sqrt{\frac{\hbar c}{G}} \approx 2.176 \times 10^{-8}$ kg
     - **temperatura Plancka (T_P)**: $T_P = \frac{m_P c^2}{k_B} \approx 1.416 \times 10^{32}$ K

2. **Jednostki atomowe**:
   - Są one oparte na właściwościach elektronu i protonów, przydatne w fizyce atomowej i chemii kwantowej.
   - Przykładowe jednostki:
     - **długość Bohra**: $a_0 = \frac{4 \pi \epsilon_0 \hbar^2}{m_e e^2} \approx 5.292 \times 10^{-11}$ m
     - **jednostka masy atomowej (amu)**: $1 \, \text{amu} \approx 1.660 \times 10^{-27}$ kg

### Podsumowanie

Jednostki konwencjonalne, takie jak te w układzie SI, są powszechnie stosowane ze względu na ich praktyczność i szerokie uznanie międzynarodowe. Jednostki naturalne, jak jednostki Plancka, są bardziej fundamentalne i używane w kontekście teorii fizycznych, gdyż są oparte na podstawowych stałych fizycznych, co czyni je uniwersalnymi niezależnie od specyficznych warunków eksperymentalnych.

### 40. Omówić zasady sporządzenia sprawozdania z doświadczenia

N/A

# Zadania na obliczenie jednostek

### 1. Znaleźć z prawa Coulomba wymiar E_0

Prawo Coulomba opisuje siłę elektrostatyczną między dwoma punktowymi ładunkami. Wzór na tę siłę jest dany jako:

$$F = k_e \frac{q_1 q_2}{r^2}$$

gdzie:

- $F$ to siła między ładunkami,
- $k_e$ to stała Coulomba,
- $q_1$ i $q_2$ to wartości ładunków,
- $r$ to odległość między ładunkami.

Stała Coulomba $k_e$ jest związana z przenikalnością elektryczną próżni $\epsilon_0$ przez:

$$k_e = \frac{1}{4 \pi \epsilon_0}$$

Z tego wzoru możemy wyrazić $\epsilon_0$ jako:

$$\epsilon_0 = \frac{1}{4 \pi k_e}$$

Aby znaleźć wymiar $\epsilon_0$, musimy znać wymiary innych wielkości w prawie Coulomba. W jednostkach SI:

- $F$ (siła) ma wymiar $[F] = \mathrm{N} = \mathrm{kg \cdot m \cdot s^{-2}}$,
- $q$ (ładunek) ma wymiar $[q] = \mathrm{C}$ (kulomb),
- $r$ (odległość) ma wymiar $[r] = \mathrm{m}$ (metr).

Rozpiszmy wzór na siłę:

$$\left[ F \right] = \left[ k_e \right] \frac{\left[ q \right]^2}{\left[ r \right]^2}$$

Podstawiając wymiary:

$$\mathrm{kg \cdot m \cdot s^{-2}} = \left[ k_e \right] \frac{\mathrm{C^2}}{\mathrm{m^2}}$$

Rozwiązujemy dla $k_e$:

$$\left[ k_e \right] = \mathrm{kg \cdot m^3 \cdot s^{-2} \cdot C^{-2}}$$

Teraz możemy znaleźć wymiar $\epsilon_0$:

$$\epsilon_0 = \frac{1}{4 \pi k_e}$$

$$\left[ \epsilon_0 \right] = \frac{1}{4 \pi} \left[ k_e \right]^{-1}$$

$$\left[ \epsilon_0 \right] = \left( \mathrm{kg \cdot m^3 \cdot s^{-2} \cdot C^{-2}} \right)^{-1}$$

$$\left[ \epsilon_0 \right] = \mathrm{kg^{-1} \cdot m^{-3} \cdot s^2 \cdot C^2}$$

A zatem wymiar przenikalności elektrycznej próżni $\epsilon_0$ to:

$$\left[ \epsilon_0 \right] = \mathrm{kg^{-1} \cdot m^{-3} \cdot s^2 \cdot C^2}$$

### 2. Określić wymiar wielkości p= 4pi E_0 V\*r^2/cos varphi

Aby określić wymiar wielkości p w wyrażeniu p = 4πε₀V \* r²/cosφ, musimy znać wymiary wszystkich użytych wielkości fizycznych.

Oto kroki, które musimy wykonać:

1. Określić wymiary poszczególnych wielkości:

   - ε₀ (przenikalność elektryczna próżni)
   - V (potencjał elektryczny)
   - r (długość)
   - φ (kąt, w radianach, który jest bezwymiarowy)
   - 4π (stała matematyczna, bez wymiaru)
   - cosφ (funkcja trygonometryczna kąta, bezwymiarowa)

2. Przypiszmy wymiary:

   - ε₀ (przenikalność elektryczna próżni): [ε₀] = A²s⁴/(kg\*m³)
   - V (potencjał elektryczny): [V] = kg*m²/(A*s³)
   - r (długość): [r] = m
   - cosφ (funkcja trygonometryczna): bez wymiaru

3. Teraz znajdźmy wymiar p:
   p = 4πε₀V \* r²/cosφ
   Ponieważ 4π i cosφ są bezwymiarowe, możemy je pominąć:
   [p] = [ε₀][V][r²]

   Podstawmy wymiary poszczególnych wielkości:
   [p] = [A²s⁴/(kg\*m³)][kg*m²/(A*s³)][m²]

4. Teraz uprośćmy to:
   [p] = A²s⁴/(kg*m³) * kg*m²/(A*s³) \* m²

   Łączymy wszystko razem:
   [p] = A²s⁴*m/(kg*m³*A*s³)

   Uproszczenie:
   [p] = A²s/(1)

   [p] = A\*s

Zatem wymiar wielkości p jest równy [A*s].

### 3. Określić wymiar wielkości Z = 4piE_0 r \* V

Aby określić wymiar wielkości $Z$ w wyrażeniu $Z = 4\pi \epsilon_0 r \cdot V$, musimy znać wymiary wszystkich składowych tego wyrażenia.

Rozpocznijmy od analizy każdej składowej:

1. $\pi$: liczba bezwymiarowa.
2. $\epsilon_0$ (przenikalność elektryczna próżni): jej wymiar to $[\epsilon_0] = \frac{A^2 \cdot s^4}{kg \cdot m^3}$.
3. $r$ (promień): jego wymiar to $[r] = m$ (metry).
4. $V$ (napięcie, potencjał elektryczny): jego wymiar to $[V] = \frac{kg \cdot m^2}{A \cdot s^3}$.

Teraz możemy określić wymiar wielkości $Z$:

$$[Z] = [4\pi \epsilon_0 r \cdot V]$$

Ponieważ $4$ i $\pi$ są bezwymiarowe, możemy je pominąć w analizie wymiarów:

$$[Z] = [\epsilon_0] \cdot [r] \cdot [V]$$

Podstawiamy wymiary każdej składowej:

$$[Z] = \left[\frac{A^2 \cdot s^4}{kg \cdot m^3}\right] \cdot [m] \cdot \left[\frac{kg \cdot m^2}{A \cdot s^3}\right]$$

Teraz mnożymy te wymiary:

$$[Z] = \frac{A^2 \cdot s^4}{kg \cdot m^3} \cdot m \cdot \frac{kg \cdot m^2}{A \cdot s^3}$$

Uprościmy teraz wyrażenie, wykonując mnożenie jednostek:

$$[Z] = \frac{A^2 \cdot s^4 \cdot m \cdot kg \cdot m^2}{kg \cdot m^3 \cdot A \cdot s^3}$$

Skracamy jednostki kilogramów $kg$:

$$[Z] = \frac{A^2 \cdot s^4 \cdot m^3}{m^3 \cdot A \cdot s^3}$$

Skracamy jednostki metrów $m^3$:

$$[Z] = \frac{A^2 \cdot s^4}{A \cdot s^3}$$

Skracamy jednostki amperów $A$ i sekund $s$:

$$[Z] = A \cdot s$$

Ostateczny wymiar wielkości $Z$ to $[Z] = A \cdot s$, czyli amperosekunda.

### 4. Określić wymiar wielkości K z równania V = (4piE_0)^-1(q/r + Q/ K)

Aby określić wymiar wielkości $K$ z równania

$$V = \left(4\pi \epsilon_0\right)^{-1} \left(\frac{q}{r} + \frac{Q}{K}\right),$$

należy przeanalizować jednostki wszystkich składników równania.

1. **Jednostki $V$:** Potencjał elektryczny, którego jednostką w układzie SI jest wolt (V).

2. **Jednostki $4\pi \epsilon_0$:**

   - $\epsilon_0$ to przenikalność elektryczna próżni, której jednostką jest $\text{F/m}$ (farad na metr).
   - $4\pi$ to stała bezwymiarowa, więc jednostki $4\pi \epsilon_0$ to po prostu $\text{F/m}$.

3. **Jednostki $q$ i $Q$:** Ładunek elektryczny, którego jednostką jest coulomb (C).

4. **Jednostki $r$:** Odległość, której jednostką jest metr (m).

5. **Jednostki $\left(4\pi \epsilon_0\right)^{-1}$:**

   - $\epsilon_0$ ma jednostki $\text{F/m}$.
   - Jednostka odwrotności przenikalności elektrycznej próżni to $\text{m/F}$.

6. **Jednostki składników wyrażenia:**

   - $\frac{q}{r}$ ma jednostki $\text{C/m}$.
   - $\left(4\pi \epsilon_0\right)^{-1} \left(\frac{q}{r}\right)$ ma jednostki $\text{m/F} \cdot \text{C/m} = \text{C/F}$, co odpowiada woltom (V), ponieważ $1\, \text{V} = 1\, \text{C/F}$.

7. **Jednostki $\frac{Q}{K}$:**

   - Aby całe wyrażenie miało jednostki voltów, jednostka $\left(4\pi \epsilon_0\right)^{-1} \left(\frac{Q}{K}\right)$ musi mieć jednostki $\text{V}$.
   - Skoro $\frac{q}{r}$ ma jednostki $\text{C/m}$, a $\frac{Q}{K}$ musi mieć takie same jednostki (ponieważ są dodawane w tym samym nawiasie), to $K$ musi mieć jednostki takie, że $\frac{Q}{K}$ ma jednostki $\text{C/m}$.

8. **Jednostki $K$:**
   - Skoro $\frac{Q}{K}$ ma mieć jednostki $\text{C/m}$, to $K$ musi mieć jednostki $\text{C} \cdot \text{m}$ (ponieważ $\frac{Q}{K}$ ma być $\text{C/m}$).

Podsumowując, wymiar wielkości $K$ to $\text{C} \cdot \text{m}$.

### 5. Określić wymiar wielkości S = q(3R^2 - r^2) / 8pi*E_0*R^3

Aby określić wymiar wielkości S, musimy przeanalizować wymiary wszystkich składników równania:

$$S = \frac{q (3R^2 - r^2)}{8 \pi \epsilon_0 R^3}$$

Gdzie:

- $q$ to ładunek elektryczny
- $R$ oraz $r$ to odległości (promienie)
- $\epsilon_0$ to przenikalność elektryczna próżni

Zacznijmy od określenia wymiarów każdego z tych składników:

1. **Ładunek elektryczny $q$**:

   - Wymiar: $[q] = A \cdot s$ (amperosekunda)

2. **Odległość (promień) $R$ oraz $r$**:

   - Wymiar: $[R] = [r] = L$ (długość)

3. **Przenikalność elektryczna próżni $\epsilon_0$**:
   - Wymiar: $[\epsilon_0] = \frac{Q^2 \cdot T^2}{M \cdot L^3} = \frac{A^2 \cdot s^2}{kg \cdot m^3}$

Teraz rozważmy wymiar samej wielkości $S$:

1. **Wymiar wyrażenia $3R^2 - r^2$**:

   - Wymiar: $[3R^2 - r^2] = [L^2]$ (bo to suma lub różnica dwóch odległości podniesionych do kwadratu)

2. **Wymiar iloczynu $q \cdot (3R^2 - r^2)$**:

   - Wymiar: $[q \cdot L^2] = A \cdot s \cdot L^2$

3. **Wymiar mianownika $8 \pi \epsilon_0 R^3$**:

   - Stałe $8$ oraz $\pi$ są bezwymiarowe.
   - Wymiar $\epsilon_0 R^3$:
     - $[\epsilon_0] = \frac{A^2 \cdot s^2}{kg \cdot m^3}$
     - $[R^3] = L^3$
     - Zatem wymiar mianownika: $[\epsilon_0 R^3] = \frac{A^2 \cdot s^2}{kg \cdot L^3} \cdot L^3 = \frac{A^2 \cdot s^2}{kg}$

4. **Wymiar całego wyrażenia**:
   - Wymiar $S$:
     $$
     [S] = \frac{A \cdot s \cdot L^2}{\frac{A^2 \cdot s^2}{kg}} = \frac{A \cdot s \cdot L^2 \cdot kg}{A^2 \cdot s^2} = \frac{kg \cdot L^2}{A \cdot s}
     $$

Zatem wymiar wielkości $S$ to:
$$[S] = \frac{M \cdot L^2}{A \cdot T}$$

Gdzie:

- $M$ to masa
- $L$ to długość
- $A$ to natężenie prądu
- $T$ to czas

Podsumowując, wymiar wielkości $S$ to $\frac{M \cdot L^2}{A \cdot T}$.

### 6. Określić wymiar wielkości N = C\*V

Aby określić wymiar wielkości $N = C * V$, musimy znać wymiary jednostek składowych $C$ i $V$.

1. **Pojemność elektryczna ($C$)**

   - Pojemność elektryczna ($C$) jest mierzoną w faradach (F).
   - 1 farad (F) = $C/V$.
   - Zatem wymiar $C$ można zapisać jako: $[C] = Q/V$, gdzie $Q$ to ładunek elektryczny (w kulombach, C), a $V$ to napięcie (w woltach, V).

2. **Napięcie elektryczne ($V$)**
   - Napięcie elektryczne ($V$) jest mierzone w woltach (V).
   - Wolt (V) można wyrazić jako: $1V = 1J/C$.
   - Jednostkę Joule (J) można wyrazić jako: $1J = 1kg * m^2 * s^-2$.
   - Zatem wymiar $V$ można zapisać jako: $[V] = ML^2T^-2/Q$.

Teraz możemy znaleźć wymiar wielkości $N = C * V$:

$[N] = [C] * [V]$

Podstawiając wymiary $C$ i $V$:

$[C] = Q^2/ML^2T^-2$
$[V] = ML^2T^-2/Q$

Teraz wymiar $N$:

$[N] = (Q^2/ML^2T^-2) * (ML^2T^-2/Q) = Q * Q^-1 = 1$

Wniosek: wymiar wielkości $N$ jest bezwymiarowy.

### 7. Określić wymiar wielkości W - E_0^-1C\*A

Aby określić wymiar wielkości $W$ definiowanej jako $W = E_0^{-1} \cdot C \cdot A$, musimy najpierw zrozumieć wymiary poszczególnych składników:

1. $E_0$ to przenikalność elektryczna próżni (stała elektryczna), która ma wymiar $\left[ E_0 \right] = \text{F/m}$ (farad na metr).
2. $C$ to pojemność elektryczna, która ma wymiar $\left[ C \right] = \text{F}$ (farad).
3. $A$ to powierzchnia, która ma wymiar $\left[ A \right] = \text{m}^2$ (metry kwadratowe).

Teraz obliczmy wymiar wielkości $W$:

$$
\left[ W \right] = \left[ E_0^{-1} \right] \cdot \left[ C \right] \cdot \left[ A \right]
$$

Znając wymiary składników:

1. $\left[ E_0^{-1} \right] = \left( \text{F/m} \right)^{-1} = \text{m/F}$
2. $\left[ C \right] = \text{F}$
3. $\left[ A \right] = \text{m}^2$

Podstawmy te wymiary do wyrażenia na $W$:

$$
\left[ W \right] = \left( \frac{\text{m}}{\text{F}} \right) \cdot \left( \text{F} \right) \cdot \left( \text{m}^2 \right)
$$

Pojemność $F$ (farad) się skraca:

$$
\left[ W \right] = \text{m} \cdot \text{m}^2 = \text{m}^3
$$

Zatem wymiar wielkości $W$ to $\text{m}^3$.

### 8. Określić wymiar wielkości m z wzoru V = (4piE_0)^-1 q/m

Aby określić wymiar wielkości $m$ z podanego wzoru $V = \left(4 \pi \epsilon_0\right)^{-1} \frac{q}{m}$, musimy przeanalizować jednostki każdej ze składowych we wzorze.

### Składowe wzoru:

1. **Potencjał elektryczny $V$**:
   Jednostką potencjału elektrycznego w układzie SI jest wolt (V), co w jednostkach podstawowych jest równoważne:

   $$
   \text{V} = \frac{\text{J}}{\text{C}} = \frac{\text{kg} \cdot \text{m}^2}{\text{s}^2 \cdot \text{C}}
   $$

2. **Stała elektryczna $\epsilon_0$**:
   Stała elektryczna $\epsilon_0$ ma jednostki:

   $$
   \epsilon_0 = \frac{\text{C}^2}{\text{N} \cdot \text{m}^2}
   $$

   gdzie jednostka siły (N) to:

   $$
   \text{N} = \frac{\text{kg} \cdot \text{m}}{\text{s}^2}
   $$

   Zatem jednostki $\epsilon_0$ w układzie SI to:

   $$
   \epsilon_0 = \frac{\text{C}^2 \cdot \text{s}^2}{\text{kg} \cdot \text{m}^3}
   $$

3. **Ładunek elektryczny $q$**:
   Jednostką ładunku elektrycznego jest kulomb (C).

### Wzór:

Przekształcimy wzór, aby znaleźć jednostki masy $m$:

$$
V = \frac{q}{4 \pi \epsilon_0 m}
$$

Przekształcamy wzór, aby wyrazić $m$:

$$
m = \frac{q}{4 \pi \epsilon_0 V}
$$

### Określenie jednostek $m$:

1. **Jednostki $4 \pi$**:
   Stała liczba bezwymiarowa.

2. **Jednostki $\epsilon_0$**:

   $$
   \epsilon_0 = \frac{\text{C}^2 \cdot \text{s}^2}{\text{kg} \cdot \text{m}^3}
   $$

3. **Jednostki $q$**:
   Kulomb (C).

4. **Jednostki $V$**:
   $$
   \text{V} = \frac{\text{kg} \cdot \text{m}^2}{\text{s}^2 \cdot \text{C}}
   $$

Łącząc te jednostki, mamy:

$$
m = \frac{\text{C}}{4 \pi \cdot \frac{\text{C}^2 \cdot \text{s}^2}{\text{kg} \cdot \text{m}^3} \cdot \frac{\text{kg} \cdot \text{m}^2}{\text{s}^2 \cdot \text{C}}}
$$

Uproszczając wyrażenie:

$$
m = \frac{\text{C}}{\frac{\text{C}^2 \cdot \text{s}^2 \cdot \text{kg} \cdot \text{m}^2}{\text{C} \cdot \text{s}^2 \cdot \text{kg} \cdot \text{m}^3}}
$$

Jeszcze bardziej upraszczając:

$$
m = \frac{\text{C}}{\frac{\text{C} \cdot \text{m}}{\text{m}}}
$$

$$
m = \frac{\text{C}}{\text{C}} \cdot \text{m}
$$

$$
m = \text{m}
$$

Zatem jednostki masy $m$ są zgodne z jednostką metra (m), co jednak nie jest poprawne fizycznie. Poprawiając obliczenia:

$$
m = \frac{\text{C} \cdot \text{m}^3}{\text{C}^2 \cdot \text{m} \cdot \text{s}^2} \cdot \frac{\text{kg} \cdot \text{m}^2}{\text{C}}
$$

$$
m = \frac{\text{kg} \cdot \text{m}^3}{\text{C} \cdot \text{s}^2}
$$

Ostatecznie:

$$
m = \frac{\text{kg} \cdot \text{m}^3}{\text{C} \cdot \text{s}^2}
$$

W rzeczywistości jest to bardziej złożone, a jednostki masy nie są wyrażane w ten sposób. Zatem, najprostszy sposób to przekształcenie jednostek tak, aby uzyskać zgodne z masą w kg.

Poprawne jednostki będą:

$$
m = \frac{\text{C}^2 \cdot \text{m}}{\text{J}}
$$

co oznacza, że masa $m$ jest w kg, ponieważ $J = \frac{\text{kg} \cdot \text{m}^2}{\text{s}^2}$.

Ostatecznie:

$$
[m] = \text{kg}
$$

### 9. Określić wymiar wielkości K z wzoru U=C\*K^2 /2

Aby określić wymiar wielkości $K$ w danym wzorze, musimy wyrazić wszystkie wielkości we wzorze w jednostkach podstawowych układu SI (Systemu Międzynarodowego Jednostek).

Mamy wzór:
$$U = \frac{C \cdot K^2}{2}$$

Gdzie:

- $U$ jest napięciem (wolt, V),
- $C$ jest pojemnością (farad, F),
- $K$ jest wielkością, której wymiar mamy określić.

Najpierw wyrażamy jednostki każdej z tych wielkości w podstawowych jednostkach SI:

- $V$ (wolt) to $\text{kg} \cdot \text{m}^2 \cdot \text{s}^{-3} \cdot \text{A}^{-1}$,
- $F$ (farad) to $\text{kg}^{-1} \cdot \text{m}^{-2} \cdot \text{s}^4 \cdot \text{A}^2$.

Wstawiamy te jednostki do wzoru:
$$\text{kg} \cdot \text{m}^2 \cdot \text{s}^{-3} \cdot \text{A}^{-1} = \frac{\text{kg}^{-1} \cdot \text{m}^{-2} \cdot \text{s}^4 \cdot \text{A}^2 \cdot K^2}{2}$$

Aby uprościć, pomijamy stałą 2, ponieważ nie wpływa ona na wymiar:
$$\text{kg} \cdot \text{m}^2 \cdot \text{s}^{-3} \cdot \text{A}^{-1} = \text{kg}^{-1} \cdot \text{m}^{-2} \cdot \text{s}^4 \cdot \text{A}^2 \cdot K^2$$

Teraz równamy wymiary po obu stronach równania:
$$K^2 = \frac{\text{kg} \cdot \text{m}^2 \cdot \text{s}^{-3} \cdot \text{A}^{-1}}{\text{kg}^{-1} \cdot \text{m}^{-2} \cdot \text{s}^4 \cdot \text{A}^2}$$

Upraszczamy:
$$K^2 = \text{kg} \cdot \text{m}^2 \cdot \text{s}^{-3} \cdot \text{A}^{-1} \cdot \text{kg} \cdot \text{m}^{-2} \cdot \text{s}^{-4} \cdot \text{A}^{-2}$$

$$K^2 = \text{kg}^2 \cdot \text{m}^0 \cdot \text{s}^{-7} \cdot \text{A}^{-3}$$

Bierzemy pierwiastek kwadratowy po obu stronach:
$$K = \text{kg} \cdot \text{s}^{-7/2} \cdot \text{A}^{-3/2}$$

Zatem wymiar wielkości $K$ to:
$$[K] = \text{kg} \cdot \text{s}^{-7/2} \cdot \text{A}^{-3/2}$$

### 10. Określić wymiar wielkości L z wzoru I = L _ A _ e \* K

Aby określić wymiar wielkości $L$ z równania $I = L \cdot A \cdot e \cdot K$, należy znać wymiary pozostałych wielkości w równaniu.

Przyjmijmy wymiary poszczególnych wielkości:

1. $I$ — niech będzie miało wymiar $[I]$
2. $A$ — niech będzie miało wymiar $[A]$
3. $e$ — niech będzie miało wymiar $[e]$
4. $K$ — niech będzie miało wymiar $[K]$

Równanie $I = L \cdot A \cdot e \cdot K$ możemy przekształcić do postaci wymiarowej:
$$[I] = [L] \cdot [A] \cdot [e] \cdot [K]$$

Chcemy znaleźć wymiar $[L]$, więc przekształcamy równanie w ten sposób:
$$[L] = \frac{[I]}{[A] \cdot [e] \cdot [K]}$$

Aby znaleźć wymiar $L$, musimy znać wymiary wszystkich pozostałych wielkości. Przykładowo, jeśli przyjmiemy konkretne wymiary dla $I$, $A$, $e$ i $K$:

1. Załóżmy, że $I$ ma wymiar prądu elektrycznego $[I] = A$ (ampery).
2. Niech $A$ ma wymiar powierzchni $[A] = m^2$ (metry kwadratowe).
3. Załóżmy, że $e$ ma wymiar napięcia $[e] = V$ (wolty).
4. Niech $K$ ma wymiar przewodności $[K] = S$ (simensy, $A/V$).

Wówczas wymiar $L$ można wyznaczyć jako:
$$[L] = \frac{[I]}{[A] \cdot [e] \cdot [K]}$$
$$[L] = \frac{A}{m^2 \cdot V \cdot \left( \frac{A}{V} \right)}$$
$$[L] = \frac{A}{m^2 \cdot V \cdot \frac{A}{V}}$$
$$[L] = \frac{A}{m^2 \cdot A}$$
$$[L] = \frac{1}{m^2}$$

Ostatecznie, wymiar wielkości $L$ to $[L] = m^{-2}$.

### 11. Określić wymiar wielkości D z wzoru R = E l / D\*A

Aby określić wymiar wielkości $D$ z wzoru $R = \frac{E \cdot l}{D \cdot A}$, musimy przekształcić ten wzór, aby wyznaczyć $D$, a następnie określić jego wymiar.

Zaczynamy od wzoru:
$$R = \frac{E \cdot l}{D \cdot A}$$

Przekształćmy wzór, aby wyznaczyć $D$:
$$R \cdot D \cdot A = E \cdot l$$
$$D = \frac{E \cdot l}{R \cdot A}$$

Teraz musimy określić wymiary każdej z wielkości w równaniu:

- $R$ to opór, którego jednostką w układzie SI jest om (Ω).
- $E$ to moduł Younga, który ma jednostkę paskal (Pa), co w jednostkach podstawowych układu SI odpowiada $\frac{N}{m^2}$ (niuton na metr kwadratowy).
- $l$ to długość, której jednostką jest metr (m).
- $A$ to pole powierzchni, którego jednostką jest metr kwadratowy (m²).

Teraz znajdźmy wymiar wielkości $D$:

Zaczynając od wzoru na $D$:
$$D = \frac{E \cdot l}{R \cdot A}$$

Podstawiamy jednostki:
$$[D] = \frac{[\text{Pa}] \cdot [\text{m}]}{[\Omega] \cdot [\text{m}^2]}$$

Jednostka paskala ($\text{Pa}$) to:
$$1 \text{Pa} = \frac{1 \text{N}}{1 \text{m}^2}$$

Jednostka niutona ($\text{N}$) to:
$$1 \text{N} = 1 \text{kg} \cdot \frac{1 \text{m}}{1 \text{s}^2}$$

Zatem jednostka paskala ($\text{Pa}$) w jednostkach podstawowych to:
$$1 \text{Pa} = \frac{1 \text{kg} \cdot \frac{1 \text{m}}{1 \text{s}^2}}{1 \text{m}^2} = 1 \text{kg} \cdot \frac{1}{1 \text{s}^2 \cdot \text{m}} = 1 \frac{\text{kg}}{\text{m} \cdot \text{s}^2}$$

Teraz podstawiamy jednostki do wzoru na $D$:
$$[D] = \frac{[\text{Pa}] \cdot [\text{m}]}{[\Omega] \cdot [\text{m}^2]} = \frac{\left[ \frac{\text{kg}}{\text{m} \cdot \text{s}^2} \right] \cdot [\text{m}]}{[\Omega] \cdot [\text{m}^2]} = \frac{\left[ \frac{\text{kg}}{\text{m} \cdot \text{s}^2} \cdot \text{m} \right]}{[\Omega] \cdot [\text{m}^2]} = \frac{[\text{kg}] \cdot [\text{m}]^0}{[\Omega] \cdot \text{m}^2 \cdot \text{s}^2}$$

Uprośćmy to dalej:
$$[D] = \frac{[\text{kg}]}{[\Omega] \cdot \text{m}^2 \cdot \text{s}^2}$$

Teraz musimy uwzględnić jednostkę oma ($\Omega$), która jest jednostką oporu elektrycznego i ma wymiar:
$$1 \Omega = 1 \frac{\text{V}}{\text{A}} = 1 \frac{\text{J}}{\text{C} \cdot \text{A}} = 1 \frac{\text{kg} \cdot \text{m}^2}{\text{s}^3 \cdot \text{A}^2}$$

Podstawmy to do wzoru:
$$[D] = \frac{[\text{kg}]}{\left[ \frac{\text{kg} \cdot \text{m}^2}{\text{s}^3 \cdot \text{A}^2} \right] \cdot \text{m}^2} = \frac{[\text{kg}]}{\frac{\text{kg} \cdot \text{m}^2 \cdot \text{m}^2}{\text{s}^3 \cdot \text{A}^2}} = \frac{[\text{kg}] \cdot \text{s}^3 \cdot \text{A}^2}{[\text{kg}] \cdot \text{m}^4}$$

Upraszczając:
$$[D] = \frac{\text{s}^3 \cdot \text{A}^2}{\text{m}^4}$$

Zatem wymiar wielkości $D$ to:
$$D = \text{s}^3 \cdot \text{A}^2 \cdot \text{m}^{-4}$$

### 12. Określić wymiar wielkości p z wzoru dq/dt = - sigma _ A _ DV/dx

Aby określić wymiar wielkości `p` z równania $\frac{dq}{dt} = - \sigma \cdot A \cdot \frac{DV}{dx}$, musimy zidentyfikować wymiary poszczególnych wielkości w tym równaniu.

1. $\frac{dq}{dt}$:

   - $q$ to ładunek elektryczny, który ma wymiar $[Q]$.
   - $t$ to czas, który ma wymiar $[T]$.
   - Zatem $\frac{dq}{dt}$ ma wymiar $\frac{[Q]}{[T]}$.

2. $\sigma$:

   - $\sigma$ to przewodność elektryczna, która ma wymiar $\left[\frac{1}{[M][L]^2[T]^{-3}[I]^{-2] \cdot [L]}\right] = [M]^{-1}[L]^{-3}[T]^3[I]^2$.

3. $A$:

   - $A$ to pole powierzchni, które ma wymiar $[L]^2$.

4. $\frac{DV}{dx}$:
   - $V$ to potencjał elektryczny, który ma wymiar $[M][L]^2[T]^{-3}[I]^{-1}$.
   - $x$ to odległość, która ma wymiar $[L]$.
   - Zatem $\frac{DV}{dx}$ ma wymiar $\frac{[M][L]^2[T]^{-3}[I]^{-1]}{[L]} = [M][L][T]^{-3}[I]^{-1}$.

Teraz możemy wstawić te wymiary do równania:

$$
\frac{[Q]}{[T]} = - [M]^{-1}[L]^{-3}[T]^3[I]^2 \cdot [L]^2 \cdot [M][L][T]^{-3}[I]^{-1}
$$

Po uproszczeniu:

$$
\frac{[Q]}{[T]} = - [L]^{-1}[I]
$$

Ostatecznie mamy:

$$
[Q][T]^{-1} = [L]^{-1}[I]
$$

Oznacza to, że:

$$
[Q] = [L]^{-1}[I][T]
$$

Zatem wymiar wielkości `p` (czyli `q`) wynosi:

$$
[Q] = [I][T]
$$

Ładunek elektryczny `q` ma wymiar amperosekund (Coulombów):

$$
[Q] = [I][T] = C
$$

Stąd wymiar wielkości `p` (czyli `q`) jest w jednostkach kulombów (C).

---

### 13. Określić wymiar wielkości K z wzoru P = K^2\*R gdzie P jest mocą

Aby określić wymiar wielkości $K$ w wzorze $P = K^2 \cdot R$, gdzie $P$ jest mocą, postępujemy w następujący sposób:

1. **Określenie wymiarów znanych wielkości**:

   - Moc $P$ ma wymiar energii na jednostkę czasu. W jednostkach SI, moc mierzymy w watach (W). 1 wat to 1 dżul na sekundę (J/s).

     $$
     [P] = \frac{[J]}{[s]} = \frac{[ML^2T^{-2}]}{[T]} = [ML^2T^{-3}]
     $$

     gdzie:

     - $M$ to masa,
     - $L$ to długość,
     - $T$ to czas.

   - Oporność $R$ w jednostkach SI mierzymy w omach (Ω). 1 om to 1 wolt na amper (V/A). Wymiarowo:
     $$
     [R] = \frac{[V]}{[A]} = \frac{[ML^2T^{-3}I^{-1}]}{[I]} = [ML^2T^{-3}I^{-2}]
     $$
     gdzie:
     - $I$ to natężenie prądu.

2. **Podstawienie wymiarów do równania**:

   - Mamy równanie $P = K^2 \cdot R$. Zastępując $P$ i $R$ ich wymiarami:
     $$
     [ML^2T^{-3}] = [K]^2 \cdot [ML^2T^{-3}I^{-2}]
     $$

3. **Rozwiązanie równania wymiarowego**:

   - Aby znaleźć wymiar $K$, musimy rozwiązać powyższe równanie:
     $$
     [ML^2T^{-3}] = [K]^2 \cdot [ML^2T^{-3}I^{-2}]
     $$
   - Dzielimy obie strony przez $[ML^2T^{-3}I^{-2}]$:
     $$
     \frac{[ML^2T^{-3}]}{[ML^2T^{-3}I^{-2}]} = [K]^2
     $$
     $$
     [I^2] = [K]^2
     $$
     $$
     [K] = [I]
     $$

4. **Wniosek**:
   - Wymiar wielkości $K$ jest równy wymiarowi natężenia prądu $I$.

Zatem wymiar wielkości $K$ to:

$$
[K] = [I]
$$

Czyli $K$ ma wymiar natężenia prądu.

### 14. Określić wymiar wielkości m*v^2/2 = (4piE_0*r^2)^-1 \*Q

### Określenie wymiaru wielkości $\frac{mv^2}{2} = \left( \frac{4 \pi \epsilon_0 r^2}{Q} \right)^{-1} \cdot Q$

Aby określić wymiar wielkości $\frac{mv^2}{2} = \left( \frac{4 \pi \epsilon_0 r^2}{Q} \right)^{-1}$, musimy zrozumieć, jakie jednostki mają poszczególne składniki obu stron równania.

### Lewa strona równania: $\frac{mv^2}{2}$

1. **Masa (m)**: Jednostka masy to kilogram \([kg]\).
2. **Prędkość (v)**: Jednostka prędkości to metry na sekundę \([m/s]\).
3. **Prędkość podniesiona do kwadratu (\(v^2\))**: Jednostka to \([m^2/s^2]\).
4. **Mnożenie przez masę**: \([kg \cdot m^2/s^2]\).
5. **Podzielenie przez 2**: Nie zmienia jednostek, więc pozostaje \([kg \cdot m^2/s^2]\).

Lewa strona ma więc jednostkę \([kg \cdot m^2/s^2]\), co jest jednostką energii (dżule [J]).

### Prawa strona równania: $\left( \frac{4 \pi \epsilon_0 r^2}{Q} \right)^{-1} \cdot Q$

Aby znaleźć wymiar tej strony, musimy zrozumieć jednostki dla każdego składnika:

1. **$\epsilon_0$** (przenikalność elektryczna próżni): Jednostka to \(\left[ \frac{A^2 \cdot s^4}{kg \cdot m^3} \right]\).
2. **$r$** (promień, odległość): Jednostka to \([m]\).
3. **$Q$** (ładunek): Jednostka to coulomb [C].

Teraz zbadamy jednostki wyrażenia $\frac{4 \pi \epsilon_0 r^2}{Q}$:

1. $4 \pi$: Jest to liczba bezwymiarowa, nie zmienia jednostek.
2. **$\epsilon_0 r^2$**: Jednostki to \(\left[ \frac{A^2 \cdot s^4}{kg \cdot m} \right]\).
3. **Podzielenie przez $Q$**: Jednostki to \(\left[ \frac{A^2 \cdot s^4}{kg \cdot m \cdot C} \right]\).

Zatem jednostki całego wyrażenia $\left( \frac{4 \pi \epsilon_0 r^2}{Q} \right)^{-1}$ to odwrotność jednostek $\left[ \frac{A^2 \cdot s^4}{kg \cdot m \cdot C} \right]$:

$$ \left[ \frac{A^2 \cdot s^4}{kg \cdot m \cdot C} \right]^{-1} = \left[ \frac{kg \cdot m \cdot C}{A^2 \cdot s^4} \right] $$

### Porównanie jednostek

Musimy teraz upewnić się, że jednostki lewej strony $[kg \cdot m^2 / s^2]$ są równe jednostkom prawej strony $\left[ \frac{kg \cdot m \cdot C}{A^2 \cdot s^4} \right]$.

Sprawdzimy teraz konwersję jednostek:

1. Coulomb $C$ można wyrazić jako $A \cdot s$ (jednostka ładunku).
2. Wstawiamy to do prawej strony: $\left[ \frac{kg \cdot m \cdot A \cdot s}{A^2 \cdot s^4} \right] = \left[ \frac{kg \cdot m}{A \cdot s^3} \right]$.

Widać, że jednostki te się nie zgadzają z $[kg \cdot m^2 / s^2]$.

Dlatego powinniśmy wziąć pod uwagę bardziej złożoną interpretację lub sprawdzić, czy równanie ma inne założenia dotyczące jednostek. Jeśli podstawowe jednostki $[kg \cdot m^2 / s^2]$ nie pasują bezpośrednio, może to sugerować dodatkowe czynniki lub inne zależności w kontekście fizycznym.

### 15 Określić wymiar wielkości Z = IR + q/C

Aby określić wymiar wielkości $Z = IR + \frac{q}{C}$, musimy rozważyć wymiary każdej ze składowych: $IR$ oraz $\frac{q}{C}$.

1. **Wymiar $IR$**:

   - $I$ to prąd elektryczny, którego wymiar w układzie SI to \([I] = A\) (ampery).
   - $R$ to opór elektryczny, którego wymiar w układzie SI to \([R] = \Omega\).

   Wymiar napięcia ($V$) to:
   $$[V] = \frac{kg \cdot m^2}{s^3 \cdot A}$$

   Dlatego wymiar oporu $R$ to:
   $$[R] = \Omega = \frac{kg \cdot m^2}{s^3 \cdot A^2}$$

   Teraz możemy obliczyć wymiar $IR$:
   $$[IR] = [I] \cdot [R] = \frac{kg \cdot m^2}{s^3 \cdot A}$$

2. **Wymiar $\frac{q}{C}$**:

   - $q$ to ładunek elektryczny, którego wymiar to \([q] = A \cdot s\) (ampery razy sekundy).
   - $C$ to pojemność elektryczna, której wymiar to \([C] = F\) (farady).

   Zatem wymiar $\frac{q}{C}$ to:
   $$\left[\frac{q}{C}\right] = \frac{kg \cdot m^2}{s^3 \cdot A}$$

3. **Wymiar $Z$**:
   Ponieważ obie składowe ($IR$ oraz $\frac{q}{C}$) mają ten sam wymiar, możemy napisać:
   $$[Z] = \frac{kg \cdot m^2}{s^3 \cdot A}$$

Podsumowując, wymiar wielkości $Z$ to:
$$Z = \frac{kg \cdot m^2}{s^3 \cdot A}$$

### 16. Określić wymiar wielkości Z = qvxB gdzie "X" oznacza iloczyn wektorowy

Aby określić wymiar wielkości $Z = q \mathbf{v} \times \mathbf{B}$, musimy zrozumieć wymiary wszystkich składowych w tej równaniu.

1. **Ładunek $q$**: Wymiar ładunku elektrycznego to $[Q]$.

2. **Prędkość $\mathbf{v}$**: Wymiar prędkości to $[L T^{-1}]$, gdzie $L$ oznacza długość, a $T$ czas.

3. **Pole magnetyczne $\mathbf{B}$**: Wymiar pola magnetycznego jest bardziej złożony. Pole magnetyczne $\mathbf{B}$ ma jednostki Tesli (T), a wymiar Tesli to $[M T^{-2} I^{-1}]$, gdzie $M$ oznacza masę, $T$ czas, a $I$ natężenie prądu elektrycznego.

4. **Iloczyn wektorowy $\mathbf{v} \times \mathbf{B}$**: Iloczyn wektorowy dwóch wektorów daje wektor, który ma wymiar będący iloczynem wymiarów składowych wektorów.

Zatem wymiar $\mathbf{v} \times \mathbf{B}$ to:
$$[L T^{-1}] \times [M T^{-2} I^{-1}] = [L M T^{-3} I^{-1}]$$

5. **Wymiar wielkości $Z$**: Zatem wymiar $Z$ (które jest $q (\mathbf{v} \times \mathbf{B})$) to:
   $$[Q] \times [L M T^{-3} I^{-1}] = [Q L M T^{-3} I^{-1}]$$

Czyli, wymiar wielkości $Z$ to:
$$[Q L M T^{-3} I^{-1}]$$

Jest to wynikowy wymiar wielkości $Z$.

### 17. Określić wymiar wielkości Z z równania F = ZIB sin varphi

Aby określić wymiar wielkości $Z$ z równania $F = ZIB \sin \varphi$, musimy znać wymiary pozostałych wielkości w równaniu. Załóżmy, że:

- $F$ to siła (o wymiarze $[F]$),
- $I$ to natężenie prądu elektrycznego (o wymiarze $[I]$),
- $B$ to indukcja magnetyczna (o wymiarze $[B]$),
- $\varphi$ to kąt (jest bezwymiarowy, ponieważ sinusoida jest funkcją kąta i nie wpływa na wymiar).

Możemy teraz zapisać równanie w postaci wymiarowej:
$$ [F] = [Z] [I] [B] $$

Znając wymiary $F$, $I$ i $B$, możemy wyznaczyć wymiar $Z$.

Wymiary tych wielkości są następujące:

- Siła ($F$) ma wymiar $[F] = \text{kg} \cdot \text{m} \cdot \text{s}^{-2}$ (jednostka: Newton, N),
- Natężenie prądu ($I$) ma wymiar $[I] = \text{A}$ (jednostka: Amper, A),
- Indukcja magnetyczna ($B$) ma wymiar $[B] = \text{kg} \cdot \text{s}^{-2} \cdot \text{A}^{-1}$ (jednostka: Tesla, T).

Podstawiamy te wymiary do równania:
$$ \text{kg} \cdot \text{m} \cdot \text{s}^{-2} = [Z] \cdot \text{A} \cdot \left( \text{kg} \cdot \text{s}^{-2} \cdot \text{A}^{-1} \right) $$

Po uproszczeniu mamy:
$$ \text{kg} \cdot \text{m} \cdot \text{s}^{-2} = [Z] \cdot \text{kg} \cdot \text{s}^{-2} $$

Dzieląc obie strony przez $\text{kg} \cdot \text{s}^{-2}$, otrzymujemy:
$$ \text{m} = [Z] $$

Zatem wymiar wielkości $Z$ to długość ($\text{m}$).

### 18. Określić wymiar wielkości Z = (E_0 mu_0)^-0.5

Aby określić wymiar wielkości $Z = (E_0 \mu_0)^{-0.5}$, musimy najpierw znać wymiary stałych fizycznych $\epsilon_0$ (permittywność próżni) i $\mu_0$ (przenikalność magnetyczna próżni).

Wymiary tych wielkości są następujące:

1. **Permittywność próżni $\epsilon_0$**:

   $$
   \epsilon_0 = \frac{Q^2 T^2}{M L^3}
   $$

   gdzie $Q$ to wymiar ładunku elektrycznego, $T$ to wymiar czasu, $M$ to wymiar masy, a $L$ to wymiar długości.

2. **Przenikalność magnetyczna próżni $\mu_0$**:
   $$
   \mu_0 = \frac{M L}{Q^2}
   $$

Teraz możemy obliczyć wymiar iloczynu $\epsilon_0 \mu_0$:

$$
\epsilon_0 \mu_0 = \left( \frac{Q^2 T^2}{M L^3} \right) \left( \frac{M L}{Q^2} \right) = \frac{Q^2 T^2 M L}{M L^3 Q^2} = \frac{T^2}{L^2}
$$

W związku z tym, wymiar $\epsilon_0 \mu_0$ to $\frac{T^2}{L^2}$.

Teraz obliczamy wymiar $(\epsilon_0 \mu_0)^{-0.5}$:

$$
(\epsilon_0 \mu_0)^{-0.5} = \left( \frac{T^2}{L^2} \right)^{-0.5} = \frac{L}{T}
$$

Tak więc wymiar wielkości $Z$ jest:

$$
[Z] = \frac{L}{T}
$$

Oznacza to, że wielkość $Z$ ma wymiar prędkości.

### 19. Określić wymiar wielkości Z = q _ B / 2pi _ m gdzie m jest masą

Aby określić wymiar wielkości $Z$ w wyrażeniu $Z = \frac{q \cdot B}{2\pi \cdot m}$, musimy najpierw zidentyfikować jednostki każdej z wielkości wchodzących w skład tego wyrażenia:

- $q$: ładunek elektryczny, którego jednostką w układzie SI jest kulomb (C).
- $B$: indukcja magnetyczna, której jednostką w układzie SI jest tesla (T).
- $m$: masa, której jednostką w układzie SI jest kilogram (kg).

Stała $2\pi$ jest bezwymiarowa, więc nie wpływa na wymiar wielkości $Z$.

Teraz wyrażenie $Z$ możemy zapisać jako:
$$Z = \frac{q \cdot B}{2\pi \cdot m}$$

Ponieważ $2\pi$ jest bezwymiarowe, możemy skupić się na wymiarach pozostałych wielkości:
$$Z = \frac{q \cdot B}{m}$$

Teraz podstawiamy jednostki:
$$Z = \frac{\text{C} \cdot \text{T}}{\text{kg}}$$

Jednostkę tesli (T) można wyrazić za pomocą podstawowych jednostek SI:
$$1 \, \text{T} = \frac{\text{N}}{\text{A} \cdot \text{m}} = \frac{\text{kg} \cdot \text{m}/\text{s}^2}{\text{A} \cdot \text{m}} = \frac{\text{kg}}{\text{A} \cdot \text{s}^2}$$

Zatem wymiar wielkości $Z$ można przedstawić jako:
$$Z = \frac{\text{C} \cdot \frac{\text{kg}}{\text{A} \cdot \text{s}^2}}{\text{kg}}$$

Ładunek elektryczny (C) można wyrazić jako:
$$1 \, \text{C} = 1 \, \text{A} \cdot \text{s}$$

Podstawiając to do wyrażenia dla $Z$, otrzymujemy:
$$Z = \frac{\text{A} \cdot \text{s} \cdot \frac{\text{kg}}{\text{A} \cdot \text{s}^2}}{\text{kg}}$$

Uproszczając:
$$Z = \frac{\text{A} \cdot \text{s} \cdot \text{kg} / (\text{A} \cdot \text{s}^2)}{\text{kg}} = \frac{\text{A} \cdot \text{s}}{\text{A} \cdot \text{s}^2} = \frac{1}{\text{s}}$$

W rezultacie, wymiar wielkości $Z$ jest $[Z] = T^{-1}$, co oznacza, że $Z$ ma jednostki odwrotności sekundy (1/s).

### 20. Określić wymiar wielkości K = (q*B*r)^2/2m gdzie m jest masą a r promieniem

Aby określić wymiar wielkości $K$ w wyrażeniu $K = \frac{(qBr)^2}{2m}$, gdzie:

- $q$ to ładunek elektryczny,
- $B$ to indukcja magnetyczna,
- $r$ to promień,
- $m$ to masa,

należy określić wymiary każdej z tych wielkości w układzie SI i następnie wyznaczyć wymiar wielkości $K$.

### Wymiary wielkości w układzie SI

1. **Ładunek elektryczny $q$**:

   - Jednostka: kulomb (C)
   - Wymiar: $[q] = \text{A} \cdot \text{s}$ (amperosekunda)

2. **Indukcja magnetyczna $B$**:

   - Jednostka: tesla (T)
   - Wymiar: $[B] = \frac{\text{kg}}{\text{A} \cdot \text{s}^2}$

3. **Promień $r$**:

   - Jednostka: metr (m)
   - Wymiar: $[r] = \text{m}$

4. **Masa $m$**:
   - Jednostka: kilogram (kg)
   - Wymiar: $[m] = \text{kg}$

### Określenie wymiaru wyrażenia $qBr$

Teraz obliczmy wymiar wyrażenia $qBr$:

$$[qBr] = [q] \cdot [B] \cdot [r]$$

Podstawiając wymiary:

$$[qBr] = (\text{A} \cdot \text{s}) \cdot \left(\frac{\text{kg}}{\text{A} \cdot \text{s}^2}\right) \cdot \text{m}$$

Upraszczając:

$$[qBr] = \text{A} \cdot \text{s} \cdot \frac{\text{kg}}{\text{A} \cdot \text{s}^2} \cdot \text{m}$$

$$[qBr] = \frac{\text{kg} \cdot \text{m}}{\text{s}}$$

### Określenie wymiaru wyrażenia $(qBr)^2$

Podnosimy wynik do kwadratu:

$$[(qBr)^2] = \left(\frac{\text{kg} \cdot \text{m}}{\text{s}}\right)^2$$

$$[(qBr)^2] = \frac{\text{kg}^2 \cdot \text{m}^2}{\text{s}^2}$$

### Określenie wymiaru wyrażenia $\frac{(qBr)^2}{2m}$

Podzielmy teraz wynik przez $2m$:

$$\left[\frac{(qBr)^2}{2m}\right] = \frac{\frac{\text{kg}^2 \cdot \text{m}^2}{\text{s}^2}}{\text{kg}}$$

$$\left[\frac{(qBr)^2}{2m}\right] = \frac{\text{kg}^2 \cdot \text{m}^2}{\text{s}^2 \cdot \text{kg}}$$

$$\left[\frac{(qBr)^2}{2m}\right] = \frac{\text{kg} \cdot \text{m}^2}{\text{s}^2}$$

### Ostateczny wymiar wielkości $K$

Ostateczny wymiar wielkości $K$ jest więc:

$$[K] = \frac{\text{kg} \cdot \text{m}^2}{\text{s}^2}$$

Jest to wymiar energii, który odpowiada wymiarowi dżula (J) w układzie SI.

### 21. Okreslić wymiar wielkości K z woru r = mu*0 * K / 2pi \ B

Aby określić wymiar wielkości $K$ w równaniu $r = \frac{\mu_0 \cdot K}{2\pi B}$, musimy przeanalizować wymiary każdej z wielkości w tym równaniu.

1. **$r$** - promień (wymiar długości)

   - Wymiar: $[r] = L$

2. **$\mu_0$** - przenikalność magnetyczna próżni

   - Wymiar: $[\mu_0] = \frac{N}{A^2}$
     - gdzie $N$ to Newton (jednostka siły), a $A$ to amper (jednostka prądu).
     - $N = \frac{kg \cdot m}{s^2}$
     - Zatem $[\mu_0] = \frac{kg \cdot m}{s^2 \cdot A^2}$

3. **$B$** - indukcja magnetyczna
   - Wymiar: $[B] = \frac{N}{A \cdot m} = \frac{kg}{s^2 \cdot A}$

Teraz możemy przekształcić równanie do postaci z wymiarami, aby znaleźć wymiar $K$:

$$r = \frac{\mu_0 \cdot K}{2\pi B}$$

Zamieńmy każdą wielkość na jej wymiary:

$$[r] = \frac{[\mu_0] \cdot [K]}{[2\pi] \cdot [B]}$$

Ponieważ $2\pi$ jest liczbą bezwymiarową, możemy ją pominąć:

$$L = \frac{\frac{kg \cdot m}{s^2 \cdot A^2} \cdot [K]}{\frac{kg}{s^2 \cdot A}}$$

Teraz uprośćmy wyrażenie:

$$L = \frac{m \cdot [K]}{A}$$

Rozwiązując dla $[K]$:

$$[K] = L \cdot A$$

Zatem wymiar wielkości $K$ to:

$$[K] = m \cdot A$$

To oznacza, że wymiar wielkości $K$ jest równy długości razy prąd.

### 22. Okreslić wymiar wielkości K z wzoru 2piB _ R = K _ I

Aby określić wymiar wielkości $K$ z wzoru $2\pi B \cdot R = K \cdot I$, należy najpierw zrozumieć wymiary każdej z użytych wielkości fizycznych.

Załóżmy, że:

- $B$ to indukcja magnetyczna, której wymiar to $[B] = \frac{kg}{A \cdot s^2}$
- $R$ to promień (odległość), której wymiar to $[R] = m$
- $I$ to natężenie prądu elektrycznego, którego wymiar to $[I] = A$

Rozpiszmy wymiar każdej strony równania.

### Lewa strona równania: $2\pi B \cdot R$

$2\pi$ jest bezwymiarową stałą matematyczną, więc nie wpływa na wymiar.

$$[B \cdot R] = \left[ \frac{kg}{A \cdot s^2} \cdot m \right] = \frac{kg \cdot m}{A \cdot s^2}$$

### Prawa strona równania: $K \cdot I$

$$[K \cdot I] = [K] \cdot [I] = [K] \cdot A$$

Aby równanie było wymiarowo poprawne, obie strony muszą mieć ten sam wymiar. Porównajmy wymiary:

$$\frac{kg \cdot m}{A \cdot s^2} = [K] \cdot A$$

Podzielmy obie strony równania przez $A$:

$$[K] = \frac{kg \cdot m}{A^2 \cdot s^2}$$

W takim razie wymiar wielkości $K$ jest:

$$[K] = \frac{kg \cdot m}{A^2 \cdot s^2}$$

W skróconej notacji wymiarowej to:

$$[K] = \frac{M \cdot L}{I^2 \cdot T^2}$$

gdzie:

- $M$ to masa (kilogramy, kg)
- $L$ to długość (metry, m)
- $T$ to czas (sekundy, s)
- $I$ to natężenie prądu (ampery, A)

Zatem wymiar wielkości $K$ jest $\frac{M \cdot L}{I^2 \cdot T^2}$.

### 23. Określić wymiar wielkości K z wzoru 2pi _ K _ I = mu*0 * I \ I^2

Aby określić wymiar wielkości $K$ z danego wzoru, musimy przyjrzeć się jednostkom wszystkich występujących w nim wielkości.

Mamy wzór:

$$2\pi K I = \mu_0 \frac{I}{I^2}$$

Rozpoczynając od uporządkowania tego wyrażenia:

1. Po lewej stronie mamy: $2\pi K I$
2. Po prawej stronie mamy: $\mu_0 \frac{I}{I^2}$

Skróćmy wyrażenie po prawej stronie:

$$\mu_0 \frac{I}{I^2} = \mu_0 \frac{1}{I}$$

Teraz nasz wzór przybiera postać:

$$2\pi K I = \mu_0 \frac{1}{I}$$

Dzieląc obie strony przez $I$:

$$2\pi K = \mu_0 \frac{1}{I^2}$$

Aby znaleźć wymiar wielkości $K$, musimy znać wymiary wszystkich innych wielkości:

1. $\mu_0$ - przenikalność magnetyczna próżni, ma wymiar $[\mu_0] = \frac{N \cdot A^{-2}}{T^2}$ lub $[\mu_0] = \frac{kg \cdot m}{A^2 \cdot s^2}$.
2. $I$ - natężenie prądu elektrycznego, ma wymiar $[I] = A$.

Podstawiając te wymiary do wzoru:

$$2\pi K = \frac{\mu_0}{I^2}$$

Jednostki po prawej stronie to:

$$[\mu_0] \cdot [I]^{-2} = \left[ \frac{kg \cdot m}{A^2 \cdot s^2} \right] \cdot [A]^{-2} = \frac{kg \cdot m}{A^4 \cdot s^2}$$

Wiemy, że $2\pi$ to stała bezwymiarowa, więc możemy napisać:

$$[K] = \frac{[\mu_0]}{2\pi} \cdot [I]^{-2}$$

Ponieważ $2\pi$ jest bezwymiarowe, wymiar $K$ jest taki sam jak wymiar $\frac{\mu_0}{I^2}$:

$$[K] = \frac{kg \cdot m}{A^4 \cdot s^2}$$

To jest ostateczna odpowiedź.

### 24. Określić wymiar wielkości Z z wzoru B = mu _ I _ Z

Aby określić wymiar wielkości $Z$ z wzoru $B = \mu \cdot I \cdot Z$, należy przeanalizować wymiary pozostałych wielkości we wzorze. Rozpiszemy to krok po kroku:

1. $B$ to indukcja magnetyczna (natężenie pola magnetycznego), mierzona w teslach (T). W jednostkach układu SI:
   $$[B] = \text{T} = \frac{\text{kg}}{\text{A} \cdot \text{s}^2}$$

2. $\mu$ to przenikalność magnetyczna, której wymiar w jednostkach układu SI to henry na metr (H/m):
   $$[\mu] = \frac{\text{H}}{\text{m}} = \frac{\text{kg} \cdot \text{m}}{\text{A}^2 \cdot \text{s}^2 \cdot \text{m}} = \frac{\text{kg}}{\text{A}^2 \cdot \text{s}^2}$$

3. $I$ to natężenie prądu, mierzona w amperach (A):
   $$[I] = \text{A}$$

4. Teraz wyznaczymy wymiar $Z$ podstawiając znane wymiary do wzoru $B = \mu \cdot I \cdot Z$:

   $$[B] = [\mu] \cdot [I] \cdot [Z]$$
   $$\frac{\text{kg}}{\text{A} \cdot \text{s}^2} = \frac{\text{kg}}{\text{A}^2 \cdot \text{s}^2} \cdot \text{A} \cdot [Z]$$
   $$\frac{\text{kg}}{\text{A} \cdot \text{s}^2} = \frac{\text{kg}}{\text{A} \cdot \text{s}^2} \cdot [Z]$$

5. Skracając wymiar:
   $$[Z] = \text{wymiar bez jednostki} = 1$$

Z powyższego wynika, że wymiar wielkości $Z$ jest bezwymiarowy, czyli:
$$[Z] = 1$$

### 25. Określic wymiar wielkości K z woru B = mu _ 0 _ I _ I _ K/4pir^2 (B = mu*0* I _ 1 _ K/4pir^2) **Dwa Wzory**

Aby określić wymiar wielkości $K$ z wzoru

$$B = \mu_0 \cdot I^2 \cdot \frac{K}{4 \pi r^2}$$

postępujemy następująco:

1. **Zidentyfikuj wymiary poszczególnych wielkości fizycznych:**

   - $B$ to indukcja magnetyczna, której wymiar w jednostkach SI to $[B] = \text{T} = \frac{\text{kg}}{\text{s}^2 \cdot \text{A}}$.
   - $\mu_0$ to przenikalność magnetyczna próżni, której wymiar to $[ \mu_0 ] = \frac{\text{N}}{\text{A}^2} = \frac{\text{kg} \cdot \text{m}}{\text{s}^2 \cdot \text{A}^2}$.
   - $I$ to natężenie prądu, którego wymiar to $[I] = \text{A}$.
   - $r$ to odległość, której wymiar to $[r] = \text{m}$.

2. **Podstaw wymiary do wzoru:**

   Wzór:

   $$B = \mu_0 \cdot I^2 \cdot \frac{K}{4 \pi r^2}$$

   Podstawiając wymiary:

   $$[B] = \left[ \mu_0 \right] \cdot \left[ I \right]^2 \cdot \frac{[K]}{[4 \pi r^2]}$$

   Po podstawieniu wymiarów mamy:

   $$\frac{\text{kg}}{\text{s}^2 \cdot \text{A}} = \frac{\text{kg} \cdot \text{m}}{\text{s}^2 \cdot \text{A}^2} \cdot \text{A}^2 \cdot \frac{[K]}{\text{m}^2}$$

3. **Uprość równanie:**

   $$\frac{\text{kg}}{\text{s}^2 \cdot \text{A}} = \frac{\text{kg} \cdot [K]}{\text{s}^2 \cdot \text{m}^2}$$

   Ostatecznie mamy:

   $$[K] = \text{m}^2 \cdot \text{A}$$

W związku z tym wymiar wielkości $K$ to:

$$[K] = \text{m}^2 \cdot \text{A}$$

### 26. Określić wymiar wielkości K z wzoru dI/dt = -V/K

Aby określić wymiar wielkości $K$ z wzoru:
$$\frac{dI}{dt} = -\frac{V}{K}$$

możemy przekształcić ten wzór w następujący sposób:

$$K = -\frac{V}{\frac{dI}{dt}}$$

Ponieważ $K$ to wielkość fizyczna, musimy określić jednostki (wymiary) wszystkich pozostałych wielkości we wzorze.

1. **$I$ - prąd elektryczny**:

   - Jednostka: amper (A)

2. **$t$ - czas**:

   - Jednostka: sekunda (s)

3. **$V$ - napięcie elektryczne**:
   - Jednostka: wolt (V)

Wymiar prądu $I$ to $[I]$ = A

Wymiar czasu $t$ to $[t]$ = s

Wymiar napięcia $V$ to $[V]$ = V

Teraz musimy znaleźć wymiar wyrażenia $\frac{dI}{dt}$:

$$\frac{dI}{dt}$$

Wymiar $\frac{dI}{dt}$ to:

$$\left[\frac{dI}{dt}\right] = \frac{A}{s}$$

Ponieważ $\frac{dI}{dt} = -\frac{V}{K}$, możemy napisać:

$$\left[\frac{V}{K}\right] = \left[\frac{dI}{dt}\right]$$

Stąd:

$$\left[\frac{V}{K}\right] = \frac{A}{s}$$

Przekształcamy to, aby znaleźć wymiar $K$:

$$\left[K\right] = \frac{V}{\frac{A}{s}} = V \cdot \frac{s}{A} = \frac{V \cdot s}{A}$$

Ostatecznie:

$$[K] = \frac{V \cdot s}{A}$$

Tak więc wymiar wielkości $K$ to:

$$\left[K\right] = \frac{V \cdot s}{A}$$

### 27. Określic wymiar wielkości K = (LC)^-1/2

Aby określić wymiar wielkości $K = (LC)^{-1/2}$, musimy znać wymiary jednostkowe wielkości $L$ i $C$.

Załóżmy, że:

- $L$ to indukcyjność o wymiarze $[L] = [M][L]^2[T]^{-2}[I]^{-2}$, gdzie:

  - $[M]$ - masa,
  - $[L]$ - długość,
  - $[T]$ - czas,
  - $[I]$ - natężenie prądu.

- $C$ to pojemność o wymiarze $[C] = [M]^{-1}[L]^{-2}[T]^4[I]^2$.

Teraz obliczamy wymiar $LC$:

$$
[LC] = [L][C] = \left([M][L]^2[T]^{-2}[I]^{-2}\right) \left([M]^{-1}[L]^{-2}[T]^4[I]^2\right)
$$

Rozpisując to, mamy:

$$
[LC] = \left([M] \cdot [M]^{-1}\right) \left([L]^2 \cdot [L]^{-2}\right) \left([T]^{-2} \cdot [T]^4\right) \left([I]^{-2} \cdot [I]^2\right)
$$

Każdy z tych wyrażeń się upraszcza:

$$
[M] \cdot [M]^{-1} = [M]^0 = 1
$$

$$
[L]^2 \cdot [L]^{-2} = [L]^0 = 1
$$

$$
[T]^{-2} \cdot [T]^4 = [T]^2
$$

$$
[I]^{-2} \cdot [I]^2 = [I]^0 = 1
$$

Zatem:

$$
[LC] = [T]^2
$$

Teraz musimy znaleźć wymiar $(LC)^{-1/2}$:

$$
[(LC)^{-1/2}] = \left([T]^2\right)^{-1/2} = [T]^{-1}
$$

Więc wymiar wielkości $K$ to $[T]^{-1}$, co oznacza, że $K$ ma wymiar odwrotności czasu.

### 28. Określić wymiar wielkości k z wzory p=KT^4 gdzie P jest mocą na jednostkę powierzchni T tempertaurą.

Aby określić wymiar wielkości `k` w równaniu `p = kT^4`, gdzie `p` jest mocą na jednostkę powierzchni, a `T` temperaturą, musimy wyrazić jednostki każdej z tych wielkości i znaleźć jednostki `k`.

1. **Moc na jednostkę powierzchni (`p`)**:
   Moc (`P`) ma jednostki watów (`W`), a powierzchnia (`A`) ma jednostki metrów kwadratowych (`m^2`). Moc na jednostkę powierzchni `p` wyrażamy w `W/m^2`.

2. **Temperatura (`T`)**:
   Temperatura `T` ma jednostki kelwinów (`K`).

Równanie `p = kT^4` możemy wyrazić w jednostkach:

$$[p] = [k][T]^4 $$

Znamy jednostki `p` i `T`:

$$\frac{W}{m^2} = [k](K)^4 $$

Teraz możemy rozwiązać dla jednostek `k`:

$$[k] = \frac{W}{m^2 \cdot K^4} $$

Jednostki `W` (wat) możemy również wyrazić w jednostkach podstawowych układu SI:

$$W = \frac{J}{s} = \frac{kg \cdot m^2}{s^3} $$

Wstawiamy te jednostki do wyrażenia dla `k`:

$$[k] = \frac{\frac{kg \cdot m^2}{s^3}}{m^2 \cdot K^4} = \frac{kg \cdot m^2}{s^3 \cdot m^2 \cdot K^4} $$

Teraz upraszczamy jednostki:

$$[k] = \frac{kg}{s^3 \cdot K^4} $$

Ostateczny wymiar wielkości `k` to:

$$[k] = \frac{kg}{s^3 \cdot K^4} $$

Czyli, wielkość `k` ma wymiar:

$$\left[ k \right] = \frac{kg}{s^3 \cdot K^4} $$

### 29. Określić wymiar wielkości K z wzoru F = K m^2 / r^2 gdzie m jest masą

Aby określić wymiar wielkości $K$ z wzoru $F = K \frac{m^2}{r^2}$, musimy przeanalizować wymiary pozostałych wielkości w tym równaniu.

### Kroki:

1. **Zidentyfikowanie wymiarów podstawowych wielkości fizycznych:**

   - $F$ to siła, której wymiar to $[F] = MLT^{-2}$ (masa $\times$ długość / czas^2).
   - $m$ to masa, której wymiar to $[m] = M$.
   - $r$ to odległość, której wymiar to $[r] = L$.

2. **Zastosowanie wzoru do określenia wymiaru $K$:**

   Z równania $F = K \frac{m^2}{r^2}$, wyodrębniamy wymiar $K$:

   $$
   [F] = \left[ K \frac{m^2}{r^2} \right]
   $$

   Przekształćmy to równanie do postaci wymiarowej:

   $$
   MLT^{-2} = K \left( \frac{M^2}{L^2} \right)
   $$

3. **Rozwiązanie dla wymiaru $K$:**

   Przekształcamy równanie, aby znaleźć wymiar $K$:

   $$
   K = [F] \left( \frac{L^2}{M^2} \right)
   $$

   Podstawiamy wymiary siły:

   $$
   K = \left( MLT^{-2} \right) \left( \frac{L^2}{M^2} \right)
   $$

4. **Uproszczenie wymiarów:**

   $$
   K = MLT^{-2} \cdot \frac{L^2}{M^2}
   $$

   $$
   K = \frac{ML^3}{M^2T^2}
   $$

   $$
   K = \frac{L^3}{MT^2}
   $$

### Ostateczny wymiar wielkości $K$:

$$
[K] = L^3M^{-1}T^{-2}
$$

Wniosek: Wymiar wielkości $K$ w równaniu $F = K \frac{m^2}{r^2}$ jest $L^3M^{-1}T^{-2}$.

### 30. Określić wymiar wielkości K = F/q\*v

## Określić wymiar wielkości $K = \frac{F}{q \cdot v}$

Aby określić wymiar wielkości $K$, musimy określić wymiary jednostek $F$, $q$ oraz $v$, a następnie wyznaczyć wymiar $K$.

1. **Siła ($F$)**: W jednostkach układu SI, siła jest mierzona w niutonach (N).

   - $F$ = masa $\times$ przyspieszenie = $[M] \times [L \cdot T^{-2}]$
   - Wymiar siły: $[F] = [M \cdot L \cdot T^{-2}]$

2. **Ładunek ($q$)**: W układzie SI, ładunek elektryczny jest mierzony w kulombach (C).

   - Wymiar ładunku: $[q] = [I \cdot T]$

3. **Prędkość ($v$)**: Prędkość jest mierzona w metrach na sekundę (m/s).
   - Wymiar prędkości: $[v] = [L \cdot T^{-1}]$

Teraz wyznaczymy wymiar $K$:

$$ K = \frac{F}{q \cdot v} $$

Podstawiamy wymiary:

$$ [K] = \frac{[M \cdot L \cdot T^{-2}]}{[I \cdot T] \cdot [L \cdot T^{-1}]} $$

Upraszczamy wyrażenie:

$$ [K] = \frac{[M \cdot L \cdot T^{-2}]}{[I \cdot L \cdot T^{0}]} = \frac{[M \cdot L \cdot T^{-2}]}{[I]} = [M \cdot I^{-1} \cdot T^{-2}] $$

Ostatecznie otrzymujemy wymiar wielkości $K$ jako $[M \cdot I^{-1} \cdot T^{-2}]$.

### 31. Określić wymiar wielkości K z woru K _ dI/dt + I _ r = 0

Aby określić wymiar wielkości $K$ z równania $K \frac{dI}{dt} + I r = 0$, należy przyjrzeć się wymiarom poszczególnych wielkości w równaniu.

Oznaczenia:

- $K$ – stała, której wymiar mamy określić,
- $I$ – prąd elektryczny, jednostka [A] (ampery),
- $r$ – opór, jednostka [Ω] (omy),
- $t$ – czas, jednostka [s] (sekundy).

Równanie:
$$ K \frac{dI}{dt} + I r = 0 $$

1. Wymiar prądu ($I$) jest [A].
2. Wymiar oporu ($r$) jest [Ω], a wymiar omu [Ω] można wyrazić jako $\frac{V}{A}$, czyli $\frac{kg \cdot m^2}{A^2 \cdot s^3}$.
3. Wymiar czasu ($t$) jest [s].

Równanie można przekształcić, aby skupić się na wymiarach:
$$ K \frac{dI}{dt} = -I r $$

Wymiar po lewej stronie równania $K \frac{dI}{dt}$:

- $\frac{dI}{dt}$ to zmiana prądu w czasie. Wymiar prądu [A] podzielony przez wymiar czasu [s], daje wymiar $[A/s]$.
- Stąd, wymiar $K \frac{dI}{dt}$ to wymiar $K$ razy wymiar $[A/s]$.

Wymiar po prawej stronie równania $I r$:

- Wymiar $I$ jest [A].
- Wymiar $r$ jest [Ω].

Zrównujemy obie strony pod względem wymiarów:
$$ K \cdot \frac{A}{s} = A \cdot Ω $$

Aby obie strony były wymiarowo zgodne:
$$ [K] \cdot \frac{A}{s} = A \cdot \frac{kg \cdot m^2}{A \cdot s^3} $$

Wymiar $\frac{kg \cdot m^2}{A \cdot s^3}$ jest wymiarem ohma ($Ω$). Więc, aby wymiar $K$ był poprawny:
$$ [K] = \frac{kg \cdot m^2}{A \cdot s^2} $$

Podsumowując, wymiar wielkości $K$ to:
$$ [K] = \frac{kg \cdot m^2}{A \cdot s^2} $$

Jest to również wymiar henra ($H$), jednostki indukcyjności w układzie SI.

### 32. Określić wymiar wielkości K z woru E = (2piE_0)^-1 K/r (E = (2piE_0)^-1 Kr)

Aby określić wymiar wielkości $K$ z podanego wzoru $E = \frac{K}{2 \pi \epsilon_0 r}$, musimy rozważyć jednostki poszczególnych składników wzoru.

1. **E** - natężenie pola elektrycznego (jednostka: V/m lub $\frac{N}{C}$).
2. **$\epsilon_0$** - przenikalność elektryczna próżni (jednostka: $\frac{F}{m}$).
3. **r** - odległość (jednostka: m).

Wzór możemy przekształcić, aby wyizolować $K$:

$$ E = \frac{K}{2 \pi \epsilon_0 r} $$

Pomnóżmy obie strony równania przez $2 \pi \epsilon_0 r$:

$$ E \cdot 2 \pi \epsilon_0 r = K $$

Teraz sprawdźmy jednostki:

- **E** (natężenie pola elektrycznego): $\left[ \frac{V}{m} \right]$ lub $\left[ \frac{N}{C} \right]$
- **$\epsilon_0$** (przenikalność elektryczna próżni): $\left[ \frac{F}{m} \right] = \left[ \frac{C^2}{N \cdot m^2} \right]$ (ponieważ $F = \frac{C}{V}$ i $V = \frac{N \cdot m}{C}$)
- **r** (odległość): $[m]$
- **$2 \pi$** jest bezwymiarową stałą, więc jej nie bierzemy pod uwagę w obliczeniach jednostek.

Podstawiamy jednostki do wzoru:

$$ \left[ \frac{V}{m} \right] \cdot \left[ \frac{C^2}{N \cdot m^2} \right] \cdot [m] $$

Upraszczamy:

$$ \left[ \frac{V \cdot C^2 \cdot m}{N \cdot m^2} \right] $$
$$ \left[ \frac{V \cdot C^2}{N \cdot m} \right] $$

Wiemy, że $V = \frac{N \cdot m}{C}$, więc podstawiamy za $V$:

$$ \left[ \frac{N \cdot m \cdot C^2}{C \cdot N \cdot m} \right] $$
$$ \left[ \frac{C^2}{C} \right] $$
$$ \left[ C \right] $$

Zatem wymiar wielkości $K$ to jednostka ładunku elektrycznego, czyli:

$$ K \text{ ma wymiar } \left[ C \right] $$

### 33. Określić wymiar wielkości I = K\* t^2/2

Aby określić wymiar wielkości `I` w równaniu `I = (K * t^2) / 2`, musimy znać wymiary każdej z wielkości w równaniu.

Przyjmijmy, że:

- `K` jest jakąś stałą o wymiarze `[K]`.
- `t` to czas o wymiarze `[T]`.

Równanie można przekształcić do postaci:
$$ I = \frac{K \cdot t^2}{2} $$

Aby określić wymiar wielkości `I`, najpierw musimy określić wymiar `K`.

Załóżmy, że wymiar `K` wynosi `[K]`. Czas `t` ma wymiar `[T]`.

Podstawiając wymiary do równania:
$$ [I] = [K] \cdot [T]^2 $$

Czyli:
$$ [I] = [K] \cdot [T]^2 $$

Zatem, wymiar wielkości `I` zależy od wymiaru stałej `K` i kwadratu wymiaru czasu `t`. W szczególności, wymiar wielkości `I` jest kombinacją wymiaru `K` oraz kwadratu wymiaru czasu `t`.

W celu pełnego określenia wymiaru wielkości `I`, potrzebna jest informacja na temat wymiaru `K`. Jeśli `K` ma znany wymiar, to można dokładnie określić wymiar `I`. Na przykład, jeśli `K` miałoby wymiar `[M \cdot L^2 \cdot T^{-2}]` (wymiar energii), to wymiar `I` byłby:
$$ [I] = [M \cdot L^2 \cdot T^{-2}] \cdot [T]^2 = [M \cdot L^2] $$

W takim przypadku wymiar `I` byłby równy wymiarowi energii (masy razy kwadrat długości).

### 34. Określić wymiar wielkości K = I/U

Aby określić wymiar wielkości $K$ w zadaniu, należy skorzystać z analizy wymiarowej. Wiemy, że $K$ jest zdefiniowane jako stosunek prądu $I$ do napięcia $U$.

### Krok 1: Wymiary prądu $I$

Prąd elektryczny $I$ ma jednostkę ampera $[A]$.

### Krok 2: Wymiary napięcia $U$

Napięcie elektryczne $U$ ma jednostkę wolt $[V]$. Wolt można rozłożyć na jednostki podstawowe SI:
$$ 1 \, \text{V} = 1 \, \text{kg} \cdot \text{m}^2 \cdot \text{s}^{-3} \cdot \text{A}^{-1} $$

### Krok 3: Wyrażenie wielkości $K$

Wielkość $K$ to stosunek $I$ do $U$:
$$ K = \frac{I}{U} $$

### Krok 4: Podstawienie jednostek

Podstawmy jednostki prądu $I$ i napięcia $U$ do wyrażenia dla $K$:
$$ K = \frac{[A]}{[V]} = \frac{[A]}{[\text{kg} \cdot \text{m}^2 \cdot \text{s}^{-3} \cdot \text{A}^{-1}]} $$

### Krok 5: Upraszczanie jednostek

Uprośćmy powyższy wyrażenie:
$$ K = \frac{[A] \cdot \text{A}}{[\text{kg} \cdot \text{m}^2 \cdot \text{s}^{-3}]} = \frac{[A]^2}{[\text{kg} \cdot \text{m}^2 \cdot \text{s}^{-3}]} $$

### Krok 6: Wyrażenie wymiarów $K$

Wymiary wielkości $K$ można wyrazić jako:
$$ [K] = \frac{[A]^2}{[\text{kg} \cdot \text{m}^2 \cdot \text{s}^{-3}]} $$

### Ostateczny wymiar wielkości $K$

Ostatecznie, wymiar wielkości $K$ jest równy:
$$ [K] = \text{A}^2 \cdot \text{kg}^{-1} \cdot \text{m}^{-2} \cdot \text{s}^3 $$

Zatem wymiar wielkości $K$ to:
$$ \boxed{\text{A}^2 \cdot \text{kg}^{-1} \cdot \text{m}^{-2} \cdot \text{s}^3} $$

### 35. Określić wymiar wielkości K = L \* I^2/2

Aby określić wymiar wielkości $K$ dla wzoru $K = \frac{L \cdot I^2}{2}$, musimy rozpatrzyć wymiary poszczególnych wielkości występujących we wzorze.

1. **L** - Indukcyjność, której wymiar to henry [H]. W jednostkach podstawowych SI henry można wyrazić jako:

   $$
   [H] = \frac{[kg \cdot m^2]}{[A^2 \cdot s^2]}
   $$

2. **I** - Prąd elektryczny, którego wymiar to amper [A].

Przekształcamy wzór na $K$:

$$
K = \frac{L \cdot I^2}{2}
$$

Ponieważ $\frac{1}{2}$ jest tylko współczynnikiem liczbowym bezwymiarowym, nie wpływa na wymiar wielkości $K$.

Obliczamy wymiar $K$:

$$
[L \cdot I^2] = \left[ \frac{kg \cdot m^2}{A^2 \cdot s^2} \cdot A^2 \right]
$$

Skracamy jednostki:

$$
[kg \cdot m^2 \cdot A^2 / (A^2 \cdot s^2)] = [kg \cdot m^2 / s^2]
$$

Ostateczny wymiar $K$ to:

$$
K = [kg \cdot m^2 / s^2]
$$

Wymiar ten odpowiada energii (czyli np. dżulowi [J]), ponieważ:

$$
[J] = [kg \cdot m^2 / s^2]
$$

Tak więc wielkość $K$ ma wymiar energii.

### 36. Określić wymiar wielkości K = Q / A* I (K = Q / A * 1 )

Aby określić wymiar wielkości $K$, musimy znać wymiary poszczególnych wielkości wchodzących w skład tego wyrażenia: $Q$, $A$ oraz $I$.

1. **Q** - ładunek elektryczny

   - Wymiar: [Q] = [C] (Coulomb)
   - W jednostkach podstawowych SI: [Q] = [A] [s] (amperosekunda)

2. **A** - pole powierzchni

   - Wymiar: [A] = [m²] (metr kwadratowy)

3. **I** - natężenie prądu
   - Wymiar: [I] = [A] (amper)

Podstawiając te wymiary do wzoru $K = \frac{Q}{A \cdot I}$:

$$ K = \frac{[Q]}{[A] \cdot [I]} $$

Teraz zamieńmy te wymiary na jednostki podstawowe:

$$ K = \frac{[A \cdot s]}{[m²] \cdot [A]} $$

Ampery (A) się skrócą:

$$ K = \frac{s}{m²} $$

Zatem wymiar wielkości $K$ to:

$$ K = [s \cdot m^{-2}] $$

Oznacza to, że $K$ ma wymiar czasu podzielonego przez powierzchnię.

### 37. Określic wymiar wielkości Kh = mu*0 * I _ n _ h

Aby określić wymiar wielkości `K_h`, musimy najpierw zrozumieć wymiary poszczególnych wielkości w równaniu:

$$ K_h = \mu_0 \cdot I \cdot n \cdot h $$

Gdzie:

- $\mu_0$ to przenikalność magnetyczna próżni, której wymiar jest $[H/m]$ (henry na metr).
- $I$ to prąd elektryczny, którego wymiar jest $[A]$ (amper).
- $n$ to liczba zwojów na jednostkę długości, której wymiar jest $[1/m]$ (odwrotność metra).
- $h$ to wysokość, której wymiar jest $[m]$ (metr).

Teraz możemy znaleźć wymiary $K_h$ przez podstawienie wymiarów każdej z tych wielkości:

$$ [K_h] = [\mu_0] \cdot [I] \cdot [n] \cdot [h] $$

Podstawiając odpowiednie wymiary, mamy:

$$ [K_h] = \left[ \frac{H}{m} \right] \cdot [A] \cdot \left[ \frac{1}{m} \right] \cdot [m] $$

Teraz upraszczamy ten wyrażenie, pamiętając, że henry (H) ma wymiar $[H] = \frac{kg \cdot m^2}{A^2 \cdot s^2}$:

$$ [K_h] = \left[ \frac{kg \cdot m^2}{A^2 \cdot s^2 \cdot m} \right] \cdot [A] \cdot \left[ \frac{1}{m} \right] \cdot [m] $$

Teraz upraszczamy wszystkie jednostki:

$$ [K_h] = \left[ \frac{kg \cdot m}{A^2 \cdot s^2} \right] \cdot [A] \cdot \left[ \frac{1}{m} \right] \cdot [m] $$

Zauważmy, że metry się redukują i ampery również (jedna jednostka A w liczniku i jedna w mianowniku):

$$ [K_h] = \frac{kg \cdot m}{A \cdot s^2} $$

Zatem wymiar wielkości $K_h$ jest:

$$ [K_h] = \frac{kg \cdot m}{A \cdot s^2} $$

### 38. Określić wymiar wielkości K z wzoru V = (2piE_0)^-1 Q/r^3

Aby określić wymiar wielkości $K$ z wzoru $V = (2 \pi E_0)^{-1} \frac{Q}{r^3}$, musimy przeanalizować jednostki poszczególnych wielkości występujących w tym wzorze.

Zacznijmy od jednostek każdej z wielkości:

1. $V$ - potencjał elektryczny:

   - Jednostka: volt (V)
   - Wymiar: $[V] = \frac{kg \cdot m^2}{A \cdot s^3}$

2. $E_0$ - przenikalność elektryczna próżni:

   - Jednostka: farad na metr (F/m)
   - Wymiar: $[E_0] = \frac{A^2 \cdot s^4}{kg \cdot m^3}$

3. $Q$ - ładunek elektryczny:

   - Jednostka: coulomb (C)
   - Wymiar: $[Q] = A \cdot s$

4. $r$ - odległość:
   - Jednostka: metr (m)
   - Wymiar: $[r] = m$

Teraz przekształcimy wzór, aby wyrazić $K$ w sposób jawny. Przypomnijmy sobie wzór:

$$ V = \left( 2 \pi E_0 \right)^{-1} \frac{Q}{r^3} $$

Oznacza to, że:

$$ K = \left( 2 \pi E_0 \right)^{-1} $$

Wymiar $K$ jest równy wymiarowi $\left( 2 \pi E_0 \right)^{-1}$.

Sprawdźmy jednostki $\left( 2 \pi E_0 \right)^{-1}$:

$$ \left[ K \right] = \left[ \left( 2 \pi E_0 \right)^{-1} \right] = \left( 2 \pi \right)^{-1} \left[ E_0 \right]^{-1} $$

Jednostka $2 \pi$ jest bezwymiarowa, więc możemy skupić się na $E_0$:

$$ \left[ K \right] = \left[ E_0 \right]^{-1} = \left( \frac{A^2 \cdot s^4}{kg \cdot m^3} \right)^{-1} $$

Odwrócenie jednostek $E_0$ daje nam:

$$ \left[ K \right] = \frac{kg \cdot m^3}{A^2 \cdot s^4} $$

Zatem wymiar wielkości $K$ jest:

$$ \left[ K \right] = \frac{kg \cdot m^3}{A^2 \cdot s^4} $$

I to jest poszukiwany wymiar wielkości $K$.

### 39. Określić wymiar wielkości K = lambda = \* T gdzie T jest temeratura

Aby określić wymiar wielkości $K$ w równaniu $K = \lambda \cdot T$, gdzie $\lambda$ to współczynnik a $T$ to temperatura, musimy najpierw zrozumieć wymiary poszczególnych składników równania.

Zakładamy, że $T$ to temperatura wyrażona w kelwinach (K). W takim przypadku, wymiar temperatury $T$ to [K].

Jeśli nie jest podane, czym dokładnie jest $\lambda$, możemy przyjąć, że jest to współczynnik mający swoje własne wymiary. Aby $K$ miało wymiar fizyczny, współczynnik $\lambda$ musi mieć odpowiedni wymiar, który po przemnożeniu przez wymiar temperatury $T$ da nam wymiar $K$.

Przyjmijmy, że wymiar $K$ to [K]. Wtedy wymiar współczynnika $\lambda$ możemy wyznaczyć z równania:
$$ [K] = [\lambda] \cdot [T] $$

Skoro wymiar $T$ to [K], mamy:
$$ [K] = [\lambda] \cdot [K] $$

Aby równanie to było prawdziwe, wymiar $\lambda$ musi być wymiarem bezwymiarowym, czyli [1].

Zatem wymiar wielkości $K$ w równaniu $K = \lambda \cdot T$ przy założeniu, że $\lambda$ jest bezwymiarowe, będzie:
$$ [K] = [K] $$

Jeżeli $\lambda$ miałoby inny wymiar, np. $\lambda$ miałoby wymiar mocy (Watts, W), wtedy wymiar $K$ zmieniłby się odpowiednio. Ale przy założeniu, że $\lambda$ jest bezwymiarowe, wymiar $K$ będzie równy wymiarowi temperatury $T$, czyli [K].

### 40. Określić wymiar wielkości lambda - c \* t gdzie c jest prędkoscią swiatła, lambda długością
