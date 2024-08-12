# Machine Learning Pipeline with Scikit-learn

Machine learning pipelines make it easier to reproduce experiements. By defining the sequence of steps and their parameters in a pipeline, you can recreate the entire process exactly, ensuring consistent results
In other words, it's a broad term for automated preprocessing pipeline

![Machine Learning Pipeline](https://static.designandreuse.com/img20/20230306c_1.jpg)

## Why it is so important?
These scripts are to ensure reliability, scablability, error-free and FAST!

Machine learning pipeline example flow:
* Downloads data from AWS S3
* It checks for erros and outliers
* Removes bad data and emails a data report log
* Trains the model
* Tests the model
* Model Analysis and examine its performance
* Upload to S3

This is an example of preprocessing pipeline
[machine-learning-pipeline.ipynb](https://github.com/jonatng/jonatng/blob/master/machine-learning-pipeline.ipynb)

To find out more, check out the documentation
[Scikit-Learn make_pipeline](https://scikit-learn.org/stable/modules/generated/sklearn.pipeline.make_pipeline.html)
