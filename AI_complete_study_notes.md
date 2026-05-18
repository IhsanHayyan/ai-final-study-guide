# Complete AI Study Notes

Source rule used in these notes: these notes are based only on the supplied PDFs listed by the user. No outside theory has been added. Links and names that appear here are included only when they appear in the source slides.

Companion coverage file: see `AI_page_by_page_coverage_index.md` for a page-by-page source map.

---

## 01 Introduction-rrm2024.pdf

### INTRODUCTION

This chapter introduces Artificial Intelligence, its history, major types, machine learning, deep learning, generative AI, applications, and risks.

### Content

| Source page(s) | Topic covered |
|---|---|
| 1-2 | Introduction and chapter content |
| 3-4 | What AI is and what intelligence means |
| 5-11 | Historical context: Turing Test, Dartmouth Workshop, AI winters, expert systems, neural networks |
| 13, 18-19 | Brain inspiration and neural networks |
| 20-24 | Types of AI and machine learning basics |
| 27-35 | AI applications and AI literacy |
| 36-42 | Discriminative AI, generative AI, and industry/academia examples |
| 45-51 | AI risks, job replacement, hallucination |

### What is Artificial Intelligence?

Artificial Intelligence is the part of computer science that creates systems or machines that can do tasks that normally need human intelligence. In the slides, these tasks include recognizing patterns, perception, understanding natural language, learning from experience, solving problems, reasoning, and making decisions.

The source example is a self-driving car. It uses cameras to perceive the road, signs, obstacles, and pedestrians, then uses that information to make driving decisions such as stopping or following traffic signals.

### Intelligence

| Level of intelligence from the slides | Simple meaning |
|---|---|
| Performing complex tasks | Solving difficult problems and handling many things at the same time |
| Learning new skills | Picking up new information and improving over time |
| Innovation | Creating new ideas, technologies, or solutions |
| Taking over | Handling tasks that used to be done manually or at a lower level |

### Historical Context

| Period / item | What the slides say | Simple study meaning |
|---|---|---|
| Alan Turing Test, 1950 | The test was described in Alan Turing's 1950 article. | A machine is judged by whether a questioner can tell it apart from a human through answers. |
| Dartmouth Workshop, 1956 | Described as the birth of AI. | AI became a formal research field. |
| 1960s-1980s | Symbolic AI, reasoning and logic, inference, knowledge representation, search, first AI winter, expert systems, brute-force AI, IBM Watson, Deep Blue. | AI focused strongly on symbols, rules, search, and expert-like decision making. |
| First AI winter | Progress slowed and interest/funding decreased because expectations were not met. | AI became less popular for a time. |
| Expert systems | Computer systems designed to imitate human expert decision-making. | Systems that use expert rules to make decisions. |
| Brute-force approach | Trying every possible solution until the correct one is found. | A try-everything method. |
| 1980s-1990s | Connectionist AI, neural networks, second AI winter, backpropagation paper in 1986. | AI interest returned to brain-inspired networks, then slowed again. |
| Backpropagation paper, 1986 | Introduced a method to improve neural network training. | Helped make modern deep learning possible. |

### Turing Test

The Turing Test asks whether an interrogator can tell which respondent is a human and which is a machine by asking questions through a terminal. If the computer can fool the interrogator so that the interrogator cannot distinguish it from the human, the machine may be assumed to be intelligent according to the slide.

### The Solution is in the Brain

The slides connect learning and intelligence to the human brain. The brain is made of neurons, and neurons send signals and connect with each other. This idea inspires artificial neural networks.

### The Neural Network

| Biological idea | AI version in the slides |
|---|---|
| Neurons and synapses help the brain learn. | Artificial neural networks are inspired by this learning structure. |
| Synapses connect neurons. | Parameters and weights act like synapses in a neural network. |
| The brain has about 100 trillion synapses or more. | ChatGPT is stated in the slide as having 150 billion parameters. |

Important caution from the slide: an artificial neural network is not the same as a brain.

### Types of AI

| Type named in the slide | Short source-based meaning |
|---|---|
| Artificial Intelligence (AI) | The broad field. |
| Artificial Narrow Intelligence (ANI) | Listed as a type of AI in the slide. |
| Artificial General Intelligence (AGI) | Listed as a type of AI in the slide. |

### Machine Learning

Machine learning is described in the slides as programming computers so they can learn from data, and as giving computers the ability to learn without being explicitly programmed.

### The Basic Idea

| Approach | What is given | What is produced |
|---|---|---|
| Traditional programming | Data + rules | Results |
| Machine learning | Data + results | Rules |

Simple meaning: in normal programming, humans write the rules. In machine learning, the system learns the rules from examples.

### When Should We Use ML?

| Condition from the slide | Simple meaning |
|---|---|
| A pattern exists | There is something repeatable in the data. |
| We cannot pin it down mathematically | It is hard to write exact rules by hand. |
| We have a representative data set | We have examples that fairly show the problem. |

### Example Applications of AI

| Area | Examples from the slides |
|---|---|
| Images and vision | Product image analysis, tumor detection, tumor type detection |
| Text and language | Classifying news, flagging offensive comments, summarizing documents, chatbots, translation |
| Business and finance | Forecasting revenue, detecting credit card fraud, market forecasting, recommender systems |
| Voice | Reacting to voice commands |
| Customer/data grouping | Segmenting clients based on purchases, profiling |
| Medicine | Medical diagnosis |

### Deep Learning

Deep learning is presented as a branch of AI that uses neural networks with multiple hidden layers, needs lots of data, uses less feature engineering, and is described as the most successful branch of AI.

| Shallow neural network | Deep neural network |
|---|---|
| Fewer hidden layers. | Multiple hidden layers. |
| Less depth for learning patterns. | More layers for learning richer patterns. |

### Why Now?

The slides give three reasons deep learning became powerful now: data, models, and computation.

### Killer Applications

| Area | Examples from the slides |
|---|---|
| Computer vision | Image classification, object detection, image segmentation, tracking |
| Speech | Speech-to-text, text-to-speech, trigger/wake-word detection, speaker ID |
| Natural language processing | Text classification, sentiment recognition, machine translation |
| Information retrieval | Web search |

### Other Applications of AI

AI can be used for demand forecasting, product placement, supply chain, and quality control. The slides give examples of checking fabric defects, cake quality, vegetable quality, and wood quality.

### Applications in the Medical Field

The slides mention personalized medicine, remote medicine, and detecting a signal that would otherwise be buried in noise.

### AI Literacy

Low-code and no-code tools, plus platforms such as LandingLens by Landing AI, may allow more people to build AI systems, including doctors, store managers, accountants, quality inspectors, retailers, restaurants, and small business owners.

### Sample FYP/Master Projects

| Project area | Examples from the slides |
|---|---|
| Human Activity Recognition (HAR) | Sports, fitness, lifestyle, healthcare |
| Gesture recognition | Hand/head gesture recognition |
| Smart environments | Smart home applications |
| Interfaces | Machine user interface |
| Roads | Road surface monitoring, road maintenance, road safety, comfort driving |

### Discriminative versus Generative

| Discriminative | Generative |
|---|---|
| Given a picture, tells who or what it is. | Creates something new, such as a non-existing person's face. |
| Used for recognition or classification. | Used for creating text, images, or other media. |

### Generative AI

Generative AI creates text, images, or other media using generative models. It learns patterns and structure from training data, then creates new data with similar characteristics.

The slides mention transformer-based deep neural networks and examples such as ChatGPT, Bing Chat, Bard, LLaMA, Stable Diffusion, Midjourney, and DALL-E.

### Academia versus Industry

| Example | What the slide says |
|---|---|
| AlexNet, 2012 | Started the current AI revolution; done by a graduate student in a university. |
| GAN model, 2014 | Started the generative AI revolution; done by a graduate student in a university. |
| AlphaFold, 2021 | DeepMind. |
| ChatGPT, 2022 | OpenAI. |
| Parameter scale | From less than 100 million parameters to more than 100 billion parameters. |

### The Risks of AI

| Risk area | Examples from the slides |
|---|---|
| Malicious use | Disinformation, scams, hacking, cybercrime |
| Fake media | Fake news and deepfakes |
| Attacks | Adversarial attacks |
| Ethical and societal concerns | Responsible AI, bias, fairness, privacy |
| Human impact | Mental health, depression, anxiety, job replacement |
| Severe future concern | Existential threat question |
| Reliability | Hallucination |

### On Job Replacement

The slides say the AI revolution may happen much faster than the industrial revolution. They also state that AI can automate tasks requiring routine intelligence, with examples in transportation, customer service, healthcare, and marketing.

---

## 02 Logic and inference- sem 2 202526 (2).pdf

### LOGIC AND INFERENCE

This chapter explains how AI uses knowledge, logic, structured representation, inference, propositional logic, predicate logic, and reasoning rules.

### Content

| Source page(s) | Topic covered |
|---|---|
| 1-2 | Chapter title and content |
| 3-6 | Introduction to logic in AI and knowledge representation methods |
| 7-13 | Domain knowledge, inference mechanism, syntax and semantics |
| 14-16 | Logic as a formal AI language and modus ponens |
| 17-23 | Propositional logic and sentences |
| 24-31 | Arguments, syllogism, deductive reasoning, rules of inference |
| 32-45 | Predicate calculus / FOL and predicate logic exercise |

### Introduction to Logic in AI

Knowledge is necessary for intelligent behavior. The slides give simple examples: if you do not know the features of two products, you cannot choose smartly between them; if you do not know fire burns, you could hurt yourself.

AI systems use knowledge to decide and solve problems. A smart assistant uses knowledge about user preferences, while a self-driving car needs knowledge about road objects to make safe decisions.

### Need for Knowledge Representation

