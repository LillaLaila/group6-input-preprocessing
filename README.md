# Gruppuppgift Deep Learning – Input & Preprocessing

Detta projekt undersöker hur Input & Preprocessing påverkar en CNN-modells förmåga att generalisera till ny data.

Projektet genomfördes inom kursen Deep Learning och använder datasetet Fashion MNIST från Keras.

## Projektets syfte
Målet med projektet var att:
- Bygga en baseline-modell
- Testa olika tekniker inom input & preprocessing
- Jämföra modellernas resultat

## Dataset
Fashion MNIST består av:
- 70 000 svartvita bilder
- 10 olika klasser av kläder och skor
- bildstorlek 28x28 pixlar

Datasetet delades upp i:
- träningsdata
- validation-data
- testdata

## Modeller och experiment
Projektet testade:
- Baseline-modell
- Normalisering
- Standardisering
- Låg upplösning
- Center Crop
- Compressed
- Weak Augmentation
- Strong Augmentation
- MixUp
- Dense

## Resultat
Modellerna jämfördes med:
- accuracy
- loss
- träningskurvor

Vi såg att preprocessing har stor påverkan på deep learning-modeller. 
Samma modell kan ge väldigt olika resultat beroende på hur datan förbereds. Av alla testade förändringar (experiment) gav normalisering bäst resultat i vårt projekt och gjorde träningen mer stabil. 

## Miljö
- **Python:** 3.13.7
- **Paket:** `Pandas`, `Numpy`, `Matplotlib`, `Tensorflow`, `Scikit-learn` (se `requirements.txt`)

## Kom igång
```bash
# klona projektet
git clone https://github.com/LillaLaila/group6-input-preprocessing.git

# Skapa och aktivera virtuell moljö
python -m venv .venv

# installera beroenden
python -m pip install -r requirements.txt

```

## Arbetsfördelning
Projektet genomfördes av:

- Milda Kopmane
- Nadine Knoop
- Henry Che
