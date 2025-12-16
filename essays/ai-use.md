---
layout: essay
type: essay
title: "Reflection on My AI Use and More"
# All dates must be YYYY-MM-DD format!
date: 2025-12-15
published: true
labels:
  - Software Engineering
  - AI
---

<img width="300px" src="../img/copilot-logo.jpg" alt="GitHub Copilot logo">

## The Role of AI in education and software engineering

With the prevalence of AI now, generative AI being used in education seems unavoidable. The role of AI in education should be to help students and aid the learning process. AI aiding the learning process can be done through breaking down and explaining more complex topics, and finding resources for research. In the context of software engineering, AI can be used to help developers learn by explaining bugs and how to resolve them, explaining code syntax and concepts based on documentation, and generating initial code solutions. In both education and software engineering, AI is a very slippery slope because it can be very easy to become overreliant on it to get to a solution. Just copying and pasting code from AI will never help anyone learn how to actually code. Even with AI, it’s important to use your brain and other resources before relying on AI. It’s also important to know that generative AI is just an amalgamation of information that humans have already come up with; nothing that AI creates is original, so the solution to your problems has most likely already been solved by someone else. AI is just another tool, don’t let it become a crutch. 

This semester in ICS314, I used ChatGPT 5 and Claude Sonnet 4 in the browser, and GitHub Copilot in VSCode. 

## My personal experience with AI in ICS314

<br />
### WODs, practice WODs, and in-class practice WODs

In my ICS314 Software Engineering class, we had timed coding exercises called WODs (Workout of the Day, the term is borrowed from CrossFit) that we did in class every Wednesday. We had practice WODs as homework assignments in order to prepare us for the upcoming WOD on Wednesday, and we also had in-class practice WODs on the Mondays before the WODs on Wednesday. When I used AI for all three of these exercises, I used it to try and get a better understanding of the problem, which usually required pasting the WOD instructions into the generative AI and asking it to further explain the instructions. It was pretty useful in explaining problems and breaking down problems into a simple step by step solution. The code solution it usually generated was usually never good, however, that’s alright though. I also remember having Claude generate tests for me on the first WOD, and all of them passed, so I thought my code was good. Unfortunately, it turned out that those generated tests didn’t account for a couple edge cases, so I ended up failing that WOD. I never had AI make tests for me after that. 

### Essays

I never used AI in writing my essays because it sucks at writing, and it’s painfully obvious when someone does use AI for writing. I think that it was more important to express my actual opinions on topics rather than using a bland, AI-generated opinion, so that’s why I never used it for essays. 

### Final project

For my final project in ICS314, I made use of both GitHub Copilot autocompletion and chat features. I found the autocompletion to be useful, especially when typing objects and components that hadn’t been imported into the TypeScript file yet. I also prompted Copilot chat to generate some code for a component; it was helpful because the component I wanted to implement had almost identical structure to another component within the code base. There are times when Copilot autocomplete and chat is annoying, however. When I knew exactly what I wanted to code, but Copilot’s autocomplete generated something completely different from what I was thinking about; that was annoying. One annoying thing about Copilot chat (similar to browser generative AI) is hallucinations and giving me answers that were flat out unhelpful. Overall, I’d say that AI was pretty useful in working on my final project. 

### Learning a concept

I don’t think that I used AI to learn a specific concept this semester because the documentation that the course curriculum provided was good for the most part. Even though it takes a bit longer to read through documentation, I found it to be more helpful than just using AI because while AI can just make things up, the documentation was written by people who actually know that topic. For example, the Prisma documentation is really good for the most part. 

### Answering a question in class or in Discord

I can’t speak on answering questions in Discord because I never did, but when I answered any questions that my classmates had in class, I never referred to AI to make sure I was correct. I’m okay with being honest when I don’t know the answer to a question, and why would I refer to AI for something that’s already in my brain? Relying on AI to answer questions sounds pretty dystopian to me. 

### Asking/answering a smart question

Again, why would I need to use AI to create or answer a question? It’s already in my head. 

### Generating coding examples

I don’t remember generating examples of code using AI this semester. I don’t think that I used AI to generate code examples because the documentation provided good examples of code already.

### Explaining code

I did use AI to help explain code, especially when I got a bug. Whenever I didn’t understand a bug I got, I would paste the error code into Copilot chat, and then it would break down what caused the error and steps I could take to resolve it. I like using AI in this way because it helps me be more proactive about resolving bugs, instead of just staring at my computer screen for hours and having no idea what to do. 

