Here’s a structured **Week 5 (Day 1–Day 7)** plan focused on:

- **Permutations & Combinations (P&C) – basics**
- **Elementary Probability**
- **Sets & Venn Diagrams (2- and simple 3-set)**
- **Arithmetic Progressions (AP)**

Assume ~**2–3 hours/day**. You can scale number of questions, but keep the structure and progression.

---

## Day 1 – Fundamental Counting Principle & Factorials

**Focus:** Learn the basic counting rule (“choices multiply”) and factorials.

### 1. Warm‑up (15–20 min)

- 5 quick mental arithmetic questions:
  - 23 + 47, 71 + 59, 84 − 37, 12 × 9, 14 × 7.
- 5 quick recall tasks:
  - List 3-digit numbers starting with 1 and ending with 5.
  - How many choices for the last digit of an even number? (0,2,4,6,8 → 5 choices)

This warms up your “choices” thinking.

---

### 2. Concept Block 1 – Fundamental Counting Principle (30–40 min)

Learn:

- If event 1 can occur in **m** ways and event 2 in **n** ways, and both are independent, total ways = **m × n**.
- Extend to 3, 4, … steps: multiply choices at each step.

**Problem Type A: Stage-by-Stage Counting (Beginner–Medium)**  
Solve 15–20 questions.

Examples:

1. A password is 2 characters long:  
   - First character: digit 0–9 (10 choices).  
   - Second character: digit 0–9 (10 choices).  
   - How many such passwords?  
2. A bag has 3 red, 2 blue pens. You want to choose:  
   - 1 pen, then 1 notebook from 4 types. How many combinations?  
3. A 3-digit number is formed using digits 1–5 (repetition allowed). How many such numbers?  
4. A 3-digit number is formed using digits 1–5 (no repetition). How many such numbers?

Key concepts:

- Break problem into *stages*: position 1, position 2, etc.
- Distinguish **with repetition** vs **without repetition**.

> For each problem, explicitly write:  
> Choices at step 1 × Choices at step 2 × Choices at step 3…

---

### 3. Concept Block 2 – Factorials & Simple Arrangements (30–40 min)

Learn:

- **Factorial**:  
  n! = n × (n−1) × (n−2) × … × 1  
  Common: 1!, 2!, 3!, 4!, 5!, 6!, 7!
- Arranging **n distinct objects in a row** ⇒ n! ways.

**Problem Type B: Factorials & Straight Arrangements (Beginner–Medium)**  
Solve 12–15 questions.

Examples:

1. Evaluate: 3!, 4!, 5!, 6!.  
2. In how many ways can 4 students stand in a line? (Answer: 4!)  
3. In how many ways can letters A, B, C, D be arranged in a row?  
4. How many 3-letter “words” (not necessarily meaningful) can be formed using letters A, B, C, D with no repetition?

Key concepts:

- Connecting “choose an order for all” → factorial.
- Seeing that **permutations** = counting arrangements.

---

### 4. Independent Thinking Task (10–15 min)

- Create 2 small real situations and solve:
  1. Choosing clothes: say 3 shirts, 2 pants, 2 shoes. How many outfits?  
  2. Ordering 3 different books on a shelf. How many orders?

Write them as text first, then translate into “choices multiply”.

---

### 5. Short Timed Drill (10–15 min)

- 10 questions:
  - 5 on simple stage-by-stage counting (Type A).
  - 5 on factorial/row arrangements (Type B).
- Time: **10–12 minutes**.
- Aim:
  - Quickly identify stages and whether repetition is allowed.

---

## Day 2 – Permutations of Distinct Objects (with Simple Restrictions)

**Focus:** Arrangements where order matters (permutations), plus basic restrictions.

### 1. Warm‑up (15–20 min)

- Quickly write:
  - 3! = ?, 4! = ?, 5! = ?, 6! = ?
- Recall:
  - Stage-by-stage method from Day 1 (write choices per position).

---

### 2. Concept Block 1 – Permutations Without Restrictions (30–40 min)

Learn:

- Selecting and arranging r items from n distinct items:  
  **nPr = n! / (n − r)!**
