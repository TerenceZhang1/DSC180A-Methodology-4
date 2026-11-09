# Terence Zhang

tez002@ucsd.edu

**Section:** D30 – LLM Reliability & Reasoning

**Mentors:** Misha Belkin and Tianhao Wang

**What is the most interesting topic covered in your domain this quarter?**

The most interesting topic to me this quarter has been activation steering based off emotions, especially the idea that concepts like pain or distress can appear as directions in a model’s internal activation space. I found it interesting that changing these internal representations can affect model behavior without changing the model’s weights.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

Something that I was thinking about and maybe would like to investigate whether a pain or distress steering direction transfers across different models and situations. For example, I would test whether a direction learned on one model or dataset still works on another model and whether steering continues to work when the model is placed under different types of pressure.

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**

A change I would make is to compare multiple methods for constructing the steering direction instead of relying on only one approach. Like I could compare difference-in-means with methods like contrastive activation addition or other learned concept-vector methods and evaluate which produces the most consistent steering.

**What other techniques would you be interested in using in your project?**

I would be interested in using techniques like linear probes to better understand how pain or distress is represented across different layers of the model. This could help us identify where these concepts are represented most clearly and whether the same representations are useful for both monitoring and steering.