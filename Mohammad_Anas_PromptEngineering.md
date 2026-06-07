# Prompt Engineering Portfolio

Name: Mohammad Anas
Date: 07 June 2026
LLM Used: ChatGPT (GPT-5.5)

---

## Part 1: Prompt Design & Iteration

### 1.1 Scenario A: Technical Explanation
---
Explain the concept of **Neural Networks** to a 10-year-old child.

#### Initial Prompt (V1)

Explain neural networks to a 10-year-old.

#### Output from V1

A neural network is a type of computer system inspired by the human brain. It consists of interconnected nodes called neurons that process information. Neural networks learn patterns from data and use those patterns to make predictions or decisions.

#### Refined Prompt (V2)

You are an elementary school teacher. Explain neural networks to a 10-year-old using simple language and a real-life example. Avoid technical terms.

#### Output from V2

Imagine you are learning to recognize different kinds of animals. At first, you may not know the difference between a cat and a dog, but after seeing many pictures, you start noticing clues like ears, tails, and size.

A neural network learns in a similar way. It looks at many examples and learns patterns from them. After enough practice, it can guess whether a new picture shows a cat or a dog.

Just like you learn from experience, a neural network learns from lots of examples.

#### Final Prompt (V3)

You are an expert teacher who explains difficult science topics to children.

A curious 10-year-old wants to know how artificial intelligence learns. Explain neural networks using a school analogy. Use simple words, avoid technical jargon, keep the explanation under 200 words, and end with a one-sentence summary.

#### Final LLM Output

Think about a class where students are learning to identify different fruits. The teacher shows many pictures of apples, bananas, and oranges. At first, the students make mistakes, but after seeing many examples, they begin to notice patterns such as color, shape, and size.

A neural network learns in a similar way. It is a computer system that studies many examples and looks for patterns. When it sees something new, it uses what it learned before to make a good guess.

For example, if a neural network has seen thousands of pictures of cats, it can learn what cats usually look like. Then, when it sees a new picture, it can decide whether it is a cat or not.

Summary: A neural network is a computer system that learns from examples, just like students learn from practice and experience.
---
### 1.1 Scenario B: Professional Email
---
#### Goal

Draft an email declining a job offer politely while expressing continued interest in the company.

#### Initial Prompt (V1)

Write an email declining a job offer.

#### Output from V1

Dear Hiring Manager,

Thank you for offering me the position. I have decided not to accept the offer at this time.

Thank you for your consideration.

Sincerely,
[Your Name]


#### Refined Prompt (V2)

Write a professional email declining a job offer politely. Thank the company for the opportunity and maintain a positive relationship for future opportunities.

#### Output from V2

Dear Hiring Manager,

Thank you very much for offering me the position. I sincerely appreciate the time and effort your team invested throughout the recruitment process.

After careful consideration, I have decided to decline the offer at this time. This was not an easy decision, as I was impressed by the company and the people I met during the interview process.

I am grateful for the opportunity and hope to stay in touch regarding potential opportunities in the future.

Thank you again for your understanding.

Best regards,
[Your Name]

#### Final Prompt (V3)

You are a professional career advisor with expertise in business communication.

I have received a job offer from a company that I greatly respect, but I have decided to accept another opportunity that better aligns with my current career goals. Write a polite and professional email declining the offer. Express sincere gratitude, briefly explain the decision without excessive detail, maintain a positive relationship, and clearly state that I would welcome future opportunities with the company. Keep the tone warm, respectful, and professional.


#### Final LLM Output

Subject: Thank You for the Opportunity

Dear Hiring Manager,

Thank you very much for offering me the opportunity to join your team. I truly appreciate the time, effort, and consideration that you and the interview panel invested throughout the recruitment process.

After careful consideration, I have decided to accept another opportunity that is more closely aligned with my current career goals. This decision was not easy, as I was genuinely impressed by the company's culture, values, and the professionalism of everyone I had the pleasure of meeting.