- But early on, often easier to think as:
  - Positions: r positions.
  - First position: n choices.
  - Second: (n−1), etc.

**Problem Type C: Direct Permutations (Medium)**  
Solve 12–15 questions.

Examples:

1. In how many ways can 3 students be chosen and arranged in 3 seats from a group of 5 students? (5P3)  
2. How many 4-digit numbers can be formed from digits 1–7, without repetition?  
3. How many different ways can you arrange the letters of the word “DOG”? (3! ways)  
4. From letters A, B, C, D, E, in how many ways can you form a 3-letter word (no repetition)?

Key concepts:

- Difference between **choosing** and **arranging** (here we arrange).
- When in doubt, draw positions and fill choices stepwise.

---

### 3. Concept Block 2 – Simple Restrictions (30–40 min)

Handle constraints like “must start with X” or “vowels together”.

**Problem Type D: Restricted Permutations (Medium–High)**  
Solve 10–12 questions.

Examples:

1. How many 4-letter words can be formed from letters A, B, C, D, E such that first letter is A?  
2. How many 4-digit even numbers can be formed from 1, 2, 3, 4, 5, 6 without repetition?  
3. How many 5-letter words can be formed from letters A, B, C, D, E if vowels (A, E) are always together?

Key concepts:

- Fix a position or block when needed:
  - For vowels-together: treat (AE) or (EA) as “one block” first.
- Separate cases if needed (e.g., last digit even → consider each possible last digit and count).

> For each restricted problem, write explicitly:
> - Strategy choice: “Fix last digit”, or “Group vowels”, etc.  
> - Then count using multiplication of choices.

---

### 4. Independent Thinking Task (10–15 min)

- Take one of today’s problems and:
  - Change the restriction (e.g., “vowels not together” instead of “together”).
  - Try to count using complement:
    - Total arrangements − arrangements with vowels together.
- Even if you don’t fully simplify, attempt to reason it out.

---

### 5. Short Timed Drill (10–15 min)

- 10 questions: mix of Types C & D.
- Time: **12–15 minutes**.
- Focus:
  - Clear stepwise reasoning.
  - Avoid jumping straight to formula without understanding.

---

## Day 3 – Combinations (Selections) & Simple Applications

**Focus:** Selections where order does not matter.

### 1. Warm‑up (15–20 min)

- Compare:
  - Arranging A,B,C in order (ABC, ACB, BAC, BCA, CAB, CBA) vs
  - Choosing {A,B,C} as a *set* (only 1 way).
- Recall idea:
  - Many arrangements correspond to **one** combination.

---

### 2. Concept Block 1 – nCr Formula (30–40 min)

Learn:

- **nCr = n! / (r!(n−r)!)**  
- Symmetry: nCr = nC(n−r).

**Problem Type E: Evaluating Combinations (Beginner–Medium)**  
Solve 12–15 questions.

Examples:

1. Compute: 5C2, 5C3, 6C2, 6C3, 7C1, 7C6.  
2. Show 5C2 = 5C3 numerically.  
3. Find 10C2 and interpret what it might mean (e.g., handshake pairs from 10 people).

Key concepts:

- Factorial simplification (cancel common parts).
- Recognize nC0 = 1, nC1 = n, nCn = 1.

---

### 3. Concept Block 2 – Selection Word Problems (30–40 min)

**Problem Type F: Committees / Team Selection (Medium)**  
Solve 10–12 questions.

Examples:

1. From 6 students, in how many ways can 3 be chosen for a project?  
2. A committee of 4 is to be chosen from 7 people. In how many ways?  
3. From 5 men and 4 women, choose a team of 3 people:  
   a) with no restriction.  
   b) with at least 1 woman.  
4. In a group of 8 people, how many pairs can be formed? (Handshakes: 8C2)

Key concepts:

- Order does not matter in a “group/committee”.
- “At least 1 woman” often easier as:
  - total ways − ways with 0 women.

> For each problem, explicitly write whether order matters.  
> If not, you must use combinations, not permutations.

---

