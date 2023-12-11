# *Neural Nets and Flying Saucers*

# Introduction

## Who am I?

A brief introduction.

## The minds behind the research

**Credits:**

- Adrian Wood
- Nicholas Carlini
- Nicolas Papernot
- Ram Shankar
- Siva Kumar
- Hyrum Anderson
- Others

# Flight Path (Agenda)

Briefly go over the agenda and set the tone for the talk.

# First Contact (ML Overview)

## AI/ML Intro

**OLD**

- All the rage
- Not new, timeline
- Why is it all the rage now?
- So what is it, how does it work?
  - It's all just math - Statistics, Linear Algebra
  - Supervised vs unsupervised learning
  - Classification vs Regression problems
  - Training
  - Models (All gets saved in a model for future use)
 
**NEW**

## Applications

- Image and Speech Recognition: Machine learning algorithms are extensively used for recognizing images and speech. For example, facial recognition in photos and voice assistants like Siri or Alexa.
- Medical Diagnosis: AI and machine learning are used to identify diseases and assist in diagnosing based on medical imaging, genetic information, or other data.
- Self-Driving Cars: Machine learning algorithms help in making decisions for autonomous vehicles, including recognizing objects, predicting pedestrian behavior, and navigating.
- Natural Language Processing (NLP): Used in applications like language translation (Google Translate), chatbots, and sentiment analysis.


## But how do these systems work

### Solving problems with traditional programming

- imagine a developer is asked to write a program that can detect wether someone was going over the speed limit
- they would probably come up with something like this.
- Even without programming experience, it isn't difficult to see that the functions takes three inputs...
- A straightforward programming task using a clear function/algorithm for deciding whether the are classified as true or false

### Solving problems with Machine Learning

- Now what if we asked the programmer to write a function that can classify any image as a circle, triangle, or square
- They could perhaps start by defining rules, like counting three sides for a triangle, look for round edges for a circle
- Now what if the shapes were hand drawn? Is this a circle, or a square? 
- They would quickly realize that writing a program, or a function, to perform this task is unfeasible due to the variabilty in hand drawn shapes
- This is a problem tailor made for machine learning

#### Types of Machine Learning

- Becaused in traditional programming, we define the process (a function) to turn inputs into outputs.
- But with machine learning, we feed the system inputs (and their outputs when available) to derive the process itself.
- This process is known as a model, which can then be applied to new, unseen data to make predictions or assessments. 
- Essentially, machine learning algorithms act as universal creators of functions.

(show video of function guy)

1) Supervised Learning

Definition: The algorithm learns from labeled training data, trying to make predictions or decisions.

Types:

- Classification: Identify threats, such as distinguishing between harmful and harmless emails.
- Regression: Assess risk levels, like predicting the likelihood of a system being vulnerable to a specific type of attack.

Algorithms:

- 
- 

2) Unsupervised Learning

Definition: Deals with unlabeled data. The algorithm tries to learn the underlying patterns without any explicit instructions.

Types:

- Clustering: Automatically grouping similar types of network behavior to identify potential threats or anomalies, without predefined categories.
- Dimensionality Reduction: Simplifying complex cybersecurity data (like logs with numerous variables) to more manageable and insightful formats, aiding in quicker threat detection.

Algorithms:

- 
- 

3) Reinforcement Learning

- Imagine training an adaptive cybersecurity system. The algorithm learns through trial and error, akin to teaching a pet. It makes decisions (like blocking or allowing traffic), receives feedback (rewards for correct identifications and penalties for false positives/negatives), and adjusts its approach to improve accuracy in real-time threat response.

Algorithms:

- 
- 

#### How would we solve the shape problem?

- Supervised learning
- large dataset of images and their labels (expected outputs)
- Algorithm: Nueral Network

(show video)

- backpropagation
- error => loss function
- gradient
- gradient decent (update model)



*We'll now look at a model I trained for the research I'll be demoing. Specifically I want to demonstrate the exact ML dev ops data scientists follow when developing a new model.*
 
  ## Demo ML Dev OPs
  - Data aquisition
  - Preprocessing (key concepts)
  - Training (key concepts)
    - Trained a model from scratch
    - Then used a pretrained model (Introduce concept of transferability)
  - Fine tuning (key concepts)
  - Inference, make decisions, ready for production

*mention stats, val_loss, val_accuracy - very good model ready for production use*
*These steps are the core of AI/ML development operations. This is in large part what datascientists get hired to do.

# Unidentified Flaws and Oversights  (Is security being overlooked?)

Now, with everyone racing to implement soplutions like this, security is easy to overlook.

## Confirmed Sightings (Known Exploits)

Substantiate the previous section by highlighting some actual attacks and ongoing research:

- Adrian's work on supply chain attacks
- Phishing Attacks (Will Pearce)
- LLMs (Dropbox at CAMLIS)
- Adversarial examples
- Others

## Industry Standards

As a result, industry is catching up:

- OWASP
- MITRE
- ML Framework (Adrian)

# Demos

The rest of this talk will focus on addressing the following questions:

- What kinds of attacks are possible? (will focus on just a few attack vectors)
- And what can be done about them?

We now know how this technology is developed, we created a model and its ready for use in production, but in order to answer these questions, we need to understand how the technology is **used**.

## UFO Reporting System & Huggingface (DEMO)

Show the app and its use-cases.

Introduce first attack then go to the attack slide:

### Demo: DNN Attacks (Go back to slides)

Force a model to infer an arbitrary class by giving it a carefully crafted image (targeted adversarial image).

### Demo: Trojan Models (Go back to slides)

Show what an infected model looks like (high level code review) and what it does. Link to Adrian's work for further details.

### Demo: Supply Chain Attacks (Go back to slides)

Pulling infected model from Huggingface to use in UFO app demonstrating RCE on developer machine.

### Demo: LLM Attacks (Go back to slides)

Prompt injection in UFO Tracker page.
   
## ML/AI Supply Chain (THIS SECTION MAY OR MAY NOT MAKE THE CUT) (DEMO)

**Talk about how this app fits in an enterprise technology ecosystem :

==Highlight attack vectors==

# Safe Landing (Mitigating Controls)

**Scary, what can be done?**

- Supply chain attacks
- Adversarial LLM
- Infected models
- Adversarial DNN

# For the intrepid explorer

**Recommended learning resources:**

- Books (Not with a bug but with a sticker)
- Researchers to follow (Arian Wood, Nicholas Carlini, Nicolas Papernot, Ram Shankar, Siva Kumar, hyrum anderson)
- Learning courses (fast.ai, building an LLM from scratch)
