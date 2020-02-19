# Diffie-hellman key exchange

walkthrough of Diffie-Hellman Key Exchange.



Now, this is our solution. First, Alice and Bob agree publicly on a prime modulus and a generator, in this case, 17 and three. Then, Alice selects a private, random number, say 15, and calculates three to the power 15, mod 17, and sends this result publicly to Bob. Then Bob selects his private, random number, say 13, and calculates three to power 13, mod 17 and sends this result publicly to Alice. And now, the heart of the trick. Alice takes Bob's public result and raises it to the power of her private number to obtain the shared secret, which in this case is 10. Bob takes Alice's public result and raises it to the power of his private number, resulting in the same shared secret. Notice they did the same calculation, though it may not look like it, at first. Consider Alice, the 12 she receive from Bob was calculated as three to the power 13, mod 17. So her calculation was the same as three to the power 13, to the power 15, mod 17. Now consider Bob, the six he received from Alice was calculated as three to the power 15, mod 17. So his calculation was the same as three to power 15, to the power 13. Notice they did the same calculation with the exponents in a different order. when you flip the exponent, the result does't change. So they both calculated three to the power o their private numbers. Without one of there private numbers, 15 or 13, Eve will not be able to  find the solution. And this is how it's done;

While Eve is stuck grinding away at the discrete logaritm problem, and with large enough numbers, we can say it's practically impossible for her to break the encryption in a reasonable amount of time. This solves the key exchange problem. It can be used in conjunction with a pseudorandom generator to encrypt messages between  people who have never met. 





Comments:

1 how to find moudular and generator?