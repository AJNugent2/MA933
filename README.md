# MA933
Resources for the MA933 Stochastic Modelling and Random Processes module.
My thanks to Kamran Pentland and Susana Gomes for creating these resources. 

This project uses python 3.9. You can create a new conda virtual environment with the following command.
```bash
conda create -n MA933 python=3.9.12
```
Then activate it using
```bash
conda activate MA933
```
After doing this, you should see the environment name in brackets at the beginning of your command prompt.
If you are slightly lazy (like me) you can make an alias that will open the MA933 folder and activate the environment together. 

In bash aliases add 
```bash
alias ma933='cd ~/Documents/MA933 && conda activate MA933'
```

Then install package versions listed in `requirements.txt`.
```bash
conda install --file requirements.txt
```
