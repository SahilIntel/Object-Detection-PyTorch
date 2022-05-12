# Object-Detection-PyTorch

The coco_classes.pickle file contains all the class labels of COCO Dataset.

The pickling_classes.py file contains the script to create a pickle of a list of all class labels.

The detect_image.py is main code, where in we use any of the pre-trained model out of the following 3 - 
1. fasterrcnn_resnet50_fpn
2. fasterrcnn_mobilenet_v3_large_320_fpn
3. retinanet_resnet50_fpn

We use any of these models and detect/predict object(s) on an input image which we specify as an argument in the command.

For running the detect_image.py program, the following command with the specified arguments needs to be passed.
 
 >python detect_image.py --model <model_name>  --image <img_path> --labels <path to file that  contains class_labels(pickled)>