AI needs a structured way to store and process information. The slides mention knowledge graphs, where entities are nodes and relationships are edges.

### Logic as a Technique

Logic provides a systematic way to represent facts, rules, and relationships in a formal language that AI can interpret. It also helps AI reason about what it knows.

### Knowledge Representation Methods

| Method | Strengths | Weaknesses |
|---|---|---|
| Logic | Precise, clear, and allows automated reasoning and new knowledge inference. | Can be complex for real-world knowledge and may not capture common sense well. |
| Semantic Networks | Clear visual representation of relationships and efficient for specific tasks. | Limited expression power and limited reasoning ability. |
| Production Rules | Good for cause-and-effect relationships. | Can become difficult to manage with complex knowledge and exceptions. |

### Knowledge Representation - How to represent Knowledge in Machine?

| Component | Simple meaning | Source example |
|---|---|---|
| Domain-specific knowledge | Knowledge built for one field or problem area. | Medical diagnosis AI uses disease, symptom, and treatment knowledge. |
| Inference mechanism | A method for interpreting knowledge after sensing facts from the environment. | Smart home turns on heat if temperature drops; turns on lights if motion is detected at night. |
| Syntax and semantics | Syntax controls valid symbol structure; semantics controls meaning. | NLP grammar vs actual meaning; image pixels linked to "stop sign." |

### 🚨 EXAM TOPIC: Predicate and Propositional Logic 🚨

This is one of the most important exam areas. Keep the difference clear:

| Logic type | What it can talk about | Simple meaning |
|---|---|---|
| Propositional logic | Whole statements that are true or false. | It treats statements like blocks: "It is raining" is either true or false. |
| Predicate logic / First-Order Logic (FOL) | Objects, properties, relationships, and quantities such as "all" or "some." | It can say who or what a statement is about, such as "Aminah likes pizza." |

### Logic as a Foundation for AI

Logic is a formal language for representing knowledge at the symbol level. It includes:

| Part of logic | Simple meaning |
|---|---|
| Syntax | Rules for forming valid logical sentences. |
| Semantics | Meaning of the sentences. |
| Deduction | Deriving conclusions from premises. |

In logic, letters such as P, Q, and R can stand for propositions or statements. A statement must have a truth value: True (T) or False (F).

### Modus Ponens

| Piece | Source scheduling example |
|---|---|
| Premise 1 | If there is a conflicting meeting, then I cannot schedule a new meeting at that time. P -> Q |
| Premise 2 | There is a conflicting meeting at 2 PM. P |
| Conclusion | Therefore, I cannot schedule a new meeting at 2 PM. Q |

Simple meaning: if "P causes Q" is true, and P happens, then Q must happen.

### Propositional Logic and Sentences

Propositional logic deals with statements that can be either true or false. The simplest knowledge pieces are propositions.

Example from the slide: "It is raining" can be True or False depending on the weather.

The question "Please work AI before AI works us" is not treated like a normal proposition in the same way, because it is a request/command rather than a statement with a clear true/false value.

### How to Form Propositional Sentences

| Rule from the slide | Simple meaning |
|---|---|
| Each symbol is a sentence. | P by itself can be a valid logical sentence. |
| If P and Q are sentences, then (P) is a sentence. | Parentheses can group a sentence. |
| P ∧ Q is a sentence. | P AND Q. |
| P ∨ Q is a sentence. | P OR Q. |
| ¬P is a sentence. | NOT P. |
| P -> Q is a sentence. | IF P, THEN Q. |
| P <-> Q is a sentence. | P IF AND ONLY IF Q. |
| Nothing else is a sentence. | Only expressions built by the rules count as well-formed formulas. |

Sentences are also called well-formed formulas (WFF).

### Logical Connectives

| Symbol | Word meaning | Everyday source-style meaning |
|---|---|---|
| ∧ | AND | Both parts must be true. |
| ∨ | OR | At least one part is true. |
| ¬ | NOT | Reverses the truth value. |
| -> | IMPLIES | If the first part is true, the second follows. |
| <-> | IF AND ONLY IF | Both sides match each other. |

### Truth Values and Semantics

When we interpret a logical sentence, we give it meaning, then it becomes either True or False. For compound sentences, first assign truth values to the smaller statements, then calculate the truth value of the whole expression.

### English Sentences to Propositional Logic Sentences

| English form | Logic form | Example from slides |
|---|---|---|
| and, but | P ∧ Q | It is hot and cloudy. |
| not | ¬P | It is not hot. |
| inclusive or | P ∨ Q | It is hot or cloudy, or both. |
| exclusive or | (P ∨ Q) ∧ ¬(P ∧ Q) | It is either hot or cloudy, but not both. |
| neither... nor | ¬P ∧ ¬Q | It is neither hot nor cloudy. |

### Propositional Exercise

Let P = "King is healthy", Q = "King is wealthy", and R = "King is wise".

| Statement | Propositional expression |
|---|---|
| King is healthy and wealthy but not wise. | P ∧ Q ∧ ¬R |
| King is not wealthy, but he is healthy and wise. | ¬Q ∧ P ∧ R |
| King is neither healthy nor wealthy nor wise. | ¬P ∧ ¬Q ∧ ¬R |
| King is healthy, wealthy and wise. | P ∧ Q ∧ R |
| King is wealthy, but he is not both healthy and wise. | Q ∧ ¬(P ∧ R) |

### Arguments, Premises, and Conclusions

| Part | Meaning | Source example |
|---|---|---|
| Premise | A statement used as support. | All humans are mortal. Socrates is a human. |
| Conclusion | The statement supported by the premises. | Therefore, Socrates is mortal. |

AI uses logical reasoning to draw new conclusions from known premises.

### Syllogism and Deductive Reasoning

A syllogism has two premises and one conclusion. It helps us reason based on clear evidence.

| Type | Meaning |
|---|---|
| Valid syllogism | The conclusion logically follows from true premises. |
| Invalid syllogism | The conclusion does not logically follow from the premises. |

AI can detect invalid syllogisms by checking logical structure, truth conditions, and reasoning patterns against known logical fallacies.

### Rules of Inference

Rules of inference are logical rules for deriving valid conclusions from premises. They make sure the reasoning process has the correct structure.

| Rule named in slides | Simple meaning |
|---|---|
| Modus Ponens | If P -> Q and P is true, conclude Q. |
| Modus Tollens | Named as a rule used by AI systems in the slide. |
| Hypothetical rule | Named as another inference rule. |
| Disjunctive rule | Named as another inference rule. |

### Predicate Calculus / FOL

Predicate logic is usually used as another name for first-order logic. It is needed because propositional logic has limited expressive power.

| Need | Source example |
|---|---|
| Talk about "some" humans. | "Some humans are rich." |
| Talk about a relationship involving a named object/person. | "Aminah likes pizza." |

### FOL - Introduction

First-order logic is another way to represent knowledge in AI. It extends propositional logic and can express natural language statements more meaningfully and concisely.

### FOL Contains

| Element | Simple meaning | Source examples |
|---|---|---|
| Objects | Things being talked about. | A, B, people, numbers, colors, wars, theories, squares, pits |
| Relations | Ways objects connect or properties they have. | red, round, adjacent, sister of, brother of, has color, comes between |
| Functions | A relation-like expression that gives an object. | father of, best friend, sons of |
| Syntax | Rules for writing valid FOL expressions. | Listed as one of the two main parts. |
| Semantics | Meaning of FOL expressions. | Listed as one of the two main parts. |

### Atomic Sentences and Complex Sentences

| Sentence type | Form | Example |
|---|---|---|
| Atomic sentence | Predicate(term1, term2, ..., term n) | Brothers(Ravi, Ajay), cat(Chinky) |
| Complex sentence | Atomic sentences combined using connectives. | Built by joining smaller logical parts. |

### Subject and Predicate

In the source example "x is an integer", x is the subject and "is an integer" is the predicate.

### Quantifiers in First-Order Logic

| Quantifier | Symbol | Simple reading | Main connective from slides | Source example |
|---|---|---|---|---|
| Universal quantifier | ∀ | For all / for each / for every | Implication -> | ∀x students(x) -> learn(x, AI) |
| Existential quantifier | ∃ | There exists / for some / at least one | AND ∧ | ∃x staff(x) ∧ busy(x) |

### Properties of Quantifiers

| Property | Meaning |
|---|---|
| ∀x∀y is similar to ∀y∀x | Two universal quantifiers can be switched. |
| ∃x∃y is similar to ∃y∃x | Two existential quantifiers can be switched. |
| ∃x∀y is not similar to ∀y∃x | Mixing existential and universal order changes meaning. |

---

## 03 CSNB4133_Chap3- sem 1 2024 2025.pdf

### State Search Representation

This chapter explains search as the process of finding a sequence of actions that reaches a goal.

### Content

| Source page(s) | Topic covered |
|---|---|
| 1-3 | Outline and search introduction |
| 4-9 | State space, paths, goal tests, travelling salesperson example |
| 10-14 | Search trees, evaluation criteria, search method overview |
| 15-36 | Blind search and depth-first search |
| 37-42 | Breadth-first search |
| 43-44 | Heuristic search and benefits |
| 45-56 | Hill-climbing search, problems, and solutions |
| 57-62 | Best-first search |

### Introduction

Predicate calculus can describe objects and relationships. Inference rules such as modus ponens let us infer new knowledge. These inferences create a space that can be searched for a problem solution.

Search means looking for a sequence of actions that reaches a goal. A search algorithm takes a problem as input and returns a solution as an action sequence.

### State Search Representation

| Part of state space | Simple meaning |
|---|---|
| Initial state space | Where the problem starts. |
| Possible actions / operators | Moves the system can take. |
| Goal state | The state we want to reach. |
| Nodes | States in the tree/graph. |
| Links | Actions between states. |

