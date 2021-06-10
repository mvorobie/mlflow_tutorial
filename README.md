# mlflow_tutorial

Re-implementation of the following tutorial, with some small code improvements:
https://www.mlflow.org/docs/latest/tutorials-and-examples/tutorial.html

To reproduce the training, clone the repo and run from the folder:
1. conda env create -f conda.yaml
1. conda activate mlflow_tutorial
1. python train.py {alpha} {l1_ratio}

You can then follow the last part of the tutorial to check your training in mlflow GUI and deploy the model as an endpoint


