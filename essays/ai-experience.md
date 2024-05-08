---
layout: essay
type: essay
title: "Experiencing Artificial Intelligence"
# All dates must be YYYY-MM-DD format!
date: 2024-05-03
published: true
labels:
  - Artificial Intelligence
  - ChatGPT
  - Software Engineering
  - Education
---

### I. Introduction

Artificial intelligence is still very much in its infancy, and the use of tools like ChatGPT and Co-Pilot in the education field is the center of much debate, as is how to incorporate them into the learning environment. While learning to work with AI is a skill that is becoming more and more valuable, the amount of prompt tweaking needed can make it seem gimmicky, and the hallucinations mean whatever it puts out can't be fully trusted. So for now, it can only really complement traditional learning and is best used with caution. Whether that is researching what it is saying, possessing a degree of knowledge already of the topic, or, as in the case of software engineering, testing the code it generates before deploying it to a live environment. The times I have used ChatGPT and Co-Pilot, I've found them to often be useful, but not always.

### II. Personal Experience with AI:

I have used AI in class this semester in the following areas:

##### 1. Experience WODs e.g. E18

I didn't use help from AI during the experience WODs at home. Because they were not graded for correctness, or even complete code, I could afford to search documentation or google for help if I needed it. If I still couldn't find the help I need, I knew I had the instructor's video walkthrough of the WOD that I could review.  

##### 2. In-class Practice WODs

Same as the experience WODs, the in-class practice WODs weren't graded for correctness, so I opted to not seek help from AI. These often followed along the same topic or concepts as the preceding experience WODs, so I had more familiarity going into it. If I needed assistance, I would search, google, or ask for help from teammates.

##### 3. In-class WODs

For most of the in-class WODs, the preceding practice/experience WODs sufficiently prepared me for the actual WOD to the point that I didn't need to seek help from AI. The searching and googling done previously were often enough, and I would know where to go exactly for the specific thing I was looking for. Some of the WODs though, I did utilize ChatGPT for help. One in particular, I completely blanked on what to do, so I input some of the WOD instructions into ChatGPT and it output enough to kickstart me so I could complete it. I've used it on others to fix mistakes that I had made.

##### 4. Essays

For some of the essays, I tried inputting the prompt into ChatGPT to see what it spits out. I tried a few different variations of the prompt, such as telling it to be less technical, more casual, not too bloggy, but it never spat out anything good, so I didn't use any of its suggestions. I did, however, use it to correct any spelling or grammatical mistakes that I missed, as well as assist in markdown formatting.

For this essay, I used ChatGPT to finish out the last few sections, V through VIII. Usually, I don't think what it puts out for the technical essays is any good, but in this instance, I thought it was pretty decent and ended up using it. For the prompt, I copied and pasted the entirety of the essay that I had finished up until section V and said for it to create responses to the instructions under V through VIII. [ChatGPT Prompt](https://chat.openai.com/share/69c863fe-ea8a-45c4-9d25-5733b69d9ef8)

##### 5. Final project

For the final project, I didn't use ChatGPT because I wasn't sure how to efficiently feed it all the files so that it sees how my code interacts with everything. I tried using Co-Pilot since it's built into the IDE and can see all of the files, but it didn't really output anything I could use.

##### 6. Learning a concept / tutorial

The only concept that I used AI for was the topic of fundamental programming. Specifically I was trying to understand what 'map' does under the hood. Since I had only really been exposed to imperative programming, the declarative nature of 'map' was foreign to me, and I kept trying to think of it as a 'for' loop. ChatGPT said it can be conceptually thought of as one, but the 'map' function provides a "higher-level abstration" and the actual implementation is more complex and handles various edge cases, optimizations, and error checking. It also said, "in summary, higher-level abstractions offer a more conceptual, expressive, and readable way to work with programming concepts, allowing developers to focus on solving problems rather than managing implementation details", which I took as ChatGPT telling me to stop worrying about it. But it was helpful.

##### 7. Answering a question in class or in Discord

I did not use AI for this simply because I did not think about doing so.

##### 8. Asking or answering a smart-question

I did not use AI for this simply because I did not think about doing so, but that would have been good to try out.

##### 9. Coding example e.g. “give an example of using Underscore .pluck”

I forgot what the not equal operator was in JavaScript, so I asked ChatGPT, "in javascript, create a sample while loop with a not equal condition", and it replied with
```
let count = 0;

while (count !== 5) {
  console.log("Count is: " + count);
  count++;
}

console.log("Loop exited because count is now equal to 5.");
```

##### 10. Explaining code

