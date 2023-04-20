# GAN-for-CVD
Official repository for Infosys Springboard Internship

The npz file created from daltonization for dataset creation can be downloaded from the following link:
https://drive.google.com/file/d/1pQmmFHtFzE6UUZ93Vlauui3BZ5Lhhdw9/view?usp=share_link

The pre-trained weights of the generator model are available here:
https://drive.google.com/drive/folders/1OE9HcwwoiF7ahZG8_yKKE4wCN4HLs8rY?usp=share_link

Steps:
- Run the tritanopia_daltonize.ipynb file on images in 'org' folder for getting daltonized images.
- Use the npz_convert.ipynb file for converting original and recolored dataset into npz file.
- Run the Recoloring_GAN.ipynb file for training the GAN model and saving weights at every 5 epochs.
- Finally, use the validation.ipynb file for validating all the saved models and choosing the best model from them.