### 4. Independent Thinking Task (10–15 min)

- Create 2 reality-based problems:
  1. Choosing a project team from your classmates with some gender/role constraint.  
  2. Choosing subgroups (e.g., “How many pairs of friends from N people?”).

Solve them, then slightly alter the condition (e.g., “at least 2 women instead of 1”) and solve again.

---

### 5. Short Timed Drill (10–15 min)

- 10 questions: mostly Type F, plus a couple of direct nCr evaluations.
- Time: **12–15 minutes**.
- Focus:
  - Translating text to combination formula correctly.
  - Using nCr symmetry to simplify quickly when needed.

---

## Day 4 – Basic Probability: Equally Likely Outcomes

**Focus:** Probability as favourable / total, and using counting ideas.

### 1. Warm‑up (15–20 min)

- 5 quick nCr evaluation questions.
- 5 quick questions:
  - Sample space size for:
    - Tossing 1 coin (2),
    - 2 coins (4),
    - Rolling 1 die (6).

---

### 2. Concept Block 1 – Probability Basics (30–40 min)

Learn:

- For equally likely outcomes:  
  P(Event) = (Number of favourable outcomes) / (Total number of outcomes).
- 0 ≤ P ≤ 1.

**Problem Type G: Simple Single-Event Probability (Beginner–Medium)**  
Solve 12–15 questions.

Examples:

1. A fair coin is tossed. Probability of head? Tail?  
2. A die is rolled. Probability of getting:  
   a) 3  
   b) even number  
   c) a number > 4  
3. A card is drawn from numbers 1–10 in a box. Probability that it is:  
   a) odd  
   b) prime  
   c) a multiple of 3

Key concepts:

- Identify sample space clearly.
- Count favourable outcomes cleanly.

---

### 3. Concept Block 2 – Two-Step Experiments & “At Least” (30–40 min)

Learn:

- For independent events, total outcomes = product of outcomes in each step.
- “At least one” trick:
  - P(at least one) = 1 − P(none).

**Problem Type H: Two-Step / Compound Events (Medium)**  
Solve 10–12 questions.

Examples:

1. Two coins are tossed. Find probability of:  
   a) exactly one head,  
   b) at least one head,  
   c) no head.  
2. A die is rolled twice. Probability that:  
   a) sum is 7,  
   b) both rolls are even,  
   c) at least one roll is 6.  
3. A bag has 3 red and 2 blue balls. One ball is drawn at random and not replaced; then another is drawn. Probability that both are red?

Key concepts:

- List sample space for small experiments (coins).
- For larger (2 dice), count smartly: use combinatorial/structured counting.
- Use complement for “at least one”:  
  P(≥1 success) = 1 − P(0 success).

---

### 4. Independent Thinking Task (10–15 min)

- Design a tiny experiment:
  - Example: “Roll a die then toss a coin.”  
- Define:
  - Sample space (all possible outcome pairs).  
  - Probability of specific combined events (e.g., “even number and head”).

This will force you to think structurally about sample spaces.

---

### 5. Short Timed Drill (10–15 min)

- 10 questions: 5 single-event, 5 two-step events (Type G & H).
- Time: **12–15 minutes**.
- Aim:
  - Quick identification of total outcomes and favourable outcomes.

---

## Day 5 – Sets & Venn Diagrams (2- and Simple 3-Set)

**Focus:** Counting using sets, union/intersection, “only”, “at least”, “neither”.

### 1. Warm‑up (15–20 min)

- 5 short probability questions from Day 4 (redo quickly).
- Recall notions:
  - Universe set, subset, complement.

---

### 2. Concept Block 1 – Two-Set Venn & Inclusion–Exclusion (30–40 min)

Learn:

- For sets A and B:
  - n(A ∪ B) = n(A) + n(B) − n(A ∩ B)
- Venn regions:
  - Only A, only B, both A & B, neither.

**Problem Type I: 2-Set Venn Problems (Medium)**  
Solve 12–15 questions.

Examples:

1. In a class of 50 students, 30 like Maths (M), 25 like Science (S), and 10 like both.  
   - How many like at least one of the two subjects?  
   - How many like only Maths? only Science? neither?  
