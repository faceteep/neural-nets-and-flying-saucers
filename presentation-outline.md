# Introduction

## Who is this guy?

A brief introduction.
## The minds behind the research

**Credits:**

- Arian Wood
- Nicholas Carlini
- Nicolas Papernot
- Ram Shankar
- Siva Kumar
- Hyrum Anderson
- Others
# Flight Path

Briefly go over the agenda and set the tone for the talk.
# First Contact

## ML overview
## What are the benefits
## Why it seems to be all the rage all of a sudden

# Unidentified Flaws and Oversights

With everyone racing to catch up with the rapid advancements and popularity of AI, security is easy to overlook.
# Confirmed Sightings

Substantiate the previous section by highlighting some actual attacks and ongoing research:

- Adrian's work on supply chain attacks
- Phishing Attacks (Will Pearce)
- LLMs (Dropbox at CAMLIS)
- Others
# Systems Check

The rest of this talk will focus on answering the following questions:

- So where does security fit? 
- What kinds of attacks are possible?
- And what can we do about them?

# Systems check...what system?

In order to answer the previous questions, we need to understand how this technology is used.
## Demo: UFO Reporting System

**Show how the technology is used in a sample application:**

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