### State Space Terms

| Term | Meaning |
|---|---|
| Path | A sequence of actions from one state to another, hopefully ending at the goal. |
| Path cost | A numeric cost assigned to a path. The desired path is usually the shortest. |
| Goal test | A check to see whether a state is a goal state. |

### Why "Search"?

Search helps explore alternatives in a tree and find a sequence of steps in planning. Goal-driven activities happen in a state space, so they are state space problems.

### Classical Search Domains

| Domain listed in slides | Simple study meaning |
|---|---|
| 8-Puzzle | A puzzle search problem. |
| Water Jug | A problem involving possible water states. |
| Blocks World | A block-arrangement search problem. |
| Travelling Salesman | Find shortest route visiting cities and returning home. |
| Maze | Find a route through a maze. |
| Chess | Search possible moves. |
| Tower of Hanoi | Search move sequences between pegs. |

### Travelling Salesman Example

The goal is for a salesperson to visit five cities, return home, and find the shortest path.

### 🚨 EXAM TOPIC: Search Trees 🚨

A tree is a graph that is connected, becomes disconnected if any branch is removed, and has exactly one path between any two nodes.

When judging a search method, ask these exam-style questions:

| Question | What it checks |
|---|---|
| Does the method actually find a solution? | Completeness. |
| Is it a good solution? | Path cost and search cost. |
| How much time and memory are needed? | Search cost. |
| Does it find the best possible solution? | Optimality. |

### Evaluating a Search

| Criterion | Simple meaning |
|---|---|
| Completeness | Guaranteed to find a solution if one exists. |
| Time complexity | How long it takes to find a solution. |
| Space complexity | How much memory is needed. |
| Optimality | Whether it finds the best solution when several solutions exist. |

### Search Methods

| Category | Methods listed |
|---|---|
| Blind search / uninformed algorithms | Depth-first, breadth-first, bi-directional, iterative deepening, depth-limited, uniform cost |
| Heuristic search / informed algorithms | Hill-climbing, best-first, generate and test, induction, greedy search |
| Optimal search | A* search |

### Search Methods at the First Glance

| Method | Simple source-based explanation |
|---|---|
| Depth-first search | Explores the search tree branch by branch. |
| Breadth-first search | Examines the search tree row by row. |
| Hill-climbing | Like depth-first, but examines the most promising child first. |
| Best-first search | Expands the most promising partial path found so far. |
| A* search | Described as best-first plus branch-and-bound. |

### Blind Search Methods

Blind search examines the search tree in an orderly way. It is also called uninformed search because it has no domain knowledge. It can only tell whether a state is a goal state or not a goal state.

| Blind search idea | Meaning |
|---|---|
| Exhaustive / complete | Checks all possible solutions. |
| Partial | Checks only some alternatives. |

### Depth-First Search (DFS)

DFS begins at the root and works downward into deeper levels. It continues until it finds a solution or reaches a dead end and must backtrack.

| DFS algorithm step | Simple meaning |
|---|---|
| Delete FIRSTNODE from start of QUEUE | Take the next node to process. |
| Take children of FIRSTNODE | Look at the node's next possible states. |
| Add to the front of QUEUE | Put children first so the search goes deep. |
| Put result in NEWQUEUE | Continue with the updated queue. |

For the source tree, DFS traversal order is:

| Source tree | DFS order |
|---|---|
| S with children A and B; A has C and D; B has E and F; E has G and H | S, A, C, D, B, E, G, H, F |

DFS exercise answer from the slide:

| Initial state | DFS output |
|---|---|
| A | A, B, L, C, D, E, H, G, F |

### 🚨 EXAM TOPIC: Breadth-First Search (BFS) 🚨

BFS examines all nodes in the search tree starting from the root. It finishes one level before moving to the next level.

| BFS algorithm step | Simple meaning |
|---|---|
| Take children of FIRSTNODE | Find all next states from the current node. |
| Delete FIRSTNODE from start of QUEUE | Remove the node that has just been handled. |
| Append children to the end of QUEUE | Add new nodes at the back so older same-level nodes go first. |
| Put result in NEWQUEUE | Continue with the updated queue. |

For the source tree, BFS traversal order is:

| Source tree | BFS order |
|---|---|
| S with children A and B; A has C and D; B has E and F; E has G and H | S, A, B, C, D, E, F, G, H |

BFS exercise answer from the slide:

| Initial state | BFS output by levels |
|---|---|
| A | A, BL, CG, DFEH |

### Heuristics Search

Heuristic search reduces the amount of searching. It uses a rule-of-thumb approach, prunes non-promising or weaker nodes, and usually speeds up the process of getting a good-enough solution.

### Benefits of Heuristics

| Benefit / use case | Simple meaning |
|---|---|
| Used when there is no exact solution, such as medical diagnosis. | It helps when perfect certainty is not available. |
| Used when exact solution is too expensive, such as chess. | It helps when checking everything would take too much time. |
| Flexible. | It can adapt to problem situations. |
| Better when the optimal solution is too costly to generate. | A good-enough answer may be practical. |
| Simpler for decision makers to understand. | Managers may think in a similar rule-of-thumb way. |

### 🚨 EXAM TOPIC: Hill-Climbing Search 🚨

Hill-climbing combines depth-first search with a way to order alternatives by measuring likely success at each decision point. It tries to reach the goal by choosing nodes predicted to be nearest to the goal.

| Hill-climbing algorithm step | Simple meaning |
|---|---|
| Delete FIRSTNODE from start of QUEUE | Pick the current node. |
| Take children of FIRSTNODE | Look at possible next nodes. |
| Order children with most promising first | Rank children by how close they seem to the goal. |
| Place them at the front of QUEUE | Search the best-looking child first. |
| Put result in NEWQUEUE | Continue. |

Hill-climbing is similar to DFS, but paths are not selected randomly. They are selected based on closeness to the goal.

In the source example for finding target node "1", hill-climbing compares B, C, and D, starts with branch I because it has the lowest value among B, C, and D, then backtracks and eventually reaches path A, B, E, I, D, H, G, J. The slide says the path A-C-F was not visited, saving time and cost.

### Problems with Hill-Climbing

| Problem | Simple meaning from the slides |
|---|---|
| Foothill problem | A local peak is better than nearby states, but another higher state exists elsewhere. |
| Plateau problem | A flat area where neighboring states have the same value, so the algorithm cannot find a best direction. |
| Ridges problem | A high area with a slope that cannot be reached in a single move. |

### Solution to Hill-Climbing

| Solution | Simple meaning |
|---|---|
| Random restart hill-climbing | Generate random initial states and try again. |
| Simulated annealing | Like hill-climbing, but it can accept random moves. If the move improves the solution, accept it; bad moves can also be allowed with a probability that decreases as the move gets worse. |

### Best-First Search

Best-first search combines depth-first and breadth-first search. It uses a heuristic evaluation function to score candidate nodes, then chooses the best value node.

| Best-first feature | Simple meaning |
|---|---|
| More flexible than hill-climbing | It can switch between paths. |
| Uses an evaluation function | Each candidate node gets a score. |
| Chooses the most promising node | It follows the best-looking option at each step. |
| Can become shortsighted | It may focus on a promising partial path too strongly. |

Source examples include games and web crawlers. In a web crawler, pages are nodes and hyperlinks are unvisited successor nodes. Priority can be based on how closely a page matches a search query.

| Best-first algorithm step | Simple meaning |
|---|---|
| Delete FIRSTNODE from start of QUEUE | Take the current best node. |
| Take children of FIRSTNODE | Generate next possible nodes. |
| Append children to QUEUE | Add them to possible choices. |
| Order result with most promising first | Sort by best score. |
| Put ordered result in NEWQUEUE | Continue with the sorted queue. |

In the source example for finding target "3", best-first search path is A, B, D, H, G, J. The slide says hill-climbing would use A, B, E, I, D, H, G, J, which is longer.

---

## 05_CSNB234_Chap5_Notes_Knowledge_representation_sem_1_2024_2025.pdf

### Knowledge Representation

This chapter covers formal logic, semantic networks, conceptual graph, frames, scripts, production rules, and reasoning methods in production rule systems.

### Content

| Source page(s) | Topic covered |
|---|---|
| 1-4 | Introduction to knowledge representation and reasoning |
| 5-8 | Types of knowledge and representation techniques |
| 9-12 | Semantic networks |
| 13-15 | Frames and frame advantages |
| 16-22 | Production rules and rule firing |
| 23-32 | Forward chaining |
| 33-37, 40-43 | Backward chaining |
| 38-39 | Summary and supplementary |

Conceptual Graph and Scripts are named in the source outline and summary. The extracted source pages do not provide separate explanatory body text for them, so these notes do not add outside explanation for those two headings.

### Introduction

Humans understand, reason, and interpret knowledge. Knowledge representation asks how machines can represent information about the real world so they can use it to solve complex problems such as medical diagnosis or natural language communication.

Knowledge representation is not just storing data. It lets an intelligent machine learn from knowledge and experience so it can behave intelligently.

### Knowledge and KRR

| Term | Simple meaning |
|---|---|
| Knowledge | Awareness or familiarity gained from facts, data, situations, and experience. |
| Knowledge representation and reasoning (KR, KRR) | The AI area about how agents think and how thinking supports intelligent behavior. |

### Types of Knowledge to Represent

| Type | Simple meaning | Source example |
|---|---|---|
| Object | Facts about objects in the world. | Guitars have strings; trumpets are brass instruments. |
| Events | Actions that happen in the world. | Events are actions. |
| Performance | Knowledge about how to do things. | Behavior/action knowledge. |
| Meta-knowledge | Knowledge about what we know. | Knowing about knowledge. |
| Facts | Truths about the real world. | What is represented. |
| Knowledge-base (KB) | A group of sentences used by a knowledge-based agent. | Central component of knowledge-based agents. |

