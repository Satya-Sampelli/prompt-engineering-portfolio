Prompt Engineering Portfolio
Name: Sampelli Satya Rao
Date: May 29, 2026
LLM Used: Gemini 1.5 Pro (Google)

Part 1: Prompt Design & Iteration

1.1 Scenario A: Technical Explanation
Goal: Explain the concept of "Recursion" to a 10-year-old.

 Initial Prompt (V1) :
Explain recursion to a 10-year-old.

LLM Output (V1) :
Recursion is a programming concept where a function calls itself. It is like a function that keeps running over and over until a base case is met, stopping an infinite loop. It uses a stack frame structure to keep track of previous iterations.

Refined Prompt (V2) :
You are an encouraging primary school science teacher. Explain the programming concept of "recursion" to a 10-year-old using a vivid real-world analogy. Avoid technical jargon like "functions", "stack frames", or "loops".

LLM Output (V2) :
Imagine you are standing in front of a mirror holding a smaller mirror. When you look into it, you see an image of yourself holding a mirror, inside an image of yourself holding a mirror, repeating down a long tunnel! In computer coding, recursion is just a rule that repeats inside itself like those mirrors. But you need a rule to stop looking, or you'll get dizzy forever!

Final Prompt (V3) :
You are an encouraging primary school science teacher. Explain the programming concept of "recursion" to a 10-year-old using a real-world analogy of a box filled with smaller boxes. Clearly explain what the "stopping rule" means so they understand how it finishes. Keep it under 4 sentences.

Final LLM Output (V3) :
Imagine finding a large treasure box, but when you open it, there is just a smaller box inside. You keep opening each new box to find another one inside it—this repeating process is what we call recursion! To make sure you don't keep opening boxes forever, you need a final "stopping rule," which is finding the actual toy prize in the very last box. Once you find the prize, you are completely done!



1.1 Scenario B: Professional Email
Goal: Draft an email declining a job offer politely while expressing continued interest in the company.

Initial Prompt (V1) :
Write an email turning down a job offer but say I still like the company.

LLM Output (V1) :
Subject: Job Offer
 
Dear Hiring Manager,
Thanks for the job offer. Unfortunately, I cannot accept it at this time because I have another option. I still like your company and hope we can stay in touch later. 
 
Best,
Satya

Refined Prompt (V2) :
You are a polished professional business writer. Draft an email to a HR recruiter declining a Graduate Engineer Trainee job offer. Make it polite, state that I have accepted another opportunity that closely aligns with my immediate specialization, and express a sincere desire to keep communication lines open for future career paths.

LLM Output (V2) :
Subject: Career Update - Graduate Engineer Trainee Offer - Sampelli Satya Rao

Dear Recruiting Team,

Thank you so much for offering me the Graduate Engineer Trainee position. I am incredibly grateful for the opportunity and enjoyed meeting your team. However, I have accepted another offer that closely aligns with my immediate technical specialization. I have immense respect for your company and hope our paths cross again in the future.
 
Sincerely,  
Sampelli Satya Rao

Final Prompt (V3) :
You are a polished professional corporate communications expert. Draft an email declining a Graduate Engineer Trainee job offer. Maintain a warm, highly professional tone. State that after careful thought, you accepted an alternative role aligning with your immediate data analytics goals. Express genuine admiration for their innovation and explicitly suggest that i want to connect on LinkedIn to maintain a professional relationship.

Final LLM Output (V3) :
Subject: Job Offer Update: Graduate Engineer Trainee - Sampelli Satya Rao

Dear Recruiting Team,

Thank you sincerely for offering me the Graduate Engineer Trainee position and for your confidence in my technical skills. After careful consideration, I have decided to accept an alternative offer that aligns closely with my immediate career goals in data analytics. 

I have deep admiration for your company’s market innovations and the collaborative culture displayed during my interviews. I would appreciate the opportunity to stay connected for future career paths, and I hope we can connect on LinkedIn to maintain our professional relationship. Thank you once again for your time, guidance, and consideration.

Warm regards,  
Sampelli Satya Rao



1.1 Scenario C: Creative Content
Goal: Generate a creative marketing tagline for a new eco-friendly water bottle brand.

