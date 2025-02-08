Overview

This project analyzes Ethereum transaction rates per minute using the Poisson distribution. The Poisson model helps predict transaction bursts, congestion, and gas fee fluctuations.
Why Poisson Distribution?

    Ethereum transactions occur randomly but follow a predictable pattern.
    Transactions per minute vary—some minutes have fewer transactions, while others experience spikes.
    This variability aligns with a Poisson distribution, making it useful for network congestion analysis and gas fee optimization.

What’s Inside?

✅ Python Script (ethereum_poisson.py) – Generates a simulated Poisson distribution for Ethereum transactions.
✅ Jupyter Notebook (ethereum_poisson.ipynb) – Run it in Google Colab for easy experimentation.
✅ Output Graph (ethereum_transactions.png) – A histogram showing transaction frequency per minute.
✅ README.md – Explanation of the analysis, code, and insights.
How to Use?

    Clone the repo:

git clone https://github.com/YOUR-USERNAME/ethereum-poisson-analysis.git
cd ethereum-poisson-analysis

Install dependencies:

pip install numpy matplotlib

Run the script:

    python ethereum_poisson.py

Or open the Colab notebook and run the cells for interactive analysis.
Live Demo in Google Colab

🔗 Open in Google Colab (Replace with actual Colab link)
Use Cases

    Predicting network congestion
    Gas fee optimization
    Blockchain analytics & trading models
    Ethereum Layer 2 scaling insights
