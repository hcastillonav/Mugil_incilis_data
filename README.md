# Mugil incilis data
# Morphometric Dataset of *Mugil incilis* from Three Estuarine Systems of the Colombian Caribbean

This dataset supports the study titled **"Stock identification of the striped mullet Mugil incilis (Actinopterygii: Mugilidae) using truss networks, morphometric relationships, and probabilistic models in three regions of the Colombian Caribbean"**, submitted to *Fisheries Research*.

## 📁 Data Description

The dataset (`Mugil_incilis_dataset.Rdata`) contains a single R object: a `data.frame` named `datos`, which includes morphometric and biological information for **196 individuals** of *Mugil incilis* collected from three estuarine systems in northern Colombia:

- **CGSM**: Ciénaga Grande de Santa Marta  
- **CVir**: Ciénaga de la Virgen  
- **CCera**: Ciénaga de la Caimanera

### 📊 Variables

| Variable          | Description                                               |
|-------------------|-----------------------------------------------------------|
| `ID`              | Unique identifier for each specimen                      |
| `CÓDIGO`          | Sample code                                               |
| `Arte_pesca`      | Fishing gear used (e.g., *transmallo*)                   |
| `Fecha_captura`   | Capture date (numeric format from Excel)                 |
| `Fecha.medición`  | Date of measurement                                       |
| `Lugar`           | Sampling site: CVir, CGSM, or CCera                      |
| `Especie`         | Species (all: *Mugil incilis*)                           |
| `LT`              | Total length (mm)                                        |
| `LH`              | Fork length (mm)                                         |
| `LE`              | Standard length (mm)                                     |
| `PT`              | Total weight (g)                                         |
| `PE`              | Eviscerated weight (g)                                   |
| `Sexo`            | Sex (H: female, M: male)                                 |
| `EM`              | Maturity stage                                           |
| `PG`              | Gonad weight (g)                                         |
| `Observaciones`   | Field notes or observations                              |
| `X-Y`             | Truss distances between anatomical landmarks 1 to 12     |

A total of **33 morphometric distances** (e.g., `1-4`, `5-8`, `10-12`) were measured using a truss network system based on homologous landmarks.

## 🔎 Usage

This dataset was used to:
- Fit length–weight and allometric models
- Calculate condition factors
- Analyze truss network morphometrics
- Apply multivariate and machine learning models for stock discrimination

## 📦 How to load the dataset in R

```r
load("Mugil_incilis_dataset.Rdata")
str(datos)
```

## 📄 Citation

Please cite this dataset as:

> Carrillo-Castro, K.E., del Monte-Luna, P., Cardenas-Uribe, C., Castillo-Navarro, H., 2025. Stock identification of the striped mullet Mugil incilis (Actinopterygii: Mugilidae) using truss networks, morphometric relationships, and probabilistic models in three regions of the Colombian Caribbean. Dataset. Zenodo. https://doi.org/10.5281/zenodo.16115950

## 📬 Contact

**Corresponding Author**:  
Harold Castillo Navarro  
Universidad del Sinú, Seccional Cartagena  
Email: harold.castillo@unisinu.edu.co  
ORCID: [0000-0002-2824-0861](https://orcid.org/0000-0002-2824-0861)