### Knowledge Representation Techniques

| Technique | Simple source-based meaning |
|---|---|
| Logical representation | Uses rules, propositions, syntax, and semantics with no ambiguity. |
| Semantic networks | Concepts as nodes and relationships as links. |
| Frames | Information stored in meaningful chunks using slots and slot values. |
| Production rules | Knowledge captured as IF condition THEN action rules. |

### Formal Logic

Logical representation is a language with concrete rules. It draws conclusions based on conditions, uses precise syntax and semantics, and supports sound inference. The slides categorize it into propositional logic and predicate logic.

### Syntax and Semantics

| Concept | Simple meaning |
|---|---|
| Syntax | Rules that decide how legal sentences are built and which symbols can be used. |
| Semantics | Rules for interpreting the sentence and assigning meaning. |

### 🚨 EXAM TOPIC: Semantics / Semantic Networks 🚨

Semantic networks show meaning by drawing concepts and relationships. Think of them as a meaning map.

| Semantic network part | What it means |
|---|---|
| Node | A concept, such as bird, person, book, famous, intelligent. |
| Link / arc | A relationship between concepts. |
| Label on arc | The type of relationship, such as is_a, has_a, has_part. |
| Binary relation | A relationship connecting two concepts. |

How meaning and relationships are mapped:

| Source statement | Semantic network mapping |
|---|---|
| Jerry is a cat. | Arrow from Jerry to cat, labeled is_a. |
| Jerry is a mammal. | Arrow from Jerry to mammal, labeled is_a. |
| Jerry is owned by Priya. | Relationship link between Jerry and Priya. |
| Jerry is brown colored. | Relationship link from Jerry to brown colored. |
| All mammals are animal. | Arrow from mammal to animal, labeled is_a. |

Example 2 from the source:

| Description | Relationship |
|---|---|
| Lab is a room. | Lab is_a room. |
| Lab has a door. | Lab has_a door. |
| Lab has many computers. | Lab has computers. |
| Printer is in lab. | Printer in lab. |
| Laser printer is a printer. | Laser printer is_a printer. |

### Drawbacks of Semantic Networks

| Drawback | Source example |
|---|---|
| Disjunctive information is hard to include. | Apple can be either green or red. |
| Conjunctive information is hard to include. | Panda has color black and white. |

### Frames

A frame stores information in meaningful chunks. It has slots and slot values.

| Frame idea | Simple meaning |
|---|---|
| Slot | A field/category, such as title or author. |
| Slot value | The value stored in that field. |

Book frame example from the slide:

| Slot | Value |
|---|---|
| Title | Qualitative Reasoning |
| Author | Ken D. Forbus |
| Publisher | Prentice-Hall |
| Year | 2000 |

### Advantages of Frame Representation

| Advantage | Simple meaning |
|---|---|
| Groups related data. | Makes programming easier. |
| Flexible and used in many AI applications. | Can fit different situations. |
| Easy to add slots. | New attributes and relationships can be added. |
| Easy to include default data. | Missing values can be searched for or filled. |
| Easy to understand and visualize. | Humans can read the structure more easily. |

### Production Rules

Production rules use simple IF-THEN form. Expert systems often use large sets of production rules.

| Production rule part | Other names in slide | Simple meaning |
|---|---|---|
| IF part | Antecedent, premise, condition | What must be true. |
| THEN part | Consequent, conclusion, action | What happens after the condition is true. |

Traffic-light examples:

| Rule | Meaning |
|---|---|
| IF traffic-light is green THEN action is go | Green means go. |
| IF traffic-light is red THEN action is stop | Red means stop. |

### Multiple Conditions

| Connector | Meaning |
|---|---|
| AND | All conditions must hold. |
| OR | At least one condition must hold. |

Example from the slide:

| IF conditions | THEN action |
|---|---|
| Age of student < 21 AND SPM number of A's >= 8 | Admit student to BIT |

### Types of Things Rules Can Represent

| Type | Source example |
|---|---|
| Relations | IF fuel tank is empty THEN car will not start. |
| Recommendation | IF you study hard AND smart AND never absent THEN you will get an "A". |
| Strategy | Step-by-step car troubleshooting rules. |
| Heuristics | IF spill is liquid AND pH < 6 AND smell is vinegar THEN spill material is acetic acid. |
| Directive | IF fuel tank is empty THEN refuel the car. |

### "Firing" of Rules

A rule fires when its condition part is satisfied. Then its action part is executed. The inference engine links rules in the KB with facts in the DB to reach a solution. The explanation facility lets users ask "why" and "how".

### Reasoning Methods in Production Rule Systems

| Method | Simple name | Direction |
|---|---|---|
| Forward chaining | Data-driven reasoning | Starts from known facts and moves forward to conclusions. |
| Backward chaining | Goal-driven reasoning | Starts from a goal and works backward to prove it. |

### 🚨 EXAM TOPIC: Forward Chaining 🚨

Forward chaining is data-driven reasoning. It begins with known facts/data, then uses rules to add new facts until it solves the problem or no rule can fire.

### Forward Chaining Rules

| Forward chaining rule from slides | Simple meaning |
|---|---|
| Starts from known fact/data. | Begin with what is already true. |
| Proceeds forward with the data. | Use facts to trigger rules. |
| Only the topmost rule is executed each time. | Rules are checked in order. |
| Fired rule adds a new fact to the database. | New knowledge is created. |
| Any rule can be executed only once. | Do not fire the same rule repeatedly. |
| Stops when no further rules can fire. | End when nothing new can be concluded. |

### Forward Chaining - Simplest Process

| Step | What to do |
|---|---|
| 1 | Collect rules in the KB whose conditions match facts in the DB. |
| 2 | Do the action stated by the rule. |
| 3 | Add facts to the DB or delete facts from the DB. |
| 4 | Repeat until the problem is solved or no condition matches. |

### Forward Chaining Example: Prove If A and B true, then D is true

| Given rule | Meaning |
|---|---|
| Rule 1: If A and C then F | A plus C gives F. |
| Rule 2: If A and E then G | A plus E gives G. |
| Rule 3: If B then E | B gives E. |
| Rule 4: If G then D | G gives D. |

| Step | Known facts / fired rule | Result |
|---|---|---|
| Start | A and B are true. | DB has A, B. |
| 1 | Rule 3 fires because B is true. | Add E. |
| 2 | Rule 2 fires because A and E are true. | Add G. |
| 3 | Rule 4 fires because G is true. | Add D. |
| End | D is true. | Goal reached. |

### Forward Chaining Health Exercise

| Starting facts | Fired rules | Final recommendation |
|---|---|---|
| Catholic, eats poultry, works 4 hours today | R9, R4, R2, R6 | Healthy |
| Eats veal | R8, R1, R7 | Unhealthy |

Why rules did or did not fire in the Catholic/poultry example:

| Rule | Used? | Reason from slide |
|---|---|---|
| R9 | Yes | Working 6 hours or less today means it is Friday. |
| R4 | Yes | Catholic and Friday means eat no fish and no beef. |
| R2 | Yes | Eats fish or poultry and no beef gives low cholesterol. |
| R6 | Yes | Low cholesterol gives healthy. |
| R1 | No | No clue on egg. |
| R3 | No | Person eats poultry, so condition is false. |
| R5 | No | Not told the person is vegetarian. |
| R8 | No | Eating veal is unknown. |

### Forward Chaining Exercise: A, B, C, E are true

| Rule | Condition | Conclusion |
|---|---|---|
| Rule 1 | X, B, E true | Y true |
| Rule 2 | Y, D true | Z true |
| Rule 3 | A true | X true |
| Rule 4 | Y, C true | W true |

| Step | Fired rule | Result |
|---|---|---|
| Start | A, B, C, E true | Facts available. |
| 1 | Rule 3 | X becomes true. |
| 2 | Rule 1 | Y becomes true. |
| 3 | Rule 4 | W becomes true. |
| End | Rule 2 fails because D is not true. | System returns W. |

### Backward Chaining

Backward chaining is goal-driven. It is best when we want to find the reason after something has happened. The expert system starts with a goal and tries to find evidence to prove it. If evidence is not found, backtracking is used.

### Forward Chaining vs Backward Chaining

| Feature | Forward chaining | Backward chaining |
|---|---|---|
| Starting point | Known facts/data | Goal/hypothesis |
| Direction | Facts -> conclusions | Goal -> supporting facts |
| Main use from slides | Data-driven reasoning | Goal-driven reasoning |
| Stop condition | Problem solved or no rule fires | Goal proven or no rules can prove subgoal |

### Backward Chaining - Simplest Process

| Step | What to do |
|---|---|
| 1 | To prove goal G, first check if G is already a fact. |
| 2 | If G is a fact, G is proven and stop. |
| 3 | If not, find a rule that concludes G. |
| 4 | Try to prove each condition of that rule. |
| 5 | G is true if all required premises are true. |

### Backward Chaining Example: Catch 6:00 Flight

| Rule | IF | THEN |
|---|---|---|
| 1 | Wake up at 4:00 | Pack at 4:30 |
| 2 | Pack at 4:30 | Leave home by 5:00 |
| 3 | Leave home at 5:00 | Park car by 5:15 |
| 4 | Park car at 5:15 | Check in by 5:30 |
| 5 | Check in by 5:30 | Catch 6:00 flight |

Backward chaining starts with the goal "catch 6:00 flight", then looks for the rule that can prove it, then keeps moving backward until it reaches the starting premise: wake up at 4:00.

---

## 06 ML - First Iteration sem 1 2024 2025 (1).pdf

### INTRODUCTION

This chapter gives a first overview of machine learning.

