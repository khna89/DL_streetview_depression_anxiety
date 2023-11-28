# DL_streetview_depression_anxiety
This code is supplementary to Khodorivsko, N., & Spigler, G. (2023). Predicting Depression and Anxiety Risk in Dutch Neighborhoods from Street-View Images (in BNAIC/BeNeLearn 2023 pre-proceedings) https://bnaic2023.tudelft.nl/static/media/BNAICBENELEARN_2023_paper_62.e795d9519efb7971e25f.pdf .

Depression and anxiety disorders are prevalent mental health challenges affecting a substantial segment of the global population. In this study, we explored the environmental correlates of these disorders by analyzing street-view images (SVI) of neighborhoods in the Netherlands. Our dataset comprises 9,879 Dutch SVIs sourced from Google Street View, paired with statistical depression and anxiety risk metrics from the Dutch Health Monitor.

To tackle this challenge, we refined two existing neural network architectures, DeiT Base and ResNet50. Our goal was to predict neighborhood risk levels, categorized into four tiers from low to high risk, using the raw images. The results showed that DeiT Base and ResNet50 achieved accuracies of 43.43% and 43.63%, respectively. Notably, a significant portion of the errors were between adjacent risk categories, resulting in adjusted accuracies of 83.55% and 80.38%. We also implemented the SHapley Additive exPlanations (SHAP) method on both models and employed gradient rollout on DeiT. Interestingly, while SHAP underscored specific landscape attributes, the correlation between these features and distinct depression risk categories remained unclear. The gradient rollout findings were similarly non-definitive. However, through manual analysis, we identified certain landscape types that were consistently linked with specific risk categories. These findings suggest the potential of these techniques in monitoring the correlation between various landscapes and environmental risk factors for mental health issues. As a future direction, we recommend employing these methods to observe how risk scores from the Dutch Health Monitor shift across neighborhoods over time.

![image](https://github.com/khna89/DL_streetview_depression_anxiety/assets/78618639/a486b55b-7984-4f66-8d7f-5e82ee01d4d1)


![image](https://github.com/khna89/DL_streetview_depression_anxiety/assets/78618639/43bccd8e-bfe4-42af-8b27-a0755a5899ad)

![image](https://github.com/khna89/DL_streetview_depression_anxiety/assets/78618639/619b8056-367e-4788-b3cf-24867e601430)

![image](https://github.com/khna89/DL_streetview_depression_anxiety/assets/78618639/c45d4e81-7705-4c07-b4c6-e76b8eb30c04)

![image](https://github.com/khna89/DL_streetview_depression_anxiety/assets/78618639/51dc426f-77b9-4190-b9e0-c8c7fe95b468)

![image](https://github.com/khna89/DL_streetview_depression_anxiety/assets/78618639/ef82a053-a568-4182-ad12-a819169fdc83)

![image](https://github.com/khna89/DL_streetview_depression_anxiety/assets/78618639/7c6c72c5-cfe7-4032-9ee2-75ba934036de)


![image](https://github.com/khna89/DL_streetview_depression_anxiety/assets/78618639/917df68e-c4d8-42f6-8d13-78adef4b83b5)
