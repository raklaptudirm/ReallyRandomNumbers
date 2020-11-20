# ReallyRandomNumbers
Random numbers in computers are not actually random. Since computer is a perfect machine, it has no hold on randomness. Random numbers generated by the computer are actually [pseudo-random](https://www.geeksforgeeks.org/pseudo-random-number-generator-prng/), a _function_ which generates a sequence of numbers which look like they are random, a _pseudo-random sequence_, based on a _seed_, an argument accepted by the function which acts as the base of the sequence.

As, I have mentioned above, the computer is a **_perfect-machine_**, so it has no hold on randomness. No number generated by a computer are completely random as I have mentioned.

But when I was working on my JavaScript library, [Precise.js](https://github.com/raklaptudirm/Precise.js), and was speed-testing the funtions, I found that the amount of time required by the compiler varies between two values, _randomly_. So, here is a __ReallyRandomNumber Generator__.
