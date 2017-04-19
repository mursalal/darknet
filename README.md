# Training Flickr Logos 27

## Download Flickr Logos 27 dataset


```
cd data/
wget http://image.ntua.gr/iva/datasets/flickr_logos/flickr_logos_27_dataset.tar.gz
tar -xvf flickr_logos_27_dataset.tar.gz
cd flickr_logos_27_dataset
tar -xvf flickr_logos_27_dataset_images.tar.gz
cd ../../
```

## Script to convert flickr27 to Yolov2 format

Change path in scripts/formatting_flickr27_dataset.py

Then run


```
python formatting_flickr27_dataset.py
```

## Config net 

Config net: https://github.com/AlexeyAB/darknet#how-to-train-to-detect-your-custom-objects
