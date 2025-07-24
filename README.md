# DTA-Tool
![软件图](https://github.com/Saillxl/DTA-Tool/blob/main/assets/DTA-Tool.png)
**DTA-Tool** is an integrated and user-friendly toolkit designed for **drug–target binding affinity (DTA) prediction**. It brings together six classical and state-of-the-art sequence-based DTA prediction algorithms, enabling researchers and developers to efficiently estimate binding affinity values for drug–target pairs.

👉 **[Download here](https://drive.google.com/file/d/1jRyARZn2OrgsFQ3F1Vwra3p6qGLyk11t/view?usp=sharing)**

## 🔬 Key Features

- **Integrated Algorithms**: Includes six representative and widely used DTA prediction models (e.g., DeepDTA, GraphDTA, DGraphDTA, FusionDTA, HGRL-DTA, NHGNN-DTA).
- **Cold Start Support**: Enables data splitting strategies tailored to cold start scenarios, allowing rigorous evaluation of model generalization to unseen drugs or targets.
- **End-to-End Pipeline**: Supports the full workflow — from data generation and preprocessing, to model training, evaluation, and single-pair prediction.
- **Default Models**: Provides pre-trained default parameter files for each algorithm, allowing quick use without needing to train from scratch.
- **Flexible Prediction**: Offers single-pair prediction functionality for rapid assessment of drug–target interaction strength based on SMILES and protein sequences.

## 📦 Modules

- **Data Generation**: Configure dataset splits (training, validation, test) and select cold start modes.
- **Model Training**: Train models on customized datasets and store the parameters.
- **Model Evaluation**: Assess model performance using metrics like RMSE, MSE, Pearson correlation, and Concordance Index (CI).
- **Single-pair Prediction**: Predict the binding affinity of a specific drug–target pair using trained or default models.

## 📈 Applications

DTA-Tool provides computational support for:

- Virtual screening in early-stage drug discovery  
- Target identification and prioritization  
- Performance benchmarking across DTA prediction algorithms
