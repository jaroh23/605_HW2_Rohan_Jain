# 605_HW2_Rohan_Jain

https://github.com/allegroai/clearml/blob/master/examples/frameworks/pytorch/pytorch_mnist.pyLinks to an external site.

Links to an external site.https://app.clear.ml/dashboardLinks to an external site.

- Setup/configure ClearML on your local machine
- Train a PyTorch CNN model to accurately predict items on Fashion MNIST dataset
- Programmatically create a task, connect to ClearML and log training results

Feel free to use requirements.txt file content below for guidance:
clearml>=1.14.4
jsonschema==3.2.0 ; python_version <= '3.5'
matplotlib
pytorch-ignite
tensorboard<=2.11.2 ; python_version <= '3.7'
tensorboard>2.11.2 ; python_version > '3.7'
tensorboardX
torch>=1.1.0
torchvision>=0.3.0
tqdm
protobuf==3.20.* ; python_version <= '3.7'
protobuf>=4.21.1 ; python_version > '3.7' 

Also, feel free to use the parameters below in your model training:
batch size: 64
Number of epochs: 100
learning rate: 0.01
SGD momentum: 0.5
no cuda: True
log interval: 10

Upon completion of the training, provide the screenshots on ClearML web view for the following items in your report:

- Configuration arguments
- The final line of the console output, where accuracy and loss are provided. Ensure that accuracy reaches at least 90% on test set. 
- Scalars, i.e. test, and train accuracy and loss over iterations along with machine utilization (cpu usage, io read mbs, etc.) over iterations
