# Prompt Engineering Portfolio
Name: Rachit Jain
Date: 05 June 2026
LLM Used: ChatGPT (GPT-5.5)

## Part 1: Prompt Design & Iteration

### 1.1 Scenario A: Technical Explanation
**Goal:** Explain the concept of Neural Networks to a 10-year-old child.

#### Initial Prompt (V1)

Explain neural networks.

#### Output (V1)

Neural networks are computing systems inspired by the human brain. They consist of layers of interconnected nodes that process information and learn patterns from data. Neural networks are widely used in machine learning applications such as image recognition and natural language processing.

#### Refined Prompt (V2)

Explain neural networks to a 10-year-old child using simple language and an everyday example.

#### Output (V2)

A neural network is like a team of helpers working together to solve a puzzle. Each helper looks at a small piece of information and passes it along. Over time, the team gets better at recognizing patterns, like identifying whether a picture contains a cat or a dog.

#### Final Prompt (V3)

You are an expert elementary school teacher. Explain neural networks to a 10-year-old child using simple language, a fun real-life analogy, and a short example. Avoid technical jargon and keep the explanation under 150 words.

#### Final Output

Imagine a neural network as a group of friends trying to recognize different animals. Each friend notices one thing, such as ears, tails, or colors. They share their observations with the next friend, who combines the information and makes a guess. If the group makes a mistake, they learn from it and do better next time.

Just like children get better at identifying animals after seeing many examples, neural networks improve by practicing with lots of data. This helps computers recognize pictures, understand speech, and even recommend videos you might enjoy.

---

### 1.1 Scenario B: Professional Email
**Goal:** Draft an email declining a job offer politely while expressing continued interest in the company.

#### Initial Prompt (V1)

Write an email declining a job offer.

#### Output (V1)

Dear Hiring Manager,

Thank you for the job offer. I appreciate the opportunity. Unfortunately, I have decided not to accept the offer at this time.

Best regards,
Rachit Jain

#### Refined Prompt (V2)

Write a professional email declining a job offer while remaining polite and thanking the company for the opportunity.

#### Output (V2)

Dear Hiring Manager,

Thank you very much for offering me the position. I appreciate the time and effort invested throughout the interview process.

After careful consideration, I have decided to decline the offer. This was not an easy decision, and I am grateful for the opportunity.

Sincerely,
Rachit Jain

#### Final Prompt (V3)

You are an experienced HR communication specialist. Draft a professional and respectful email declining a job offer due to personal career considerations. Express sincere gratitude, maintain a positive relationship, and mention continued interest in future opportunities with the company.

#### Final Output

Subject: Thank You for the Opportunity

Dear Hiring Manager,

Thank you very much for offering me the position at your company. I truly appreciate the time, effort, and consideration extended to me throughout the recruitment process.

After careful thought, I have decided to decline the offer due to personal career considerations. This decision was not easy, as I have great respect for your organization and the team I had the opportunity to meet.

I remain genuinely interested in your company's work and would welcome the possibility of exploring future opportunities should our paths cross again.

Thank you once again for your understanding, and I wish the company continued success.

Kind regards,
Rachit Jain

---

### 1.1 Scenario C: Creative Content
**Goal:** Generate a creative marketing tagline for a new eco-friendly water bottle brand.

#### Initial Prompt (V1)

Create a tagline for an eco-friendly water bottle.

#### Output (V1)

Stay hydrated. Save the planet.

#### Refined Prompt (V2)

Create five creative taglines for an eco-friendly water bottle brand that promotes sustainability.

#### Output (V2)

1. Sip Smart, Live Green.
2. Refresh Naturally.
3. Drink Better, Waste Less.
4. Every Sip Counts.
5. Hydrate Sustainably.

#### Final Prompt (V3)

You are a professional advertising copywriter. Create ten memorable and modern taglines for a premium eco-friendly water bottle brand targeting environmentally conscious young professionals. The taglines should be short, catchy, and emotionally engaging.

#### Final Output

