---
theme: slidev-theme-dataroots
layout: intro
lineNumbers: false
themeConfig:
  title: MLOps - Bringing ideas to production 🚀
  github: murilo-cunha
  twitter: _murilocunha
  linkedin: in/murilo-cunha
title: MLOps
info: |
  ## MLOps
class: text-center
highlighter: shiki
drawings:
  persist: false
mdc: true
hideInToc: true
favicon: 'https://raw.githubusercontent.com/datarootsio/slidev-theme-dataroots/main/components/assets/symbol-rainbow.png'
titleTemplate: '%s'
---

# [MLOops]{v-mark.crossed-off=1} to MLOps

<br/>
<br/>

<v-click v-motion-pop-visible at=2>
<carbon-arrow-right/> Bringing ideas to production 🚀

March 15th, 2024
</v-click>

---
hideInToc: true
---

# Agenda

<br/>

::left::

<Toc />

::right::

<img src="https://media.giphy.com/media/NytMLKyiaIh6VH9SPm/giphy.gif?cid=790b7611306dhsfqkf6esokoqs15cp6n2qs33oueers2dnr3&ep=v1_gifs_search&rid=giphy.gif" rounded-lg shadow h-70/>

<style>
li:not(li:first-child) {
  margin-top: 0;
}
</style>

---
layout: presenter
photo: https://charlas.2023.es.pycon.org/media/avatars/blob_p6VtbO9.jpg
---

# About me

- 🇧🇷 → 🇧🇪: Brazilian @ Belgium
- 🤓 B.Sc. in Mechanical Engineering @PNW
- 👨‍🎓 M.Sc. in Artificial Intelligence @KUL
- <img src="https://www.gend.co/hs-fs/hubfs/gcp-logo-cloud.png?width=730&name=gcp-logo-cloud.png" inline-block h-4/> Professional Data & ML Engineer
- <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/93/Amazon_Web_Services_Logo.svg/1024px-Amazon_Web_Services_Logo.svg.png" inline-block h-3 /> Machine Learning Specialty
- <img src="https://upload.wikimedia.org/wikipedia/commons/8/80/HashiCorp_Logo_no_text.png" inline-block h-5/> Terraform Associate
- <img src="https://www.astronomer.io/monogram/astronomer-monogram-RGB-600px.png" inline-block h-5/> DAG Authoring & Airflow
- <img src="https://appsembler.com/wp-content/uploads/2022/02/bug-sno-blue.png" inline-block h-5/> SnowPro Core
- <img src="https://cdn.worldvectorlogo.com/logos/prefect-1.svg" inline-block m-1 h-5/> Prefect Associate
- 🤪 Fun facts: 🐍, 🦀, 🐓
- 🫂 Python User Group Belgium <img src="https://dataroots.io/branding/pyug-logo/python-ugb-logo.png" inline-block h-5 animate-spin/>
- 📣 Confs: 🇯🇵, 🇵🇱, 🇮🇪, 🇵🇹, 🇪🇸, 🇸🇪
- 🎙️ Datatopics Unplugged Podcast <img src="https://storage.buzzsprout.com/variants/eqfwl9pk54qv75liqcsfiw7uqofc/b49cbe86cb411762753e730c58953bb88ad958a9d657212c074729b6f04e5463.jpg" h-6 rounded inline animate-bounce>
- 🤖 Tech lead AI @ <img src="https://dataroots.io/branding/logo/logo-green.png" inline-block h-5/>

<style>
li {
  margin-top: 0 !important;
}
</style>

---
hideInToc: true
layout: default
---

# I have worked on different [Data/AI projects]{.gradient-text}

<br/>

::left::

<br/>
<br/>

<v-clicks >

- Events company 📣
- No show prediction 🫥
- Record deduplication 👯‍♀️
- Recommend visitors and exhibitors 🤝
- PoC <carbon-arrow-right/> MVP <carbon-arrow-right/> Production 🚀

</v-clicks>


::right::

<br/>
<br/>
<br/>


<v-click>
  
<Youtube id="SD3irxdKfxk" rounded-lg scale-130 shadow />
  
</v-click>

---
hideInToc: true
layout: twocols
---

# From the [prototyping]{.gradient-text} side...
<br/>

::left::

<v-click>
  
<div flex items-center justify-center h-full class="-mt-10">
<img src="https://media.giphy.com/media/1BfhAhC5Vvd12EUaFq/giphy.gif?cid=790b7611h13pesldm28uqz6naaeuys4mag61pe7jl99znt7b&ep=v1_gifs_search&rid=giphy.gif" rounded-lg scale-70 shadow-lg />
</div>
  
