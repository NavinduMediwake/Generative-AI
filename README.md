# 📈 LSTM-GAN Stock Price Generator

This project implements an enhanced LSTM-based Generative Adversarial Network (GAN) to generate synthetic stock price sequences. It demonstrates how generative models can learn the temporal dynamics of real-world financial data.

---

## 🧠 Model Summary

- **Generator**: LSTM (2 layers) that generates realistic stock price sequences from noise
- **Discriminator**: Bidirectional LSTM that distinguishes real vs. fake sequences
- **Loss Function**: Binary Cross Entropy
- **Framework**: PyTorch

---

## 🗂️ Files

- `GenAI_Stocks.ipynb`: Jupyter Notebook implementing the full model
- `README.md`: Project overview and usage instructions

---

## 🚀 How to Run

1. Install requirements:
    ```bash
    pip install torch yfinance matplotlib scikit-learn
    ```

2. Open the notebook:
    ```bash
    jupyter notebook GenAI_Stocks.ipynb
    ```

3. Run all cells to:
    - Download and normalize stock data (e.g., AAPL)
    - Train the LSTM-GAN
    - Generate and visualize synthetic vs. real price sequences

---

## 📊 Example Output

![Example Plot](https://upload.wikimedia.org/wikipedia/commons/thumb/3/3c/Line_chart_example.svg/800px-Line_chart_example.svg.png)

> *Synthetic vs. Real stock price sequences*

---

## 💡 Key Concepts

- **Time Series GANs**
- **LSTM for sequential modeling**
- **MinMax normalization**
- **Financial data simulation**

---

## 📎 References

- [GANs in Finance — arXiv](https://arxiv.org/abs/1906.01253)
- [YFinance Docs](https://pypi.org/project/yfinance/)
- [PyTorch Documentation](https://pytorch.org/docs/stable/index.html)

---

## 📬 Contact

For any queries or collaborations, reach out at [your-email@example.com].

---

## ⭐ Star This Repo

If you found this helpful, please ⭐ the repo to support the project!