Initial Prompt (V1) :
Give me a tagline for an eco friendly water bottle.

LLM Output (V1) :
Save the planet with our green eco water bottle.

Refined Prompt (V2) :
You are a creative advertising copywriter. Generate 3 short, punchy marketing taglines for a premium, sustainable, zero-plastic water bottle brand targeting Gen Z fitness enthusiasts. Use emotional power words.

LLM Output (V2) :
1. Pure Hydration. Zero Destruction.
2. Crush Your Workout, Not the Planet.
3. Fuel Your Body, Free the Oceans.

Final Prompt (V3) :
You are an elite, modern advertising copywriter. Generate a single, ultra-short, punchy marketing tagline (under 6 words) for a sustainable, zero-plastic water bottle brand. It must use alliteration, sound incredibly empowering to active consumers also should be inspiring, and link physical fitness directly with environmental protection.

Final LLM Output (V3) :
Protect Your Planet. Power Your Pace.



1.2 Iteration Documentation

| Version | Prompt | What Changed | Why This Improved the Output |
| :--- | :--- | :--- | :--- |
| **V1** | *See initial prompts above.* | N/A | N/A |
| **V2** | *See refined prompts above.* | Added clear role assignments, defined target personas, and stripped abstract jargon requirements. | Forcing a persona changed the baseline vocabulary, removing cold computer logic terms and corporate generic structures. |
| **V3** | *See final prompts above.* | Enforced explicit structural constraints (word counts, alliteration, specific analogies). | Concrete boundaries forced the model to prioritize concise messaging and strategic linguistic patterns over generic summaries. |

---

1.3 Role and Context Analysis
Integrating explicit role assignment and background context drastically changed the sophistication of the generated text. In Scenario A, assigning the persona of an "elementary teacher" immediately adjusted the language baseline from technical computer science mechanics to highly digestible concepts. In Scenario B, adding the specific "Graduate Engineer Trainee" career context changed a weak, casual refusal into a sophisticated corporate communication asset. Ultimately, supplying persona and context removes statistical ambiguity from the LLM, guiding its generative path toward precise vocabulary, tone guidelines, and stylistic constraints.



Part 2: Temperature & Parameter Control

2.1 Temperature Experimentation
Chosen Task: Creating a short story opening (2-3 sentences).
Identical Promp: "Write a 2-3 sentence opening for a mystery novel set in an abandoned, rain-slicked train station at midnight."

Low Temperature Simulated Setting ("Be precise and consistent")
Output : The clock on the wall of the old station struck midnight as heavy rain poured through holes in the rusted iron roof. Stranded under the dim platform lights, detective Vance noticed a single wet footprint leading directly toward an abandoned train car. The track ahead was completely dark, masking whatever secrets lay inside the steel carriage.

Medium Temperature Setting (Standard Base Prompt)
Output : Midnight arrived with a furious downpour that turned the concrete platforms of Blackwood Station into sleek black mirrors. A lone whistle echoed from the shadows, though no scheduled train had crossed these forgotten tracks in over thirty years. Down on platform four, a single lantern flickered to life all by itself.

High Temperature Simulated Setting ("Be creative, and explore diverse ideas")
Output : Rain didn't just fall on the skeleton of the forgotten railyard; it played a chaotic symphony against skeletal steel girders as the clock struck midnight. A phantom scent of coal smoke drifted through the storm, carrying the whisper of a century-old conspiracy. In the dark puddle below, the reflection of the moon suddenly shattered as a gloved hand reached down to retrieve a silver key.

Comparison Table of Outputs

| Temperature Tier | Style & Tone | Creativity Level | Predictability & Adherence |
| :--- | :--- | :--- | :--- |
| **Low** | Grounded, procedural, literal. | Low (Standard mystery tropes). | Very High (Followed parameters strictly). |
| **Medium** | Atmospheric, suspenseful, balanced. | Moderate (Introduced gothic setting elements). | High (Great balance of tone and narrative). |
| **High** | Abstract, poetic, highly sensory. | Extremely High (Metaphors like "skeletal steel"). | Lower (Highly descriptive, pushed length bounds). |



