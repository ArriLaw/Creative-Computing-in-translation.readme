# Beauty Lies In The Eyes Of The Beholder

How is coding creative? is the first question I asked myself when introduced to creative computing. 

Coding boosts and strengthens our brains. It increases creativity, analyzing problems, and logical thinking of solving problems. 
"is it possible for jobs like software engineering to be classed as a creative career?". Despite what you may think, The truth is that software development requires a lot of creativity! I know crazy right. 
While coding doesn't normally involve complete freedom of expression in the same way that art and music does, the creativity involved with coding is technical creativity, where people create new theories, technologies or ideas.
As a creative practisioner you have most likely already used technical creativity in your practice without realizing it. Weather that's through excersing your creative thinking using spiderdiagrams or sketchbooks to record ideas. 

Applying Technical creativity to coding:

The first aspect of creativity in code is figuring out how to use code to solve problems given particular constraints. Think about this puzzle for a second: Like an escape room, Imagine you're locked inside a house, and you have just a rope, a box of matches, and an egg. How can you escape? I have no idea what the answer to this puzzle is, but it certainly takes creativity to figure it out! I'm sure if you have read or watched Sherlock Holms, you know he uses a lot of creativity, often approaching clues like parts of a code he needs to solve.

A second aspect of creativity comes with the optimization of code. When one first learns to code, their main focus is on getting their code to work. But when one becomes more proficient, they start figuring out tricks and techniques to make their code run faster and consume less memory. There are some legendary stories about how early Nintendo programmers used creative hacks to fit their large games onto a single Nintendo cartridge that had very limited storage space!

A third aspect of creativity is being able to write code that is easy for other developers to understand and maintain. Again, when one first learns to code, their focus is on getting the code to work. But as they level up, they begin to consider that code isn't only for the computer to read; at some point, other software developers will need to read and update the code as well. It takes great creative skill and communication ability to write code that humans can easily read while the computer can still properly execute it. Some refer to this kind of code as "beautiful code."

What is beautiful code?

How can coding be described as beautiful?

Asking myself these questions, I discovered a forum where softwear engineers discussed what "beautiful code" means to them:

“I think most programmers will agree that beautiful code demonstrates a balance between clarity and transparency, elegance, efficiency and aesthetics.”

“It's just a figure of speech. Beauty lies in the eyes of the beholder, and beyond that, it's all about the clarity of the instructions that you've laid down in a text file to solve a problem, and how easily you or anyone else can modify and maintain it in the future. Beyond that, how much more beauty your code exudes is entirely up to you - indentations, modular structure, complexity, efficiency simultaneously with easy readability, naming conventions,etc.” 

"Beauty has many sources. When it comes to software development, beauty is conferred by simplicity and architectural coherence, which go hand in hand with the functional precision as well as the creativity applied to solve the problem in question. Likewise, the coding style is an integral part of the code’s elegance and should not be underestimated when it comes to improving the development team’s communication."

Looking deeper into the Q and A I noticed the use of other descriptive language, inlcuding words such as Elegant and even cute. I wanted to look further into the more visual side of coding...

The Visual side of coding:

Clarity and Transparency: Clarity is how easily a reader can deduce what the code does. Transparent code does what it seems to do. If code seems to do one thing but actually does something else (or something more), it's not transparent - it's misleading.

Elegance: there are many ways to implement most algorithms, but some ways are clumsy while other ways are neat and graceful. Succinctness often adds elegance, but excessive succinctness can reduce clarity.

Efficiency: avoiding unnecessary use of resources (such as CPU time, memory, and I/O).
Aesthetics: being easy on the eyes. This is quite subjective. It mostly comes down to style. One important consideration is to have a consistent style. Code which changes, for example, indenting style halfway through, is ugly.
 
Elegant code: uses cleverness to accomplish something in much less code than most people would think possible, but in a way that's readable and obvious. ... It uses the cleverness of recursion to produce a program able to solve the problem in much less code than the non-recursive version.
Elegant code example: Here is another example, the Fast Inverse Square Root code, found in the game Quake. All it does is basically calculate (1/√x). You’re thinking, why not calculate the square root, and divide in the regular way? Well, division, and square root calculation are expensive (or at least they used to be). So looking for a better way of performing this in a program which may use the calculation millions of times a second may be important – nobody likes slow games. Here is the code for the function invSqrt(), (obviously in C), derived from the original code:
 
1  float invSqrt(float x){
2     long i;
3     float x2, y;
4     x2 = x * 0.5F;
5     i = *(long*)&x;
6     i = 0x5f3759df - (i >> 1); 
7     y = *(float*)&i;
8     y = y*(1.5F - x2*y*y);
9     return y;
10 }

Making Art From code

an introduction to creative coding



 
 



