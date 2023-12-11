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

- All the rage
- Not new, timeline
- Why is it all the rage now?
- So what is it, how does it work?
  - It's all just math - Statistics, Linear Algebra
  - Supervised vs unsupervised learning
  - Classification vs Regression problems
  - Training
  - Models (All gets saved in a model for future use)

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

# Unidentified Flaws and Oversights  (Is security breing overlooked?)

Now, with everyone racing to implement soplutions like this, security is easy to overlook.

## Confirmed Sightings (Known Exploits)

Substantiate the previous section by highlighting some actual attacks and ongoing research:

- Adrian's work on supply chain attacks
- Phishing Attacks (Will Pearce)
- LLMs (Dropbox at CAMLIS)
- Others

## Industry Standards

- OWASP
- MITRE
- ML Framework (Adrian)

## Demo: UFO Reporting System

The rest of this talk will focus on addressing the following questions:

- What kinds of attacks are possible?
- And what can be done about them?

We now know how this technology is developed, but in order to answer these questions, we need to understand **how** the technology is used.

**Introduce the app and its practical AI/ML use cases:**

- LLM use case (UFO Tracker)
- DNN use case (File upload validation)
- Getting models from Huggingface
   
## ML/AI OPs

**Talk about the "SDLC" process for model development:**

==Highlight attack vectors==
## ML/AI Supply Chain

**Talk about how this app fits in an enterprise technology ecosystem :

==Highlight attack vectors==

# Preparing for Invasion

Now focus on each attack vector (show vector thumbnail as it was shown previously so audience knows where we're at).

## Demo: Infected Models
Show what an infected model looks like (high level code review) and what it does. Link to Adrian's work for further details.
## Demo: Supply chain attacks
Pulling infected model from Huggingface to use in UFO app demonstrating RCE on developer machine.
## Adversarial DNN
Model extraction in file validation feature in UFO app to bypass file upload controls.
## Adversarial LLMs
Prompt injection in UFO Tracker page.

# Safe Landing: Mitigating Controls

**Scary, what can be done?**

- Supply chain attacks
- Infected models
- Adversarial DNN
- Adversarial LLM

# For the intrepid explorer

**Recommended learning resources:**

- Books (Not with a bug but with a sticker)
- Researchers to follow (Arian Wood, Nicholas Carlini, Nicolas Papernot, Ram Shankar, Siva Kumar, hyrum anderson)
- Learning courses (fast.ai, building an LLM from scratch)