</v-click>

::right::


<br/>
<br/>


<div class="-ml-10">
<v-clicks >

- Content moderation @ social media company 🤬
- NER @ clinical studies 🔎
- Q&A chatbots @ automotive industry 🏎️
- Energy consumption forecasting @ public sector 📈
- Network analysis @ accounting company 🕸️

</v-clicks>
</div>

---
hideInToc: true
---

# ...to <p inline bg-gradient-to-r from-rose to-indigo bg-clip-text text-transparent> production </p> applications

<br/>

::left::

<br/>
<br/>
<br/>

<v-clicks>

- Finacial sector 💰
- Early customer lifetime value 🤑
- Pipeline migrations 🧑‍🔧
- **Churn prediction 🫠**

</v-clicks>

::right::

<img src="https://media.giphy.com/media/ND6xkVPaj8tHO/giphy.gif?cid=ecf05e47k50mo4pn7fgs4f1c6uaqa19dxwfhdux3qfihg0ez&ep=v1_gifs_search&rid=giphy.gif&ct=g" rounded-lg scale-80 shadow-md />


---
hideInToc: true
---

# Why am I [here]{.gradient-text}?


<br/>

<div flex items-center justify-center h-full m-5>
  
## " To help us understand what it takes for a machine learning project takes to go from [idea to production]{v-mark.box.yellow=3}, looking closely at the differences between [machine learning]{.gradient-text} and [operations]{.gradient-text} "
  
</div>

---
layout: cover
title: What is  MLOps?
---

# Why MLOps?

---

# Use case: [content moderation]{.gradient-text}


<div flex flex-col items-center justify-center h-full>

<div shadow-lg rounded-lg >  
<img src="https://openai-labs-public-images-prod.azureedge.net/user-FpwegUavI965wXO1WB5HjsxZ/generations/generation-8Aew75oFXWIuddrQkA3j5b1U/image.webp" h-80 />
  
</div>

`“pixel art angry face with symbols on mouth censoring profanity”` - <img src="https://static-00.iconduck.com/assets.00/openai-icon-2021x2048-4rpe5x7n.png" h-6 inline> DALL·E 2

</div>

---
hideInToc: true
---

# What is [content moderation]{.gradient-text}?

::left::

<br/>

<v-clicks depth=3>

- You're the CEO of 10gag ( congrats! <span inline-block animate-ping>🎉</span> )
	- (Like 9gag, but better) <img src="https://upload.wikimedia.org/wikipedia/fr/2/28/9gag_new_logo.png" rounded-full animate-spin inline h-4/>
- Things haven't been so good lately 🫣
- Some people are leaving nasty comments 🤬
- You have an idea! 💡
	- You can probably detect these comments, and remove them from the platform
    - <p inline bg-gradient-to-r from-rose to-indigo bg-clip-text text-transparent font-extrabold>How well can we identify these comments using machine learning?</p>
 
</v-clicks>

::right::

