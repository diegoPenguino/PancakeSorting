# Pancake Sorting

_Pancake Sorting is scientifically known as Sorting by Prefix Reversal, but we will call it Pancake Sorting to give a meaning that has some curious implication in real life._

Let&#39;s imagine we have a stack of n pancakes, one on top of another, and they all have different sizes, for the purpose of the exercise, well assign an integer value to represent the size of each pancake.

Now let&#39;s picture a spatula, we can insert this spatula between two pancakes at any point of our stack, and flip all the pancakes that are on top of the spatula.

<p align="center">
  <img src="https://github.com/anguloramiresd/PancakeSorting/blob/main/pancakes.PNG" width="650" title="example">
</p>

A _pancake number_ is the minimum number of flips needed to sort a given number of pancakes, where a stack of sorted pancakes has the biggest pancake at the bottom of the stack, and every pancake above the bottom one is smaller than the pancake below.

It has been shown that for any stack of ___N___ pancakes, the minimum number of flips required to sort it lies between ___1.0714 N___ and ___1.6364 N___ flips, but there is not an exact formula yet.
[Lower Bound](https://www.sciencedirect.com/science/article/pii/0012365X79900682?via%3Dihub), [Upper Bound](https://www.sciencedirect.com/science/article/pii/S0304397508003575?via%3Dihub)

There are simple algorithms, but inefficient for the purpose of the problem, these algorithms take ___2N - 3___ flips at most.

There are numerous ways to represent this problem on a computer, including graphs, permutations, strings and lists. We will try to take as many approaches as possible during the development of this project.

Pancake sort can be reduced from the NP-Hard problem 3-SAT, which implies that Pancake Sorting is also NP-Hard.
We can see the proof of such assertion in the following [paper](https://arxiv.org/abs/1111.0434v1).

There are some interesting practical purposes for this problem - in comparative genomics, or parallel processor networks, in which it can provide an effective routing algorithm between processors.

    But who needs practical uses of Sorting by Prefix Reversal when we can simply be hungry for sorted pancakes?


<p align="center">
  <img src="https://img.favpng.com/1/4/22/pancake-breakfast-english-muffin-waffle-bacon-png-favpng-svq3yuXZXUZwZ4jyTR3seYrfE_t.jpg" width="350" title="pancakes">
</p>



