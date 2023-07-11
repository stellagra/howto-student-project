
- [Intention](#intention)
- [My Expectations and Philosophy as your supervisor](#my-expectations-and-philosophy-as-your-supervisor)
- [What is the goal of your project?](#what-is-the-goal-of-your-project)
  - [Examples](#examples)
- [Related Work](#related-work)
  - [Literature Review](#literature-review)
    - [ATTENTION - credible and accessible?](#attention---credible-and-accessible)
  - [Data and Code](#data-and-code)
- [Recommendations](#recommendations)
  - [Tools](#tools)
  - [Time and Project management hints](#time-and-project-management-hints)
- [How to report](#how-to-report)
  - [The general structure](#the-general-structure)
  - [What to report?](#what-to-report)
  - [Hints](#hints)
  - [DO NOT PLAGIARISE aka credit where credit is due](#do-not-plagiarise-aka-credit-where-credit-is-due)
- [Exam and Presentation](#exam-and-presentation)
  - [Hints on how to present](#hints-on-how-to-present)
  - [What to Expect](#what-to-expect)


# Intention
Consider this a buffet: Take what you like, combine according to your own needs, and leave the rest behind. 
I am not responsible for the consequences arising from your use of this content. 
This repo has been created with the best intentions to provide:
- Hints on how to perform and report a scientific project, e.g. thesis project 
- LaTeX template
- list of helpful tools and techniques

This repo does NOT claim:
- to provide complete information
- to be suitable for all fields
- to be suitable for everyone
- to replace your scientific supervisor, the contact to them or their advise
 
# My Expectations and Philosophy as your supervisor
You may find this document helpful, independent of if I am your supervisor or not. In case I am, or you are considering it, I want to share some expectations and philosophies before the start. 
* I am your coach and scientific supervisor, i.e. I will guide you and provide advice, but I will not do the work for you. Your project is your responsibility. 
* I am your customer. At the beginning we will carefully define a project description together. My main concern is that it is achievable, hence consider this a clearly defined lower bound which we agree upon. 
* We will decide together if you want to have recurring regular meetings, or if you prefer to call for a meeting when needed. Either way, I expect it common curtesy to inform the other party of a meeting if they cannot make it. 
* Don't worry about "failing". Expect that things do not work out as expected. Those are actually the interesting findings and the things you should investigate, analyse and report. In terms of setting things up and getting things to work: reach out. But also consider that some things, e.g. old codebase, might not work out for you. In this case: adapt, overcome.


# What is the goal of your project?
What is the goal of your thesis? Perform and report a scientifically solid work in a structured manner, such that other fellow researchers can understand, and reproduce your findings. 
## Examples
You project may include one or several of the following:
- Compare several tools on the same task and compare their performance
- Create a new method to solve a known problem
- Adapt and implement one or several method(s) such that it is tailored to the task at hand
- ...

# Related Work
You will find scientific papers, databases, and interesting tools/methods which you want to use. 
First you need to search what others have done:
- How did they solve/approach your research problem?
- How and with which intent was your considered method/tool used?
- How and with which intent was your considered data used?
It is good practice to use a tool to collect and organize your references, e.g. https://www.zotero.org/

## Literature Review
You must cite the work which you used, and which inspired you. For basic and commonly known methods a book references is fine. 
Credible Sources:
- https://scholar.google.com/
- https://ieeexplore.ieee.org/
- https://dl.acm.org/
- ...

### ATTENTION - credible and accessible?
Please consider the following when looking for related work and any kind of literature:
- Credibility: There are predatory conferences and journals, which claim to be credible, but aren't! Don't use those. 
- Accessibility: On some websites you will not have access to the full papers. However, you might find some publications on the free webpage arxiv.org, or you might have full access through the IT university. In the latter case please check the following link with descriptions for ITU students: https://kub.kb.dk/c.php?g=91657&p=591599
- How to cite: If a publication is available on arxiv.org, and has been published at a conference or journal, use the reference to the conference/journal instead of the arxiv one.

## Data and Code
Keep in mind: You must cite the data and code which you used. In case you refer to a website, include the date when you accessed it, because websites are due to change. If you use code from a github repository you often find a reference and instructions how to cite the work at the bottom of the page, in a readme file or in a license file. I highly encourage you to look for it. 
In general to search for available data and code, I recommend the following sources as starting points
- github.com
- https://datasetsearch.research.google.com/
- https://www.kaggle.com/
- https://paperswithcode.com/
- ...

# Recommendations
General recommendations for the process. 
## Tools
- try google colab for computations (good if your hardware is very limited)
- use overleaf for Latex (Pro: you do not need to set anything up on your own machine, and can write "anywhere". Contra: You need internet.)
- forgot the LaTeX symbol? no problem: https://detexify.kirelabs.org/classify.html
- need some math help? https://www.wolframalpha.com/

## Time and Project management hints
- use pomodoro technique: https://www.marinaratimer.com/
- define your goals 'SMART': Specific Measurable Achievable Reasonable Time-Bound
- explore other methods here: https://en.wikipedia.org/wiki/Time_management


# How to report
In general your report should be self-contained, i.e. not depend on a link to a github repo to be understood. My general advice is try to write the report which you would like to read. 
But how shall you report your findings? A scientific report conforms to a common structure, which may vary depending on your task and focus. 


## The general structure
Your report should be structured similarly as the following:
<ol>
<li> Introduction: intention, i.e. context and related work referring to state of the art (the latter can also be separate).</li>
<li> Methods: Which tools did you use? detailed description of existing methods and your new one (if applicable).</li> 
<li> Experiments: What did you do? </li> 
<ul>
<li> Data: Which data did you use? How did you collect it? (Might be a separate chapter.)</li> 
<li> Results/Evaluation: How did it turn out?</li> 
</ul>
<li> Discussion: Did the experiments work our as intended? What did you find? </li> 
<li> Conclusion: Summarize your findings.</li> 
<ul>
<li> Future Work: In case you have further ideas for future works, and how to address shortcomings you found, here is the right place to put them.</li> 
</ul>
<li> References: list of references which you used.</li> 
<li> Appendix: not always needed, but might be useful for large tables etc. </li> 
</ol>
Note: There are variations, e.g. often there are no separate sections for experiments and results. 


## What to report? 
Which questions must be answered?
- Report what you did and why, also and especially if the outcome is not positive. 
- How did your method perform compare to others? 
- Reflect on what went wrong and can be improved. Research includes failures.
- If you collected new data: describe how you did it with which intentions. 
- Did you unveil limitations of your data of choice?
- ...

## Hints
- All Figures and Tables must be referenced in the text. 
- If you use LaTeX, use the environments "figure" and "table" with caption and label. Remember that the name of the label must be unique. 
- Caption of figures at the bottom
- Caption of tables at the top
- Don't know how to say it? Check this out: https://www.phrasebank.manchester.ac.uk/
- Stuck in how to put your thoughts into text? Talk it out! Explain it to peers, friends, family, or use a voice to text service. Google docs in Chrome offers this feature. 

## DO NOT PLAGIARISE aka credit where credit is due
You may use data, code, images, and even text from others IF and only IF:
- you refer to it properly! (e.g. on github there is often a license agreement and required citations)
- Do not display, distribute, copy data from others without their consent! (GDPR)


# Exam and Presentation 
Your written project submission will traditionally be followed by an oral exam, where your supervisor(s) and another examiner will be present. This oral exam includes a presentation, followed by a question round. The guidelines at ITU allocate 40 minutes per student. A common timeline for such an oral exam can hence look as follows:
- 10-15 minutes presentation
- 15-20 minutes exam
- 5 minutes grading (you will have to leave the room for this)
- 5 minutes buffer+sharing the grade

## Hints on how to present
You can assume that the supervisor(s) and examiner have read your written work. During your presentation your task is to summarize the important points of your project. It also gives you the opportunity to clarify things, and incorporate videos. 
It is recommended that you talk your presentation through as a practice, and add slide numbers such that the examiners can refer to slides for questions. 

## What to Expect
It is possible that you will receive questions which you cannot answer. My best advise here is: expect this, and don't panic. Just say what you know. You did your project, hence you are the expert in what you did. 