![](https://media.giphy.com/media/3Fkw8DCq4eUxp31E4n/giphy.gif){.rounded-lg .shadow-lg .scale-80}

---

# So you build a [model]{.gradient-text}...

<br/>
<br/>

::right::

<br/>

![](http://jalammar.github.io/images/gpt3/10-gpt3-fine-tuning.gif){.rounded .shadow-xl .object-contain v-click=1}

::left::


<v-clicks at=2>

👨‍💼 "How long will it take to go though 100 posts? How can we make it faster?"

👷‍♀️ "How can we make sure the model scales?"

👷‍♂️ "What packages did you use?"

😡 "Why is it removing my posts?"

👩‍🔬 "What models did you already try?"

🕵️ "What data was used to train this model?"

</v-clicks>

::bottom::

<v-click at=8>
 
<carbon-arrow-right /> [MLOps decreases the burden of deploying ML systems by following best practices]{v-mark.highlight.yellow=8}

</v-click>

---

# Real life [testimonials]{.gradient-text}


# [TODO]{.bg-red .flex-center .h-100}

“At this point, everybody does what they like, there is little to no standardisation. Since there are little to no best practices, the current platform contains the largest common denominator of a lot of heterogeneous projects. This causes a lot of burden in maintaining these projects”

“For quite some time, the focus was on more traditional Business Intelligence and Data Engineering. More recently we have seen the focus shifted more towards Advanced Analytics in the form of some scattered initiatives and products, which in turn lead to little success on these.”

“While I love our Data Science team, the code they write is not at all up to standards in comparison to what we normally push into production. This puts a heavy burden on the Data Engineering team to rewrite and refactor this. At the same time the Data Science team is often unhappy, because this refactoring process tends to introduce mistakes or misunderstandings.”

---
layout: cover
title: What is  MLOps?
---

# What is [ML]{v-mark.red=1}[Ops]{v-mark.circle.yellow=2}?

---

# What's in the [name]{.gradient-text}?

<br/>

::left::

## Machine learning 🧠

<br/>

<v-clicks>

- Experimentation
- Data exploration
- Modelling
- Hyperparameter tuning
- Evaluation

</v-clicks>

::right::

## Operations ⚙️

<br/>

<v-clicks>

- Availability
- Scalability
- Reproducibility
- Monitoring/Alerting
- Automation

</v-clicks>

::bottom::

## [✨ MLOps ✨]{.flex .justify-center .'-mt-20' v-click}

---

# DevOps vs. [MLOps]{.gradient-text}

![](https://valohai.com/blog/difference-between-devops-and-mlops/mldevops.png){.rounded .shadow .bg-blue .scale-50 v-click .'-mt-20' .'-mb-25'}

## [MLOps principles](https://ml-ops.org/content/mlops-principles):

"[...] By codifying these practices, we hope to accelerate the adoption of ML/AI in software systems and fast delivery of intelligent software. In the following, we describe a set of important concepts in MLOps such as [Iterative-Incremental Development, Automation, Continuous Deployment, Versioning, Testing, Reproducibility, and Monitoring]{v-mark="{type:'highlight', color:'yellow', multiline:true}"}."

---

# DevOps vs. [MLOps]{.gradient-text} ?

<br/>

::left::

## MLOps
<br/>

- Iterative-Incremental Development
- [Automation]{v-mark.blue="'+1'"}
- [Continuous Deployment]{v-mark.blue="'+1'"}
- Versioning
- [Testing]{v-mark.blue="'+1'"}
- [Reproducibility]{v-mark.blue="'+1'" v-mark.box.red=6}
- Monitoring

::right::

<v-click at='+2'>

## vs. DevOps

<br/>

\+ Model

\+ Features

\+ Model

</v-click>

---

# So... what is it?

<br/>

<div flex flex-col items-center justify-center h-full mx-5>
  
## “The [level]{v-mark.circle.blue=1} of automation of these steps defines the maturity of the ML process, which [reflects the velocity of training new models given new data or training new models given new implementations]{v-mark="{type:'highlight', color:'yellow', multiline:true, at:2}"}. The following sections describe three levels of MLOps, starting from the most common level, which involves no automation, up to automating both ML and CI/CD pipelines.”

</div>

<div flex justify-end w-full class='-mx-10'>

## [- Google](https://cloud.google.com/architecture/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning)

</div>

---

# (MLOps in theory vs. [practice]{.gradient-text})

[> “In theory, theory and practice are the same. In practice, they are not.” - Einstein]{v-click}

<iframe src="https://arxiv.org/ftp/arxiv/papers/2205/2205.02302.pdf" w-full h-95 rounded shadow-lg v-click/>


---

# Pop Quiz 💥

## For each of these challenges, which ones are related to [ML]{v-mark.highlight.red} or [Ops]{v-mark.highlight.cyan} ?

<br/>

::left::

- [Locality of the data (distributional shift)]{v-mark.highlight.red=1}
- [Models and experiments are not properly tracked]{v-mark.highlight.cyan=2}
- [Model decay]{v-mark.highlight.red=3}
- [Changing business objectives]{v-mark.highlight.red=4}
- [Models monitoring and (re)trainining]{v-mark.highlight.cyan=5}
- [Retraining]{v-mark.highlight.red=6}
- [Data quality]{v-mark.highlight.red=7}




::right::

- [Consistent project structure]{v-mark.highlight.cyan=8}
- [Data availability]{v-mark.highlight.red=9}
- [Code and dependencies tracking]{v-mark.highlight.cyan=10}
- [Auditability and regulations - reproducibility and explainability]{v-mark.highlight.cyan=11}
- [Wrong initial assumptions (problem definition)]{v-mark.highlight.red=12}
- [Deploy model systems(not just one off solutions)]{v-mark.highlight.cyan=13}

---
layout: cover
---

# MLOps Illustrated
## ML Lifecyle Recap

---
hideInToc: true
---



---
hideInToc: true
---

# ML lifecycle & development (simplified)

<div h-full flex flex-col justify-center items-center scale-250 my-20 space-y-5>

<v-clicks>
```mermaid
%%{init: {"flowchart": {"htmlLabels": false}} }%%
flowchart LR
    idea["`💡
    Idea`"]
    poc["`Proof-of-Concept 🤖`"]
    mvp["`Minimal Viable Product 🦴`"]
    prod["`Iterate 🚀`"]
    
    idea --> poc --> mvp --> prod
```

```mermaid
%%{init: {"flowchart": {"htmlLabels": false}} }%%
flowchart LR
    eda["`Exploratory Data Analysis 🔎`"]
    model["`Modeling 📦`"]
    eval["`Evaluation ⚖️`"]
    deploy["`Deployment 🏗️`"]
    monitor["`Monitoring 👀`"]
    eval .-> model
    eval .-> eda    
    eda --> model --> eval --> deploy --> monitor
```

</v-clicks>
</div>

---

# Exploratory data analysis (EDA)


::left::

<div class="-mr-23">
<v-clicks>

- Check that the data is available
- Join data sources
- Look for outliers and validate data correctness
- Create new features
- Tooling:
  	- Python <carbon-logo-python/>
    - SQL <carbon-db2-Database/>
    - Jupyter notebooks <carbon-logo-jupyter/>
  	- BI tooling/dashboards <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c9/Power_bi_logo_black.svg/1024px-Power_bi_logo_black.svg.png" h-5 inline/>

</v-clicks>

<br/>
  
<v-clicks>
<div>
<carbon-arrow-right/> <p inline bg-gradient-to-r from-rose to-indigo bg-clip-text text-transparent font-extrabold> Share and validate findings with business stakeholders </p>
</div>

- "Users that don't log in are the ones that leave"
- "Some users leave the platform because they are 'addicted'"

</v-clicks>
</div>

::right::

<div flex flex-col items-center justify-center h-full class="-mt-4">

<v-click>
<img src="https://openai-labs-public-images-prod.azureedge.net/user-FpwegUavI965wXO1WB5HjsxZ/generations/generation-bhu1ElLCd0z6CGaQX59a7rqB/image.webp" h-40 shadow-lg  rounded/>

`“A data scientist at work as pixel art”`

</v-click>

<v-click>
<img src="https://openai-labs-public-images-prod.azureedge.net/user-FpwegUavI965wXO1WB5HjsxZ/generations/generation-QGmoinDojSrwN667OwVyRgtn/image.webp" h-40 shadow-lg rounded/>

`“A data analyst at work as pixel art”`
</v-click>
</div>

<style>
li:not(li:first-child) {
  margin-top: 0;
}
</style>


---

# Modeling

::left::

<br/>
<br/>

<div class="-mr-23">
<v-clicks>

- Define data for training and testing
- Deal with class imbalance
- Define cost function
- Try different models
- Tune hyper parameters
- Iterate on different architectures
- Tooling:
  	- Python <carbon-logo-python/>
    - Jupyter notebooks <carbon-logo-jupyter/>

</v-clicks>
</div>

::right::

<div flex flex-col items-center justify-center h-full class="-mt-4">

<v-click>
<img src="https://openai-labs-public-images-prod.azureedge.net/user-FpwegUavI965wXO1WB5HjsxZ/generations/generation-bhu1ElLCd0z6CGaQX59a7rqB/image.webp" h-40 shadow-lg  rounded/>

`“A data scientist at work as pixel art”`

</v-click>

<v-click>
<img src="https://openai-labs-public-images-prod.azureedge.net/user-FpwegUavI965wXO1WB5HjsxZ/generations/generation-KaWyGPwUtMelJEo6mAYrAbfH/image.webp" h-40 shadow-lg rounded/>

`“ml engineer pixel art”`
</v-click>
</div>

<style>
li:not(li:first-child) {
  margin-top: 0;
}
</style>


---

# Evaluation

::left::

<div class="-mr-12">
<v-clicks>

- **Define the appropriate metrics and plots**
- Compare model predictions with labeled data
- Compute metrics and build plots
- Assess feature imporance
- Check for anomalies (better performance in subgroups, etc.)
- Tooling:
  	- Python <carbon-logo-python/>
    - Jupyter notebooks <carbon-logo-jupyter/>

</v-clicks>
</div>

  
<v-clicks>
<div>
<carbon-arrow-right/> <p inline bg-gradient-to-r from-rose to-indigo bg-clip-text text-transparent font-extrabold> Assess with business whether model performance is acceptable </p>
</div>

- Should we try other models?
- Should we build new features?
- **How will these predictions be used?**


</v-clicks>


::right::

<div flex flex-col items-center justify-center h-full class="-mt-4">

<v-click>
<img src="https://openai-labs-public-images-prod.azureedge.net/user-FpwegUavI965wXO1WB5HjsxZ/generations/generation-bhu1ElLCd0z6CGaQX59a7rqB/image.webp" h-40 shadow-lg  rounded/>

`“A data scientist at work as pixel art”`
  

</v-click>

<v-click>
<img src="https://openai-labs-public-images-prod.azureedge.net/user-FpwegUavI965wXO1WB5HjsxZ/generations/generation-KaWyGPwUtMelJEo6mAYrAbfH/image.webp" h-40 shadow-lg rounded/>

`“ml engineer pixel art”`
</v-click>
</div>

<style>
li:not(li:first-child) {
  margin-top: 0;
}
</style>

---

# Deployment

::left::

> (Congrats! <span inline-block animate-ping>🎉</span> Many projects don't get this far)

<br/>

<div class="-mr-12">
<v-clicks>

- Event-driven or scheduled? (<carbon-arrow-right/> batch or real time?)
- How much data?
- Where should the predictions go?
- Who should have access to it?
- How can we just make predictions for the new data?
- Define (re?)deployment strategy
- Tooling:
  	- Python <carbon-logo-python/>
    - Cloud <carbon-IbmCloudHpc />
  	- Orchestrators <img src="https://icon.icepanel.io/Technology/svg/Apache-Airflow.svg" inline h-5 grayscale/>
  	- Web servers <img src="https://techcommunity.microsoft.com/t5/image/serverpage/image-id/420557i0319A4181851485A/image-size/original?v=v2&px=-1" inline h-5 grayscale/>
  

</v-clicks>
</div>

::right::

<div flex flex-col items-center justify-center h-full class="-mt-4">

<v-click>
<img src="https://openai-labs-public-images-prod.azureedge.net/user-FpwegUavI965wXO1WB5HjsxZ/generations/generation-KaWyGPwUtMelJEo6mAYrAbfH/image.webp" h-40 shadow-lg rounded/>

`“ml engineer pixel art”`
</v-click>

<v-click>
<img src="https://openai-labs-public-images-prod.azureedge.net/user-FpwegUavI965wXO1WB5HjsxZ/generations/generation-aHp55zVrme5SmXxdWkdgYhCK/image.webp" h-40 shadow-lg  rounded/>

`“mlops engineer pixel art”`
</v-click>
</div>

<style>
li:not(li:first-child) {
  margin-top: 0;
}
</style>


---

# Monitoring

::left::

<div class="-mr-12">
<v-clicks>

- Will we know if the predictions were correct?
- What metrics should we use?
- Ensure that only "unbiased data" is monitored
  	- We may "poison" the data by acting on the predictions ☠️
- How often should the metrics be computed?
- Set up automatic alerts
- Set up automatic retraining
- Fix operational issues and triage ML issues
- Tooling:
  	- Python <carbon-logo-python/>
    - Cloud <carbon-IbmCloudHpc />
  	- Orchestrators <img src="https://icon.icepanel.io/Technology/svg/Apache-Airflow.svg" inline h-5 grayscale/>
  	- Monitoring services <img src="https://assets-global.website-files.com/6266b595eef18c96eef938e2/62b245d0f032adaa18124084_evidently_ai_logo_fi.png" inline h-5 grayscale/>
  

</v-clicks>
</div>

::right::

<div flex flex-col items-center justify-center h-full class="-mt-4">

<v-click>
<img src="https://openai-labs-public-images-prod.azureedge.net/user-FpwegUavI965wXO1WB5HjsxZ/generations/generation-aHp55zVrme5SmXxdWkdgYhCK/image.webp" h-40 shadow-lg  rounded/>

`“mlops engineer pixel art”`
</v-click>

<v-click>
<img src="https://openai-labs-public-images-prod.azureedge.net/user-FpwegUavI965wXO1WB5HjsxZ/generations/generation-IiIHE6KT2n9pUDekqGTsEJlr/image.webp" h-40 shadow-lg rounded/>


`“data and cloud engineer pixel art”`
</v-click>
</div>

<style>
li:not(li:first-child) {
  margin-top: 0;
}
</style>
---


---
layout: iframe

# the web page source
url: https://sli.dev/custom/config-unocss
---
<!--
1. mlops definitions - operations?
2. ideal vs practical mlops
3. ML Lifecycle
4. use case, explained - content moderation
5. batch vs. real time
6. batch
7. real time
8. latency
9. examples
10. exercise/live demo
11. -->
