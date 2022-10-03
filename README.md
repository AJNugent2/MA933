# MA933 - Stochastic Modelling and Random Processes
My thanks to Kamran Pentland and Emma Southall for creating these resources, and to Jack Buckingham for originally writing most of this README. 

The module webpage can be found [here](https://warwick.ac.uk/fac/sci/mathsys/courses/msc/ma933/).

Lecturer: [Susana Gomes](https://warwick.ac.uk/fac/sci/maths/people/staff/gomes/) 

Teaching Assistant: [Andrew Nugent](https://warwick.ac.uk/fac/sci/mathsys/people/students/2021intake/nugent/)

## Setup

You can clone this repository using the following command. This will create a folder called MA933 containing the respository (so you don't need to make a folder first). Go to your Documents folder and enter:
```bash
git clone https://github.com/AJNugent2/MA933
```

This project uses python 3.9. You can create a new conda virtual environment with the following command.
```bash
conda create -n MA933 python=3.9.12
```
Then activate it using
```bash
conda activate MA933
```
After doing this, you should see the environment name in brackets at the beginning of your command prompt.

Then install package versions listed in `requirements.txt`.
```bash
conda install --file requirements.txt
```

If you are slightly lazy (like me) you can make an alias that will open the MA933 folder and activate the environment together. To set up an alias like this, you can create a file in your home directory called `.bash_aliases` (if it doesn't already exist) and add the following line to it. You may need to edit this slightly depending on where your local version of the respository is. 
```bash
alias ma933='cd ~/Documents/MA933 && conda activate MA933'
```

## Contents of each notebook

`Support Class 1.ipynb`
* Basic commands
* Linear algebra basics
* Simple random walk exercises 

`Support Class 2.ipynb`
* Sheet 1 simulations
* Q3(c): Three state Markov chain
* Q4(c): Wright-Fisher model

`Support Class 3.ipynb`
* Sheet 2 simulations
* Q1(c/d): DTMC simulation (e'vals/e'vectors/stationary distributions)
* Q2(d): geometric random walk

`Support Class 4.ipynb`
* Sheet 3 simulations
* Q2: CTMC simulation
* Q3: playing with multivariate Gaussians
* Q4: Geometric Brownian Motion SDE
* Q5: Fractional Brownian motion/Brownian Bridges/Gaussian Processes

`Support Class 5.ipynb`
* Sheet 4 simulations
* Q2: Contact process simulation (with Gillespie algorithm)

`Support Class 6.ipynb`
* Sheet 5 simulations
* Q2: Using the 'networkx' package to simulate random networks

## LaTeX
It's recommended you use Overleaf (particularly useful for group projects as multiple people can work on the same document at the same time). You can sign up with your Warwick details (and you should have access to premium features): [https://www.overleaf.com/](https://www.overleaf.com/)

## Other Useful links (for this module)

* Log Normal Distribution: [https://en.wikipedia.org/wiki/Log-normal_distribution](https://en.wikipedia.org/wiki/Log-normal_distribution)
* Log Normal Scipy Documentstion: https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.lognorm.html
* KDE plot visualisation: https://mathisonian.github.io/kde/
* Fokker-Planck Equation: book Stochastic Processes in physics and chemistry - N.G. Van Kampen
* Ornstein-Uhlenbeck process: [https://en.wikipedia.org/wiki/Ornstein%E2%80%93Uhlenbeck_process#Fokker%E2%80%93Planck_equation_representation](https://en.wikipedia.org/wiki/Ornstein%E2%80%93Uhlenbeck_process#Fokker%E2%80%93Planck_equation_representation)
* Colour options in matplotlib [https://xkcd.com/color/rgb/](https://xkcd.com/color/rgb/)
