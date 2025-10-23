# Odpowiedzi na pytania

### 1. Scharakteryzuj przelotki zagrzebane oraz ślepe.

* **[span_0](start_span)Przelotki zagrzebane (Buried vias)**: Łączą wyłącznie wewnętrzne warstwy obwodu drukowanego[span_0](end_span).
* **[span_1](start_span)Przelotki ślepe (Blind vias)**: Łączą najbliższe warstwy (dwie lub trzy), zaczynając od warstwy zewnętrznej[span_1](end_span).

### 2. Dlaczego standardowe przelotki PTH nie nadają się jako Via-in-Pad?

[span_2](start_span)Dokumenty wskazują, że standardowe przelotki PTH (Through-Hole Technology) są niewypełnione ("No fill")[span_2](end_span). [span_3](start_span)Natomiast przelotki rekomendowane do stosowania w technologii Via-in-Pad są opisane jako wypełnione i zamknięte ("Filled and Capped")[span_3](end_span).

### 3. Jaka różnica jest pomiędzy prepregiem a rdzeniem?

* **[span_4](start_span)Rdzeń (Core)**: Jest to laminat (substrat), który ma już fabrycznie naniesioną warstwę miedzianą po obu stronach[span_4](end_span).
* **Prepreg**: To półprodukt laminatu. [span_5](start_span)Składa się z włókien kompozytowych nasączonych żywicą i jest wykorzystywany do łączenia (prasowania) kolejnych rdzeni w obwodach wielowarstwowych[span_5](end_span).

### 4. Jaki typ padu NSMD czy SMD jest rekomendowany dla układów BGA i dlaczego?

[span_6](start_span)Dla układów BGA rekomendowany jest typ padu **NSMD (Non-Solder Mask Defined)**[span_6](end_span). [span_7](start_span)W padzie typu NSMD, otwór w soldermasce jest *większy* niż miedziany pad[span_7](end_span). [span_8](start_span)Typ SMD (Solder Mask Defined), gdzie soldermaska nachodzi na pad i definiuje jego krawędź, jest oznaczony jako nierekomendowany[span_8](end_span).

### 5. Do czego służą fiduciale i czym różnią się fiduciale globalne od lokalnych?

[span_9](start_span)Fiduciale to punkty referencyjne na płytce PCB, które są wykorzystywane przez automaty montażowe (Pick&Place) do kalibracji położenia elementów[span_9](end_span).

* **[span_10](start_span)Fiducial globalny**: Służy do kalibracji pozycji *całej płytki*[span_10](end_span).
* **[span_11](start_span)Fiducial lokalny**: Służy do *precyzyjnej* kalibracji pozycji układów o małym rastrze (gęsto rozmieszczonych wyprowadzeniach)[span_11](end_span).
