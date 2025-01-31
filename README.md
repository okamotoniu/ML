<div id="top"></div>
<h2 align="center">COMP7250<br/> Data augmentation for classifying CIFAR10 images using ResNet</h2>
<p align="center">
    Design experiments to evaluate the effectiveness of data augmentation to improve the training performance and to reduce overfitting for image classification tasks based on the ResNet18. 
</p>


### Built With

* [Colab](https://colab.research.google.com/)
* [pyTorch](https://pytorch.org/)
* [TensorBroad](https://www.tensorflow.org/tensorboard)

### Model
* [ResNet18](https://medium.com/@14prakash/understanding-and-implementing-architectures-of-resnet-and-resnext-for-state-of-the-art-image-cf51669e1624)
### Dataset
* [CIFAR10](http://www.cs.toronto.edu/~kriz/cifar.html)





<!-- GETTING STARTED -->
## Getting Started

I recommend to use Colab for running this project, bacause Colab provide free GPU which will save the training time.

### Using a GPU for faster training

You can use a Graphics Processing Unit (GPU) to train your models faster if your execution platform is connected to a GPU manufactured by NVIDIA.<br/> Follow these instructions to use a GPU on the platform of your choice:
1. Google Colab: Use the menu option "Runtime > Change Runtime Type" and select "GPU" from the "Hardware Accelerator" dropdown.
2. Kaggle: In the "Settings" section of the sidebar, select "GPU" from the "Accelerator" dropdown. Use the button on the top-right to open the sidebar.
3. Binder: Notebooks running on Binder cannot use a GPU, as the machines powering Binder aren't connected to any GPUs.
4. Linux: If your laptop/desktop has an NVIDIA GPU (graphics card), make sure you have installed the NVIDIA CUDA drivers.
5. Windows: If your laptop/desktop has an NVIDIA GPU (graphics card), make sure you have installed the NVIDIA CUDA drivers.
6. macOS: macOS is not compatible with NVIDIA GPUs
<br/>
If you do not have access to a GPU or aren't sure what it is, don't worry, you can execute all the code in this tutorial just fine without a GPU.

### Prerequisites（by using Colab)

1. Enter the Colab [https://colab.research.google.com/](https://colab.research.google.com/)
2. Choose the .ipynb file
   <img src="images/截屏2022-04-12 17.10.30.png" width="900" height="400" float="left">
3. Choose the GPU <br/>
<img src="images/gpu1.png" width="350" height="500"> <img src="images/gpu2.png" width="350" height="500"> 

4. Mount the Google Drive to Google Colab
   ```
   from google.colab import drive
   drive.mount('/content/drive');
   ```
5. Download the data first time
   ```
   torchvision.datasets.CIFAR10(root = "Colab Notebooks/CIFAR10", train = True,download = True,transform=transform)
   ```
6. install TensorBoard
   ```
   pip install tensorboardX
   ```



<!-- CONTACT -->
## Contact

SHI Linyu -  21453713@life.hkbu.edu.hk

<p align="right">(<a href="#top">back to top</a>)</p>
