# The Caesar cipher

Brit explains the Caesar cipher, the first popular substitution cipher, and shows how it was broken with "frequency analysis".



The first well known cipher, a substitution cipher was used by Julius Caesar around 58 BC. It's now referred to as the Caesar cipher. Caesar shifted each letter in his military commands in order to made them appear meaningless should the enemy intercept it. Imagine Alice and Bob decide to communicate using the Caesar cipher. First, they would need to agress in advance on a shift to use, say 3, so to encrypt her message Alice will need to apply a shift of 3 to each letter in her original message, so A becomes D, B becomes E, C becomes F, and so on. This unreadable or encrypted message, is then sent to Bob openly. Then Bob simply subtracts the shift of 3 from each letter in order to read the original message. Incredibly, this basic cipher was used by military leaders for hundreds of years after Caesar. However, a lock is only as strong as its weakest point, a lockbreaker may look for mechanical flaws or falling that extract information in order to narrow down the correct combination. The process of lock breaking and code breaking are very similar. The weakness of the Caesar cipher was published 800 years later by an Arab mathematician named AI-Kindi. He broke the Caesar cipher by using a clue based on an important property of the language the message is written in. If you scan text from any book and count the frequency of each letter, you'll find a fairly consistent pattern. For example, these are the letter frequencies of English. This can be thought of as a fingerprint of Englist. We leave this fingerprint when we communicate without realizing it. This clue is one of the most valuable tools for a codebreaker. To break this cipher, they count up the frequencies of each letter in the encrypted text and check how far the fingerprint had shifted. For example, if H is the most popular letter in the encrypted message instead of E, then the shift was likely 3. So they reverse the shift in order to reveal the original message. This is called frequency analysis and that was a blow to the security of the Caesar cipher. 





Reference:

1 Python密码学之旅---01古典密码之初识.<https://zhuanlan.zhihu.com/p/25157493>

