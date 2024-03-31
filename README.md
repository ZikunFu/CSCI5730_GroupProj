# Analysis of Elicited and Acted Emotional Expressions in PEDFE

## Group Members
- Zikun Fu
- Tony Wang

## Objective
1. Investigate the differences between genuine and posed emotional expressions within the Padova Emotional Dataset of Facial Expressions (PEDFE).
2. Provide insights into the nuances of emotional expression and the ability of current technological systems to recognize genuine emotional states.

## Research Question
1. How do automated emotion recognition systems perform in differentiating between genuine and posed emotional expressions in the PEDFE dataset?
2. How do genuineness, intensity, and hit rate correlate with the emotion classification accuracy, and are these correlations consistent between genuine and posed emotional expressions?

## Methodology
1. **Data Preparation**: Utilize the PEDFE dataset for the analysis. [PEDFE dataset](https://link.springer.com/article/10.3758/s13428-022-01914-4)
2. **Feature Extraction**: Use Py-Feat for extracting relevant features from the dataset. [Py-Feat Introduction](https://py-feat.org/pages/intro.html)
3. **Emotion Classification**: Apply Resmasknet to identify patterns and distinctions in facial emotions. [Pyfeat Notebook](https://github.com/ZikunFu/CSCI5730_GroupProj/blob/master/Pyfeat.ipynb)
4. **Result Analysis**: Evaluate the classifier's performance and analyze the distinctions between genuine and posed expressions. [Analysis Notebook](https://github.com/ZikunFu/CSCI5730_GroupProj/blob/master/Analysis.ipynb)

## Ipynb Description
- `Pyfeat.ipynb`: Notebook used for feature extraction with Py-Feat.
- `Analysis.ipynb`: Notebook used for emotion classification and result analysis.

## Installation
To set up the project environment and run the notebooks, follow these steps:
```bash
git clone https://github.com/ZikunFu/CSCI5730_GroupProj.git
cd CSCI5730_GroupProj
pip install -r requirements.txt
