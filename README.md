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
První instrukce změní skript download_minst.sh na spustitelný.
Druhá instrukce spustí skript, který stáhne dataset ručně psaných číslic MNIST ve formátu csv.

Po  stažení datasetu je možné spustit nn.py
```
$ chmod +x nn.py
$ ./nn.py
```
První příkaz změní program nn.py na spustitelný.
Druhý příkaz onen program spustí.

### Běh programu


