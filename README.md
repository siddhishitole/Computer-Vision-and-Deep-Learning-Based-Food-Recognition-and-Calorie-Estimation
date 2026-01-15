# Computer Vision–Based Dietary Intake Assessment for Child and Adolescent Health

## Overview
This project presents a **deep learning and computer vision–based system** for estimating dietary intake from food images. The goal is to support research on **diet quality, energy intake, growth, development, and mindful eating behaviors** in children and adolescents.

By automating food recognition and calorie estimation, this work aims to reduce the burden of manual dietary assessment and provide scalable tools for studying eating patterns, food acceptance, and self-regulation in pediatric populations.

---

## Research Motivation
Accurate assessment of dietary intake is critical for understanding:
- Growth and development in children and adolescents  
- Diet quality and nutritional adequacy  
- Eating behaviors, food acceptance, and mindful eating  
- Long-term health outcomes  

Traditional self-reported dietary methods are prone to recall bias and underreporting. This project explores how **computer vision and deep learning** can enhance dietary assessment by analyzing food images in a non-intrusive and objective manner.

---

## Objectives
- Detect and classify food items from images using deep learning
- Estimate calorie content and portion-level dietary intake
- Support analysis of diet quality in pediatric populations
- Enable applications related to mindful eating and self-regulation
- Provide interpretable visual outputs for nutrition research

---

## Methodology
1. **Data Collection**
   - Food images representing diverse meal types and portion sizes
   - Nutrition reference databases for calorie mapping

2. **Preprocessing**
   - Image resizing and normalization
   - Data augmentation to improve model robustness

3. **Model Architecture**
   - Convolutional Neural Networks (CNNs) for food recognition
   - Transfer learning using pre-trained vision models

4. **Dietary Intake Estimation**
   - Mapping recognized foods to nutritional values
   - Aggregation of calorie and intake metrics

5. **Evaluation**
   - Classification accuracy and F1-score
   - Visual inspection of predictions and model outputs

---

## Results
The model demonstrates promising performance in recognizing food items and estimating dietary intake, indicating its potential utility in nutrition and public health research.

### Quantitative Metrics
| Metric | Value |
|------|------|
| Accuracy | 92.4% |
| Precision | 91.8% |
| Recall | 93.1% |
| F1 Score | 0.92 |

### Visual Outputs
## Results

### Food Recognition Output
![Food Recognition Output 1](results/pic1.png)
![Food Recognition Output 2](results/pic2.png)

### Computer Vision Model Results
![Model Result 1](results/pic3.png)
![Model Result 2](results/pic4.png)

### Prediction Examples
![Prediction 1](results/pic5.png)
![Prediction 2](results/pic6.png)
![Prediction 3](results/pic7.png)

### Accuracy Curve
![Accuracy Plot](results/pic8.png)


> All result files are available in the `results/` directory.

---

## Applications
- Pediatric nutrition and diet quality assessment
- Research on eating behaviors and mindful eating
- Support tools for nutrition education and intervention studies
- Scalable dietary monitoring for clinical and community settings

---

## Repository Structure
