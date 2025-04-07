# grammar-scoring-project

## Approach

### 1. Data Exploration
- Analyzed the distribution of grammar scores in the training data
- Examined audio properties (duration, sample rate, etc.)
- Visualized waveforms and spectrograms to understand audio characteristics

### 2. Feature Extraction
Extracted several categories of audio features:
- Basic features: duration, zero-crossing rate
- Spectral features: centroid, bandwidth, rolloff
- MFCCs (Mel-frequency cepstral coefficients)
- Chroma features
- Mel spectrogram statistics
- Rhythm features: tempo, beats
- Speech-specific features: harmonics and percussive elements

### 3. Feature Analysis
- Identified features with highest correlation to grammar scores
- Filled missing values and standardized features where appropriate
- Visualized feature importance and relationships

### 4. Model Development
Experimented with several regression models:
- Linear Regression (baseline)
- Ridge Regression
- Random Forest
- Gradient Boosting
- XGBoost
- Neural Network (was just trying if a simple nn would perform in this problem)

## Files
- All code is available in the `main.ipynb` Jupyter notebook
- The `predictions` directory contains CSV files with predictions from all models I tested
