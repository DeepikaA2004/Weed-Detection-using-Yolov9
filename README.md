# Weed Detection Using YOLO v9

## Introduction

The "Weed Detection Using YOLO v9" project aims to leverage advanced deep learning techniques to identify and classify weeds in agricultural fields in real time. The YOLO (You Only Look Once) v9 algorithm is renowned for its speed and accuracy in object detection tasks, making it an excellent choice for this application. Efficient weed detection is crucial for modern agriculture as it helps in reducing crop losses and improving yield quality by enabling targeted weed management practices. This project showcases the application of YOLO v9 for precise and rapid weed detection, providing significant benefits to farmers and the agricultural industry.

### Objectives

- To develop a high-accuracy model capable of detecting various types of weeds.
- To implement YOLO v9 for real-time object detection in agricultural settings.
- To provide visualizations of the detection process, including output images and performance graphs.

## Methodology

1. **Data Collection**: High-resolution images of agricultural fields containing various types of weeds were collected.
2. **Data Annotation**: The images were annotated to mark the regions containing weeds.
3. **Model Training**: The annotated dataset was used to train the YOLO v9 model.
4. **Model Evaluation**: The trained model was evaluated on a test set to determine its accuracy and performance.
5. **Real-Time Detection**: The model was deployed to perform real-time detection on new images and video streams.

## Results

### Output Images

Below are some examples of the model's output, showcasing its ability to detect weeds in agricultural fields:

**VALIDATION PREDICTION**

![val_batch1_pred](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/7d74fd0c-5af3-4676-aa1f-925f1524c664)

![val_batch2_pred](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/8017dbda-f876-444b-addc-dbe01a94fb31)

**OUTPUT IMAGES**

![20210907_153931_x264_mp4-1070_jpg rf 3975b5449eae59ae682316236781f019](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/098e4b48-fdf5-407f-a85a-34cc3f44b5d7), 
![20210907_153931_x264_mp4-1119_jpg rf 075c69f7b85fa075b614184f9b459ba5](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/e11b4f68-22c1-4d9a-a26d-fc918088ed22)
![20210907_153931_x264_mp4-1132_jpg rf 75e1ff1007cef6bf7ded79392baf2a9e](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/c8a2b4a8-7077-4cc6-a77c-282bc2a2c8c5)
![20210907_153931_x264_mp4-1208_jpg rf eabc89ce1950afa994380ed136bc2abb](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/b8c7f584-c1f9-4764-8659-de2492f6dd68)
![20210907_153931_x264_mp4-1287_jpg rf 910c29aa38add0af106b5fc525d56cec](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/168016a6-6e03-4d4e-88ad-b4aa602b0af3)
![20210907_153931_x264_mp4-1346_jpg rf 906dc046df7d3ea470dfa3c2e71ee169](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/e4a52083-8aaf-44df-9ec7-641c9a563cb5)
![20210907_153931_x264_mp4-1370_jpg rf a92d0ba1b3c52019bca194dd3d4741c9](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/8997985d-2180-44ea-a53c-2e0bcc8937e3)
![20210907_153931_x264_mp4-1431_jpg rf 9f805ec5c15cd81643c8398baaf64906](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/73a5a9e9-e660-4cd2-810c-fb84a857d5a4)
![20210907_153931_x264_mp4-1492_jpg rf 630489ec4ec57d289d0a8b8f166d6a08](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/44dda3bd-5232-4cfb-ad3e-a26fe3fbf04a)
![20210907_153931_x264_mp4-1618_jpg rf 89a69a46b7d0794bfd632a3095b72996](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/41d54239-1975-417b-adcd-1c82d07ef81e)
![20210907_153931_x264_mp4-188_jpg rf 8105a2ea0632b6b5800e3a324d108f31](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/ecc22fcd-3457-413e-bcf1-39f34b9aae1c)
![20210907_153931_x264_mp4-296_jpg rf 6e070eae028793652fba49b842e5f380](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/debf6ff3-47ae-4d26-abce-5e5cb2475af5)
![20210907_153931_x264_mp4-397_jpg rf 071e7361ad39b24443b9a382c20f646f](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/c8d94161-d4ab-45f9-815a-52c21201a2b4)
![20210907_153931_x264_mp4-591_jpg rf 04484c2b40c1eadab535ffb531718cff](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/6ec84166-ea53-4687-9fb9-094870eaf6e0)
![20210907_153931_x264_mp4-855_jpg rf 333b40674f3e15fdcf12aa068ce7f365](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/56b0ea04-6534-44c1-bf10-d5aebd786403)
![20210907_153931_x264_mp4-896_jpg rf 1b5e73368b9f71cc9a20d59a19abdc01](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/16049b0b-08ab-4087-8d0a-754c0e8466e8)
![20210907_153931_x264_mp4-960_jpg rf 61b5fe8d0e0307917517f7f3c25c25b0](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/2c65c8f4-b3f2-4379-8bd9-7fd02d900245)
![20210907_153931_x264_mp4-1002_jpg rf 10fe6c39b9c6a810caa6f95220362e21](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/d0c30976-d296-43ab-a13c-7108e8520b9d)


### Performance Graphs

The following graphs illustrate the performance metrics of the model:

**RESULTS**
![results (1)](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/b914a088-8766-4224-9f10-d926c9ad9e81)

**CORRELOGRAM**
![labels_correlogram](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/bdcebfd5-49dd-485c-9839-c8a3863113ee)

**LABELS**
![labels](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/2c0ee532-50f5-4cf6-956a-64d834efcef7)

**CONFUSION MATRIX**
![confusion_matrix](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/523bec4f-bfd0-4cf8-bb5e-c11eaf99ddf9)

**R CURVE**
![R_curve](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/f6c101d2-b39f-4360-a139-ddd7856bf1b7)

**P CURVE**
![P_curve](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/c48ae801-3700-408b-9b7f-dd6be1f3fe21)

**PR CURVE**
![PR_curve](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/b06fed33-31f3-45a5-9a34-0364c1ca5e93)

**F1 SCORE**
![F1_curve](https://github.com/DeepikaA2004/Weed-Detection-using-Yolov9/assets/110418508/5ba07086-1dfb-4dc4-a096-70c99c8494c8)

## Conclusion

The "Weed Detection Using YOLO v9" project successfully demonstrates the application of advanced object detection techniques to address a critical challenge in agriculture. By leveraging the powerful YOLO v9 algorithm, the project achieved high accuracy in identifying and classifying various types of weeds, thereby facilitating effective and efficient weed management practices.

The model's performance, as illustrated by the provided output images and performance graphs, highlights its potential for deployment in real-world agricultural environments. Implementing this technology can lead to significant benefits, including improved crop health, reduced reliance on herbicides, and increased overall agricultural productivity.

Future work could focus on further refining the model to enhance its accuracy and robustness, expanding the dataset to include more weed species and diverse field conditions, and exploring the deployment of the model on edge devices for real-time field applications. Additionally, integrating this system with automated weed removal tools could provide a comprehensive solution for weed management, ultimately contributing to sustainable farming practices.

Overall, this project underscores the value of combining advanced machine learning techniques with practical agricultural applications, paving the way for innovative and sustainable solutions in the farming industry.

## Contact

**MY LINKEDIN PROFILE** - https://www.linkedin.com/in/deepika2004/






