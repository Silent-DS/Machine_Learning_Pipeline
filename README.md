# Silent DS Machine Learning Pipeline

## Project Overview
This project implements a complete machine learning pipeline, including data ingestion, validation, transformation, model training, and evaluation.

## Directory Structure
```
└── silent-ds-machine_learning_pipeline/
    ├── README.md
    ├── LICENSE
    ├── app.py
    ├── data.zip
    ├── main.py
    ├── params.yaml
    ├── requirements.txt
    ├── schema.yaml
    ├── template.py
    ├── test.py
    ├── config/
    │   └── config.yaml
    ├── data/
    │   └── winequality-red.csv
    ├── research/
    │   ├── Experiments.ipynb
    │   ├── Step_01_data_ingestion.ipynb
    │   ├── Step_02_data_validation.ipynb
    │   ├── Step_03_data_transformation.ipynb
    │   ├── Step_04_model_trainer.ipynb
    │   └── Step_05_model_evaluation.ipynb
    ├── src/
    │   └── MLProject/
    │       ├── __init__.py
    │       ├── components/
    │       │   ├── __init__.py
    │       │   ├── data_ingestion.py
    │       │   ├── data_transformation.py
    │       │   ├── data_validation.py
    │       │   ├── model_evaluation.py
    │       │   └── model_trainer.py
    │       ├── config/
    │       │   ├── __init__.py
    │       │   └── configuration.py
    │       ├── constants/
    │       │   └── __init__.py
    │       ├── entity/
    │       │   ├── __init__.py
    │       │   └── config_entity.py
    │       ├── pipeline/
    │       │   ├── Step_01_data_ingestion.py
    │       │   ├── Step_02_data_validation.py
    │       │   ├── Step_03_data_transformation.py
    │       │   ├── Step_04_model_trainer.py
    │       │   ├── Step_05_model_evaluation.py
    │       │   ├── __init__.py
    │       │   └── prediction.py
    │       └── utils/
    │           ├── __init__.py
    │           └── common.py
    └── templates/
        └── index.html
```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Silent-DS/Machine_Learning_Pipeline.git
   ```
2. Create a virtual environment:
   ```bash
   python -m venv .venv
   ``` 
3. Activate the virtual environment:
   - On Windows:
     ```bash
     .venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source .venv/bin/activate
     ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Run the main script to start the pipeline:
```bash
python main.py
```

## License
This project is licensed under the MIT License.

## Contributors
- Silent DS
