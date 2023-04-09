# Autoencoders

-> Autoencoder (AE) is a class of artificial neural network models that learns in an unsupervised manner  

-> It tries to reconstruct the input at its output, essentially requiring no additional label for training  

-> AE learns the underlying patterns in data and represent them in latent space 

![Alt text](https://github.com/kris-mlguy/Autoencoders/blob/main/AE_image.PNG?raw=true "Optional Title")

### Applications include  
    1. Feature extraction  
    2. Dimensionality reduction  
    3. Filtering noise and reconstruction of data  
    4. Concise representation (reduced size) of data  
    5. Generation of new data from learned latent space distribution 
    
### Different types of autoencoders  
    i. Denoising autoencoder  
    ii. Sparse autoencoder  
    iii. Deep autoencoder  
    iv. Contractive autoencoder  
    v. Undercomplete autoencoder  
    vi. Convolutional autoencoder  
    vii. Variational autoencoder  

### Getting started
    1. Clone the repository: git clone https://github.com/kris-mlguy/Autoencoders.git
    2. Open anaconda prompt and navigate to directory containing the cloned repo
    3. Create a conda environment: conda create -n AE_env
    4. Activate the environment: conda activate AE_env
    5. Install jupyter notebook library: conda install jupyter notebook
    6. Install other dependent libraries: pip install -r requirements.txt
    7. Open jupyter notebook: jupyter notebook
    8. Above step will open jupyter notebook in a browser. Open the <requiredNotebook>.ipynb and run it cell-by-cell to see the working of autoencoders