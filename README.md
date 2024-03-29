# EMAR 349: Machine Learning for the Arts - Spring 2024

[Description](#description) | [Schedule](#course-schedule) | [Resources](#resources) | [Grading](#course-grading-policy) | [Policies](#policies) | [References](#references)

![Image](ml_art2019.png)

# Description

As Artificial Intelligence and Machine Learning transform all aspects of culture, industry, and scholarship, it is essential to train the next generation of AI-literate artists and engineers in these emerging technologies, and to equip them with the critical context necessary to assess their consequence. How do computational tools augment, assist, or replace traditional human creative efforts? What new forms and expressions are fostered by these tools?

This project-based course will be conducted primarily in python using free, open-source machine learning and scientific computing toolkits, running on cloud-based educational computing resources. In addition to hands-on experience with ML techniques, students will become familiar with cloud-based workflows and jupyter notebooks. Architectures and topics covered include Recurrent Neural Networks (RNNs), Convolutional Neural Networks (CNNs), Diffusion, Transformer Models, Wavenets, Generative Adversarial Networks (GANs) and others. Students will be responsible both for technical implementation and creative value of course projects.

## Details
- **Time:** Th 2:00-4:45pm
- **Location:** CEMA 205
- **Instructor:** Robert Twomey
  - **My Zoom:** [https://unl.zoom.us/my/twomey](https://unl.zoom.us/my/twomey)
  - **Office Hours:** Wednesday, 3-4pm on zoom or by appointment
- **Teaching Assistant:** Reid Brockmeier
  - **Office Hours:** 2 hours TBD.

## Course objectives
- Experiential Learning
- Critical thinking and making
- Train and deploy Neural Networks (NN) and Machine Learning (ML) models
- Exposure to contemporary Machine Learning and Artificial Intelligence technologies.
- Exposure to contemporary generative arts projects and practitioners.
- Think critically about generative arts processes

A student who successfully completes this course will:
- Be able to understand and critique contemporary Machine Learning (ML), Artificial Intelligence (AI),
and deep learning technologies and their consequences.
- Demonstrate a satisfactory ability to knowledgably critique and engage in a discussion about
creative work employing ML and generative art techniques.
- Be able to manage the basics of version control and software project management.
- Use online cloud-computing platforms for ML and generative arts processes.

**Prequisites:** Major in Emerging Media Arts and successful completion of EMAR161 Computational Media Studio II, or permission of instructor.

# Resources
- **Syllabus + Website:** [ml.roberttwomey.com](https://ml.roberttwomey.com)
- **Code:** [https://github.com/roberttwomey/ml-art-code](https://github.com/roberttwomey/ml-art-code)
- **Discord Channel:** `#ml-for-art-sp2024` on the Carson Center server [https://discord.com/channels/688079641738608705/1181082635867541585](https://discord.com/channels/688079641738608705/1181082635867541585)
- **Class Zoom:**  [https://unl.zoom.us/j/94101425950](https://unl.zoom.us/j/94101425950)
- **Canvas:** [https://canvas.unl.edu/courses/167819/](https://canvas.unl.edu/courses/167819/)
<!--- **Github Classroom:** this is where you will submit your code: [link to come]()-->

# Course Schedule
(Subject to Change-Always check back for most up to date information)

| Week | Topic |
|------|-------|
| 1 | **Hello. Syllabus and Policies. Compute Setup** <br> **Generative Systems in the Arts** <br> - Course environment setup <br> - python/jupyter basics;<br> - Exercise: introductory python/jupyter/colab exercise <br> HW: RNN in 100 lines|
| 2 | **Basics of Neural Nets. Text Generation I** <br> - Historical Approaches;<br> - RNNs, LSTMs, GRUs;<br> - text scraping and data cleaning;<br> - RNN exercise;<br> Assign Project 1 |
| 3 | **Text Generation II**<br> - Transformers;<br> - Fine-Tuning;<br> - Exercise: GPT and fine-tuning;<br> - Due: Project 1 Proposal |
| 4 | **Chatbots, Interactive Text**<br> - Time Series in ML<br> - Exercise: interactive text |
| 5 | **Time II: Autoencoders, Embeddings, Sketch-RNN** <br>- Sketch-RNN exercise <br> - Due: Project 1 |
| 6 | **Audio I**<br> - Intro to Generative Audio<br> - Generative Networks for Music<br> - Exercise: MIDI RNN|
| 7 | **Audio II**<br> - Music transformers<br> - Speech generation<br> - Exercise: speech generation<br> - Assign Project 2 |
| 8 | **Audio III**<br> - Speech Recognition<br> -vocal cloning<br> - Exercise: speech interaction <br> - Due: Project 2 Proposal |
| 9 | **Visual Processing**<br> - CNNs<br> - Style Transfer and Deep Dream<br> - Exercise: style transfer/deep dream<br> |
| 10 | **GANs**<br> - Generative Adversarial Networks<br> -Exercise: GAN<br> - Due: Project 2 <br> - Assign Project 3|
| 11 | **Visual II**<br> - Segmentation and masked generation - GauGAN exercise - Due Project 3 Proposal |
| 12 | **Text and Image**<br> - Image Captioning, transformers and GANs<br> - Text to image translation (CLIP, DALL-E, guided diffusion)<br> - Exercise: text and image<br> - Due: Final Project Proposal |
| 13 | **ML and Video**<br> - Video processing exercise<br> - Due: Project 3<br> - Exercise: Final project proposal |
| 14 | **Platforms and Applications**<br> - infrastructure for ML and the Arts<br> - Final project work time |
| 15 | **Workshopping Final Presentations**<br> - Final project work time |
| 16 | Exhibition/Showcase Open Studios (Final Project, Talk, Documentation due) NO FINAL EXAM |

<!--
## Introduction to Art and ML (Week 1)
**Day 1: Course and Syllabus** 9/29
- Lecture: ([pdf](https://drive.google.com/open?id=1_RhMhnznkVwYLGB0ZzACeH5U0yR4hOgg))
  - Syllabus, policies, schedule
  - Projects
  - My approach
- Lab:
  - Enrollment questions?
  - Sign up for slack [https://join.slack.com/t/ucsd-ml-art/signup](https://join.slack.com/t/ucsd-ml-art/signup)
  - Log onto datahub
  - Clone repository: **New->Terminal**:
    - `git clone https://github.com/roberttwomey/ml-art-code/`

**Homework:** Post something you are interested in (a project, paper, github link) to [#shiny](https://ucsd-ml-art.slack.com/messages/CHJDGRV0X).

**Day 2: Introduction to ML and the Arts** 10/2
- Lecture ([pdf](https://drive.google.com/open?id=17jwUvIypWtmXWn7B6dOS9Yq5GcHVbrtc))
  - Generative Systems in Art Overview
  - Survey of notable work in Art and ML
  - NN Basics

**Lab 1: Make sure you can log in** 
- Hands-on with datahub.ucsd.edu, jupyter
- Confirm everyone's logon works for datahub.ucsd.edu.
- Help? 

**Homework:** Read Andrej Karpathy's _The Unreasonable Effectiveness of RNNs_ (2015) [http://karpathy.github.io/2015/05/21/rnn-effectiveness/](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)

## Text Generation (Week 2)

**Day 3: Generative Text** 10/7
- Lecture ([pdf](https://drive.google.com/open?id=1LIfsYbEd8JDvDXDirf_SU6Kk2tQPiLnM))
  - Approaches to generative text
    - RNNs (karpathy) (character level)
    - LSTM/GRU
  - Practical Issues
    - Where to get a textual corpus. 
    - Working with textual corpora (cleaning, parsing, etc.)
  - Outputs
    - Generative text (recipes, poetry, fiction, screenplays, etc…)
    - How to compose / harness RNN creativity?
- **Assign Project 1: Generative Text** 
  - [Generative Text Assignment](https://docs.google.com/document/d/17FX0Vt3ur9QVmhnq4n4JJ0dmqBJuKIKGrslLoAkDpeM/export?format=pdf). Due 10/20/2019, 11:59pm.
  - Examples of student projects from last quarter.
  - Questions?

**Day 4: Text part 2** 10/9
- Lecture ([pdf](https://drive.google.com/open?id=1yzy1bKY7Nf_wHvL6sxyMu9Vi0fX1fCZu))
  - Transformers and Attention 
  - Fine-tuning
  - Case Study: GPT, GPT-2

**Lab 2: GPT-2 Examples**

**Homework: Project proposal**
- Please clone the project1 repository from github classroom, and edit the abstract to be a description of your proposed project.

## Time Series in ML (Week 3)

**Day 5: Chatbots** 10/14
- Lecture ([pdf](https://drive.google.com/open?id=1qjeE2ZlX-0XVfThCwBPoCgpFb1rsdm2v))
  - Chatbots (the eliza effect)
  - Issues
   - Sense and non-sense with ML.
   - Wilful suspension of disbelief
   - Projective psychology
   - Learning?
   
**Lab: Chatbots**
- Hands on with chatbots:
  - ELIZA: [https://www.masswerk.at/elizabot/](https://www.masswerk.at/elizabot/)
  - Alicebot Alysse: [http://demo.vhost.pandorabots.com/pandora/talk?botid=829713883e34f760](http://demo.vhost.pandorabots.com/pandora/talk?botid=829713883e34f760)
  - Cleverbot: [https://www.cleverbot.com/](https://www.cleverbot.com/)
  - Hugging Face chatbot demo: [https://convai.huggingface.co/](https://www.cleverbot.com/)
- Check in regarding project1 idea

**Day 6: Autoencoders, Embeddings, Sketch-RNN** 10/16
Autoencoders, Embeddings, Sketch-RNN
- Lecture ([pdf](https://drive.google.com/open?id=1TaidNOomzcQ3zK8asDr6U6i_didF8kp9))
  - VAEs (MNIST VAE)
  - Latent representation, Embeddings
  - Modeling Drawings (Sketch-RNN)
- Talk about how to submit project 1.

**Lab: Autoencoders and online Sketch-RNN demos**
- Work through:
  - week3/Autoencoders.ipynb
  - Sketch-RNN interactive demos.
  
**Homework: Project 1**
- Reminder Project 1 is due Sunday night at midnight (10/20), we will spend Monday's class critiquing (in class discussion)
- __Bring a printed copy of your project!__

## Generative Audio (Week 4)

**Project 1 Due** 10/20 11:59pm

- Submit assignment to github classroom. Use the github classroom below: [Project 1](#project-1-generative-text)

**Day 7: Project 1 discussion** 10/21
- Bring printed copy of your project and abstract. 
- Discuss in small groups (20 minutes)
- Present selected projects to class (50 minutes)

**Day 8: Intro to Generative Audio** 10/23
- Lecture: History of generative music ([pdf](https://drive.google.com/open?id=1SfyC-SuYydrUaLC6b_8rosExbc3beamP)]
- Lab: Hands-on with contemporary music generators
  - NSynth: [blog](https://magenta.tensorflow.org/nsynth), [interactive example](https://experiments.withgoogle.com/ai/sound-maker/view/)
  - MusicVAE: [blog](https://magenta.tensorflow.org/music-vae), [interactive example](https://magenta.tensorflow.org/multitrack)
  - PerformanceRNN: [blog](https://magenta.tensorflow.org/performance-rnn), [interactive example](https://magenta.tensorflow.org/performance-rnn-browser)
  - GANSynth: [blog](https://magenta.tensorflow.org/gansynth), [interactive colab example](https://colab.research.google.com/notebooks/magenta/gansynth/gansynth_demo.ipynb)
  - Music Transformer: [blog](https://magenta.tensorflow.org/music-transformer)

## Audio Continued (Week 5)

**Day 9: Generative Networks for Music** 10/28
- Lecture: Contemporary Musicians using AI ([pdf](https://drive.google.com/open?id=1QdkvtpchKBNwihGf-ZhHf6heQSD5fuG-))
- Examples of Project 2 from last quarter. 
- Hands on with ML Music:
  - In small groups, work through these examples from the code repository (divide, conquer, and share!): [https://github.com/roberttwomey/ml-art-code/blob/master/week5/01_Activities.ipynb](https://github.com/roberttwomey/ml-art-code/blob/master/week5/01_Activities.ipynb)
  - Covering:
    - sequence generation
    - seeding sequences
    - sequence interpolation
    - direct sound synthesis
    - sound latent-space interpolation.
  
**Day 10: Speech Generation** 10/30
- Lecture ([pdf](https://drive.google.com/open?id=11SIAljfUtgI6ZK3rMQMxbD-7ADl0ahea))
  - Text to Speech 
  - Vocoders, Unit Selection
  - Art with Speech Synthesis
  - ML(Tacotron, WaveGlow, DeepVoice, DeepSpeech)
  
 **Lab: Hands-On with ML Speech**

_Synthesis_:

DeepVoice
  - [DeepVoice3: Single-speaker text-to-speech demo](https://colab.research.google.com/github/r9y9/Colaboratory/blob/master/DeepVoice3_single_speaker_TTS_en_demo.ipynb)
  - [DeepVoice3: Multi-speaker text-to-speech demo](https://colab.research.google.com/github/r9y9/Colaboratory/blob/master/DeepVoice3_multi_speaker_TTS_en_demo.ipynb)
- [Tacotron2/WaveGlow](https://colab.research.google.com/github/pytorch/pytorch.github.io/blob/master/assets/hub/nvidia_deeplearningexamples_waveglow.ipynb)

_Recognition:_

- [DeepSpeech](https://github.com/roberttwomey/ml-art-code/blob/master/week5/mozilla_deepspeech.ipynb) on datahub

**Homework: Project proposal**
- Please clone the project2 repository from github classroom, and edit the abstract to be a description of your proposed project.
  - I will discuss these individually with you during lab on Monday

## Visual Processing (Week 6)

**Day 11: Visual Processing** 11/4
- Lecture: CNNs ([pdf](https://drive.google.com/open?id=1wKY75xocKcn8Bb5HY3mpFpO1q6NLzVd5))
  - CNNs vs other NNs. 
    - LeNet
    - VGG16, VGG19

**Lab:** 
- Week 6 LeNet CNN, VGG19 Classification, Neural Style: [https://github.com/roberttwomey/ml-art-code/tree/master/week6
](https://github.com/roberttwomey/ml-art-code/tree/master/week6)
- Individual meetings about Project 2 ideas.

**Day 12: Style Transfer** 11/6
- Lecture: Style Transfer ([pdf](https://drive.google.com/open?id=1qFNlYUB8ze5KEf3-iyIN_VJQMF0vkDB6))
  - Neural Style Transfer
  - Fast Style Transfer
  - Arbitrary Style Transfer
  - Deep Photo Stylization
  - Popular applications

**Lab:**
- [https://github.com/roberttwomey/ml-art-code/tree/master/week6](https://github.com/roberttwomey/ml-art-code/tree/master/week6)
  - Fast Style, Arbitrary Style, Deep Photo Style
  
## Visual Continued (Week 7)

**Day 13: VETERANS DAY NO CLASS** 11/11

**Project 2 Due:** 11/12, 11:59pm, through github classroom.

**Day 14: Critique: Project 2** 11/13

## Visual Continued (Week 8)

**Day 15: Deep Dream and Gradient Ascent** 11/18
- Lecture: ([pdf](https://drive.google.com/open?id=1lrQGY3Nu1WuqiGfXfMNdhUztvn_IguR9))
  - Neural Doodle [https://github.com/roberttwomey/ml-art-code/tree/master/week8/Neural_Doodle_keras](https://github.com/roberttwomey/ml-art-code/tree/master/week8/Neural_Doodle_keras)
  - Deep Dream [https://github.com/roberttwomey/ml-art-code/tree/master/week8/deepdream](https://github.com/roberttwomey/ml-art-code/tree/master/week8/deepdream)
  - Gradient Ascent, maximal activation/excitation
  - GauGAN using [SPADE](https://github.com/NVlabs/SPADE)

**Lab:**
- Hands on with Deep Dream.

**Assign Project 3: Generative Visual**

**Day 16: GANs** 11/20
- Lecture: ([pdf](https://drive.google.com/open?id=1ikd8HH6VQITmJX2_vVdwVRwmAVXC--QH))
  - StyleGAN, BigGAN, CycleGAN, DCGAN, Pix2Pix on code repository: [https://github.com/roberttwomey/ml-art-code/tree/master/week8](https://github.com/roberttwomey/ml-art-code/tree/master/week8)
  - Ian Goodfellow tutorial on GANs, NeurIPS 2016 [https://www.youtube.com/watch?v=RvgYvHyT15E](https://www.youtube.com/watch?v=RvgYvHyT15E)
  - Art using GANs

**Lab:**
- BigGAN Latent Exploration
- StyleGAN Exploration
- Latent Math

**Homework: Project 3 proposal**
- For MONDAY: Please clone the project3 repository from github classroom, and edit the abstract to be a description of your proposed project.


## Visual (Week 9)

**Day 17: Image Captioning and Segmentation** 11/25
- Lecture: ([pdf](https://drive.google.com/open?id=1fyqdat0MlkbuNjgWtncWjkVBwnchEl__))
- Image Captioning with Visual Attention (MS-COCO)
  - https://colab.research.google.com/drive/1sGC26H7zIZEWrMdI-LN7cIWsF0Ak9tx9
- Semantic Segmentation
- Art using Segmentation and Captioning

**Lab**
- Review Project 3 proposals individually.

**Day 18: Platforms** 11/27
- Lecture: ([pdf](https://drive.google.com/open?id=1e1cq7NQSY5-bzwocT8V9ZxDjwP3tIEzK))
  - What is Datahub?
  - Embedded systems (NVIDIA jetson nano, Google Coral, TPUs, others)
  - Tools (DNNWeaver)  

## Final Project Development (Week 10)

**Project 3 due:** 12/1, 11:59pm.

**Day 19: Project 3 Critique** 12/2

**Homework**
- Final Projects
  - Project repository as usual through github classroom: []()
  - An extended project report (4 pages): [google docs](https://docs.google.com/document/d/133H59WZBmH6MlAgFSskFLMQITeIC5d9b2iuzsOfa4E8/edit?usp=sharing)
  - By wednesday: accept the classroom assignment, fill in your abstract/proposal. Check in with me on Wednesday during class.
- Inspiration for final projects (from your peers at CMU)
  - CMU ArtML Spring 19 Finals: http://kangeunsu.com/artml19s/gallery.html  
- Individual meetings regarding final project.


**Day 20: Creativity Metric Activity, Final Project Check-in** 12/4
- No Lecture
- Discuss Final Project Ideas
- In class Assessing Computational Creativity activity
  - In small groups (2 ppl), work with [this spreadsheet](https://docs.google.com/spreadsheets/d/1RVQS78aAa5CBBkG7tXRpURzETUh3lZbDeLWsOrUSkwg/edit?usp=sharing): 

## Final Presentations / Exhibition (Finals Week)

**FINAL TIME:** Wednesday December 11, 8-11am. Location TBD.
- PROJECT DUE: 8am, Wednesday December 11. 
- REPORT DUE: 11:59pm, Friday December 13 (add to your github repository as pdf)

-->

# Course Grading Policy

## Graded activities
- 25% Weekly Exercises – approximately 10 exercises
  * Code notebooks.
  * Small assignments/tasks as they arise, graded on completion.
  * Readings.
- 45% Projects – You will do three projects at 15% each*
  * Code, Documentation, and Results must be submitted for credit.
  * Any written proposals, work-in-progress updates, check-ins, etc., I request for individual projects.
- 20% Final Project
  * Code
  * Documentation
  * Presentation
- 10% Participation
  * Peer review and critique.
  * Finding and sharing resources on our course discussion. 

*Work will be evaluated on the quality of concept, the degree of experimentation (both aesthetic and technical), and final realization (again, aesthetic and technical). Prompts and rubrics will be provided with more specific details regarding each assignment and breakdowns

## Description of Assignments and Exams

__*Weekly Exercises*__
We will have regular, weekly programming assignments employing the tools and techniques covered in class. These will be short activities with clearly stated creative prompts and technical requirements. Projects will be graded on satisfactory completion with additional credit for creative, technical, expressive extension beyond requirements.

__*Projects*__
We will have three projects over the semester at 15% each. Each of these will explore one perspective on generative AI, and each will use the variety of generative media we have learned about in class (text, audio, speech, image, video, etc.). Projects will be submitted as github repositories following a uniform template. This includes a statement of concept, source code, links to data resources, discussion of results, and future directions. When assigned, students will submit a proposal/concept for their project to receive instructor feedback, and then work to complete the project. Projects will be presented and critiqued in class and github respositories will be submitted for grading.

__*Final Project, Documentation, and Presentation*__
At the end of the semester, you will propose and create a self-directed ML for the Arts project engaging a subject of your choice. You may either revisit a subject or idea that excited you from earlier in the semester, or explore a topic of interest that we have not covered in class. The format, workflow, and submission of this project will follow the process of the earlier projects. In week 16 we will have a showcase for these projects, including a short talk and exhibition of the resulting work. Projects will additionally be added to an online virtual gallery of ML Arts projects.

__*Participation*__
Contributions to class discussions and active participation in critiques and workshops are essential to the momentum of the course and the development of your ideas. This requires that you come to class prepared (having completed assigned reading or exercises), and ready to participate in class activities. Bring finished work for in-class crtiqiues. See the participation evaluation in the Grading Scale below for more information.

## Attendance
On-time attendance is required as well as playtesting inside and outside of section. Please notify your instructor in advance if you must be absent for illness or family emergency. Any absences must be cleared with the instructor, or justified with written documentation (e.g. letter from team, etc.). We do not differentiate between mental and physical health and in either case please be in communication for when you need to take a day off. After a student misses a week’s worth of classes each subsequent missed class will result in the reduction of the final grade by a full letter grade (i.e., A to B, B- to C-) Excessive tardiness or leaving early will also impact your grade and will follow the same rubric.

Please also note the JCSTF attendance policy:
- 4.7 Attendance Policy
- 4.7.1 After a student misses an equivalent of one week’s worth of classes, each subsequent missed
class will result in the reduction of the final grade by a full letter grade (i.e., A to B, B- to C-).
- 4.7.2 Students may be granted an excused absence at the instructor’s discretion.
- 4.7.3 Students may be granted an excused absence, at the instructor’s discretion, to allow those students to participate in extra-curricular events representing the University. In such cases, the instructor must be notified in advance.
- 4.7.4 This policy, as approved by the faculty, represents the minimum requirement. Faculty members are permitted to develop more stringent attendance requirements, as long as those requirements are detailed in writing in the class syllabus and distributed at the beginning of each course.
- 4.7.5 The policy on students who are late to class will be left up to the individual instructors.

## Late work policy
An assignment may receive an F if a student does not participate in every phase of the development of the project and meet all deadlines for preliminary materials (proposals, drafts, etc.). Failure to submit any of the graded course assignments is grounds for failure in the course. If a final draft or project, plus required addenda, is not submitted in class on the date due, it will be considered late and will lose one letter grade for each day or part of a day past due (A to B, etc.). Assignments are due in hard copy and or via email/link (online assignment). You must submit your assignments directly to the instructor. Any late submissions must be approved by your faculty instructor well in advance of the due date.

## Grading Scale
A+ = 96.67-100 | A = 93.33-96.67 | A- = 90-93.33 <br>
B+ = 86.66-90 | B = 83.33-86.67 | B- = 80-83.33 <br>
C+ = 76.67-80 | C = 73.33-76.67 | C- = 70-73.33 <br>
D+ = 66.67-70 | D = 63.33-66.67 | D- = 60-63.33 <br>
F = below 60%<br>

Here is a description of the kind of participation in the course that would earn you an A, B, C, etc. Your instructor may use pluses and minuses to reflect your participation more fairly, but this is a general description for each letter grade.

A – Excellent 

Excellent participation is marked by near-perfect attendance and rigorous preparation for class work. You respond to questions and activities with enthusiasm and insight and you listen and respond thoughtfully to your peers. You submit assignments on time, adhering to posted requirements, and demonstrate a thorough engagement with the assignment. You respond creatively to any feedback you receive (from both your peers and instructor). You are an active contributor to classroom community. 

B – Good<br>
Good participation is marked by near-perfect attendance and thorough preparation for class. You respond to questions with specificity and make active contributions to class. You submit assignments on time, and demonstrate a thorough engagement with the assignment. You respond effectively to the feedback you receive (from both your peers and instructor). You are a regular and reliable contributor to classroom community. 

C – Satisfactory<br>
Satisfactory participation is marked by regular attendance and preparation for class. You respond to questions when prompted and participate in classroom activities, though you may sometimes be distracted. You are present in class, with few absences, and have done some of the work some of the time. You submit assignments and make some efforts toward revision proposals and final submission. You are involved in classroom activities, but you offer minimal feedback and you may not always contribute fully to classroom community.

D – Unsatisfactory<br>
Unsatisfactory participation is marked by multiple absences from class and a consistent lack of preparation. You may regularly be distracted by materials/technology not directly related to class. You submit late or incomplete work. You are absent for classroom activities, or do not work cooperatively in collaborative environments. 

F—Failing<br>
Failing participation is marked by excessive absences, a habitual lack of preparation, and failure to engage in classroom activities and development processes.

# Policies

Course-specific policies and rules.

[Attendance](#attendance) | [Late Work](#late-work) | [Other People's Code](#other-peoples-code) | [UNL Course Policies and Resources](#unl-course-policies-and-resources)

## Attendance
On-time attendance is required as well as work inside and outside of section. Please notify your instructor in advance if you must be absent for illness or family emergency. Any absences must be cleared with the instructor, or justified with written documentation (e.g. letter from team, etc.). We do not differentiate between mental and physical health and in either case please be in communication for when you need to take a day off. After a student misses a week’s worth of classes each subsequent missed class will result in the reduction of the final grade by a full letter grade (i.e., A to B, B- to C-) Excessive tardiness or leaving early will also impact your grade and will follow the same rubric.

Please also note the JCSTF attendance policy:
- 4.7 Attendance Policy
- 4.7.1 After a student misses an equivalent of one week’s worth of classes, each subsequent missed
class will result in the reduction of the final grade by a full letter grade (i.e., A to B, B- to C-).
- 4.7.2 Students may be granted an excused absence at the instructor’s discretion.
- 4.7.3 Students may be granted an excused absence, at the instructor’s discretion, to allow those students to participate in extra-curricular events representing the University. In such cases, the instructor must be notified in advance.
- 4.7.4 This policy, as approved by the faculty, represents the minimum requirement. Faculty members are permitted to develop more stringent attendance requirements, as long as those requirements are detailed in writing in the class syllabus and distributed at the beginning of each course.
- 4.7.5 The policy on students who are late to class will be left up to the individual instructors.

## Late Work
An assignment may receive an F if a student does not participate in every phase of the development of the project and meet all deadlines for preliminary materials (proposals, drafts, work in progress, etc.). Failure to submit any of the graded course assignments is grounds for failure in the course. If a final draft or project, plus required addenda, is not submitted in class on the date due, it will be considered late and will lose one 5% for each day or part of a day past due (A to B, etc.). Assignments are due in class and via online submission, as specified in assignment descriptions. Any late submissions must be approved by your faculty instructor well in advance of the due date.

## Other People's Code
We will use many open source projects to make our work. It is ok to use others' code. However, **you need to cite your sources**, and **you need to do transformative work/make it your own**.

## UNL Course Policies and Resources

Students are responsible for knowing the university policies and resources found on this page ([https://go.unl.edu/coursepolicies](https://go.unl.edu/coursepolicies)):
- University-wide Attendance Policy
- Academic Honesty Policy
- Services for Students with Disabilities
- Mental Health and Well-Being Resources
- Final Exam Schedule
- Fifteenth Week Policy
- Emergency Procedures
- Diversity & Inclusiveness
- Title IX Policy
- Other Relevant University-Wide Policies

# Land Acknowledgment
We acknowledge that the University of Nebraska is a land-grant institution with campuses and programs on the past, present, and future homelands of the Pawnee, Ponca, Oto-Missouria, Omaha, Dakota, Lakota, Arapaho, Cheyenne, and Kaw Peoples, as well as the relocated Ho-Chunk, Iowa, and Sac and Fox Peoples. Please take a moment to consider the legacies of more than 150 years of displacement, violence, settlement, and survival that bring us together here today. This acknowledgement and the centering of Indigenous Peoples is a start as we move forward together for the next 150 years

# Addenda
## CMU Collaboration

We may have a couple of opportunities to interact with a similar class running this Spring at Carnegie Mellon University, as well as making a joint, online, public-facing exhibition for excellent student work (opt-in). More info coming soon!

# References
<!--- Past courses: [UCSD ECE188 ML for the Arts 2019](https://roberttwomey.github.io/ucsd-ml-art/)-->
