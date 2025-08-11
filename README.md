Light Weight GAN Segmentation Framework
Python code documentation:
CODE:  UGAN_vs_Baseline_methods.ipynb
Python code will accept input from user “Google Drive link”  of SUIM dataset and UIEB datasets. Program will Print the PSNR (dB) and SSIM values for SUIM dataset and UIEB dataset for the following methods, Input image, Histogram equalization, CLAHE, UGAN.  
CODE: UW_image_segmentation_metrics.ipynb
Python code will accept the input from user “Google Drive link”  of SUIM dataset and UIEB dataset.  Program will Print Pixel accuracy, Mean IoU, Dice Coefficient, mPA using SUIM dataset and UIEB dataset for the UNet, PSPNet, UNet++, DeepLavv3+ models. 
CODE: segmentation_loss_computation.ipynb
Python code will accept the input from user “Google Drive link” of SUIM dataset.  Maximum epochs = 40. Program will Print the train Lovasz loss, Train BCE loss, Train total loss, Validation total loss at epoch=1, epoch=10, epoch=20, epoch=30, epoch=40.
Code: Orig_img_GT_mask_segment_masks.ipynb
Python code will  accept the input from user “Google Drive link”  of SUIM dataset. Read the images and the corresponding ground truth masks. Epochs = 50.  Program will Print the original image , ground truth mask,  segmentation mask output during epoch 1, 30, 50.
Code: Model_performance_on_two_datasets.ipynb
Python code will  accept the input from user “Google Drive link” of SUIM dataset and UIEB datasets.  Program will Print the Params, GFLOPs, Latency, Power, mIoU for SUIM dataset and UIEB dataset, Dice for SUIM dataset and UIEB dataset for the following models FUnIEGAN+ResNet50, DeepLab+MobileNetV2, DeepLab+TinyFUnIE GAN + Pruned MobileOne50.
Code: Visual_quality_of_different_models.ipynb
Python code will  accept the input from user “Google Drive link” of SUIM dataset. Program will Print the visual quality of original input frame, enhanced frame output, ground truth mask, predicted mask from each model (FUnIE GAN, Tiny FUnIE GAN, MobileNetV2)
Code: Performance_comparison_on_two_datasets.ipynb
Python code will  accept the input from user “Google Drive link” of SUIM dataset and UIEB dataset.  Program will Print the Latency, FPS, GPU utilization, Power, Params, GFLOPs, mIoU for SUIM datset, mIoU for UIEB dataset,  for the following models (Fast-EUVP- UW-SegFormer-B0 (Proposed), UW-SegFormer-B0 (No enhancement), ResNet-50 DeepLab v3+ (FP16)).
