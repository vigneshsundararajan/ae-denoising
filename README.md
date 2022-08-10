# CNN based autoencoder for image denoising on the MNIST dataset

## Dataset used 
MNIST: http://yann.lecun.com/exdb/mnist/

The noisy dataset was created by adding a Gaussian noise of $\mu = 0$ and $\sigma = 0.5$. Test train splits are then made accordingly for the noisy and clean parts.

## Results
```bash
Test result on epoch 10: Avg loss is 17.3354560546875
```

In the plot below, the first line of images are the originals, followed by their noisy counterparts, and then finally the denoised output from the CNN

![results](https://user-images.githubusercontent.com/68025565/184027450-b3ac6963-9ff8-4868-8cc9-05a618b09971.png)


