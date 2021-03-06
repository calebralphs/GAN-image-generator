# GAN-image-generator

GAN for generating MNIST digit images

### Running model

The script is structured into individual cells in the 'GAN.py' file to replicate an ipynb file, but usable within VSCode. The cells can be run in chronological order, and the code will execute correctly.

The train() function, found in the Training cell, outputs the loss graph on the completion of each epoch, plotting the discriminative and generative loss against the eopochs. The cell below the Training cell is the Train Model cell which when run, executes the train() function.

In the Training cell you can find the defined 'num_epochs' variable, initially set to 100, if you want to change this for running the code.

To generate the results run the cell below the Train Model cell, the Create Results cell. This cell calls the plotLoss() and plotGeneration() functions.


### Expiramental Results

Please see the attached pdf file 'GAN.pdf' for the final graph of the loss and the 25 generated digit images.

Additionally, you can find the images in the '/images' folder which contains all of the results (i.e the generated digits and the loss data) for each expiriment.


### Notes

As explained to Professor Li, after I can my final expiriment and tried to export my model to .json and .h5 files, the kernel crashed. Additionally, after assuring that the h5py library was installed correctly and after multiple trials of exporting, the kernel crashed every time. Professor Li said it is okay that I am not submitting these two files since the code executes correctly, with no errors, and the final generated images and loss is present in the 'GAN.pdf' file.