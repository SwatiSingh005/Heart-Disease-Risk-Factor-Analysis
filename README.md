#Heart Disease Risk Factor Analysis

Exploratory data analysis on a 999-record heart disease dataset, covering risk factor distribution, BMI, age trends, and feature correlations.

Files

FileDescriptionheart.csvRaw dataset (999 rows, 11 columns)heart_analysis.ipynbMain analysis notebook

Dataset Columns

ColumnTypeDescriptionGeneral_HealthCategoricalSelf-rated health (Excellent → Poor)ExerciseYes/NoRegular physical activityDepressionYes/NoDiagnosed depressionDiabetesYes/NoDiagnosed diabetesSexCategoricalMale / FemaleAge_CategoryCategoricalAge group (18-24 to 80+)Weight_(kg)FloatBody weight in kgBMIFloatBody Mass IndexSmoking_HistoryYes/NoHistory of smokingAlcohol_ConsumptionYes/NoAlcohol useHeart_DiseaseYes/NoTarget variable

Key Findings


Overall heart disease rate: 14.1%
Smokers have nearly 2× higher HD rate (19.8%) vs non-smokers (10.4%)
Diabetics show 22.6% HD rate vs 11.3% in non-diabetics
Poor self-rated health correlates with 43.1% HD rate; Excellent health only 0.9%
No cases under age 50; rate rises sharply after 60
HD patients average ~5 kg heavier (85.1 kg vs 80.3 kg)


Requirements

pandas
numpy
matplotlib
seaborn
scikit-learn

Install with:

bashpip install pandas numpy matplotlib seaborn scikit-learn

Usage

bashjupyter notebook heart_analysis.ipynb