2. In a survey, 60 people like tea, 40 like coffee, and 20 like both. Total surveyed = 100.  
   - How many like neither?  
3. In an office, 35 know Java, 28 know Python, 15 know both. How many know only Java? Only Python? At least one?

Key concepts:

- Draw Venn diagram every time.
- Systematic filling: start with intersection, then only A, only B, then neither.

---

### 3. Concept Block 2 – Three-Set Venn (Conceptual) (30–40 min)

Learn formula (don’t worry about proving it):

- For A, B, C:
  - n(A ∪ B ∪ C) = n(A) + n(B) + n(C)  
    − n(A∩B) − n(B∩C) − n(C∩A)  
    + n(A∩B∩C)

**Problem Type J: Simple 3-Set Counting (Medium–High)**  
Solve 8–10 questions.

Examples:

1. In a class,  
   - 20 study Maths (M), 25 study Physics (P), 18 study Chemistry (C),  
   - 8 study both M & P, 5 study P & C, 6 study C & M,  
   - 3 study all three.  
   Total students = 40.  
   Find:  
   - how many study at least one subject,  
   - how many study exactly two,  
   - how many study none.  
2. Numbers from 1 to 100:  
   - Let A = multiples of 2, B = multiples of 3, C = multiples of 5.  
   Roughly count how many are in A ∪ B ∪ C (you can approximate first, then be precise).

Key concepts:

- Use stepwise inclusion–exclusion, not memory alone.
- Clearly identify:
  - Only one subject, exactly two subjects, all three, none.

> For each 3-set problem, **always** draw a 3-circle Venn and label regions, even if it feels slow at first.

---

### 4. Independent Thinking Task (10–15 min)

- Create your own 2-set Venn problem:
  - Example: students who like Cricket (C) and Football (F).  
- Choose:
  - Total students, n(C), n(F), n(C∩F).  
- Ask and solve:
  - Only C, only F, at least one, neither.

---

### 5. Short Timed Drill (10–15 min)

- 10 questions:
  - 7 on 2-set Venn (Type I).
  - 3 on simple 3-set (Type J).
- Time: **15 minutes**.
- Focus:
  - Filling Venn regions in a consistent order.

---

## Day 6 – Arithmetic Progressions (AP): nth Term & Sum

**Focus:** AP basics: nth term, sum of n terms, simple word problems.

### 1. Warm‑up (15–20 min)

- List first 10 natural numbers and note:
  - Differences (always 1).
- List: 3, 7, 11, 15, 19… check difference (4).
- This shows AP as “constant difference” sequence.

---

### 2. Concept Block 1 – nth Term of AP (30–40 min)

Learn:

- AP: a, a + d, a + 2d, a + 3d, …  
- nth term:  
  **aₙ = a + (n − 1)d**

**Problem Type K: Finding nth Term, First Term, Common Difference (Beginner–Medium)**  
Solve 12–15 questions.

Examples:

1. For AP: 3, 7, 11, 15, … find:  
   - a (first term), d, a₁₀.  
2. AP: 5, 10, 15, 20, … find 25th term.  
3. In an AP, a₁ = 2, a₅ = 18. Find d and a₁₀.  
4. The 8th term of an AP is 50 and the 3rd term is 20. Find a and d.

Key concepts:

- Using formula in both directions (given term indices to solve for a,d).
- Treat a and d as unknowns and solve small linear equations.

---

### 3. Concept Block 2 – Sum of n Terms (30–40 min)

Learn:

- Sum of first n terms of AP:
  - Sₙ = n/2 [2a + (n − 1)d]  
  or
  - Sₙ = n/2 (a₁ + aₙ)

**Problem Type L: Sum & Word Problems (Medium)**  
Solve 10–12 questions.

Examples:

1. Find sum of first 10 natural numbers.  
2. Sum of first 20 terms of AP with a=3, d=4.  
3. In an AP, a₁ = 5, d = 3. What is the sum of first 15 terms?  
4. How many terms of the AP 7, 10, 13, … must be taken so that their sum is 210?

