# NLP-Preprocessing-And-Text-Classification
Lab Assignment No. 4- NLP Preprocessing And Text Classificationsing)

## 1. Objective
This assignment focuses on preprocessing raw text data and applying a pre-trained NLP model for text classification. The aim is to build an end-to-end pipeline from cleaning data to classification and evaluation.

## 2. Problem Definition
- **Dataset**: Labeled dataset containing text samples.
- **Task**: Classify the text into categories (e.g., sentiment analysis or topic classification).
- **Approach**: Use text preprocessing techniques followed by classification using a transformer-based pre-trained model (e.g., BERT, DistilBERT).

## 3. Methodology

### Pre-trained Model
- **Model Used**: BERT / DistilBERT (or as used in the notebook)
- **Framework**: Hugging Face Transformers

### Steps Involved
1. **Text Preprocessing**:
   - Convert to lowercase
   - Remove punctuation, special characters, stopwords
   - Tokenization and stemming or lemmatization

2. **Tokenization**:
   - Use tokenizer from transformer models

3. **Model Loading**:
   - Load pre-trained transformer model with classification head

4. **Training & Evaluation**:
   - Fine-tune the model on training data
   - Evaluate with accuracy, F1-score, and confusion matrix

5. **Prediction**:
   - Predict class labels for new text samples

## 4. Libraries & Tools Used
- Hugging Face Transformers  
- scikit-learn  
- NLTK / spaCy  
- Pandas  
- Matplotlib

## 5. Results
- Model training and validation accuracy shown  
- Confusion matrix plotted  
- Text predictions demonstrated

---

## Declaration
I, **Nilambari Mahajan**, confirm that the work submitted in this assignment is my own and has been completed following academic integrity guidelines. The code is uploaded on my GitHub repository account, and the repository link is provided below:
