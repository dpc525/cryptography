# Polyalphabetic cipher

Brit introduces the polyalphabetic cipher, which creates a lighter fingerprint than the Caesar cipher. Created by Brit Cruise.



A strong cipher is one which disguises your fingerprint. To make a lighter fingerprint is to flatten this distribution of letter frequencies. By the mid-15th century, we had advanced to polyalphabetic ciphers to accomplish this. Imagine Alice and Bob shared a secret shift word. First, Alice converts the word into numbers according to the letter position in the alphabet. Next, this sequence of numbers is repeated along the message. Then each letter in the message is encrypted by shifting according to the number below it. Now she is using multiple shifts instead of a single shift across the message, as Caesar had done before. Then the encrypted meaaage is sent openly to Bob. Bob decrypts the message by subtracting the shifts according to the secret word he also has a copy of. Now imagine a code breaker, Eve, intercepts a series of message and calculates the letter frequencies. She will find a flatter distribution, or a lighter fingerprint. So how could she break this? Remember, code breakers look for information leak, the same as finding a partial fingerprint. Any time there is a differential in letter frequencies , a leak of information occurs. This difference is casused by repetition in encrypted message. In this case, Alice's cipher contains a repeating code word. To break the encryption, Eve would first need to determine the length of this shift word used, not the word itself. She will need to go through and check the frequency distribution of different intervals. When she checks the frequency distribution of every fifth letter, the fingerprint will reveal itself. The problem now is to break five Cesar Ciphers in a repeating sequence. Individually this is trivial task, as we have seen before. The added strength of this cipher is the time taken to determine the length of the shift word used. The longer the shift word, the strong the cipher.



Reference:

1 https://www.khanacademy.org/computing/computer-science/cryptography/crypt/v/polyalphabetic-cipher