### What is Machine Learning?

Machine Learning is a subset of AI that enables systems to learn and improve from data without being explicitly programmed. The key concept is learning from data.

### Why Machine Learning?

| Application area | Examples from slides |
|---|---|
| Search | Google search |
| Ads | Google ads |
| Recommendation | Netflix, YouTube |
| Voice assistants | Siri, Alexa |
| Computer vision | Face recognition |
| NLP | Google Translate, ChatGPT |

### When Should We Use ML?

| Condition | Simple meaning |
|---|---|
| A pattern exists | The data has a repeatable pattern. |
| We cannot pin it down mathematically | Exact hand-written rules are hard. |
| We have a representative data set | We have examples that show the problem well. |

### Core Concepts of Machine Learning

| Concept | Simple meaning |
|---|---|
| Data | The foundation of ML. |
| Algorithms | The engine of learning. |
| Models | The result of learning. |
| Training set | Data used to train the model and let it learn patterns. |
| Test set | Data used to evaluate performance on unseen data. |

### Types of Machine Learning

| Type | Simple meaning | Source examples |
|---|---|---|
| Supervised learning | Learning with labeled data. | Image recognition, spam detection |
| Unsupervised learning | Finding patterns in data without labels. | Customer segmentation, anomaly detection |
| Reinforcement learning | Learning by trial and error using feedback from the environment. | Self-driving cars, AlphaGo |

### Machine Learning Tasks

| Task | What it does | Type named in slides |
|---|---|---|
| Classification | Puts data into predefined classes. | Supervised learning |
| Regression | Predicts continuous values. | Supervised learning |
| Clustering | Groups similar data points. | Unsupervised learning |
| Association | Discovers rules in large data. | Unsupervised learning |

### Machine Learning Techniques

| Technique | Simple meaning |
|---|---|
| Neural networks | Mimic the human brain. |
| Decision trees | Flowchart-like tree structures. |
| Support vector machines | Find the best boundary that separates classes. |
| Ensemble methods | Combine predictions from multiple models. |

### Challenges in Machine Learning

| Challenge type | Challenge | Simple meaning |
|---|---|---|
| Technical | Data quality | Bad data can hurt learning. |
| Technical | Overfitting | Model learns training details too much, including noise. |
| Technical | Underfitting | Model is too simple to learn the real pattern. |
| Technical | Resources | ML may need resources. |
| Ethical | Bias and fairness | Output may be unfair. |
| Ethical | Privacy concerns | Data may involve private information. |
| Ethical | Future of work and automation | Jobs and work may change. |
| Ethical | Mental health | Human well-being may be affected. |
| Ethical | Malicious use of ML | ML can be used harmfully. |

---

## 07 Traditional ML - sem 2 2025 2026 Supervised learning 1 (2).pdf

### TRADITIONAL ML - SUPERVISED LEARNING 1

This chapter covers supervised learning tasks, regression, classification, linear regression, loss functions, gradient descent, overfitting, and underfitting.

### Content

| Source page(s) | Topic covered |
|---|---|
| 1-5 | Supervised learning overview and tasks |
| 6-9 | Classification and income prediction examples |
| 10-16 | Regression, features, training/test datasets, learning algorithms |
| 17-24 | Linear regression, OLS, cost/loss, optimization |
| 25-28, 37 | Overfitting and underfitting |
| 31-36 | Gradient descent |

### Supervised Learning

Supervised learning starts with training examples that have correct labels. The algorithm learns how to map input data to specific outputs.

### Tasks of Supervised Learning

| Task | What it predicts | Example from source |
|---|---|---|
| Classification | A category/label. | Handwritten digit label 0-9. |
| Regression | A continuous value. | Annual income from years of education. |

### Classification Example: Handwritten Digits

| Step | Simple meaning |
|---|---|
| Model sees many labeled images. | Example: image of "5" -> label 5. |
| Model learns patterns. | It notices image features linked to labels. |
| Model predicts new images. | It guesses the number for an unseen handwritten image. |

### Predicting Annual Income

The slides compare a rigid rule-based model with machine learning. A hand-written rule might say every extra year of higher education increases annual income by $5,000. Machine learning instead learns the relationship from labeled data.

| Approach | How it works | Source issue |
|---|---|---|
| Rules-based model | Human writes fixed rules. | Rules become complicated as more factors are added. |
| Supervised learning | Machine learns relationship from X and Y examples. | Goal is to predict Y accurately for new X. |

### Regression: Predicting a Continuous Value

Regression predicts a continuous target variable Y. Continuous means the value can move smoothly without gaps, such as weight or height.

| Term | Meaning |
|---|---|
| X | Input data/features. |
| Y | Target output we want to predict. |
| Feature | Useful attribute, such as years of education or job title. |
| Numerical feature | Number-based feature, such as years of work experience. |
| Categorical feature | Category-based feature, such as job title. |

### Training and Test Datasets

| Dataset | What it contains | Purpose |
|---|---|---|
| Training dataset | Labeled examples with features and target values. | Used to train the model. |
| Testing dataset | Used during evaluation. | Tests whether model works on unseen data. |

Generalization means the model should not only memorize training data. It should predict accurately on new data.

### Importance of Training and Testing

| If training/testing is used | If it is skipped |
|---|---|
| Helps check whether the model generalizes to new data. | Model may look better than it really is. |
| Helps detect overfitting. | Real-world accuracy may suffer. |

### Linear Regression (Ordinary Least Squares)

Linear regression is used in the source to predict income Y from years of education X. The goal is to learn a linear model that predicts a new Y for an unseen X with as little error as possible.

The slide uses the form Y = mX + c, also described with parameters β0 and β1.

| Linear regression part | Simple meaning |
|---|---|
| Slope β1 | How much Y changes when X increases by one unit. |
| Intercept β0 | Starting value when X is zero. |
| Prediction ŷ | The model's guessed value. |

If the slope is 5 and income is measured in thousands of dollars, then one more year of education increases predicted income by 5 units, meaning $5,000.

### Cost Function / Loss Function

A cost or loss function measures how inaccurate the model's predictions are. For linear regression, the slide names Mean Squared Error (MSE) as the common cost function.

| Goal | Meaning |
|---|---|
| Define cost function | Measure error. |
| Minimize cost function | Adjust β0 and β1 so predictions become more accurate. |

### Optimization Process

| Method | Source meaning |
|---|---|
| Ordinary Least Squares (OLS) | Directly computes parameters that minimize the cost function. |
| Gradient descent | Iteratively adjusts parameters to reduce the cost function. |

### Overfitting

Overfitting happens when a model learns training data too well, including noise and small mistakes.

| Overfitting behavior | Result |
|---|---|
| Works very well on training data. | Looks strong during practice. |
| Works poorly on new data. | Fails to generalize. |
| Memorizes instead of understanding. | Like memorizing exact past exam answers, then failing when questions change. |

### Ways to Combat Overfitting

| Method | Simple meaning | Source example |
|---|---|---|
| Get more data | More examples make memorization harder. | Use 500-1000 spam emails instead of 50. |
| Simplify the model | Smaller models are less likely to memorize noise. | Use smaller neural network or logistic regression instead of huge deep network. |

### Underfitting

| Underfitting behavior | Result |
|---|---|
| Model is too simple. | It cannot learn the real pattern. |
| Performs poorly on training data. | It did not learn enough. |
| Performs poorly on new data. | It also fails outside training. |

### Overfitting vs Underfitting

| Concept | Main problem | Performance |
|---|---|---|
| Overfitting | Learns too much detail/noise from training data. | Good on training, poor on new data. |
| Underfitting | Too simple to learn the real pattern. | Poor on training and poor on new data. |

### Gradient Descent: Learn the Parameters

Gradient descent is used to find the minimum of the model's loss function by repeatedly improving the parameter guesses.

The slide's analogy is walking through a valley blindfolded. You feel which direction slopes downward, take a step, and repeat until the ground is flat. The bottom of the valley is the minimum loss.

| Gradient descent idea | Simple meaning |
|---|---|
| Start with guessed β0 and β1 | Begin with estimated parameters. |
| Compute partial derivatives | See how changing each parameter affects loss. |
| Move opposite the direction that increases loss | Walk downhill. |
| Stop when loss is minimized | The algorithm has converged. |

For β1, if dz/dβ1 is negative, increasing β1 reduces loss. If it is positive, decrease β1. If it is zero, do not change β1 because an optimum has been reached.

---

## 09_Traditional_ML_Supervised_learning_3_part_1_sem_1_2025_2026.pdf

### TRADITIONAL ML - SUPERVISED LEARNING 3

This chapter covers non-parametric learners, k-nearest neighbors, decision trees, random forests, cross-validation, hyperparameter tuning, and ensemble models.

### Supervised Learning: A Quick Recap

Supervised learning uses labeled training data. The goal is to predict an output label from input data.

| Term | Meaning | Source example |
|---|---|---|
| Features X | Input data. | House size, email text. |
| Label Y | Output to predict. | House price, spam/not spam. |

Without labels, the problem is not supervised learning.

### Parametric Models and Non-Parametric Models

| Feature | Parametric models | Non-parametric models |
|---|---|---|
| Function form | Assume a fixed form. | Do not assume a fixed form. |
| Example equation | Y = mx + b. | No predefined equation. |
| What they learn | Parameters. | Structure directly from data. |
| Examples | Linear regression, logistic regression. | Decision tree, k-nearest neighbors. |
| Strength | Simple, fast, easier to interpret. | More flexible, handles complex patterns. |
| Limitation | Less flexible. | More complex as more data is added. |

### What Are Non-Parametric Learners?

Non-parametric models do not assume a fixed structure for the function. They learn directly from data, which helps them adapt to complex and nonlinear patterns.

