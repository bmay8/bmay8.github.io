---
layout: essay
type: essay
image: images/question.jpg
title: How to design smart questions
# All dates must be YYYY-MM-DD format!
date: 2021-01-28
labels:
  - Internet Etiquette 
  - Stack Overflow
---

<img class="ui tiny left circular floated image" src="../images/stackoverflow.png">

Bradley May
01/28/2021
	
# Intelligent questions get intelligent answers


It’s often pointed out that in the software industry, communication skills are a vital necessity. This isn’t technically unique to the profession. Every endeavor has a learning curve and more often than naught, can be helped along by asking constructive questions. 

The problem is that the questions inherent in, say, learning a new programming language can be very complicated and very simple, depending on the user's experience. 

‘Constructive questions’ are the keywords here though. When querying a mailing list, forum or developer for a resolution to a specific dilemma, there’s an unwritten contract involved. Or at least, to this user’s knowledge, it was unwritten prior to reading Eric Raymond’s all-encompassing dissertation about “How to Ask Questions the Smart Way”. As Mr Raymond points out in his article, there are a number of rules one should observe when requesting free knowledge from strangers on the internet. 

This manner of internet etiquette is predicated on the understanding that you should “Never assume you are entitled to an answer. You are not, after all, paying for the service.” [1]. As such, trying to get your point across as efficiently and succinctly as possible should be a principle strategy when formulating a question.

It may help to observe a few instances of ‘good’ and ‘bad’ questions though. For instance, one user posted a question about a specific dilemma when implementing a feature in the CSS language ‘Bootstrap’ [2]. The question begins with a concise description of what’s going on:

> width -webkit-fill-available is causing text selection on mouse click scrolling

And then proceeds with a clearer explanation elaborating on the issue. It’s kept brief, and then they help further troubleshoot the problem by explaining their initial attempts at rectifying it:

> “I had applied width:inherit the test project was successful in Bootstrap 4, but…”

And finally, they include a segment of their code, giving a clearer picture of what they’re working with. 

```css
.left-img{ 
  width: -webkit-fill-available; 
  margin-top: 2rem; } 

@media(max-width:992px){ 
  .left-img{ 
    margin-top: 00.5rem; 
  } 
} 

@media(max-width:768px){ 
  .left-img{ 
    margin-top: 00.25rem; 
  } 
}
```

The response that followed was quick, concise and clear, subsequently demonstrating the efficiency of this format of ‘question/answer’.  

With this in mind, let’s take a look at a poorly formatted question [3]. This user opens the somewhat cryptic title:
	
> Hidden div window

They’re working with Node.js and are attempting to create a ‘username/password’ interface, but this title doesn’t immediately explain that. Furthermore, there is no mention of the code being used or any screenshots alluding to such. Instead, what’s offered is an open ended request, asking: 

> “What is the best way to open that input window?”

This isn’t a request on how to properly implement a certain line of code, but rather an entreaty for someone to research and write the code for them. It goes without saying that this is poor form and not something that should be encouraged. 

In summary, when requesting information and assistance from peers and strangers, it’s best to be tactful, descriptive and concise. Don’t waste the other user’s time on needless details, but likewise, don’t omit so much information that your query appears vague or unclear. Most of all though, it’s very much appreciated if one does the proper leg work and research ahead of time. Before posting a question. Even if an individual remains uncertain after leafing through forums and documents, this exercise will doubtlessly help guide them towards a succinct, intelligent way of framing their question.


1. [How to Ask Questions the Smart Way - Eric Steven Raymond] (How to Ask Questions the Smart Way, 2001, http://www.catb.org/esr/faqs/smart-questions.html)  
2. [Smart Question] (https://stackoverflow.com/questions/65948309/width-webkit-fill-available-is-causing-text-selection-on-mouse-click-scrolling) 
3. [Clumsy Question] (https://stackoverflow.com/questions/65948243/hidden-div-window) 