### Writing code

I used GitHub Copilot to generate some code for my final project. It was more solid than having an LLM in the browser generate the code because it’s easier to give Copilot context from your code base. For example, I prompted Copilot, “Based on this component’s code structure, generate a RIOCard component that takes in name, type, purpose_statement, main_contact, email. <component code here>.” If it has a blueprint to go off of, AI gives you more desirable responses. 

### Documenting code

I used GitHub Copilot autocomplete to generate documentation comments for one of the WODs. It was pretty useful because it generated close to what I was going to type, so I got it done faster. It was helpful because I was in a time crunch, and I was NOT going to type all that documentation out in such a short amount of time.

### Quality assurance

For some WODs, I prompted Claude with: “Given my code, could you list any problems with it, including syntax and edge cases? <code here>.” It was useful in pointing out syntax errors and offered alternative methods to type the code too. 

## Impact on learning and understanding

Incorporating AI has definitely affected my learning experience, both positively and negatively. Using AI in learning has affected me positively by helping me apply concepts faster, especially in code. AI has helped me create things I never thought I would’ve created at this point in my software development career. On the other hand, AI doesn’t really help me foster a depth in software engineering knowledge in the same way as reading documentation and watching tutorials does. There have also been times where I didn’t know the responses that AI was giving me were wrong, so I kept prompting it again and again until it arrived at the right answer. Using AI like this in learning is not helpful to actually learn anything. 

## Practical applications

Outside of ICS314, AI can be used in software development to somewhat automate the parts of the job that are monotonous, so more of a focus can be on coding and solving problems. For example, AI can be used to help generate documentation for a code base. In actual development, AI could be used to help resolve bugs that developers will inevitably run into when coding. It can help developers reach solutions to those bugs, so they can spend less time struggling on problems. 

## Challenges and opportunities

One challenge I ran into with AI use this semester was deciding when to use it. I struggled with this because sometimes I feel like I’ll be too quick to default to it. I feel like my line between actual coding knowledge and knowledge I fostered with AI is blurring a little bit. While I think the integration of AI in software engineering education is beneficial in some aspects, we should acknowledge the limitations of AI (hallucinations, cost to use it) and make sure that we’re still prioritizing using our own skills to create, instead of relying on AI to create everything. If we are to further integrate it into education, we need to teach everyone how to use it responsibly. For example, everyone should know basic prompt engineering so that they can get the best possible outputs from generative AI. It’s also important to teach people not to overrely on it, and when it isn’t giving them the best answer, it’s okay to stop using it. 

## Comparative analysis

Compared to traditional teaching methods, I think that AI-enhanced learning provides a couple of benefits. One benefit of employing AI-enhanced learning is that students can spend less time listening to boring lectures, and more time actually building and applying concepts taught in the course. With AI, it’s easier for students to quickly learn more about topics (especially with AI-enhanced web search), so teachers could potentially spend less time lecturing students and more time teaching them how to apply that knowledge. This would help students stay engaged during class. Another benefit would be that AI can help students create products faster than they could before. My main drawback is the knowledge retention, as it’s so easy to default to copying and pasting code that AI generates, and little to no learning is done through that. AI can also use coding concepts that beginner developers are unfamiliar with, and I think that also impedes real learning. That’s why I think it’s important to know that AI can’t completely replace traditional learning, but it can aid that learning. 

## Future considerations

Given the rapid rise of agentic AI development and tech giants like Microsoft investing so heavily into AI development, I think that it’ll be important for at least AI basics to be incorporated into college computer science curricula. However, given that almost every compsci student will be using AI in some capacity, it’ll be a challenge to assess students’ actual knowledge on coding concepts. I’m not sure how else to combat this other than teachers giving more tests on paper. 

## Conclusion

After this semester, I found out more about how to constructively use AI when developing software. AI is helpful when it comes to debugging and resolving issues in code, explaining snippets of code, and breaking down tasks into more manageable steps. AI is not so helpful when it comes to consistently generating accurate and desirable answers, so I always must take each response with a grain of salt. In order to improve ICS314 with further integration of AI, I think that there should be a module that teaches students about responsible and ethical AI use, so that they can know how to use it in order to benefit their learning instead of hinder it (it’s really easy to hinder learning with AI). This module should probably consist of a prompt engineering tutorial, an article on the pitfalls of generative AI, and a video lecture on how to use AI responsibly in software development. 
