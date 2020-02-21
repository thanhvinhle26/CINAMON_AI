# REPORT
## IMPLEMENTATION
* Read authentic, tampered images and labels.
* Generate fake data by finding tampered area with block 64*64 using labels.
    * Function: sample_fake()
* Generate authentic data by dividing in 64*64 blocks
    * Function : sample_random()
* Concat authentic and tamperd data for train data,creat label, suffle and split.
* Train blocks 64*64 data with RESNET50 pretrained without top layers.
* Finding ratio of authentic blocks/ tampered blocks in all train data to classification base on ratio
    * sample_image(): Function use for dividing input image into 64*64 blocks
    *  ratio(): Function for finding ratio of authentic blocks/ tampered blocks 
    *  predict_forensic_image(): Predict image is authentic or not base on SVM classification with 87% accuracy on test set.
