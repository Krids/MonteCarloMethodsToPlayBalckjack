# MonteCarloMethodsToPlayBlackjack

*I will write my own implementations of many Monte Carlo (MC) algorithms.*

In this project, you will design an agent to learn Blackjack and use an instance of the Blackjack environment provide by OpenIA. 

## Project Instructions

1. Clone the repository and navigate to the downloaded folder.

```
git clone https://github.com/MonteCarloMethodsToPlayBlackjack.git
cd MonteCarloMethodsToPlayBlackjack
```

2. Create and activate a new environment.

```
conda create -n blackjack python=3.6 matplotlib numpy pandas
source activate blackjack
```

3. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `blackjack` environment. 
```
python -m ipykernel install --user --name blackjack --display-name "blackjack"
```

4. Open the notebook.
```
jupyter notebook Monte_Carlo.ipynb
```

5. Before running code, change the kernel to match the `blackjack` environment by using the drop-down menu (**Kernel > Change kernel > quadcop**). Then, follow the instructions in the notebook.

6. You will likely need to install more pip packages to complete this project.  Please curate the list of packages needed to run your project in the `requirements.txt` file in the repository.