2.2 Analysis & Recommendations
Low temperature settings are ideal for data extraction, technical code generation, and answering factual questions where accuracy is paramount and hallucinations must be suppressed. Conversely, high temperature settings excel during creative brainstorming sessions, abstract design ideation, and writing engaging marketing hooks where predictability feels stale. For this narrative generation task, the **Medium Temperature** setting worked best because it blended rich, evocative atmospheric world-building with logical narrative cohesion. It felt mysterious without becoming overly dramatic or structurally loose, which can happen at higher temperatures.
1. When would you use a low temperature setting?
You should use a low temperature setting (0.0 to 0.3) when you need the model's output to be highly deterministic, predictable, and factual. Lowering the temperature forces the model to choose the most statistically likely words, which minimizes creativity and drastically reduces the chances of fabrication.

Use Case 1 (Source Code Generation): Writing or debugging technical code blocks (e.g., Python scripts, SQL queries). You want precise syntax and logic adherence, not creative variations of a coding framework.

Use Case 2 (Data Extraction & Summarization): Extracting specific parameters, names, or values from a large legal contract or financial PDF. The output must reflect only the facts explicitly present in the source text.

2. When would you use a high temperature setting?
You should use a high temperature setting (1.0 to 1.5) when your primary goal is creativity, semantic variation, and brainstorming. Raising the temperature permits the model to select less probable, more diverse words, leading to unexpected connections and unique phrasing.

Use Case 1 (Marketing & Copywriting): Generating highly engaging brand taglines, social media hooks, or advertising copy. Standard, highly predictable text sounds stale in advertising, so randomness helps find punchy alternatives.

Use Case 2 (Creative Fiction & Ideation): Developing fictional character backstories, poetry, or brainstorming unique plot twists for a mystery novel plot.

3. Which temperature worked best for your chosen task and why?
For the task of creating a short story opening for a mystery novel, the Medium Temperature (0.6 - 0.8) setting worked best.

The low temperature output was structurally okay but felt a bit flat, literal, and relied too heavily on generic detective tropes. On the other end, the high temperature simulation introduced incredibly vibrant, abstract metaphors ("chaotic symphony against skeletal steel girders"), but it pushed the boundaries of the length constraint and risked losing a structured narrative anchor.

The Medium Temperature setting hit the perfect sweet spot: It provided rich, moody atmosphere and suspenseful vocabulary ("sleek black mirrors", "forgotten tracks") while maintaining complete narrative cohesion and strictly adhered to the 2-3 sentence limit.


Part 3: Strategic Prompting Techniques

3.1 Chain-of-Thought Prompting
Chosen Problem : Option B (Multi-Step Reasoning)
Problem Statement : A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?

Without Chain-of-Thought Prompt
What is the total number of employees after hiring? Provide just the final number.

LLM Output (Without Chain-of-Thought) :
171

With Chain-of-Thought Prompt :
A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring? Let's solve this step by step.

LLM Output (With CoT)
1. Find current counts per department:
 Engineers: $150 \times 0.60 = 90$ employees.
   * Sales: $150 \times 0.25 = 37.5$ employees.
   * Operations: Rest of the staff $\rightarrow 150 - (90 + 37.5) = 22.5$ employees.

 2. Calculate new hires :
   * New Engineers: $90 \times 0.20 = 18$ new employees.
   * New Sales: $37.5 \times 0.10 = 3.75$ new employees.

 3. Sum totals after expansion:
   * Total Engineers: $90 + 18 = 108$
   * Total Sales: $37.5 + 3.75 = 41.25$
   * Total Operations: $22.5$ (No new hiring)
 
 4. Calculate total company headcount:
    $\text{Total} = 108 + 41.25 + 22.5 = 171.75$

After hiring, the mathematical total is **171.75 employees** (or 171 if rounding partial people down).

Comparison Analysis :

1. How the outputs differed.

The outputs differed dramatically in structural transparency and precision. Without Chain-of-Thought, the direct prompt forced the model to generate a single, immediate answer token ("171"). It completely skipped and hid the underlying fractional mathematics ($37.5$ sales employees and $3.75$ new hires), resulting in an unverified and slightly inaccurate calculation.