### Advantages of Non-Parametric Learners

| Advantage | Simple meaning |
|---|---|
| Handles complex and nonlinear relationships. | Can learn patterns that are not straight lines. |
| More flexible than parametric models. | Less tied to a fixed formula. |
| Useful when the true function is unknown or complex. | Helpful when one formula is not enough. |

The source example is predicting housing prices using many factors such as size, location, rooms, school proximity, crime rate, and neighborhood appeal.

### Why Use k-NN?

k-nearest neighbors predicts by looking at similar examples. For house prices, it can find similar houses and average their prices.

### k-NN Recap

| k-NN feature | Meaning |
|---|---|
| Type | Supervised, non-parametric. |
| Use cases | Classification and regression. |
| Classification prediction | Majority vote. |
| Regression prediction | Average. |
| Strength | No need to define a mathematical function in advance. |
| Requirement | Need to compute distance between data points. |

### k-Nearest Neighbors (k-NN)

To classify a mysterious green circle, measure its distance to all known points, select the k closest points, and use majority vote.

| k value | Source example result |
|---|---|
| k = 3 | If two nearest points are red and one blue, predict red. |
| k = 5 | Label is based on majority vote among five nearest neighbors. |

For continuous variables such as house prices, k-NN takes the average of the k closest values. For categories such as cat vs dog, it uses the mode/most common label.

### How to Use k-NN to Predict Housing Prices

| Step | What happens |
|---|---|
| 1 | Store training data X with features such as zip code, neighborhood, bedrooms, square feet, distance from public transport, and corresponding sale prices Y. |
| 2 | Sort training houses by similarity to the house being predicted. |
| 3 | Take the mean of the k closest houses as the sale price guess. |

### Euclidean Distance in k-NN

Euclidean distance measures straight-line distance between points. In 2D, the slide gives:

sqrt((x2 - x1)^2 + (y2 - y1)^2)

This distance helps decide which data points are nearest.

### k-NN Example: Predict Label for (3,4) with k = 3

| Point | Feature 1 | Feature 2 | Label |
|---|---:|---:|---|
| P | 1 | 2 | YES |
| Q | 4 | 6 | NO |
| R | 5 | 7 | NO |
| S | 2 | 3 | YES |

| Point | Distance to (3,4) | Label | Rank |
|---|---:|---|---:|
| S | 1.41 | YES | 1 |
| Q | 2.24 | NO | 2 |
| P | 2.83 | YES | 3 |
| R | 3.61 | NO | 4 |

| k nearest points | Labels |
|---|---|
| S, Q, P | YES, NO, YES |

Final prediction: YES, because YES appears twice and NO appears once.

### Choosing k: Tuning Hyperparameters by Cross-Validation

A hyperparameter is a setting chosen before training. It is not learned from the data.

| Hyperparameter example | Model |
|---|---|
| k | k-NN |
| max_depth | Decision trees |
| learning_rate | Neural networks |

Weights in regression or splits in trees are not hyperparameters because they are learned during training.

### Cross-Validation

| Step | Meaning |
|---|---|
| Split data into folds | Example: 5 groups. |
| Train/test each fold | Train on 4 folds, test on 1. |
| Repeat | Each fold becomes the test set once. |
| Try different k values | Example: 1, 3, 5, 7. |
| Measure performance | Use accuracy or mean squared error. |
| Average results | Gives a more reliable evaluation. |

### Higher k Prevents Overfitting

| k size | Behavior | Risk |
|---|---|---|
| Small k, such as k = 1 | Focuses only on nearest neighbor. | Can overfit to random noise. |
| Larger k | Considers more neighbors. | More general. |
| Too large k, such as k = N | Looks at all training points. | Too simple and may predict only the majority class. |

The slide's animal example: if 90 out of 100 animals are cats and 10 are dogs, k = N = 100 may predict "cat" even for a dog-like test point.

### Where to Use k-NN in the Real World

| Use case | Why k-NN fits |
|---|---|
| Fraud detection | Can update quickly with new training examples. |
| Housing price prediction | Nearby houses can be similar in price. |
| Missing data imputation | Mean or mode of nearby points can fill missing values. |

### Random Forest and Decision Tree

### Random Forest: Many Trees, One Strong Forest

Random forest is an ensemble of decision trees. Each tree trains on a random data subset. Each split considers a random subset of features. Classification uses majority voting, while regression uses averaging.

### Random Forest Benefits and Trade-Off

| Benefit / trade-off | Meaning |
|---|---|
| Reduces overfitting | Many trees help avoid depending too much on one tree. |
| Robust with noisy or large datasets | Handles difficult data better. |
| Helps identify important features | Shows which inputs matter. |
| Less interpretable | Harder to explain than one tree. |
| Slower to train | Takes more time/resources. |

### Decision Tree vs Random Forest

| Feature | Decision Tree | Random Forest |
|---|---|---|
| Number of models | Single model. | Ensemble of trees. |
| Interpretability | Easy to interpret. | Harder to interpret. |
| Overfitting | Prone to overfitting. | More accurate and less overfitting. |
| Speed/resources | Simpler. | Slower and more resource-intensive. |

### When to Use Decision Tree vs Random Forest

| Situation | Use Decision Tree | Use Random Forest |
|---|---|---|
| Need simple model | Yes. | Less suitable. |
| Need clear interpretation | Yes. | Less suitable. |
| Can accept some overfitting risk | Yes. | Less necessary. |
| Want better accuracy and robustness | Less suitable. | Yes. |
| Large or noisy dataset | Less suitable. | Yes. |
| Interpretability less critical | Less suitable. | Yes. |

---

## 10 Unsupervised learning.pdf

### UNSUPERVISED LEARNING

This chapter covers clustering, dimensionality reduction, k-means clustering, and principal component analysis.

### Introduction - Why do we need Unsupervised Learning?

Unsupervised learning helps when we do not have labels or predefined categories. It finds hidden patterns, groups similar data, and reduces complexity.

### Main Unsupervised Learning Tasks

| Task | Simple meaning |
|---|---|
| Clustering | Group data by similarity. |
| Dimensionality reduction | Compress data while keeping useful structure. |

### Examples

| Example from slides | How unsupervised learning helps |
|---|---|
| Advertising platform | Segments people into similar groups for relevant ads. |
| Airbnb | Groups housing listings into neighborhoods. |
| Data science team | Reduces dimensions to simplify modeling and reduce file size. |

Unlike supervised learning, evaluation is harder because there are no predefined labels. The quality depends on whether the patterns are meaningful for the task.

### Clustering

Clustering groups similar data points together. The source example is Acxiom's Personicx system, which categorizes U.S. households into 70 clusters within 21 life-stage groups.

| Personicx cluster idea | Source example |
|---|---|
| Starting Out | Young people beginning careers or education. |
| Top Wealth | Wealthy, established professionals. |

Advertisers can use clusters to target ads, such as gym memberships to active groups or luxury products to top wealth groups.

### K-Means Clustering

K-means divides data into k clusters.

| k value | Effect |
|---|---|
| Larger k | Smaller, more detailed groups. |
| Smaller k | Broader groups. |

Student performance example:

| k setting | Possible grouping |
|---|---|
| Larger k, such as 10 groups | Small categories like 90-92%, 93-95%. |
| Smaller k, such as 2 groups | High Performers and Low Performers. |

A centroid is the central point of a cluster, representing the average position of points in that group. Points closest to a centroid are assigned to that centroid's cluster.

### K-Means Clustering Steps

| Step | What happens |
|---|---|
| 1. Initialize centroids | Choose k centroids at random. |
| 2. Assign data points | Assign each point to the nearest centroid using distance. |
| 3. Update centroids | Recalculate each centroid as the average position of its cluster points. |
| 4. Repeat until stable | Repeat assigning and updating until centroids no longer change much. |
| 5. Stable clusters | The clusters become well-defined and stable. |

The slides also say k-means can group handwritten digit images by finding patterns in pixel values.

### Dimensionality Reduction

Dimensionality reduction is like compression. It reduces data complexity while keeping as much important structure as possible.

| Problem | Simple meaning |
|---|---|
| Too many features | Example: 128 x 128 image has 16,384 pixels/dimensions. |
| Hard to analyze or visualize | Too much information makes work difficult. |
| Noise/repetition | Some features may not add useful information. |

### Principal Component Analysis (PCA)

PCA is presented as a common dimensionality reduction technique.

Source analogies:

| Analogy | PCA meaning |
|---|---|
| Library with thousands of books | PCA groups similar books into categories, so we manage fewer categories instead of many books. |
| Weather factors | PCA finds a simpler set of factors when variables such as temperature, humidity, sunlight, and wind overlap. |

The supplementary slide also introduces spaces and bases, showing that points can be described using a different basis while still making the math work.

---

## 11_Neural_Networks_and_Deep_Learning_may_2026_sem_2_2025_2026.pdf

### NEURAL NETWORKS AND DEEP LEARNING

This chapter explains deep neural networks, image classification, brain inspiration, neurons, feature learning, layers of abstraction, software packages, CNNs, RNNs, and applications.

### Content

| Source page(s) | Topic covered |
|---|---|
| 1-4 | Deep learning and the function f |
| 5-6 | Image classification and gradient descent training |
| 7-8 | Deep learning history and enabling factors |
| 9-14 | Biological neurons and artificial neurons |
| 15-19, 29 | Feature learning and layers of abstraction |
| 20-23 | Interpretability, software packages, CNNs, RNNs |
| 24-28 | Deep learning applications |
| 25 | DNN vs CNN vs RNN |

### Deep Learning

In machine learning, f is the function the model tries to learn. It maps an input to an output.

| Input | Output | Meaning of f |
|---|---|---|
| Image | Label or class | Maps pixels to the correct image class. |
| Sentence | Sentiment or translation | Maps text to meaning or translated text. |
| Game state | Best move | Maps game situation to action. |

