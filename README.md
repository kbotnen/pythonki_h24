# pythonki_h24
Midlertidig repositorie for kurs desember 2024

# Oppgave(r) - Kommer litt og litt...

## Oppgave 1 - Pandas, Excel og Kaggle
Når vi jobber med KI er det ofte fordi vi ønsker å løse et problem basert på et, eller flere, sett med data. For å kunne behandle data må vi kunne gjøre det tilgjengelig for koden vår.

- Opprett bruker på kaggle.com.
- Opprett et nytt datasett og last opp valgfritt datasett (.csv eller .xslx). Eventuelt kan du bruke filen KPI_tabell.xlsx som ligger i repoet her (kode/data/excel/KPI_tabell.xlsx)
- Lag en ny notebook.
- Skriv kode for å laste inn dataene fra datasettet.
- Skriv kode for å inspisere dataene (liste ut kolonner, rader med mer).

Legge til et datasett i Kaggle: [https://youtu.be/YHJ6t958gjw](https://youtu.be/YHJ6t958gjw)

Åpne og skrive excelfiler i Kaggle: [https://youtu.be/RoA367CZcU8](https://youtu.be/RoA367CZcU8)

## Oppgave 2 - Scikit-learn - Sett opp, tren og bruk en modell
Gitt det innebygde Iris datasettet, prøv å klassifiser følgende observasjon: iris_observation = [5.5, 2.9, 4.0, 1.4]

Dette er altså en observasjon med følgende egenskaper: sepal_length_cm = 5.5, sepal_width_cm = 2.9, petal_length_cm = 4.0, petal_width_cm = 1.4.

- Lag en ny notebook.
- Last inn Iris datasettet.
- Sett opp en egnet modell. Vi brukte LogisticRegression i gjennomgangen på mandag.
- Tren modellen (.fit())
- Bruk modellen til å gjøre prediksjon på observasjonen over (.predict())

Bonus oppgave: Kan du gjøre et sannsynlighetsestimat på den trente modellen? Hvor sikker er den på at den har gitt deg rett klassifisering?

## Oppgave 3 - Tensorflow og Teachable machine - Tren og bruk en modell
Vi kan bruke Google sin Teachable Machine [https://teachablemachine.withgoogle.com/train/image](https://teachablemachine.withgoogle.com/train/image) til å trene en TensorFlow modell som gjenkjenner objekter. Prøv å bruke denne til å lage en enkel modell som kan brukes for å gjenkjenne objekter i et pythonprogram.

- Sett opp et kjøremiljø lokalt på maskinen (virtual environment eller conda environment).
- Aktiver og installer nødvendige biblioteker i dette kjøremiljøet.
- Skriv kode som kan laste inn og bruke resultatet som du laget i Teachable Machine.

*Grunnet en feil / utdatert eksport fra Teachable machine må en sette opp pythonmiljøet med en eldre versjon av python og TensorFlow.*

    % conda create -n tensorflow python=3.11
    % conda activate tensorflow
    % pip install tensorflow==2.13
    % pip install opencv-python

*Med miljøet beskrevet over vil det være mulig å laste inn TensorFlow -> Keras (h5) som er anbefalt eksportformat fra Teachable Machine.*

Hvordan bruke Teachable Machine for å trene en KI modell med egne bilder: [https://youtu.be/ie9d9VUnKAc](https://youtu.be/ie9d9VUnKAc)
