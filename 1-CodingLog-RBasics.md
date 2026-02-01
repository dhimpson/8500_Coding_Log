# Week [1] Learning Log

**Student Name:** [Dori Impson]  
**Week of:** [01/26/2026 - 02/02/2026]  
**Topic(s):** [e.g., "Basics of R"]

---

## What I Worked On This Week

**Assignment(s):**
- [x] Worksheet [1]
- [x ] Other: [describe]I also worked on the r tutorial on codecademy before class.

---

## Challenges & Problem-Solving

### Challenge 1: [Issues with Github connecting to VS Code]

**What I was trying to do:**
I was attempting to make my first commits to github from VS Code when I encountered failure messages.

**What went wrong:**
I ran into an issue with my first attempt to commit. VS Code could not identify my github account. After trouble-shooting and googling the issue, I had to reintroduce my github account to VS code by identifying my user name and email.  After doing this, I was able to push commits with no problem. After rectifying the user/id issue, I also had a issue with merging my work inorder to commit. This was easier to fix. I am not sure why the user/id issue happended in the first place.

**My problem-solving process:**
1. First attempt - I attempted to commit multiple times in VS Code, thinking that somehow my unfamiliarity with the interface was the issue.
2. Second attempt - I googled the error message to try to understand what I could do to reconnect my github account to the VS Code App
3. [Additional attempts- what helped most was scrolling through the git code in the VS Code terminal and following the prompts there. This actually helped the most.

**Resources I consulted:**
- [x ] Documentation for [package/function]
- [ ] Stack Overflow: [describe what you searched for]
- [ ] Course materials: [which ones]
- [ ] Slack discussion
- [ ] Office hours
- [x] Other: [describe] Just precisely worded google searches to try to identify the problem and how to fix it.

**Resolution:**
Ultimately, reading back through the git failure data in my terminal helped the most. It told me how to reconnect my github account to the VS Code interface.

**What I learned:**
I learned to not be afraid to look back through the terminal for specific errors and advice. This may sound silly, but the terminial is rather intimidating at first glance. I also have a hard time visually disciphering information within it. I have a photographic memory and the appearance of code in the terminal seems to overload my ability to process. I am hoping that with time,as I learn more about coding, this information with in the terminial will become more meaningful and I will be better at visually identifying what I see. For me to be able to go into the terminal and find what I needed to fix my github issue was a major win.

---

### Challenge 2: [Not being able to open a dataset from the DigitalMethodsData]

**What I was trying to do:**
I attempted to load the undergroundRR dataset from the DigitalMethodsData library to complete my worksheet.   

**What went wrong:**
Because I had exited and re-entered VS Code, I needed to reload the DigitalMethodsData library package to then load the dataset that I wanted. After I got into the dataset, I still had a few issues accessing the data. Here is what my code looked like: 
> library(DigitalMethodsData)
> help(package="DigitalMethodsData")
Browsing http://127.0.0.1:14016/library/DigitalMethodsData/html/00Index.html
> data(undergroundRR)
Warning message:
In data(undergroundRR) : data set ‘undergroundRR’ not found
> data("undergroundRR")
Warning message:
In data("undergroundRR") : data set ‘undergroundRR’ not found
> data("undergroundRR")
Warning message:
In data("undergroundRR") : data set ‘undergroundRR’ not found
> data("UndergroundRR")
> head(UndergroundRR)
Error: object 'UndergroundRR' not found
> head(undergroundRR)
**My problem-solving process:**
1. [First attempt] I attempted to load the data using the information from the dataset library for undergroundRR. This did not work and I got an error. 
2. [Second attempt] I tried again and added "" around the undergroundRR. It also did not work.
3. [Third attempt) I experimented with capitalization which gave me the same error. I think tried the head command which seemed to have worked. I am still not quite sure what exactly I did wrong, but I was able to access data and work within the dataframe.

**Resources I consulted:**
- [ x] Documentation for [package/function]
- [ ] Stack Overflow: [describe what you searched for]
- [x ] Course materials: [which ones] R for Data Science (looked up opening packages and dataframes
- [ x] Slack discussion
- [ ] Office hours
- [ x] Other: [describe] I googled how to open dataset in r in VS Code, however, I could not successfully figure out what to do from the results. I also had a family member (Computer engineering student) take a peak and see if they could help, but they were equally stuck. After trying everything that I could think of, I reached out to Dr. R via Slack.

**Resolution:**
The nudge from Dr. R via slack discussion helped me to recall that I needed to reload my library. I think this was mentioned in class and I had forgotten it. 

**What I learned:**
I learned that while trying to fix something on my own is a good thing to do, sometimes I really do just need to ask for help. I spent 2 to 3 hours attempting to fix this. I most likely should have reached out sooner, but I was just being rather stubborn.

---

### Challenge 3 (Optional): [Brief descriptive title]

**What I was trying to do:**
[Describe the task or problem]

**What went wrong:**
[Describe the error, confusion, or roadblock]

**My problem-solving process:**
1. [First attempt - what you did and what happened]
2. [Second attempt - what you did and what happened]
3. [Additional attempts if relevant]

**Resources I consulted:**
- [ ] Documentation for [package/function]
- [ ] Stack Overflow: [describe what you searched for]
- [ ] Course materials: [which ones]
- [ ] Slack discussion
- [ ] Office hours
- [ ] Other: [describe]

**Resolution:**
[What ultimately worked or where you're still stuck]

**What I learned:**
[What did this teach you about the concept, the tool, or problem-solving?]

---

## Reflection

**What I understand well now:**
I am much better at commiting my changes to github. I have learned a lot of the terminology for the VS Code interface. I understand how to run r code. I have learned many basic functions for r and how to use some operators. I also have learned the value of a well-executed google search. 

**What I'm still confused about:**
[What remains unclear? What questions do you have?] I am still a little confused about the issues that I had with the undergroundRR dataset. 

**Connection to historical research:**
Our readings from this week and the worksheet have me thinking through how to use r with my airtable databases for my data on Little Texas. I am really excited about the possibilities of taking my data and creating a dataframe where I can queary and compare information. I am already thinking through what kind of arguments I might be able to make using the data that I have and how that data might need to be expanded in order to grow my research. The idea of eventually using my own data, to bring my reasearch to life in ways that I could not do otherwise is very exciting to me. 