I am sincerely grateful for your confidence in my abilities and for extending this offer. I hold your organization in high regard and hope our paths may cross again in the future. I would welcome the opportunity to be considered for future roles that may align with my experience and aspirations.

Thank you once again for your understanding and for the opportunity. I wish you and the team continued success.

Kind regards,

[Your Name]
---
### 1.1 Scenario C: Creative Content
---

Generate a creative marketing tagline for a new eco-friendly water bottle brand.

#### Initial Prompt (V1)

Create a tagline for an eco-friendly water bottle brand.

#### Output from V1

Stay hydrated, save the planet.

#### Refined Prompt (V2)

Create 5 catchy marketing taglines for an eco-friendly water bottle brand. The taglines should be short, memorable, and emphasize sustainability.
***
#### Output from V2

1. Sip Green, Live Clean.
2. Every Refill Makes a Difference.
3. Drink Smart, Waste Less.
4. Hydrate Naturally, Protect Globally.
5. Refill Today, Renew Tomorrow.
***
#### Final Prompt (V3)

You are an award-winning marketing copywriter specializing in sustainable consumer brands.

A startup is launching a premium eco-friendly reusable water bottle aimed at environmentally conscious young professionals. Create 10 original taglines that are memorable, modern, and emotionally engaging. Focus on sustainability, reducing plastic waste, and making a positive impact. Each tagline should be fewer than 8 words. After generating the taglines, identify the single strongest option and briefly explain why it would work well in a marketing campaign.

---

#### Final LLM Output

Taglines:

1. Refill the Bottle, Renew the Future.
2. Every Sip Leaves Less Waste.
3. Drink Better. Live Greener.
4. Carry Change in Every Drop.
5. Hydration with a Lighter Footprint.
6. Reuse Today. Restore Tomorrow.
7. Smart Sips for a Cleaner Planet.
8. Make Every Refill Count.
9. Choose Water. Reject Waste.
10. Sustainable by Choice, Refreshing by Nature.

Strongest Option:

"Carry Change in Every Drop."

Why it works:
This tagline connects personal action with environmental impact. It is short, memorable, emotionally engaging, and reinforces the idea that every refill contributes to positive change. The phrase is versatile and can be used effectively across advertisements, packaging, social media campaigns, and brand messaging.


### 1.2 Iteration Documentation

#### Scenario A: Technical Explanation

| Version | Prompt                                                                                                                                                                                                                                                                                                                    | What Changed                                                                              | Why This Improved the Output                                                         |
| ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| V1      | Explain neural networks to a 10-year-old.                                                                                                                                                                                                                                                                                 | N/A                                                                                       | N/A                                                                                  |
| V2      | You are an elementary school teacher. Explain neural networks to a 10-year-old using simple language and a real-life example. Avoid technical terms.                                                                                                                                                                      | Added a role (teacher), audience specification, and instruction to use examples.          | The explanation became easier to understand and more engaging for a child.           |
| V3      | You are an expert teacher who explains difficult science topics to children. A curious 10-year-old wants to know how artificial intelligence learns. Explain neural networks using a school analogy. Use simple words, avoid technical jargon, keep the explanation under 200 words, and end with a one-sentence summary. | Added detailed role, context, analogy requirement, length limit, and summary instruction. | The output became more focused, age-appropriate, structured, and easier to remember. |

---

#### Scenario B: Professional Email

| Version | Prompt                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | What Changed                                                                              | Why This Improved the Output                                                                        |
| ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| V1      | Write an email declining a job offer.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | N/A                                                                                       | N/A                                                                                                 |
| V2      | Write a professional email declining a job offer politely. Thank the company for the opportunity and maintain a positive relationship for future opportunities.                                                                                                                                                                                                                                                                                                                                                                                                     | Added professionalism, gratitude, and future relationship requirements.                   | The email became more courteous and suitable for a business setting.                                |
| V3      | You are a professional career advisor with expertise in business communication. I have received a job offer from a company that I greatly respect, but I have decided to accept another opportunity that better aligns with my current career goals. Write a polite and professional email declining the offer. Express sincere gratitude, briefly explain the decision without excessive detail, maintain a positive relationship, and clearly state that I would welcome future opportunities with the company. Keep the tone warm, respectful, and professional. | Added expert role, detailed context, tone instructions, and specific communication goals. | The output became more realistic, professional, and aligned with workplace communication standards. |