1. Every Sip Shapes Tomorrow.
2. Carry Water. Carry Change.
3. Hydration with a Purpose.
4. Drink Clean. Live Green.
5. Refill the Bottle, Renew the Planet.
6. Sustainable by Nature.
7. Smart Hydration Starts Here.
8. One Bottle. Endless Impact.
9. Refresh Yourself, Respect the Earth.
10. Better Choices in Every Sip.

### 1.2 Iteration Documentation

#### Scenario A: Technical Explanation

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Explain neural networks. | N/A | N/A |
| V2 | Explain neural networks to a 10-year-old child using simple language and an everyday example. | Added audience and simplicity requirement. | Made the explanation easier to understand. |
| V3 | You are an expert elementary school teacher. Explain neural networks to a 10-year-old child using simple language, a fun real-life analogy, and a short example. Avoid technical jargon and keep the explanation under 150 words. | Added role, analogy, constraints, and context. | Produced a more engaging and age-appropriate explanation. |

#### Scenario B: Professional Email

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Write an email declining a job offer. | N/A | N/A |
| V2 | Write a professional email declining a job offer while remaining polite and thanking the company for the opportunity. | Added professionalism and gratitude requirements. | Improved tone and professionalism. |
| V3 | You are an experienced HR communication specialist. Draft a professional and respectful email declining a job offer due to personal career considerations. Express sincere gratitude, maintain a positive relationship, and mention continued interest in future opportunities with the company. | Added role assignment and detailed context. | Generated a more polished and relationship-focused email. |

#### Scenario C: Creative Content

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Create a tagline for an eco-friendly water bottle. | N/A | N/A |
| V2 | Create five creative taglines for an eco-friendly water bottle brand that promotes sustainability. | Requested multiple options and added brand focus. | Increased creativity and variety. |
| V3 | You are a professional advertising copywriter. Create ten memorable and modern taglines for a premium eco-friendly water bottle brand targeting environmentally conscious young professionals. The taglines should be short, catchy, and emotionally engaging. | Added role assignment, audience, and style requirements. | Produced stronger, more targeted marketing content. |

### 1.3 Role and Context Analysis

Role assignment significantly improved the quality of the generated outputs. By instructing the model to act as an expert elementary school teacher and an experienced HR communication specialist, the responses became more tailored to the intended audience and purpose. Context setting provided important background information, such as the target age group, communication goals, and audience demographics. Together, role assignment and context setting made the outputs more relevant, focused, and effective compared to the generic responses produced by the initial prompts.


## Part 2: Temperature & Parameter Control

### 2.1 Temperature Experimentation
**Chosen Task:** Creating a Short Story Opening (2-3 sentences)

#### Base Prompt

Write the opening of a short story about a mysterious door that appears in a small town.

---

### Low Temperature (0.2)

**Prompt Used**

Write the opening of a short story about a mysterious door that appears in a small town. Be precise and consistent.

**Output**

One morning, the residents of a small town discovered a wooden door standing alone in the center of the town square. No one knew where it had come from or who had placed it there. As people gathered around it, questions began to spread throughout the town.

---

### Medium Temperature (0.7)

**Prompt Used**

Write the opening of a short story about a mysterious door that appears in a small town.

**Output**

The door appeared overnight, standing silently beside the old fountain in the center of town. It was painted deep blue and covered with strange symbols that no one could recognize. By sunrise, curious residents had already formed a crowd around it, whispering theories about its origin.

---

### High Temperature (1.3)

**Prompt Used**

Write the opening of a short story about a mysterious door that appears in a small town. Be creative and explore diverse ideas.

**Output**

At exactly 3:13 a.m., a shimmering violet door emerged from a swirl of golden leaves in the middle of Maple Street. The door hummed softly, as if singing a forgotten song from another world, and every clock in town stopped the moment it appeared. By dawn, the townspeople stood frozen between fear and wonder, unable to decide whether to open it or run away.

---

### Comparison Table

| Temperature  | Characteristics                 | Creativity Level | Predictability | Style                    |
| ------------ | ------------------------------- | ---------------- | -------------- | ------------------------ |
| Low (0.2)    | Straightforward and factual     | Low              | Very High      | Clear and direct         |
| Medium (0.7) | Balanced detail and imagination | Medium           | Moderate       | Descriptive and engaging |
| High (1.3)   | Highly imaginative and unique   | High             | Lower          | Creative and dramatic    |

