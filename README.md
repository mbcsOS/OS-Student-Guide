## Welcome to the OS x MBCS Student Guide!

Here we will direct you through the steps of your Research Project and give you advice and resources to implement Open Science practices into your own research!

### 1. Finding an Internship


**Choosing an internship** is a crucial decision during our Master. Much of your training will come from your supervisor and lab! This is an opportunity to learn not only methods and topics that interest you, but good research practices and how to be an engaged member of the scientific community.

When looking for a lab, consider investigating some questions related to open science practices. Look these up when searching for the lab, but also, don’t be afraid to directly ask when being interviewed! This will allow you to gauge if the lab is open to such ideas: 

**Science communication:** Does the lab have a Twitter? A YouTube channel? A blog? Are they making an effort to share their research with the wider community?

**Transparency:** Does the lab have repositories on OSF? Do they have open data and open code (preferably in open source languages/programs)? Do they publish preprints and open access papers? 

**Diversity:** This is a key component of science as it promotes diverse perspectives and increased creativity. To make sure you have a positive experience, make sure that the lab is a place where you yourself would feel included and comfortable.

### 2. Research Proposal

In the **research proposal** required by MBCS, you outline prior research, your hypotheses, experimental design and potential results. This is a great opportunity to flex some open science muscles and **preregister** your experiment(s)!

**Preregistration** goes beyond our required research proposal:
- In preregistration, you also outline your methods, stopping rules, and your analysis plan (What tests will you use? What counts as significant?)
- Preregistrations are time stamped and uploaded to an public online repository (though you can keep it private as long as you want)
- Preregistrations are submitted before data is collected (or in some cases, before data is analysed).

Preregistration separates **confirmatory** and **exploratory** research. Different data must be used to generate and to test hypotheses. Despite our best efforts and intentions, confusing these types of analyses can happen in research if your plans are not explicitly laid out. 

```markdown
What if I need to change something? You don’t need to feel shackled to your preregistration; if you want to make a change, make it. Preregistration forces you to simply be transparent in your final report about the changes you made and why.
```

Most of the work done for our mandatory research proposals can feed right into a preregistration. It’s a small extra step to take for increased transparency and accountability to yourself and the scientific community.

The two largest repositories for preregistration are:
- AsPredicted: One simple template of 9 questions. 
- OSF: A more flexible platform with many templates available, such as EEG and fMRI. Templates are very helpful to start, but note that you can always tailor a preregistration to what you believe is important.

**Talk to your supervisor about which repository and template are right for your project.** For one take on the pros and cons, check out this blog post.


### 3. Collecting Data (or using existing one)

Data collection and dissemination are integral to ensure good research practices in research projects. Sharing data refers to making a dataset used for a particular project openly available to other researchers. This includes posting the data on the Open Science Framework (OSF), part of the Centre for Open Science, or another data repository from which researchers can download and use data. A part of data sharing is sharing analysis scripts, especially those related to data cleaning and labelling. 

When considering data collection and dissemination, especially within psychology and neuroscience, one has to consider how the majority of data is collected from a “WEIRD” population (Henrich et al., 2010). The acronym “WEIRD''refers to a western, educated, industrialized, rich and democratic population. This population makes up 96% of the data in psychology experiments, while it is not remotely representative of the diversity of the world’s general population. Sharing more data openly, and reusing shared data, would help increase the inclusivity of populations in data, so that it is more generalizable, and consequently also more beneficial to individuals outside the WEIRD population (Henrich et al., 2010).

Another prominent reason to share data regards the infamous replication crisis in psychology. Sharing data would increase commitment to transparency, allowing for more ethical data processing and statistical analysis (Banks et al., 2019). Moreover, sharing data allows for the opportunity for others to check for quality and accuracy, as well as to potentially debunk some findings. 

