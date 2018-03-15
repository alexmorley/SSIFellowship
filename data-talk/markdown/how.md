## 5 Golden Rules of Data Management


- Raw Data must never be touched.
<canvas id="matrix" style="height: 50%; width:100%;"></canvas>
<!-- raw data, i.e. what comes from your rig, notes you've taken on the day, images of sections etc. must all be a) backed-up and b) must be left raw. Don't cook sashimi. Setting to read-only.-->


- Have a plan.
<img src="img/plan.jpg" class="plain">
<!-- you have to have a plan that details exactly what you will do with every bit of data you collect that needs to include - *What data* is going to be collected during the experiment? - Where is it going to be stored initially? - Where is it going to be backed-up. - When/How will it be curated so that you/others can use it for analysis.-->


- Document *everything*.
<!-- At some point, someone is going to want to use either your data or your analysis scripts. And, (it's sad I know) at some point you're not going to still be working at the unit. Data or code without any comments or documentation is almost always pretty useless. If you want anything to have any chance of being re-used again (data or code) you have to include as much documentation as possible with it. -->
<!-- If you're as selfish as I am, I'll let you into a little secret, 95% of the time the person that's going to be using that documentation is you. -->


- Create the data you want to see in the world.
<!-- If you were to be handed a dataset and told to check it, understand or otherwise analyse it, how would that look. Try to make your own data as close to that as possible. File formats, variable names, file-names -->


- Try not to re-invent the wheel.
<!-- you may be doing some incredibly original research but the likelyhood it someone else in the lab, or elsewhere, has already done something similar. Ask around *before* you start doing your experiments about how people stored there data, what format they kept their notes etc. If you can keep that standardised across the lab then even better. -->



### 3 Golden Rules of Writing Software/Code


### 3 Golden Rules of Writing Software/Code
Actually there's just one:


### Document *everything*.
<!-- Comments at the start of every script and function, a list of all the requirements to run a particular program, the version of the software you are using, a url to that comment on stack overflow where you found a solution. Insert a screenshot of a program from e.g. Microsoft's code base -->


### Document everything
- Comments (aim for 50% comments!)
- README/How-To for every script/collection of scripts
- Requirements (list of all software + versions needed)


Tip: try out a document / Notebook Interface
- Live Script (Matlab)
- Jupyter (Python, R)
- R Markdown (R)


<img src="img/matlab_livescript.png" class="plain">


Tip:
Use some form of Version Control.
<!-- Version control means that every time you whenever you make a change to a program you aren't throwing away old versions. You could just add the date to every program and create a folder with old versions. But you might find life easier if you decide to use a dedicated system for doing. Git is the most widely used tool for doing this. It takes a few hours to learn what you need for it to be useful (a few lifetimes to know everything there is to know...) and its a pretty good skill to have on your CV. -->
