---
layout: default
title: CSC415 - Introduction to Reinforcement Learning
permalink: /
---

# Winter 2026 - CSC415: Introduction to Reinforcement Learning {#overview}

## Course Overview

Reinforcement learning is a powerful paradigm for modeling autonomous and intelligent agents interacting with the environment, and it is relevant to an enormous range of tasks, including robotics, game playing, consumer modeling and healthcare. This course provides an introduction to reinforcement learning intelligence, focusing on the study and design of agents that interact with a complex, uncertain world to achieve a goal. We will study agents that can make near-optimal decisions in a timely manner with incomplete information and limited computational resources.

This course will broadly cover the following areas:

* **Markov Decision Processes (MDPs)**
* **Reinforcement Learning** algorithms
* **Planning** methods
* **Function Approximation** (online supervised learning)

### Prerequisites

You need to be comfortable with: introductory machine learning concepts (such as from CSC311H5 or equivalent), linear algebra, basic multivariable calculus, intro to probability. You also need to have strong programming skills in Python.

**Prerequisites:** CSC311H5  
**Recommended:** CSC413  
**Credit Value:** 0.5

### Learning Outcomes

By the end of this course, students will be able to:

1. **Theoretically analyze** and **practically implement** fundamental and advanced Reinforcement Learning algorithms, ranging from tabular methods and DQN to Policy Gradients (PPO)
2. **Design and execute** a research project that applies these concepts to domains such as robotics (both simulation and real-world robots)
3. **Communicate findings** through a conference-level research paper
4. **Critically evaluate** the work of peers
5. **Effectively defend** technical decisions through oral presentations

---

## Course Information {#course-info}

### Course Delivery Details

* **Lectures:** In-person, Wednesdays @ 11:00 AM - 1:00 PM ET, DH 2070
* **Practicals:** In-person, Thursdays @ 7:00 PM - 8:00 PM ET, DH 2026
* **Announcements:** Will be posted on this website

### Instructor

**Dr. Amey Pore**

**Office Hours:**  
Wednesday, 6:00 PM - 7:00 PM  
_In Person: MN3110_

### Teaching Assistants

**Deniz Jafari**  
**Office Hours:**  
_Tuesday 5:15pm-6:15pm Online zoom_

**Quentin Clark**  
**Office Hours:**  
_Tuesday 5:15pm-6:15pm Online zoom_

---

## Course Material and Schedule {#schedule}

| Week | Date | Topic | Key Concepts | Lecture Slides |
|------|------|-------|--------------|----------------|
| **1** | Jan 7 | Foundations of Reinforcement Learning | Agent–environment loop, MDP structure, value functions, Bellman equations, biological motivation | [lecture1]({{ '/assets/lectures/lecture1_compressed.pdf' | relative_url }}) |
| **2** | Jan 14 | Dynamic programming | Policy evaluation, Policy iteration, Value iteration | [lecture2]({{ '/assets/lectures/lecture2_compressed.pdf' | relative_url }}) |
| **3** | Jan 21 | Monte Carlo & Temporal-Difference | MC prediction (first/every visit), TD(0), SARSA, Q-Learning | [lecture3]({{ '/assets/lectures/lecture3_compressed.pdf' | relative_url }}) |
| **4** | Jan 28 | Function Approximation | Value function approximation, Off-policy learning, Deep Q-Networks (DQN) | [lecture4]({{ '/assets/lectures/lecture4_compressed.pdf' | relative_url }}) |
| **5** | Feb 4 | Policy Gradient | REINFORCE, A3C | [lecture5]({{ '/assets/lectures/lecture5_compressed.pdf' | relative_url }}) |
| **6** | Feb 11 | Advanced Policy Gradient | A3C → PPO, trust-region optimization, GAE, training stability | [lecture6]({{ '/assets/lectures/lecture6_compressed.pdf' | relative_url }}) |
| **7** | Feb 25 | Exploration in RL | Intrinsic motivation (ICM, RND), robustness and generalization | |
| **8** | Mar 4 | Representation Learning | Contrastive learning (CURL), Data augmentation (DrQ-v2), Auxiliary tasks | |
| **9** | Mar 11 | RL for Robotics (Embodied RL) | Continuous control policies, sim-to-real transfer, domain randomization, hybrid IL + RL strategies | |
| **10** | Mar 18 | RL for LLMs and Alignment (RLHF) | Preference modeling, reward models, PPO/DPO/RLAIF, alignment issues, reward mis-specification | |
| **11** | Mar 28 | World Models & Latent Planning | Latent dynamics models (VAE, RSSM, Dreamer), imagination rollouts, planning in latent space | |
| **12** | Apr 2 | Final Project Presentations | Student presentations of term projects (oral defense) | |
| **13** _(Optional)_ | Apr 9 | Safe-RL and Hierarchical RL | Safe MDPs, constraint optimization, Lyapunov-based safety, CPO, risk-sensitive criteria, hierarchical task decomposition, options framework, HRL architectures | |

