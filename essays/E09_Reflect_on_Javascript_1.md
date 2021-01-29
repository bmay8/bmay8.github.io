---
layout: essay
type: essay
title: What I've learned so far
# All dates must be YYYY-MM-DD format!
date: 2021-01-21
labels:
  - Learning how to install the editor 'Atom'
  - Learning Javascript
---

<img class="ui tiny left circular floated image" src="../images/atom.png">

Bradley May
ICS 314 - M/W - 9:00 AM - 10:15 AM
01/21/2021

E09: Reflect on Javascript 1

This class has been quite a bit of fun. It’s been a long time since I’ve written a scrap of code, but it’s not unlike riding a bicycle. Slowly but surely, the gears are starting to turn again. 

Case in point, the ‘Euler’ exercise initially took me hours to solve. I was aware of the time constraints of the ‘Workout of the day’ exercise, but I wished to dive deep and attempt to grasp the material and language on my own, before viewing the correct way to solve the problem. As such, I learned that I took a very unconventional and illogical route to the finish line. Rather than iterating through the integers and ‘capturing’ the threes and fives, I instead endeavoured to started with a ‘three variable’ and a ‘five variable’, put them in a loop and add their respective values each iteration: 

```
while (threes < num) {
    if (threes % 5 != 0) {
      eulerArray.push(threes);
    }
    threes += 3;
    if (fives < num && fives < threes) {
      eulerArray.push(fives);
      fives += 5;
    }
  };
```  

This isn’t technically incorrect, but it is needlessly complicated and required quite a bit of debugging. For instance, when the numbers three and five added successively, they both eventually add up to ‘15’. And consequently, ‘15’ was added to the ‘eulerArray’ twice. It took an embarrassingly long time to work out how to correct that. 

The next iteration was a bit more streamlined and only took 6 minutes to code, making use of a ‘for loop:

```
for (let i = 0; i < maxInteger; i++) {
    if (i % 3 == 0) {
      arr.push(i);
    } else if (i % 5 == 0) {
      arr.push(i);
    }
 ```
 
Similarly, the third iteration only took 2 minutes and 48 seconds. Again though, the professor’s implementation was vastly superior.

Back to square one with the ‘is it unique’ problem though. I toiled for hours before arriving at an unwieldy solution. But iterations 2, 3 and 4 became successively shorter and more optimized, making use of new methods and functions. It was all a bit quicker after I finally managed to get the Atom editor up and running (my internet is so slow that JSFiddle was effectively inoperable). 

