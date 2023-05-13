# AutoGluon
Open source AutoGluon library for AutoML 
. In January 2020, AWS launched an open-source library called AutoGluon the library behind Sagemaker Autopilot.
. AutoGluon allows for quick prototyping of AI/ML models using few simple lines of code. 
. Autogluon works with text, image and tabular datasets. 
. No need for expert level knowledge to train/test AI/ML models in Autogluon.
. Allows for automatic hyperparameters tuning and model selection. 
Check this out: https://auto.gluon.ai/stable/index.html
Excellent Article: https://aws.amazon.com/blogs/opensource/machine-learning-with-autogluon-an-open-source-automl-library/
Excellent Article 2: https://www.philschmid.de/getting-started-with-automl-and-aws-autogluon
-


AutoGluon is modularized into sub-modules for:
Tabular
text 
Images
Install a sub-module using: 
				python3 -m pip install <submodule>

<submodule> may be one of the following options:
autogluon.tabular - tabular data (TabularPredictor)
autogluon.vision - computer vision (ImagePredictor, ObjectDetector)
autogluon.text - natural language processing (TextPredictor)
autogluon.core - only core functionality (example: hyperparameter tuning of arbitrary code/models).
autogluon.features - feature generation/preprocessing pipelines (Tabular data).
![image](https://github.com/apatidar0/AutoGluon/assets/48124727/6a1e710c-6333-4f0c-8b0f-69288bfd2c5c)

