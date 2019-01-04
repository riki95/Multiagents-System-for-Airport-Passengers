# Multiagents System for Airport Passengers

University Project for Multiagents Systems Course.

This is an implementation of queues inside the airport developed with Netlogo.

## Getting Started

To download my repo:

```
git clone https://github.com/riki95/Multiagents-System-for-Airport-Passengers
```

The program was written and executed with [Netlogo](https://ccl.northwestern.edu/netlogo/).
Once it's installed, just click on the program and press "Open" to open my .nlogo file.

### Interface and behaviour

![Interface](https://i.gyazo.com/c87fb1f55dc0e388e18af169d394ab79.png)

The interface is quite simple.
You can open/close queues and increase or decrease the number of passengers.
When you clic on Setup the passengers are at the entrance of the airport. 
Pressing "Go" you will make the passengers move in nontrivial ways. 
If they hit a green patches, they enter the queue and go to the metal detector, which is colored by grey.
If they meet a red, the queue is closed and they go back.
After they have been scanned at the metal detector, they face the yellow patches which is the exit and they get out.

## Monitors and study

![Monitors](https://i.gyazo.com/fda87db3533d89a65d8e3ebac0264a47.png)

With this implementation we want to study queues inside the airport basing on some parameters.
If you want to check how many people there are inside the airport and in a certain queue, you can watch to the monitors.
They are updated at each step with some functions that I've developed in the code section.
These functions are also used for experiments.

## Experiments

Since we are not supposed to run manually different experiments, I've done a set of experiments under the experiment section.
By pressing it we can modify the queues opened or not and set the values we want to check.
We can also test our simulation for different number of passengers.
Once we're ready, we press run and a dataset is generated.
Inside my experiment folder, there are 2 experiments:
* The first one is Experiment1 and has been done opening and closing different queues for 101 passengers
* The second one is Experiment2 and has been done opening and closing different queues for 496 passengers
You can have fun running experiments for different values but these are some case limit that I wanted to study.

## Author

* **Riccardo Basso** - Università degli studi di Genova - *Multiagents Systems 2018-2019*
