AutoGluon
AutoGluon is an open-source AutoML library developed by AWS and used as the backbone for Sagemaker Autopilot. It allows for quick prototyping of AI/ML models with just a few lines of code. The library can work with text, image, and tabular datasets, and does not require expert-level knowledge to train/test AI/ML models. Additionally, AutoGluon allows for automatic hyperparameter tuning and model selection.

Check out the following resources to learn more:

AutoGluon official website
Excellent Article on AWS Blog
Getting Started with AutoML and AWS AutoGluon
Usage
AutoGluon is modularized into sub-modules for different types of data. You can install a sub-module using the following command:

python3 -m pip install <submodule>
Here are the available sub-modules:

autogluon.tabular: for tabular data (TabularPredictor)
autogluon.vision: for computer vision (ImagePredictor, ObjectDetector)
autogluon.text: for natural language processing (TextPredictor)
autogluon.core: for core functionality (e.g., hyperparameter tuning of arbitrary code/models)
autogluon.features: for feature generation/preprocessing pipelines (Tabular data)
AutoGluon architecture

License
AutoGluon is released under the Apache 2.0 License. See the LICENSE file for details.


