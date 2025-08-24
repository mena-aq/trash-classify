# Resnet-based Trash Classifier

This notebook outlines a custom *Resnet-18* model used to classify trash into the 6 categories as outlined in the [Trashnet](https://www.kaggle.com/datasets/feyzazkefe/trashnet) dataset. <br>
After training for *50 epochs* (1), the model achieved *~70% accuracy*.<br>
Notably, the model struggles to classify "trash", which may be due to the diversity of materials visually present in the trash category. 

Several models such as Resnet-50, AlexNet, and DenseNet were experimented with; however the modifications with Resnet-18 showed the best training results.

(1) : due to resource constraints using public GPUs. With future training utilising more epochs, a slight improvement in accuracy is anticipated 
