# Art Project Design Document

## Project Overview

**Goals:**
- Explore the potential of AI in the field of art.
- Evaluate the quality of AI-generated art through a judging AI system trained on winning results from art competitions.
- Identify AI-generated art that aligns best with human aesthetic preferences, aiming for an "optimal" artistic outcome.

**Related AI Projects:**
- Limited research on AI for judging art, with YOLO tested on paintings for classification and detection.
- Extensive work on art generation, including DALL-E, Bing, Midjourney, etc.

## Functional Requirements

1. Generate 10 art pieces in a user-specified style.
2. Train a neural network to identify patterns in winning results from art competitions.
3. Rank generated art by likelihood of winning a contest.

## Non-Functional Requirements

1. Art-generation AI must produce 10 pieces in under 60 seconds.
2. Judging AI preferences should be consistent across repeated trials.
3. User interface accessible to both technical and non-technical users.

## Technologies to Be Used

- **Programming Language:** Python 3, NumPy, OpenCV/PyTorch.
- **AI Model:** DALL-E 3 for image generation using OpenAI API.

## User Profiles

- **Professional and Amateur Artists:** Evaluate their own art.
- **Art Educators:** Teach techniques for quality art visually and interactively.
- **Art Museums:** Explore opportunities for exhibiting AI-generated art.
- **Art Judges:** Define more objective criteria for AI art competitions.
- **Psychologists:** Gain insights into the nature of human subjectivity.

## Technical Limitations

**Generation:**
- Challenges with human figures (hands, teeth, etc.).
- Input quality crucial for good image outcomes.
- Accuracy of image to prompt is essential.

**Evaluation:**
- Difficulty in proper image ranking.
- Classification lacks a limit of one image per label.
- Limited to providing general rankings rather than comparative ones.

## User Interface (UI)/User Experience (UX)

1. Start with a “Generate Art” button.
2. User selects art style from a drop-down menu.
3. Loading bar during AI art generation.
4. Display generated art pieces in a grid format.
5. User can press “Judge Art” button.
6. Multiple art pieces possible for each placing.
7. Designed for accessibility to non-technical and non-artistic users.

## Team Roles and Responsibilities

**Toba and Josh:**
- Development and training of the model.
- Creation of presentations and reports.
- Documentation.
- Generation of AI art.
- Testing network with generated art.