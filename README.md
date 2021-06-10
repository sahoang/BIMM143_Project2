# BIMM143_Project2
Scientific Question: Is it possible to visually identify between the American Alligator and the American Crocodile quickly? | Scientific Hypothesis: If there are defining features to the head shape appearance between the American Alligator and the American Crocodile, then their images can be classified in an automated process.

You will need the following image datasets to use in unison with the code.

1) "Alligator" Image Dataset
2) "Crocodile" Image Dataset

These images can be obtained from Google Drive using this link and downloading the folders: https://drive.google.com/drive/folders/1STqrl1SqPyngqcwTH-zEvm_5_JXBoOjK?usp=sharing.

How to use the dataset in the code:

IMPORTANT: Please run line 2 first before proceeding with the images. Line 2 will create a directory in Juypter Notebook called "reptile_data" and two folders within it named "alligators" and "crocodiles". Manually upload the images to the respective folders. You may need to press upload for each image to download. 

After this, run the code normally and the model will create directories and shuffle images on its own, but it will need your help with uploading the source images initially with the above instructions.

Finally, a last warning for multiple runs of the code. If you would like to rerun the code and test the model once again, please delete the folder in Juypter Notebook called "reptile_data". If it is not deleted and the same folder exists during the additional run, the code will not understand where the dataset is coming from and will give differing values.

If you are unsure if this is happening to you, there are len functions in line 3 and 6 which are used as checks and balances to ensure the correct amount of images are in each directory. The expected outcomes are noted in the code with a # and should match the output.
