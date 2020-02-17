# The discrete logarithm problem

A mathematical lock using modular arithmetic.

We need a numerical procedure, which is easy in one direction and hard in the other. This brings us to modular arithmetic, also known as clock arithmetic. For example, to find 46 mod 12, we could take a rope of length 46 units and rap it around a clock of 12 units, which is called the modulus, and where the rope ends is the solution. So we say 46 mod 12 is congruent to 10, easy.

Now, to make this work, we use a prime modules, such as 17, then we find a primitive root of 17, in this case three, which has this important property that when raised to different exponent's, the solution distirbutes uniformly around the clock. Three is known as the generator. If we raise three to any exponent x, then the solution is equally likely to be any integer between zero and 17. Now, the reverse procedure is hard. Say, given 12, find the exponent three needs to be raised to. This called the discrete logarithm problem. And now we have our one-way function, easy to perform but hard to reverse. Given 12, we would have to resort to trial and error to find matching exponents. How hard is this? With small numbers it's easy, but if we use a prime modulus which is hundreds of digits long, it becomes impractical to solve. Even if you had access to all computational power on Earth, it could take thousands of years to run through all possibilities. So the strength of a one-way function is based on the time needed to reverse it.

Reference:
1 https://www.khanacademy.org/computing/computer-science/cryptography/modern-crypt/v/discrete-logarithm-problem

