# 📈 Similar Name Finder

Similar Name Finder is a **machine learning–based name similarity and matching system** built using **PyTorch** and **Python**.  
The project focuses on analyzing name datasets, generating name embeddings using neural networks, and finding semantically similar names through learned representations.

---

## 🚀 Project Overview

This system processes a dataset of names, applies deep learning techniques to learn name representations, and identifies similar names based on their embeddings.  
The application uses neural networks to understand the semantic structure of names, making it possible to find names that sound or look similar despite different spellings.

---

## 🧠 Key Features

- 📊 **Name Dataset Processing**
  - Loading and preprocessing name datasets
  - Character-level tokenization
  - Vocabulary construction

- 🤖 **Deep Learning Models**
  - Neural network embedding layers
  - Name encoder architecture using PyTorch
  - Embedding vector generation for similarity matching

- 🧪 **Experimentation & Iteration**
  - Jupyter Notebook for experimentation (`main.ipynb`)
  - Modular model structure for scalability
  - Custom tokenization and encoding pipeline

- 🌐 **Similarity Matching**
  - Vector-based similarity computation
  - Finding semantically related names
  - Potential for real-time name matching applications

---

## 🛠 Tech Stack

- **Programming Language:** Python  
- **Libraries & Tools:**
  - PyTorch
  - NumPy
  - CUDA (GPU support optional)
- **Development Environment:** Jupyter Notebook

---

## 📁 Project Structure

```bash
SimilarNameFinder/
├── first_name.txt
│   └── Dataset of first names (2195+ names)
│
├── main.ipynb
│   └── Complete implementation and experimentation
│
└── README.md
```

---

## 🚀 Running the Project Locally

1. Clone the repository
   ```bash
   git clone https://github.com/Droid-DevX/SimilarNameFinder.git
   ```

2. Navigate to the project directory
   ```bash
   cd SimilarNameFinder
   ```

3. Install dependencies
   ```bash
   pip install torch numpy jupyter
   ```

4. Open and run the Jupyter Notebook
   ```bash
   jupyter notebook main.ipynb
   ```

---

## 🔮 Future Improvements

- Implement similarity search functionality to find closest name matches

- Add cosine similarity computation for embedding vectors

- Create a web API or UI for real-time name matching

- Expand dataset with international names and variants

- Implement approximate nearest neighbor search (Faiss/Annoy)

- Add evaluation metrics for name similarity quality

- Deploy as a REST API or web interface

---

## 👨‍💻 Author

Droid-DevX

GitHub: https://github.com/Droid-DevX

---

## 📄 License

This project is licensed under the MIT License.