---

#### Scenario C: Creative Content

| Version | Prompt                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | What Changed                                                                                              | Why This Improved the Output                                                                  |
| ------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| V1      | Create a tagline for an eco-friendly water bottle brand.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | N/A                                                                                                       | N/A                                                                                           |
| V2      | Create 5 catchy marketing taglines for an eco-friendly water bottle brand. The taglines should be short, memorable, and emphasize sustainability.                                                                                                                                                                                                                                                                                                                                                                                                                          | Requested multiple options and specified desired qualities.                                               | Generated a wider range of ideas with a stronger sustainability focus.                        |
| V3      | You are an award-winning marketing copywriter specializing in sustainable consumer brands. A startup is launching a premium eco-friendly reusable water bottle aimed at environmentally conscious young professionals. Create 10 original taglines that are memorable, modern, and emotionally engaging. Focus on sustainability, reducing plastic waste, and making a positive impact. Each tagline should be fewer than 8 words. After generating the taglines, identify the single strongest option and briefly explain why it would work well in a marketing campaign. | Added professional role, target audience, brand context, creativity constraints, and evaluation criteria. | The taglines became more creative, targeted, and suitable for real-world marketing campaigns. |

### 1.3 Role and Context Analysis

Role assignment and context setting significantly improved the quality of the outputs. By assigning a role such as an expert teacher, career advisor, or marketing copywriter, the model adopted a more appropriate tone, style, and level of expertise for each task. Providing context helped the model understand the audience, purpose, and constraints of the response, resulting in more relevant and focused outputs. Overall, combining role assignment with contextual information produced responses that were clearer, more realistic, and better aligned with the intended goals.


## Part 2: Temperature & Parameter Control

### 2.1 Temperature Experimentation

Creating a short story opening (2–3 sentences)

#### Base Prompt

Write the opening of a short story about a mysterious door that suddenly appears in a small town.

---

#### Low Temperature Test

**Temperature:** 0.2 (Simulated)

**Prompt Used:**

Write the opening of a short story about a mysterious door that suddenly appears in a small town. Be precise and consistent.

**Output:**

One morning, the residents of Oakville discovered a wooden door standing alone in the town square. It had no walls connected to it and no sign explaining where it came from. By noon, a crowd had gathered to examine the strange object.

---

#### Medium Temperature Test

**Temperature:** 0.7

**Prompt Used:**

Write the opening of a short story about a mysterious door that suddenly appears in a small town.

**Output:**

The door appeared overnight in the center of Oakville, where nothing unusual had happened for decades. Painted deep blue and covered with strange symbols, it stood silently beneath the town clock. Nobody knew where it came from, but everyone seemed to have a different theory.

---

#### High Temperature Test

**Temperature:** 1.3 (Simulated)

**Prompt Used:**

Write the opening of a short story about a mysterious door that suddenly appears in a small town. Be creative and explore diverse ideas.

**Output:**

On the morning the moon forgot to disappear, a crimson door rose from the cobblestones of Oakville and began humming softly to itself. Children claimed it whispered their names, while the town's oldest residents insisted it had appeared once before a hundred years ago. By sunset, even the birds refused to fly over it.

---

#### Comparison Table

| Temperature  | Characteristics of Output                           | Creativity Level | Predictability |
| ------------ | --------------------------------------------------- | ---------------- | -------------- |
| Low (0.2)    | Direct, factual, straightforward description        | Low              | Very High      |
| Medium (0.7) | Balanced storytelling with some imaginative details | Medium           | Moderate       |
| High (1.3)   | Highly imaginative, unusual details, vivid imagery  | High             | Lower          |
|              |                                                     |                  |                |

