## 🛠 Tools & Libraries Used

- Python 3.x
- PyTorch
- Hugging Face `datasets`
- NumPy
- Matplotlib

---

## 🔢 How It Works

1. Load and clean the dataset
2. Tokenize text and build vocabulary
3. Create input-output sequences
4. Build RNN model using Embedding + LSTM + Dense
5. Train the model with CrossEntropyLoss and Adam optimizer
6. Predict the next word from a given seed sentence
7. Visualize loss using Matplotlib

---

## 📈 Sample Output

**Input**: `"the meaning of life is"`  
**Predicted Next Word**: `"love"`

---

## 📊 Loss Visualization

After training, the loss per epoch is plotted to analyze the model’s learning progress.

---

## 💡 Future Improvements

- Switch to GRU or Transformer-based model
- Use character-level prediction
- Train on larger datasets with GPU
- Build a web app using Streamlit

---

## 👩‍💻 Author

**Sarita Singh**  
Feel free to connect with me on [LinkedIn](#) or check out my other projects!

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