### Key Differences Observed

* The low-temperature response focused on clarity and simple storytelling.
* The medium-temperature response added descriptive details while remaining coherent.
* The high-temperature response introduced unusual imagery, fantasy elements, and dramatic language.
* Creativity increased as temperature increased, while predictability decreased.
* All outputs followed the same prompt but produced noticeably different styles.

---

### 2.2 Analysis & Recommendations

Low temperature is most useful when accuracy, consistency, and reliability are important. Two examples are generating technical documentation and answering factual customer support questions. In these situations, predictable and precise responses are preferred over creativity.

High temperature is most useful when generating creative content and brainstorming new ideas. Two examples are writing fictional stories and creating marketing campaign concepts. In these cases, originality and diversity are more valuable than consistency.

For this experiment, the medium temperature worked best. It provided a good balance between creativity and coherence, making the story interesting while still remaining clear and easy to follow. The output was imaginative without becoming overly random or difficult to understand.


## Part 3: Strategic Prompting Techniques

### 3.1 Chain-of-Thought Prompting

**Selected Problem:** Option B – Multi-Step Reasoning

**Problem:**

A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?

#### Without Chain-of-Thought

**Prompt**

Calculate the answer to the following problem and provide only the final answer:

A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?

**LLM Output**

172 employees

---

#### With Chain-of-Thought

**Prompt**

Let's solve this step by step.

A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?

Show all calculations and reasoning.

**LLM Output**

Step 1: Calculate current employees in each department.

Engineering = 60% of 150 = 90 employees

Sales = 25% of 150 = 37.5 employees

Operations = 150 − 90 − 37.5 = 22.5 employees

Step 2: Calculate new hires.

Additional engineers = 20% of 90 = 18 employees

Additional sales employees = 10% of 37.5 = 3.75 employees

Total new hires = 18 + 3.75 = 21.75 employees

Step 3: Calculate total employees after hiring.

150 + 21.75 = 171.75

Rounded to the nearest whole employee = 172 employees

Final Answer: 172 employees

---

#### Comparison

The output without chain-of-thought provided only the final answer and did not explain how the result was obtained. The chain-of-thought prompt produced a detailed breakdown of each calculation and showed the reasoning process clearly. This makes it easier to verify the answer and identify potential mistakes. One limitation is that chain-of-thought responses are longer and may include unnecessary details for simple problems.

---

### 3.2 Few-Shot Prompting

#### Step 1: Zero-Shot Attempt

**Prompt**

Classify the sentiment of each customer review as Positive, Negative, or Neutral.

**Results**

| Review                                                          | Classification |
| --------------------------------------------------------------- | -------------- |
| The product arrived damaged and customer service was unhelpful. | Negative       |
| Works as expected, nothing special but does the job.            | Neutral        |
| Absolutely love this! Best purchase I've made all year!         | Positive       |
| The quality is okay but slightly overpriced for what you get.   | Neutral        |
| Terrible experience, would not recommend to anyone.             | Negative       |

---

#### Step 2: Few-Shot Attempt

**Prompt**

Classify customer reviews as Positive, Negative, or Neutral.

Example 1:

Review: "This product exceeded my expectations!"

Sentiment: Positive

Example 2:

Review: "Completely broke after one week of use."

Sentiment: Negative

Example 3:

Review: "It's fine, does what it says on the box."

Sentiment: Neutral

Example 4:

Review: "Excellent quality and fast delivery."

Sentiment: Positive

Example 5:

Review: "The product arrived late and was damaged."

Sentiment: Negative

Now classify the following reviews.

**Results**

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

The few-shot prompt provided examples that helped clarify how sentiment categories should be interpreted. Few-shot prompting is particularly useful when tasks require a specific format, labeling style, or decision criteria. It can improve consistency and accuracy, especially for more complex classification tasks where instructions alone may be ambiguous.

