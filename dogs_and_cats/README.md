# dogs_and_cats

subset of the Kaggle dogs vs cats data-set created for the purpose of the Crash Course in Deep Learning. To obtain the original data set please refer to [Kaggle.com](https://www.kaggle.com/c/dogs-vs-cats/data)

## get the dataset

To get the dataset open a terminal, go into the directory you wish to host the repo and type in
```python
git clone https://github.com/georgiosouzounis/dogs_and_cats.git
cd dogs_and_cats
unzip train_dogs.zip
unzip train_cats.zip
unzip test.zip
unzip exercise.zip
```

## structure your directory

Create a ```train/``` directory and move the dog and cat training images in there:
```python
mkdir train/
mkdir train/dogs/
mkdir train/cats/
mv train_dogs/* train/dogs/
mv train_cats/* train/cats/
```

## remove temporary files

Clean-up some space by typing in:
```python
rm *.zip
rm -r train_dogs/
rm -r train_cats/
```

## Contact

Contact [Georgios K. Ouzounis](mailto:georgios.ouzounis@gmail.com)
