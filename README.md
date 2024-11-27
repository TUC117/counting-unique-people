# Counting Unique people in a movie clip

This is the repo containing the code for **IE 643 Deep Learning - Theory and Practice Course Project**.

Detect, Track and Count unique people or characters in a movie clip

### Team Name - Pixel Pioneers
##### Member 1 : Trasula Umesh Karthikeya - 22B0913
##### Member 2 : Mariyala Venkata Sai Mukhesh - 22B0972

# Steps to run the code
1) First install python and Git in your laptop.
2) Download/clone this repository on your laptop.
3) Navigate to the repository downloaded.
4) Now  run the ipynb file deploy_final.ipynb.
5) Make shore that deploy_final.ipynb and data folder are in the same folder on your laptop.
6) On running the file if you get the error for any modules not installed download them,this might be the only error you might get.
7) If the file deploy_final.ipynb ran succesfully in the output of the last cell of the ipynb file you will get a link.
8) Please open the link and upload the video.

#  Hyperparameters
tracker=DeepSort(max_age=30,n_init=10,nn_budget=200,nms_max_overlap=0.3,max_iou_distance=0.6,max_cosine_distance=0.3,embedder='torchreid',embedder_model_name='osnet_x1_0')
This is the part of the code that contains the hyperparameters and the default hyperparameters are clearly mentioned in the code.You can read about the hyperparameters from the report and chage them accordingly.
