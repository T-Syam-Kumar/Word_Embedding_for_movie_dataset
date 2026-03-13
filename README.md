# 🎬 IMDB Sentiment Analysis using Word Embedding

This project implements **Word Embedding using TensorFlow and Keras** to perform **Sentiment Analysis on the IMDB Movie Reviews dataset**.  
The model learns **vector representations of words** through an **Embedding Layer** and classifies movie reviews as **Positive or Negative**.

---

# 📌 Project Overview

Natural Language Processing (NLP) models require text data to be converted into **numerical representations** before training machine learning models.

**Word Embedding** is a technique that represents words as **dense vectors in a continuous vector space**, allowing models to capture semantic relationships between words.

In this project:

- The **IMDB Movie Review Dataset** is used.
- The dataset contains **50,000 labeled movie reviews**.
- The model learns word embeddings and performs **binary sentiment classification**.

---

# 🛠️ Technologies Used

- 🐍 Python  
- 🤖 TensorFlow  
- 🧠 Keras  
- 🔢 NumPy  
- 📓 Jupyter Notebook / Google Colab  

---

# 📂 Dataset

The dataset used is the **IMDB Movie Review Dataset**, which is available directly through the **Keras library**.

### Dataset Details

| Feature | Description |
|-------|-------------|
| Total Reviews | 50,000 |
| Training Samples | 25,000 |
| Testing Samples | 25,000 |
| Task | Binary Sentiment Classification |
| Classes | Positive / Negative |

---

# 🧠 Model Architecture

The neural network architecture used in this project:

### 1️⃣ Embedding Layer
- Converts each word into a **dense vector representation**
- Vocabulary Size: **10,000**
- Embedding Dimension: **128**

### 2️⃣ Flatten Layer
- Flattens the embedding output into a **single feature vector**

### 3️⃣ Dense Layer
- Fully connected layer
- Activation Function: **ReLU**

### 4️⃣ Output Layer
- **Sigmoid activation** for binary classification

---

# 🔄 Project Workflow

### Step 1: Import Required Libraries
TensorFlow and Keras libraries are imported for building the deep learning model.

### Step 2: Load the IMDB Dataset
The dataset is loaded with a **vocabulary size of 10,000 words**.

### Step 3: Pad Sequences
Movie reviews have different lengths, so they are padded to a **fixed length of 200 words**.

### Step 4: Build the Model
A **Sequential Neural Network** is created with an embedding layer followed by dense layers.

### Step 5: Compile the Model

The model is compiled with:

- **Optimizer:** Adam  
- **Loss Function:** Binary Crossentropy  
- **Evaluation Metric:** Accuracy  

### Step 6: Train the Model

The model is trained with:

- **Epochs:** 5  
- **Batch Size:** 64  
- **Validation Split:** 0.2  

### Step 7: Evaluate the Model
The trained model is evaluated on the **test dataset** to measure performance.

---

# 🚀 How to Run the Project

### 1️⃣ Install Dependencies

```bash
pip install tensorflow



## ▶️ Run the Project

You can run the project using:

- 📓 **Jupyter Notebook**
- ☁️ **Google Colab**
- 💻 **VS Code**

---

## 📊 Expected Output

The program displays:

- 📌 Number of training samples  
- 📌 Number of testing samples  
- 📌 Model architecture summary  
- 📌 Training accuracy  
- 📌 Validation accuracy  
- 📌 Final test accuracy  

⭐ **Typical model accuracy achieved:** 85% – 88%

---

## 📚 Key Concepts Demonstrated

- 🧠 **Word Embeddings**
- 📖 **Natural Language Processing (NLP)**
- 🔄 **Text Preprocessing**
- 🤖 **Deep Learning for Sentiment Analysis**
- ⚡ **Binary Text Classification**

---

## 🎓 Learning Outcomes

After completing this project you will understand:

- ✔️ How text data is converted into numerical sequences  
- ✔️ How embedding layers learn semantic relationships  
- ✔️ How neural networks perform sentiment classification  

---

## 🔮 Future Improvements

Possible improvements to this project:

- 🔹 Replace **Flatten Layer** with `GlobalAveragePooling1D`
- 🔹 Use advanced architectures like **LSTM** or **GRU**
- 🔹 Use **pre-trained embeddings** such as:
  - Word2Vec
  - GloVe
- 🔹 Add **Attention Mechanisms** for improved performance

---

## 👨‍💻 Author

**Syam Kumar**  

AI & Machine Learning Student  
Exploring **NLP, Deep Learning, and Generative AI**