The real world is messy, so f can be complicated. The slides mention natural language, vision problems, and games as difficult cases.

### 🚨 EXAM TOPIC: Neural Networks 🚨

A neural network is a computational model inspired by biological neurons. It is used to recognize patterns, classify data, and make predictions.

### Image Classification

The source example is a deep neural network classifying an image such as a lion.

| Network part | What it does in simple language |
|---|---|
| Input layer | Receives raw image data. Each pixel is treated as a feature. |
| Hidden layer 1 | Detects basic features such as edges or lines. |
| Hidden layer 2 | Combines basic features into shapes or patterns. |
| Hidden layer 3 | Finds complex parts such as ears, nose, or mane. |
| Output layer | Gives class probabilities, such as Lion 90%, Dog 5%, Cat 3%. |

### How Hidden Layers Learn

| Operation named in slide | Simple meaning |
|---|---|
| Matrix multiplication | Combines previous layer outputs with weights. |
| Activation functions | Add non-linearity so the network can learn complex patterns. |
| Weights and biases | Values adjusted during training to reduce errors. |

### Training a Deep Neural Network with Gradient Descent

| Step | Simple meaning |
|---|---|
| Start with random weights. | The model begins with rough guesses. |
| Predict output. | Example: it guesses "Lion." |
| Calculate loss. | Compare prediction with the correct label. |
| Adjust weights. | Use gradient descent to reduce future error. |
| Repeat many times. | With many examples, the model learns patterns. |

Gradient descent is described as the backbone of learning in neural networks.

### Where Deep Learning Does Well, and Some History

| Period / factor | Source detail |
|---|---|
| 1940s-1960s | Neural networks historically referred to as cybernetics. |
| 1980s-1990s | Referred to as connectionism. |
| Around 2006 | Neural networks became deeper and deep learning came into vogue. |
| Compute | Moore's Law, GPUs, ASICs. |
| Data | Data in a nice form, such as ImageNet. |
| Algorithms | Ideas such as backprop, CNN, LSTM. |
| Infrastructure | Linux, TCP/IP, Git, ROS, PR2, AWS, AMT, TensorFlow. |

### Neuron

The slides say the human brain has around 10 billion neurons, each connected on average to 10,000 other neurons. Neurons receive signals through synapses. When sufficiently activated, neurons "fire" by sending electrical signals to other neurons.

### Biological Neuron vs Artificial Neural Network Idea

| Biological part | Simple role | AI connection in slides |
|---|---|---|
| Dendrites | Receive signals. | Inputs. |
| Soma / cell body | Processes information. | Processing in artificial neuron. |
| Axon | Carries output. | Output. |
| Synapses | Points of connection between neurons. | Modeled by adjustable weights. |

### Neural Network Structure

| Layer / component | Simple meaning |
|---|---|
| Input layer | Receives data. |
| Hidden layers | Extract features and patterns. |
| Output layer | Produces final result. |
| Inputs x | Data values entering the neuron. |
| Weights w | Importance values for inputs. |
| Bias b | Extra adjustable value. |
| Activation function | Decides the neuron output. |

### Single Neuron Calculation

Source values:

| Item | Values |
|---|---|
| Inputs | x1=2, x2=1, x3=3, x4=1 |
| Weights | w1=0.3, w2=0.1, w3=0.4, w4=0.2 |
| Bias | b=-1.2 |

Calculation from the food freshness example:

| Step | Working |
|---|---|
| Weighted sum | z = (0.3 x 2) + (0.1 x 1) + (0.4 x 3) + (0.2 x 1) - 1.2 |
| Value | z = 0.6 + 0.1 + 1.2 + 0.2 - 1.2 = 0.9 |
| Activation rule | If z >= 0, output = 1. If z < 0, output = 0. |
| Result | Since z = 0.9, output = 1. |
| Food freshness status | Fresh. |

### Neurons, Feature Learning, and Layers of Abstraction

Feature learning means the network learns useful patterns layer by layer. In the visual example, early layers detect basic edges, middle layers detect parts such as eyes/nose/mouth, and higher layers detect a complete face.

| Level | What is detected |
|---|---|
| Low-level features | Edges and basic lines. |
| Mid-level features | Parts such as eyes and noses. |
| High-level features | Whole face or complete object. |

### Why Linear Models Do Not Work

The slides explain that simple template-like models average images in each class. This creates blurry templates and loses details such as orientation, color, and position.

| Linear/template problem | Simple meaning |
|---|---|
| No abstraction | Cannot understand different shapes or angles. |
| Blurry details | Important features disappear when images are averaged. |
| Not flexible | Cannot handle small differences, such as left vs right. |

Deep neural networks are better here because they learn layers of features instead of averaging everything into one blurry template.

### DNN

A deep neural network processes data hierarchically:

| Layer stage | What happens |
|---|---|
| Input layer | Raw pixel data enters. |
| Early hidden layers | Detect simple features such as diagonal lines or edges. |
| Middle hidden layers | Combine features into object parts, such as face-like shapes. |
| Deeper layers | Assemble parts into complete objects. |
| Output layer | Gives final classification such as face or cat. |

### Interpretability in DNNs

| Point | Simple meaning |
|---|---|
| Interpretability | Understanding how a model makes decisions. |
| DNN challenge | DNNs work well but can be hard to explain because they learn complex patterns through many layers. |
| Why it matters | In critical areas such as healthcare, people need to know why a decision was made. |
| Source conclusion | DNNs are powerful but not always interpretable; visualization tools and explainable AI help make decisions clearer. |

### Deep Learning Software Packages

The source lists TensorFlow, Torch, PyTorch, Caffe, Theano, and more. The point is that people rarely need to implement every part of neural networks from scratch.

### Convolutional Neural Networks (CNNs)

CNNs are designed for image input and are effective for computer vision. They are also used in deep reinforcement learning and mimic how biological visual systems process visual input.

### Recurrent Neural Networks (RNNs)

RNNs have built-in memory and suit language problems. They are also important in reinforcement learning because they help an agent keep track of what happened before, even when not everything is visible at once.

### DNN VS CNN VS RNN

| Model | Main idea | Best for | Limitation / special note |
|---|---|---|---|
| Deep Neural Network (DNN) | General-purpose neural network with many hidden layers and fully connected layers. | Tabular data, basic classification, regression. | Not good at image patterns or time sequences. |
| Convolutional Neural Network (CNN) | Specialized for images and spatial data using convolution layers. | Image classification, facial recognition, object detection. | Captures spatial features in pictures. |
| Recurrent Neural Network (RNN) | Specialized for sequential data and uses memory/loops. | Time series, language, speech, music. | Good for patterns over time, such as predicting next word. |

### Deep Learning Applications

| Application | Source example |
|---|---|
| Drug discovery | Predicting molecule bioactivity. |
| Photo/video tagging | Face and object recognition. |
| Search | Powering Google search results. |
| Language | Google Translate and natural language generation/understanding. |
| Robotics | Mars rover Curiosity selecting inspection-worthy soil targets. |
| Question answering | Facebook neural network with short-term memory answering Lord of the Rings plot questions. |
| Self-driving cars | Road signs, lanes, obstacles. |
| Art generation | Neural style mimics an artist's style and remixes another image. |

---

## chapt 12 Generative AI-sem 1 2024 2025.pdf

### GENERATIVE AI

This chapter covers generative AI, large language models, natural language processing, business applications, responsible AI, and discriminative versus generative models.

### Introduction to Generative AI

Generative AI is a subset of AI focused on creating new content such as text, images, and music. It enables creativity and automation.

| Capability | Source wording |
|---|---|
| Generates text | Creates written content. |
| Generates images | Creates visual content. |
| Generates code | Creates programming content. |
| Enhances efficiency | Helps different industries work faster. |
| Powered by LLMs | Uses advanced models to understand natural language. |

### Large Language Models (LLMs)

LLMs are advanced AI models trained on large text datasets. They use transformers for deep learning.

| LLM feature | Simple meaning |
|---|---|
| Language mastery | Learns grammar, patterns, and meaning. |
| Applications | Chatbots, content tools, virtual assistants. |
| Continual evolution | Research keeps expanding capabilities. |

### Natural Language Processing (NLP)

NLP is AI technology for understanding and generating human language. It goes beyond recognizing words by analyzing meaning and context.

| NLP application | Source example |
|---|---|
| Customer service | Chatbots. |
| Social media | Sentiment analysis. |
| Reporting | Automated report generation. |

### Business Applications of Generative AI and LLMs

| Business area | Applications from source |
|---|---|
| Marketing and sales | Personalized content creation, lead generation automation. |
| Customer service | 24/7 chatbots and email responses. |
| Operations | Automates reporting and optimizes processes. |
| HR | Candidate screening and onboarding. |
| R&D | Idea generation and data synthesis. |

### Ethical Considerations and Responsible AI

| Concern | Simple meaning |
|---|---|
| Bias mitigation | Reduce potential bias in AI outputs. |
| Transparency | Be open about how AI is used and what data it was trained on. |
| Accountability | Set clear responsibility for AI-generated content. |
| Human-in-the-loop | Keep human review and oversight for quality and accuracy. |

### Discriminative versus Generative

| Discriminative models | Generative models |
|---|---|
| Focus on classification. | Create new content. |
| Example: identify objects in a picture. | Example: generate a non-existing face. |
| Question: "Who is this in the picture?" | Request: "Generate a new face." |

### Generative AI Overview

Generative AI is trained on patterns and structures in input data, then generates outputs based on those patterns. The slide mentions ChatGPT, Bing Chat, Bard, DALL-E, and Midjourney. It also names transformer architecture as the backbone of modern natural language processing models, including BERT and GPT.

