# **Spam Detection with Logistic Regression**  
 
Spam detection model using **Logistic Regression**. The model classifies text messages as either **spam 1** or **ham 0** based on their content.  

---

### **1. Data Loading**
- The dataset `spam_ham_dataset.csv` contains two columns:  
  - **`text`**  The message content.  
  - **`label_num`**  1 (spam) or 0 (ham).  
- The dataset is split into **training 80%** and **testing 20%** sets.

---

### **2. Feature Engineering**  
#### **Bag of Words (BOW) Representation**
- Converts text into a numerical format using **CountVectorizer**.  
- Removes **English stopwords** and keeps **5,000 most frequent words**.  


---

### **3. Training the Model**
- Uses **Logistic Regression** with:  
- Trains the model on the **BOW**.

---

### **4. Model Evaluation**

  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1-score**
    
