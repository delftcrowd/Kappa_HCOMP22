# HCOMP22 Papers from Kappa

Kappa is one of the research lines in the [Web Information Systems](https://www.wis.ewi.tudelft.nl/) group at Delft University of Technology. In Kappa, we investigate Crowd Computing and Human-Centered AI: two core areas which are instrumental in developing the next generation of data-driven AI systems.
Encompassing *Human-in-the-loop computing*, *Human-AI interaction*, and *User Modeling and Explainability*, these areas consider
- **AI by humans**: the computational role of humans for AI systems
- **AI for humans**: and the interactional role of humans with AI systems

**Papers presented at HCOMP 2022**
- [Goal-Setting Behavior of Workers on Crowdsourcing Platforms: An Exploratory Study on MTurk and Prolific](#goal-setting-behavior-of-workers-on-crowdsourcing-platforms-an-exploratory-study-on-mturk-and-prolific)
- [CHIME: Causal Human-in-the-Loop Model Explanations](#chime-causal-human-in-the-loop-model-explanations)
- [Gesticulate for Health’s Sake! Understanding the Use of Gestures as an Input Modality for Microtask Crowdsourcing](#gesticulate-for-healths-sake-understanding-the-use-of-gestures-as-an-input-modality-for-microtask-crowdsourcing)
- [It Is like Finding a Polar Bear in the Savannah! Concept-Level AI Explanations with Analogical Inference from Commonsense Knowledge](#it-is-like-finding-a-polar-bear-in-the-savannah-concept-level-ai-explanations-with-analogical-inference-from-commonsense-knowledge)
- [SignUpCrowd: Using Sign-Language as an Input Modality for Microtask Crowdsourcing](#signupcrowd-using-sign-language-as-an-input-modality-for-microtask-crowdsourcing)

## Goal-Setting Behavior of Workers on Crowdsourcing Platforms: An Exploratory Study on MTurk and Prolific

**Authors**: Tahir Abbas and Ujwal Gadiraju

[**Link to Paper**](https://ojs.aaai.org/index.php/HCOMP/article/view/21983) 

**Synopsis**

## CHIME: Causal Human-in-the-Loop Model Explanations  

**Authors**: Shreyan Biswas, Lorenzo Corti, Stefan Buijsman, and Jie Yang  

[**Link to Paper**](https://ojs.aaai.org/index.php/HCOMP/article/view/21985)

[**Link to Repository**](https://github.com/delftcrowd/CHIME_HCOMP22)

**Synopsis**

Explaining the behaviour of Artificial Intelligence models has become a necessity. Their opaqueness and fragility are not tolerable in high-stakes domains especially. Although considerable progress is being made in the field of Explainable Artificial Intelligence, scholars have demonstrated limits and flaws of existing approaches: explanations requiring further interpretation, non-standardised explanatory format, and overall fragility. In light of this fragmentation, we turn to the field of philosophy of science to understand what constitutes a good explanation, that is, a generalisation that covers both the actual outcome and, possibly multiple, counterfactual outcomes. 
In this work led by Shreyan, we propose CHIME: a human-in-the-loop, post-hoc approach focused on creating such explanations by establishing the causal features in the input. 
We first elicit people's cognitive abilities to understand what parts of the input the model might be attending to. Then, through Causal Discovery we uncover the underlying causal graph relating the different concepts. Finally, with such a structure, we compute the causal effects different concepts have towards a model's outcome. We evaluate the Fidelity, Coherence, and Accuracy of the explanations obtained with CHIME with respect to two state-of-the-art Computer Vision models trained on real-world image data sets. We found evidence that the explanations reflect the causal concepts tied to a model's prediction, both in terms of causal strength and accuracy. We think exploring the intersection between Explainable AI and Causal Inference is beneficial to build better explanation methods.

## Gesticulate for Health’s Sake! Understanding the Use of Gestures as an Input Modality for Microtask Crowdsourcing

**Authors**: Garrett Allen, Andrea Hu, and Ujwal Gadiraju

[**Link to Paper**](https://ojs.aaai.org/index.php/HCOMP/article/view/21984)

**Synopsis**

## It Is like Finding a Polar Bear in the Savannah! Concept-Level AI Explanations with Analogical Inference from Commonsense Knowledge

**Authors**: Gaole He, Agathe Balayn, Stefan Buijsman, Jie Yang, and Ujwal Gadiraju

[**Link to Paper**](https://ojs.aaai.org/index.php/HCOMP/article/view/21990)

[**Link to Repository**](https://github.com/delftcrowd/HCOMP2022_ARCHIE)

**Synopsis**

With recent advances in explainable artificial intelligence (XAI), researchers have started to pay attention to conceptlevel explanations, which explain model predictions with a high level of abstraction. However, such explanations may be difficult to digest for laypeople due to the potential knowledge gap and the concomitant cognitive load. Inspired by recent work, we argue that analogy-based explanations composed of commonsense knowledge may be a potential solution to tackle this issue. In this paper, we propose analogical inference as a bridge to help end-users leverage their commonsense knowledge to better understand the concept-level explanations. Specifically, we design an effective analogy-based explanation generation method and collect 600 analogy-based explanations from 100 crowd workers. Furthermore, we propose a set of structured dimensions for the qualitative assessment of analogy-based explanations and conduct an empirical evaluation of the generated analogies with experts. Our findings reveal significant positive correlations between the qualitative dimensions of analogies and the perceived helpfulness of analogy-based explanations. These insights can inform the design of future methods for the generation of effective analogy-based explanations. We also find that the understanding of commonsense explanations varies with the experience of the recipient user, which points out the need for further work on personalization when leveraging commonsense explanations.

## SignUpCrowd: Using Sign-Language as an Input Modality for Microtask Crowdsourcing

**Authors**: Aayush Singh, Sebastian Wehkamp, and Ujwal Gadiraju

[**Link to Paper**](https://ojs.aaai.org/index.php/HCOMP/article/view/21998)

**Synopsis**