### Resources

| Resource listed in slides |
|---|
| Introduction to Generative AI from Google Cloud Skills Boost |
| Generative AI for Everyone from deeplearning.ai on Coursera |
| Introduction to Generative AI from Google Cloud Tech channel on YouTube |
| Introduction to large language models from Google Cloud Tech on YouTube |

---

## Chap13-Other AI Approaches.pdf

### CHAPTER 13 - Other AI approaches - Fuzzy Logic

This chapter focuses on uncertainty and fuzzy logic.

### Content

| Source page(s) | Topic covered |
|---|---|
| 1-4 | Introduction and uncertainty |
| 5-7 | Fuzzy logic definition and vague language examples |
| 8 | History |
| 9-13 | Crisp logic versus fuzzy logic and temperature examples |
| 14-15 | Human-like reasoning and fuzzy logic abilities |
| 16-19 | Fuzzy rules and linguistic variables |
| 20-24 | Air-conditioner, shower, and washing machine examples |
| 25-27 | Applications in consumer products, medicine, and information systems |

### Introduction

The world is uncertain and not always clear. The slides describe uncertainty as lack of exact knowledge that would let us reach a perfectly reliable conclusion.

### Forms of Uncertainty

| Form | Source example | Simple meaning |
|---|---|---|
| Imprecise measurements | Exact temperature may vary by tool or condition. | Measurements may not match perfectly. |
| Imprecise definitions | Whether a leader is "good" is subjective. | Words can depend on opinion. |
| Imprecise knowledge | Where is the pit? | We may not know exact facts. |
| Uncertain inferences | Rash after gardening probably means poison ivy. | A conclusion can be likely but not guaranteed. |

Information may be imperfect because it is inconsistent, incomplete, unsure, or all three.

### 🚨 EXAM TOPIC: Fuzzy Logic 🚨

Fuzzy logic was introduced by Lotfi Zadeh in 1965. It is a problem-solving method that uses human-language rules and handles uncertainty, vague criteria, and unclear values.

The key idea: not everything is only yes/no or true/false. Some things have degrees. For example, "cold" depends on what someone means by cold. A temperature might feel cold to one person but not to another.

### Fuzzy Logic Core Idea

| Idea | Simple explanation |
|---|---|
| Fuzziness | Something is not clear enough. |
| Fuzzy set | A set with fuzzy boundaries. |
| Degrees/scales | Things can be partly true, partly matching, or partly belonging. |
| Common sense | Experts often solve problems using approximate human reasoning. |

### Why Fuzzy Logic is Needed

Some questions have exact yes/no answers, such as "Do you need this book?" But many natural-language statements are vague:

| Vague statement from slides | Why it is fuzzy |
|---|---|
| He is quite tall. | "Quite tall" has no single exact boundary. |
| The student is intelligent. | Intelligence can be judged by degree. |
| Today is a very hot day. | "Very hot" depends on a scale and context. |

Fuzzy logic helps computers handle these human-like vague terms.

### History

| Year | Source milestone |
|---|---|
| 1965 | Fuzzy Sets, Lotfi Zadeh seminar |
| 1966 | Fuzzy Logic, P. Marinos, Bell Labs |
| 1972 | Fuzzy Measure, M. Sugeno, TIT |
| 1974 | Fuzzy Logic Control, E.H. Mamdani |
| 1980 | Control of Cement Kiln, F.L. Smidt, Denmark |
| 1987 | Sendai Subway Train Experiment, Hitachi |
| 1988 | Stock Trading Expert System, Yamaichi |
| 1989 | LIFE, Lab for International Fuzzy Engineering |

### Differences between Fuzzy Logic and Crisp Logic

| Crisp Logic | Fuzzy Logic |
|---|---|
| Precise properties. | Imprecise properties. |
| Full membership. | Partial membership. |
| YES or NO. | YES moving gradually toward NO. |
| TRUE or FALSE. | TRUE moving gradually toward FALSE. |
| 1 or 0. | 1 moving gradually toward 0. |
| Crisp sets. | Fuzzy sets. |
| "She is 18 years old." | "She is about 18 years old." |
| "Man 1.6m tall." | "Man about 1.6m tall." |

### Degree of Membership: "Tall" Man Example

In crisp logic, a numeric height returns only yes or no. In fuzzy logic, a height can belong to the idea of "tall" by a degree.

| Height (cm) | Crisp value | Fuzzy value |
|---:|---:|---:|
| 208 | 1 | 1.00 |
| 205 | 1 | 1.00 |
| 198 | 1 | 0.98 |
| 181 | 1 | 0.82 |
| 179 | 0 | 0.78 |
| 172 | 0 | 0.24 |
| 167 | 0 | 0.15 |
| 158 | 0 | 0.06 |
| 155 | 0 | 0.01 |
| 152 | 0 | 0.00 |

Simple exam reading: crisp logic suddenly changes from 1 to 0 at a boundary. Fuzzy logic changes gradually. A person at 179 cm can still be somewhat tall, even if crisp logic says 0.

### Boolean Logic vs Fuzzy Logic for Temperature

| Boolean / crisp temperature | Fuzzy temperature |
|---|---|
| Uses two values. | Uses continuous values. |
| Temperature is either Hot or Cold. | Temperature can be Extremely Cold, Cold, Quite Cold, Quite Hot, Hot, Extremely Hot. |
| Sharp boundary. | Smooth shift between meanings. |

### How Fuzzy Logic Resembles Human Intelligence

| Human-like ability | Simple meaning |
|---|---|
| Handles imprecision and uncertainty. | Can work when facts are not perfectly clear. |
| Clustering and classification. | Divides situations into parts. |
| Ranking importance and alternatives. | Focuses on parts with different levels of importance. |
| Combining parts into a whole. | Builds an integrated decision. |

### Fuzzy Logic is Able To

| Ability / benefit | Simple meaning |
|---|---|
| Represent vague language naturally. | Handles words like cold, hot, tall, medium. |
| Enrich, not replace, crisp sets. | Adds gradual meaning instead of removing exact logic. |
| Allow flexible engineering design. | Helps design systems that handle real-world variation. |
| Improve model performance. | Source examples: save power consumption, increase lifespan. |
| Implement simply and often work. | Can be practical and effective. |

### Fuzzy Rule

A fuzzy rule has the form:

| IF part | THEN part |
|---|---|
| x is A | y is B |

In the slides, x and y are linguistic variables, while A and B are linguistic values determined by fuzzy sets.

### Linguistic Variable

A linguistic variable is a variable whose values are words or sentences in natural or artificial language.

| Linguistic variable | Possible linguistic values from source |
|---|---|
| Speed | slow, fast, very fast |
| Driving_speed | slow, medium, fast |
| Stop_distance | short, medium, long |

It is a mathematical way to represent semantic concepts with several terms and degrees of membership.

### Fuzzy Rules: Driving Example

| Rule | Meaning |
|---|---|
| IF driving_speed is fast THEN stop_distance is long | Faster driving needs longer stopping distance. |
| IF driving_speed is slow THEN stop_distance is short | Slower driving needs shorter stopping distance. |

The source says driving_speed can range from 0 to 220 km/h and include fuzzy sets such as slow, medium, and fast. Stop_distance can range from 0 to 300m and include short, medium, and long.

### Fuzzy Rules: Project and Tip Examples

| Conditions | Result |
|---|---|
| project_duration short AND project_staffing medium AND project_funding inadequate | risk high |
| project_duration long AND project_staffing large AND project_funding adequate | risk low |
| project_duration short AND project_staffing large AND project_funding adequate | risk medium |
| service excellent OR food delicious | tip generous |

### Air-Conditioner Example

Problem: set a room temperature so it is not too hot or too cold, including when there are many or very few students in the room.

| Temperature condition | Fan speed action |
|---|---|
| IF temperature is cold | set fan_speed to zero |
| IF temperature is cool | set fan_speed to low |
| IF temperature is warm | set fan_speed to medium |
| IF temperature is hot | set fan_speed to high |

The membership function has fuzzy temperature sets: Cold, Cool, Warm, Hot. It expresses temperature changes smoothly and naturally.

### Bathroom Shower Fuzzy Rules

| Water volume | Temperature setting |
|---|---|
| Full | Hot |
| Half | Warm |
| Quarter | Cold |

### Washing Machine Fuzzy Rules

| Load weight | Water amount |
|---|---|
| Heavy | Full / maximum |
| Not_so_heavy | Three_quarter |
| Not_so_light | Half |
| Light | Quarter / minimum |
| Medium | Regular |

### Fuzzy Logic Applications

Fuzzy logic decision making uses fuzzy set operations, if-then-else statements, and logical operators. It resembles human decision making because it works from approximate data and can find precise solutions.

| Consumer product / area | Source examples |
|---|---|
| Home devices | Electrical shower unit, air conditioner, washing machines, refrigerators, television, rice cooker |
| Vehicles | Brake control |
| Medicine | Diagnosis-related decision making |
| Information systems | Information retrieval and database management |

### Fuzzy Decision Making in Medicine

| Medical diagnosis aspect | Simple meaning |
|---|---|
| Relative importance of symptoms | Some symptoms matter more than others. |
| Different disease stages | Symptoms may vary by stage. |
| Relations between diseases | Diseases can relate to each other. |
| Hypothesis formation | Forming possible explanations. |
| Preliminary diagnosis | Early diagnosis stage. |
| Final diagnosis | Final decision in diagnosis process. |

### Fuzzy Decision Making in Information System

| Benefit | Simple meaning |
|---|---|
| Soft requests | Allows searches that are not perfectly exact. |
| Ordering results | Items can more or less satisfy a request. |
| Imprecise database information | Can handle vague, uncertain, or imprecise information. |
