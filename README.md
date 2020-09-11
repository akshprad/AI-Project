# AI-Project
TSP with Genetic Algorithm 

Artificial Intelligence Mini Project- T(10)

A genetic algorithm is a search heuristic that is inspired by Charles Darwin’s theory of natural evolution.This algorithm reflects the process of natural selection where the fittest individuals are selected for reproduction in order to produce offspring of the next generation.


The process of natural selection starts with the selection of fittest individuals from a population. They produce offspring which inherit the characteristics of the parents and will be added to the next generation. If parents have better fitness, their offspring will be better than parents and have a better chance at surviving. This process keeps on iterating and at the end, a generation with the fittest individuals will be found.

This notion can be applied for a search problem. We consider a set of solutions for a problem and select the set of best ones out of them.

Five phases are considered in a genetic algorithm:

1.) Initial population<br>
3.) Selection<br>
4.) Crossover<br>
5.) Mutation<br>

<h1><b>Initial Population: </b><br></h1>
The process begins with a set of individuals which is called a Population.<br> Each individual is a solution to the problem you want to solve.
An individual is characterized by a set of parameters (variables) known as Genes.<br> Genes are joined into a string to form a Chromosome (solution).
<br>In a genetic algorithm, the set of genes of an individual is represented using a string, in terms of an alphabet. Usually, binary values are used (string of 1s and 0s). We say that we encode the genes in a chromosome.<br>

<h1><b>Fitness Function</b></h1><br>
The fitness function determines how fit an individual is (the ability of an individual to compete with other individuals). It gives a fitness score to each individual. The probability that an individual will be selected for reproduction is based on its fitness score.

<h1><b> Selection</b></h1><br>
The idea of selection phase is to select the fittest individuals and let them pass their genes to the next generation.<br>
Two pairs of individuals (parents) are selected based on their fitness scores. Individuals with high fitness have more chance to be selected for reproduction.

<h1><b> Crossover</b></h1><br>
Crossover is the most significant phase in a genetic algorithm. For each pair of parents to be mated, a crossover point is chosen at random from within the genes.

<h1><b> Mutation</b></h1><br>
In certain new offspring formed, some of their genes can be subjected to a mutation with a low random probability. This implies that some of the bits in the bit string can be flipped.<br>
Mutation occurs to maintain diversity within the population and prevent premature convergence.
<br>

To visualize, use p5:<br>
<href>https://editor.p5js.org/</href>