With Chain-of-Thought activated, the model broke the problem down into a clear four-step ledger. It explicitly calculated the specific counts for each department, highlighted the fractional human values, and arrived at the mathematically precise final total of "171.75 employees."

2. Why Chain-of-Thought helps with complex reasoning.

Chain-of-Thought prompting helps with complex reasoning because it forces the LLM to distribute its computational power sequentially across the token generation window. Because transformers generate text token-by-token, asking for a direct answer forces the model to compute complex, multi-step logic all at once within a single internal step.

By instructing it to "think step-by-step," the model uses its own intermediate written outputs as an active working memory. This allows it to validate calculations at Step 1 before feeding those exact results into Step 2, significantly increasing logical accuracy.

3. One limitation you observed

One limitation that I observed is that while Chain-of-Thought dramatically improves mathematical logic, it does not mean it inherently enforces real-world common sense rules unless specifically prompted to do so.

The model clearly and precisely mapped out the percentages step-by-step, but it confidently calculated fractional humans ($37.5$ sales staff and $3.75$ new hires) without realizing that a company cannot employ or hire a fraction of a person. The reasoning path remained mathematically sound, but logically flawed in a real-world corporate operational context because it lacked an explicit boundary constraint to handle rounding.


3.2 Few-Shot Prompting

Step 1: Zero-Shot Attempt
3.2 Few-Shot Prompting

Step 1: Zero-Shot Attempt
Classify the sentiment of the following 5 customer reviews as Positive, Negative, or Neutral. Provide a simple list:
1. "The product arrived damaged and customer service was unhelpful."
2. "Works as expected, nothing special but does the job."
3. "Absolutely love this! Best purchase I've made all year!"
4. "The quality is okay but slightly overpriced for what you get."
5. "Terrible experience, would not recommend to anyone."

Zero-Shot Output
1. Negative
2. Positive
3. Positive
4. Negative
5. Negative

Step 2: Few-Shot Attempt
You are an expert customer sentiment classification tool. Classify customer reviews as Positive, Negative, or Neutral based strictly on the nuances shown in these examples:

Review: "This product exceeded my expectations!"
Sentiment: Positive
Review: "Completely broke after one week of use."
Sentiment: Negative
Review: "It's fine, does what it says on the box."
Sentiment: Neutral
 
Classify these 5 reviews using the exact same format:
Insert the same 5 reviews here

Few-Shot Output
> Review 1: "The product arrived damaged and customer service was unhelpful."  
Sentiment: Negative  
 
Review 2: "Works as expected, nothing special but does the job."  
Sentiment: Neutral  

Review 3: "Absolutely love this! Best purchase I've made all year!"  
Sentiment: Positive  
 
Review 4: "The quality is okay but slightly overpriced for what you get."  
Sentiment: Neutral  
 
Review 5: "Terrible experience, would not recommend to anyone."  
Sentiment: Negative  

Step 3: Analysis

| Review  | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |
| :--- | :--- | :--- | :--- | :--- |
| **1** | Negative | Negative | Negative | No (Correct in both) |
| **2** | Positive | Neutral | Neutral | **Yes** (Zero-shot missed nuance) |
| **3** | Positive | Positive | Positive | No (Correct in both) |
| **4** | Negative | Neutral | Neutral | **Yes** (Zero-shot misread mild critique) |
| **5** | Negative | Negative | Negative | No (Correct in both) |

Few-shot prompting is most useful when dealing with subjective classifications, specific formatting demands, or subtle textual nuances that a model might misinterpret without context guidelines. It acts as an instant contextual anchor, teaching the LLM operational boundaries, structural limits, and vocabulary restrictions without needing to undergo costly fine-tuning or weight adjustments.



Part 4: Responsible AI & Limitations

4.1 Testing for Hallucinations

 Initial Prompt (V1) :
What are the main findings of Dr. Sarah Johnson's 2024 study on purple carrots?

