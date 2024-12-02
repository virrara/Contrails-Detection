# Improving Contrail Detection with Deep Learning and Band Selection  
**Final Project Scientific Writing**  
📄 DOI: [10.12720/jait.15.6.682-692](https://doi.org/10.12720/jait.15.6.682-692)  

☁️ **Enhancing contrail detection in satellite imagery using deep learning models and optimized band selection techniques.**  

---

## 🌍 Abstract  
The consequences of climate change are becoming increasingly urgent, with contrails (condensation trails) identified as potential contributors to this phenomenon. This study tackles the challenge of detecting contrails in satellite imagery by employing advanced deep learning models and band selection strategies.  

Using the **Landsat-8 dataset** with human-labeled contrails sourced from the GOES-16 Advanced Baseline Imager, the study evaluates the effectiveness of various deep learning models:  
- **DeepLabV3**  
- **U-Net**  
- **Fully Convolutional Network (FCN)**  
- **Pyramid Scene Parsing Network (PSPNET2)**  
- **Ensemble Deep Learning**  

Additionally, we explored the impact of specific band combinations, such as the ash color scheme using **Bands 11, 14, 15, and 08**, on improving contrail identification.  

---

## Research Methodology  
<p align="center">
  <img src="https://github.com/user-attachments/assets/bb38112c-db11-434e-9a4b-b2cddc3b5a0c" alt="Research Methodology" width="80%">
</p>

---

## Key Findings  
- The **FCN model with Band 08** achieved the best performance, showing the **lowest average loss** during training (0.032591) and validation (0.013321).  
- Incorporating **Band 08** did not universally enhance performance but proved effective for specific models.  
- Results highlight the importance of model selection and band configuration for detecting contrails with greater precision.  

---

## 📊 Features  
1. **Deep Learning Models**: Comparative analysis of various architectures for contrail detection.  
2. **Band Selection**: Optimized band combinations for improved satellite image interpretation.  
3. **Dataset**: Human-labeled contrails from GOES-16 Advanced Baseline Imager and Landsat-8.  
4. **Performance Metrics**: Evaluation using training/validation loss and other key metrics.  

---

## 🚀 Tools & Technologies  
- **Dataset**: Landsat-8, GOES-16 Advanced Baseline Imager  
- **Deep Learning Framework**: TensorFlow/Keras  
- **Models**: U-Net, DeepLabV3, FCN, PSPNET2, Ensemble Learning  
- **Evaluation Metrics**: Loss, Accuracy  
- **Kaggle Competition**: [Challenge](https://www.kaggle.com/competitions/google-research-identify-contrails-reduce-global-warming)  

---

## 📸 Visualizations  

### Model Performance Comparison  
<p align="center">
  <table>
    <tr>
      <td align="center"><strong>DeepLabV3</strong></td>
      <td align="center"><strong>Fully Convolutional Network (FCN)</strong></td>
      <td align="center"><strong>PSPNET2</strong></td>
    </tr>
    <tr>
      <td>
        <img src="https://github.com/user-attachments/assets/418ca519-dc73-415a-94fe-656db549b66e" alt="DeepLabV3 Visualization" width="100%">
      </td>
      <td>
        <img src="https://github.com/user-attachments/assets/8bf87f72-77b0-4e4a-bc40-f32c6c0c98bc" alt="FCN Visualization" width="100%">
      </td>
      <td>
        <img src="https://github.com/user-attachments/assets/537737bd-1a93-416d-9d60-7664fe28bfc8" alt="PSPNET2 Visualization" width="100%">
      </td>
    </tr>
    <tr>
      <td align="center"><strong>U-Net</strong></td>
      <td align="center"><strong>Ensemble Learning</strong></td>
    </tr>
    <tr>
      <td>
        <img src="https://github.com/user-attachments/assets/0fdd16a0-1029-4fbd-a51d-8b7190084d23" alt="U-Net Visualization" width="100%">
      </td>
      <td>
        <img src="https://github.com/user-attachments/assets/fdfc62c7-855c-4a68-b399-af40325077dc" alt="Ensemble Learning Visualization" width="100%">
      </td>
    </tr>
  </table>
</p>

---

## 📈 Results  
- **Best Model**: Fully Convolutional Network (FCN) with Band 08  
- **Training Loss**: 0.032591  
- **Validation Loss**: 0.013321  

This research provides significant insights into improving contrail detection, supporting efforts to mitigate the climate impact of aviation.  
