# Public key cryptography: What is it?

Why do we need public key cryptography?

After World War 2, with most of Europe in ruins, tension grew between the Soviet Union and the United States. It was clear that the next global superpower required the ability to both lanch and succssively defend nuclear attacks from intercontinental ballistic missiles. In North America, the most vulnerable point of attack was over the North Pole. So in 1958, a joint effort between United States and Canada was established, known as NORAD, or North American Aerospace Defense Command. An important line of defense was the semi-automatic ground environment. It was an automated system of over 100 long-distance radars scattered across North America. They were connected to computerized radar stations that transmitted tracking data using telephone lines or radio waves. All of this radar information was fed into a primary warning center buried a mile deep inside Cheyenne Mountain in Colorado. This application of machine to machine communication allowed operators to make split-second decisions using information transmitted and processed automatically by computers.  This idea of being online was quickly adapted and advanced by universities in the following years as they understood the potential of computer networking. 

Man: The thing that makes the computer communication network special, is that it puts that the workers that's be the team members who are geographically distributed in touch not only with one another, but with the information base with which they work all the time. And this is obviously going to make a tremendous difference in how we plan, organize, and execute almost everything of any interllectual consequence. If we get into a mode in which everything is handled electronically, and your only identification is some little plastic thing you stick into the machinery, then I can imagine that they want to get that settled up with your bank account just right now, and put it through all the checks, and that would require a network. 

Brit: Money transfers are just one of a growing number of application which required encryption to remain secure; and as the internet grew to encompass millions around the world, a new problem emerged. At the time, encryption required two parties to first share a secret random number, know as  a key. So how could two people who have never met agree on a secret shared key without letting Eve, who is always listening, also obtain a copy?

In 1976, Whitfield Diffie & Martin Hellman devised an amazing trick to do this. First, Let's explore how this trick is done using colors. How could Alice and Bob agree on a secret color without Eve finding it out? The trick is based on two facts: one, it's easy to mix two colors together to make a third color; and two, give a mixed color, it's hard to reverse it in order to find the exact original colors. This is the basis for a lock: easy in one direction, hard in the reverse direction. This is known as a one-way function. Now, the solution works as follows: First, they agree publicly on a starting color, say yellow. Next, Alice and Bob both randomly select private colors, and mix them into the public yellow in order to disguise their private colors. Now, Alice keeps her private color and send her mixture to Bob, and Bob keeps his private color and sends his mixture to Alice. Now, the heart of the trick: Alice and Bob add their private colors to the other person's mixture and arrive at a shared secret color. Notice how Eve is unable to determine this exact color, since she needs one of their private colors to do so. And that is the trick. Now, to do this with numbers, we need a numerical procedure which is easy in one direction and hard in the other. 





Reference:

Requirement is question. 

It is very hard to have been a good question.