---

## Grading {#grading}

| Assessment | Weight | Due Date | Description |
|------------|--------|----------|-------------|
| **Laboratory Exercises** | 25% | Various dates | 6 lab exercises (top 5 count). Programming assignments in Python using Gymnasium and PyTorch. Implement algorithms from tabular methods to DQN and PPO. |
| **Midterm Exam** | 15% | Jan 29, 2026 | _Written test covering concepts from Weeks 1-4: MDPs, Bellman Equations, Q-Learning, and Policy Gradients._ |
| **Assignment 1** | 10% | Feb 13, 2026 | Literature review of assigned papers (2 papers) along with code implementation of one of the papers. |
| **Project Proposal** | 5% | Feb 24, 2026 | Document outlining selected research topic, intended environment/dataset, and hypothesis. |
| **Final Project Paper** | 25% | Mar 24, 2026 | Research paper in conference format (e.g., ICLR style) detailing methodology, experimental setup, results, and discussion. |
| **Assignment 2 (Peer Review)** | 10% | Mar 31, 2026 | Evaluation of peer project reports, providing constructive feedback on technical correctness, clarity, and novelty. |
| **Final Project Presentation** | 10% | Apr 2, 2026 | 10-minute oral presentation of research findings, methodology, and analysis. |

---

## Tutorial {#tutorial}

| Lab | Lab Date | Due Date | Topic |
|-----|----------|----------|-------|
| Lab 1 | Jan 15, 2026 | Jan 20, 2026 | Tabular value-iteration agent on Gridworld |
| Lab 2 | Jan 23, 2026 | Jan 27, 2026 | Compare MC and TD methods; Q-Learning with ε-greedy |
| Test | Jan 29, 2026 |  | 90mins test |
| Skill 1 | Feb 5, 2026 | Not graded | How to review a paper |
| Lab 3 | Feb 12, 2026 | Feb 17, 2026 | Implement DQN in Gymnasium (CartPole or MountainCar) |
| Lab 4 | Feb 26, 2026 | Mar 3, 2026 | Train PPO agent on Pendulum-v1 (dm_control) |
| Lab 5 | Mar 5, 2026 | Mar 10, 2026 | RLHF: LLM fine-tuning with RL |
| Lab 6 | Mar 12, 2026 | Mar 17, 2026 | Train CNN encoder on Atari frames; visualize latent space/RL for LLM |
| Skill 2 | Mar 19, 2026 | Not graded | How to write a paper |
| Demo/Presentation | Mar 26, 2026 |  | Project presentation/Real Robot Demos |

---

## Final Project {#project}

The course ends in a capstone research project where students produce a conference-level paper. This is the primary deliverable for the course.

### Project Resources

**Project Guidelines**  
Guidelines for the final project, including format requirements, evaluation criteria, and submission instructions.  
[Download Guidelines]({{ '/assets/pdf/csc415_project_guidelines.pdf' | relative_url }}){: .btn .btn-primary}

**Project Topics**  
Suggested research topics and project ideas to help you get started on your final project.  
[View Topics]({{ '/assets/pdf/csc415_project_topics.pdf' | relative_url }}){: .btn .btn-primary}

**Simulation Setup**  
Instructions for setting up simulation environments for your RL experiments, including Gymnasium, dm_control, and other relevant frameworks.  
[Download Setup Guide]({{ '/assets/pdf/csc415_simulation_setup.pdf' | relative_url }}){: .btn .btn-primary}