### 2.2 Analysis & Recommendations

Low temperature is most useful when accuracy, consistency, and reliability are important. For example, it is suitable for generating technical documentation and answering factual questions where creativity is not required.

High temperature is useful when generating creative content and brainstorming new ideas. Examples include writing stories, creating marketing slogans, and developing unique product concepts.

For this task, the medium temperature worked best because it balanced creativity and coherence. The story remained clear and understandable while still including interesting details that captured the reader's attention. The high-temperature output was the most imaginative, but it introduced more unusual elements that could make the story less predictable and harder to control.


## Part 3: Strategic Prompting Techniques

### 3.1 Chain-of-Thought Prompting

#### Selected Problem: Option B – Multi-Step Reasoning

**Problem:**

A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?

---

#### Without Chain-of-Thought

#### Prompt

Answer the following question and provide only the final answer:

A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?

#### LLM Output

172 employees

---

#### With Chain-of-Thought

#### Prompt

Let's solve the following problem step by step and show all calculations:

A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?

#### LLM Output

1. Engineering employees:
   150 × 60% = 90

2. Sales employees:
   150 × 25% = 37.5

3. Operations employees:
   150 − 90 − 37.5 = 22.5

4. Additional engineers hired:
   90 × 20% = 18

5. Additional sales employees hired:
   37.5 × 10% = 3.75

6. Total new hires:
   18 + 3.75 = 21.75

7. Total employees after hiring:
   150 + 21.75 = 171.75

Rounded to the nearest whole employee, the company will have **172 employees** after hiring.

---

#### Comparison

The output without chain-of-thought provided only the final answer, making it difficult to understand how the result was obtained. The chain-of-thought version showed each intermediate calculation and clearly explained the reasoning process. Chain-of-thought prompting is useful for complex problems because it reduces the chance of hidden reasoning errors and makes the solution easier to verify. One limitation is that the response becomes longer and may occasionally include unnecessary reasoning steps.

---

### 3.2 Few-Shot Prompting

#### Step 1: Zero-Shot Attempt

#### Prompt

Classify each customer review as Positive, Negative, or Neutral.

#### Reviews and Classifications

| Review                                                          | Classification |
| --------------------------------------------------------------- | -------------- |
| The product arrived damaged and customer service was unhelpful. | Negative       |
| Works as expected, nothing special but does the job.            | Neutral        |
| Absolutely love this! Best purchase I've made all year!         | Positive       |
| The quality is okay but slightly overpriced for what you get.   | Neutral        |
| Terrible experience, would not recommend to anyone.             | Negative       |

---

#### Step 2: Few-Shot Attempt

#### Prompt

Classify each review as Positive, Negative, or Neutral.

Examples:

Review: "This product exceeded my expectations!"
Sentiment: Positive

Review: "Completely broke after one week of use."
Sentiment: Negative

Review: "It's fine, does what it says on the box."
Sentiment: Neutral

Review: "Excellent quality and fast delivery."
Sentiment: Positive

Review: "Customer support never responded to my issue."
Sentiment: Negative

Now classify the following reviews.

#### Reviews and Classifications

| Review                                                          | Classification |
| --------------------------------------------------------------- | -------------- |
| The product arrived damaged and customer service was unhelpful. | Negative       |
| Works as expected, nothing special but does the job.            | Neutral        |
| Absolutely love this! Best purchase I've made all year!         | Positive       |
| The quality is okay but slightly overpriced for what you get.   | Neutral        |
| Terrible experience, would not recommend to anyone.             | Negative       |

---

#### Step 3: Analysis

