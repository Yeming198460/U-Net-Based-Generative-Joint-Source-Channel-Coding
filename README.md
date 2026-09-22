# U-Net-Based-Generative-Joint-Source-Channel-Coding for Wireless Image Transmission

Source code for the article: [1] M. Ye, K. Cai, C. Pan, Z. Mei, W. Yang, and C. Li, “U-Net-Based-Generative-Joint-Source-Channel-Coding for Wireless Image Transmission,”  IEEE Transactions on Cognitive Communications and Networking, under review.

If you use this simulation code package in any way, please cite the original paper [1] above. For questions regarding the code, please contact Ming Ye at 230198460@aa.seu.edu.cn.

Acknowledgments: We are very grateful to the authors of the following reference paper. Our source code is developed based on and extends their publicly available implementation:

[5] E. Bourtsoulatze, D. B. Kurka, and D. Gündüz, “Deep joint source-channel coding for wireless image transmission,” IEEE Transactions on Cognitive Communications and Networking, vol. 5, no. 3, pp. 567–579, Sep. 2019.

Software Requirements: This simulation package was developed and tested using Python 3.8 and TensorFlow 2.6.0. Compatibility issues may arise when using different versions of Python or TensorFlow.

###############################################################################################################################################

How to use this simulation code package?

This repository contains the source code for U-Net-based GAN JSCC image transmission and reconstruction implemented in Python.

Image Reconstruction/Transmission: Use the scripts train_GAN412_nray66_normci10.py and eval2_GAN412_nray66_6normci10.py from the tex9_code.zip archive to train and evaluate the proposed framework based on the U-Net-based generator. The script JSCC_Model_GAN412_nray66_normci10.py from the same archive contains the code that defines the proposed JSCC model.

The tex9_code.zip archive also contains a checkpoint folder containing the trained weights of the G-UNet-JSCC model trained at SNRs of 5 dB and 15 dB.

[tex9_code.zip](https://github.com/user-attachments/files/32502006/tex9_code.zip)


