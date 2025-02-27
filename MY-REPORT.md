![GenI-Banner](https://github.com/genilab-fau/genial-fau.github.io/blob/8f1a2d3523f879e1082918c7bba19553cb6e7212/images/geni-lab-banner.png?raw=true)

# {Automated Prompt Engineering for Requirement Analysis in SDLC}

Investigating Prompt Engineering techniques for generating Requirement Analysis in the Software Development Lifecycle (SDLC).

<!-- WHEN APPLICABLE, REMOVE THE COMMENT MARK AND COMPLETE
This is a response to the Assignment part of the COURSE.
-->

* Authors: [Jhansy Harshitha Vankayalapati](http://www.YOURPAGE.xxx), [Jamar Andrade](http://www.YOURPAGE.xxx), [Thrinay Kumar Devi Ramakrishna](http://www.YOURPAGE.xxx)
* Academic Supervisor: [Dr. Fernando Koch](http://www.fernandokoch.me)

  
# Research Question 

Which configuration of Prompt Engineering works best in combining techniques for Automated Prompt Engineering in Requirement Analysis for SDLC?
## Arguments

#### What is already known about this topic

* Prompt Engineering is critical in maximizing the efficiency of Generative AI models.

* Automated Prompt Engineering enhances consistency and improves result accuracy.

* Various techniques exist, such as manual, semi-automated, and fully automated prompt generation.

* Different levels of automation impact model performance in Requirement Analysis tasks.
#### What this research is exploring

<!-- Free-format; use the topics that are applicable to your exploration  -->

* We employ diverse Prompt Engineering techniques, including Automated Prompt Generation and Workflow Execution.

* We are building a framework to analyze different Prompt Engineering configurations in SDLC.

* We are exploring how variations in automation levels impact accuracy, efficiency, and cost.

#### Implications for practice

<!-- Free-format; use the topics that are applicable to your exploration  -->

* It will be easier to integrate AI-driven Requirement Analysis into SDLC workflows.

* It will optimize the balance between automation and manual intervention in AI-driven requirements gathering.

* We will better understand how AI can enhance software development ideation and exploration phases.

# Research Method

The research follows an experimental approach, where different prompt engineering techniques are implemented and evaluated across various tasks. The methodologies include:

* Zero-Shot Learning: Evaluating model responses without prior examples.

* Few-Shot Learning: Providing a limited number of examples to guide model responses.

* Chain of Thought (CoT): Step-by-step reasoning to improve interpretability and accuracy.

* Meta Self-Evaluation: Assessing generated outputs to refine AI decision-making.

* Self-Consistency: Generating multiple answers and selecting the most consistent result.

* Experimenting with Temperature Parameter in Ollama Model:

Different temperature values were tested to analyze their impact on response variability and accuracy.

Lower temperatures produced more deterministic outputs, while higher temperatures increased diversity but sometimes reduced precision.

We analyze the outputs from each method to determine their effectiveness in handling different reasoning tasks.

<!-- WHEN APPLICABLE AND AVAILABLE -->

# Results
1. Zero-Shot Learning - Level 0 Automation:

* Effective for tasks with well-defined patterns but struggled with ambiguous or complex reasoning.

* Lower accuracy compared to few-shot and CoT approaches.

2. Few-Shot Learning - Level 0 Automation:

* Demonstrated significant improvements in response quality when provided with a few examples.

* Reduced hallucinations compared to zero-shot learning.

3.  Chain of Thought (CoT) - Level 2 Automation:

* Improved answer accuracy by breaking down complex problems into logical steps.

* This method breaked down its thought process into clear, logical steps rather than providing an opaque or unstructured answer.

4. Meta Self-Evaluation - Level 2 Automation:

* Helped refine responses by enabling models to critique their own outputs.

* Enhanced decision-making in uncertain scenarios.

* However, it failed to generate a specific requirement analysis for the use case, instead producing a generalized requirement analysis.

5. Self-Consistency - Level 2 Automation:

* Increased reliability by selecting the most frequent response from multiple generated answers.

* This method improves the accuracy of generating a response compared to generating a single response without additional validation.

6. Temperature Parameter Experimentation - Level 1 Automation:

* Lower temperatures resulted in more structured and deterministic responses.

* Higher temperatures led to more diverse answers but sometimes introduced inconsistencies.

* The model at lower temperatures (0.3) provided detailed requirement analysis relevant to the use case, whereas at higher temperatures (0.7), it generated more abstract and generalized results.

* Finding an optimal balance is crucial for requirement analysis tasks.

7. Level of Automation Analysis:

* Level 2 Automation: Chain of Thought and Self-Consistency provided the highest level of automation by reducing human intervention in requirement analysis.

* Level 0 Automation: Zero-Shot Learning and Few-Shot Learning exhibited the lowest automation level due to their dependency on pre-defined patterns and lack of contextual adaptation.

* The overall trend indicated that the combination of Chain of Thought and Self-Consistency achieved the most effective automated requirement analysis with minimal manual refinement.

# Conclusion
From our analysis of various Prompt Engineering techniques for Requirement Analysis in SDLC, it is evident that automation plays a crucial role in improving accuracy and efficiency. Among the methods tested:

* Self-Consistency - Level 2 provided reliable results by selecting the most frequent and consistent outputs, ensuring stability in AI-generated requirements.

* Chain of Thought (CoT) - Level 2 emerged as a strong approach for structured reasoning, improving interpretability and accuracy.

* Meta Self-Evaluation - Level 2 refined responses but struggled to produce specific, use-case-driven requirement analyses.

* Few-Shot Learning - Level 0 demonstrated significant improvements in response quality when guided with examples.

* Zero-Shot Learning - Level 0 was effective for well-defined tasks but lacked precision for complex requirements.

* Temperature Parameter Adjustments - Level 1 showed that lower temperatures (0.3) generated structured, case-specific requirement analyses, whereas higher temperatures (0.7) resulted in more generalized responses.

* Automation Analysis showed that Chain of Thought, and Self-Consistency provided the highest level of automation while maintaining accuracy and relevance.

Based on these findings, a combination of Chain of Thought, and Self-Consistency provides the most effective automated requirement analysis in SDLC. These techniques collectively balance structure, adaptability, and reliability, making them suitable for automating the requirement analysis process while maintaining accuracy and relevance. Future research should focus on hybrid models that integrate these techniques dynamically based on task complexity.

# Further research

* Investigate hybrid approaches that combine multiple reasoning techniques, such as Meta Self-Evaluation and Chain of Thought, to optimize accuracy and specificity in requirement analysis.

* Explore the scalability of these techniques in real-world applications.

* Develop automated mechanisms to determine when to use CoT, Few-Shot, or Self-Consistency based on task complexity.

* Further refine temperature parameter tuning for enhanced model response consistency.

This research provides insights into the strengths and weaknesses of different AI reasoning techniques, paving the way for more reliable and interpretable AI systems.