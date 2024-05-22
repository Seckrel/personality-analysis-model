# Personality Analysis
___
## Abstract
The Purpose of this project is to develop a webapp with a NLP engine running at the backend to visualize personality traits, and similarity comparison. Project focuses on using MBTI dataset collected through Kaggle.com to develop an engine that can parse PDF resumes, and perform personality analysis on it also comparing the resume with job description. The output of the web app will be visualization of personality traits and similarity of resume with job description.

## 🚀 To Install
```
conda activate <your_env>
conda env update --file enviroment.yml --prune
conda install --yes --file requirements.txt
```

## Directory Structure
```
./-|
  |-/model directory contains trained model
  |-/vectorizer directorycontains fine-tuned tfidf and other pre-processing vectorizer
  |-/test_resume directory add any pdf resume file here to test
```

## 🏁 To Run
- Open and Execute Juypter Notebook


## References
> - A. S. Khan, H. Ahmad, M. Z. Asghar, F. K. Saddozai, A. Arif and H. A. Khalid, "Personlity Classification from Online Text using Machine Learning Approach," International Journal of Advanced Computer Science and Applications , vol. 11, no. 3, p. 460, 2020.
> - M. Kosinski, D. Stillwell and T. Graepel, "Private traits and attributes are predictable from digital records of human behavior," Proceedings of National Academy of Sciences, vol. 110, no. 15, 2013.