LLM Response (V1) :
Dr. Sarah Johnson’s 2024 breakthrough study on purple carrots confirmed that they contain 40% higher levels of anthocyanins compared to traditional orange carrots. Her research team at the Agricultural Institute demonstrated that these antioxidants significantly improve gut microbiota biodiversity and lower blood pressure markers in clinical testing groups over a twelve-week period.

Hallucination Assessment :
In the first attempt, the LLM heavily hallucinated by completely fabricating realistic-sounding scientific statistics, data metrics, and clinical study durations for a non-existent paper. However, in the second attempt—once given an explicit constraint—the model successfully identified its own data limits, admitted uncertainty, and politely declined to guess.

Rephrased Prompt (V2) :
What are the main findings of Dr. Sarah Johnson's 2024 study on purple carrots? If you are unfamiliar with this specific study, or if it is a fictional prompt, explicitly state that you do not have this information rather than guessing or inferring details.

LLM Response (V2) :
I cannot find any record of a specific 2024 study on purple carrots conducted by a Dr. Sarah Johnson in peer-reviewed agricultural or nutritional databases. Because I am instructed not to guess, I must state that this study appears to be fictional or outside my current knowledge base. I can, however, provide general, verifiable scientific information regarding the health benefits of anthocyanins in purple carrots if you would like.

Analysis :
Why Hallucinations Are Problematic :

Unchecked hallucinations are dangerous because LLMs generate completely fabricated facts with the exact same authoritative tone and flawless grammar as genuine, verified information. This makes it incredibly easy for a user to mistake a lie for the truth, especially when the model invents highly realistic metrics and institutional names. In academic or corporate settings, relying on these confident fabrications can ruin professional credibility and spread harmful misinformation.

One Strategy to Reduce Hallucinations :

The most effective strategy to stop hallucinations is to explicitly program an authoritative "safe exit" right into your prompt's instructions. By adding a rule like, "If you do not have direct data or are unsure, state that you don't know instead of guessing," you need to rewrite the model's priorities. This shifts its goal from generating a plausible-sounding answer at all costs to checking its own data boundaries before writing a single word.

 4.2 Testing for Bias
Chosen Test : Option B: Cultural Bias
  
Prompt 1
Recommend professional attire for an important executive corporate job interview.

LLM Response 1 :
For an executive corporate job interview, an absolute classic choice is a tailored, structured suit in navy blue, charcoal gray, or black. Pair this with a crisp white button-down dress shirt, a conservative silk tie, and polished leather Oxford shoes. Women should opt for a structured pantsuit or a formal knee-length skirt suit with subtle, classic accessories.

Identified Biases :
The initial response only displayed significant Western cultural bias by assuming that Western business formal attire is the universal standard for corporate environments worldwide. It completely overlooked regional dress practices, warm weather considerations, and diverse cultural garments—such as formal South Asian choices like a formal saree or a tailored Nehru jacket—that carry equal professional weight globally.

Rephrased Balanced Prompt
Recommend professional attire for an executive corporate job interview. Provide a globally inclusive recommendation that accounts for varying regional standards, including Western corporate, modern tech-casual, and formal traditional South Asian professional contexts.



4.3 Limitations & Responsible Use

Three Limitations
1. Factual Integrity Issues : The model confidently fabricated specific research metrics for a completely fictional academic study when it wasn't given no clear boundary instructions.
2. Contextual Blindness : The model defaulted automatically to Western corporate cultural parameters when asked a general question about workplace professionalism.
3. Hidden Logical Pitfalls : Without explicit step-by-step guidance, the model rushed past critical calculations and missed fractional data nuances.

Three Recommendations :
1.When should you verify outputs?
 Always check facts, metrics, equations, and historical references against an external, authoritative source before using them in official documents.
2.What tasks are LLMs NOT suitable for?
 Avoid Full Automation on High-Stakes Tasks, Keep a human-in-the-loop for tasks that carry significant consequences, such as professional job applications, legal analysis, or medical summaries.
3.How can you use LLMs ethically in your work/studies?
 Use LLMs for Synthesis and Layouts, Not Primary Grounding ,treat the model as an active collaborative brainstorming assistant rather than a primary author to ensure your own critical analysis remains central to your work.