Data sharing can be done through multiple repositories online, including (osf project page: https://osf.io/w5mbp/) and Depositing Data in the AEA Data and Code Repository (https://www.openicpsr.org/openicpsr/aea). 


### 4. Data Analysis

The data analysis part of your project allows you to show off your good research practices and open science mindset. Not only do you make important decisions on how to properly and sincerely handle your data, you also set the groundwork for how your results are interpreted and presented in the end. Data analysis Also, this part is an important step integral for towards a transparent research project. Consider the following points to achieve these goals: 

**Appropriate statistics:**
Check your assumptions and consider the statistical methods that you are using in your project. This is a very broad topic and it is best practice to check in with your supervisors or even consult experts of the field or trained statisticians. 
Common pitfalls which you can keep in mind yourself:

- Violation of assumptions:, Ccertain statistical tests have assumptions about i.e., the distribution of your data. These assumptions vary by test, but it is important to check beforehand whether you can use a certain method on your data.
- False positives due to multiple comparisons (see this fishy example): If you do a lot of statistical tests in your analysis, which is often the case when analysing neuroimaging data, you run the risk of finding significant results just by chance (i.e. false positives) and thus interpreting findings that are not actually there! This multiple comparison problem can be remedied by applying one of many corrections to your p-values.
- Interpretation of p-values:. Although you probably know what a p-value is...do you really? The interpretation of p-values is not always straightforward and relying on significant results for publication is often questionable. Here is a paper and a handy video explaining p-values and their interpretation and alternatives.
- Outlier exclusion:n - Often, refers to the exclusion of data points or entire participants are excluded from analyses if the data is unusual or faulty. However, deciding whatdecidingthe decision of what is an outlier and what is variation and meaningful information is tricky. See this blogpost for an overview of the problem.
- Interpretation of multivariate statistics:. Many of us as students will work with multivariate models, especially in neuroimaging. However, the interpretation of these results can be misleading, as we often do not know for sure what is driving the classification results. See this paper for a discussion on the topic.

A good overview of “good research practices” as these aspects are referred to is the book “Seven Deadly Sins”.

```markdown
Whichever statistical tests you carry out, it is beneficial for you and the reader of your report to write down decisions for every step of your analysis. 

```

Furthermore, to carry out your research project you will likely need programming or statistical software. Points to consider here are:
- Software:The use of software, pPopular software such as MATLAB or SPSS are not open source, which means that you haveneed  to pay to use them and people who do not possess licences cannot easily reproduce your analysis. R, Python or JASP are widely-available greatvery good open-source alternatives.
- Clean code: Writing “clean” code means that your code is readable to others (and your future self!). From variable names to comments and documentation, there is a lot to consider to make your code as transparent as possible. Good places to start are style guides for programming languages (R, Python).
- Data and code sharing: . Sharing experimental data is likely not in your power as an intern, so , you should always ask for the data management protocols in your lab and never share data without asking! However, you can think about publishing your own analysis code so that others can re-use it (and cite you) or to reproduce your analysis. Github is a popular platform to upload and share code. Repositories can be private as well, which is an excellent way for version control and sharing code with your supervisors. If you are not comfortable sharing your code or your lab does not agree to share analysis code, a private repository is an option. Since Git is not the most intuitive, here is a nice tutorial and a guide on how to get started.


### 5. Writing the Final Report

Tying up your research project with your report is an important step to reflect on your findings, think critically about future scientific endeavours and to show other researchers what you can do! It is with this piece of writing that you convince others that what you did is relevant, scientifically valid and brings about new directions and ideas. The report also helps you reflect on and summarise what you did in the past couple of months. It is important that you draft your ideas in a transparent and clear way to get your message across. 

Writing a transparent report has several benefits. For one, keeping track of analysis steps and using citation managers will help you when writing your final product. It is easy to forget certain steps in your analysis or decisions that you made in the beginning. Writing these steps down in a transparent fashion will prevent this. Furthermore, when it comes to the actual writing process, you might wonder how much detail in each section. Following specific writing guidelines, such as the APA standards, will help you structure and write your report. If you are unsure about the level of detail to include, here is a handy guide explaining all the relevant sections.
A transparent and readable report contributes to a reproducible research project. It is easier to correct, gives a good impression and makes the review process shorter and easier!

If you need additional help, the UvA writing center may be worth checking out.

### 6. (Bonus) Publication


