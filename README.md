# ZUM semestrální práce

Úkolem bylo vypracovat dopřednou neuronovou síť (FFA neural network), s jednou input layer, jednou hidden layer a jednou output layer, klasifikující ručně psané číslice z datasetu MNIST bez použití knihoven pro strojové učení, jako jsou například keras, nebo tensorflow. Je použita zjednodušená verze datasetu ve formátu csv viz https://pjreddie.com/projects/mnist-in-csv/.


### Závislosti

python3, numpy, scipy, datetime

instalace python3 s package managerem aptitude

```
apt-get install python3
```

instalace modulů s pip3
```
$ pip3 install numpy scipy datetime
```

### Spuštění

pred spuštěním nn.py je třeba stáhnout dataset 

```
$ chmod +x donwnload_mnist.sh
$ ./donwload_mnist.sh
```
Prvni instrukce zmení skript download_minst.sh na spustitelny.
Druhá instrukce spustí skript, který stáhne dataset ručně psaných číslic MNIST ve formátu csv.

Po  stažení datasetu 
Astep by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

