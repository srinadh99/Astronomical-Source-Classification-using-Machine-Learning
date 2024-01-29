# Astronomical-Source-Separation-using-Machine-Learning
Exploring a Variety of Machine Learning Techniques for Astronomical Source Classification Across Multiple Modalities.

For any queries, please contact at ee19resch01008@iith.ac.in

# Details
In this work, I studied the performance of a new Multimodal Fusion Transformer (MFT) for Remote Sensing (RS) Image Classification proposed recently. The link for the original MFT paper is here https://arxiv.org/pdf/2203.16952.pdf. 

Transformer-based models are widely used in several image-processing applications due to their promising performance over Convolutional Neural Networks (CNNs). However, there are certain challenges while adapting transformer models for the Hyperspectral Image (HSI) classification tasks. In RS image classification, using images from multiple sources and exploiting the complementary information is getting more attention these days with the increased availability of multi-sensor data. But considering the patch-level processing in the transformer models and the number of spectral bands in the HSI data or the fused data (HSI+other modalities), the number of model parameters is becoming a major issue. In the MFT work, a new transformer-based architecture with novel attention and tokenization mechanisms are proposed to obtain the complementary information from other modalities through external CLS token. They showed CLS token extracted from other multimodal data is generalizing well compared to the random CLS token used in general transformer models.

In this work, I specifically studied the performance of the MFT model with vaying the CLS token. Specifically, I used the CLS token to be 'random', processed through 'channel' and 'pixel' tokenization methods. I considered the 'Trneto' dataset to validate the performance of the MFT model.
The performance is studies using Overall Accuracy (OA), Average Accuracy (AA) and KAPPA Scores. The training loss and confusion matrix are also studied. 