### Project Timeline

* **Feb 24, 2026:** Project Proposal Due (5%)
* **Mar 24, 2026:** Final Project Paper Due (25%)
* **Mar 31, 2026:** Peer Review Due (10%)
* **Apr 2, 2026:** Final Project Presentation (10%)

---

## Course References {#materials}

### Required Textbook

**Reinforcement Learning: An Introduction (2nd Edition)**

**Authors:** Richard S. Sutton and Andrew G. Barto  
**Available online:** [http://incompleteideas.net/book/](http://incompleteideas.net/book/)

This textbook covers foundational theory (MDPs, Bellman equations, TD learning) extensively. Best for Weeks 1–3 of the syllabus (Foundations, MC, TD).

### Additional Resources

The course draws inspiration from several excellent open-source courses and resources:

* **[UCL Course on Reinforcement Learning](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html)** by David Silver (DeepMind)
* **[Stanford CS234: Introduction to Reinforcement Learning](https://www.youtube.com/watch?v=WsvFL-LjA6U&list=PLoROMvodv4rN4wG6Nk6sNpTEbuOSosZdX)** by Emma Brunskill
* **[Stanford CS224R: Deep Reinforcement Learning](https://cs224r.stanford.edu/)** by Chelsea Finn
* **[Introduction to Reinforcement Learning](https://amfarahmand.github.io/IntroRL/)** by Amir-massoud Farahmand

---

## Course Policies {#policies}

### Late Submission Policy

<div class="alert alert-warning">
  <strong>Important Deadlines</strong><br>
  <strong>Laboratory Exercises:</strong> Late submissions are <strong>prohibited</strong>. No late work will be accepted for the laboratory component.<br>
  <strong>Assignments and Project Deliverables:</strong> Late submissions permitted for a maximum of <strong>3 days</strong> following the deadline. A penalty of <strong>15% per day</strong> will be deducted. Submissions made more than 3 days after the deadline will not be accepted.
</div>

### Attendance

Success in this course is highly correlated with active participation in both lectures and tutorial sessions. While attendance is not strictly graded for standard lectures, students are strongly encouraged to attend in person.

<div class="alert alert-info">
  <strong>Note:</strong> Attendance is <strong>mandatory</strong> for the Final Project Presentations in Week 12, as peer interaction is a core learning outcome.
</div>

### Academic Integrity

All work submitted must be your own. Collaboration on assignments is allowed but must be acknowledged. Plagiarism or any form of academic dishonesty will result in severe penalties, including possible failure of the course.

Please familiarize yourself with the [Code of Behaviour on Academic Matters](https://governingcouncil.utoronto.ca/secretariat/policies/code-behaviour-academic-matters-july-1-2019) and the [Code of Student Conduct](https://www.utoronto.ca/student-affairs/code-student-conduct).

### Generative AI Policy

**AI Tool Usage Guidelines**

Students are **permitted** to use AI tools (e.g., ChatGPT, Claude, GitHub Copilot) as learning aids and to assist in assignments. However:

* Students remain **ultimately accountable** for all work submitted
* **Citation is required:** Any content, code, or ideas produced by AI must be explicitly cited
* Include an "AI Statement" at the end of assignments detailing which tools were used and for what purpose
* **No grading penalty** for declared use of AI tools, provided they are cited correctly
* **Midterm Exam:** Closed environment - use of AI tools/electronic devices is strictly prohibited

### Accommodations

* **Religious Accommodations:** Information available at the [University's Policy on Scheduling](https://www.viceprovoststudents.utoronto.ca/student-resources/rights-responsibilities/accommodation-religious/)
* **Temporary Absence:** Students may use the ACORN Absence Declaration Tool for absences up to 7 consecutive days
* **Equity and Academic Rights:** The University of Toronto is committed to equity, meaningful inclusion, and respect for diversity

---

## Contact {#contact}

For questions about the course:

1. **Check this website** first
2. **Attend office hours:** Wednesday, 6:00 PM - 7:00 PM (MN3110)
3. **Email the instructor:** amey.pore@utoronto.ca
   * Please include **[CSC415]** in the subject line
   * Allow 24-48 hours for response during regular business hours
