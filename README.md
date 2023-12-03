# Art Contest

## Overview

We use an art-generation AI (e.g. DALL-E 3 or Midjourny) to generate 10 pieces of art in an artstyle specified by the user.

## Art Generation Process
If we choose to use DALL-E, then we can follow the following documentation as a guide: [Image generation - OpenAI API](https://platform.openai.com/docs/guides/images/usage?context=node).

## Art Competition Analysis
Then, using an AI that has been trained on the results of past art competitions, we determine which pieces of generated art would most likely win an art competition. Here’s a link to some of the most prominent art competitions that we can potentially train the second AI on: [Famous Art Competitions](https://docs.google.com/document/d/1KVvRwFW128LQDPw9TKWAlmKQ-JCHwYefLqyTPciWMcU/edit?usp=sharing).

### Model Architecture
The model we will use is a neural network where the inputs are artworks and the labels are the position they got in the competition. To save time, we will use a pre-trained network and a new layer on top that will be trained instead of training a full network from scratch.

## Ethical Use Guidelines
For detailed information on the ethical use of our AI project, please refer to our [Ethical Use Guidelines](https://github.com/AIFictionFact/F23_Art_Contest/blob/main/Ethical%20Use%20Guidelines.md).