Key concepts:

- Selecting correct form of sum formula based on data.
- Sometimes need:
  - Find n when Sₙ given (leads to quadratic; for small ones you can try by trial or small manipulations).

---

### 4. Independent Thinking Task (10–15 min)

- Observe patterns:
  - Sum of first n odd numbers: 1 + 3 + 5 + …  
    - Compute for n=1,2,3,4,5 and guess a formula (it turns out to be n²).  
- Try to explain in your own words why this seems to hold (pattern observation is enough, no formal proof needed).

---

### 5. Short Timed Drill (10–15 min)

- 10 questions: mix of Types K & L.
- Time: **12–15 minutes**.
- Aim:
  - Quickly identify given data (a, d, n, aₙ, Sₙ) and what’s missing.

---

## Day 7 – Consolidation & Mixed Sectional Test

**Focus:** Integrate P&C, Probability, Sets/Venn, and AP under mild test conditions.

### 1. Quick Revision (30–40 min)

From your notes, write a 2–3 page summary:

- P&C:
  - Fundamental counting principle.
  - Factorials and simple permutations.
  - nCr formula, when to use permutations vs combinations.
- Probability:
  - P = favourable / total for equally likely outcomes.
  - Simple single-event and 2-step events, “at least one” using complement.
- Sets/Venn:
  - 2-set formula, 3-set inclusion–exclusion idea.
  - “Only”, “exactly two”, “at least one”, “neither”.
- AP:
  - aₙ = a + (n − 1)d.
  - Sₙ = n/2 [2a + (n − 1)d] or n/2(a₁ + aₙ).

---

### 2. Mixed Practice (25–30 min)

Solve **20–25 mixed questions**, untimed but focused:

Suggested mix:

- 5 on P&C (counting, simple permutations, combinations).
- 5 on probability (coins, dice, simple bag draws).
- 5 on sets/Venn (2-set, plus 1–2 simple 3-set).
- 5 on AP (nth term, sum, number of terms).

While solving:

- For each question, explicitly ask:
  - “Is order important?” (P&C)
  - “What is sample space?” (Probability)
  - “What region(s) of Venn am I counting?” (Sets)
  - “Which AP formula matches given info?” (AP)

---

### 3. Sectional Test – Week 5 Topics (30–40 min)

Create or use a small test:

- **Total:** 22–25 questions.
  - 6–7 P&C (mix permutations & combinations).
  - 6–7 Probability (single + two-step, no heavy conditional).
  - 5–6 Sets/Venn.
  - 4–5 AP.

**Time:** 30–35 minutes.

Guidelines:

- First pass:
  - Don’t spend >90 seconds on any one question.
  - Mark potentially time-consuming ones and move on.
- Attempt easier/shorter ones first (e.g., straightforward AP and simple probability) to secure marks.

---

### 4. Detailed Analysis (30–40 min)

After the test:

1. **Correct & Fast:**
   - Identify patterns you now find easy:
     - e.g., 2-set Venn, single-coin probability, basic AP nth term.

2. **Correct but Slow:**
   - Ask:
     - Did you over-write steps?
     - Could you have used a known template?  
       (e.g., at least one = total − none, handshake = nC2)
   - Re-solve 2–3 such questions focusing on speed and fewer steps.

3. **Wrong:**
   - Classify:
     - Misinterpretation (order vs no order in P&C)?  
     - Miscounting in sample space?  
     - Wrong region in Venn?  
     - Misapplied AP formula?
   - Immediately do **2 similar** questions correctly for each type of mistake.

Finally, write in your notebook:

- “Top 3 weak areas after Week 5”, e.g.:
  - Distinguishing permutations vs combinations.
  - 3-set Venn with “exactly two” vs “at least two”.
  - Probability with two dependent draws (without replacement).

These will guide your revision and targeted practice in Weeks 6–8 and your mocks.

---

If you want, next we can structure **Week 6 (Logical Reasoning – arrangements & puzzles) Day 1–Day 7** in the same style, aligned with placement patterns.
