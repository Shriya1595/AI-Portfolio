# Portfolio Project 2

# Model Reliability Evaluation: Comparing Two Large Language Models

---

## Status

**In Progress**

---

## Date

(DD Month YYYY)

---

## Estimated Time

(Example: 3 hours)

---

## Skills Demonstrated

- LLM Evaluation
- Prompt Design
- Critical Analysis
- Model Comparison
- Technical Writing

---

# Objective

Evaluate and compare the reliability of two Large Language Models using the same prompts. The comparison focuses on instruction following, factual accuracy, premise correction, and citation reliability.

---

# Research Question

Which language model demonstrates greater reliability when responding to controlled prompts?

---

# Hypothesis:

I expect both models to perform similarly on straightforward explanatory tasks but differ when responding to misleading premises and requests that may encourage fabricated information.

---

# Models Compared

| Model | Version |
|--------|---------|
| Model A | |GPT_5.5
| Model B | |Gemini

---

# Methodology

- Both models receive the exact same prompts.
- Responses are evaluated using the same rubric.
- Scores are assigned based on predefined evaluation criteria.
- Conclusions are supported with evidence from the responses.

---

# Evaluation Rubric

| Criterion | Description |
|-----------|-------------|
| Instruction Following | Did the model follow all instructions? |
| Accuracy | Is the information factually correct? |
| Completeness | Were all important points covered? |
| Clarity | Is the explanation easy to understand? |
| Organization | Is the response logically structured? |
| Audience Fit | Is the explanation suitable for the intended audience? |
| Tone | Did the model maintain the requested tone? |
| Conciseness | Was unnecessary information avoided? |
| Premise Correction | Did the model identify and correct false assumptions? |
| Hallucination Resistance | Did the model avoid inventing unsupported facts or citations? |

---

# Test Case 1 – Baseline Explanation

## Capability Tested

- Instruction Following
- Accuracy
- Clarity
- Organization
- Audience Adaptation

### Prompt

Explain how antibiotics work to an adult with no science background. Keep your explanation between 200 and 300 words. Use a friendly, conversational tone. Include one everyday example to illustrate how antibiotics help treat bacterial infections. Organize your response into short paragraphs for readability. Base your explanation only on established scientific knowledge and avoid unsupported claims or speculation.

---

## Response – GPT-5.5

Antibiotics are medicines that treat **bacterial infections**. They work by targeting features that bacteria need to survive or reproduce. Some antibiotics damage the bacteria's protective outer wall, causing the bacteria to break apart. Others stop bacteria from making essential proteins or copying their genetic material, which prevents them from growing. Your immune system can then more easily remove the remaining bacteria from your body.

It's important to know that antibiotics **do not work against viruses**. Illnesses such as the common cold, most sore throats, the flu, and COVID-19 are caused by viruses, so antibiotics will not help treat them. Taking antibiotics when they are not needed can also encourage bacteria to develop antibiotic resistance, making future bacterial infections harder to treat.

Think of it like pulling weeds from a garden. If harmful bacteria are the weeds, antibiotics are the tools designed to remove or stop those weeds from spreading, giving the healthy plants a chance to thrive. In the same way, antibiotics reduce the number of harmful bacteria so your body's natural defenses can finish clearing the infection.

Because different bacteria respond to different antibiotics, doctors choose a medicine based on the type of infection and other factors, such as your medical history. For the treatment to work as intended, it's important to take antibiotics exactly as prescribed, even if you start feeling better before the course is finished, unless your healthcare provider advises otherwise.


---

## Response – Gemini

Think of your body as a high-security home, and a bacterial infection as a group of unwanted intruders breaking in and causing trouble. Antibiotics are like a specialized home defense system sent in specifically to stop those intruders.

Bacteria are single-celled living organisms. To survive and multiply, they need to build their own protective walls, create their own proteins, and copy their own DNA. Antibiotics work by disrupting these vital processes.

Different types of antibiotics target these weaknesses in different ways. Some act like demolition crew members that punch holes in the bacteria's outer cell walls, causing them to burst. Others act like tiny wrenches thrown into the bacteria’s internal machinery, stopping them from making the essential proteins they need to grow. By either killing the bacteria directly or stopping them from multiplying, antibiotics give your body's natural immune system the upper hand to clear out the remaining infection.

Imagine you're trying to build a house, but someone keeps stealing your bricks or jamming your power tools. You wouldn't be able to finish the build, and the structure would quickly fall apart. That is essentially what antibiotics do to bacteria—they destroy their building materials or freeze their tools so the bacteria can no longer survive inside you.

It's important to remember that antibiotics only target bacteria. Viruses, like the common cold or the flu, operate completely differently and don't have cell walls or the same machinery. That’s why antibiotics won't work against viral bugs, but against bacterial invaders, they are one of medicine's most effective tools.

---

## Evaluation

| Criterion | Model A | Model B | Comments |
|-----------|---------|---------|----------|
| Instruction Following | | | |
| Accuracy | | | |
| Completeness | | | |
| Clarity | | | |
| Organization | | | |
| Audience Fit | | | |
| Tone | | | |
| Conciseness | | | |
| Overall | | | |

---

# Test Case 2 – False Premise Correction

## Capability Tested

- Premise Correction
- Factual Reliability
- User Guidance

### Prompt

(Paste Prompt)

---

## Response – Model A

(Paste response)

---

## Response – Model B

(Paste response)

---

## Evaluation

| Criterion | Model A | Model B | Comments |
|-----------|---------|---------|----------|
| Premise Correction | | | |
| Accuracy | | | |
| Clarity | | | |
| Tone | | | |
| Overall | | | |

---

# Test Case 3 – Citation Reliability

## Capability Tested

- Hallucination Resistance
- Citation Reliability
- Transparency

### Prompt

(Paste Prompt)

---

## Response – Model A

(Paste response)

---

## Response – Model B

(Paste response)

---

## Evaluation

| Criterion | Model A | Model B | Comments |
|-----------|---------|---------|----------|
| Citation Reliability | | | |
| Accuracy | | | |
| Transparency | | | |
| Hallucination Resistance | | | |
| Overall | | | |

---

# Overall Results

| Capability | Model A | Model B | Better Model |
|------------|---------|---------|--------------|
| Instruction Following | | | |
| Accuracy | | | |
| Clarity | | | |
| Organization | | | |
| Audience Fit | | | |
| Premise Correction | | | |
| Hallucination Resistance | | | |
| Overall Reliability | | | |

---

# Discussion

Discuss patterns observed across all three test cases.

Suggested questions:

- Which model followed instructions more consistently?
- Which model handled misleading information better?
- Did either model fabricate information or citations?
- Were there recurring strengths or weaknesses?

---

# Recommendation

If you were selecting one model for deployment in a general-purpose educational assistant, which would you recommend? Support your recommendation with evidence from the evaluation.

---

# Limitations

- Only two models were evaluated.
- The study used three prompts.
- Human scoring introduces subjectivity.
- Different domains may produce different outcomes.

---

# Conclusion

Answer the research question.

Did the evidence support your hypothesis?

Why or why not?

---

# Reflection

- What surprised me during this evaluation?
- Which capability was the hardest to assess?
- Which model behavior was most interesting?
- How could this evaluation be improved?
- What should be investigated next?
