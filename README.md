# BU-Net
Source Code for BU-Net (continuously updating)

---------Environment

Hardware ：all experiments are run on a computer with Intel(R) Xeon(R) CPU E5-2650 v4 @ 2.20GHz and GPU GeForce GTX 1080 Ti.

Software（Major）：

 tensorflow                1.13.1 
 scipy                     1.5.2 
 numpy                     1.19.2
 opencv-python             4.2.0.34 
 Pillow                    8.4.0 
 scikit-image              0.17.2 
 keras-base                2.2.4 
 matplotlib                2.2.2 
 anaconda                  5.2.0   


---------Samson Dataset 

samson_1.mat : Hyperspectral data

end3.mat : GT of abudnances and endmembers 



----------Data processing && Training && Predicting

All components are integrated in BUNet_samson.py

Run : python BUNet_samson.py (for samson dataset  )