Most of what I've used ChatGPT for is to explain code. Both JavaScript and functional programming were new to me in ICS 314, so a lot of the questions I asked were about explaining syntax, slightly different keywords, or small code snippets. A couple of examples, I asked, "In javascript, what's the difference between: ```for (let x of y)``` and ```for (let x in y)```", and , "In javascript, what's the difference between ```slice``` and ```splice```?". For both pairs, it gave me a breakdown of what each one does and when to use them, as well as example code snippets.

##### 11. Writing code

For the in-class WOD that I had completely blanked on, I simply fed ChatGPT the code outline from the instructions (2 classes with constructors and undefined but descriptively named methods, along with the method calls and expected answers), and it gave me pretty much everything I needed. I had to make a couple adjustments to my prompt, so I first edited it to say, "don't add any new methods to implementation", then, "and don't change the properties of class Score". After that, I had to make a couple small tweaks and additions to the code, particularly to the math it used, and I was done. [ChatGPT Prompt](https://chat.openai.com/share/a63f41e0-962c-41a2-bf9f-66f9380aada7) / [JSFiddle](https://jsfiddle.net/sgills/k36sqn01/28/)

##### 12. Documenting code

I did not use AI for this because I didn't comment on code as much as I should have in this class, but this would have been an excellent use of it.

##### 13. Quality assurance 

I wouldn't say this is an example of quality assurance, but I needed help troubleshooting what it was that I was doing wrong with a function. I provided ChatGPT with the function as well as what I was trying to do with it and a sample of the objects I was working with. It pointed out what specifically I was doing wrong with my ```_.mapObject()``` method and corrected it, while also providing an explanation. [ChatGPT Prompt](https://chat.openai.com/share/0bfaad8f-a163-4704-8b16-1473aedd95c3)

##### 14. Other uses in ICS 314 not listed above

There were quite a few times that I used ChatGPT to help me in the command prompt. One example is when my computer is still listening on port 3000 even after I had supposedly quit out of the service (such as Meteor). I started off with "windows operating system using cmd, how do i list open ports?" to which it replied with ```netstat -an```. I followed up with "how do i kill a particular connection?", and ChatGPT revised it to ```netstat -ano``` to list process ID associated with port 3000 so that I can use ```taskkill /PID [PID] /F``` to kill it. [ChatGPT Prompt](https://chat.openai.com/share/66afe21a-2e9a-4317-b46d-520a0512ebb7)

### III. Impact on Learning and Understanding:

I think AI positively impacts the learning experience, and it has for me. The other traditional avenues of learning are still there, and AI does not replace them, it complements them. In my experience, ChatGPT has been good to get quick answers, or to rephrase something in a different way. It doesn't get annoyed at you for not understanding, and it's always there, in contrast to a person that may not be able to explain it in a way that you get, or they step away from their computer.

### IV. Practical Applications:

Looking back through my ChatGPT history, I haven't yet used it for a practical application outside the scope of ICS 314, and it was not until ICS 314 that I used Co-Pilot. My prompts for ChatGPT usually revolved around a random thought or question I had, like "What was Orlando known for before Disney World?" or "What does 'Every language has its warts' mean?".

### V. Challenges and Opportunities:

Challenges in utilizing AI within the course include the need for careful consideration of its limitations, such as the necessity for prompt tweaking and the occasional generation of unreliable outputs. Opportunities for further integration lie in leveraging AI for personalized learning experiences, adaptive assessments, and real-time feedback mechanisms. Addressing these challenges while exploring these opportunities could significantly enhance software engineering education.

### VI. Comparative Analysis:

Comparing traditional teaching methods with AI-enhanced approaches in software engineering education reveals nuanced differences. While traditional methods offer interpersonal engagement and opportunities for in-depth discussions, AI-enhanced approaches excel in providing immediate assistance, personalized feedback, and access to vast knowledge repositories. The combination of both methodologies can optimize engagement, improve knowledge retention, and foster practical skill development effectively. 

### VII. Future Considerations:

The future role of AI in software engineering education holds immense promise. Advancements in natural language processing, machine learning, and AI-driven adaptive learning platforms can revolutionize how concepts are taught and learned. However, challenges such as ensuring ethical use, maintaining student privacy, and addressing biases in AI algorithms require careful consideration. Continued research, development, and collaboration between educators and AI developers will be crucial in maximizing the benefits of AI in education. 

### VIII. Conclusion:

Reflecting on my use of AI in ICS 314, it's evident that AI serves as a valuable tool for augmenting learning experiences. My recommendations for optimizing its integration in future courses include providing clear guidelines for its usage, fostering a culture of critical thinking alongside AI assistance, and continuously evaluating its effectiveness in addressing educational objectives. With thoughtful implementation and ongoing refinement, AI has the potential to greatly enhance software engineering education.