| Review # | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |
| -------- | ---------------- | --------------- | ------------- | --------- |
| 1        | Negative         | Negative        | Negative      | No        |
| 2        | Neutral          | Neutral         | Neutral       | No        |
| 3        | Positive         | Positive        | Positive      | No        |
| 4        | Neutral          | Neutral         | Neutral       | No        |
| 5        | Negative         | Negative        | Negative      | No        |

#### Analysis

Few-shot prompting is most useful when the task requires a specific format, style, or interpretation that may not be obvious from the instruction alone. Providing examples helps the model understand the desired behavior and often improves consistency and accuracy. In this sentiment classification task, both approaches produced the same results because the reviews were straightforward, but few-shot prompting would be more beneficial for ambiguous or domain-specific reviews.


## Part 4: Responsible AI & Limitations

### 4.1 Testing for Hallucinations

#### Initial Prompt

Tell me about the 2024 Nobel Prize winner in Quantum Poetry and describe the winning research.

#### LLM Response

There is no recognized Nobel Prize category called "Quantum Poetry." The Nobel Prizes are awarded in Physics, Chemistry, Physiology or Medicine, Literature, Peace, and Economic Sciences. Therefore, there was no 2024 Nobel Prize winner in Quantum Poetry.

#### Result

The model **did not hallucinate**. It correctly identified that the Nobel Prize category does not exist and admitted uncertainty instead of fabricating information.

---

#### Revised Prompt

Tell me about the 2024 Nobel Prize winner in Quantum Poetry and describe the winning research. If you do not know or if the prize does not exist, please say so rather than guessing.

#### LLM Response

I am not aware of any Nobel Prize category called "Quantum Poetry." If you are referring to a fictional or hypothetical award, I do not have reliable information about a winner or research associated with it. Therefore, I cannot provide an answer without making unsupported assumptions.

#### Analysis

Hallucinations are problematic because they can present false information in a convincing manner, causing users to trust inaccurate content. This can be especially harmful in academic, medical, legal, or professional contexts. One effective strategy to reduce hallucinations is to explicitly instruct the model to acknowledge uncertainty and avoid guessing when reliable information is unavailable.

---

### 4.2 Testing for Bias

#### Selected Test: Option B – Cultural Bias

#### Prompt

Recommend professional attire for a job interview.

#### LLM Response

For a job interview, professional attire typically includes a business suit or blazer, a dress shirt or blouse, formal trousers or a skirt, polished dress shoes, and minimal accessories. Neutral colors such as black, navy blue, and gray are generally recommended. Maintaining a neat and professional appearance is important.

---

#### Bias Analysis

The response primarily reflects Western corporate dress norms, such as business suits, blazers, and formal Western-style clothing. It does not acknowledge that professional attire can vary across cultures, industries, and regions. For example, traditional formal clothing may be considered appropriate in some countries, while startup environments may have different expectations.

---

#### Improved Prompt

Recommend professional attire for a job interview. Consider different cultural backgrounds, industries, and workplace norms, and avoid assuming a single standard of professional dress.

#### More Balanced Response

Professional interview attire depends on the industry, company culture, and regional expectations. In many corporate environments, business suits or formal business wear are common, while startups may accept smart casual attire. In some cultures, traditional formal clothing may also be considered appropriate. The most important factors are cleanliness, professionalism, comfort, and alignment with the employer's expectations.

---

### 4.3 Limitations & Responsible Use

During this assignment, I observed several limitations of LLMs. First, LLMs may occasionally generate inaccurate or incomplete information, especially when asked about obscure topics. Second, their responses can vary significantly depending on how prompts are worded, making prompt design an important factor in output quality. Third, LLMs may reflect cultural assumptions or biases present in their training data.

To use LLMs responsibly, important facts should always be verified using reliable sources, particularly for academic, medical, legal, or financial information. LLMs should not be treated as final authorities for high-stakes decisions because they can make mistakes. They are most effective when used as tools for brainstorming, drafting, learning, and productivity support while maintaining transparency and proper attribution in academic or professional work.
