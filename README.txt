The submission contains the following:

1) Project Report

2) Folder src that contains 5 python notebook described as follows:
    
    a) face_detection_with_detectron2.ipynb:
    It contains all work about finetuning detectron2 and evaluating it. To run it, it needs to be uploaded to Google Colab and while following the instructions in the notebook itself.

    b) Detect_Faces.ipynb:
    Dedicated for extracting faces from any given input using the finetuned Detectron2 model
    (Either a video, a multi-faced image or the custom dataset used to evaluate the system)
    To run, the custom dataset should be uploaded to the drive alongside with any input that needs to be face-detected and all paths should be changed accordingly.

    c) Face_Recognition.ipynb:
    This notebook recognizes faces using Facenet, it was used to train the SVM to recognize the custom dataset and apply it on the image that contains multiple faces and on the input video. 
    To use it, the dataset and the video should be uploaded and all the paths should be changed accordingly.
    In addition, the Facenet model should be uploaded and loaded inside the notebook.

    d) Face_Recognition_Surveillance.ipynb:
    Tests Facenet on Surveillance data.
    Loads 20 identites from the QMUL-SurvFace dataset and recognizes them using Facenet and SVMs.
    To run this notebook, 20 identites from the QMUL-SurvFace dataset should be uploaded and all of them must have no less than 200 images each.

3) Folder outputs that contains:
    
    a) Face detection and recognition applied to a video
    b) Face detection and recognition applied to a photo
