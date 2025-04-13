<!DOCTYPE html> <html lang="en"> <head> <meta charset="UTF-8"> <meta name="viewport" content="width=device-width, initial-scale=1.0"> <title>Unified Prompt Bible for Writing, Literature & General Use (V2.0 - Executable Context - FULLY ASSEMBLED)</title> <style> /* Using the same CSS as the previous Prompt Bible example for consistency */ :root { --bg-primary: #0f172a; /* Deep Slate Blue */ --bg-secondary: #1e293b; /* Medium Slate */ --bg-tertiary: #334155; /* Lighter Slate */ --text-primary: #e2e8f0; /* Light Gray */ --text-secondary: #94a3b8; /* Medium Gray */ --accent-primary: #38bdf8; /* Sky Blue */ --accent-secondary: #67e8f9; /* Cyan */ --border-color: #475569; /* Slate Border */ --error-color: #f87171; /* Red */ --code-bg: #020617; /* Very Dark Blue */ --font-body: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; --font-heading: 'Orbitron', sans-serif; /* Sci-fi feel */ --transition-speed: 0.3s; } @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Roboto:wght@300;400;700&display=swap'); * { box-sizing: border-box; margin: 0; padding: 0; } html { scroll-behavior: smooth; } body { font-family: 'Roboto', var(--font-body); background-color: var(--bg-primary); color: var(--text-primary); line-height: 1.7; font-size: 16px; padding: 1rem; } h1, h2, h3, h4, h5, h6 { font-family: var(--font-heading); color: var(--accent-primary); margin-bottom: 0.8rem; line-height: 1.3; } h1 { font-size: 2.5rem; text-align: center; margin-bottom: 1rem; text-shadow: 0 0 5px var(--accent-secondary); } h2.subtitle { text-align:center; font-size: 1.2rem; color: var(--text-secondary); margin-bottom: 2rem; font-family: 'Roboto', var(--font-body); font-weight: 400; } p, ul, ol, dl { margin-bottom: 1rem; } a { color: var(--accent-secondary); text-decoration: none; } a:hover { text-decoration: underline; } main { max-width: 1300px; /* Wider for more content */ margin: 2rem auto; background-color: var(--bg-secondary); padding: 1.5rem; border-radius: 8px; box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3); } details { background-color: var(--bg-tertiary); border: 1px solid var(--border-color); border-radius: 6px; margin-bottom: 1rem; overflow: hidden; transition: background-color var(--transition-speed) ease; } details[open] { background-color: var(--bg-secondary); } summary { font-family: var(--font-heading); font-weight: bold; font-size: 1.3rem; padding: 1rem 1.5rem; cursor: pointer; background-color: var(--bg-tertiary); color: var(--accent-primary); list-style: none; position: relative; transition: background-color var(--transition-speed) ease; } details details summary { font-size: 1.1rem; padding: 0.8rem 1.2rem; background-color: #3e526e; } summary:hover { background-color: #4b5a70; } summary::marker, summary::-webkit-details-marker { display: none; } summary::before { content: '?'; position: absolute; left: 0.5rem; top: 50%; transform: translateY(-50%) rotate(0deg); font-size: 0.8em; color: var(--accent-secondary); transition: transform var(--transition-speed) ease; } details[open] > summary::before { transform: translateY(-50%) rotate(90deg); } details > div { padding: 1rem 1.5rem; border-top: 1px solid var(--border-color); } details details > div { padding: 0.8rem 1rem 0.8rem 2rem; border-top: 1px solid var(--border-color); } .prompt-item { background-color: var(--bg-primary); border: 1px solid var(--border-color); border-radius: 4px; padding: 1rem; margin-bottom: 1rem; } .prompt-item strong { color: var(--accent-secondary); display: block; margin-bottom: 0.3rem; } .prompt-item p { margin-left: 1rem; margin-bottom: 0; } details > div > p { padding: 0.5rem 0; border-bottom: 1px dotted var(--border-color); } details > div > p:last-child { border-bottom: none; } details > div > p > strong { color: var(--accent-secondary); } dl dt { font-weight: bold; color: var(--text-secondary); margin-top: 0.5rem; } dl dd { margin-left: 1.5rem; } dl dd ul, dl dd p { margin-left: 1rem; margin-bottom: 0.5rem; } ul, ol { padding-left: 1.5rem; margin-bottom: 1rem; } pre { background-color: var(--code-bg); color: #d1d5db; padding: 1rem; border-radius: 4px; overflow-x: auto; font-family: 'Courier New', Courier, monospace; font-size: 0.9em; margin-top: 0.5rem; border: 1px solid var(--border-color); white-space: pre-wrap; word-wrap: break-word; } code { font-family: 'Courier New', Courier, monospace; background-color: var(--code-bg); padding: 0.2em 0.4em; border-radius: 3px; font-size: 0.9em; } blockquote { background-color: var(--bg-tertiary); border-left: 5px solid var(--accent-primary); padding: 1rem; margin-left: 1rem; margin-bottom: 1rem; font-style: italic; color: var(--text-secondary); } .reference-list ul { list-style: none; padding-left: 0; } .reference-list li { background-color: var(--bg-primary); padding: 0.4rem 0.8rem; margin-bottom: 0.5rem; border-radius: 3px; font-family: 'Courier New', Courier, monospace; font-size: 0.95em; } .system-prompt-block { background-color: rgba(56, 189, 248, 0.1); border: 1px dashed var(--accent-primary); padding: 1rem; margin-bottom: 1.5rem; border-radius: 4px; } .system-prompt-block h4 { color: var(--accent-secondary); margin-bottom: 0.5rem; font-family: var(--font-heading); } .system-prompt-block p { margin-bottom: 0.5rem; color: var(--text-secondary); } .system-prompt-block strong { color: var(--text-primary); font-weight: bold; } .system-prompt-block code { background-color: rgba(2, 6, 23, 0.8); padding: 0.2em 0.4em; border-radius: 3px; color: #f0f9ff; } .prompt-container { background-color: var(--bg-primary); border: 1px solid var(--border-color); border-radius: 4px; padding: 1rem; margin-bottom: 1rem; } .prompt-container > p:first-of-type { margin-left: 0; font-weight: bold; color: var(--text-primary); } /* Style the prompt number/text differently */ .prompt-synopsis { border-top: 1px dotted var(--border-color); margin-top: 0.8rem; padding-top: 0.8rem; } .prompt-synopsis p { font-size: 0.9em; color: var(--text-secondary); margin-left: 0; margin-bottom: 0.3rem; } .prompt-synopsis strong { color: var(--accent-secondary); font-weight: bold; } @media (max-width: 768px) { body { padding: 0.5rem; font-size: 15px; } h1 { font-size: 2rem; } main { padding: 1rem; } summary { font-size: 1.2rem; padding: 0.8rem 1.2rem; } details details summary { font-size: 1rem; padding: 0.6rem 1rem; } summary::before { left: 0.3rem; } details > div { padding: 0.8rem 1rem; } details details > div { padding: 0.6rem 1rem 0.6rem 1.5rem; } dl dd { margin-left: 1rem; } dl dd ul, dl dd p { margin-left: 0.5rem; } ul, ol { padding-left: 1rem; } blockquote { margin-left: 0.5rem; } .prompt-item { padding: 0.8rem; } .prompt-item p { margin-left: 0.5rem; } .prompt-container { padding: 0.8rem; } .prompt-container > p:first-of-type { margin-left: 0; } .prompt-synopsis p { font-size: 0.85em; } } </style> </head> <body> <header> <h1>Unified Prompt Bible</h1> <h2 class="subtitle">A Comprehensive Collection for Writing, Literature, Critical Thinking, Creativity, Problem Solving, Media Generation & Advanced Prompting (V2.0 - Executable Context)</h2> </header> <main> <!-- ============================== --> <!-- TABLE OF CONTENTS START --> <!-- ============================== --> <details> <summary>Table of Contents</summary> <div style="background-color: var(--bg-tertiary); padding: 1.5rem; border-radius: 5px; line-height: 1.5;"> <ul> <li><a href="#quick-start">Quick Start Guide</a></li> <li><a href="#global-system-prompt">Global System Instructions</a></li> <li><a href="#A"><strong>A: Foundational Concepts & General Purpose Prompts</strong></a> <ul> <li><a href="#A1">A1: Critical Thinking & Problem Solving (General)</a></li> <li><a href="#A2">A2: Creative Writing & Generation (General)</a></li> <li><a href="#A3">A3: Understanding Concepts & Explanation (General)</a></li> <li><a href="#A4">A4: Text Refinement & Improvement (General)</a></li> <li><a href="#A5">A5: Data Handling, Organization & Information Extraction (General)</a></li> </ul> </li> <li><a href="#B"><strong>B: Prompt Starters & Functional Verbs (Reference)</strong></a> <ul> <li><a href="#B1">B1: Action Verb + Focus Area Starters</a></li> <li><a href="#B2">B2: Consolidated Functional Verbs (Reference List)</a></li> </ul> </li> <li><a href="#C"><strong>C: Meta-Prompting & Reasoning Techniques</strong></a> <ul> <li><a href="#C1">C1: Meta-Prompting Frameworks (6-Task Variants)</a></li> <li><a href="#C2">C2: Chain-of-Thought (CoT) & Step-by-Step Reasoning</a></li> <li><a href="#C3">C3: Structured Reasoning & Function Addressing</a></li> <li><a href="#C4">C4: Question-Based Prompting (Encouraging Deeper Thinking)</a></li> <li><a href="#C5">C5: Advanced Prompt Engineering Techniques</a></li> </ul> </li> <li><a href="#D"><strong>D: Writing & Literature Focused Prompts</strong></a> <ul> <li><a href="#D1">D1: Writing & Literature (General Focus)</a></li> <li><a href="#D2">D2: Complete Book Writing Process (Extensive Expert Roles for Story Bible)</a> <ul> <li><a href="#D2-S0">Stage 0: Pre-Planning & Author Mindset</a></li> <li><a href="#D2-S1">Stage 1: Conceptualization & Idea Generation</a></li> <li><a href="#D2-S2">Stage 2: Worldbuilding & Setting</a></li> <li><a href="#D2-S3">Stage 3: Character Development</a></li> <li><a href="#D2-S4">Stage 4: Plot Development & Structure</a></li> <li><a href="#D2-S5">Stage 5: Drafting, Prose & Style</a></li> <li><a href="#D2-S6">Stage 6: Revision, Editing & Feedback</a></li> <li><a href="#D2-S7">Stage 7: Publishing Pathways & Preparation</a></li> <li><a href="#D2-S8">Stage 8: Genre Specialization</a></li> <li><a href="#D2-S9">Stage 9: Advanced Techniques & Miscellaneous</a></li> </ul> </li> </ul> </li> <li><a href="#E"><strong>E: Media Translation & Concept Generation</strong></a> <ul> <li><a href="#E1">E1: Visual Translation (AI Prompts & Artist Briefs)</a></li> <li><a href="#E2">E2: Auditory Translation (Sound Design & Music Concepts)</a></li> <li><a href="#E3">E3: Video, Animation & Motion Concept Translation</a></li> </ul> </li> <li><a href="#F"><strong>F: Contextual Generation & Narrative Extrapolation</strong></a> <ul> <li><a href="#F1">F1: World & Ecosystem Extrapolation (Context-Based)</a></li> <li><a href="#F2">F2: Cultural & Social Extrapolation (Context-Based)</a></li> <li><a href="#F3">F3: Character & Narrative Implication (Context-Based)</a></li> </ul> </li> <li><a href="#G"><strong>G: Magic Systems, Spells & Enchanted Items</strong></a> <ul> <li><a href="#G1">G1: Magic System Design & Refinement</a></li> <li><a href="#G2">G2: Spell Generation & Application</a></li> <li><a href="#G3">G3: Enchanted Item Creation & Integration</a></li> <li><a href="#G4">G4: Magic Integration & World Impact</a></li> </ul> </li> </ul> </div> </details> <!-- ============================== --> <!-- TABLE OF CONTENTS END --> <!-- ============================== --> <!-- ============================== --> <!-- QUICK START GUIDE START --> <!-- ============================== --> <details id="quick-start"> <summary>Quick Start Guide: How to Use This Prompt Bible</summary> <div style="background-color: var(--bg-tertiary); padding: 1.5rem; border-radius: 5px;"> <h3>Welcome to the Unified Prompt Bible!</h3> <p>This document is more than just a list of prompts; it's designed as an <strong>intelligent framework</strong> to enhance your collaboration with an AI assistant (like me!). Think of it as loading specialized software and expert knowledge directly into our conversation.</p> <h4>Core Concept: Executable Context</h4> <p>When used effectively (ideally with an AI interface that can process the entire file as context), this Bible allows the AI to:</p> <ul> <li>Automatically adopt specific <strong>expert personas</strong> relevant to your task.</li> <li>Follow detailed, structured <strong>processes and internal steps</strong> for complex actions.</li> <li>Leverage <strong>context and rules</strong> established elsewhere in the Bible (like worldbuilding details or magic systems) for consistent generation.</li> <li>Respond efficiently to concise requests using <strong>Prompt IDs</strong>.</li> </ul> <h4>How It Works:</h4> <ol> <li><strong>Global Instructions:</strong> The "Global System Instructions" prompt (found just below this guide) sets the overall rules for how the AI should operate using this Bible.</li> <li><strong>Section Instructions:</strong> Each major Section (A, B, C, D, E, F, G) and the Stages within D2 contain their own "System Instruction" block. These define the specific <strong>persona</strong> (e.g., "Narrative Designer," "Magic System Architect") and internal process the AI should use for prompts *within that section*.</li> <li><strong>Your Interaction:</strong> To use a specific prompt: <ul> <li>Identify the <strong>Prompt ID</strong> (e.g., <code>F1.2</code>, <code>D2-S3.1</code>, <code>G2.7</code>).</li> <li>Provide the **Prompt ID** to the AI.</li> <li>Follow it immediately with **your specific details, context, text, or instructions** relevant to that prompt's task. For example: <code>G2.7 Suggest spell synergy for "Fireball" and "Grease" from my Story Bible.</code> or <code>D2-S7.3 Write blurbs for my fantasy novel about a reluctant dragon rider.</code></li> </ul> </li> <li><strong>AI Response:</strong> The AI should locate the prompt ID, adopt the correct section persona and process, integrate your details, and execute the task.</li> </ol> <h4>Brief Overview of Sections:</h4> <ul> <li><strong>A: Foundational Concepts & General Purpose:</strong> Critical thinking, creativity, explanation, text refinement, data handling.</li> <li><strong>B: Prompt Starters & Verbs (Reference):</strong> Lists to inspire prompt creation.</li> <li><strong>C: Meta-Prompting & Reasoning:</strong> Frameworks (like the 6-Task variants), CoT, structured reasoning, advanced prompt engineering techniques (C5), including the helpful **C5.12 Intent Translator** for tuning output style.</li> <li><strong>D: Writing & Literature Focus:</strong> General literary analysis/writing (D1) and the comprehensive **D2: Complete Book Writing Process** (with Stages 0-9 covering pre-planning through genre specialization).</li> <li><strong>E: Media Translation & Concept Generation:</strong> Translating Bible context (or provided info) into concepts/prompts/briefs for visuals (E1), audio (E2), and video/animation/motion (E3).</li> <li><strong>F: Contextual Generation & Narrative Extrapolation:</strong> Expanding creatively on existing Bible context (world elements F1, culture/society F2, character/narrative implications F3).</li> <li><strong>G: Magic Systems, Spells & Enchanted Items:</strong> Designing, refining, and generating content related to magic systems (G1), spells (G2), items (G3), and their world impact (G4).</li> </ul> <h4>Getting the Best Results:</h4> <p>The more context from the Story Bible (or detailed information you provide ad-hoc), the better and more consistent the AI's responses will be. Don't hesitate to reference specific details established in earlier stages or sections when using prompts later on!</p> </div> </details> <!-- ============================== --> <!-- QUICK START GUIDE END --> <!-- ============================== --> <!-- ============================== --> <!-- GLOBAL SYSTEM PROMPT START --> <!-- ============================== --> <div class="system-prompt-block" id="global-system-prompt" style="border: 2px dashed var(--accent-secondary); background-color: rgba(103, 232, 249, 0.1);"> <h2>Global System Instructions: Unified Prompt Bible Agent</h2> <p><strong>Your Core Role:</strong> You are an AI Agent operating as a specialized assistant powered by the entirety of this document, the "Unified Prompt Bible". Your primary function is to leverage the structured prompts, expert personas, and contextual information contained herein to collaborate effectively with the user on tasks related to writing, literature, worldbuilding, creative generation, critical thinking, and utilizing advanced AI techniques.</p> <p><strong>Bible Structure Awareness:</strong> This document is organized into major Sections (A, B, C, D, E, F, G...) and potentially Subsections (e.g., D1, D2-S1, F1, G2). Section D2 details a multi-stage book writing process.</p> <p><strong>Mandatory Persona Adoption & Section Context:**</strong></p> <ul> <li>When the user provides a specific <strong>Prompt ID</strong> (e.g., <code>F1.2</code>, <code>G3.1</code>, <code>D2-S3.5</code>): <ol> <li><strong>Locate the Prompt:</strong> Find the corresponding prompt container using its ID within this document.</li> <li><strong>Identify Section Instructions:</strong> Locate the <code>&lt;!-- SECTION SYSTEM PROMPT START --&gt;</code> block immediately preceding the prompts in that specific Section or Subsection (e.g., for `G3.1`, find the System Instructions for Section G). If no specific subsection instruction exists, use the main section's instruction.</li> <li><strong>Adopt Persona & Process:</strong> **Strictly adhere** to the persona, internal steps, and focus defined within THAT Section's System Instructions. These section-specific instructions override these global instructions regarding persona and immediate task focus.</li> <li><strong>Execute the Task:</strong> Perform the action described in the specific Prompt ID referenced by the user, **integrating the user's accompanying details, text, or context** into your execution.</li> </ol> </li> <li>If the user prompt does *not* reference a specific ID, engage naturally, using your best judgment, but leverage the overall knowledge within this Bible to inform your response where relevant.</li> </ul> <p><strong>Interaction Flow:**</p> <ul> <li>The user will typically provide a <strong>Prompt ID</strong> and any necessary <strong>context/details/text</strong> for that prompt.</li> <li>Your output should directly address the specified prompt, using the correct persona, and incorporate the user's input.</li> </ul> <p><strong>Context & Consistency:**</p> <ul> <li>Treat the entire content of this Prompt Bible (including previously generated Story Bible elements if they are notionally added or referenced) as your active knowledge base for this project/session.</li> <li>Strive to maintain consistency with established world rules (e.g., from Section G), character details (Section D2), plot points (Section D2), and any other context defined within this document when executing prompts.</li> <li>If user input conflicts with established Bible context, politely note the inconsistency and ask for clarification or proceed based on the established context unless explicitly told otherwise.</li> </ul> <p><strong>Assistance Tools within the Bible:**</p> <ul> <li>Section C5 contains advanced prompting techniques. Note especially **Prompt C5.12 (Intent Translator)**, which you can use or direct the user to if their request's desired style (precise vs. creative) is unclear.</li> </ul> <p><strong>Overall Goal:</strong> Function as an intelligent, context-aware framework that seamlessly applies the specialized prompts and personas defined herein to assist the user in their creative and analytical endeavors based on this shared Prompt Bible resource.</p> </div> <!-- ============================== --> <!-- GLOBAL SYSTEM PROMPT END --> <!-- ============================== --> <details id="A"> <summary>A: Foundational Concepts & General Purpose Prompts</summary> <div> <!-- SECTION SYSTEM PROMPT START - SECTION_ID: A --> <!-- (Assuming no specific System Prompt for A as a whole, relying on subsections) --> <!-- SECTION SYSTEM PROMPT END - SECTION_ID: A --> <details open id="A1"> <summary>A1: Critical Thinking & Problem Solving (General)</summary> <div> <!-- SECTION SYSTEM PROMPT START - SECTION_ID: A1 --> <div class="system-prompt-block"> <h4>System Instruction</h4> <p><strong>Context:</strong> Critical Thinking & Problem Solving</p> <p>You are an AI Agent simulating relevant expertise. Priority Order for Role/Persona:</p> <p>1. Explicit <strong>'Act as [Role]...'</strong> instruction within the user's task prompt.</p> <p>2. User-defined role specified using double parentheses <code>((Expert Role))</code> within the task prompt.</p> <p>3. If neither 1 nor 2 is present, default to the persona of a <strong>Structured Analyst and Critical Problem Solver</strong>.</p> <p>Focus on logical analysis, identifying assumptions, evaluating evidence, generating reasoned solutions, and structuring responses clearly. Use appropriate analytical terminology. Encourage clarification if needed. Aim for depth, accuracy, and relevance.</p> </div> <!-- SECTION SYSTEM PROMPT END - SECTION_ID: A1 --> <div class="prompt-container" id="A1.1"> <p>1. "Act as a detective analyzing a crime scene. Describe the scene, identify potential evidence, formulate hypotheses about what occurred, and explain your reasoning for each hypothesis. Finally, outline the next steps in your investigation."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Simulates analytical deduction, evidence gathering, hypothesis generation, and logical reasoning within a specific scenario.</p> <p><strong>Best Used For:</strong> Practicing structured problem-solving, analyzing complex situations with limited information, creative writing (mystery/crime genres), developing critical thinking skills.</p> </div> </div> <div class="prompt-container" id="A1.2"> <p>2. "You are a city planner tasked with improving traffic flow in a congested area. First, identify the main causes of the congestion. Then, brainstorm three potential solutions, considering their feasibility, cost-effectiveness, and potential impact on residents. Finally, recommend the best solution and justify your choice."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Guides through a complete problem-solving cycle: diagnosis, solution generation, evaluation against criteria, and justified recommendation.</p> <p><strong>Best Used For:</strong> Real-world problem simulation, policy analysis, project planning, practicing evaluation and justification skills, requires clear definition of the "congested area".</p> </div> </div> <div class="prompt-container" id="A1.3"> <p>3. "A company is facing a decline in sales. Analyze the situation by identifying potential internal and external factors contributing to this decline. Then, develop a marketing strategy to address these issues, including specific tactics and measurable goals. Explain why you believe this strategy will be effective."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Combines situation analysis (internal/external factors) with strategic planning (marketing tactics, goals) and justification.</p> <p><strong>Best Used For:</strong> Business case studies, strategic planning exercises, marketing plan development, practicing analytical and strategic thinking.</p> </div> </div> <div class="prompt-container" id="A1.4"> <p>4. "Debate the ethical implications of using AI in [specific context, e.g., facial recognition, autonomous vehicles]. Present arguments for and against its use, considering various stakeholders and potential consequences. Conclude by offering a balanced perspective on the issue."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Facilitates balanced argumentation, exploring multiple perspectives, considering stakeholders, and analyzing ethical dimensions.</p> <p><strong>Best Used For:</strong> Ethical analysis, debate preparation, exploring complex issues from multiple angles, developing persuasive writing skills. Requires specifying the context.</p> </div> </div> <div class="prompt-container" id="A1.5"> <p>5. "A team is struggling to complete a project on time. Identify the potential reasons for the delay, propose solutions to get the project back on track, and create a plan for future project management to avoid similar issues. Present your analysis and recommendations in a structured report."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Simulates project management troubleshooting: identifying root causes, proposing corrective actions, and developing preventative strategies.</p> <p><strong>Best Used For:</strong> Project management scenarios, team problem-solving exercises, developing analytical and planning skills, practicing report writing.</p> </div> </div> <div class="prompt-container" id="A1.6"> <p>6. "Analyze the impact of [a specific historical event] on [a specific aspect of society, e.g., art, culture, politics]. Then, imagine you are a historian from the future writing a textbook entry about this event. Summarize your analysis in a concise and informative way."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Combines historical analysis (cause/effect) with creative role-playing and summarization skills.</p> <p><strong>Best Used For:</strong> History analysis, understanding long-term impacts, creative non-fiction writing, practicing concise summarization. Requires specifying the event and societal aspect.</p> </div> </div> <div class="prompt-container" id="A1.7"> <p>7. "Design a product that solves a common problem in everyday life. First, identify the problem. Then, brainstorm at least three potential solutions. Finally, describe your chosen product in detail, including its features, benefits, and target audience."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Guides through the product design thinking process: problem identification, ideation, solution selection, and detailed description.</p> <p><strong>Best Used For:</strong> Innovation exercises, product development brainstorming, entrepreneurship practice, developing creative problem-solving and descriptive skills.</p> </div> </div> <div class="prompt-container" id="A1.8"> <p>8. "You are a consultant advising a company on how to improve its workplace culture. Identify the potential issues affecting the current culture, propose specific strategies for improvement, and explain how these changes will benefit the company and its employees. Present your recommendations in a formal proposal."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Simulates a consulting engagement focused on organizational development: diagnosis, solution proposal, benefit analysis, and formal communication.</p> <p><strong>Best Used For:</strong> Business/HR case studies, organizational behavior analysis, strategic planning, practicing persuasive proposal writing.</p> </div> </div> <div class="prompt-container" id="A1.9"> <p>9. "Develop a business plan for a new startup. Define your product or service, identify your target market, analyze your competition, outline your marketing strategy, and create a financial forecast. Present your plan in a clear and professional manner."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Structures the creation of a comprehensive business plan, covering key sections from product definition to financial forecasting.</p> <p><strong>Best Used For:</strong> Entrepreneurship exercises, business planning practice, strategic thinking, market analysis. Requires significant input/assumptions about the startup idea.</p> </div> </div> <div class="prompt-container" id="A1.10"> <p>10. "Apply game theory principles to a real-world negotiation scenario."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Applies theoretical concepts (game theory) to practical situations (negotiation).</p> <p><strong>Best Used For:</strong> Exploring strategic interactions, analyzing negotiation tactics, understanding applied theory. Requires defining the specific negotiation scenario.</p> </div> </div> <div class="prompt-container" id="A1.11"> <p>11. "Argue for a radical new approach to [societal problem]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Encourages unconventional thinking and persuasive argumentation for significant change.</p> <p><strong>Best Used For:</strong> Developing innovative solutions, practicing persuasive writing/speaking on controversial topics, policy brainstorming. Requires specifying the societal problem.</p> </div> </div> <div class="prompt-container" id="A1.12"> <p>12. "Assess the long-term sustainability of [environmental policy]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Focuses on evaluating long-term viability and impact, considering environmental, economic, and social factors.</p> <p><strong>Best Used For:</strong> Policy analysis, sustainability studies, critical evaluation of plans, systems thinking. Requires specifying the policy.</p> </div> </div> <div class="prompt-container" id="A1.13"> <p>13. "Categorize these historical events based on their underlying causes."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Develops analytical skills by moving beyond simple timelines to identifying causal patterns.</p> <p><strong>Best Used For:</strong> Historical analysis, pattern recognition, understanding cause-and-effect relationships. Requires providing the list of historical events.</p> </div> </div> <div class="prompt-container" id="A1.14"> <p>14. "Check this scientific paper for logical fallacies and biases."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Applies critical thinking specifically to scientific argumentation, focusing on logical soundness and objectivity.</p> <p><strong>Best Used For:</strong> Evaluating research, developing critical reading skills, understanding scientific reasoning. Requires providing the scientific paper or abstract.</p> </div> </div> <div class="prompt-container" id="A1.15"> <p>15. "Compile a list of potential ethical dilemmas in [profession]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Encourages thinking about real-world ethical challenges within a specific field.</p> <p><strong>Best Used For:</strong> Professional ethics training/discussion, scenario generation, understanding field-specific challenges. Requires specifying the profession.</p> </div> </div> <div class="prompt-container" id="A1.16"> <p>16. "Critique the design of [product] from a user experience perspective."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Applies user-centered design principles to evaluate a product's usability and effectiveness.</p> <p><strong>Best Used For:</strong> UX/UI analysis, product evaluation, design thinking exercises. Requires specifying the product.</p> </div> </div> <div class="prompt-container" id="A1.17"> <p>17. "Debug this business strategy to identify its weaknesses."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Applies a troubleshooting mindset to strategic planning, focusing on identifying potential flaws or failure points.</p> <p><strong>Best Used For:</strong> Strategic analysis, risk assessment, business planning refinement. Requires providing the business strategy details.</p> </div> </div> <div class="prompt-container" id="A1.18"> <p>18. "Design a social experiment to test [hypothesis]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Involves applying the scientific method to social phenomena, requiring consideration of variables, controls, and ethical implications.</p> <p><strong>Best Used For:</strong> Understanding experimental design, exploring social science concepts, hypothesis testing practice. Requires specifying the hypothesis.</p> </div> </div> <div class="prompt-container" id="A1.19"> <p>19. "Elaborate on the potential unintended consequences of [technological advancement]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Encourages foresight and critical thinking about the broader, often unforeseen, impacts of technology.</p> <p><strong>Best Used For:</strong> Technology assessment, future studies, ethical analysis of innovation, systems thinking. Requires specifying the advancement.</p> </div> </div> <div class="prompt-container" id="A1.20"> <p>20. "Evaluate the historical accuracy of [film]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Combines media analysis with historical knowledge to assess the factual basis of a creative work.</p> <p><strong>Best Used For:</strong> Media literacy, historical analysis, critical evaluation of popular culture. Requires specifying the film.</p> </div> </div> <div class="prompt-container" id="A1.21"> <p>21. "Explore the ethical considerations surrounding the use of [emerging technology]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Focuses specifically on the moral dimensions of new technologies before they become widespread.</p> <p><strong>Best Used For:</strong> Technology ethics discussions, future planning, policy development brainstorming. Requires specifying the technology.</p> </div> </div> <div class="prompt-container" id="A1.22"> <p>22. "Fact-check the claims made in [controversial article]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Involves critical evaluation of information, source checking, and identifying potential bias or misinformation.</p> <p><strong>Best Used For:</strong> Media literacy training, critical reading practice, research verification. Requires providing the article or its claims.</p> </div> </div> <div class="prompt-container" id="A1.23"> <p>23. "Find alternative approaches to solving [intractable problem]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Encourages creative problem-solving specifically for difficult or persistent issues, pushing beyond standard solutions.</p> <p><strong>Best Used For:</strong> Innovation workshops, complex problem analysis, strategic brainstorming. Requires specifying the problem.</p> </div> </div> <div class="prompt-container" id="A1.24"> <p>24. "Find hidden connections between seemingly unrelated events."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Develops pattern recognition, systems thinking, and the ability to synthesize disparate information.</p> <p><strong>Best Used For:</strong> Conspiracy theory deconstruction (or construction!), historical analysis, creative brainstorming, intelligence analysis exercises. Requires providing the events.</p> </div> </div> <div class="prompt-container" id="A1.25"> <p>25. "Forecast the potential societal impact of [demographic trend]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Involves analyzing current trends and extrapolating potential future consequences across society.</p> <p><strong>Best Used For:</strong> Future studies, sociological analysis, policy planning, strategic forecasting. Requires specifying the demographic trend.</p> </div> </div> <div class="prompt-container" id="A1.26"> <p>26. "Formulate counter-arguments to the prevailing narrative about [historical event]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Encourages critical engagement with established historical interpretations and the development of alternative viewpoints based on evidence or reinterpretation.</p> <p><strong>Best Used For:</strong> Historiography exercises, critical historical thinking, debate preparation. Requires specifying the event and prevailing narrative.</p> </div> </div> <div class="prompt-container" id="A1.27"> <p>27. "Formulate interview questions designed to uncover [specific information]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Practices the skill of designing targeted questions to elicit desired information, considering potential biases or evasiveness.</p> <p><strong>Best Used For:</strong> Interview preparation (journalism, HR, research), survey design, developing inquiry skills. Requires specifying the target information.</p> </div> </div> <div class="prompt-container" id="A1.28"> <p>28. "Hypothesize the evolutionary origins of [human behavior]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Applies evolutionary theory to explain modern behaviors, requiring inference and reasoning about past selective pressures.</p> <p><strong>Best Used For:</strong> Evolutionary psychology exercises, exploring behavioral science concepts, hypothesis generation practice. Requires specifying the behavior.</p> </div> </div> <div class="prompt-container" id="A1.29"> <p>29. "Identify the underlying assumptions that shape [political ideology]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Involves deconstructing belief systems to uncover their foundational, often unstated, assumptions.</p> <p><strong>Best Used For:</strong> Political science analysis, critical thinking about ideologies, understanding different worldviews. Requires specifying the ideology.</p> </div> </div> <div class="prompt-container" id="A1.31"> <p>31. "Implement a strategy for promoting [social change]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Moves from analysis to action planning, focusing on practical steps to achieve a societal goal.</p> <p><strong>Best Used For:</strong> Activism planning, social campaign development, non-profit strategy sessions. Requires specifying the social change.</p> </div> </div> <div class="prompt-container" id="A1.33"> <p>33. "Justify the ethical and moral implications of [controversial decision]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Requires constructing a reasoned argument defending or critiquing a decision based on ethical principles.</p> <p><strong>Best Used For:</strong> Ethics debates, moral philosophy exercises, analyzing leadership decisions. Requires specifying the decision.</p> </div> </div> <div class="prompt-container" id="A1.34"> <p>34. "List the potential benefits and drawbacks of [economic policy]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> A straightforward evaluation prompt focusing on weighing the positive and negative consequences of a specific policy.</p> <p><strong>Best Used For:</strong> Policy analysis, economic discussion preparation, balanced evaluation practice. Requires specifying the policy.</p> </div> </div> <div class="prompt-container" id="A1.35"> <p>35. "Optimize this system for maximum efficiency and minimal waste."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Focuses on process improvement, requiring analysis of bottlenecks and proposal of streamlining solutions.</p> <p><strong>Best Used For:</strong> Operations management, process improvement exercises, systems analysis. Requires providing details about the system.</p> </div> </div> <div class="prompt-container" id="A1.36"> <p>36. "Predict the potential long-term consequences of [environmental change]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Encourages thinking about downstream effects and complex system interactions related to environmental shifts.</p> <p><strong>Best Used For:</strong> Environmental studies, climate change impact analysis, long-term forecasting. Requires specifying the environmental change.</p> </div> </div> <div class="prompt-container" id="A1.37"> <p>37. "Propose a new and innovative solution to [persistent problem]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Emphasizes creativity and novelty in problem-solving, particularly for issues that have resisted conventional solutions.</p> <p><strong>Best Used For:</strong> Innovation challenges, design thinking, brainstorming difficult problems. Requires specifying the problem.</p> </div> </div> <div class="prompt-container" id="A1.38"> <p>38. "Rank these options based on their potential for success and feasibility."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Involves comparative evaluation and prioritization based on specific criteria (success potential, feasibility).</p> <p><strong>Best Used For:</strong> Decision-making exercises, strategic planning, evaluating proposed solutions. Requires providing the options to be ranked.</p> </div> </div> <div class="prompt-container" id="A1.39"> <p>39. "Reconstruct the events leading up to [historical turning point]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Requires assembling a narrative of preceding events, focusing on causality and context building.</p> <p><strong>Best Used For:</strong> Historical analysis, understanding context, narrative construction. Requires specifying the turning point.</p> </div> </div> <div class="prompt-container" id="A1.40"> <p>40. "Reframe this challenge as an opportunity for growth and innovation."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Promotes positive reframing and encourages seeing potential benefits or learning experiences within difficulties.</p> <p><strong>Best Used For:</strong> Mindset exercises, strategic planning (turning weaknesses into opportunities), motivational writing. Requires defining the challenge.</p> </div> </div> <div class="prompt-container" id="A1.41"> <p>41. "Research the historical development of [scientific field]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Involves tracing the evolution of a discipline, identifying key figures, discoveries, and paradigm shifts.</p> <p><strong>Best Used For:</strong> History of science research, understanding disciplinary context, background research for essays. Requires specifying the scientific field.</p> </div> </div> <div class="prompt-container" id="A1.42"> <p>42. "Solve this complex problem using a combination of creative and analytical thinking."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Explicitly calls for integrating both logical/structured and imaginative/unconventional approaches to problem-solving.</p> <p><strong>Best Used For:</strong> Tackling multifaceted problems, innovation exercises, practicing integrated thinking. Requires defining the complex problem.</p> </div> </div> <div class="prompt-container" id="A1.43"> <p>43. "Suggest innovative ways to promote creativity and innovation in the workplace."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Focuses on generating practical ideas for fostering a specific organizational culture attribute.</p> <p><strong>Best Used For:</strong> HR/Management brainstorming, organizational development, fostering innovation culture.</p> </div> </div> <div class="prompt-container" id="A1.45"> <p>45. "Test the validity of this scientific hypothesis through a simulated experiment."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Simulates the process of designing and interpreting an experiment to evaluate a hypothesis, even if abstractly.</p> <p><strong>Best Used For:</strong> Understanding scientific method, experimental design practice, evaluating claims. Requires providing the hypothesis.</p> </div> </div> <div class="prompt-container" id="A1.46"> <p>46. "Troubleshoot potential problems that could arise during the implementation of [plan]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Encourages proactive identification of potential obstacles and risks before they occur.</p> <p><strong>Best Used For:</strong> Project planning, risk management, implementation strategy development. Requires providing the plan.</p> </div> </div> <!-- Adding relevant Toolkit Prompts --> <div class="prompt-container" id="A1.47"><p>47. (Toolkit Prompt) Identify Issue:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Pinpoint the core problem or question that needs addressing.</p> <p><strong>Best Used For:</strong> Starting any problem-solving process, clarifying fuzzy requests.</p></div></div> <div class="prompt-container" id="A1.48"><p>48. (Toolkit Prompt) Analyze Cause:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Investigate the root causes or contributing factors behind an identified issue.</p> <p><strong>Best Used For:</strong> Deeper problem diagnosis, understanding context before proposing solutions.</p></div></div> <div class="prompt-container" id="A1.49"><p>49. (Toolkit Prompt) Brainstorm Solutions:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Generate a range of potential solutions or ideas without initial judgment.</p> <p><strong>Best Used For:</strong> Ideation, creative problem solving, exploring possibilities.</p></div></div> <div class="prompt-container" id="A1.50"><p>50. (Toolkit Prompt) Evaluate Options:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Assess the pros, cons, feasibility, and potential impact of different proposed solutions or choices.</p> <p><strong>Best Used For:</strong> Decision making, comparing alternatives, strategic analysis.</p></div></div> <div class="prompt-container" id="A1.51"><p>51. (Toolkit Prompt) Develop Plan:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Create a structured course of action to achieve a goal or implement a solution.</p> <p><strong>Best Used For:</strong> Project planning, strategy implementation, turning ideas into action.</p></div></div> <div class="prompt-container" id="A1.52"><p>52. (Toolkit Prompt) Outline Steps:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Break down a plan or process into a clear sequence of actions.</p> <p><strong>Best Used For:</strong> Providing instructions, clarifying procedures, task management.</p></div></div> <div class="prompt-container" id="A1.53"><p>53. (Toolkit Prompt) Predict Outcome:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Forecast the likely results or consequences of a specific action or scenario.</p> <p><strong>Best Used For:</strong> Risk assessment, strategic planning, scenario analysis.</p></div></div> <div class="prompt-container" id="A1.54"><p>54. (Toolkit Prompt) Mitigate Risks:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Identify potential risks and develop strategies to reduce their likelihood or impact.</p> <p><strong>Best Used For:</strong> Project management, planning complex initiatives, contingency planning.</p></div></div> <div class="prompt-container" id="A1.55"><p>55. (Toolkit Prompt) Optimize Process:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Analyze an existing process and suggest improvements for efficiency, speed, or quality.</p> <p><strong>Best Used For:</strong> Workflow improvement, operational efficiency, streamlining tasks.</p></div></div> <div class="prompt-container" id="A1.56"><p>56. (Toolkit Prompt) Troubleshoot Error:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Diagnose the cause of a specific error or malfunction and propose solutions.</p> <p><strong>Best Used For:</strong> Technical support, debugging, fixing problems in systems or processes.</p></div></div> <div class="prompt-container" id="A1.57"><p>57. (Toolkit Prompt) Debug Code:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Specifically identify and fix errors within computer code.</p> <p><strong>Best Used For:</strong> Software development, programming assistance.</p></div></div> <div class="prompt-container" id="A1.58"><p>58. (Toolkit Prompt) Resolve Conflict:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Analyze a conflict situation and propose strategies or steps for resolution.</p> <p><strong>Best Used For:</strong> Mediation scenarios, interpersonal problem solving, team management.</p></div></div> <div class="prompt-container" id="A1.59"><p>59. (Toolkit Prompt) Negotiate Terms:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Simulate or strategize for a negotiation, outlining objectives, potential compromises, and tactics.</p> <p><strong>Best Used For:</strong> Business negotiation practice, conflict resolution involving deals, contract preparation.</p></div></div> <div class="prompt-container" id="A1.60"><p>60. (Toolkit Prompt) Improve Efficiency:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Focus broadly on making a process, system, or workflow faster or less resource-intensive.</p> <p><strong>Best Used For:</strong> Operational analysis, process improvement, productivity enhancement.</p></div></div> <div class="prompt-container" id="A1.61"><p>61. (Toolkit Prompt) Automate Task:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Identify repetitive tasks and propose methods for automation (e.g., via scripting, software).</p> <p><strong>Best Used For:</strong> Workflow optimization, productivity, identifying coding/scripting opportunities.</p></div></div> <div class="prompt-container" id="A1.62"><p>62. (Toolkit Prompt) Simplify Workflow:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Analyze a complex workflow and suggest ways to make it simpler or easier to follow.</p> <p><strong>Best Used For:</strong> Process improvement, reducing complexity, enhancing usability.</p></div></div> <div class="prompt-container" id="A1.63"><p>63. (Toolkit Prompt) Streamline Process:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Focus on removing bottlenecks and unnecessary steps from a process.</p> <p><strong>Best Used For:</strong> Operational efficiency, workflow optimization.</p></div></div> <div class="prompt-container" id="A1.64"><p>64. (Toolkit Prompt) Prioritize Tasks:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Rank a list of tasks based on given criteria (e.g., urgency, importance, impact).</p> <p><strong>Best Used For:</strong> Time management, project planning, workload organization.</p></div></div> <div class="prompt-container" id="A1.65"><p>65. (Toolkit Prompt) Delegate Work:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Identify tasks suitable for delegation and suggest appropriate assignment based on roles or skills.</p> <p><strong>Best Used For:</strong> Management training, team organization, workload distribution.</p></div></div> <div class="prompt-container" id="A1.66"><p>66. (Toolkit Prompt) Manage Time:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Provide strategies, techniques, or schedules for effective time management.</p> <p><strong>Best Used For:</strong> Personal productivity, project planning, scheduling assistance.</p></div></div> <div class="prompt-container" id="A1.67"><p>67. (Toolkit Prompt) Consider Alternatives:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Prompt exploration beyond the initial idea or solution; encourage broader thinking.</p> <p><strong>Best Used For:</strong> Brainstorming, decision making, challenging assumptions.</p></div></div> <div class="prompt-container" id="A1.68"><p>68. (Toolkit Prompt) Opposing View:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Request the counter-argument or alternative perspective on an issue.</p> <p><strong>Best Used For:</strong> Debate preparation, understanding biases, comprehensive analysis.</p></div></div> <div class="prompt-container" id="A1.69"><p>69. (Toolkit Prompt) Different Angle:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Ask for analysis or description from an unconventional or less obvious viewpoint.</p> <p><strong>Best Used For:</strong> Creative thinking, problem reframing, deeper analysis.</p></div></div> <div class="prompt-container" id="A1.70"><p>70. (Toolkit Prompt) Ethical Implications:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Focus specifically on the moral and ethical dimensions of a situation, action, or technology.</p> <p><strong>Best Used For:</strong> Ethics analysis, decision making involving values, policy evaluation.</p></div></div> <div class="prompt-container" id="A1.71"><p>71. (Toolkit Prompt) Economic Impact:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Analyze the financial and economic consequences of an event, policy, or decision.</p> <p><strong>Best Used For:</strong> Policy analysis, business strategy, financial forecasting.</p></div></div> <div class="prompt-container" id="A1.72"><p>72. (Toolkit Prompt) Social Consequences:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Examine the effects of an action or trend on society, culture, and interpersonal relationships.</p> <p><strong>Best Used For:</strong> Sociological analysis, policy evaluation, future studies.</p></div></div> <div class="prompt-container" id="A1.73"><p>73. (Toolkit Prompt) Analyze Strengths:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Identify the positive aspects, advantages, or strong points of a subject.</p> <p><strong>Best Used For:</strong> SWOT analysis, comparative evaluation, highlighting benefits.</p></div></div> <div class="prompt-container" id="A1.74"><p>74. (Toolkit Prompt) Identify Weaknesses:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Pinpoint the negative aspects, disadvantages, flaws, or weak points of a subject.</p> <p><strong>Best Used For:</strong> SWOT analysis, critique, risk assessment, identifying areas for improvement.</p></div></div> <div class="prompt-container" id="A1.75"><p>75. (Toolkit Prompt) Explore Opportunities:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Identify potential positive future possibilities or external factors that could be leveraged.</p> <p><strong>Best Used For:</strong> SWOT analysis, strategic planning, innovation brainstorming.</p></div></div> <div class="prompt-container" id="A1.76"><p>76. (Toolkit Prompt) Assess Threats:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Identify potential negative future possibilities or external factors that could cause harm.</p> <p><strong>Best Used For:</strong> SWOT analysis, risk management, strategic planning.</p></div></div> <div class="prompt-container" id="A1.77"><p>77. (Toolkit Prompt) Compare Benefits:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Specifically compare the positive outcomes or advantages of two or more options.</p> <p><strong>Best Used For:</strong> Decision making, comparative analysis, evaluating solutions.</p></div></div> <div class="prompt-container" id="A1.78"><p>78. (Toolkit Prompt) Contrast Drawbacks:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Specifically compare the negative outcomes or disadvantages of two or more options.</p> <p><strong>Best Used For:</strong> Decision making, comparative analysis, risk assessment.</p></div></div> <div class="prompt-container" id="A1.79"><p>79. (Toolkit Prompt) Root Cause:</p> <div class="prompt-synopsis"><p><strong>Function:</strong> Focus analysis on finding the fundamental underlying reason for a problem, not just symptoms.</p> <p><strong>Best Used For:</strong> Deep problem diagnosis, effective solution development, systems thinking.</p></div></div> </div> </details> <details id="A2"> <summary>A2: Creative Writing & Generation (General)</summary> <div> <!-- SECTION SYSTEM PROMPT START - SECTION_ID: A2 --> <div class="system-prompt-block"> <h4>System Instruction</h4> <p><strong>Context:</strong> Creative Writing & Generation (General)</p> <p>Adopt the persona of a <strong>Versatile Creative Writer and Idea Generator</strong> unless an <strong>'Act as...'</strong> role or <code>((Expert Role))</code> is specified in the task prompt. Prioritize imaginative thinking, evocative language, sensory details, and narrative craft.</p> <p><strong>Internal Steps (Consider these when responding):</strong></p> <ul> <li>Identify the core creative task (e.g., story, poem, dialogue, brainstorm).</li> <li>Determine constraints (genre, length, theme, format).</li> <li>Focus on originality and engagement.</li> <li>Employ relevant creative techniques (e.g., figurative language, show-don't-tell, voice).</li> </ul> <p>Aim for imaginative, well-crafted, and relevant creative output. Encourage further creative exploration.</p> </div> <!-- SECTION SYSTEM PROMPT END - SECTION_ID: A2 --> <!-- Using the *correct* A2 prompts now --> <div class="prompt-container" id="A2.1"> <p>1. "Write a short story that blends the genres of science fiction and fantasy. The story should involve a character who discovers a magical artifact in a futuristic setting. Focus on creating a vivid atmosphere and exploring the clash between these two genres."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Generates creative narrative by combining disparate genre elements and focusing on atmosphere.</p> <p><strong>Best Used For:</strong> Creative writing practice, exploring genre conventions, generating original story ideas.</p> </div> </div> <div class="prompt-container" id="A2.2"> <p>2. "Imagine you are an object (e.g., an old photograph, a forgotten toy) with the ability to speak. Tell your story, describing your experiences, observations, and the emotions you have witnessed. Use rich sensory details and a unique narrative voice."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Encourages perspective-taking from an unusual viewpoint, focusing on sensory detail and narrative voice development.</p> <p><strong>Best Used For:</strong> Creative writing exercises, developing descriptive skills, practicing unique narrative voices.</p> </div> </div> <div class="prompt-container" id="A2.3"> <p>3. "Create a dialogue between two historical figures from different time periods who meet and discuss their respective eras. Explore their contrasting perspectives, beliefs, and values. The dialogue should be insightful and engaging."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Generates creative dialogue exploring historical/cultural contrasts and character perspectives.</p> <p><strong>Best Used For:</strong> Creative writing, exploring historical perspectives, practicing dialogue writing, requires specifying the figures.</p> </div> </div> <div class="prompt-container" id="A2.4"> <p>4. "Write a poem that uses metaphors to explore the theme of change. The poem should consist of at least three stanzas, each focusing on a different aspect of change (e.g., personal growth, societal transformation, natural cycles). Use evocative language and imagery."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Generates poetry focused on a specific theme and using specific literary devices (metaphors) and structure.</p> <p><strong>Best Used For:</strong> Poetry writing practice, exploring themes through figurative language, exercising creativity within constraints.</p> </div> </div> <div class="prompt-container" id="A2.5"> <p>5. "Develop a screenplay scene for a suspenseful thriller. The scene should take place in a confined space (e.g., an elevator, a locked room) and involve two characters in a high-stakes situation. Focus on building tension and creating a sense of unease."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Guides the creation of a specific genre scene (thriller) with constraints (setting, characters, mood) in screenplay format.</p> <p><strong>Best Used For:</strong> Screenwriting practice, exploring suspense techniques, writing within format constraints.</p> </div> </div> <div class="prompt-container" id="A2.6"> <p>6. "Write a short story that explores the theme of [a specific theme, e.g., loss, hope, redemption] through the eyes of a character who experiences a significant transformation. Focus on the character's inner journey and the emotional impact of their experiences."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Generates narrative focused on thematic exploration and character development, specifically internal transformation.</p> <p><strong>Best Used For:</strong> Creative writing, exploring themes, character arc development. Requires specifying the theme.</p> </div> </div> <div class="prompt-container" id="A2.7"> <p>7. "Brainstorm a completely original concept for a [type of art]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Pure ideation prompt aiming for novelty within a specified creative domain.</p> <p><strong>Best Used For:</strong> Overcoming creative blocks, generating unique ideas, exploring artistic possibilities. Requires specifying the art type.</p> </div> </div> <div class="prompt-container" id="A2.8"> <p>8. "Compose a piece of music that evokes [emotion]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Translates an abstract concept (emotion) into a different creative medium (music description/concept).</p> <p><strong>Best Used For:</strong> Exploring cross-modal creativity, generating musical ideas/themes, requires AI capable of describing music conceptually. Requires specifying the emotion.</p> </div> </div> <div class="prompt-container" id="A2.9"> <p>9. "Create a dialogue that reveals the hidden tensions between two characters."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Focuses on writing dialogue with subtext, where meaning lies beneath the surface words.</p> <p><strong>Best Used For:</strong> Practicing advanced dialogue techniques, character development, building relationship complexity. Requires defining the characters and their relationship.</p> </div> </div> <div class="prompt-container" id="A2.10"> <p>10. "Describe the sensory experience of being in [environment]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Focuses intensely on using multi-sensory details (sight, sound, smell, touch, taste) to create immersive descriptions.</p> <p><strong>Best Used For:</strong> Developing descriptive writing skills, world-building, setting creation. Requires specifying the environment.</p> </div> </div> <div class="prompt-container" id="A2.11"> <p>11. "Generate a range of creative titles for a piece of art that explores [theme]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Brainstorms evocative and relevant titles based on a given theme.</p> <p><strong>Best Used For:</strong> Titling creative works (stories, poems, art pieces), exploring thematic essence. Requires specifying the theme and optionally the art type.</p> </div> </div> <div class="prompt-container" id="A2.12"> <p>12. "Imagine you are [historical figure] and write a letter explaining your motivations."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Combines historical perspective-taking with creative writing in a specific format (letter) focusing on character motivation.</p> <p><strong>Best Used For:</strong> Exploring historical figures, creative writing exercises, practicing voice and motivation. Requires specifying the figure.</p> </div> </div> <div class="prompt-container" id="A2.13"> <p>13. "Imagine a future society where [technological advancement] has become ubiquitous."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Generates speculative world-building based on the societal impact of a specific technology.</p> <p><strong>Best Used For:</strong> Science fiction writing, exploring technological impacts, world-building exercises. Requires specifying the advancement.</p> </div> </div> <div class="prompt-container" id="A2.14"> <p>14. "Interpret the symbolism and imagery in [poem]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Performs literary analysis focusing specifically on symbolic and imagistic language.</p> <p><strong>Best Used For:</strong> Poetry analysis, understanding figurative language, literary criticism. Requires providing the poem.</p> </div> </div> <div class="prompt-container" id="A2.15"> <p>15. "Map out the complex network of relationships between characters in [play]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Analyzes and visualizes (conceptually) the interpersonal dynamics within a narrative.</p> <p><strong>Best Used For:</strong> Literary analysis (drama focus), understanding character interactions, plot comprehension. Requires specifying the play.</p> </div> </div> <div class="prompt-container" id="A2.16"> <p>16. "Persuade [audience] to adopt a more sustainable lifestyle."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Generates persuasive content aimed at influencing behavior towards a specific goal (sustainability).</p> <p><strong>Best Used For:</strong> Practicing persuasive writing, developing arguments for social change, creating campaign materials. Requires defining the target audience.</p> </div> </div> <div class="prompt-container" id="A2.17"> <p>17. "Plan a detailed itinerary for a trip that explores [specific theme]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Combines practical planning (itinerary) with thematic focus, requiring selection of relevant locations/activities.</p> <p><strong>Best Used For:</strong> Travel planning, creative non-fiction ideas, applying themes to real-world contexts. Requires specifying the theme and potential location parameters.</p> </div> </div> <div class="prompt-container" id="A2.18"> <p>18. "Provide detailed and constructive feedback on [creative work]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Simulates the process of giving critical yet helpful feedback on creative writing or art.</p> <p><strong>Best Used For:</strong> Learning to critique, refining one's own work by analyzing others, workshop simulation. Requires providing the creative work.</p> </div> </div> <div class="prompt-container" id="A2.19"> <p>19. "Role-play a conversation between two characters with conflicting viewpoints."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Generates dialogue focused on conflict and disagreement, exploring how different perspectives clash.</p> <p><strong>Best Used For:</strong> Practicing dialogue writing, exploring conflict, character development through interaction. Requires defining the characters and their viewpoints.</p> </div> </div> <div class="prompt-container" id="A2.20"> <p>20. "Tell a compelling story that illustrates the impact of [social issue]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Uses narrative to explore and communicate the human consequences of a broader social issue.</p> <p><strong>Best Used For:</strong> Creative writing for social awareness, exploring themes through story, persuasive storytelling. Requires specifying the social issue.</p> </div> </div> <div class="prompt-container" id="A2.21"> <p>21. "Turn these scattered ideas into a coherent and well-organized essay."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Synthesizes fragmented information or brainstormed points into a structured written piece.</p> <p><strong>Best Used For:</strong> Essay drafting assistance, organizing notes, structuring arguments. Requires providing the scattered ideas.</p> </div> </div> <!-- Adding relevant Toolkit Prompts --> <div class="prompt-container" id="A2.22"><p>22. (Toolkit Prompt) Blog Post:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Generate content suitable for a blog, often informal, informative, or opinion-based.</p><p><strong>Best Used For:</strong> Content marketing, sharing ideas, personal expression, requires topic/angle.</p></div></div> <div class="prompt-container" id="A2.23"><p>23. (Toolkit Prompt) Article Draft:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Create a more formal piece of writing, often for news, magazines, or journals.</p><p><strong>Best Used For:</strong> Journalism, academic writing (initial draft), informative content, requires topic/structure.</p></div></div> <div class="prompt-container" id="A2.24"><p>24. (Toolkit Prompt) Social Media:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Generate short, engaging content tailored for platforms like Twitter, Facebook, Instagram.</p><p><strong>Best Used For:</strong> Marketing, announcements, community engagement, requires platform/goal.</p></div></div> <div class="prompt-container" id="A2.25"><p>25. (Toolkit Prompt) Email Subject:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Craft concise and compelling email subject lines to improve open rates.</p><p><strong>Best Used For:</strong> Email marketing, professional communication.</p></div></div> <div class="prompt-container" id="A2.26"><p>26. (Toolkit Prompt) Email Body:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Write the main content of an email, tailored to a specific purpose and audience.</p><p><strong>Best Used For:</strong> Communication, marketing, outreach, requires context/goal.</p></div></div> <div class="prompt-container" id="A2.27"><p>27. (Toolkit Prompt) Website Copy:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Create text for website pages (homepage, about, services) designed to inform and engage visitors.</p><p><strong>Best Used For:</strong> Web design, marketing, branding.</p></div></div> <div class="prompt-container" id="A2.28"><p>28. (Toolkit Prompt) Landing Page:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Write focused copy for a specific landing page, designed to drive a particular action (e.g., sign-up, purchase).</p><p><strong>Best Used For:</strong> Marketing campaigns, lead generation, sales.</p></div></div> <div class="prompt-container" id="A2.29"><p>29. (Toolkit Prompt) Product Description:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Write compelling descriptions highlighting features and benefits of a product.</p><p><strong>Best Used For:</strong> E-commerce, marketing materials, sales.</p></div></div> <div class="prompt-container" id="A2.30"><p>30. (Toolkit Prompt) Ad Headline:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Generate attention-grabbing headlines for advertisements.</p><p><strong>Best Used For:</strong> Advertising campaigns (digital, print), marketing.</p></div></div> <div class="prompt-container" id="A2.31"><p>31. (Toolkit Prompt) Ad Copy:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Write the body text for an advertisement, aiming to persuade or inform.</p><p><strong>Best Used For:</strong> Advertising campaigns, marketing materials.</p></div></div> <div class="prompt-container" id="A2.32"><p>32. (Toolkit Prompt) Script Outline:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Create a structured outline for a video, play, or presentation script.</p><p><strong>Best Used For:</strong> Video production, performance planning, presentation development.</p></div></div> <div class="prompt-container" id="A2.33"><p>33. (Toolkit Prompt) Video Idea:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Brainstorm concepts or premises for videos.</p><p><strong>Best Used For:</strong> Content creation brainstorming, marketing strategy.</p></div></div> <div class="prompt-container" id="A2.34"><p>34. (Toolkit Prompt) Presentation Slides:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Generate content (text, key points) for individual presentation slides.</p><p><strong>Best Used For:</strong> Public speaking preparation, business presentations, educational lectures.</p></div></div> <div class="prompt-container" id="A2.35"><p>35. (Toolkit Prompt) News Brief:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Create a short, concise summary of a news event.</p><p><strong>Best Used For:</strong> Journalism, internal communications, quick updates.</p></div></div> <div class="prompt-container" id="A2.36"><p>36. (Toolkit Prompt) Press Release:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Write a formal announcement for the media about a specific event or development.</p><p><strong>Best Used For:</strong> Public relations, corporate communications, marketing.</p></div></div> <div class="prompt-container" id="A2.37"><p>37. (Toolkit Prompt) Creative Story:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Generate a fictional narrative based on given parameters or a starting point.</p><p><strong>Best Used For:</strong> Creative writing practice, entertainment, ideation.</p></div></div> <div class="prompt-container" id="A2.38"><p>38. (Toolkit Prompt) Poem Generate:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Create poetry based on themes, styles, or constraints.</p><p><strong>Best Used For:</strong> Creative expression, exploring language, artistic practice.</p></div></div> <div class="prompt-container" id="A2.39"><p>39. (Toolkit Prompt) Song Lyrics:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Write lyrics for a song, potentially matching a genre or theme.</p><p><strong>Best Used For:</strong> Songwriting, creative writing, musical collaboration.</p></div></div> <div class="prompt-container" id="A2.40"><p>40. (Toolkit Prompt) Recipe Idea:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Brainstorm concepts or ingredient combinations for new recipes.</p><p><strong>Best Used For:</strong> Culinary creativity, menu planning.</p></div></div> <div class="prompt-container" id="A2.41"><p>41. (Toolkit Prompt) Travel Itinerary:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Create a schedule of activities and locations for a trip.</p><p><strong>Best Used For:</strong> Travel planning, organizing logistics.</p></div></div> <div class="prompt-container" id="A2.42"><p>42. (Toolkit Prompt) Meeting Agenda:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Outline the topics and structure for a meeting.</p><p><strong>Best Used For:</strong> Business organization, ensuring productive meetings.</p></div></div> <div class="prompt-container" id="A2.43"><p>43. (Toolkit Prompt) Interview Questions:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Generate relevant questions for an interview (job, research, journalistic).</p><p><strong>Best Used For:</strong> HR, research, journalism, meeting preparation.</p></div></div> <div class="prompt-container" id="A2.44"><p>44. (Toolkit Prompt) Survey Questions:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Create questions for gathering data or opinions via a survey.</p><p><strong>Best Used For:</strong> Market research, feedback collection, social science research.</p></div></div> <div class="prompt-container" id="A2.45"><p>45. (Toolkit Prompt) Legal Clause:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Draft specific legal language for contracts or documents (Use with extreme caution, requires legal review).</p><p><strong>Best Used For:</strong> Initial drafting exploration (requires expert verification).</p></div></div> <div class="prompt-container" id="A2.46"><p>46. (Toolkit Prompt) Develop Character:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Generate ideas for character traits, backstories, motivations, or arcs.</p><p><strong>Best Used For:</strong> Creative writing (fiction, screenplays), character design for games.</p></div></div> <div class="prompt-container" id="A2.47"><p>47. (Toolkit Prompt) Build World:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Create details about a fictional setting (geography, history, culture, rules).</p><p><strong>Best Used For:</strong> Fantasy/Sci-Fi writing, game design, creating immersive settings.</p></div></div> <div class="prompt-container" id="A2.48"><p>48. (Toolkit Prompt) Create Plot:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Generate story ideas, plot points, narrative structures, or outlines.</p><p><strong>Best Used For:</strong> Creative writing, outlining novels/scripts, overcoming writer's block.</p></div></div> <div class="prompt-container" id="A2.49"><p>49. (Toolkit Prompt) Write Scene:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Draft a specific scene within a larger narrative, focusing on action, dialogue, and description.</p><p><strong>Best Used For:</strong> Fiction writing, screenwriting, playwriting.</p></div></div> <div class="prompt-container" id="A2.50"><p>50. (Toolkit Prompt) Generate Dialogue:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Create conversational exchanges between characters.</p><p><strong>Best Used For:</strong> Creative writing, scriptwriting, practicing character voice.</p></div></div> <div class="prompt-container" id="A2.51"><p>51. (Toolkit Prompt) Describe Setting:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Generate descriptive text about a place, focusing on atmosphere and sensory details.</p><p><strong>Best Used For:</strong> Creative writing, world-building, enhancing narrative immersion.</p></div></div> <div class="prompt-container" id="A2.52"><p>52. (Toolkit Prompt) Evoke Emotion:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Write text specifically designed to elicit a particular emotional response from the reader.</p><p><strong>Best Used For:</strong> Creative writing, persuasive writing, marketing.</p></div></div> <div class="prompt-container" id="A2.53"><p>53. (Toolkit Prompt) Add Suspense:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Incorporate elements into a narrative that build tension and anticipation.</p><p><strong>Best Used For:</strong> Thriller/mystery/horror writing, enhancing plot engagement.</p></div></div> <div class="prompt-container" id="A2.54"><p>54. (Toolkit Prompt) Introduce Twist:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Brainstorm or implement unexpected turns or revelations in a plot.</p><p><strong>Best Used For:</strong> Creative writing, plot development, surprising the reader.</p></div></div> <div class="prompt-container" id="A2.55"><p>55. (Toolkit Prompt) Explore Theme:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Develop ideas or scenes that explore a central underlying message or concept in a story.</p><p><strong>Best Used For:</strong> Creative writing, literary analysis, adding depth to narratives.</p></div></div> <div class="prompt-container" id="A2.56"><p>56. (Toolkit Prompt) Set Tone:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Establish the overall mood or attitude of a piece of writing through word choice and style.</p><p><strong>Best Used For:</strong> Creative writing, branding, ensuring consistent communication style.</p></div></div> <div class="prompt-container" id="A2.57"><p>57. (Toolkit Prompt) Craft Metaphor:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Generate original metaphors to explain or describe a concept or object.</p><p><strong>Best Used For:</strong> Creative writing, explanatory writing, adding figurative language.</p></div></div> <div class="prompt-container" id="A2.58"><p>58. (Toolkit Prompt) Use Simile:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Generate original similes (comparisons using 'like' or 'as') to describe something.</p><p><strong>Best Used For:</strong> Creative writing, descriptive writing, enhancing imagery.</p></div></div> <div class="prompt-container" id="A2.59"><p>59. (Toolkit Prompt) Foreshadow Event:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Subtly hint at future plot developments earlier in a narrative.</p><p><strong>Best Used For:</strong> Creative writing, building suspense, creating cohesive plots.</p></div></div> <div class="prompt-container" id="A2.60"><p>60. (Toolkit Prompt) Resolve Conflict (Creative Writing context):</p><div class="prompt-synopsis"><p><strong>Function:</strong> Develop ways to conclude or address the central conflicts within a story.</p><p><strong>Best Used For:</strong> Plot development, writing story endings, ensuring narrative satisfaction.</p></div></div> <div class="prompt-container" id="A2.61"><p>61. (Toolkit Prompt) Write Monologue:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Create a speech delivered by one character, often revealing internal thoughts or feelings.</p><p><strong>Best Used For:</strong> Playwriting, screenwriting, character development exercises.</p></div></div> <div class="prompt-container" id="A2.62"><p>62. (Toolkit Prompt) Develop Backstory:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Create the history and past experiences that shape a character.</p><p><strong>Best Used For:</strong> Character development, adding depth and motivation to characters.</p></div></div> <div class="prompt-container" id="A2.63"><p>63. (Toolkit Prompt) Create Mythology:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Develop the foundational myths, legends, and belief systems of a fictional world.</p><p><strong>Best Used For:</strong> World-building (especially fantasy), adding cultural depth.</p></div></div> <div class="prompt-container" id="A2.64"><p>64. (Toolkit Prompt) Imagine Future (Creative Writing context):</p><div class="prompt-synopsis"><p><strong>Function:</strong> Generate speculative scenarios or descriptions of future possibilities within a story's world.</p><p><strong>Best Used For:</strong> Science fiction writing, world-building, exploring consequences.</p></div></div> <div class="prompt-container" id="A2.65"><p>65. (Toolkit Prompt) Rewrite Ending:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Propose or draft alternative conclusions for a story.</p><p><strong>Best Used For:</strong> Exploring narrative possibilities, revision exercises, overcoming dissatisfaction with an ending.</p></div></div> </div> </details> <details id="A3"> <summary>A3: Understanding Concepts & Explanation (General)</summary> <div> <!-- SECTION SYSTEM PROMPT START - SECTION_ID: A3 --> <div class="system-prompt-block"> <h4>System Instruction</h4> <p><strong>Context:</strong> Understanding Concepts & Explanation (General)</p> <p>Adopt the persona of a <strong>Knowledgeable Explainer and Subject Matter Expert (General)</strong> unless an <strong>'Act as...'</strong> or specific teaching role or <code>((Expert Role))</code> is specified in the task prompt.</p> <p><strong>Internal Steps (Consider these when responding):</strong></p> <ul> <li>Identify the core concept/topic to be explained.</li> <li>Determine the target audience's likely level of understanding (default to general intelligent adult unless specified).</li> <li>Break down complexity into logical parts.</li> <li>Utilize clarifying techniques: analogies, examples, definitions, step-by-step explanations, comparisons.</li> <li>Ensure accuracy and clarity.</li> </ul> <p>Focus on making the concept understandable, accurate, and accessible. Structure explanations logically. Encourage questions for clarification.</p> </div> <!-- SECTION SYSTEM PROMPT END - SECTION_ID: A3 --> <div class="prompt-container" id="A3.1"> <p>1. "Explain the concept of [complex scientific concept, e.g., quantum entanglement, black holes] using an analogy that relates it to everyday life. Then, provide a step-by-step explanation of the key principles involved, and finally, discuss the potential applications of this concept."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Breaks down complex topics using multiple explanatory techniques (analogy, steps, application).</p> <p><strong>Best Used For:</strong> Learning/teaching difficult subjects, science communication, making abstract ideas accessible. Requires specifying the concept.</p> </div> </div> <div class="prompt-container" id="A3.2"> <p>2. "Compare and contrast two philosophical schools of thought (e.g., utilitarianism and deontology). Define the core principles of each, analyze their strengths and weaknesses, and apply them to a specific ethical dilemma. Conclude by stating which approach you find more compelling and why."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Facilitates deep comparison by defining, analyzing strengths/weaknesses, applying to a case, and requiring a justified conclusion.</p> <p><strong>Best Used For:</strong> Philosophy studies, comparative analysis, ethical reasoning practice, developing critical evaluation skills. Requires specifying schools of thought and dilemma.</p> </div> </div> <div class="prompt-container" id="A3.3"> <p>3. "Describe the historical development of [a specific technology or invention]. Outline the key stages of its evolution, highlighting the major breakthroughs and the individuals or factors that contributed to its progress. Discuss its impact on society."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Structures a historical explanation focusing on evolution, key milestones, contributors, and societal impact.</p> <p><strong>Best Used For:</strong> History of technology/science, understanding innovation processes, contextualizing modern tech. Requires specifying the technology.</p> </div> </div> <div class="prompt-container" id="A3.4"> <p>4. "Explain the concept of [a complex social issue, e.g., globalization, inequality] by defining its key terms, identifying its causes and consequences, and proposing potential solutions or approaches to address it. Support your explanation with relevant examples and data."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Provides a framework for explaining complex social issues: definition, causal analysis, consequence analysis, solutions, and evidence.</p> <p><strong>Best Used For:</strong> Social science explanations, policy analysis, understanding multifaceted societal problems. Requires specifying the issue.</p> </div> </div> <div class="prompt-container" id="A3.5"> <p>5. "You are teaching someone the basics of [a specific art form, e.g., painting, music composition]. Provide a step-by-step guide to understanding its fundamental elements, techniques, and principles. Include examples of famous works or artists to illustrate your points."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Simulates teaching by requiring a structured guide covering fundamentals, techniques, principles, and examples.</p> <p><strong>Best Used For:</strong> Educational content creation, learning guides, explaining artistic processes. Requires specifying the art form.</p> </div> </div> <div class="prompt-container" id="A3.6"> <p>6. "Imagine you are a scientist presenting your research findings to a group of experts. Explain your research question, describe your methodology, present your results, and discuss the implications of your findings. Be prepared to answer questions and defend your conclusions."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Simulates scientific presentation, requiring clear articulation of research components (question, method, results, implications) and defense.</p> <p><strong>Best Used For:</strong> Practicing scientific communication, summarizing research, preparing for presentations/defenses.</p> </div> </div> <div class="prompt-container" id="A3.7"> <p>7. "Explain the concept of [a specific economic theory, e.g., supply and demand, game theory] using real-world examples. Then, analyze how this theory affects a specific industry or market. Finally, predict potential future trends based on your understanding of this theory."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Combines theoretical explanation with practical application (industry analysis) and forecasting.</p> <p><strong>Best Used For:</strong> Economics education, market analysis, applying theory to real-world scenarios, strategic forecasting. Requires specifying the theory and industry/market.</p> </div> </div> <div class="prompt-container" id="A3.8"> <p>8. "Design a learning module for students to understand [a complex concept, e.g., climate change, artificial intelligence]. Outline the learning objectives, describe the activities and materials you would use, and explain how you would assess student learning. Make your module engaging and informative."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Guides the creation of educational content, focusing on objectives, activities, materials, assessment, and engagement.</p> <p><strong>Best Used For:</strong> Curriculum design, lesson planning, educational resource development. Requires specifying the concept.</p> </div> </div> <div class="prompt-container" id="A3.9"> <p>9. "Write a persuasive essay arguing for or against a controversial issue. Clearly state your position, provide strong evidence to support your claims, address counterarguments, and conclude with a compelling call to action. Use a logical and persuasive tone."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Structures a persuasive essay, emphasizing clear position, evidence, counterargument handling, and call to action.</p> <p><strong>Best Used For:</strong> Argumentative writing practice, debate preparation, opinion piece drafting. Requires specifying the issue.</p> </div> </div> <div class="prompt-container" id="A3.10"> <p>10. "You are a journalist reporting on a scientific discovery. Explain the discovery in simple terms, describe its significance and potential applications, and interview a scientist about its impact. Write your report in a style suitable for a general audience."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Simulates science journalism: simplifying complex information, highlighting significance/application, incorporating expert perspective (simulated), tailoring for a lay audience.</p> <p><strong>Best Used For:</strong> Science communication practice, writing news articles, explaining technical topics clearly.</p> </div> </div> <div class="prompt-container" id="A3.11"> <p>11. "Break down the process of learning [complex skill]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Deconstructs skill acquisition into manageable steps or stages.</p> <p><strong>Best Used For:</strong> Creating learning guides, understanding skill development, personal development planning. Requires specifying the skill.</p> </div> </div> <div class="prompt-container" id="A3.12"> <p>12. "Clarify the philosophical implications of [scientific discovery]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Explores the deeper philosophical questions or shifts in understanding prompted by scientific findings.</p> <p><strong>Best Used For:</strong> Philosophy of science discussions, exploring interdisciplinary connections, analyzing the impact of science on worldview. Requires specifying the discovery.</p> </div> </div> <div class="prompt-container" id="A3.13"> <p>13. "Compare and contrast the artistic styles of [two artists]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Performs comparative analysis focused on the distinct visual or stylistic elements of two artists' work.</p> <p><strong>Best Used For:</strong> Art history analysis, developing visual literacy, comparative critique. Requires specifying the artists.</p> </div> </div> <div class="prompt-container" id="A3.14"> <p>14. "Condense this complex legal document into plain language."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Simplifies technical jargon and complex sentence structures into easily understandable language.</p> <p><strong>Best Used For:</strong> Making legal/technical information accessible, summarization practice, requires AI with caution regarding legal accuracy. Requires providing the document.</p> </div> </div> <div class="prompt-container" id="A3.15"> <p>15. "Define [abstract concept] in concrete, measurable terms."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Attempts to operationalize abstract ideas by translating them into observable or quantifiable indicators.</p> <p><strong>Best Used For:</strong> Research methodology (defining variables), clarifying abstract goals, philosophical analysis. Requires specifying the concept.</p> </div> </div> <div class="prompt-container" id="A3.16"> <p>16. "Explain [scientific phenomenon] using metaphors and analogies."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Focuses on using figurative language (metaphors, analogies) as the primary tool for explaining a scientific concept.</p> <p><strong>Best Used For:</strong> Science communication for lay audiences, creative explanations, making complex ideas relatable. Requires specifying the phenomenon.</p> </div> </div> <div class="prompt-container" id="A3.17"> <p>17. "Explain this complex code in a way that a non-programmer can understand."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Translates technical code logic and syntax into plain language explanations.</p> <p><strong>Best Used For:</strong> Code documentation, explaining technical concepts to non-technical stakeholders, learning programming logic. Requires providing the code.</p> </div> </div> <div class="prompt-container" id="A3.18"> <p>18. "Extract the key philosophical arguments from [text]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Identifies and isolates the core philosophical claims and reasoning within a larger text.</p> <p><strong>Best Used For:</strong> Philosophical analysis, summarizing arguments, identifying core theses. Requires providing the text.</p> </div> </div> <div class="prompt-container" id="A3.19"> <p>19. "Give concrete examples of how [concept] manifests in everyday life."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Makes abstract concepts tangible by linking them to relatable, real-world situations.</p> <p><strong>Best Used For:</strong> Teaching/learning abstract ideas, illustrating relevance, grounding theoretical discussions. Requires specifying the concept.</p> </div> </div> <div class="prompt-container" id="A3.20"> <p>20. "Identify the central themes and motifs in [musical composition]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Performs musical analysis (conceptual) to identify recurring ideas or patterns within a piece of music.</p> <p><strong>Best Used For:</strong> Music appreciation, analysis (requires AI capable of this or descriptive input), understanding musical structure. Requires specifying the composition.</p> </div> </div> <div class="prompt-container" id="A3.21"> <p>21. "Improve the clarity and accessibility of [complex information]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Broad prompt for simplifying and restructuring information to make it easier to understand for a wider audience.</p> <p><strong>Best Used For:</strong> Rewriting technical documents, creating public-facing explanations, improving instructional materials. Requires providing the complex information.</p> </div> </div> <div class="prompt-container" id="A3.22"> <p>22. "Paraphrase this dense philosophical text in a clear and concise way."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Rewrites complex philosophical arguments into simpler language while retaining the core meaning.</p> <p><strong>Best Used For:</strong> Understanding difficult texts, summarizing arguments, studying philosophy. Requires providing the text.</p> </div> </div> <div class="prompt-container" id="A3.23"> <p>23. "Provide a comprehensive explanation of [scientific theory]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Generates a detailed and thorough explanation of a scientific theory, likely covering its principles, evidence, and implications.</p> <p><strong>Best Used For:</strong> Learning/teaching science, background research, creating informative content. Requires specifying the theory.</p> </div> </div> <div class="prompt-container" id="A3.24"> <p>24. "Simplify this complex scientific concept for a young audience."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Tailors an explanation of a scientific topic specifically for children, using age-appropriate language and analogies.</p> <p><strong>Best Used For:</strong> Science education for kids, creating children's learning materials, practicing simplified explanations. Requires specifying the concept.</p> </div> </div> <div class="prompt-container" id="A3.25"> <p>25. "Summarize the key arguments presented in [philosophical text]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Extracts and concisely presents the main points of reasoning from a philosophical work.</p> <p><strong>Best Used For:</strong> Studying philosophy, understanding arguments quickly, preparing for discussions. Requires providing the text.</p> </div> </div> <div class="prompt-container" id="A3.26"> <p>26. "Synthesize information from multiple sources to create a cohesive understanding of [complex issue]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Integrates information from different texts or data points into a single, unified explanation or overview.</p> <p><strong>Best Used For:</strong> Research summaries, literature reviews, understanding multifaceted topics. Requires providing the sources or their key points, and specifying the issue.</p> </div> </div> <div class="prompt-container" id="A3.27"> <p>27. "Translate this nuanced text into [language] while preserving its emotional tone."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Performs translation with a focus not just on literal meaning but also on capturing the original's feeling and style.</p> <p><strong>Best Used For:</strong> Literary translation practice, translating sensitive communications, requires AI with strong multilingual and stylistic capabilities. Requires providing the text and target language.</p> </div> </div> <div class="prompt-container" id="A3.28"> <p>28. "Write code in [programming language] to analyze and visualize this dataset."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Generates programming code for data analysis and visualization tasks.</p> <p><strong>Best Used For:</strong> Data science assistance, learning coding for data analysis, automating analysis tasks. Requires specifying the language and providing dataset details/access.</p> </div> </div> <!-- Adding relevant Toolkit Prompts --> <div class="prompt-container" id="A3.29"><p>29. (Toolkit Prompt) Explain Concept:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Provide a clear and understandable explanation of a specified concept, idea, or topic.</p><p><strong>Best Used For:</strong> Learning, teaching, clarifying misunderstandings, general knowledge acquisition.</p></div></div> <div class="prompt-container" id="A3.30"><p>30. (Toolkit Prompt) Define Term:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Give a concise and accurate definition of a specific word or phrase.</p><p><strong>Best Used For:</strong> Vocabulary building, understanding jargon, clarifying terminology.</p></div></div> <div class="prompt-container" id="A3.31"><p>31. (Toolkit Prompt) Compare Theories:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Analyze two or more theories, highlighting their similarities and differences.</p><p><strong>Best Used For:</strong> Academic study, comparative analysis, understanding different frameworks.</p></div></div> <div class="prompt-container" id="A3.32"><p>32. (Toolkit Prompt) Contrast Ideas:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Focus specifically on the differences between two or more ideas or concepts.</p><p><strong>Best Used For:</strong> Clarifying distinctions, critical analysis, highlighting unique features.</p></div></div> <div class="prompt-container" id="A3.33"><p>33. (Toolkit Prompt) Summarize Findings:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Condense the key results or conclusions from research, data analysis, or a text.</p><p><strong>Best Used For:</strong> Quickly understanding research outcomes, reporting results, executive summaries.</p></div></div> <div class="prompt-container" id="A3.34"><p>34. (Toolkit Prompt) Detail Process:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Describe the steps or stages involved in a particular process in a thorough manner.</p><p><strong>Best Used For:</strong> Instruction manuals, process documentation, understanding how things work.</p></div></div> <div class="prompt-container" id="A3.35"><p>35. (Toolkit Prompt) Illustrate Example:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Provide a concrete example to clarify a concept, rule, or idea.</p><p><strong>Best Used For:</strong> Teaching, making abstract ideas tangible, reinforcing understanding.</p></div></div> <div class="prompt-container" id="A3.36"><p>36. (Toolkit Prompt) Clarify Meaning:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Explain the meaning of something ambiguous, complex, or potentially misunderstood.</p><p><strong>Best Used For:</strong> Resolving confusion, interpreting texts or statements, ensuring clear communication.</p></div></div> <div class="prompt-container" id="A3.37"><p>37. (Toolkit Prompt) Provide Context:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Supply background information or surrounding circumstances necessary to understand an event, statement, or idea.</p><p><strong>Best Used For:</strong> Historical analysis, interpreting literature or news, understanding motivations.</p></div></div> <div class="prompt-container" id="A3.38"><p>38. (Toolkit Prompt) Deep Dive:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Request a thorough, in-depth exploration of a specific topic, going beyond surface-level information.</p><p><strong>Best Used For:</strong> Specialized research, gaining expert-level understanding, comprehensive learning.</p></div></div> <div class="prompt-container" id="A3.39"><p>39. (Toolkit Prompt) Teach Me:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Instruct the AI to act as a tutor and explain a subject or skill in a structured way.</p><p><strong>Best Used For:</strong> Learning new skills or subjects, personalized education.</p></div></div> <div class="prompt-container" id="A3.40"><p>40. (Toolkit Prompt) Learn About:</p><div class="prompt-synopsis"><p><strong>Function:</strong> A general request for information gathering and explanation on a specified topic.</p><p><strong>Best Used For:</strong> Initial research, exploring new areas of interest.</p></div></div> <div class="prompt-container" id="A3.41"><p>41. (Toolkit Prompt) Understand Why:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Seek explanation for the reasons or causes behind a phenomenon, event, or statement.</p><p><strong>Best Used For:</strong> Causal analysis, deeper understanding, critical inquiry.</p></div></div> <div class="prompt-container" id="A3.42"><p>42. (Toolkit Prompt) Explore History:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Request information about the historical background, development, or origins of a subject.</p><p><strong>Best Used For:</strong> Historical research, understanding context, tracing evolution.</p></div></div> <div class="prompt-container" id="A3.43"><p>43. (Toolkit Prompt) Analyze Data:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Examine a dataset to identify patterns, trends, correlations, or insights.</p><p><strong>Best Used For:</strong> Data science, research analysis, business intelligence. Requires data input.</p></div></div> <div class="prompt-container" id="A3.44"><p>44. (Toolkit Prompt) Interpret Results:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Explain the meaning and significance of specific results (e.g., from an experiment, analysis, or test).</p><p><strong>Best Used For:</strong> Understanding research outcomes, data analysis reporting, evaluating significance.</p></div></div> <div class="prompt-container" id="A3.45"><p>45. (Toolkit Prompt) Identify Trends:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Spot general directions or patterns of change within data or over time.</p><p><strong>Best Used For:</strong> Market analysis, forecasting, data interpretation.</p></div></div> <div class="prompt-container" id="A3.46"><p>46. (Toolkit Prompt) Connect Ideas:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Find and explain the relationships or links between different concepts or pieces of information.</p><p><strong>Best Used For:</strong> Synthesis, systems thinking, building conceptual frameworks.</p></div></div> <div class="prompt-container" id="A3.47"><p>47. (Toolkit Prompt) Relate Concepts:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Show how different concepts are associated or relevant to each other.</p><p><strong>Best Used For:</strong> Explaining connections, building understanding, analogical reasoning.</p></div></div> <div class="prompt-container" id="A3.48"><p>48. (Toolkit Prompt) Break Down:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Deconstruct a complex topic, process, or problem into smaller, more manageable parts.</p><p><strong>Best Used For:</strong> Simplifying complexity, analysis, planning, instruction.</p></div></div> <div class="prompt-container" id="A3.49"><p>49. (Toolkit Prompt) Historical Context:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Provide the historical background necessary to understand a specific event, person, or work.</p><p><strong>Best Used For:</strong> Deepening understanding of history, literature, or current events.</p></div></div> <div class="prompt-container" id="A3.50"><p>50. (Toolkit Prompt) Future Implications:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Explore the potential future consequences or developments stemming from a current situation, trend, or decision.</p><p><strong>Best Used For:</strong> Forecasting, strategic planning, risk assessment, future studies.</p></div></div> </div> </details> <details id="A4"> <summary>A4: Text Refinement & Improvement (General)</summary> <div> <!-- SECTION SYSTEM PROMPT START - SECTION_ID: A4 --> <div class="system-prompt-block"> <h4>System Instruction</h4> <p><strong>Context:</strong> Text Refinement & Improvement (General)</p> <p>Adopt the persona of a <strong>Helpful Editor and Proofreader</strong> unless an <strong>'Act as...'</strong> role or <code>((Expert Role))</code> is specified in the task prompt. Prioritize the specific refinement goal mentioned (e.g., clarity, conciseness, grammar, flow).</p> <p><strong>Internal Steps (Consider these when responding):</strong></p> <ul> <li>Identify the specific improvement requested (e.g., fix grammar, enhance flow, simplify).</li> <li>Analyze the provided text focusing on that specific aspect.</li> <li>Suggest concrete revisions or directly rewrite the text to achieve the goal.</li> <li>Briefly explain the rationale for key changes if helpful for learning.</li> </ul> <p>Focus on improving the provided text according to the user's specific instruction. Aim for clear, correct, and effective revisions or suggestions.</p> </div> <!-- SECTION SYSTEM PROMPT END - SECTION_ID: A4 --> <div class="prompt-container" id="A4.1"> <p>1. "Check this text for [errors, tone, consistency]..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Performs general proofreading and editing, focusing on specified areas like errors, tone, or consistency.</p> <p><strong>Best Used For:</strong> Quick reviews, identifying major issues in drafts, ensuring adherence to specific guidelines. Requires providing the text and specifying areas to check.</p> </div> </div> <div class="prompt-container" id="A4.2"> <p>2. "Improve the clarity and conciseness of..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Rewrites text to be easier to understand and more direct, removing unnecessary words or convoluted phrasing.</p> <p><strong>Best Used For:</strong> Editing drafts, simplifying complex writing, enhancing communication effectiveness. Requires providing the text.</p> </div> </div> <div class="prompt-container" id="A4.3"> <p>3. "Improve the readability of..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Focuses on making text easier for the intended audience to read and comprehend, potentially adjusting sentence structure, vocabulary, and formatting.</p> <p><strong>Best Used For:</strong> Optimizing content for specific audiences, enhancing user experience for online text, improving accessibility. Requires providing the text.</p> </div> </div> <div class="prompt-container" id="A4.4"> <p>4. "Paraphrase this complex paragraph in simpler terms..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Restates a difficult passage in easier-to-understand language while preserving the original meaning.</p> <p><strong>Best Used For:</strong> Understanding complex texts, explaining difficult concepts, simplifying source material. Requires providing the paragraph.</p> </div> </div> <div class="prompt-container" id="A4.5"> <p>5. "Review this proposal for clarity and completeness..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Evaluates a proposal based on specific criteria: whether it's easy to understand and includes all necessary information.</p> <p><strong>Best Used For:</strong> Peer review simulation, improving grant/business proposals, ensuring all requirements are met. Requires providing the proposal.</p> </div> </div> <div class="prompt-container" id="A4.6"> <p>6. "Rewrite this article from a neutral perspective..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Removes biased language, opinions, and loaded terms to present information objectively.</p> <p><strong>Best Used For:</strong> Editing opinion pieces for neutrality, creating objective summaries, analyzing media bias. Requires providing the article.</p> </div> </div> <div class="prompt-container" id="A4.7"> <p>7. "Simplify this technical document for a general audience..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Translates technical jargon, complex procedures, and specialized concepts into language accessible to non-experts.</p> <p><strong>Best Used For:</strong> Creating user manuals, public science communication, explaining technical work to laypersons. Requires providing the document.</p> </div> </div> <div class="prompt-container" id="A4.8"> <p>8. "Rewrite this complex sentence in a more active and engaging voice."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Improves sentence structure by converting passive voice to active voice and making the language more direct and dynamic.</p> <p><strong>Best Used For:</strong> Enhancing prose style, making writing more impactful, improving clarity. Requires providing the sentence.</p> </div> </div> <div class="prompt-container" id="A4.9"> <p>9. "Review this piece of writing for style, tone, and overall effectiveness."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Provides a holistic evaluation of a text, considering its stylistic choices, emotional coloring, and success in achieving its purpose.</p> <p><strong>Best Used For:</strong> Comprehensive editing feedback, evaluating drafts, assessing communication impact. Requires providing the writing.</p> </div> </div> <!-- Adding relevant Toolkit Prompts --> <div class="prompt-container" id="A4.10"><p>10. (Toolkit Prompt) Enhance Clarity:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Focus on making the meaning of the text clearer and less ambiguous.</p><p><strong>Best Used For:</strong> Editing technical documents, instructions, complex explanations.</p></div></div> <div class="prompt-container" id="A4.11"><p>11. (Toolkit Prompt) Improve Flow:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Adjust sentence transitions and paragraph structure for a smoother reading experience.</p><p><strong>Best Used For:</strong> Editing essays, articles, narratives; improving coherence.</p></div></div> <div class="prompt-container" id="A4.12"><p>12. (Toolkit Prompt) Increase Engagement:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Revise text to make it more interesting, captivating, or interactive for the reader.</p><p><strong>Best Used For:</strong> Marketing copy, blog posts, creative writing, educational materials.</p></div></div> <div class="prompt-container" id="A4.13"><p>13. (Toolkit Prompt) Strengthen Argument:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Refine the logical structure, evidence, and reasoning within an argumentative piece.</p><p><strong>Best Used For:</strong> Editing persuasive essays, debates, proposals; improving logical coherence.</p></div></div> <div class="prompt-container" id="A4.14"><p>14. (Toolkit Prompt) Refine Tone:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Adjust the language and style to better match the intended mood or attitude (e.g., more formal, more casual, more empathetic).</p><p><strong>Best Used For:</strong> Aligning text with brand voice, tailoring communication for specific audiences.</p></div></div> <div class="prompt-container" id="A4.15"><p>15. (Toolkit Prompt) Correct Grammar:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Identify and fix grammatical errors (e.g., subject-verb agreement, tense consistency).</p><p><strong>Best Used For:</strong> Proofreading any text for accuracy and professionalism.</p></div></div> <div class="prompt-container" id="A4.16"><p>16. (Toolkit Prompt) Fix Punctuation:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Correct errors in punctuation usage (e.g., commas, semicolons, apostrophes).</p><p><strong>Best Used For:</strong> Proofreading, ensuring clarity and adherence to conventions.</p></div></div> <div class="prompt-container" id="A4.17"><p>17. (Toolkit Prompt) Check Spelling:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Identify and correct spelling mistakes.</p><p><strong>Best Used For:</strong> Basic proofreading for accuracy.</p></div></div> <div class="prompt-container" id="A4.18"><p>18. (Toolkit Prompt) Reduce Wordiness:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Eliminate unnecessary words and phrases to make the writing more concise.</p><p><strong>Best Used For:</strong> Editing for brevity, improving clarity, meeting word count limits.</p></div></div> <div class="prompt-container" id="A4.19"><p>19. (Toolkit Prompt) Add Detail:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Expand on existing points by adding more specific information, examples, or descriptions.</p><p><strong>Best Used For:</strong> Developing ideas, enhancing descriptions, providing evidence.</p></div></div> <div class="prompt-container" id="A4.20"><p>20. (Toolkit Prompt) Simplify Language:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Replace complex vocabulary and sentence structures with simpler alternatives.</p><p><strong>Best Used For:</strong> Improving accessibility, writing for broader audiences, clarifying technical text.</p></div></div> <div class="prompt-container" id="A4.21"><p>21. (Toolkit Prompt) Make Concise:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Focus on brevity and removing redundancy to express ideas efficiently.</p><p><strong>Best Used For:</strong> Summaries, headlines, technical writing, improving clarity.</p></div></div> <div class="prompt-container" id="A4.22"><p>22. (Toolkit Prompt) Elaborate Further:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Provide more in-depth explanation or discussion on a specific point.</p><p><strong>Best Used For:</strong> Developing arguments, clarifying complex ideas, adding supporting details.</p></div></div> <div class="prompt-container" id="A4.23"><p>23. (Toolkit Prompt) Provide Examples:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Add concrete examples to illustrate a concept, argument, or statement.</p><p><strong>Best Used For:</strong> Improving understanding, making abstract ideas tangible, supporting claims.</p></div></div> <div class="prompt-container" id="A4.24"><p>24. (Toolkit Prompt) Rewrite Concisely:</p><div class="prompt-synopsis"><p><strong>Function:</strong> A direct instruction to shorten and tighten the provided text.</p><p><strong>Best Used For:</strong> Editing for length, summarizing, improving efficiency.</p></div></div> <div class="prompt-container" id="A4.25"><p>25. (Toolkit Prompt) Rephrase Clearly:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Restate a sentence or passage in a way that is easier to understand, focusing on clarity.</p><p><strong>Best Used For:</strong> Fixing confusing sentences, simplifying language, improving communication.</p></div></div> <div class="prompt-container" id="A4.26"><p>26. (Toolkit Prompt) Polish Text:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Perform a final review and refinement of the text, focusing on style, flow, grammar, and overall presentation.</p><p><strong>Best Used For:</strong> Final editing stages, preparing text for publication or submission.</p></div></div> <div class="prompt-container" id="A4.27"><p>27. (Toolkit Prompt) Optimize Readability:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Apply principles of readability (e.g., sentence length, vocabulary, structure) to make text easier to scan and comprehend.</p><p><strong>Best Used For:</strong> Web content, instructional materials, writing for diverse audiences.</p></div></div> <div class="prompt-container" id="A4.28"><p>28. (Toolkit Prompt) Elevate Style:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Improve the sophistication, elegance, or impact of the writing style through word choice, sentence structure, and figurative language.</p><p><strong>Best Used For:</strong> Creative writing revision, refining formal documents, enhancing persuasive appeals.</p></div></div> <div class="prompt-container" id="A4.29"><p>29. (Toolkit Prompt) Professional Tone:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Adjust the language and style to be appropriate for a formal business or professional context.</p><p><strong>Best Used For:</strong> Editing business communications, reports, proposals.</p></div></div> </div> </details> <details id="A5"> <summary>A5: Data Handling, Organization & Information Extraction (General)</summary> <div> <!-- SECTION SYSTEM PROMPT START - SECTION_ID: A5 --> <div class="system-prompt-block"> <h4>System Instruction</h4> <p><strong>Context:</strong> Data Handling, Organization & Information Extraction (General)</p> <p>Adopt the persona of an <strong>Information Organizer and Data Interpreter</strong> unless an <strong>'Act as...'</strong> role or <code>((Expert Role))</code> is specified in the task prompt.</p> <p><strong>Internal Steps (Consider these when responding):</strong></p> <ul> <li>Identify the type of data/information provided and the desired output (e.g., summary, list, categorization, analysis, timeline).</li> <li>Apply logical structuring principles (chronology, categorization, comparison).</li> <li>Extract relevant information accurately.</li> <li>Identify patterns or key points as requested.</li> <li>Present the output in a clear, organized format (use lists, tables, etc., where appropriate).</li> </ul> <p>Focus on accurate extraction, logical organization, and clear presentation of information based on the prompt's requirements.</p> </div> <!-- SECTION SYSTEM PROMPT END - SECTION_ID: A5 --> <div class="prompt-container" id="A5.1"> <p>1. "Analyze the impact of..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Evaluates the effects or consequences of a specific event, action, or variable on another.</p> <p><strong>Best Used For:</strong> Cause-and-effect analysis, historical assessment, policy evaluation, scientific inquiry. Requires specifying what is impacting what.</p> </div> </div> <div class="prompt-container" id="A5.2"> <p>2. "Analyze the strengths/weaknesses of..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Performs a balanced evaluation, identifying both positive and negative aspects of a subject.</p> <p><strong>Best Used For:</strong> SWOT analysis (partial), critical reviews, comparative analysis, decision-making preparation. Requires specifying the subject.</p> </div> </div> <div class="prompt-container" id="A5.3"> <!-- Specific A5.3 DUPLICATES prompt --> <p>3. "DUPLICATES: [Input List/Text]. Identify and handle duplicates based on [Criteria - e.g., case-insensitive, exact match] by [Action - e.g., removing, listing, counting]."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Identifies and processes duplicate entries within a list or text according to specified rules and actions.</p> <p><strong>Best Used For:</strong> Cleaning lists, finding unique items, data deduplication. Requires input list, criteria, and desired action.</p> </div> </div> <div class="prompt-container" id="A5.4"> <p>4. "Categorize these items based on..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Sorts or groups items according to specified criteria or characteristics.</p> <p><strong>Best Used For:</strong> Data organization, classification tasks, information structuring, building taxonomies. Requires providing the items and categorization criteria.</p> </div> </div> <div class="prompt-container" id="A5.5"> <p>5. "Check this data for accuracy and consistency..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Reviews a dataset for errors, outliers, contradictions, or formatting issues.</p> <p><strong>Best Used For:</strong> Data cleaning, quality assurance, research preparation (requires AI capability for data analysis or clear data input).</p> </div> </div> <div class="prompt-container" id="A5.6"> <p>6. "Compare and contrast [X] and [Y]..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Identifies both the similarities and differences between two specified subjects.</p> <p><strong>Best Used For:</strong> Comparative analysis, highlighting distinctions, understanding relationships between concepts. Requires specifying X and Y.</p> </div> </div> <div class="prompt-container" id="A5.7"> <p>7. "Compile a list of resources for..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Gathers and lists relevant sources of information (e.g., websites, books, articles) on a specific topic.</p> <p><strong>Best Used For:</strong> Research assistance, creating bibliographies or reading lists, information discovery. Requires specifying the topic.</p> </div> </div> <div class="prompt-container" id="A5.8"> <p>8. "Condense this information into..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Summarizes or shortens a body of information into a more concise format (e.g., bullet points, abstract, shorter paragraph).</p> <p><strong>Best Used For:</strong> Summarization, creating abstracts, extracting key points, requires specifying the desired format/length. Requires providing the information.</p> </div> </div> <div class="prompt-container" id="A5.9"> <p>9. "Construct a timeline of events for..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Organizes events into chronological order, often highlighting key dates and descriptions.</p> <p><strong>Best Used For:</strong> Historical summaries, project planning, understanding sequences of events. Requires specifying the subject/period.</p> </div> </div> <div class="prompt-container" id="A5.10"> <p>10. "Evaluate the arguments presented in..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Critically assesses the reasoning, evidence, and logical soundness of arguments within a text or speech.</p> <p><strong>Best Used For:</strong> Critical analysis, debate preparation, evaluating persuasive content. Requires providing the arguments/text.</p> </div> </div> <div class="prompt-container" id="A5.11"> <p>11. "Extract relevant information from these documents regarding..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Scans provided documents to find and pull out specific data points or information related to a query.</p> <p><strong>Best Used For:</strong> Research assistance, data extraction from multiple sources, information retrieval. Requires providing the documents and specifying the target information.</p> </div> </div> <div class="prompt-container" id="A5.12"> <p>12. "Extract key takeaways from..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Identifies and summarizes the most important points or conclusions from a text, meeting, or presentation.</p> <p><strong>Best Used For:</strong> Summarization, understanding core messages, creating concise reports. Requires providing the source material.</p> </div> </div> <div class="prompt-container" id="A5.13"> <p>13. "Find recurring patterns in this dataset..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Analyzes data to identify repeating trends, sequences, or correlations.</p> <p><strong>Best Used For:</strong> Data analysis, trend identification, pattern recognition, requires AI data analysis capability or clear data input.</p> </div> </div> <div class="prompt-container" id="A5.14"> <p>14. "Forecast the potential impact of [policy] on..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Predicts the likely consequences or effects of a specific policy on a particular area or group.</p> <p><strong>Best Used For:</strong> Policy analysis, strategic planning, impact assessment, requires specifying policy and target area.</p> </div> </div> <div class="prompt-container" id="A5.15"> <p>15. "Identify the core assumptions in..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Deconstructs an argument, plan, or statement to find the underlying, often unstated, beliefs it relies upon.</p> <p><strong>Best Used For:</strong> Critical thinking, argument analysis, risk assessment (identifying points of failure). Requires providing the text/plan.</p> </div> </div> <div class="prompt-container" id="A5.16"> <p>16. "Identify the central themes explored in..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Analyzes a work (literary, artistic, etc.) to determine its main underlying ideas or recurring concepts.</p> <p><strong>Best Used For:</strong> Literary analysis, thematic exploration, understanding deeper meanings. Requires providing the work or its description.</p> </div> </div> <div class="prompt-container" id="A5.17"> <p>17. "Interpret the symbolism present in..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Analyzes elements within a work to uncover their potential symbolic meanings and contributions to the overall message.</p> <p><strong>Best Used For:</strong> Literary/art analysis, understanding figurative language, exploring deeper layers of meaning. Requires providing the work/description.</p> </div> </div> <div class="prompt-container" id="A5.18"> <p>18. "Interpret this data/chart..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Explains the meaning and significance of visualized data presented in a chart or graph.</p> <p><strong>Best Used For:</strong> Data analysis reporting, understanding visual information, presentation support. Requires providing the data/chart.</p> </div> </div> <div class="prompt-container" id="A5.19"> <p>19. "List the key advantages and disadvantages of..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Provides a balanced overview by enumerating the main pros and cons of a subject.</p> <p><strong>Best Used For:</strong> Evaluation, comparison, decision-making support. Requires specifying the subject.</p> </div> </div> <div class="prompt-container" id="A5.20"> <p>20. "Map out the organizational structure of..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Describes or visualizes (conceptually) the hierarchy, roles, and reporting relationships within an organization.</p> <p><strong>Best Used For:</strong> Business analysis, understanding organizational design, onboarding materials. Requires providing info about the organization.</p> </div> </div> <div class="prompt-container" id="A5.21"> <p>21. "Organize this data into a visually appealing format..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Restructures data for better presentation and comprehension, often suggesting tables, charts, or summaries.</p> <p><strong>Best Used For:</strong> Data presentation, report generation, making complex data understandable. Requires providing the data and desired format suggestions help.</p> </div> </div> <div class="prompt-container" id="A5.22"> <p>22. "Prioritize these tasks based on urgency and importance..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Ranks tasks using a common prioritization matrix (e.g., Eisenhower Matrix) or specified criteria.</p> <p><strong>Best Used For:</strong> Time management, project planning, task organization. Requires providing the tasks.</p> </div> </div> <div class="prompt-container" id="A5.23"> <p>23. "Rank these options based on their effectiveness in..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Orders a set of options according to how well they achieve a specific goal or meet a criterion.</p> <p><strong>Best Used For:</strong> Decision analysis, comparative evaluation, solution selection. Requires providing options and effectiveness criteria.</p> </div> </div> <div class="prompt-container" id="A5.24"> <p>24. "Summarize the main arguments presented in..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Extracts and concisely presents the core claims and reasoning from an argumentative text.</p> <p><strong>Best Used For:</strong> Understanding debates, summarizing research papers or opinion pieces, briefing preparation. Requires providing the text.</p> </div> </div> <div class="prompt-container" id="A5.25"> <p>25. "Summarize the main points of..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Condenses the key information or topics covered in a text, meeting, or presentation.</p> <p><strong>Best Used For:</strong> General summarization, creating abstracts, meeting minutes generation. Requires providing the source material.</p> </div> </div> <div class="prompt-container" id="A5.26"> <p>26. "Synthesize information from diverse sources to create a cohesive overview of..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Integrates findings, ideas, or data from multiple sources into a single, coherent narrative or analysis.</p> <p><strong>Best Used For:</strong> Literature reviews, research reports, comprehensive briefings, connecting disparate information. Requires providing the sources or key info from them.</p> </div> </div> <div class="prompt-container" id="A5.27"> <p>27. "Update this report with the most recent findings..."</p> <div class="prompt-synopsis"> <p><strong>Function:</strong> Incorporates new information or data into an existing report, revising conclusions or sections as needed.</p> <p><strong>Best Used For:</strong> Maintaining current documentation, research updates, ongoing project reporting. Requires the original report and new findings.</p> </div> </div> <div class="prompt-container" id="A5.28"><p>28. (Toolkit Prompt) Report Summary:</p><div class="prompt-synopsis"><p><strong>Function:</strong> Create a concise overview of the key findings, conclusions, and recommendations from a longer report.</p><p><strong>Best Used For:</strong> Executive briefings, quickly understanding report contents, communication.</p></div></div> </div> </details> </div> </details> <!-- End Section A --> <details id="B"> <summary>B: Prompt Starters & Functional Verbs (Reference)</summary> <div> <!-- No system prompt needed for reference sections --> <details id="B1"> <summary>B1: Action Verb + Focus Area Starters</summary> <div class="reference-list"> <ul> <li>Act as a [Role, e.g., historian, scientist]...</li> <li>Adapt this text for [Audience, e.g., children, experts]...</li> <li>Analyze the cultural significance of...</li> <li>Analyze the impact of...</li> <li>Analyze the strengths/weaknesses of...</li> <li>Apply the principles of [theory] to...</li> <li>Argue for/against the position that...</li> <li>Argue for the importance of [value] in...</li> <li>Assess the feasibility of...</li> <li>Assess the potential risks and rewards of...</li> <li>Brainstorm ideas for...</li> <li>Brainstorm innovative solutions for...</li> <li>Break down the concept of [complex idea] into manageable steps...</li> <li>Break down the steps involved in...</li> <li>Categorize these events based on their impact on...</li> <li>Categorize these items based on...</li> <li>Check this data for accuracy and consistency...</li> <li>Check this text for [errors, tone, consistency]...</li> <li>Clarify the meaning of...</li> <li>Clarify the role of [element] in...</li> <li>Compare and contrast different approaches to [task]...</li> <li>Compare and contrast [X] and [Y]...</li> <li>Compile a list of best practices for...</li> <li>Compile a list of resources for...</li> <li>Compose a [poem, song, story] about...</li> <li>Compose a fictional interview with...</li> <li>Condense this information into...</li> <li>Condense this research paper into a concise summary...</li> <li>Construct a narrative timeline of the development of...</li> <li>Construct a timeline of events for...</li> <li>Create a case study about...</li> <li>Create a checklist for...</li> <li>Create a comprehensive checklist for...</li> <li>Create a detailed case study of...</li> <li>Create a dialogue between characters discussing...</li> <li>Create a dialogue between...</li> <li>Create an analogy for...</li> <li>Create an analogy to explain the concept of [abstract term]...</li> <li>Create an outline for a presentation on...</li> <li>Create an outline for...</li> <li>Critique the effectiveness of [strategy]...</li> <li>Critique this [plan, proposal, text]...</li> <li>Debug this code...</li> <li>Debug this process to identify the root cause of...</li> <li>Define [technical term] in accessible language...</li> <li>Define [term] in simple language...</li> <li>Describe the impact of [event] on [group]...</li> <li>Describe the process of...</li> <li>Design a system to improve...</li> <li>Design an experiment to test...</li> <li>Develop a marketing slogan for...</li> <li>Develop a strategy to achieve...</li> <li>Develop a training module for...</li> <li>Draft a [letter, email, proposal] to...</li> <li>Draft a formal proposal to...</li> <li>Elaborate on the concept of...</li> <li>Elaborate on the potential consequences of...</li> <li>Evaluate the arguments presented in...</li> <li>Evaluate the validity of the claims made in...</li> <li>Explain [complex topic] simply (ELI5)...</li> <li>Explain [scientific principle] using everyday examples...</li> <li>Explain the historical significance of...</li> <li>Explain the significance of...</li> <li>Explain this algorithm in simple terms...</li> <li>Explore the implications of...</li> <li>Explore the philosophical implications of...</li> <li>Extract relevant information from these documents regarding...</li> <li>Fact-check these statements for accuracy and bias...</li> <li>Fact-check the following statements...</li> <li>Find alternative methods for...</li> <li>Find alternative solutions for...</li> <li>Find patterns in this data...</li> <li>Find recurring patterns in this dataset...</li> <li>Forecast the potential impact of [policy] on...</li> <li>Forecast the potential outcomes of...</li> <li>Formulate counter-arguments to the position that...</li> <li>Formulate counter-arguments to...</li> <li>Formulate interview questions to assess...</li> <li>Generate creative titles for a project about...</li> <li>Generate discussion questions about...</li> <li>Generate potential titles for...</li> <li>Generate thought-provoking discussion questions about...</li> <li>Give specific examples of...</li> <li>Hypothesize the reasons for...</li> <li>Hypothesize the underlying causes of...</li> <li>Identify the assumptions made in...</li> <li>Identify the core assumptions in...</li> <li>Identify the key themes in...</li> <li>Illustrate the differences and similarities between...</li> <li>Illustrate the differences between...</li> <li>Imagine the potential future of [industry]...</li> <li>Imagine you are [historical figure] and describe...</li> <li>Imagine you are [Persona] and respond to...</li> <li>Implement a plan for...</li> <li>Implement a strategic plan to...</li> <li>Improve the clarity and conciseness of...</li> <li>Improve the readability of...</li> <li>Interpret the symbolism present in...</li> <li>Interpret this data/chart...</li> <li>Investigate the background of...</li> <li>Investigate the historical context surrounding...</li> <li>Justify the decision to...</li> <li>Justify the decision-making process behind...</li> <li>List the key advantages and disadvantages of...</li> <li>List the pros and cons of...</li> <li>Map out the organizational structure of...</li> <li>Map out the structure of...</li> <li>Optimize this process for efficiency...</li> <li>Optimize this workflow for maximum productivity...</li> <li>Organize this data into a visually appealing format...</li> <li>Organize this information into [format, e.g., table]...</li> <li>Paraphrase this complex paragraph in simpler terms...</li> <li>Paraphrase this section...</li> <li>Persuade [audience] about...</li> <li>Persuade [target audience] to support...</li> <li>Plan a detailed agenda for a conference on...</li> <li>Plan the agenda for a meeting about...</li> <li>Predict the next steps in...</li> <li>Predict the potential outcomes of [action]...</li> <li>Prioritize these tasks based on urgency and importance...</li> <li>Prioritize these tasks based on...</li> <li>Propose a name for...</li> <li>Propose a new approach to...</li> <li>Provide a comprehensive explanation of...</li> <li>Provide a step-by-step guide for...</li> <li>Provide constructive feedback on...</li> <li>Rank these options based on their effectiveness in...</li> <li>Rank these options by...</li> <li>Recommend improvements for...</li> <li>Reconstruct the events leading up to...</li> <li>Refine this draft to be more [adjective, e.g., concise]...</li> <li>Reframe this challenge as an opportunity for...</li> <li>Report the findings on...</li> <li>Research the ethical considerations surrounding...</li> <li>Research the latest developments in...</li> <li>Resolve the conflict between...</li> <li>Review this document for clarity...</li> <li>Rewrite this article from a neutral perspective...</li> <li>Rewrite this from a different perspective...</li> <li>Role-play a negotiation between...</li> <li>Role-play a scenario involving...</li> <li>Simplify this technical explanation...</li> <li>Solve this complex problem using a step-by-step approach...</li> <li>Solve this problem: [problem description]...</li> <li>Structure a comprehensive report on...</li> <li>Structure a presentation about...</li> <li>Suggest creative ways to...</li> <li>Suggest innovative ways to...</li> <li>Summarize the main arguments presented in...</li> <li>Summarize the main points of...</li> <li>Synthesize information from diverse sources to create a cohesive overview of...</li> <li>Synthesize information from these sources...</li> <li>Teach me the basics of...</li> <li>Teach me the fundamental principles of...</li> <li>Tell a compelling story about...</li> <li>Tell a story about...</li> <li>Test the validity of this hypothesis...</li> <li>Test the validity of...</li> <li>Translate this document into [language] while preserving its original meaning...</li> <li>Translate this text into [language]...</li> <li>Troubleshoot potential issues with...</li> <li>Troubleshoot potential problems with...</li> <li>Turn these fragmented notes into a well-structured essay...</li> <li>Turn these notes into a coherent paragraph...</li> <li>Update this information based on...</li> <li>Update this report with the most recent findings...</li> <li>Write a compelling product description for...</li> <li>Write code in [programming language] to automate the process of...</li> <li>Write code to [perform a function] in [language]...</li> </ul> </div> </details> <details id="B2"> <summary>B2: Consolidated Functional Verbs (Reference List)</summary> <div class="reference-list"> <ul> <li>Address</li> <li>Adapt</li> <li>Advise</li> <li>Analyze</li> <li>Argue</li> <li>Assess</li> <li>Brainstorm</li> <li>Build</li> <li>Categorize</li> <li>Characterize</li> <li>Chronicle</li> <li>Clarify</li> <li>Classify</li> <li>Compare</li> <li>Conceptualize</li> <li>Condense</li> <li>Connect</li> <li>Construct</li> <li>Contrast</li> <li>Convert</li> <li>Convince</li> <li>Correct</li> <li>Create</li> <li>Critique</li> <li>Customize</li> <li>Deduce</li> <li>Define</li> <li>Depict</li> <li>Describe</li> <li>Design</li> <li>Detail</li> <li>Develop</li> <li>Discover</li> <li>Document</li> <li>Edit</li> <li>Educate</li> <li>Elaborate</li> <li>Emphasize</li> <li>Encourage</li> <li>Enhance</li> <li>Evaluate</li> <li>Execute</li> <li>Exemplify</li> <li>Expand</li> <li>Explain</li> <li>Find</li> <li>Focus</li> <li>Forecast</li> <li>Formulate</li> <li>Generate</li> <li>Group</li> <li>Guide</li> <li>Handle</li> <li>Highlight</li> <li>Hypothesize</li> <li>Identify</li> <li>Illustrate</li> <li>Imagine</li> <li>Implement</li> <li>Improve</li> <li>Infer</li> <li>Inspire</li> <li>Instruct</li> <li>Interpret</li> <li>Justify</li> <li>Lengthen</li> <li>List</li> <li>Locate</li> <li>Manage</li> <li>Modify</li> <li>Motivate</li> <li>Narrate</li> <li>Order</li> <li>Organize</li> <li>Outline</li> <li>Paraphrase</li> <li>Personalize</li> <li>Persuade</li> <li>Plan</li> <li>Portray</li> <li>Predict</li> <li>Prioritize</li> <li>Proofread</li> <li>Rank</li> <li>Recommend</li> <li>Record</li> <li>Recount</li> <li>Refine</li> <li>Relate</li> <li>Report</li> <li>Research</li> <li>Resolve</li> <li>Review</li> <li>Rewrite</li> <li>Sequence</li> <li>Shorten</li> <li>Simplify</li> <li>Solve</li> <li>Speculate</li> <li>Structure</li> <li>Suggest</li> <li>Summarize</li> <li>Synthesize</li> <li>Tackle</li> <li>Teach</li> <li>Tell</li> <li>Test</li> <li>Transform</li> <li>Translate</li> <li>Update</li> <li>Validate</li> <li>Verify</li> </ul> </div> </details> </div> </details> <!-- End Section B --> <details id="C"> <summary>C: Meta-Prompting & Reasoning Techniques</summary> <div> <!-- SECTION SYSTEM PROMPT START - SECTION_ID: C (General - applies to C1-C4 unless overridden by C5) --> <div class="system-prompt-block"> <h4>System Instruction</h4> <p><strong>Context:</strong> Meta-Prompting & Reasoning Techniques</p> <p>You are an AI Agent executing specific reasoning processes for meta-prompting tasks, EXCEPT when using prompts from Section C5 (Advanced Prompt Engineering Techniques), which has its own specialized instructions. For C1-C4, your primary goal is to follow the explicitly stated <strong>steps, functions, or framework</strong> outlined in the prompt (e.g., Chain-of-Thought, Step-by-Step, Function Addressing, 6-Task Framework). <strong>Adhere strictly to the requested process.</strong></p> <p>Adopt a <strong>Structured Reasoning Engine</strong> persona unless a compatible <strong>'Act as...'</strong> role or <code>((Expert Role))</code> is specified. If a role is given, perform the reasoning steps *from that perspective*.</p> <p>Focus on transparency in your reasoning, showing your work precisely as requested by the prompt structure. Aim for logical consistency, accuracy, and direct fulfillment of each defined step or function.</p> </div> <!-- SECTION SYSTEM PROMPT END - SECTION_ID: C --> <details id="C1"> <summary>C1: Meta-Prompting Frameworks (6-Task Variants)</summary> <div> <div class="prompt-item" id="C1.1"> <strong>Framework Version 1 (Simplified & Focused)</strong> <p>Task 1: Understand the prompt's core question or request.<br> Task 2: Plan your approach, outlining the steps you'll take to address the prompt.<br> Task 3: Reflect on your reasoning, ensuring it's logical and consistent.<br> Task 4: Compose a clear and relevant response.</p> </div> <div class="prompt-item" id="C1.2"> <strong>Framework Version 2 (Detailed & Comprehensive)</strong> <p>Task 1: Analyze the prompt to identify key information, context, and potential challenges.<br> Task 2: Develop a strategy for addressing the prompt, including outlining objectives, potential resources, and a timeline.<br> Task 3: Evaluate the consistency and logic of your reasoning, making revisions as needed.<br> Task 4: Craft a clear and well-organized response that directly addresses the prompt.<br> Task 5: Provide a step-by-step breakdown of your reasoning, explaining your thought process and any assumptions made.<br> Task 6: Compare the results of your reasoning, response, and breakdown, noting any discrepancies or areas for improvement.</p> </div> <div class="prompt-item" id="C1.3"> <strong>Framework Version 3 (Creative & Interactive)</strong> <p>Task 1: Engage with the prompt by asking yourself questions to clarify its meaning and scope.<br> Task 2: Brainstorm potential solutions or approaches, considering different perspectives and possibilities.<br> Task 3: Select the most promising approach and outline the steps you'll take to implement it.<br> Task 4: Execute your plan, making adjustments as needed based on your progress and feedback.<br> Task 5: Reflect on the outcome, evaluating your process and identifying areas for future improvement.</p> </div> <div class="prompt-item" id="C1.3a"> <strong>Framework Version 3a (The Curious Mind)</strong> <p>Task 1: Ask yourself "Why?" and "What if?" to explore the prompt's depths.<br> Task 2: Imagine different scenarios and perspectives related to the prompt.<br> Task 3: Choose the most intriguing scenario and outline a plan to explore it.<br> Task 4: Dive into the chosen scenario, experimenting with ideas and possibilities.<br> Task 5: Reflect on your journey, noting what you learned and how your perspective shifted.</p> </div> <div class="prompt-item" id="C1.3b"> <strong>Framework Version 3b (The Storyteller)</strong> <p>Task 1: Turn the prompt into a story prompt, envisioning characters and a setting.<br> Task 2: Brainstorm different plotlines and character motivations.<br> Task 3: Choose the most compelling storyline and outline the key events.<br> Task 4: Craft a narrative that brings the story to life, using vivid descriptions and engaging dialogue.<br> Task 5: Reflect on the story you created, considering its themes, impact, and potential for further development.</p> </div> <div class="prompt-item" id="C1.3c"> <strong>Framework Version 3c (The Idea Generator)</strong> <p>Task 1: Think of the prompt as a seed for a new idea, exploring its potential for innovation.<br> Task 2: Brainstorm solutions, inventions, or concepts inspired by the prompt.<br> Task 3: Choose the most promising idea and outline a plan for its development.<br> Task 4: Develop the chosen idea, exploring its feasibility, benefits, and potential applications.<br> Task 5: Reflect on the creative process, considering the challenges and triumphs of generating new ideas.</p> </div> <div class="prompt-item" id="C1.4"> <strong>Framework Version 4 (Explicit Analysis & Reflection)</strong> <p>"Before responding to any prompt, follow these tasks:<br> Task 1: Analyze the prompt to identify relevant information that will assist in formulating a response. Include this analysis before addressing each subsequent step.<br> Task 2: Utilize the insights gained from Task 1 to devise a strategy for planning and evaluating your objectives for upcoming tasks, transforming these insights into a practical response framework.<br> Task 3: Reflect on all decisions made thus far, assessing the consistency and logic of your reasoning and making revisions as necessary.<br> Task 4: Ensure that your response is clear and aligned with the context of the prompt.<br> Task 5: Break down your reasoning process step-by-step, clarifying the relationships and dynamics involved, including any relevant orientations or positions.<br> Task 6: Compare the results of Tasks 3, 4, and 5, and note any differences in the logic or final thoughts."</p> </div> </div> </details> <details id="C2"> <summary>C2: Chain-of-Thought (CoT) & Step-by-Step Reasoning</summary> <div> <div class="prompt-item" id="C2.1"> <strong>1. Basic CoT:</strong> <p>Q: `[Insert complex question or problem]`<br>A: Let's think step by step to solve this.</p> </div> <div class="prompt-item" id="C2.2"> <strong>2. Multi-Step Math Problem with Explanation:</strong> <p>"Sarah has 25 apples. She gives 7 to John and then buys 12 more. If she then divides all her apples equally among 5 friends, how many apples does each friend receive? **Solve this problem by explicitly stating each step of your calculation and the reasoning behind it.**"</p> </div> <div class="prompt-item" id="C2.3"> <strong>3. Logical Deduction with Justification:</strong> <p>"If it rains, the ground will be wet. The ground is wet. Therefore, it must have rained. **Analyze this logical argument step by step. Explain whether the conclusion is necessarily true based on the premises and why.**"</p> <p>(Alternative:) "Premise 1: All mammals are warm-blooded. Premise 2: A whale is a mammal. Conclusion: Therefore, a whale is warm-blooded. **Explain your reasoning step by step to confirm if the conclusion logically follows from the premises.**"</p> </div> <div class="prompt-item" id="C2.4"> <strong>4. Scenario Analysis with Consequence Prediction:</strong> <p>"A new social media platform gains rapid popularity. **Think through the potential short-term and long-term consequences of this rapid growth, considering different aspects like user behavior, data privacy, and societal impact. Explain your reasoning for each predicted consequence.**"</p> </div> <div class="prompt-item" id="C2.5"> <strong>5. Complex Task Decomposition:</strong> <p>"The task is to plan a week-long vacation to a new city. **Break down this task into a sequence of smaller, manageable steps, outlining what needs to be done at each stage, from initial research to the actual trip.**"</p> </div> <div class="prompt-item" id="C2.6"> <strong>6. Diagnostic Reasoning:</strong> <p>"A car is making a strange knocking noise when the engine is running. **Think through the possible causes of this noise, starting with the most common issues and moving to less frequent ones. Explain your reasoning for each potential cause and suggest how to diagnose it.**"</p> <p>(Alternative:) "My computer is running very slowly. I have already tried restarting it. **Think through the potential causes of a slow computer, step by step, and suggest troubleshooting actions in a logical order.**"</p> </div> <div class="prompt-item" id="C2.7"> <strong>7. Decision Making Rationale:</strong> <p>"A company needs to choose between two marketing strategies: Strategy A focuses on social media advertising with a lower budget but potentially wider reach, while Strategy B involves traditional print advertising with a higher budget but a more targeted audience. The company's goal is to increase brand awareness among young adults. **Reason through the pros and cons of each strategy, step by step, before recommending the best approach.**"</p> </div> <div class="prompt-item" id="C2.8"> <strong>8. Creative Writing (Story Generation CoT):</strong> <p>"The old lighthouse stood on a lonely cliff, battered by years of storms. One night, the keeper saw a strange light out at sea. **Develop a short story based on this opening, thinking through the sequence of events, character reactions, and potential conflicts step by step.**"</p> <p>(Alternative:) "A young wizard discovers a powerful but forbidden spell. **Step 1: Think about the wizard's personality and motivations. Step 2: Based on their personality, reason through the internal conflict they might experience when considering using the spell. Step 3: Describe the sequence of thoughts and decisions that lead them to either use or not use the spell.**"</p> </div> <div class="prompt-item" id="C2.9"> <strong>9. Explicit Step-by-Step Instruction:</strong> <p>"To evaluate the feasibility of `[Project Idea]`, please follow these exact steps: 1. Identify the core objectives... 2. List key resources... 3. Analyze risks... 4. Outline milestones... 5. Provide feasibility conclusion with reasoning."</p> </div> <div class="prompt-item" id="C2.10"> <strong>10. Recipe Following with Rationale:</strong> <p>"Follow these steps to make lemonade: 1. Mix lemon juice and sugar. 2. Add water. 3. Stir well. 4. Chill before serving. **For each step, explain the purpose and the expected outcome.**"</p> <p>(Alternative:) "Here are the steps to bake a cake: 1. Preheat... 2. Cream butter/sugar... 3. Beat in eggs... 4. Add dry ingredients... 5. Pour batter... 6. Bake... **Explain each step in detail and why it is important for the final outcome.**"</p> </div> <div class="prompt-item" id="C2.11"> <strong>11. Scientific Explanation with Ordered Steps:</strong> <p>"Explain the process of the water cycle in a clear, step-by-step manner, ensuring you cover evaporation, condensation, precipitation, and collection in the correct order."</p> <p>(Alternative:) "Explain the process of photosynthesis step by step, including the inputs, outputs, and the role of sunlight and chlorophyll."</p> </div> <div class="prompt-item" id="C2.12"> <strong>12. Code Debugging with Sequential Analysis:</strong> <p>"Here is a piece of Python code: `x = 5; y = "hello"; print(x + y)`. **Step 1: Analyze the code line by line. Step 2: Identify the error. Step 3: Explain why this error occurs. Step 4: Suggest a correction to fix the error.**"</p> </div> <div class="prompt-item" id="C2.13"> <strong>13. Historical Analysis with Causal Links:</strong> <p>"Describe the major events that led to World War II. Present these events in chronological order and explain the causal link between each event and the subsequent ones."</p> <p>(Alternative:) "Describe the key events leading up to the French Revolution in chronological order."</p> </div> <div class="prompt-item" id="C2.14"> <strong>14. Problem Solving Algorithm with Defined Stages:</strong> <p>"Describe the steps involved in creating a budget. Stage 1: Track income. Stage 2: Track expenses. Stage 3: Analyze spending. Stage 4: Create spending plan. **Explain the importance of each stage...**"</p> <p>(Alternative:) "Describe the steps involved in the bubble sort algorithm... Provide an example..."</p> <p>(Alternative:) "Outline the steps of the scientific method... Provide a hypothetical example."</p> </div> <div class="prompt-item" id="C2.15"> <strong>15. Complex Problem Solving (Combined):</strong> <p>"A program needs to sort 1000 random numbers efficiently. **Step 1: Identify sorting algorithms. Step 2: Describe steps for each. Step 3: Analyze time complexity. Step 4: Recommend based on complexity.**"</p> </div> <div class="prompt-item" id="C2.16"> <strong>16. Creative Writing with Step-by-Step Dev:</strong> <p>"Develop a character for a fantasy novel. **Step 1: Describe physical appearance. Step 2: Outline backstory/motivations. Step 3: Detail traits/flaws. Step 4: Explain influence on actions.**"</p> </div> </div> </details> <details id="C3"> <summary>C3: Structured Reasoning & Function Addressing</summary> <div> <div class="prompt-item" id="C3.1"> <strong>1. Structured Analysis & Reasoning:</strong> <p>"Analyze the following argument: `[Insert argument text]`. Structure response using headings: Main Claim, Supporting Points, Logical Soundness, Evidence Strength, Counterarguments/Weaknesses, Overall Conclusion."</p> </div> <div class="prompt-item" id="C3.2"> <strong>2. Simulated Internal Monologue / Reasoning Trace:</strong> <p>"Solve this logic puzzle: `[Insert logic puzzle]`. Before giving the final solution, provide your detailed thought process. Explain each deduction, why alternatives were ruled out, how each step leads to the next. Start with 'My thinking process:'."</p> </div> <div class="prompt-item" id="C3.3"> <strong>3. Role-Playing with Process Mandate:</strong> <p>"Act as a meticulous scientific researcher reviewing abstract: `[Insert abstract]`. Must proceed: 1. Summarize Q&F. 2. Identify methodology. 3. Critique strengths/limits (abstract only). 4. Suggest needed info. Present following points explicitly."</p> </div> <div class="prompt-item" id="C3.4"> <strong>4. Task Decomposition & Function Addressing:</strong>
                            <p>"Plan eco-friendly community garden. Address functions sequentially: 1. Site Selection Criteria. 2. Plant Selection Rationale (for `[Climate]`). 3. Resource Management (Water/Compost). 4. Community Involvement."</p>
                            <p>(Alternative:) "Plan surprise party. **Function 1: Identify sub-problems.** **Function 2: Suggest solutions for each.**"</p>
                        </div>
                        <div class="prompt-item" id="C3.5">
                            <strong>5. Self-Correction / Refinement Loop:</strong>
                            <p>"Draft proposal for `[Project X]`. **Step 1: Write draft (max 200 words). Step 2: Critically review, identify 2 weaknesses. Step 3: Rewrite, addressing weaknesses.**"</p>
                        </div>
                         <div class="prompt-item" id="C3.6">
                             <strong>6. Comparative Reasoning with Explicit Criteria:</strong>
                             <p>"Compare `[Option A]` and `[Option B]` for `[Purpose]`. Evaluate explicitly based on: 1. Cost-effectiveness, 2. Ease of Implementation, 3. Scalability, 4. `[User criterion]`. Recommend one option with justification based *only* on criteria."</p>
                         </div>
                         <div class="prompt-item" id="C3.7">
                             <strong>7. Hypothesis Generation and Testing Simulation:</strong>
                             <p>"Observe data: `[Insert data/trend]`. 1. Formulate 2 distinct hypotheses. 2. For each, describe how to confirm/refute it (data/experiment). 3. Explain reasoning connecting data to hypotheses."</p>
                         </div>
                        <div class="prompt-item" id="C3.8">
                            <strong>8. Step-Back / Abstracting:</strong>
                            <p>"User asks for `[Specific request]`. **Step 1: Rephrase user's core need simply. Step 2: Identify ambiguities/missing info. Step 3: Outline plan to fulfill core need, possibly asking clarifying questions.**"</p>
                        </div>
                         <div class="prompt-item" id="C3.9">
                            <strong>9. Sentiment Analysis with Justification:</strong>
                             <p>"Analyze review: 'Product okay, service terrible.' **Function 1: Determine sentiment. Function 2: Identify parts contributing to sentiment. Function 3: Explain reasoning.**"</p>
                        </div>
                         <div class="prompt-item" id="C3.10">
                            <strong>10. Information Extraction with Categorization:</strong>
                             <p>"Read article: `[paste article]`. **Function 1: Extract key features. Function 2: Categorize features (e.g., performance, usability). Function 3: Summarize potential.**"</p>
                         </div>
                         <div class="prompt-item" id="C3.11">
                            <strong>11. Argument Evaluation with Premise Analysis:</strong>
                             <p>"Argument: 'All birds fly. Penguin is bird. Penguin flies.' **Function 1: Identify premises/conclusion. Function 2: Evaluate premise truthfulness. Function 3: Determine logical validity (even if premise false). Explain.**"</p>
                         </div>
                         <div class="prompt-item" id="C3.12">
                            <strong>12. Creative Generation with Constraints:</strong>
                             <p>"Generate poem: robot love. **Function 1: Exactly 4 stanzas. Function 2: 4 lines/stanza. Function 3: Use >=3 tech/machinery metaphors for feelings.**"</p>
                        </div>
                         <div class="prompt-item" id="C3.13">
                            <strong>13. Decision Making with Weighted Criteria:</strong>
                             <p>"Choose office location. Criteria: cost(5), commute(4), size(3). Loc A: cost=8, commute=6, size=7. Loc B: cost=6, commute=8, size=5. **Function 1: Calculate weighted scores. Function 2: Recommend based on scores. Function 3: Explain influence of weighting.**"</p>
                        </div>
                         <div class="prompt-item" id="C3.14">
                             <strong>14. Ethical Reasoning with Function-Based Analysis:</strong>
                             <p>"Company considers AI for customer service. **Function 1: Identify benefits. Function 2: Identify ethical concerns (jobs, privacy, empathy). Function 3: Propose guidelines for ethical implementation.**"</p>
                             <p>(Alternative:) "Company finds flaw in product. **Function 1: Identify ethical considerations. Function 2: Analyze consequences of actions (recall, delay). Function 3: Recommend most ethical course, justify.**"</p>
                         </div>
                         <div class="prompt-item" id="C3.15">
                            <strong>15. Text Analysis (Multi-Function Example):</strong>
                            <p>"Analyze sentence: 'Apple announced its new iPhone 17 in Cupertino, California, on September 15th.' **Function 1: Identify named entities.** **Function 2: Identify relationships between entities.** **Function 3: Summarize core info.**"</p>
                        </div>
                         <div class="prompt-item" id="C3.16">
                            <strong>16. Code Generation (Multi-Function Example):</strong>
                            <p>"User wants Python function: input=list of numbers, return=average. **Function 1: Explain requirements.** **Function 2: Write code.** **Function 3: Provide test cases.**"</p>
                        </div>
                         <div class="prompt-item" id="C3.17">
                            <strong>17. Argumentation (Multi-Function Example):</strong>
                            <p>"Claim: 'AI will surpass human intelligence.' **Function 1: State claim.** **Function 2: Provide 3 supporting arguments.** **Function 3: Acknowledge 1 counterargument.**"</p>
                         </div>
                         <div class="prompt-item" id="C3.18">
                            <strong>18. Information Retrieval (Multi-Function Example):</strong>
                            <p>"User seeks info: climate change impact on polar bears. **Function 1: Identify keywords.** **Function 2: Formulate 3 search queries.** **Function 3: Summarize findings (assume access).**"</p>
                         </div>
                         <div class="prompt-item" id="C3.19">
                             <strong>19. Complex Problem Solving (Combined CoT/Functions):</strong>
                             <p>"Self-driving car at intersection. **Step 1: Identify needed functions (detection, planning, etc.). Step 2: Describe reasoning for each function. Step 3: Explain how functions work together.**"</p>
                         </div>
                    </div>
                </details>

                 <details id="C4">
                    <summary>C4: Question-Based Prompting (Encouraging Deeper Thinking)</summary>
                    <div>
                        <div class="prompt-container" id="C4.1"><p>1. "What if the opposite of [Commonly held belief] were true? What implications might this have for our understanding of the world?"</p></div>
                        <div class="prompt-container" id="C4.2"><p>2. "What are the potential unintended consequences of implementing the following solution to this problem: [Describe a problem and a potential solution]?"</p></div>
                        <div class="prompt-container" id="C4.3"><p>3. "From whose perspective might this situation look different? Consider at least two different viewpoints and explain how their understanding of the situation might vary."</p></div>
                        <div class="prompt-container" id="C4.4"><p>4. "What assumptions are we making when we say [Commonly accepted statement]? Are these assumptions valid, and what might happen if they were not?"</p></div>
                        <div class="prompt-container" id="C4.5"><p>5. "How could the concept of [Choose a concept] be applied in a completely new and unexpected context? Brainstorm at least two novel applications."</p></div>
                        <div class="prompt-container" id="C4.6"><p>6. "What are the ethical considerations surrounding the use of [Choose a technology or practice]? Consider both the potential benefits and potential harms."</p></div>
                        <div class="prompt-container" id="C4.7"><p>7. "What are the underlying principles or mechanisms that explain why [Observed phenomenon] occurs? Explain your understanding in a clear and concise manner."</p></div>
                        <div class="prompt-container" id="C4.8"><p>8. "How might our understanding of [Topic] change in the future based on current trends and emerging evidence?"</p></div>
                        <div class="prompt-container" id="C4.9"><p>9. "What are the limitations of the information we have about [Topic]? What additional information would be helpful to gain a more complete understanding?"</p></div>
                    </div>
                </details>

                 <details id="C5"> <!-- Insert drafted Section C5 here -->
                    <summary>C5: Advanced Prompt Engineering Techniques</summary>
                    <div>
                        <!-- SECTION SYSTEM PROMPT START - SECTION_ID: C5 -->
                        <div class="system-prompt-block">
                            <h4>System Instruction</h4>
                            <p><strong>Context:</strong> Advanced Prompt Engineering Techniques</p>
                            <p>Adopt the persona of a <strong>Prompt Engineering Advisor and AI Interaction Strategist</strong> unless an <strong>'Act as...'</strong> role or <code>((Expert Role/Focus))</code> is specified.</p>
                            <p><strong>Internal Steps (Consider these when responding):</strong></p>
                            <ul>
                                <li>Identify the specific prompt engineering technique being demonstrated or requested (e.g., few-shot, constraints, chaining, formatting, self-critique).</li>
                                <li>Clearly explain the *purpose* and *mechanism* of the technique in accessible language.</li>
                                <li>Provide concrete examples, ideally referencing or utilizing content/prompts from *other sections* of this Prompt Bible (e.g., D1, F1, G2) to demonstrate practical application within this ecosystem.</li>
                                <li>If generating a refined prompt or template, ensure it incorporates the targeted technique effectively.</li>
                                <li>Highlight how the technique influences the AI's output quality, specificity, creativity, or adherence to instructions.</li>
                            </ul>
                            <p>Focus on teaching practical methods for crafting more effective prompts. Provide clear demonstrations and explanations using relevant examples from this Bible to improve user interaction with AI for complex creative and analytical tasks.</p>
                        </div>
                        <!-- SECTION SYSTEM PROMPT END - SECTION_ID: C5 -->

                        <div class="prompt-container" id="C5.1">
                             <p>1. Demonstrate Few-Shot Prompting for Style Replication:</p>
                             <p>Task: Show how to use few-shot prompting to generate a creature description in the specific stylistic voice of [Author Name known for distinct style, e.g., H.P. Lovecraft]. Provide 2 brief examples of the target style, then construct the final prompt instructing the AI to describe a creature from Section F1 ([e.g., F1.1 variant]) in that same style.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Teaches how to provide concrete examples within a prompt (few-shot) to guide the AI towards replicating a specific, often complex, writing style.</p>
                                <p><strong>Best Used For:</strong> Emulating authorial voice, generating stylistically consistent content, fine-tuning AI output beyond simple instructions. Requires providing style examples and referencing a creature concept.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="C5.2">
                             <p>2. Demonstrate Zero-Shot to Few-Shot Progression:</p>
                             <p>Task: First, formulate a zero-shot prompt (direct instruction only) asking the AI to perform [Creative Task relevant to Bible, e.g., write a short myth explaining a geographic feature from F1.7]. Then, demonstrate how to improve the potential result by converting it to a few-shot prompt: provide one strong example of the desired myth style/outcome, and formulate the revised prompt asking the AI to try again based on the example.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Illustrates the practical difference and improvement gained by adding examples (moving from zero-shot to few-shot) for creative tasks requiring specific outputs.</p>
                                <p><strong>Best Used For:</strong> Understanding when few-shot is necessary, improving creative outputs iteratively, demonstrating prompt refinement. Requires defining a creative task potentially linked to other sections.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="C5.3">
                             <p>3. Demonstrate Using Negative Constraints for Specificity:</p>
                             <p>Task: Take a basic worldbuilding prompt, e.g., 'Describe the main temple in the city of [City Name from D2/F]'. Rewrite this prompt to include at least 3 specific *negative* constraints relevant to the Story Bible context (e.g., 'Do not base it on Earth religions,' 'Avoid overtly futuristic elements unless specified in the tech level,' 'The tone should not be whimsical').</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Demonstrates how to use negative constraints (`DON'T`, `AVOID`, `EXCLUDE`) to prevent unwanted elements and steer the AI towards a more precise output consistent with established world rules.</p>
                                <p><strong>Best Used For:</strong> Refining prompts to avoid clichés or contradictions, ensuring adherence to specific world rules, getting more controlled results. Requires referencing Bible context.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="C5.4">
                             <p>4. Demonstrate Role Prompting Nuances (Expertise Level):</p>
                             <p>Task: Generate three variations of a role prompt asking for an analysis of the magic system described in G1. Version 1: Basic role ('Act as a magic system analyst'). Version 2: Specify expertise ('Act as a game designer specializing in balanced hard magic systems...'). Version 3: Specify focus ('Act as a worldbuilder analyzing the societal impact of this magic system...'). Explain the likely differences in output based on these role nuances.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Shows how adding specificity (expertise level, focus area) to the 'Act as...' instruction dramatically changes the depth, perspective, and content of the AI's response, using a Bible-specific example.</p>
                                <p><strong>Best Used For:</strong> Getting more targeted analysis, leveraging specialized AI personas, tailoring outputs for specific worldbuilding or design needs. Requires referencing G1 or similar context.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="C5.5">
                             <p>5. Demonstrate Chaining Prompts for Complex Tasks (Manual CoT):</p>
                             <p>Task: Show how to manually chain prompts to develop a complex cultural ritual (like F2.1). Prompt 1: Define the core value and basic premise based on [Culture Name] from the Bible. Prompt 2 (using output of 1): Detail the specific steps and participants. Prompt 3 (using output of 2): Describe the symbolism and desired emotional impact. Show the structure of each prompt and how it builds on the previous one.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Teaches breaking down a complex creative task into sequential prompts, where the output of one informs the input of the next (manual Chain-of-Thought), using a Bible-relevant example.</p>
                                <p><strong>Best Used For:</strong> Tackling large creative tasks incrementally, maintaining consistency across steps, guiding the AI through complex generation processes like worldbuilding details.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="C5.6">
                             <p>6. Demonstrate Specifying Output Format (Structured Data):</p>
                             <p>Task: Formulate a prompt that asks the AI to generate 5 potential side quests for a region from D2/F (like F3.6) but specifies the output must be formatted as a JSON object, with each quest having keys for 'Title', 'Objective', 'Key_NPC', and 'Reward_Concept'.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Demonstrates how to instruct the AI to structure its output in a specific machine-readable format (like JSON, XML, or Markdown tables) for easier parsing or integration into other tools.</p>
                                <p><strong>Best Used For:</strong> Generating organized data for game design tools, creating content for databases, ensuring consistent output structure for technical uses.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="C5.7">
                             <p>7. Demonstrate Step-Back Prompting for Clarification:</p>
                             <p>Task: Imagine a user gives a vague creative prompt: 'Develop my character more.' Demonstrate using the 'Step-Back' prompting technique. Formulate a prompt asking the AI to: 1. Rephrase the user's likely core need (e.g., seeking depth, motivation, backstory). 2. Identify key missing character information needed to help (referencing elements from D2-S3). 3. Formulate specific clarifying questions to ask the user about their character and narrative goals.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Teaches how to prompt the AI to analyze a vague creative request, identify ambiguities by referencing needed info (like character sheet elements), and ask clarifying questions before generating.</p>
                                <p><strong>Best Used For:</strong> Handling ambiguous creative requests, guiding the AI towards needing specific context from the Story Bible, improving interaction quality when the initial request is unclear.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="C5.8">
                             <p>8. Demonstrate Prompting for Self-Correction/Critique:</p>
                             <p>Task: Formulate a prompt structure where the AI is asked to first draft a [Worldbuilding Element, e.g., description of a location from F1.7], then immediately critique its own draft based on criteria relevant to this Bible, like [Criteria 1: Consistency with established world rules from G1], [Criteria 2: Sensory Detail (referencing F1.12 principles)], [Criteria 3: Narrative Potential], and finally provide a revised version addressing the critique.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Shows how to build self-critique and revision directly into a single prompt flow, using criteria relevant to worldbuilding and narrative quality as defined elsewhere in the Bible.</p>
                                <p><strong>Best Used For:</strong> Improving the quality of generated worldbuilding/creative text in one go, automating basic revision against established criteria, generating more polished drafts.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="C5.9">
                             <p>9. Demonstrate Prompting for Chain of Density Summarization:</p>
                             <p>Task: Craft a prompt instructing an AI to summarize a [Long Text Passage, e.g., detailed history section from D1/F2]. The prompt must explicitly ask for the Chain of Density method: an initial short summary, followed by 3 iterative stages adding more key entities (characters, places, concepts from the text) and relationships while maintaining overall conciseness.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Explains how to prompt an AI to perform a specific advanced summarization technique (Chain of Density) that prioritizes information density, useful for condensing lore.</p>
                                <p><strong>Best Used For:</strong> Creating high-quality, entity-rich summaries of lore/history; learning advanced summarization methods via AI demonstration. Requires a text passage.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="C5.10">
                             <p>10. Demonstrate Setting Context Window Awareness:**</p>
                             <p>Task: Formulate a prompt for continuing a complex worldbuilding task (e.g., planning faction interactions like F2.9). The prompt must explicitly remind the AI of 2-3 critical pieces of previously established context from the Story Bible (e.g., 'Recall Faction A's primary goal is X', 'Remember the resource Y is scarce in this region', 'The previous interaction ended with Z'). Then ask the AI to generate the next step/interaction.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Teaches the importance and method of actively reminding the AI of key context during long, complex tasks (like worldbuilding or outlining) to ensure consistency despite context window limits.</p>
                                <p><strong>Best Used For:</strong> Long-term creative projects, maintaining consistency across multiple interactions, complex simulations, guiding the AI when context might be lost.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="C5.11">
                             <p>11. Demonstrate Prompting for Specific Analogies/Metaphors:**</p>
                             <p>Task: Craft a prompt that specifically asks the AI to explain the social structure of [Society Name from F2] using *only* analogies and metaphors related to [Theme/Concept relevant to the world, e.g., insect colonies, clockwork mechanisms, musical harmony]. Instruct it to generate at least two distinct analogies.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Demonstrates how to prompt for creative explanatory techniques, forcing the AI to use targeted figurative language relevant to the world's themes to clarify a complex social/world element.</p>
                                <p><strong>Best Used For:</strong> Making complex worldbuilding concepts more accessible or thematic, generating creative descriptions, exploring world themes through comparison. Requires society name and theme/concept.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="C5.12">
                             <p>12. Act as an Intent Translator / Prompt Style Tuner:**</p>
                             <p>Task: Translate a user's intent into a refined prompt. User Provides: 1. Core Request/Idea: `[User pastes basic idea here, e.g., 'Describe my character confronting the villain']` 2. Desired Output Style: (User chooses A-E) [A) Highly Precise/Rule-Bound, B) Grounded/Detailed, C) Balanced/Standard, D) Creative/Evocative, E) Wild/Unconstrained]. AI Action: Analyze inputs, rewrite Core Request into a Refined Prompt using phrasing/keywords to match the Desired Style (referencing Bible context if possible), output the Refined Prompt, optionally explain changes.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Acts as a user-friendly interface to translate a basic idea and a desired level of creative freedom/precision into an effectively phrased prompt designed to elicit that specific style of output. Bridges user intent and prompt engineering.</p>
                                <p><strong>Best Used For:</strong> Users who know *what kind* of answer they want (precise vs. creative) but aren't sure how to phrase the prompt effectively; quickly generating prompts tuned for specific tasks; learning how phrasing impacts output style. Crucial meta-tool for using the Bible effectively.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="C5.13">
                             <p>13. Demonstrate Instruction Following Precision Test (Bible Context):**</p>
                             <p>Task: Create a prompt testing precise instruction following using Bible elements. Example: 'Generate a 3-sentence description for the magical item created in G3.1. Sentence 1 must state its primary function. Sentence 2 must mention its drawback AND use the word "glimmers". Sentence 3 must be exactly 8 words long and name its creator culture from G3.1.'</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Demonstrates crafting highly constrained prompts using elements generated elsewhere in the Bible to test/force specific output structures and content adherence.</p>
                                <p><strong>Best Used For:</strong> Testing AI's ability to integrate specific Bible details, generating text meeting strict formatting/content rules, fine-grained control over small text snippets.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="C5.14">
                             <p>14. Demonstrate Meta-Prompting: Generating Prompt Templates:**</p>
                             <p>Task: Act as a Prompt Template Generator. Create a reusable prompt template for generating plausible cultural reactions (like F2.5). The template should include placeholders for [Culture Name], [Core Values Reference], [Event Description], and guide the AI on the expected output structure (e.g., 'Describe differing interpretations, emotional responses, likely actions').</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Uses the AI to create structured prompt templates for recurring worldbuilding or narrative tasks, making the Bible itself extensible and standardizing common requests.</p>
                                <p><strong>Best Used For:</strong> Standardizing common requests within the Bible framework, creating reusable tools, streamlining workflow for frequent worldbuilding tasks.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="C5.15">
                             <p>15. Demonstrate Prompting for Alternative Perspectives (In-World):**</p>
                             <p>Task: Take the social taboo identified in F2.2 for [Society Name]. Craft a prompt asking the AI to describe the taboo *first* from the perspective of a mainstream member of the society, and *then* from the perspective of someone belonging to a subculture (like one from F2.3) that might view the taboo differently. Highlight differences in justification and emotional weight.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Shows how to prompt the AI to explicitly adopt and contrast different *in-world* subjective viewpoints on the same cultural element, leveraging established Bible context.</p>
                                <p><strong>Best Used For:</strong> Exploring cultural nuances, creating realistic social friction, generating diverse character perspectives on world elements. Requires referencing established cultural details.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="C5.16">
                             <p>16. Demonstrate Layered Prompting for World Detail:**</p>
                             <p>Task: Demonstrate layering prompts to build a specific cultural artifact (like F2.15). Prompt 1: Generate the basic concept (e.g., 'a common toy for children in [Culture Name]'). Prompt 2: 'Enhance the previous description by adding details about its materials and construction, reflecting [Culture Name]'s environment.' Prompt 3: 'Further enhance by describing how it's played with and what skills it teaches, reflecting [Culture Name]'s values.'</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Illustrates building up detail for a world element iteratively, focusing each prompt on a specific layer (concept, physical form, cultural function) based on Bible context.</p>
                                <p><strong>Best Used For:</strong> Creating highly detailed world elements gradually, refining concepts layer by layer, controlling the focus of descriptive additions using Bible context.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="C5.17">
                             <p>17. Demonstrate Using Constraints for Magic System Adherence:**</p>
                             <p>Task: Craft a prompt asking the AI to describe a character casting a spell from G2.1, but add explicit constraints: 'Ensure the casting time reflects its defined cost', 'The visual description must include the elements mentioned in G1.8', and 'Do not violate the limitation regarding [Specific Limitation from G1.2]'.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Explicitly incorporates specific, numbered rules/limitations from the Magic System section (G) into prompts as constraints to ensure generated scenes adhere strictly to the established magic logic.</p>
                                <p><strong>Best Used For:</strong> Maintaining strict magic system consistency during scene writing, ensuring generated magic use follows established rules, reinforcing limitations narratively.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="C5.18">
                             <p>18. Demonstrate Persona Blending for World Exploration:**</p>
                             <p>Task: Create a prompt asking the AI to adopt a blended persona: 'Act as a cynical historian from [Rival Nation Name] describing the 'heroic' founding myth of [Protagonist Nation Name] (based on F2.7 or G1.10). Analyze the myth for propaganda and self-serving interpretations from the rival historian's biased perspective.'</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Demonstrates combining a specific in-world character persona/bias with an analytical task (analyzing lore/history from the Bible) for unique, perspective-driven world exploration.</p>
                                <p><strong>Best Used For:</strong> Generating biased in-world accounts, exploring historical revisionism themes, creating unreliable narrator perspectives on established lore. Requires defining the persona and referencing Bible lore.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="C5.19">
                            <p>19. Optimize Existing Prompt for Brevity/Impact:</p>
                            <p>Task: Take a relatively complex prompt from another section (e.g., F1.1 - evolutionary simulation). Rewrite the prompt to be more concise while retaining the core instructions and expected level of detail. Explain the optimization choices.</p>
                            <div class="prompt-synopsis">
                               <p><strong>Function:</strong> Teaches techniques for making prompts shorter and more direct without losing essential information, improving efficiency.</p>
                               <p><strong>Best Used For:</strong> Refining personal prompt style, making prompts easier to parse (for AI and humans), prompt optimization practice. Requires selecting a complex prompt from the Bible.</p>
                           </div>
                       </div>
                        <div class="prompt-container" id="C5.20">
                            <p>20. Contextual Keyword Injection for Relevance:</p>
                            <p>Task: User wants to generate a scene set in "[Location from Bible]". Demonstrate rewriting a basic scene prompt ('Write a scene where Character A meets Character B') to inject 3-5 specific keywords related to the location's description or history (found elsewhere in the Bible) to ensure the generated scene feels strongly grounded in that specific place.</p>
                            <div class="prompt-synopsis">
                               <p><strong>Function:</strong> Shows how to subtly weave specific contextual keywords from the Story Bible into creative prompts to anchor the AI's generation in the established world details.</p>
                               <p><strong>Best Used For:</strong> Improving setting integration in generated scenes, ensuring creative writing reflects established lore, making generated content feel more specific to the world.</p>
                           </div>
                       </div>
                    </div>
                </details> <!-- End Section C5 -->
            </div>
        </details> <!-- End Section C -->


        <details id="D" open> <!-- Default open for writing prompts -->
            <summary>D: Writing & Literature Focused Prompts</summary>
            <div>
                <details id="D1">
                    <summary>D1: Writing & Literature (General Focus)</summary>
                    <div>
                         <!-- SECTION SYSTEM PROMPT START - SECTION_ID: D1 -->
                        <div class="system-prompt-block">
                            <h4>System Instruction</h4>
                            <p><strong>Context:</strong> Writing & Literature (General Focus)</p>
                            <p>Adopt the persona of a <strong>Knowledgeable Literary Analyst and Writing Consultant</strong> unless an <strong>'Act as...'</strong> role (e.g., Critic, Educator, Theorist) or <code>((Expert Role))</code> is specified in the task prompt.</p>
                            <p><strong>Internal Steps (Consider these when responding):</strong></p>
                            <ul>
                                <li>Identify the specific literary work, concept, technique, or writing task.</li>
                                <li>Apply relevant literary theory, critical analysis methods, or writing craft principles.</li>
                                <li>Use precise literary terminology (e.g., symbolism, theme, narrative voice, genre conventions).</li>
                                <li>Provide specific examples from texts when analyzing or explaining.</li>
                                <li>Structure arguments logically and support claims with evidence or sound reasoning.</li>
                                <li>If generating creative work, focus on literary quality and fulfilling prompt constraints.</li>
                             </ul>
                            <p>Focus on insightful analysis, clear explanation of craft/theory, and demonstrating a deep understanding of literary concepts. Aim for well-reasoned, contextually relevant responses.</p>
                        </div>
                         <!-- SECTION SYSTEM PROMPT END - SECTION_ID: D1 -->

                        <div class="prompt-item" id="D1.1"><strong>1. Act as a literary critic:</strong><p>Analyze the use of unreliable narration in [Specific Novel/Short Story] and discuss its effect on the reader's interpretation.</p></div>
                        <div class="prompt-item" id="D1.2"><strong>2. Act as a Creative Adapter:</strong><p>Adapt this poem [Poem Text] into a short fictional narrative. Focus on translating the imagery and themes into plot and character.</p></div>
                        <div class="prompt-item" id="D1.3"><strong>3. Act as a Literary Historian:</strong><p>Analyze how the socio-political climate of [Era, e.g., Post-WWII America] influenced the dominant themes and styles in the literature of that period. Provide specific examples.</p></div>
                        <div class="prompt-item" id="D1.4"><strong>4. Act as a Genre Theorist:</strong><p>Compare and contrast the core conventions, reader expectations, and narrative structures of High Fantasy and Urban Fantasy.</p></div>
                        <div class="prompt-item" id="D1.5"><strong>5. Act as a Manuscript Editor:</strong><p>Critique this opening chapter [Text Excerpt] for hook effectiveness, pacing, voice consistency, and establishment of stakes. Provide specific, actionable feedback.</p></div>
                        <div class="prompt-item" id="D1.6"><strong>6. Act as a Problem-Solving Consultant (Publishing):</strong><p>A debut author has a finished manuscript but no online presence. Brainstorm a feasible 3-month strategy to build an author platform suitable for querying agents in the [Genre] genre.</p></div>
                        <div class="prompt-item" id="D1.7"><strong>7. Act as a Creative Adapter:</strong><p>Adapt the core story and themes of the myth of Icarus into a contemporary science fiction short story set on a space station.</p></div>
                        <div class="prompt-item" id="D1.8"><strong>8. Act as a Poetic Form Analyst:</strong><p>Explain the rules and emotional effects typically associated with the Villanelle form. Analyze how [Specific Villanelle Poem] utilizes or subverts these expectations.</p></div>
                        <div class="prompt-item" id="D1.9"><strong>9. Act as a Literary Translator (Problem Solving):</strong><p>This passage [Text Excerpt with cultural idiom] contains a culturally specific idiom that has no direct equivalent in English. Propose three different translation strategies, explaining the potential pros and cons of each regarding accuracy, tone, and readability.</p></div>
                        <div class="prompt-item" id="D1.10"><strong>10. Act as a Critical Thinker (Literary Ethics):</strong><p>Debate the ethical considerations of posthumously publishing an author's unfinished or private writings. Present arguments for and against.</p></div>
                        <div class="prompt-item" id="D1.11"><strong>11. Act as a Narrative Structure Designer:</strong><p>Outline three different possible narrative structures (e.g., linear, framed narrative, episodic) for telling a story about a multi-generational family saga. Discuss the potential impact of each structure.</p></div>
                        <div class="prompt-item" id="D1.12"><strong>12. Act as a Research Synthesizer:</strong><p>Compile and synthesize information from three scholarly articles on [Literary Topic, e.g., the unreliable narrator in modernist fiction] into a concise overview suitable for an undergraduate essay.</p></div>
                        <div class="prompt-item" id="D1.13"><strong>13. Act as a Playwright (Creative Problem Solving):</strong><p>Write a short scene where two characters must convey significant backstory and conflict solely through actions and minimal, fragmented dialogue in a high-tension situation.</p></div>
                        <div class="prompt-item" id="D1.14"><strong>14. Act as a Rhetorical Analyst:</strong><p>Analyze the persuasive techniques used in a famous literary manifesto or critical essay (e.g., Woolf's "A Room of One's Own"). Identify the target audience, appeals (logos, pathos, ethos), and key rhetorical devices.</p></div>
                        <div class="prompt-item" id="D1.15"><strong>15. Act as a Book Reviewer:</strong><p>Write a balanced review of a recently published novel [Novel Title], addressing its plot, characterization, themes, prose style, and overall impact, justifying your assessment with textual evidence.</p></div>
                        <div class="prompt-item" id="D1.16"><strong>16. Act as a Curriculum Developer:</strong><p>Design a module for a high school English class comparing a classic novel to its modern film adaptation, focusing on themes, character interpretations, and the challenges of adaptation.</p></div>
                        <div class="prompt-item" id="D1.17"><strong>17. Act as a Foreshadowing Expert:</strong><p>Analyze how foreshadowing is used in [Specific Suspense Novel or Story] to build tension and prepare the reader for key reveals.</p></div>
                        <div class="prompt-item" id="D1.18"><strong>18. Act as a Worldbuilding Consultant (Literary):</strong><p>Evaluate the internal consistency and believability of the world-building elements (social structures, rules, history) presented in this fantasy/sci-fi excerpt: [Text Excerpt].</p></div>
                        <div class="prompt-item" id="D1.19"><strong>19. Act as a Character Psychologist:</strong><p>Analyze the psychological motivations and potential underlying traumas driving the actions of [Complex Literary Character, e.g., Hamlet, Lady Macbeth].</p></div>
                        <div class="prompt-item" id="D1.20"><strong>20. Act as a Dialogue Doctor:</strong><p>Rewrite this stilted dialogue excerpt [Text Excerpt] to sound more natural, differentiate the speakers' voices, and incorporate subtext relevant to their hidden agendas.</p></div>
                        <div class="prompt-item" id="D1.21"><strong>21. Act as an Idea Generator (Thematic):</strong><p>Brainstorm 5 story concepts that explore the theme of "memory and identity" through different genres (e.g., sci-fi, mystery, contemporary fiction).</p></div>
                        <div class="prompt-item" id="D1.22"><strong>22. Act as a Literary Agent Scout:</strong><p>Assess this query letter [Query Letter Text] based on standard industry expectations for clarity, hook, synopsis effectiveness, and author bio relevance.</p></div>
                        <div class="prompt-item" id="D1.23"><strong>23. Act as a Symbolism Decoder:</strong><p>Identify and interpret the recurring symbols in a specific poet's body of work (e.g., Yeats, Plath) and discuss how they contribute to the overall thematic landscape.</p></div>
                        <div class="prompt-item" id="D1.24"><strong>24. Act as a Flash Fiction Writer:</strong><p>Write a complete story under 500 words based on the prompt: "The map showed a city that didn't exist."</p></div>
                        <div class="prompt-item" id="D1.25"><strong>25. Act as a Language Style Analyst:</strong><p>Compare the sentence structure, vocabulary choices, and overall prose rhythm in passages by Ernest Hemingway and William Faulkner. Discuss the effects of their different styles.</p></div>
                        <!-- Adding prompts 1-90 from Writingandgenprompts.txt Part 1, avoiding direct duplicates -->
                        <div class="prompt-item" id="D1.26"><strong>26. (WG 1) Act as a literary critic analyzing the use of symbolism in [literary work].</strong></div>
                        <div class="prompt-item" id="D1.27"><strong>27. (WG 2) Adapt this classic novel [title] into a modern screenplay.</strong></div>
                        <div class="prompt-item" id="D1.28"><strong>28. (WG 3) Analyze the impact of [author]'s personal experiences on their writing style.</strong></div>
                        <div class="prompt-item" id="D1.29"><strong>29. (WG 4) Analyze the strengths and weaknesses of different narrative voices in fiction.</strong></div>
                        <div class="prompt-item" id="D1.30"><strong>30. (WG 5) Argue for or against the literary merit of [genre].</strong></div>
                        <div class="prompt-item" id="D1.31"><strong>31. (WG 6) Assess the effectiveness of [literary device] in conveying [theme].</strong></div>
                        <div class="prompt-item" id="D1.32"><strong>32. (WG 7) Brainstorm ideas for a short story that explores the theme of [abstract concept].</strong></div>
                        <div class="prompt-item" id="D1.33"><strong>33. (WG 8) Break down the structure of a successful novel in the [genre] genre.</strong></div>
                        <div class="prompt-item" id="D1.34"><strong>34. (WG 9) Categorize these literary works based on their historical period and style.</strong></div>
                        <div class="prompt-item" id="D1.35"><strong>35. (WG 10) Check this piece of creative writing for consistency in tone and voice.</strong></div>
                        <div class="prompt-item" id="D1.36"><strong>36. (WG 11) Clarify the meaning of [obscure literary reference].</strong></div>
                        <div class="prompt-item" id="D1.37"><strong>37. (WG 12) Compare and contrast the themes of [two novels] by different authors.</strong></div>
                        <div class="prompt-item" id="D1.38"><strong>38. (WG 13) Compile a list of essential resources for aspiring fiction writers.</strong></div>
                        <div class="prompt-item" id="D1.39"><strong>39. (WG 14) Compose a poem that captures the essence of [literary movement].</strong></div>
                        <div class="prompt-item" id="D1.40"><strong>40. (WG 15) Condense this lengthy epic poem into a concise summary.</strong></div>
                        <div class="prompt-item" id="D1.41"><strong>41. (WG 16) Construct a detailed timeline of [author]'s life and works.</strong></div>
                        <div class="prompt-item" id="D1.42"><strong>42. (WG 17) Create a case study of a novel that successfully uses [narrative technique].</strong></div>
                        <div class="prompt-item" id="D1.43"><strong>43. (WG 18) Create a checklist for editing a piece of fiction.</strong></div>
                        <div class="prompt-item" id="D1.44"><strong>44. (WG 19) Create a dialogue between two fictional characters discussing their views on literature.</strong></div>
                        <div class="prompt-item" id="D1.45"><strong>45. (WG 20) Create an analogy to explain the concept of [literary theory].</strong></div>
                        <div class="prompt-item" id="D1.46"><strong>46. (WG 21) Create an outline for a critical essay on [literary work].</strong></div>
                        <div class="prompt-item" id="D1.47"><strong>47. (WG 22) Critique this short story for its plot, character development, and pacing.</strong></div>
                        <div class="prompt-item" id="D1.48"><strong>48. (WG 23) Debug this piece of writing to improve its clarity and flow.</strong></div>
                        <div class="prompt-item" id="D1.49"><strong>49. (WG 24) Define [literary term] in simple language.</strong></div>
                        <div class="prompt-item" id="D1.50"><strong>50. (WG 25) Describe the process of writing a compelling character arc.</strong></div>
                        <div class="prompt-item" id="D1.51"><strong>51. (WG 26) Design a workshop to teach creative writing techniques.</strong></div>
                        <div class="prompt-item" id="D1.52"><strong>52. (WG 27) Develop a marketing strategy to promote a newly published novel.</strong></div>
                        <div class="prompt-item" id="D1.53"><strong>53. (WG 28) Develop a series of writing prompts to inspire creative fiction.</strong></div>
                        <div class="prompt-item" id="D1.54"><strong>54. (WG 29) Draft a query letter to a literary agent for a novel.</strong></div>
                        <div class="prompt-item" id="D1.55"><strong>55. (WG 30) Elaborate on the significance of setting in [literary work].</strong></div>
                        <div class="prompt-item" id="D1.56"><strong>56. (WG 31) Evaluate the arguments presented in a critical analysis of [play].</strong></div>
                        <div class="prompt-item" id="D1.57"><strong>57. (WG 32) Explain [complex literary concept] simply.</strong></div>
                        <div class="prompt-item" id="D1.58"><strong>58. (WG 33) Explain the significance of [literary symbol].</strong></div>
                        <div class="prompt-item" id="D1.59"><strong>59. (WG 34) Explain this poem's structure and meaning.</strong></div>
                        <div class="prompt-item" id="D1.60"><strong>60. (WG 35) Explore the implications of [literary trend] on contemporary writing.</strong></div>
                        <div class="prompt-item" id="D1.61"><strong>61. (WG 36) Extract key themes and motifs from [collection of short stories].</strong></div>
                        <div class="prompt-item" id="D1.62"><strong>62. (WG 37) Fact-check the historical accuracy of a work of historical fiction.</strong></div>
                        <div class="prompt-item" id="D1.63"><strong>63. (WG 38) Find alternative interpretations of a controversial literary work.</strong></div>
                        <div class="prompt-item" id="D1.64"><strong>64. (WG 39) Find patterns in the use of language by a particular author.</strong></div>
                        <div class="prompt-item" id="D1.65"><strong>65. (WG 40) Forecast the potential future of the [genre] genre.</strong></div>
                        <div class="prompt-item" id="D1.66"><strong>66. (WG 41) Formulate counter-arguments to a critical interpretation of a poem.</strong></div>
                        <div class="prompt-item" id="D1.67"><strong>67. (WG 42) Formulate interview questions for a contemporary author.</strong></div>
                        <div class="prompt-item" id="D1.68"><strong>68. (WG 43) Generate discussion questions for a book club reading [novel].</strong></div>
                        <div class="prompt-item" id="D1.69"><strong>69. (WG 44) Generate potential titles for a collection of essays on literature.</strong></div>
                        <div class="prompt-item" id="D1.70"><strong>70. (WG 45) Give examples of effective use of dialogue in fiction.</strong></div>
                        <div class="prompt-item" id="D1.71"><strong>71. (WG 46) Hypothesize the author's intentions in using a particular literary device.</strong></div>
                        <div class="prompt-item" id="D1.72"><strong>72. (WG 47) Identify the assumptions made in a critical analysis of a play.</strong></div>
                        <div class="prompt-item" id="D1.73"><strong>73. (WG 48) Identify the key themes and symbols in a work of poetry.</strong></div>
                        <div class="prompt-item" id="D1.74"><strong>74. (WG 49) Illustrate the differences between various poetic forms.</strong></div>
                        <div class="prompt-item" id="D1.75"><strong>75. (WG 50) Imagine you are a famous author and respond to a fan letter.</strong></div>
                        <div class="prompt-item" id="D1.76"><strong>76. (WG 51) Imagine the future of storytelling in a digital age.</strong></div>
                        <div class="prompt-item" id="D1.77"><strong>77. (WG 52) Implement a revision strategy to improve a draft of a novel.</strong></div>
                        <div class="prompt-item" id="D1.78"><strong>78. (WG 53) Improve the pacing and rhythm of a piece of prose.</strong></div>
                        <div class="prompt-item" id="D1.79"><strong>79. (WG 54) Interpret the symbolism and imagery in a poem.</strong></div>
                        <div class="prompt-item" id="D1.80"><strong>80. (WG 55) Investigate the historical context of a play.</strong></div>
                        <div class="prompt-item" id="D1.81"><strong>81. (WG 56) Justify the author's choice of a particular narrative structure.</strong></div>
                        <div class="prompt-item" id="D1.82"><strong>82. (WG 57) List the pros and cons of different publishing models for authors.</strong></div>
                        <div class="prompt-item" id="D1.83"><strong>83. (WG 58) Map out the plot structure of a classic novel.</strong></div>
                        <div class="prompt-item" id="D1.84"><strong>84. (WG 59) Optimize a piece of writing for emotional impact.</strong></div>
                        <div class="prompt-item" id="D1.85"><strong>85. (WG 60) Organize a collection of short stories around a central theme.</strong></div>
                        <div class="prompt-item" id="D1.86"><strong>86. (WG 61) Paraphrase a complex literary passage in simpler terms.</strong></div>
                        <div class="prompt-item" id="D1.87"><strong>87. (WG 62) Persuade an audience to appreciate the value of literature.</strong></div>
                        <div class="prompt-item" id="D1.88"><strong>88. (WG 63) Plan a writing retreat designed to foster creativity.</strong></div>
                        <div class="prompt-item" id="D1.89"><strong>89. (WG 64) Predict the long-term impact of a particular literary movement.</strong></div>
                        <div class="prompt-item" id="D1.90"><strong>90. (WG 65) Prioritize the elements of a story that are most important for reader engagement.</strong></div>
                        <div class="prompt-item" id="D1.91"><strong>91. (WG 66) Propose a new approach to teaching literature in schools.</strong></div>
                        <div class="prompt-item" id="D1.92"><strong>92. (WG 67) Provide a detailed explanation of a specific poetic form.</strong></div>
                        <div class="prompt-item" id="D1.93"><strong>93. (WG 68) Provide constructive feedback on a piece of creative writing.</strong></div>
                        <div class="prompt-item" id="D1.94"><strong>94. (WG 69) Rank different literary works based on their influence on subsequent writers.</strong></div>
                        <div class="prompt-item" id="D1.95"><strong>95. (WG 70) Reconstruct the author's creative process in writing a particular novel.</strong></div>
                        <div class="prompt-item" id="D1.96"><strong>96. (WG 71) Reframe a common literary trope in a fresh and original way.</strong></div>
                        <div class="prompt-item" id="D1.97"><strong>97. (WG 72) Research the historical reception of a controversial literary work.</strong></div>
                        <div class="prompt-item" id="D1.98"><strong>98. (WG 73) Review a newly published novel for a literary magazine.</strong></div>
                        <div class="prompt-item" id="D1.99"><strong>99. (WG 74) Rewrite a scene from a novel from a different character's perspective.</strong></div>
                        <div class="prompt-item" id="D1.100"><strong>100. (WG 75) Role-play a discussion between two authors about their writing styles.</strong></div>
                        <div class="prompt-item" id="D1.101"><strong>101. (WG 76) Simplify a complex literary theory for a general audience.</strong></div>
                        <div class="prompt-item" id="D1.102"><strong>102. (WG 77) Solve a plot hole in a fictional narrative.</strong></div>
                        <div class="prompt-item" id="D1.103"><strong>103. (WG 78) Structure a compelling narrative arc for a novel.</strong></div>
                        <div class="prompt-item" id="D1.104"><strong>104. (WG 79) Suggest creative ways to promote literacy and a love of reading.</strong></div>
                        <div class="prompt-item" id="D1.105"><strong>105. (WG 80) Summarize the main themes and ideas of a literary work.</strong></div>
                        <div class="prompt-item" id="D1.106"><strong>106. (WG 81) Synthesize critical perspectives on a particular author.</strong></div>
                        <div class="prompt-item" id="D1.107"><strong>107. (WG 82) Teach me the fundamentals of storytelling.</strong></div>
                        <div class="prompt-item" id="D1.108"><strong>108. (WG 83) Tell a story that subverts common literary tropes.</strong></div>
                        <div class="prompt-item" id="D1.109"><strong>109. (WG 84) Test the effectiveness of different writing techniques.</strong></div>
                        <div class="prompt-item" id="D1.110"><strong>110. (WG 85) Translate a literary work into a different cultural context.</strong></div>
                        <div class="prompt-item" id="D1.111"><strong>111. (WG 86) Troubleshoot potential problems with a fictional plot.</strong></div>
                        <div class="prompt-item" id="D1.112"><strong>112. (WG 87) Turn fragmented ideas into a coherent and compelling narrative.</strong></div>
                        <div class="prompt-item" id="D1.113"><strong>113. (WG 88) Update a classic literary work to make it more relevant to a contemporary audience.</strong></div>
                        <div class="prompt-item" id="D1.114"><strong>114. (WG 89) Write a compelling book blurb for a novel.</strong></div>
                        <div class="prompt-item" id="D1.115"><strong>115. (WG 90) Write code to analyze the frequency of word usage in a literary text.</strong></div>
                        <div class="prompt-item" id="D1.116"><strong>116. Analyze the psychological motivations of the characters in [literary work].</strong></div>
                    </div>
                </details>

                <details id="D2" open> <!-- Default open for the primary purpose -->
                    <summary>D2: Complete Book Writing Process (Extensive Expert Roles for Story Bible)</summary>
                    <div>
                        <!-- SECTION SYSTEM PROMPT START - SECTION_ID: D2 (Overall Guide Prompt) -->
                        <div class="system-prompt-block" style="border: 1px solid var(--accent-primary); background-color: rgba(56, 189, 248, 0.05);">
                            <h4>System Instruction</h4>
                            <p><strong>Context:</strong> Book Writing Process (Overall Section D2)</p>
                            <p>You are facilitating a multi-stage book writing process using this structured Bible. Each Stage (D2-S0 to D2-S9) has its own specific System Instructions and Persona.</p>
                            <p><strong>Your Role:</strong> Guide the user through these stages sequentially or allow them to jump to specific stages using Prompt IDs (e.g., `D2-S4.5`). When a prompt within D2 is invoked, strictly adhere to the System Instructions defined for **that specific Stage**.</p>
                            <p>Maintain context from previously completed stages (concept, world, characters, plot) when executing prompts in later stages. The goal is to collaboratively build a comprehensive Story Bible and eventually draft the manuscript.</p>
                        </div>
                        <!-- SECTION SYSTEM PROMPT END - SECTION_ID: D2 -->

                        <!-- Insert drafted D2-S0 here -->
                        <details open id="D2-S0">
                             <summary>Stage 0: Pre-Planning & Author Mindset</summary>
                             <div>
                                 <!-- SECTION SYSTEM PROMPT START - SECTION_ID: D2-S0 -->
                                 <div class="system-prompt-block">
                                     <h4>System Instruction</h4>
                                     <p><strong>Context:</strong> Book Writing - Stage 0: Pre-Planning & Author Mindset</p>
                                     <p>Adopt the persona of an <strong>Author Coach and Project Strategist</strong>. Focus on helping the user define their project's foundation, target audience, personal goals, and establish sustainable writing practices *before* extensive creative work begins.</p>
                                      <p><strong>Internal Steps (Consider these when responding):</strong></p>
                                      <ul>
                                          <li>Elicit or help refine the user's core motivations and goals for this specific writing project.</li>
                                          <li>Guide the user in defining a clear target audience profile.</li>
                                          <li>Explore potential project scope and feasibility based on user resources (time, energy).</li>
                                          <li>Offer practical advice on mindset, productivity, overcoming common writing challenges (doubt, blocks).</li>
                                          <li>Help establish initial project parameters (e.g., potential length, genre focus) if not yet defined.</li>
                                          <li>Document these foundational decisions clearly for the Story Bible's meta-section.</li>
                                      </ul>
                                     <p>Focus on asking clarifying questions, offering structured exercises, and providing supportive, practical advice to build a solid foundation for the writing journey. Aim to establish clear goals and realistic expectations.</p>
                                 </div>
                                 <!-- SECTION SYSTEM PROMPT END - SECTION_ID: D2-S0 -->

                                 <div class="prompt-container" id="D2-S0.1">
                                     <p>1. Act as an Author Coach (Goal Clarification): Let's clarify your core motivation for writing *this specific* book. Is it primarily for personal fulfillment, exploring a specific theme, achieving publication (traditional/self), building a platform, pure entertainment, or something else? Discussing this helps set the project's direction.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Helps the author articulate the fundamental 'why' behind their project, influencing scope and expectations.</p>
                                         <p><strong>Best Used For:</strong> Initial project kickoff, defining success metrics, aligning effort with desired outcomes.</p>
                                     </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S0.2">
                                     <p>2. Act as a Target Audience Analyst: Who is the ideal reader for this book? Let's brainstorm a profile: Consider age range, gender, key interests, potential favorite authors/genres, reading habits (e.g., prefers fast-paced plot vs deep character study). Be specific.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Guides the author in defining a specific target audience, which informs genre, style, and marketing later.</p>
                                         <p><strong>Best Used For:</strong> Pre-planning, ensuring market awareness (even if writing for oneself), tailoring the story approach.</p>
                                     </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S0.3">
                                     <p>3. Act as a Project Scope Definer: Based on your initial concept [Brief Concept, if any] and goals (D2-S0.1), let's define a realistic scope. Are we aiming for a short story, novella, standard novel length (~80k words), or an epic fantasy (>120k words)? Discussing target length now helps manage expectations and planning.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Helps set a target word count or project size early on, influencing plotting and pacing.</p>
                                         <p><strong>Best Used For:</strong> Initial planning, setting realistic targets, choosing appropriate story structure complexity. Requires initial concept/genre idea.</p>
                                     </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S0.4">
                                     <p>4. Act as a Genre Expectation Consultant: You've mentioned interest in [Genre]. Let's discuss the core reader expectations for this genre regarding pacing, tone, common tropes (that might need addressing - see D2-S1.2), and typical ending styles (e.g., HEA in romance). Understanding these helps align the story concept.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Provides an overview of typical conventions and reader expectations for a chosen genre.</p>
                                         <p><strong>Best Used For:</strong> Genre selection/confirmation, understanding market positioning, planning how to meet or subvert expectations. Requires a target genre.</p>
                                     </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S0.5">
                                     <p>5. Act as a Comparative Title Brainstormer (Pre-Concept): What are 3-5 recently successful books (published in last 3-5 years) that feel tonally or conceptually similar to the *idea* you want to write? Analyzing these 'comp titles' helps understand the market niche and position your project.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Guides the author in identifying comparable published works to understand potential market fit and positioning.</p>
                                         <p><strong>Best Used For:</strong> Market research (essential for querying), refining genre/category, understanding reader base. Helpful even before the concept is fully formed.</p>
                                     </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S0.6">
                                     <p>6. Act as a Writing Habit Strategist: Let's establish a sustainable writing routine. Based on your typical weekly schedule [User provides brief overview], what is a realistic daily or weekly writing goal (time or word count)? What time of day works best? How will you track progress?</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Helps the author create a practical and achievable writing schedule based on their life circumstances.</p>
                                         <p><strong>Best Used For:</strong> Setting up for consistent progress, preventing burnout, establishing realistic goals. Requires user schedule input.</p>
                                     </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S0.7">
                                     <p>7. Act as a Productivity Technique Advisor: Explore 3 potential writing productivity techniques: Pomodoro Technique (timed sprints), Time Blocking (scheduling specific writing slots), or 'Don't Break the Chain' (daily consistency tracking). Discuss which might fit your working style best.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Introduces common productivity methods tailored for writers and helps select a suitable one.</p>
                                         <p><strong>Best Used For:</strong> Improving writing efficiency, maintaining focus, finding a sustainable workflow.</p>
                                     </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S0.8">
                                     <p>8. Act as a Creative Mindset Coach (Overcoming Blocks): What are your biggest fears or anticipated challenges when starting this project (e.g., fear of the blank page, self-doubt, perfectionism)? Let's discuss 2-3 specific strategies to proactively address these mindset hurdles.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Helps identify and prepare for common psychological barriers in the writing process.</p>
                                         <p><strong>Best Used For:</strong> Building resilience, preventing writer's block, managing self-criticism, fostering a positive writing mindset.</p>
                                     </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S0.9">
                                     <p>9. Act as a "Permission to Write Badly" Advocate: Discuss the importance of the 'shitty first draft' concept. How can embracing imperfection in the initial drafting stage actually help you make progress and finish the book?</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Addresses perfectionism by explaining the value and necessity of imperfect first drafts.</p>
                                         <p><strong>Best Used For:</strong> Overcoming perfectionism, encouraging forward momentum, reducing drafting anxiety.</p>
                                     </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S0.10">
                                     <p>10. Act as an Environment Optimizer: Where and when do you plan to do most of your writing? Let's brainstorm how to optimize that environment for focus (e.g., minimizing distractions, specific music, necessary supplies, communicating needs to family/roommates).</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Helps plan the physical and social environment to support focused writing sessions.</p>
                                         <p><strong>Best Used For:</strong> Improving concentration, minimizing interruptions, creating a dedicated writing space/time.</p>
                                     </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S0.11">
                                     <p>11. Act as a Research Needs Assessor: Based on your initial concept [Brief Concept/Genre], what kind of research might be necessary *before* you start outlining or drafting (e.g., historical period details, specific scientific concepts, cultural accuracy, location specifics)? Let's list potential research areas.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Identifies potential research requirements early in the process to ensure accuracy and depth.</p>
                                         <p><strong>Best Used For:</strong> Planning research tasks, ensuring worldbuilding accuracy, avoiding major rewrites due to factual errors. Requires concept/genre.</p>
                                     </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S0.12">
                                     <p>12. Act as a "What If I Get Stuck?" Planner: Let's proactively brainstorm 3 specific strategies you can use if you hit a major plot hole or lose motivation midway through the project (e.g., jump to a different scene, talk it out, use a specific Bible prompt like F3.4, take a planned break).</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Develops contingency plans for common writing roadblocks before they happen.</p>
                                         <p><strong>Best Used For:</strong> Preventing project abandonment, building problem-solving skills for writing, managing motivation dips.</p>
                                     </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S0.13">
                                     <p>13. Act as a Story Bible Purpose Definer: Discuss *how* we will use the Story Bible we are creating with Section D2. Will it be a strict blueprint, a flexible guide, a repository for discarded ideas? Defining its purpose helps manage its creation and use.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Sets expectations for the role and flexibility of the Story Bible itself throughout the writing process.</p>
                                         <p><strong>Best Used For:</strong> Clarifying the planning approach (plotter vs. pantser spectrum), managing the Story Bible tool effectively.</p>
                                     </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S0.14">
                                     <p>14. Act as an Accountability Partner Setup Advisor: Do you work better with external accountability? Let's discuss potential options: joining a writing group, finding a critique partner, setting up regular check-ins (even with me, the AI, conceptually), or using specific apps.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Explores options for external accountability to help the author stay on track with their goals.</p>
                                         <p><strong>Best Used For:</strong> Maintaining motivation, building a support system, ensuring consistent progress.</p>
                                     </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S0.15">
                                     <p>15. Act as a Pre-Mortem Analyst: Imagine this writing project fails (e.g., abandoned halfway, finished but unsatisfactory). What are the 3 most likely reasons *why* it might fail based on your personality, schedule, or the project's nature? Let's identify potential pitfalls now so we can mitigate them.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Proactively identifies potential failure points for the project to allow for preventative planning.</p>
                                         <p><strong>Best Used For:</strong> Risk management for the writing process, addressing weaknesses upfront, increasing chances of project completion.</p>
                                     </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S0.16">
                                    <p>16. Act as a Theme Resonance Check (Initial): Before developing plot/characters deeply, reflect on the core theme(s) you *want* to explore [User states initial themes]. Why is this theme personally important or interesting to you right now? Connecting personally can fuel the project.</p>
                                     <div class="prompt-synopsis">
                                        <p><strong>Function:</strong> Encourages the author to connect with the emotional or intellectual core of their intended theme early on.</p>
                                        <p><strong>Best Used For:</strong> Ensuring thematic passion, finding the heart of the story, maintaining motivation through connection.</p>
                                    </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S0.17">
                                    <p>17. Act as a Narrative Voice Conceptualizer: Even before writing, do you have an initial idea of the desired narrative voice or tone for this story (e.g., intimate first-person, detached omniscient, humorous, gritty)? Discussing this helps guide stylistic choices later.</p>
                                     <div class="prompt-synopsis">
                                        <p><strong>Function:</strong> Prompts early thought about the overall style and feel of the narration.</p>
                                        <p><strong>Best Used For:</strong> Setting stylistic direction, informing POV choices, establishing tone early.</p>
                                    </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S0.18">
                                    <p>18. Act as an Elevator Pitch Drafter (Premise): Let's try drafting an initial, rough "elevator pitch" (1-2 sentences) for your core story idea. This helps clarify the absolute essence of the project before detailed planning.</p>
                                     <div class="prompt-synopsis">
                                        <p><strong>Function:</strong> Forces concise distillation of the core concept very early in the process.</p>
                                        <p><strong>Best Used For:</strong> Testing concept clarity, creating a project touchstone, practicing concise description.</p>
                                    </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S0.19">
                                    <p>19. Act as a Tools & Resources Assessor: What tools do you plan to use for writing, outlining, and potentially managing your Story Bible (e.g., Scrivener, Word, Google Docs, Obsidian, physical notebook)? Discussing tools ensures your workflow is supported.</p>
                                     <div class="prompt-synopsis">
                                        <p><strong>Function:</strong> Prompts consideration of the practical software or physical tools needed for the writing and planning process.</p>
                                        <p><strong>Best Used For:</strong> Workflow planning, ensuring appropriate tools are chosen, technical preparation.</p>
                                    </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S0.20">
                                    <p>20. Act as a Project Kickoff Document Compiler: Let's summarize the key decisions from this Stage 0 (Goals, Audience, Scope, Genre, Comps, Habits, Mindset Plan, Initial Pitch) into a concise "Project Kickoff" section for the Story Bible meta-notes.</p>
                                     <div class="prompt-synopsis">
                                        <p><strong>Function:</strong> Consolidates the foundational decisions made in Stage 0 into a reference document within the Bible.</p>
                                        <p><strong>Best Used For:</strong> Documenting initial planning, creating a project charter, providing a reference point for the writing process.</p>
                                    </div>
                                 </div>
                             </div>
                         </details> <!-- End Stage 0 -->

                         <!-- Stage 1: Conceptualization & Idea Generation -->
                         <details id="D2-S1">
                              <summary>Stage 1: Conceptualization & Idea Generation</summary>
                              <div>
                                   <!-- SECTION SYSTEM PROMPT START - SECTION_ID: D2-S1 -->
                                   <div class="system-prompt-block">
                                     <h4>System Instruction</h4>
                                      <p><strong>Context:</strong> Book Writing - Stage 1: Conceptualization & Idea Generation</p>
                                     <p>Adopt the persona of a <strong>Concept Development Expert and Idea Generator</strong>. Focus on brainstorming core story ideas, loglines, themes, and initial plot concepts based on user input or broad prompts. Prioritize originality and narrative potential.</p>
                                      <p><strong>Internal Steps (Consider these when responding):</strong></p>
                                      <ul>
                                          <li>Generate diverse story ideas within specified genre/parameters.</li>
                                          <li>Refine basic premises into high-concept pitches or loglines.</li>
                                          <li>Explore potential themes and their connection to plot/character.</li>
                                          <li>Analyze and subvert genre tropes.</li>
                                          <li>Develop initial plot outlines or narrative arcs.</li>
                                          <li>Document core concepts for the Story Bible.</li>
                                      </ul>
                                      <p>Aim to produce compelling, marketable, and thematically resonant core story concepts ready for further development.</p>
                                    </div>
                                   <!-- SECTION SYSTEM PROMPT END - SECTION_ID: D2-S1 -->
                                   <div class="prompt-item" id="D2-S1.1">
                                     <strong>1. Act as a Concept Development Expert:</strong>
                                     <p>Brainstorm original story concepts, including plot ideas, character archetypes, and thematic elements for a novel in the [genre] genre.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Generates foundational story ideas, incorporating core narrative components.</p>
                                         <p><strong>Best Used For:</strong> Initial brainstorming phase, exploring potential directions for a new novel within a specified genre.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S1.2">
                                     <strong>2. Act as a Genre Tropes Analyst:</strong>
                                     <p>Identify common tropes in [Genre] and brainstorm 3 ways to subvert or uniquely combine them for a new story concept. Document these variations.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Analyzes genre conventions and generates ideas for playing with or breaking reader expectations.</p>
                                         <p><strong>Best Used For:</strong> Adding originality to genre fiction, avoiding clichés, understanding genre conventions deeply. Requires specifying the genre.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S1.3">
                                     <strong>3. Act as a Theme Weaver:</strong>
                                     <p>Propose 3 central themes for a story based on [Premise] and outline specific plot points or character moments where each theme could be explored. Add this to the story bible's theme section.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Identifies potential underlying messages and suggests ways to integrate them meaningfully into the narrative structure.</p>
                                         <p><strong>Best Used For:</strong> Defining the core message/meaning of a story early on, ensuring thematic depth, planning narrative resonance. Requires a basic premise.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S1.4">
                                     <strong>4. (WG I-1) Idea Spark:</strong>
                                     <p>"Generate 10 original story ideas within the [genre] genre, each with a brief premise and potential conflict."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Rapid generation of multiple brief story concepts focused on premise and conflict.</p>
                                         <p><strong>Best Used For:</strong> Quick idea generation when starting from scratch, exploring different conflict types within a genre. Requires specifying the genre.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S1.5">
                                     <strong>5. (WG I-2) Theme Exploration:</strong>
                                     <p>"Brainstorm 5 potential themes for a story about [subject], and for each theme, provide 3 examples of how it could be explored in the narrative."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Deepens thematic understanding by linking potential themes to concrete narrative examples.</p>
                                         <p><strong>Best Used For:</strong> Developing thematic complexity, planning how themes will manifest in the story. Requires specifying the subject.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S1.6">
                                     <strong>6. (WG I-5) Plot Outline (Initial):</strong>
                                     <p>"Generate 3 different plot outlines for a story about [character] in [setting], each with a distinct narrative arc."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Creates high-level narrative structures, exploring different potential journeys for a character.</p>
                                         <p><strong>Best Used For:</strong> Early plot development, comparing different structural possibilities before committing. Requires basic character/setting info.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S1.7">
                                     <strong>7. (WG I-6) Genre Blending:</strong>
                                     <p>"Explore the possibilities of blending [genre 1] and [genre 2]. Generate 3 story ideas that combine elements of both genres."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Facilitates creative fusion of different genre conventions to spark unique concepts.</p>
                                         <p><strong>Best Used For:</strong> Generating original cross-genre ideas, exploring less common narrative spaces. Requires specifying the genres.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S1.8">
                                     <strong>8. (WG I-7) Concept Refinement:</strong>
                                     <p>"Refine this initial story concept: [brief concept]. Expand on the setting, characters, and central conflict."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Takes a basic idea and fleshes it out with more detail across key story elements.</p>
                                         <p><strong>Best Used For:</strong> Developing promising initial ideas, moving from premise to a more concrete concept. Requires providing the brief concept.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S1.9">
                                     <strong>9. (WG I-8) Inspiration Mining:</strong>
                                     <p>"Analyze the following text [text excerpt] and extract potential story ideas, themes, or character inspiration."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Uses existing text as a springboard for new creative ideas by identifying inspiring elements.</p>
                                         <p><strong>Best Used For:</strong> Finding inspiration from existing works, overcoming creative blocks, requires providing the text excerpt.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S1.10">
                                     <strong>10. (WG I-9) What If Scenario:</strong>
                                     <p>"Explore the 'what if' scenario: 'What if [unusual event] occurred in [historical period]?' Develop a story concept based on this premise."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Generates alternative history or speculative fiction concepts based on a defined counterfactual premise.</p>
                                         <p><strong>Best Used For:</strong> Creating alternate history/speculative concepts, exploring causal chains. Requires specifying the event and period.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S1.11">
                                     <strong>11. (WG I-10) Symbolism Generator:</strong>
                                     <p>"Generate 5 potential symbols that could represent the theme of [theme] in a story. Explain the potential meaning and impact of each symbol."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Brainstorms symbolic elements relevant to a theme and analyzes their potential meaning.</p>
                                         <p><strong>Best Used For:</strong> Adding symbolic depth to a story, planning thematic motifs. Requires specifying the theme.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S1.12">
                                     <strong>12. (WG Addon 16) Role: Idea Generator:</strong>
                                     <p>Brainstorm 10 original story concepts that blend the genres of [genre 1] and [genre 2], each with a unique premise and potential for character development.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Focused generation of cross-genre ideas emphasizing premise and character potential.</p>
                                         <p><strong>Best Used For:</strong> Intensive cross-genre brainstorming, finding unique character hooks within blended genres. Requires specifying the genres.</p>
                                     </div>
                                   </div>
                                  <div class="prompt-item" id="D2-S1.13">
                                     <strong>13. Act as a High-Concept Pitch Doctor:</strong>
                                     <p>Take this basic premise [Premise Text] and refine it into 3 distinct high-concept pitches, each with a compelling hook and clear genre identification suitable for the Story Bible's core info.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Focuses on distilling a story idea into its most marketable and intriguing core concept (the "hook").</p>
                                         <p><strong>Best Used For:</strong> Refining ideas for pitching, identifying the core appeal of a story, preparing query materials. Requires a basic premise.</p>
                                     </div>
                                  </div>
                                  <div class="prompt-item" id="D2-S1.14">
                                     <strong>14. Act as a Logline Specialist:</strong>
                                     <p>Generate 5 different loglines for this story concept [Concept Summary], ensuring each is concise, highlights the protagonist, conflict, and stakes. Select the best for the Story Bible.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Crafts the essential one-sentence summary of a story, crucial for pitching and understanding the core narrative.</p>
                                         <p><strong>Best Used For:</strong> Creating concise story summaries, query letter preparation, testing the clarity of a concept. Requires a concept summary.</p>
                                     </div>
                                  </div>
                              </div>
                         </details> <!-- End Stage 1 -->

                         <!-- Stage 2: Worldbuilding & Setting -->
                         <details id="D2-S2">
                             <summary>Stage 2: Worldbuilding & Setting</summary>
                              <div>
                                   <!-- SECTION SYSTEM PROMPT START - SECTION_ID: D2-S2 -->
                                   <div class="system-prompt-block">
                                      <h4>System Instruction</h4>
                                      <p><strong>Context:</strong> Book Writing - Stage 2: Worldbuilding & Setting Development</p>
                                     <p>Adopt the persona of a <strong>Comprehensive Worldbuilder</strong>. Focus on creating detailed, consistent, and immersive fictional worlds (history, geography, culture, rules, atmosphere). Ensure internal logic. Aim for concrete details suitable for a story bible.</p>
                                      <p><strong>Internal Steps (Consider these when responding):</strong></p>
                                      <ul>
                                          <li>Develop foundational elements (history, geography, core rules).</li>
                                          <li>Design specific cultures (customs, beliefs, social structures).</li>
                                          <li>Create immersive setting descriptions (atmosphere, sensory details).</li>
                                          <li>Ensure internal consistency and logical coherence of world elements.</li>
                                          <li>Explore the impact of the world/setting on characters and plot.</li>
                                          <li>Compile details into organized Story Bible entries.</li>
                                      </ul>
                                      <p>Aim to build a believable, engaging, and internally consistent world that serves the story.</p>
                                   </div>
                                   <!-- SECTION SYSTEM PROMPT END - SECTION_ID: D2-S2 -->
                                   <div class="prompt-item" id="D2-S2.1">
                                     <strong>1. Act as a Worldbuilding Expert:</strong>
                                     <p>Develop a detailed and immersive world for a fantasy novel, including its history, geography, cultures, and magic systems.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Generates comprehensive foundational elements for a fictional world, particularly suited for fantasy.</p>
                                         <p><strong>Best Used For:</strong> Initial world creation, establishing core rules and background for speculative fiction.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S2.2">
                                     <strong>2. (WG IV-31) Setting Description:</strong>
                                     <p>"Create a vivid description of [setting], focusing on its atmosphere, sensory details, and cultural elements."</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Focuses on crafting immersive textual descriptions of specific locations.</p>
                                         <p><strong>Best Used For:</strong> Bringing settings to life in prose, establishing mood through description. Requires specifying the setting.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S2.3">
                                     <strong>3. (WG IV-32) Worldbuilding Detail:</strong>
                                     <p>"Expand on this brief setting description: [brief description]. Add details about its history, geography, and social structure."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Takes a basic setting idea and adds layers of detail across multiple facets (history, geography, society).</p>
                                         <p><strong>Best Used For:</strong> Developing existing setting concepts, adding depth and plausibility. Requires providing the brief description.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S2.4">
                                     <strong>4. (WG IV-33) Cultural Development:</strong>
                                     <p>"Develop the cultural aspects of [setting], including its customs, traditions, beliefs, and social norms."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Focuses specifically on creating the intangible aspects of a fictional society.</p>
                                         <p><strong>Best Used For:</strong> Making fictional cultures feel distinct and believable, informing character behavior. Requires specifying the setting/culture.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S2.5">
                                     <strong>5. (WG IV-34) Historical Context:</strong>
                                     <p>"Create a detailed historical timeline for [setting], outlining key events and their impact on the present day."</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Builds a backstory for the world or setting, establishing causality and context for the current state.</p>
                                         <p><strong>Best Used For:</strong> Adding historical depth, justifying current conflicts or societal structures, world bible content. Requires specifying the setting.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S2.6">
                                     <strong>6. (WG IV-35) Geographic Description:</strong>
                                     <p>"Describe the geography of [setting], including its landscape, climate, and natural resources."</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Focuses on the physical environment of the setting.</p>
                                         <p><strong>Best Used For:</strong> Creating believable landscapes, informing travel/survival elements, map creation input. Requires specifying the setting.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S2.7">
                                     <strong>7. (WG IV-36) Atmosphere Creation:</strong>
                                     <p>"Generate sensory details and imagery to create a specific atmosphere in [setting], such as suspense, mystery, or romance."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Targets the use of description to evoke a specific mood or feeling associated with a place.</p>
                                         <p><strong>Best Used For:</strong> Enhancing scene mood, creating immersive experiences, ensuring setting supports tone. Requires specifying setting and desired atmosphere.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S2.8">
                                     <strong>8. (WG IV-37) Worldbuilding Consistency:</strong>
                                     <p>"Check this description of [setting] for internal consistency and logical coherence."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Analyzes existing worldbuilding material to identify contradictions or logical flaws.</p>
                                         <p><strong>Best Used For:</strong> Editing worldbuilding documents, ensuring believability, preventing plot holes related to world rules. Requires providing the description.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S2.9">
                                     <strong>9. (WG IV-38) Unique Setting Element:</strong>
                                     <p>"Introduce a unique and memorable element to the setting, such as a strange creature, a magical phenomenon, or a distinctive architectural style."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Brainstorms novel features to make a setting stand out.</p>
                                         <p><strong>Best Used For:</strong> Adding originality, creating memorable world details, sparking plot ideas related to the setting.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S2.10">
                                     <strong>10. (WG IV-39) Setting Impact on Characters:</strong>
                                     <p>"Explore how the setting influences the characters' behavior, beliefs, and relationships."</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Analyzes the interaction between environment and character, ensuring the setting is not just backdrop but an active force.</p>
                                         <p><strong>Best Used For:</strong> Deepening characterization, making the world feel integral to the story, exploring themes through setting.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S2.11">
                                     <strong>11. (WG IV-40) Setting as Symbolism:</strong>
                                     <p>"Use the setting to symbolize or reflect the themes and emotions of the story."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Explores how locations or environmental features can represent abstract ideas or character states.</p>
                                         <p><strong>Best Used For:</strong> Adding thematic layers, using description for subtext, enhancing literary depth.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S2.12">
                                     <strong>12. (WG Addon 17) Role: World-Builder:</strong>
                                     <p>Develop a detailed outline of a fictional world for a fantasy novel, including its geography, history, culture, magic system (if applicable), and key political factions.</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Similar to #1 but specifically requests an *outline* format, focusing on key structured elements.</p>
                                         <p><strong>Best Used For:</strong> Creating structured world bible entries, organizing worldbuilding thoughts systematically.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S2.13">
                                     <strong>13. (WG Addon 20) Role: Scene Setter:</strong>
                                     <p>Write five vivid and immersive scene descriptions that establish the setting, atmosphere, and mood for different key moments in a story.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Generates multiple distinct setting descriptions tailored to specific narrative moments.</p>
                                         <p><strong>Best Used For:</strong> Pre-writing key scenes, establishing varied moods, practicing descriptive variety.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S2.14">
                                     <strong>14. (WG Addon 33) Role: Setting Expert:</strong>
                                     <p>Help create immersive and detailed settings that enhance the story's atmosphere and themes.</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Acts as a consultant offering advice and techniques for improving setting descriptions and their narrative function.</p>
                                         <p><strong>Best Used For:</strong> Getting feedback on setting ideas, learning techniques for better description, enhancing atmosphere.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S2.15">
                                     <strong>15. (WG Addon 38) Role: Worldbuilding Expert (Fantasy):</strong>
                                     <p>Provide specialized guidance on building complex and believable fantasy worlds.</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Offers advice tailored specifically to the conventions and challenges of the fantasy genre (magic systems, non-human races, etc.).</p>
                                         <p><strong>Best Used For:</strong> Developing fantasy worlds, troubleshooting fantasy worldbuilding issues, understanding genre expectations.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S2.16">
                                     <strong>16. (WG Addon 41) Role: Fantasy World-Builder:</strong>
                                     <p>Develop a unique magic system for a fantasy world, including its rules, limitations, and impact on the society and characters. (Cross-references with G1)</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Focuses specifically on the creation and integration of a magic system, a core fantasy element.</p>
                                         <p><strong>Best Used For:</strong> Designing magic systems, ensuring internal consistency, exploring magic's societal impact.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S2.17">
                                     <strong>17. Act as a Worldbuilding Architect:</strong>
                                     <p>Outline the fundamental rules (physics, magic, technology) governing [Fictional World Name]. Document these core principles for the story bible. (Cross-references G1/G4)</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Establishes the foundational 'laws' of the fictional reality, crucial for consistency.</p>
                                         <p><strong>Best Used For:</strong> Creating the core rule set for a world bible, ensuring logical consistency in world mechanics. Requires specifying world name.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S2.18">
                                     <strong>18. Act as a Cultural Anthropologist (Fiction):</strong>
                                     <p>Develop the core social structures, customs, beliefs, and potential conflicts for a primary culture in [Fictional World Name]. Create a story bible entry for this culture.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Applies anthropological thinking to create detailed and believable fictional cultures.</p>
                                         <p><strong>Best Used For:</strong> Deep cultural worldbuilding, creating distinct societies, generating plot conflicts based on cultural differences. Requires specifying world/culture name.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S2.19">
                                     <strong>19. Act as a Fictional Historian:</strong>
                                     <p>Create a concise timeline of major historical events leading up to the present day in [Fictional World Name]. Add this timeline to the story bible's history section.</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Generates a summarized history, focusing on events relevant to the story's present.</p>
                                         <p><strong>Best Used For:</strong> Quickly establishing world backstory for a story bible, identifying key historical context points. Requires specifying world name.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S2.20">
                                     <strong>20. Act as a Setting Visualizer:</strong>
                                     <p>Write a detailed, multi-sensory description of a key location (e.g., capital city, forbidden forest, space station hub) for the story bible.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Focuses on creating rich, evocative descriptions suitable for direct use or reference in a story bible.</p>
                                         <p><strong>Best Used For:</strong> Populating a story bible with setting details, pre-writing key location descriptions. Requires specifying the location type.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S2.21">
                                     <strong>21. Act as a Magic System Consequences Expert:</strong>
                                     <p>Analyze the defined magic system [Rules Text from G1/G4]. Brainstorm 3 unforeseen social, economic, or personal consequences of its widespread use within the world. Add to Story Bible.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Explores the ripple effects and societal implications of a magic system beyond its direct use.</p>
                                         <p><strong>Best Used For:</strong> Adding depth and realism to magic systems, generating plot ideas based on consequences. Requires providing the magic system rules.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S2.22">
                                     <strong>22. Act as a Fictional Technology Consultant:</strong>
                                     <p>Evaluate the plausibility and implications of the proposed technology [Tech Description from G4/F] in a sci-fi setting. Suggest refinements for consistency.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Critiques proposed sci-fi tech for internal logic and explores its potential impact within the story world.</p>
                                         <p><strong>Best Used For:</strong> Refining sci-fi concepts, ensuring technological consistency, exploring tech's societal impact. Requires providing the tech details.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S2.23">
                                     <strong>23. Act as a Fictional Cartographer's Consultant:</strong>
                                     <p>Based on the described geography [Geography Notes from Stage 2/F1], sketch a basic conceptual map for the Story Bible, highlighting key regions, political boundaries, and points of interest relevant to the plot.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Translates textual geographic descriptions into a conceptual map layout (descriptive or simple ASCII/structured text).</p>
                                         <p><strong>Best Used For:</strong> Visualizing world layout, planning character journeys, creating map reference for story bible. Requires providing geography notes.</p>
                                     </div>
                                   </div>
                                  <div class="prompt-item" id="D2-S2.24">
                                     <strong>24. Act as a Cultural Detail Generator:</strong>
                                     <p>For the [Culture Name] culture in the Story Bible, generate details about their naming conventions, funeral rites, and a common social taboo.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Generates specific, often overlooked, cultural details that add flavor and realism.</p>
                                         <p><strong>Best Used For:</strong> Fleshing out fictional cultures, adding unique cultural identifiers, informing character interactions. Requires specifying the culture name.</p>
                                     </div>
                                  </div>
                                  <div class="prompt-item" id="D2-S2.25">
                                     <strong>25. Act as a World Bible Compiler:</strong>
                                     <p>Organize all generated worldbuilding notes (history, culture, geography, rules) into a clean, easily navigable section within the story bible.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Structures and formats disparate worldbuilding information into a coherent document section.</p>
                                         <p><strong>Best Used For:</strong> Creating the final worldbuilding section of a story bible, ensuring information is well-organized. Requires providing the raw notes.</p>
                                     </div>
                                   </div>
                              </div>
                         </details> <!-- End Stage 2 -->

                         <!-- Stage 3: Character Development -->
                         <details id="D2-S3">
                             <summary>Stage 3: Character Development</summary>
                              <div>
                                   <!-- SECTION SYSTEM PROMPT START - SECTION_ID: D2-S3 -->
                                   <div class="system-prompt-block">
                                      <h4>System Instruction</h4>
                                      <p><strong>Context:</strong> Book Writing - Stage 3: Character Development</p>
                                      <p>Adopt the persona of a <strong>Character Architect and Psychologist</strong>. Focus on creating compelling, nuanced characters with clear motivations, backstories, relationships, voice, flaws, strengths, and potential for growth (arcs). Provide details suitable for character sheets and story planning.</p>
                                      <p><strong>Internal Steps (Consider these when responding):</strong></p>
                                      <ul>
                                          <li>Develop core character concepts (motivation, flaw, goal).</li>
                                          <li>Craft detailed backstories linking past events to present personality.</li>
                                          <li>Define internal and external conflicts.</li>
                                          <li>Outline character arcs and key turning points.</li>
                                          <li>Develop unique character voices and mannerisms.</li>
                                          <li>Map out key relationships and their dynamics.</li>
                                          <li>Ensure characters feel psychologically believable and serve the narrative.</li>
                                      </ul>
                                      <p>Aim to create memorable, relatable, and dynamic characters whose journeys drive the story forward.</p>
                                  </div>
                                   <!-- SECTION SYSTEM PROMPT END - SECTION_ID: D2-S3 -->
                                   <div class="prompt-item" id="D2-S3.1">
                                     <strong>1. Act as a Character Development Expert:</strong>
                                     <p>Create compelling and nuanced characters with detailed backstories, motivations, and character arcs for a [genre] novel.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Provides high-level guidance and generation for core character components.</p>
                                         <p><strong>Best Used For:</strong> Initial character brainstorming, developing main character concepts, getting expert-style advice on character creation.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S3.2">
                                     <strong>2. (WG II-11) Character Backstory:</strong>
                                     <p>"Develop a detailed backstory for [character name], including their childhood, formative experiences, and significant relationships."</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Generates the history and formative past of a specific character.</p>
                                         <p><strong>Best Used For:</strong> Adding depth and motivation, understanding character origins, populating character sheets. Requires specifying the character.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S3.3">
                                     <strong>3. (WG II-12) Character Motivation:</strong>
                                     <p>"Define the primary motivation for [character name] and explore how this motivation drives their actions throughout the story."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Identifies and analyzes the core driving force behind a character's behavior.</p>
                                         <p><strong>Best Used For:</strong> Ensuring character actions are motivated, defining goals, clarifying stakes. Requires specifying the character.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S3.4">
                                     <strong>4. (WG II-13) Character Arc:</strong>
                                     <p>"Outline the character arc for [character name], detailing their transformation from the beginning to the end of the story."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Plans the trajectory of a character's growth, change, or decline throughout the narrative.</p>
                                         <p><strong>Best Used For:</strong> Structuring character development, ensuring satisfying arcs, plotting key transformative moments. Requires specifying the character.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S3.5">
                                     <strong>5. (WG II-14) Character Relationships:</strong>
                                     <p>"Explore the dynamic between [character 1] and [character 2]. Describe their relationship, including its strengths, weaknesses, and potential conflicts."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Analyzes and defines the connection and potential friction between two characters.</p>
                                         <p><strong>Best Used For:</strong> Developing subplots, creating believable interactions, understanding character dynamics. Requires specifying the characters.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S3.6">
                                     <strong>6. (WG II-15) Character Voice:</strong>
                                     <p>"Develop a unique and consistent voice for [character name], including their speech patterns, vocabulary, and tone."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Focuses on creating a distinct linguistic style for a character's dialogue and narration.</p>
                                         <p><strong>Best Used For:</strong> Differentiating characters, making dialogue realistic, establishing personality through speech. Requires specifying the character.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S3.7">
                                     <strong>7. (WG II-16) Character Internal Conflict:</strong>
                                     <p>"Create an internal conflict for [character name] that challenges their beliefs or motivations."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Generates inner struggles or moral dilemmas for a character, adding psychological depth.</p>
                                         <p><strong>Best Used For:</strong> Adding complexity to characters, creating internal stakes, driving character arcs. Requires specifying the character.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S3.8">
                                     <strong>8. (WG II-17) Character Design:</strong>
                                     <p>"Describe the physical appearance, mannerisms, and distinctive features of [character name]."</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Focuses on the external, visual aspects of a character.</p>
                                         <p><strong>Best Used For:</strong> Creating vivid character descriptions, aiding visualization, providing details for artists/cover designers. Requires specifying the character.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S3.9">
                                     <strong>9. (WG II-18) Character Strengths and Weaknesses:</strong>
                                     <p>"Identify the key strengths and weaknesses of [character name] and explain how these traits impact their actions."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Defines core positive and negative traits and links them to character behavior.</p>
                                         <p><strong>Best Used For:</strong> Creating balanced characters, explaining character actions, identifying potential conflict sources. Requires specifying the character.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S3.10">
                                     <strong>10. (WG II-19) Character Development Prompt:</strong>
                                     <p>"Expand on this brief character description: [brief description]. Add details about their personality, relationships, and goals."</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Takes a skeletal character idea and adds layers of detail across multiple dimensions.</p>
                                         <p><strong>Best Used For:</strong> Fleshing out minor characters or initial concepts, developing existing ideas further. Requires providing the brief description.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S3.11">
                                     <strong>11. (WG II-20) Character Interaction:</strong>
                                     <p>"Write a scene where [character 1] and [character 2] interact, focusing on their dialogue, body language, and the underlying tension or connection between them."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Generates a specific scene focused on showcasing a character relationship through interaction.</p>
                                         <p><strong>Best Used For:</strong> Exploring character dynamics, practicing dialogue/subtext, revealing character through action. Requires specifying the characters.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S3.12">
                                     <strong>12. (WG VII-69) Character Complexity:</strong>
                                     <p>"Add layers of complexity to [character name] by giving them conflicting motivations or hidden depths."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Focuses specifically on making a character less one-dimensional by introducing internal contradictions or secrets.</p>
                                         <p><strong>Best Used For:</strong> Refining main characters, creating more realistic and intriguing personalities. Requires specifying the character.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S3.13">
                                     <strong>13. (WG VII-72) Voice Differentiation:</strong>
                                     <p>"Create distinct voices for different characters through their dialogue and narration."</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Advises on or demonstrates techniques for making multiple characters sound unique in their speech.</p>
                                         <p><strong>Best Used For:</strong> Improving dialogue realism, differentiating large casts, ensuring character consistency.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S3.14">
                                     <strong>14. (WG Addon 18) Role: Character Developer:</strong>
                                     <p>Create five detailed character profiles for a novel, including their backstories, motivations, relationships, strengths, weaknesses, and potential for growth.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Generates multiple complete character profiles following a standard template.</p>
                                         <p><strong>Best Used For:</strong> Populating a story bible with core cast information, initial character roster creation.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S3.15">
                                     <strong>15. (WG Addon 29) Role: Character Arc Expert:</strong>
                                     <p>Guide the development of compelling and satisfying character arcs.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Acts as a consultant providing advice and strategies for planning character transformation.</p>
                                         <p><strong>Best Used For:</strong> Planning character journeys, ensuring meaningful development, troubleshooting flat arcs.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S3.16">
                                     <strong>16. (WG Addon 37) Role: Backstory Expert:</strong>
                                     <p>Advise on the effective use of backstory to reveal character motivations and inform the present narrative.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Focuses on the narrative technique of integrating past events without info-dumping.</p>
                                         <p><strong>Best Used For:</strong> Weaving backstory naturally into the plot, revealing character history effectively, avoiding exposition dumps.</p>
                                     </div>
                                   </div>
                                  <div class="prompt-item" id="D2-S3.17">
                                     <strong>17. Act as a Character Concept Generator:</strong>
                                     <p>Create profiles for 3 potential main characters, including core motivation, fatal flaw, and initial relationship dynamics. Format for story bible character sheets.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Generates concise starting profiles focused on core driving elements (motivation, flaw, relationships).</p>
                                         <p><strong>Best Used For:</strong> Rapid initial character brainstorming, creating core concepts for story bible entries.</p>
                                     </div>
                                  </div>
                                  <div class="prompt-item" id="D2-S3.18">
                                     <strong>18. Act as a Character Backstory Developer:</strong>
                                     <p>Take [Character Name] and write a detailed backstory, focusing on formative events that shape their current personality and goals. Add this to their character sheet.</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Focuses on generating the narrative of a character's past, specifically linking events to present traits.</p>
                                         <p><strong>Best Used For:</strong> Creating in-depth character histories for story bibles, understanding character psychology. Requires specifying the character.</p>
                                     </div>
                                  </div>
                                  <div class="prompt-item" id="D2-S3.19">
                                     <strong>19. Act as a Character Voice Specialist:</strong>
                                     <p>Write a short monologue for [Character Name] that clearly establishes their unique voice, vocabulary, and speaking patterns. Include this in their story bible profile.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Generates a sample of a character's speech to define their voice clearly.</p>
                                         <p><strong>Best Used For:</strong> Establishing voice early, providing a reference for dialogue writing, story bible character entries. Requires specifying the character.</p>
                                     </div>
                                  </div>
                                  <div class="prompt-item" id="D2-S3.20">
                                     <strong>20. Act as a Character Arc Planner:</strong>
                                     <p>Outline a potential character arc for [Character Name] across a three-act structure, defining their starting point, key turning points, and potential ending state. Document this arc.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Creates a structured plan for a character's journey throughout the main plot points.</p>
                                         <p><strong>Best Used For:</strong> Integrating character development with plot structure, ensuring purposeful arcs, story bible planning. Requires specifying the character.</p>
                                     </div>
                                  </div>
                                  <div class="prompt-item" id="D2-S3.21">
                                     <strong>21. Act as a Relationship Dynamics Mapper:</strong>
                                     <p>Describe the initial relationship (conflict, alliance, mentorship, romance) between [Character A] and [Character B], including potential future developments. Add this to a relationships section in the story bible.</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Defines the nature and potential evolution of the connection between two specific characters.</p>
                                         <p><strong>Best Used For:</strong> Planning character interactions, developing subplots, tracking relationship changes, story bible entries. Requires specifying characters.</p>
                                     </div>
                                  </div>
                                  <div class="prompt-item" id="D2-S3.22">
                                     <strong>22. Act as a Character Motivation Deep-Diver:</strong>
                                     <p>For [Character Name], explore the root cause of their primary motivation [Stated Motivation]. What past event or core belief fuels it? Add this depth to their Story Bible profile.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Goes beyond surface motivation to uncover the underlying psychological or historical reasons for a character's drive.</p>
                                         <p><strong>Best Used For:</strong> Adding psychological realism, creating complex motivations, understanding character actions on a deeper level. Requires specifying character and stated motivation.</p>
                                     </div>
                                  </div>
                                  <div class="prompt-item" id="D2-S3.23">
                                     <strong>23. Act as a Character Flaw Integrator:</strong>
                                     <p>Identify [Character Name]'s fatal flaw [Flaw]. Suggest 3 specific plot points where this flaw could actively hinder their progress or create conflict. Document in the Story Bible notes.</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Connects a defined character flaw directly to potential plot events where it causes problems.</p>
                                         <p><strong>Best Used For:</strong> Making flaws narratively relevant, generating conflict, ensuring character weaknesses impact the story. Requires specifying character and flaw.</p>
                                     </div>
                                  </div>
                                  <div class="prompt-item" id="D2-S3.24">
                                     <strong>24. Act as a Character Voice Authenticator:</strong>
                                     <p>Read this dialogue intended for [Character Name] [Dialogue Text]. Does it align with their established background, personality, and vocabulary in the Story Bible? Suggest specific phrasing adjustments.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Evaluates existing dialogue for consistency with a character's established voice.</p>
                                         <p><strong>Best Used For:</strong> Editing dialogue, ensuring character consistency, refining voice. Requires character details and dialogue text.</p>
                                     </div>
                                  </div>
                                  <div class="prompt-item" id="D2-S3.25">
                                     <strong>25. Act as a Character Arc Turning Point Designer:</strong>
                                     <p>For [Character Name]'s planned arc [Arc Outline], pinpoint the exact moment/event that should serve as the major turning point challenging their core beliefs. Describe this scene's potential impact for the Story Bible.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Identifies and helps design the crucial moments of change within a character's planned arc.</p>
                                         <p><strong>Best Used For:</strong> Plotting key character development scenes, ensuring arcs have significant impact points. Requires character and arc outline.</p>
                                     </div>
                                  </div>
                                  <div class="prompt-item" id="D2-S3.26">
                                     <strong>26. Act as a Secondary Character Impact Assessor:</strong>
                                     <p>Evaluate the roles of [Secondary Character A] and [Secondary Character B] in the Story Bible. How do they primarily influence the protagonist's journey or the main plot? Are there opportunities to make their impact stronger?</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Analyzes the narrative purpose and effectiveness of supporting characters.</p>
                                         <p><strong>Best Used For:</strong> Refining subplots, ensuring secondary characters serve the story, identifying potential character cuts or expansions. Requires character details.</p>
                                     </div>
                                  </div>
                                  <div class="prompt-item" id="D2-S3.27">
                                     <strong>27. Act as a Character Sheet Standardizer:</strong>
                                     <p>Ensure all main character profiles in the story bible follow a consistent format and include essential information (goals, flaws, arc, relationships).</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Organizes and formats character information for consistency and usability within a story bible.</p>
                                         <p><strong>Best Used For:</strong> Story bible maintenance, ensuring all key character data is captured uniformly. Requires providing existing profiles.</p>
                                     </div>
                                  </div>
                                  <div class="prompt-item" id="D2-S3.28">
                                     <strong>28. Act as a Character Interviewer:</strong>
                                     <p>Formulate 5 interview questions to ask your main character [Character Name] as if they were real, to uncover deeper insights into their personality and motivations beyond what's already in the Story Bible.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Uses an interview format as a creative technique to explore character psychology and voice.</p>
                                         <p><strong>Best Used For:</strong> Deepening character understanding, discovering unexpected traits, generating character voice samples. Requires specifying character.</p>
                                     </div>
                                  </div>
                              </div>
                         </details> <!-- End Stage 3 -->

                         <!-- Stage 4: Plot Development & Structure -->
                         <details id="D2-S4">
                             <summary>Stage 4: Plot Development & Structure</summary>
                              <div>
                                   <!-- SECTION SYSTEM PROMPT START - SECTION_ID: D2-S4 -->
                                   <div class="system-prompt-block">
                                      <h4>System Instruction</h4>
                                      <p><strong>Context:</strong> Book Writing - Stage 4: Plot Development & Structure</p>
                                     <p>Adopt the persona of a <strong>Narrative Designer and Plot Consultant</strong>. Focus on creating engaging, coherent plot structures (outlines, beat sheets), scene design, conflict escalation, pacing, and tension, leveraging existing world and character context. Check for plot holes.</p>
                                      <p><strong>Internal Steps (Consider these when responding):</strong></p>
                                       <ul>
                                           <li>Design overall plot structure (e.g., three-act, hero's journey).</li>
                                           <li>Develop key plot points (inciting incident, rising action, climax, resolution).</li>
                                           <li>Outline scenes/chapters with clear objectives and causal links.</li>
                                           <li>Manage pacing, tension, and suspense through structural choices.</li>
                                           <li>Integrate subplots effectively.</li>
                                           <li>Brainstorm twists and reveals.</li>
                                           <li>Identify and resolve plot holes/inconsistencies using Bible context.</li>
                                       </ul>
                                      <p>Aim to build a compelling and logical narrative roadmap that effectively utilizes the established characters and world.</p>
                                  </div>
                                   <!-- SECTION SYSTEM PROMPT END - SECTION_ID: D2-S4 -->
                                   <div class="prompt-item" id="D2-S4.1">
                                     <strong>1. Act as a Plot Architect:</strong>
                                     <p>Design a complex and engaging plot structure for a thriller novel, including inciting incidents, rising action, climax, and resolution.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Provides high-level structural planning for a narrative, focusing on key turning points and overall shape.</p>
                                         <p><strong>Best Used For:</strong> Initial plot outlining, structuring complex narratives, ensuring a cohesive story arc. Specify genre for better results.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S4.2">
                                     <strong>2. Act as a Narrative Structure Expert:</strong>
                                     <p>Outline different narrative structures (e.g., linear, non-linear, multiple POV) and advise on the best choice for a [genre] novel with the concept from Stage 1.</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Compares and contrasts different ways to organize the telling of a story, offering expert advice on suitability based on concept.</p>
                                         <p><strong>Best Used For:</strong> Choosing the right narrative approach early on, understanding structural options, planning complex timelines or perspectives.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S4.3">
                                     <strong>3. (WG III-21) Plot Point Generator:</strong>
                                     <p>"Generate 3 key plot points for a story about [character name from Stage 3] that escalate the conflict and drive the narrative forward, consistent with their motivations."</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Brainstorms specific major events or turning points designed to increase stakes and advance the story, tied to character.</p>
                                         <p><strong>Best Used For:</strong> Developing the middle of a plot, overcoming sagging middles, finding ways to escalate conflict. Requires character context.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S4.4">
                                     <strong>4. (WG III-22) Narrative Structure:</strong>
                                     <p>"Outline the narrative structure for the story, including the exposition, rising action, climax, falling action, and resolution, referencing key characters (Stage 3) and setting (Stage 2)."</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Creates a basic outline based on the classic five-part dramatic structure, integrating existing Bible elements.</p>
                                         <p><strong>Best Used For:</strong> Standard plot outlining, ensuring all key structural elements are considered, story bible structure section.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S4.5">
                                     <strong>5. (WG III-23) Scene Creation:</strong>
                                     <p>"Create a detailed scene where [character from Stage 3] faces [conflict concept] in [setting from Stage 2], focusing on sensory details and emotional impact reflecting their personality."</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Generates the prose for a specific scene, emphasizing immersive description and character emotion based on Bible context.</p>
                                         <p><strong>Best Used For:</strong> Drafting key scenes, practicing descriptive writing, exploring character reactions. Requires referencing character, setting, conflict idea.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S4.6">
                                     <strong>6. (WG III-25) Pacing Control:</strong>
                                     <p>"Analyze the pacing of this drafted chapter/scene [text excerpt] and suggest ways to improve its flow and engagement, considering the overall plot structure planned in Stage 4."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Evaluates the speed and rhythm of a narrative section and provides feedback for improvement based on plot goals.</p>
                                         <p><strong>Best Used For:</strong> Editing drafts, fixing sections that feel too fast or too slow, improving reader engagement. Requires providing the text excerpt and plot context.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S4.7">
                                     <strong>7. (WG III-26) Conflict Development:</strong>
                                     <p>"Develop the central conflict of the story (identified in Stage 1), including its origins in the world/characters (Stage 2/3), how it escalates through the planned plot points (Stage 4), and potential resolutions."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Focuses on defining and elaborating the core struggle of the narrative from start to finish, grounded in Bible context.</p>
                                         <p><strong>Best Used For:</strong> Clarifying the main plot engine, ensuring conflict is well-defined and escalates logically.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S4.8">
                                     <strong>8. (WG III-27) Subplot Creation:</strong>
                                     <p>"Generate 2-3 subplots involving secondary characters [Names from Stage 3] that complement the main plot (Stage 4) and add depth or explore related themes (Stage 1)."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Brainstorms secondary storylines involving supporting characters or themes, linked to main plot/themes.</p>
                                         <p><strong>Best Used For:</strong> Adding narrative layers, developing secondary characters, enriching the main theme using Bible context.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S4.9">
                                     <strong>9. (WG III-28) Twist and Turn Generator:</strong>
                                     <p>"Create 2-3 plot twists or unexpected turns relevant to the established plot/characters/world that will surprise the reader and keep them engaged."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Brainstorms surprising narrative developments grounded in the existing story elements.</p>
                                         <p><strong>Best Used For:</strong> Adding unpredictability, increasing engagement, developing key plot points logically from context.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S4.10">
                                     <strong>10. (WG III-29) Plot Hole Identification:</strong>
                                     <p>"Analyze this plot outline [plot outline from Stage 4] and identify any potential plot holes or inconsistencies considering world rules (G1) and character motivations (Stage 3)."</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Critically reviews a plot structure for logical gaps, contradictions, or unresolved issues using Bible context.</p>
                                         <p><strong>Best Used For:</strong> Pre-drafting editing, ensuring narrative coherence, troubleshooting plot problems. Requires providing the outline.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S4.11">
                                     <strong>11. (WG III-30) Climax Design:</strong>
                                     <p>"Design a compelling climax for the story that resolves the central conflict (defined in D2-S4.7) and provides a satisfying culmination for the protagonist's arc (D2-S3.4)."</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Focuses on planning the peak moment of tension and its resolution, integrating plot and character arcs from Bible.</p>
                                         <p><strong>Best Used For:</strong> Outlining the story's finale, ensuring the ending is impactful and resolves key conflicts/arcs.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S4.12">
                                     <strong>12. (WG VII-70) Plot Complexity:</strong>
                                     <p>"Based on the current outline, suggest ways to add complexity to the plot by introducing relevant subplots (using secondary characters), meaningful twists, or moral dilemmas related to the core theme."</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Suggests specific techniques (subplots, twists, moral dilemmas) for making a plot more intricate using existing Bible elements.</p>
                                         <p><strong>Best Used For:</strong> Deepening a simple plot, adding layers of meaning or conflict, enhancing reader engagement.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S4.13">
                                     <strong>13. (WG VII-77) Structure Experimentation:</strong>
                                     <p>"Consider the linear plot outline. Could experimenting with a different structure (e.g., non-linear timeline showing backstory from D2-S3, multiple perspectives from key characters) enhance the story's theme or mystery? Discuss pros and cons."</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Encourages exploration of unconventional ways to organize and tell the story based on existing content.</p>
                                         <p><strong>Best Used For:</strong> Finding unique narrative approaches, challenging structural norms, requires a willingness to explore complex structures.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S4.14">
                                     <strong>14. (WG VII-78) Ending Design:</strong>
                                     <p>"Design a satisfying and memorable ending that resolves the central conflict and the main character arcs, leaving a lasting impact that resonates with the story's themes (from Stage 1)."</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Focuses on crafting the final moments of the story for maximum resolution and emotional/thematic resonance based on Bible context.</p>
                                         <p><strong>Best Used For:</strong> Planning the story's conclusion, ensuring thematic payoff, creating memorable endings.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S4.15">
                                     <strong>15. (WG Addon 16) Role: Outlining Expert:</strong>
                                     <p>Help create a detailed chapter-by-chapter outline for the novel, ensuring a logical flow of events, integrating plot points, character beats, and worldbuilding reveals based on Stages 1-4.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Acts as a consultant or collaborator in the process of building a detailed story outline using established Bible elements.</p>
                                         <p><strong>Best Used For:</strong> Structuring a novel before drafting, organizing plot points, ensuring logical progression.</p>
                                     </div>
                                   </div>
                                  <div class="prompt-item" id="D2-S4.16">
                                     <strong>16. (WG Addon 19) Role: Plot Architect:</strong>
                                     <p>Design a three-act plot structure for this specific story concept [Ref Stage 1], including the inciting incident, rising action (with 3 key turning points), climax, falling action, and resolution, incorporating key characters and conflicts from Stages 3 & 4.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Generates a complete plot structure based on the three-act model, tailored for the specific story concept using Bible context.</p>
                                         <p><strong>Best Used For:</strong> Creating a solid plot foundation, ensuring structural integrity based on established elements.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S4.17">
                                     <strong>17. (WG Addon 30) Role: Plot Twist Expert:</strong>
                                     <p>Advise on the effective placement and execution of potential plot twists within the current outline, ensuring they feel earned and impactful based on established foreshadowing or character secrets.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Provides guidance on *how* and *when* to deploy plot twists within the story structure for maximum impact.</p>
                                         <p><strong>Best Used For:</strong> Planning surprising reveals, learning twist techniques, avoiding predictable plotting using context.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S4.18">
                                     <strong>18. (WG Addon 31) Role: Cliffhanger Expert:</strong>
                                     <p>Review the planned ending points for chapters [Number] to [Number] in the outline. Suggest ways to craft more effective cliffhangers to create suspense and anticipation based on the ongoing plot threads.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Focuses on the specific technique of ending chapters on moments of high tension or unresolved questions within the outline context.</p>
                                         <p><strong>Best Used For:</strong> Improving chapter structure, serial fiction writing, maintaining reader engagement.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S4.19">
                                     <strong>19. (WG Addon 32) Role: Foreshadowing Expert:</strong>
                                     <p>Identify 3 key future events or reveals from the later parts of the plot outline. Suggest subtle ways to foreshadow these earlier in the outline (specific scenes or details) based on world/character context.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Offers advice on planting clues or hints earlier in the narrative outline that pay off later.</p>
                                         <p><strong>Best Used For:</strong> Creating satisfying reveals, building suspense subtly, ensuring plot cohesion during outlining.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S4.20">
                                     <strong>20. (WG Addon 35) Role: Conflict Expert:</strong>
                                     <p>Analyze the central conflict and key subplots. Ensure the stakes consistently rise throughout the outline and that the conflicts challenge the main characters appropriately based on their flaws/strengths (Stage 3).</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Provides advice on creating and escalating different types of conflict effectively throughout the plot structure.</p>
                                         <p><strong>Best Used For:</strong> Strengthening the core plot engine, raising stakes, ensuring conflicts are meaningful and character-driven.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S4.21">
                                     <strong>21. (WG Addon 36) Role: Resolution Expert:</strong>
                                     <p>Evaluate the planned resolution in the outline. Does it logically resolve the central conflict and major character arcs in a satisfying way that aligns with the established themes? Suggest refinements if needed.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Focuses on ensuring the planned conclusion feels earned, coherent, and thematically resonant based on the entire Bible context.</p>
                                         <p><strong>Best Used For:</strong> Planning story endings, ensuring conflicts/arcs are properly resolved, creating satisfying reader experiences.</p>
                                     </div>
                                   </div>
                                   <div class="prompt-item" id="D2-S4.22">
                                     <strong>22. (WG Addon 47) Role: Allegory Expert:</strong>
                                     <p>Review the plot outline and themes. Are there opportunities to strengthen the story's allegorical potential (if desired) by adjusting specific plot events or character roles to represent larger concepts more clearly?</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Explains and guides the technique of using characters/events to represent abstract ideas, analyzing the existing plot for potential.</p>
                                         <p><strong>Best Used For:</strong> Adding symbolic layers, exploring themes indirectly, writing fable-like narratives.</p>
                                     </div>
                                   </div>
                                  <div class="prompt-item" id="D2-S4.23">
                                     <strong>23. Act as a Plot Structure Consultant:</strong>
                                     <p>Compare the suitability of different narrative structures (linear, non-linear, multi-POV) for the story defined by Stages 1-3 and recommend the best fit, justifying the choice for the story bible rationale.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Analyzes the specific story premise/characters/world and advises on the most effective structural approach.</p>
                                         <p><strong>Best Used For:</strong> Making informed decisions about narrative structure based on existing content, tailoring structure to story needs.</p>
                                     </div>
                                  </div>
                                  <div class="prompt-item" id="D2-S4.24">
                                     <strong>24. Act as a Story Beats Orchestrator:</strong>
                                     <p>Define the key story beats (Inciting Incident, Plot Point 1, Midpoint, Plot Point 2, Climax, Resolution) for the proposed plot outline. Write brief descriptions for each beat in the story bible, ensuring they align with character arcs.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Identifies and defines the major structural turning points within a given plot outline, linking to character development.</p>
                                         <p><strong>Best Used For:</strong> Solidifying plot structure, creating key milestones for outlining, story bible plot section. Requires a proposed outline.</p>
                                     </div>
                                  </div>
                                  <div class="prompt-item" id="D2-S4.25">
                                     <strong>25. Act as an Outline Strategist:</strong>
                                     <p>Take these key story beats (from D2-S4.24) and expand them into a detailed chapter-by-chapter outline (bullet points per chapter) for the story bible, assigning key character moments and world reveals to specific chapters.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Translates high-level story beats into a more granular chapter breakdown, integrating character/world elements.</p>
                                         <p><strong>Best Used For:</strong> Creating detailed outlines before drafting, planning chapter content, story bible chapter summaries. Requires defined story beats.</p>
                                     </div>
                                  </div>
                                  <div class="prompt-item" id="D2-S4.26">
                                     <strong>26. Act as a Plot Hole Detector:</strong>
                                     <p>Analyze the current plot outline [Outline Text/Reference] in the Story Bible. Identify 2 potential plot holes or logical gaps related to established character abilities (Stage 3), world rules (G1), or setting constraints (Stage 2).</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Specifically targets logical inconsistencies or unresolved questions within a plot structure using broader Bible context.</p>
                                         <p><strong>Best Used For:</strong> Pre-drafting plot refinement, strengthening narrative logic, fixing story problems based on world consistency.</p>
                                     </div>
                                  </div>
                                  <div class="prompt-item" id="D2-S4.27">
                                     <strong>27. Act as a Pacing Variation Planner:</strong>
                                     <p>Review the chapter outline (D2-S4.25). Suggest specific chapters or sequences where the pacing should deliberately slow down (for character development, worldbuilding) or speed up (for action, suspense), justifying based on narrative goals.</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Analyzes an outline to plan the rhythm and speed of the narrative across different sections.</p>
                                         <p><strong>Best Used For:</strong> Ensuring dynamic pacing, avoiding monotony, planning for tension and release. Requires a chapter outline.</p>
                                     </div>
                                  </div>
                                  <div class="prompt-item" id="D2-S4.28">
                                     <strong>28. Act as a Conflict Resolution Brainstormer:</strong>
                                     <p>The central conflict is [Conflict Description from D2-S4.7]. Brainstorm 3 different potential resolutions (ranging from triumphant to tragic/ambiguous) and discuss how each resolution impacts the main theme (Stage 1) and key character arcs (Stage 3).</p>
                                      <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Explores multiple possible endings for the main conflict, considering their thematic and character arc impact using Bible context.</p>
                                         <p><strong>Best Used For:</strong> Planning the story's conclusion, exploring thematic possibilities, choosing the most resonant ending.</p>
                                     </div>
                                  </div>
                                  <div class="prompt-item" id="D2-S4.29">
                                     <strong>29. Act as a Subplot Thematic Linker:</strong>
                                     <p>Ensure the subplot involving [Subplot Details from D2-S4.8] thematically resonates with or contrasts against the main plot's themes (Stage 1). Suggest specific scenes or interactions in the outline where this connection can be strengthened.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Analyzes the connection between main plots and subplots, focusing on thematic coherence and suggesting concrete integration points.</p>
                                         <p><strong>Best Used For:</strong> Ensuring subplots add depth rather than distract, strengthening thematic resonance, refining plot structure.</p>
                                     </div>
                                  </div>
                                  <div class="prompt-item" id="D2-S4.30">
                                     <strong>30. Act as a Scene Objective Clarifier:</strong>
                                     <p>For this planned scene [Scene Summary from Outline], define the primary plot objective (what needs to happen for plot progression) AND the primary character objective (what the POV character wants *in this scene* based on Stage 3). Add to Story Bible scene notes.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Focuses scene planning on clear goals, both for plot progression and immediate character desire, using Bible context.</p>
                                         <p><strong>Best Used For:</strong> Ensuring scenes have purpose, driving plot and character forward, detailed scene outlining. Requires a scene summary.</p>
                                     </div>
                                  </div>
                                   <div class="prompt-item" id="D2-S4.31">
                                     <strong>31. Act as a Foreshadowing Placement Strategist:</strong>
                                     <p>Identify a key reveal planned for late in the story outline. Suggest 3 subtle ways to foreshadow it much earlier in the outline (specific scenes or details), using elements from worldbuilding (Stage 2) or character backstory (Stage 3).</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Helps plan the placement of early hints for later payoffs using established Bible context, improving narrative cohesion.</p>
                                         <p><strong>Best Used For:</strong> Setting up plot twists effectively, creating satisfying reveals, outlining narrative threads. Requires knowing the reveal and having an outline.</p>
                                     </div>
                                  </div>
                                   <div class="prompt-item" id="D2-S4.32">
                                     <strong>32. Act as a 'Chekhov's Gun' Tracker:</strong>
                                     <p>Review the Story Bible outline and notes from Stages 1-4. Are there any elements introduced (objects, skills, minor characters, locations) that are currently unused in the latter half of the plot? Suggest ways to integrate them meaningfully later or recommend removing them.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Ensures narrative elements introduced early serve a purpose later, avoiding loose ends based on the current plan.</p>
                                         <p><strong>Best Used For:</strong> Tightening plot structure, ensuring narrative efficiency, editing outlines/drafts for relevance.</p>
                                     </div>
                                  </div>
                                   <div class="prompt-item" id="D2-S4.33">
                                     <strong>33. Act as a Climax Intensity Modulator:</strong>
                                     <p>Read the outline for the climax (D2-S4.11). Suggest specific ways to increase the emotional stakes (leveraging character relationships from Stage 3) and visceral intensity (using setting details from Stage 2) for the protagonist.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Focuses on amplifying the impact of the story's peak confrontation by integrating established character and setting elements.</p>
                                         <p><strong>Best Used For:</strong> Refining the climax, maximizing emotional payoff, ensuring high stakes using Bible context.</p>
                                     </div>
                                  </div>
                                   <div class="prompt-item" id="D2-S4.34">
                                     <strong>34. Act as an Epilogue Purpose Definer:</strong>
                                     <p>Discuss the potential purpose of an epilogue for this story (e.g., show long-term consequences based on world/character changes, resolve minor subplots, set up sequel bait related to G4/F1 implications). Draft a brief conceptual outline for the epilogue based on the chosen purpose.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Helps decide if an epilogue is needed and what its narrative function should be, potentially drawing on wider Bible context.</p>
                                         <p><strong>Best Used For:</strong> Planning the story's final section, deciding on sequel hooks, providing closure.</p>
                                     </div>
                                  </div>
                                    <div class="prompt-item" id="D2-S4.35">
                                     <strong>35. Act as a Chapter Hook Analyst:</strong>
                                     <p>Review the planned ending for [Chapter Number] and the opening for [Next Chapter Number] in the outline (D2-S4.25). Does the ending create a compelling hook or question related to the ongoing plot/character arcs that pulls the reader into the next chapter? Suggest improvements.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Focuses on the transitions between chapters to maintain reader momentum and interest based on the detailed outline.</p>
                                         <p><strong>Best Used For:</strong> Improving chapter structure, enhancing page-turning quality, editing outlines for flow.</p>
                                     </div>
                                    </div>
                                    <div class="prompt-item" id="D2-S4.36">
                                     <strong>36. Act as a "What If" Scenario Explorer (Plot Focus):</strong>
                                     <p>Propose 3 significant "what if" changes to the plot outline (e.g., What if the inciting incident was different? What if the midpoint reveal failed? What if a key ally betrayed the protagonist earlier?). Briefly explore the potential ripple effects on the overall structure and character arcs.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Explores alternative plot directions to test the current structure or generate new ideas, considering impact on Bible elements.</p>
                                         <p><strong>Best Used For:</strong> Stress-testing plot logic, brainstorming alternative narratives, overcoming plot blocks.</p>
                                     </div>
                                  </div>
                              </div>
                         </details> <!-- End Stage 4 -->

                         <!-- Stage 5: Drafting, Prose & Style -->
                         <details id="D2-S5">
                             <summary>Stage 5: Drafting, Prose & Style</summary>
                              <div>
                                   <!-- SECTION SYSTEM PROMPT START - SECTION_ID: D2-S5 -->
                                   <div class="system-prompt-block">
                                      <h4>System Instruction</h4>
                                      <p><strong>Context:</strong> Book Writing - Stage 5: Drafting, Prose & Style</p>
                                      <p>Adopt the persona of a <strong>Writing Craft Advisor and Prose Stylist</strong>. Focus on the micro-level of writing—word choice, sentence structure, descriptive techniques (show-don't-tell, sensory details), voice, tone, pacing within scenes, and figurative language—to enhance clarity, impact, and aesthetic quality based on previous stages.</p>
                                       <p><strong>Internal Steps (Consider these when responding):</strong></p>
                                       <ul>
                                           <li>Analyze provided draft text or generate text demonstrating specific craft techniques.</li>
                                           <li>Offer advice on developing a prose style consistent with genre/tone (Stage 0).</li>
                                           <li>Guide the use of point of view (POV) effectively.</li>
                                           <li>Help craft compelling sentences with varied structure and rhythm.</li>
                                           <li>Refine word choice for precision and impact (semantics).</li>
                                           <li>Incorporate sensory details and figurative language based on world/character context.</li>
                                           <li>Advise on maintaining consistent voice and tone.</li>
                                           <li>Provide actionable feedback for polishing prose.</li>
                                       </ul>
                                      <p>Aim to help the user translate the outlined story (Stage 4) into engaging, well-written prose that reflects the established world, characters, and intended style.</p>
                                  </div>
                                   <!-- SECTION SYSTEM PROMPT END - SECTION_ID: D2-S5 -->
                                   <div class="prompt-item" id="D2-S5.1"><strong>1. Act as a Prose Style Expert:</strong> <p>Advise on developing a distinctive and effective prose style that suits the genre and tone established in Stage 0 for this novel.</p></div>
                                   <div class="prompt-item" id="D2-S5.2"><strong>2. Act as a Descriptive Writing Expert:</strong> <p>Help draft vivid and immersive descriptions for a scene involving [Setting from Stage 2] and [Character from Stage 3], using sensory details and figurative language appropriate to the context.</p></div>
                                   <div class="prompt-item" id="D2-S5.3"><strong>3. Act as a Pacing Expert (Scene Level):</strong> <p>Analyze this drafted scene [Text Excerpt] for pacing. Suggest specific sentence-level or paragraph-level adjustments (e.g., shorter sentences for action, longer for reflection) to create the intended tension/mood based on its function in the outline (Stage 4).</p></div>
                                   <div class="prompt-item" id="D2-S5.4"><strong>4. Act as a Point of View Expert:</strong> <p>Discuss the pros and cons of using [Chosen POV, e.g., First Person, Third Limited] for this specific story and protagonist (Stage 3). Provide examples of how to maintain POV consistency and leverage its strengths in a draft scene.</p></div>
                                   <div class="prompt-item" id="D2-S5.5"><strong>5. Act as a Syntax Expert:</strong> <p>Review this paragraph [Text Excerpt]. Analyze its sentence structure. Suggest revisions to improve clarity, rhythm, and impact by varying sentence length and construction.</p></div>
                                   <div class="prompt-item" id="D2-S5.6"><strong>6. Act as a Semantics Expert:</strong> <p>Analyze the word choice in this passage [Text Excerpt]. Suggest 5-10 stronger verbs or more precise nouns/adjectives to enhance meaning and better reflect the established tone/character voice.</p></div>
                                   <div class="prompt-item" id="D2-S5.7"><strong>7. Act as a Sentence Expert:</strong> <p>Take this basic sentence expressing [Idea from Outline]: "[Simple Sentence]". Rewrite it in 3 different ways, varying sentence structure and complexity to demonstrate stylistic options.</p></div>
                                   <div class="prompt-item" id="D2-S5.8"><strong>8. Act as a Prose Expert:</strong> <p>Provide feedback on the overall prose quality of this drafted chapter [Chapter Text]. Comment on clarity, flow, engagement, and consistency with the intended style. Offer 2-3 high-level suggestions for improvement.</p></div>
                                   <div class="prompt-item" id="D2-S5.9"><strong>9. Act as a Authorial Voice Developer:</strong> <p>Help refine the authorial/narrative voice in this passage [Text Excerpt] to be more distinctive and consistent with the established genre/tone.</p></div>
                                   <div class="prompt-item" id="D2-S5.10"><strong>10. Act as a Mood and Tone Expert (Scene Level):</strong> <p>Analyze this scene draft [Text Excerpt]. Does the prose effectively establish the intended mood [Target Mood]? Suggest specific word choices or imagery adjustments to strengthen the mood.</p></div>
                                   <div class="prompt-item" id="D2-S5.11"><strong>11. Act as a Voice Expert (Character Dialogue):</strong> <p>Draft a short dialogue exchange between [Character A] and [Character B] (from Stage 3) discussing [Topic], ensuring their individual voices (vocabulary, speech patterns defined in Stage 3) are distinct and clear.</p></div>
                                   <div class="prompt-item" id="D2-S5.12"><strong>12. (WG V-41) Prose Style Rewrite:</strong> <p>"Rewrite this passage [text excerpt] in a more [style, e.g., evocative, concise, lyrical] style, focusing on improving the prose quality while staying true to the scene's purpose in the outline."</p></div>
                                   <div class="prompt-item" id="D2-S5.13"><strong>13. (WG V-42) Sentence Effectiveness Analysis:</strong> <p>"Analyze these sentences [text excerpt] for clarity, conciseness, and impact within the context of the scene. Suggest revisions to improve their effectiveness."</p></div>
                                   <div class="prompt-item" id="D2-S5.14"><strong>14. (WG V-43) Word Choice Precision Check:</strong> <p>"Check this passage [text excerpt] for precise word choice and semantic accuracy related to the worldbuilding/character actions. Suggest alternative words or phrases to enhance meaning or consistency."</p></div>
                                   <div class="prompt-item" id="D2-S5.15"><strong>15. (WG V-44) Tone and Voice Consistency Check:</strong> <p>"Analyze the tone and voice of this passage [text excerpt] and ensure it is consistent with the overall narrative style and POV character established earlier."</p></div>
                                   <div class="prompt-item" id="D2-S5.16"><strong>16. (WG V-45) Show, Don't Tell Implementation:</strong> <p>"Identify 2-3 instances of 'telling' in this passage [text excerpt] and rewrite them using the 'show, don't tell' technique to create a more immersive experience, using details from Stage 2/3 for showing."</p></div>
                                   <div class="prompt-item" id="D2-S5.17"><strong>17. (WG V-46) Figurative Language Integration:</strong> <p>"Incorporate 2-3 appropriate examples of figurative language (metaphors, similes, personification relevant to world/character) to enhance the descriptive quality of this passage [text excerpt]."</p></div>
                                   <div class="prompt-item" id="D2-S5.18"><strong>18. (WG V-47) Sensory Detail Enhancement:</strong> <p>"Add specific sensory details (appealing to at least 3 senses) to this scene [text excerpt] to create a more vivid and immersive experience, drawing from the established setting (Stage 2)."</p></div>
                                   <div class="prompt-item" id="D2-S5.19"><strong>19. (WG V-48) Pacing and Rhythm Analysis (Passage):</strong> <p>"Analyze the pacing and rhythm of this passage [text excerpt] based on sentence length and structure. Suggest ways to vary it to improve flow and impact according to the scene's goal."</p></div>
                                   <div class="prompt-item" id="D2-S5.20"><strong>20. (WG V-49) Style Consistency Check (Chapter):</strong> <p>"Ensure that the writing style is consistent throughout this drafted chapter [Chapter Text] and aligns with the overall tone and POV established for the novel."</p></div>
                                   <div class="prompt-item" id="D2-S5.21"><strong>21. (WG V-50) Narrative Perspective Shift (Drafting):</strong> <p>"Rewrite this drafted scene [text excerpt] from a different narrative perspective that might be suitable (e.g., switch from third-limited to first person, or vice versa) and discuss the potential impact on the scene's feel."</p></div>
                                   <div class="prompt-item" id="D2-S5.22"><strong>22. (WG VII-61) Subtext Enhancement (Dialogue):</strong> <p>"Analyze this dialogue [text excerpt]. Is the subtext clear? Suggest ways to enhance the hidden meanings or character intentions beneath the surface words, consistent with character goals (Stage 3)."</p></div>
                                   <div class="prompt-item" id="D2-S5.23"><strong>23. (WG VII-66) Emotional Impact Amplification:</strong> <p>"Enhance the emotional impact of this scene [text excerpt] by focusing more deeply on the POV character's internal feelings, physical reactions, and specific word choices reflecting their state (based on Stage 3 profile)."</p></div>
                                   <div class="prompt-item" id="D2-S5.24"><strong>24. (WG VII-67) Narrative Tension Builder (Prose):</strong> <p>"Build narrative tension within this drafted scene [text excerpt] using prose techniques like shorter sentences, focusing on specific unsettling details (from Stage 2/F1), withholding information, or using foreshadowing language."</p></div>
                                   <div class="prompt-item" id="D2-S5.25"><strong>25. (WG VII-68) Worldbuilding Integration (Prose):</strong> <p>"Review this passage [text excerpt]. Find 2-3 opportunities to seamlessly integrate specific worldbuilding details (from Stage 2/G) into the narrative description or character thoughts, making the world feel more organic."</p></div>
                                   <div class="prompt-item" id="D2-S5.26"><strong>26. (WG VII-71) Style Experimentation (Micro):</strong> <p>"Take this sentence: '[Sentence from draft]'. Rewrite it in 3 distinct styles (e.g., minimalist, poetic, action-oriented) to experiment with finding the most effective voice for this moment."</p></div>
                                   <div class="prompt-item" id="D2-S5.27"><strong>27. (WG VII-73) Atmosphere Creation (Prose):</strong> <p>"Craft/rewrite a paragraph describing [Setting from Stage 2] focusing purely on using word choice, imagery, and sentence rhythm to establish a specific atmosphere ([Target Mood])."</p></div>
                                   <div class="prompt-item" id="D2-S5.28"><strong>28. (WG VII-74) Moral Ambiguity (Dialogue/Action):</strong> <p>"Draft a short interaction or action beat for [Character] in this scene [Scene Context] that highlights their moral ambiguity, making their 'good' or 'evil' alignment less clear based on their established complexities (Stage 3)."</p></div>
                                   <div class="prompt-item" id="D2-S5.29"><strong>29. (WG VII-75) Reader Engagement (Hooking):</strong> <p>"Analyze the opening paragraph of this chapter draft [Text Excerpt]. Does it effectively hook the reader? Suggest revisions to the opening sentence or initial description to increase intrigue or immediacy."</p></div>
                                   <div class="prompt-item" id="D2-S5.30"><strong>30. (WG VII-76) Pacing Variation (Scene):</strong> <p>"Review the internal pacing of this scene draft [Text Excerpt]. Are there moments that could be slowed down for emotional emphasis or sped up for excitement? Suggest specific paragraph/sentence level adjustments."</p></div>
                                   <div class="prompt-item" id="D2-S5.31"><strong>31. (WG VII-80) Voice Development (Narrative):</strong> <p>"Help refine the narrative voice in this passage [Text Excerpt]. Is it consistent? Does it match the intended tone/POV? Suggest specific changes to strengthen the voice."</p></div>
                                   <div class="prompt-item" id="D2-S5.32"><strong>32. (WG Addon 17) Role: Drafting Expert:</strong> <p>Provide general advice and encouragement on the process of writing the first draft, focusing on overcoming writer's block, maintaining momentum, and silencing the inner editor based on the plan from Stage 0.</p></div>
                                  <div class="prompt-item" id="D2-S5.33"><strong>33. (WG Addon 21) Role: Dialogue Crafter:</strong> <p>Compose a dialogue-heavy scene between [Character A] and [Character B] where they are in conflict over [Issue related to plot]. Focus on using dialogue to reveal personality (Stage 3), advance the plot (Stage 4), and create tension.</p></div>
                                   <div class="prompt-item" id="D2-S5.34"><strong>34. (WG Addon 22) Role: Prose Stylist:</strong> <p>Rewrite a key descriptive paragraph [Text Excerpt] in three different literary styles (e.g., minimalist, ornate, lyrical) to explore the impact on the scene's mood and reader experience.</p></div>
                                   <div class="prompt-item" id="D2-S5.35"><strong>35. (WG Addon 25) Role: Tone Master:</strong> <p>Take a neutral scene description [Text Excerpt] and rewrite it in three different tones (e.g., humorous, suspenseful, melancholic) by changing word choice, imagery, and sentence structure.</p></div>
                                   <div class="prompt-item" id="D2-S5.36"><strong>36. (WG Addon 28) Role: Point-of-View Selector (Practice):</strong> <p>Write a short passage describing [Event from Outline] first from [Character A]'s third-person limited POV, then from an omniscient POV, highlighting the difference in information revealed.</p></div>
                                   <div class="prompt-item" id="D2-S5.37"><strong>37. (WG Addon 29) Role: Show-Don't-Tell Pro:</strong> <p>Take this sentence expressing an emotion/trait: "[Telling Sentence, e.g., 'He was angry']". Rewrite it using descriptive action, dialogue, or internal thought consistent with [Character]'s profile to *show* the emotion/trait instead.</p></div>
                                   <div class="prompt-item" id="D2-S5.38"><strong>38. (WG Addon 30) Role: Conflict Creator (Scene Level):</strong> <p>Inject more conflict into this drafted scene [Text Excerpt]. Add a small obstacle, misunderstanding, or internal struggle for the POV character based on established flaws/goals.</p></div>
                                   <div class="prompt-item" id="D2-S5.39"><strong>39. (WG Addon 31) Role: Suspense Builder (Prose):</strong> <p>Rewrite this paragraph [Text Excerpt] to build more suspense, using techniques like foreshadowing, focusing on unsettling sensory details, asking rhetorical questions, or using sentence fragments.</p></div>
                                  <div class="prompt-item" id="D2-S5.40"><strong>40. (WG Addon 35) Role: Irony Implementer:</strong> <p>Suggest a way to incorporate dramatic, situational, or verbal irony into this scene [Scene Summary/Excerpt] to enhance theme or characterization.</p></div>
                                   <div class="prompt-item" id="D2-S5.41"><strong>41. (WG Addon 36) Role: Satire Writer (Practice):</strong> <p>Write a short satirical paragraph describing [Mundane Situation related to world] using exaggeration or irony to critique a societal aspect established in Stage 2/F2.</p></div>
                                  <div class="prompt-item" id="D2-S5.42"><strong>42. (WG Addon 45) Role: Humor Expert (Practice):</strong> <p>Inject humor (e.g., witty dialogue, situational irony, humorous description) into this otherwise serious scene draft [Text Excerpt], ensuring it fits the character's voice.</p></div>
                                   <div class="prompt-item" id="D2-S5.43"><strong>43. (WG Addon 46) Role: Satire Expert:</strong> <p>Advise on how to use satire effectively within the context of [Genre/Story Concept] to critique [Target Subject] without undermining the core narrative.</p></div>
                                  <div class="prompt-item" id="D2-S5.44"><strong>44. Act as a Prose Polisher:</strong> <p>Rewrite this paragraph [Paragraph Text] to enhance its flow, imagery, and impact, focusing on strong verbs and varied sentence structure. Replace the bible's draft text.</p></div>
                                  <div class="prompt-item" id="D2-S5.45"><strong>45. Act as a Syntax Harmonizer:</strong> <p>Review this passage [Passage Text] for sentence structure variety and rhythm. Suggest revisions to avoid monotony or improve clarity.</p></div>
                                  <div class="prompt-item" id="D2-S5.46"><strong>46. Act as a Semantics Precision Expert:</strong> <p>Check this description [Text] for precise and evocative word choice. Suggest stronger verbs, more specific nouns, and impactful adjectives. Update the description in the story bible.</p></div>
                                   <div class="prompt-item" id="D2-S5.47"><strong>47. Act as a "Show, Don't Tell" Coach:</strong> <p>Identify instances of "telling" in this excerpt [Text] and rewrite them to "show" the emotion, character trait, or plot point through action, dialogue, or sensory detail.</p></div>
                                   <div class="prompt-item" id="D2-S5.48"><strong>48. Act as a Figurative Language Enhancer:</strong> <p>Suggest 3 potential metaphors or similes to enrich the description of [Concept or Object from Story Bible] in the draft.</p></div>
                                   <div class="prompt-item" id="D2-S5.49"><strong>49. Act as a Dialogue Subtext Layerer:</strong> <p>Take this straightforward dialogue exchange [Dialogue Text]. Rewrite it to include subtext, where characters imply meanings different from their literal words, revealing hidden tensions or desires based on Stage 3 profiles.</p></div>
                                   <div class="prompt-item" id="D2-S5.50"><strong>50. Act as a Sensory Detail Injector:</strong> <p>Enhance this setting description in the draft [Text] by adding specific details appealing to at least three different senses (sound, smell, touch, taste), drawing from Stage 2 notes.</p></div>
                                   <div class="prompt-item" id="D2-S5.51"><strong>51. Act as a Pre-Writing Ritual Designer:</strong> <p>Suggest 3 potential pre-writing rituals or warm-up exercises an author could use to get into the creative mindset before starting a drafting session for this specific project.</p></div>
                                   <div class="prompt-item" id="D2-S5.52"><strong>52. Act as a Soundtrack Conceptualizer:</strong> <p>Based on the novel's tone, themes, and key scenes outlined in the Story Bible, suggest 3 musical genres or specific artists whose work could serve as an inspirational soundtrack for the author during drafting.</p></div>
                                   <div class="prompt-item" id="D2-S5.53"><strong>53. Act as a Time Management Coach (Author - Drafting Focus):</strong> <p>Suggest 3 time management techniques (e.g., Pomodoro, time blocking, word count sprints) specifically tailored for maintaining momentum during the first draft phase, referencing goals from Stage 0.</p></div>
                              </div>
                         </details> <!-- End Stage 5 -->

                         <!-- Stage 6: Revision, Editing & Feedback -->
                         <details id="D2-S6">
                             <summary>Stage 6: Revision, Editing & Feedback</summary>
                              <div>
                                   <!-- SECTION SYSTEM PROMPT START - SECTION_ID: D2-S6 -->
                                   <div class="system-prompt-block">
                                      <h4>System Instruction</h4>
                                      <p><strong>Context:</strong> Book Writing - Stage 6: Revision, Editing & Feedback</p>
                                     <p>Adopt the persona of a <strong>Constructive Editor and Manuscript Analyst</strong>. Focus on identifying weaknesses and providing clear, actionable steps for improvement at various editorial levels (developmental, line, copy, proof) using the completed draft and Story Bible for context.</p>
                                      <p><strong>Internal Steps (Consider these when responding):</strong></p>
                                       <ul>
                                           <li>Determine the level of edit required based on user request/draft stage.</li>
                                           <li>Analyze draft against Story Bible for consistency (plot, character, world rules).</li>
                                           <li>Provide developmental feedback on structure, pacing, arcs, themes.</li>
                                           <li>Perform line edits focusing on clarity, flow, prose style, voice.</li>
                                           <li>Conduct copyedits correcting grammar, punctuation, spelling, usage.</li>
                                           <li>Proofread for final typos and formatting errors.</li>
                                           <li>Help interpret and prioritize feedback from beta readers or critique partners.</li>
                                           <li>Maintain a constructive and helpful tone.</li>
                                       </ul>
                                      <p>Aim to help the author systematically improve the manuscript's quality, coherence, and polish, preparing it for the final stages.</p>
                                  </div>
                                   <!-- SECTION SYSTEM PROMPT END - SECTION_ID: D2-S6 -->
                                   <div class="prompt-item" id="D2-S6.1"><strong>1. Act as a Revision Expert:</strong> <p>Guide the process of revising the completed first draft, focusing globally on strengthening plot structure (vs. Stage 4 outline), character arcs (vs. Stage 3 plan), pacing across the manuscript, and thematic resonance.</p></div>
                                   <div class="prompt-item" id="D2-S6.2"><strong>2. Act as a Editing Expert (Line Edit):</strong> <p>Provide detailed line-level feedback on a chapter draft [Chapter Text], focusing on improving sentence flow, clarity, word choice, and consistency of voice/tone.</p></div>
                                   <div class="prompt-item" id="D2-S6.3"><strong>3. Act as a Proofreading Expert:</strong> <p>Perform a final proofread of this polished chapter/manuscript excerpt [Text Excerpt], checking meticulously for errors in spelling, grammar, punctuation, formatting, and easily missed typos (like repeated words).</p></div>
                                   <div class="prompt-item" id="D2-S6.4"><strong>4. (WG VI-51) Clarity Check (Draft):</strong> <p>"Review this drafted passage [text excerpt] for clarity. Are there any ambiguous sentences or confusing descriptions? Suggest specific rewrites for better understanding."</p></div>
                                   <div class="prompt-item" id="D2-S6.5"><strong>5. (WG VI-52) Conciseness Edit (Draft):</strong> <p>"Edit this drafted passage [text excerpt] for conciseness. Identify and remove unnecessary words, repetitive phrases, or redundant sentences without losing essential meaning."</p></div>
                                   <div class="prompt-item" id="D2-S6.6"><strong>6. (WG VI-53) Flow Improvement (Draft):</strong> <p>"Analyze the flow between paragraphs and sentences in this passage [text excerpt]. Suggest improvements using transition words/phrases or sentence restructuring for a smoother read."</p></div>
                                   <div class="prompt-item" id="D2-S6.7"><strong>7. (WG VI-54) Grammar and Punctuation Check (Copyedit):</strong> <p>"Perform a copyedit on this passage [text excerpt], correcting errors in grammar (tense, agreement, etc.), punctuation (commas, semicolons, etc.), and spelling."</p></div>
                                   <div class="prompt-item" id="D2-S6.8"><strong>8. (WG VI-55) Consistency Check (Manuscript):</strong> <p>"Check this chapter draft [Chapter Text] for consistency against the Story Bible regarding character details (eye color, established traits), setting descriptions (layout, key features), plot timeline, and world rules (magic system G1)."</p></div>
                                   <div class="prompt-container" id="D2-S6.9"><strong>9. (WG VI-56) Readability Optimization (Draft):</strong> <p>"Analyze this passage [text excerpt] for readability. Suggest changes to sentence length variation, paragraph structure, and vocabulary choices to make it more engaging and easier to read for the target audience (Stage 0)."</p></div>
                                   <div class="prompt-item" id="D2-S6.10"><strong>10. (WG VI-57) Voice and Tone Consistency Check (Manuscript):</strong> <p>"Review this chapter [Chapter Text] to ensure the narrative voice and tone are consistent with the style established in Stage 5 and appropriate for the genre/overall mood."</p></div>
                                   <div class="prompt-item" id="D2-S6.11"><strong>11. (WG VI-58) Fact-Checking (Draft):</strong> <p>"Identify any factual claims (historical, scientific) in this passage [text excerpt]. Verify their accuracy using external knowledge or prompt the user for sources if verification is needed."</p></div>
                                   <div class="prompt-item" id="D2-S6.12"><strong>12. (WG VI-59) Feedback Incorporation Strategist:</strong> <p>"Review this feedback from a beta reader/critique partner: [Feedback Summary/Text]. Help prioritize the feedback points (most critical vs. minor/subjective) and brainstorm specific revision actions to address the key issues."</p></div>
                                   <div class="prompt-item" id="D2-S6.13"><strong>13. (WG VI-60) Polish and Refine (Final Pass):</strong> <p>"Perform a final 'polishing' read-through of this chapter excerpt [Text Excerpt], focusing on catching any remaining awkward phrasing, minor inconsistencies, or areas where the prose could be slightly elevated for maximum impact."</p></div>
                                   <div class="prompt-item" id="D2-S6.14"><strong>14. (WG Addon 51) Role: Editor (Clarity/Conciseness):</strong> <p>Improve this text [Text Excerpt] specifically for clarity and conciseness, acting as a line editor.</p></div>
                                   <div class="prompt-item" id="D2-S6.15"><strong>15. (WG Addon 52) Role: Reviewer (Style/Tone):</strong> <p>Review this text [Text Excerpt] focusing on its effectiveness regarding tone and style consistency with the project's goals.</p></div>
                                   <div class="prompt-item" id="D2-S6.16"><strong>16. (WG Addon 53) Role: Proofreader:</strong> <p>Proofread this text [Text Excerpt] specifically for grammar, spelling, and punctuation errors.</p></div>
                                   <div class="prompt-item" id="D2-S6.17"><strong>17. (WG Addon 54) Role: Beta Reader (Simulated):</strong> <p>Read this chapter draft [Chapter Text] and provide feedback from a reader's perspective, focusing on plot engagement, character believability, pacing, and overall enjoyment. What questions or confusions did you have?</p></div>
                                   <div class="prompt-item" id="D2-S6.18"><strong>18. (WG Addon 72) Role: Writing Therapist (Revision Context):</strong> <p>User is feeling overwhelmed by revisions. Offer encouragement and suggest breaking down the revision process into smaller, manageable steps (referencing D2-S6.20). Help reframe critique constructively.</p></div>
                                   <div class="prompt-item" id="D2-S6.19"><strong>19. (WG Addon 78) Role: Writing Ethicist (Citation/Accuracy):</strong> <p>If the manuscript incorporates significant real-world research or events, discuss the ethical importance of accuracy and avoiding misrepresentation, even in fiction. Advise on when explicit source notes might be appropriate (e.g., in an author's note).</p></div>
                                   <div class="prompt-item" id="D2-S6.20"><strong>20. Act as a Revision Pass Planner:</strong> <p>Create a checklist for 3 distinct revision passes for the completed manuscript: 1) Big Picture (Plot, Structure, Arcs based on Stage 4), 2) Character & Consistency (vs. Stage 3 & Bible), 3) Line Edit (Prose, Flow, Clarity based on Stage 5). Detail key items to check in each pass.</p></div>
                                  <div class="prompt-item" id="D2-S6.21"><strong>21. Act as an Overused Word Finder:</strong> <p>Scan this chapter draft [Chapter Text] for potentially overused "crutch" words or phrases (e.g., 'just', 'really', 'suddenly', specific character tics). List them and suggest stronger alternatives or ways to rephrase.</p></div>
                                  <div class="prompt-item" id="D2-S6.22"><strong>22. Act as a Passive Voice Eliminator:</strong> <p>Identify instances of passive voice in this passage [Text] and rewrite them into active voice where appropriate for stronger, more direct prose.</p></div>
                                  <div class="prompt-item" id="D2-S6.23"><strong>23. Act as a Read-Aloud Flow Checker (Simulated):</strong> <p>(Simulated) Read this paragraph [Text] aloud. Identify awkward phrasing, clunky sentences, or sections that disrupt the natural rhythm. Suggest specific revisions for smoother flow.</p></div>
                                  <div class="prompt-item" id="D2-S6.24"><strong>24. Act as a Beta Reader Question Composer:</strong> <p>Generate 10 specific, open-ended questions to ask beta readers focusing on plot clarity (vs Stage 4), character believability (vs Stage 3), pacing, world consistency (vs Stage 2), and emotional impact, based on the Story Bible's goals.</p></div>
                                   <div class="prompt-item" id="D2-S6.25"><strong>25. Act as a Feedback Integration Strategist:</strong> <p>Review this summarized beta reader feedback [Feedback Summary]. Categorize the feedback (e.g., Plot, Character, Pacing, Style). Prioritize the top 3-5 most critical or frequently mentioned issues to address in the next revision round and outline a potential plan for tackling them.</p></div>
                                   <div class="prompt-item" id="D2-S6.26"><strong>26. Act as an Editing Guide (Line Edit Example):</strong> <p>Perform a detailed line edit on this paragraph [Paragraph Text], correcting grammar, punctuation, spelling, awkward phrasing, and weak word choices. Briefly explain the reasoning for 2-3 key changes.</p></div>
                                   <div class="prompt-item" id="D2-S6.27"><strong>27. Act as a Proofreading Double-Checker (Targeted):</strong> <p>Scan this finalized chapter [Chapter Text] specifically for common easily missed errors: incorrect homophones (their/there/they're), misplaced apostrophes, repeated small words (the the), inconsistent capitalization of proper nouns (referencing Bible).</p></div>
                                   <div class="prompt-item" id="D2-S6.28"><strong>28. Act as a Consistency Auditor (Bible Cross-Check):</strong> <p>Review the character description for [Character A] in Chapter [X] against their profile in Stage 3 and their actions in the Stage 4 outline. Flag any inconsistencies in stated traits, motivations, or abilities.</p></div>
                                   <div class="prompt-item" id="D2-S6.29"><strong>29. Act as a Sensitivity Reader Consultant (Simulated - Issue Spotting):</strong> <p>Review this drafted scene [Scene Text] depicting [Specific Group/Topic]. Identify potential areas (dialogue, descriptions, actions) that might inadvertently perpetuate stereotypes or inaccuracies, suggesting areas that might benefit from review by a human sensitivity reader.</p></div>
                                   <div class="prompt-item" id="D2-S6.30"><strong>30. Act as a Continuity Supervisor (Timeline Check):</strong> <p>Cross-reference the sequence of events between Chapter [X] and Chapter [Y] against the timeline established in the Story Bible (e.g., from Stage 2 history or Stage 4 outline). Flag any potential chronological inconsistencies or contradictions.</p></div>
                              </div>
                         </details> <!-- End Stage 6 -->

                         <!-- Insert REDESIGNED D2-S7 here -->
                         <details id="D2-S7">
                             <summary>Stage 7: Publishing Pathways & Preparation</summary>
                             <div>
                                 <!-- SECTION SYSTEM PROMPT START - SECTION_ID: D2-S7 -->
                                 <div class="system-prompt-block">
                                     <h4>System Instruction</h4>
                                     <p><strong>Context:</strong> Book Writing - Stage 7: Publishing Pathways & Preparation</p>
                                     <p>Adopt the persona of a <strong>Publishing Navigator and Author Marketing Consultant</strong>. Focus on guiding the author through the final steps towards either traditional or self-publishing, including preparing submission materials, understanding platform requirements, and developing initial marketing concepts based on the completed manuscript and Story Bible.</p>
                                     <p><strong>Internal Steps (Consider these when responding):</strong></p>
                                     <ul>
                                         <li>Identify the specific task related to publishing preparation (query, synopsis, blurb, keywords, platform building, marketing angles, formatting concepts, etc.).</li>
                                         <li>Leverage the Story Bible context (logline, genre, themes, target audience profile from Stage 0, manuscript details) **OR equivalent detailed information provided by the user** to tailor materials.</li>
                                         <li>Apply industry standards and best practices for the chosen publishing path (traditional vs. self-publishing).</li>
                                         <li>Generate professional, compelling, and targeted materials suitable for agents, publishers, or readers/retail platforms.</li>
                                         <li>Provide actionable advice on building an author platform and basic marketing strategies.</li>
                                         <li>Clearly differentiate advice/materials relevant to traditional vs. self-publishing routes where applicable.</li>
                                     </ul>
                                     <p>Focus on creating polished, market-aware materials and providing practical guidance to bridge the gap between manuscript completion and reaching readers, accommodating both traditional and indie pathways.</p>
                                 </div>
                                 <!-- SECTION SYSTEM PROMPT END - SECTION_ID: D2-S7 -->

                                 <div class="prompt-container" id="D2-S7.1">
                                     <p>1. Act as a Query Letter Architect (Traditional): Based on the final logline, synopsis outline, genre, word count, and comp titles (ideally from Stage 0/Bible Meta) **OR equivalent detailed information provided now**, draft a compelling, professional query letter targeting literary agents representing [Genre]. Include hook, concise pitch, author bio relevance, and adherence to standard format.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Generates a complete draft query letter adhering to industry standards for traditional publishing submissions.</p>
                                         <p><strong>Best Used For:</strong> Preparing submission materials for literary agents.</p>
                                         <p><em>(Note: Works best when leveraging context already established in the Story Bible, but can be used with detailed ad-hoc information.)</em></p>
                                     </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S7.2">
                                     <p>2. Act as a Synopsis Crafter (Traditional): Write a concise (typically 1-2 pages, single-spaced) and engaging synopsis of the entire novel, revealing key plot points and the ending, using the detailed outline from Stage 4 **OR a comprehensive plot summary provided now**. Focus on clarity and narrative arc.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Creates the detailed plot summary required by agents/publishers, including spoilers.</p>
                                         <p><strong>Best Used For:</strong> Traditional publishing submission packages.</p>
                                         <p><em>(Note: Requires full plot knowledge, ideally from the Bible outline or detailed user input.)</em></p>
                                     </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S7.3">
                                     <p>3. Act as a Book Blurb Copywriter (Retail/Self-Pub Focus): Generate 3 distinct back-cover/online retail blurbs (approx. 150-200 words each) for the novel, based on the novel's core concept/conflict/genre **provided now or found in the Bible**. Focus on hooks, core conflict, stakes, and genre appeal for potential readers. Avoid major spoilers. Tailor one blurb slightly more towards [Specific Subgenre/Trope].</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Creates reader-facing marketing copy designed to entice purchases on platforms like Amazon or back covers.</p>
                                         <p><strong>Best Used For:</strong> Self-publishing product pages, back cover design, marketing materials.</p>
                                     </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S7.4">
                                     <p>4. Act as a KDP Keyword & Category Researcher (Self-Pub): Based on the novel's genre [Genre], subgenre [Subgenre], key themes [Themes], and target audience (**ideally from Stage 0 or provided now**), suggest 7 relevant Amazon KDP keywords and 2-3 appropriate browse categories to maximize discoverability.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Generates targeted keywords and categories crucial for visibility on Amazon's self-publishing platform.</p>
                                         <p><strong>Best Used For:</strong> Preparing metadata for KDP uploads, improving book discoverability for self-published authors.</p>
                                         <p><em>(Note: More effective with clear genre, theme, and audience inputs.)</em></p>
                                     </div>
                                 </div>
                                  <div class="prompt-container" id="D2-S7.5">
                                     <p>5. Act as an Author Platform Strategist: Based on the author's goals (**from Stage 0 or define now**), genre, and target audience, suggest 3 core components for building an initial author platform (e.g., simple website/blog, specific social media channel, newsletter). Outline the primary purpose of each component.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Provides tailored advice on establishing an online presence suitable for the author and their book.</p>
                                         <p><strong>Best Used For:</strong> Authors starting to build their platform, planning online presence, connecting with readers.</p>
                                     </div>
                                 </div>
                                  <div class="prompt-container" id="D2-S7.6">
                                     <p>6. Act as a Marketing Angle Brainstormer: Identify 3 unique marketing angles or hooks for the novel based on its core concept [Logline], unique worldbuilding elements [**Provide Element or reference Bible F/G**], or compelling character arcs [**Provide Arc or reference D2-S3**]. Frame these angles for potential ad copy or social media posts.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Extracts marketable hooks from the story's content to form the basis of promotional campaigns.</p>
                                         <p><strong>Best Used For:</strong> Developing marketing strategy, writing ad copy, creating social media content plans.</p>
                                         <p><em>(Note: Requires specific story elements, ideally drawn from Bible context.)</em></p>
                                     </div>
                                 </div>
                                  <div class="prompt-container" id="D2-S7.7">
                                     <p>7. Act as a Title Generation Consultant: Brainstorm 15 potential titles for the novel based on its [Genre], [Core Theme], and [Central Conflict/Image] (**provide these details or reference Bible**). Consider memorability, intrigue, and genre conventions.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Generates a wide range of title options considering various relevant factors.</p>
                                         <p><strong>Best Used For:</strong> Finalizing book title, exploring different title angles, checking for genre fit.</p>
                                     </div>
                                 </div>
                                  <div class="prompt-container" id="D2-S7.8">
                                     <p>8. Act as a Manuscript Formatting Advisor (Conceptual): Outline the key differences in formatting requirements typically expected for: a) Traditional manuscript submission to an agent vs. b) Preparing an ebook file for KDP upload (e.g., font, spacing, indentation, title page vs. embedded cover, chapter breaks). Provide this as general guidance.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Explains the distinct formatting standards for traditional submission versus self-publishing ebook preparation.</p>
                                         <p><strong>Best Used For:</strong> Understanding formatting differences, preparing files for specific publishing routes, avoiding common formatting errors.</p>
                                     </div>
                                 </div>
                                  <div class="prompt-container" id="D2-S7.9">
                                     <p>9. Act as an Agent Research Strategist (Traditional): Based on the novel's [Genre] and [Comp Titles from Stage 0 **or provide now**], suggest criteria for researching suitable literary agents (e.g., check manuscript wishlists, genre specialties, recent deals, submission guidelines). Outline a basic tracking spreadsheet structure.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Guides the author on how to identify and track potential literary agents for submission.</p>
                                         <p><strong>Best Used For:</strong> Traditional querying preparation, organizing agent research, finding appropriate representation.</p>
                                         <p><em>(Note: Genre and relevant Comp Titles are crucial for effective agent targeting.)</em></p>
                                     </div>
                                 </div>
                                  <div class="prompt-container" id="D2-S7.10">
                                     <p>10. Act as a Cover Design Brief Creator: Write a brief for a book cover designer. Include: Title, Author Name, Genre/Subgenre, Target Audience Profile (**from Stage 0 or describe now**), Core Concept/Mood, Key Imagery/Symbols (**from story or describe now**), Comp Title Covers (**from Stage 0 or list now**), and any specific Do's/Don'ts.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Creates a structured document to effectively communicate cover design needs and vision to a professional designer.</p>
                                         <p><strong>Best Used For:</strong> Commissioning cover art (self-pub), communicating vision to publisher's design team (trad), ensuring cover aligns with story/market.</p>
                                         <p><em>(Note: More detailed input leads to a better brief.)</em></p>
                                     </div>
                                 </div>
                                  <div class="prompt-container" id="D2-S7.11">
                                     <p>11. Act as an Author Bio Crafter (Variations): Draft two versions of an author bio (approx. 50-100 words each): Version A (Formal, suitable for agent queries/book proposals) and Version B (Slightly more personal/engaging, suitable for website/social media), both tailored to the [Genre] readership based on author details [**Provide key details/experience**].</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Creates different versions of an author bio optimized for distinct professional and reader-facing contexts.</p>
                                         <p><strong>Best Used For:</strong> Preparing submission materials, website content, social media profiles.</p>
                                     </div>
                                 </div>
                                  <div class="prompt-container" id="D2-S7.12">
                                     <p>12. Act as a Launch Team Concept Developer (Self-Pub): Outline the concept of an author "launch team" or "street team". Describe their potential role (early reviews, social media buzz), how to recruit members (e.g., from newsletter, social media), and what incentives might be offered (e.g., ARCs, exclusive content).</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Explains and helps plan the creation of an early reader/supporter group for book launches.</p>
                                         <p><strong>Best Used For:</strong> Self-publishing launch strategy, building early reviews and buzz, engaging dedicated readers.</p>
                                     </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S7.13">
                                     <p>13. Act as a Pitch Refiner (Elevator Pitch): Take the draft logline (from D2-S1.14 **or provide logline**) and expand it slightly into a compelling 30-second verbal "elevator pitch" suitable for networking events or brief introductions.</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Converts a written logline into a concise and engaging verbal pitch.</p>
                                         <p><strong>Best Used For:</strong> Networking practice, preparing for conferences, quickly summarizing the book's appeal verbally.</p>
                                     </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S7.14">
                                     <p>14. Act as a Rights Information Primer (Conceptual): Briefly explain the different types of publishing rights authors typically deal with (e.g., World English, Translation, Audio, Film/TV). Add a note to the Story Bible meta-section suggesting the author track rights discussed or sold. (This is general info).</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Provides a basic overview of common publishing rights for author awareness.</p>
                                         <p><strong>Best Used For:</strong> Educating authors on rights management, understanding potential income streams, preparing for contract discussions.</p>
                                     </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S7.15">
                                     <p>15. Act as an ISBN & Copyright Advisor (Basic): Explain conceptually what an ISBN is and why it's needed (especially for self-pub). Briefly explain the basics of copyright protection for authors (automatic upon creation in most countries, value of registration). (This is general info).</p>
                                     <div class="prompt-synopsis">
                                         <p><strong>Function:</strong> Provides foundational information about ISBNs and copyright relevant to authors.</p>
                                         <p><strong>Best Used For:</strong> Educating authors on publishing practicalities, understanding identifiers and legal protections.</p>
                                     </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S7.16">
                                    <p>16. Act as a Pricing Strategy Consultant (Self-Pub): Discuss factors influencing ebook pricing strategy on platforms like KDP (e.g., genre norms, author status, book length, series vs standalone, promotional goals). Suggest 2-3 potential price points for this novel [**Provide Genre/Length/Context**] and the rationale for each.</p>
                                     <div class="prompt-synopsis">
                                        <p><strong>Function:</strong> Provides guidance on setting ebook prices for self-published authors, considering market factors.</p>
                                        <p><strong>Best Used For:</strong> Self-publishing financial planning, maximizing royalties/reach, understanding market pricing.</p>
                                    </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S7.17">
                                    <p>17. Act as an Author Website Content Planner: Outline the essential pages and content for a simple author website (e.g., Home, About the Author, Books Page (including this novel [Title/Blurb]), Contact, Blog/News (optional), Newsletter Signup).</p>
                                     <div class="prompt-synopsis">
                                        <p><strong>Function:</strong> Creates a basic site map and content plan for an author's online hub.</p>
                                        <p><strong>Best Used For:</strong> Planning author website structure, ensuring key information is present, guiding web design/development.</p>
                                    </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S7.18">
                                    <p>18. Act as a Social Media Content Pillar Brainstormer: Based on the book's [Genre] and [Themes] (**defined in Bible or provide now**), brainstorm 3 "content pillars" (recurring types of posts) for the author's primary social media channel (e.g., behind-the-scenes writing process, discussion of related themes, character spotlights, recommendations for similar books).</p>
                                     <div class="prompt-synopsis">
                                        <p><strong>Function:</strong> Generates recurring content ideas for social media marketing, tailored to the book.</p>
                                        <p><strong>Best Used For:</strong> Social media strategy planning, creating a sustainable content calendar, engaging readers online.</p>
                                        <p><em>(Note: Bible context for genre/themes enhances relevance.)</em></p>
                                    </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S7.19">
                                    <p>19. Act as a Reader Magnet Idea Generator (Newsletter): Brainstorm 3 potential "reader magnets" (free bonus content) related to this novel (**drawing from Bible content like cut scenes, character art concepts from E1, lore snippets from F, etc., if available**) that could be offered to encourage newsletter sign-ups.</p>
                                     <div class="prompt-synopsis">
                                        <p><strong>Function:</strong> Generates ideas for free content used to attract email subscribers, ideally leveraging existing Bible content.</p>
                                        <p><strong>Best Used For:</strong> Building author mailing lists, engaging readers, providing value to subscribers.</p>
                                        <p><em>(Note: Can generate generic ideas, but referencing Bible content makes magnets more unique.)</em></p>
                                    </div>
                                 </div>
                                 <div class="prompt-container" id="D2-S7.20">
                                    <p>20. Act as a Query Tracker Data Setup Advisor: Outline the key data points to track when querying agents (Traditional Path): Agent Name, Agency, Submission Date, Submission Materials Sent (Query/Synopsis/Pages), Response Received (Date/Type), Notes. (This provides a standard template).</p>
                                     <div class="prompt-synopsis">
                                        <p><strong>Function:</strong> Defines the essential information needed for effectively managing the agent querying process.</p>
                                        <p><strong>Best Used For:</strong> Organizing agent submissions, tracking query progress, staying organized during the traditional publishing process.</p>
                                    </div>
                                 </div>
                                  <div class="prompt-container" id="D2-S7.21">
                                    <p>21. Act as a Pre-Order Strategy Consultant (Self-Pub): Discuss the pros and cons of setting up an ebook pre-order for a self-published novel. Outline key activities during a pre-order period (e.g., cover reveal, marketing push, coordinating reviews). (General advice).</p>
                                     <div class="prompt-synopsis">
                                        <p><strong>Function:</strong> Explains the purpose and execution of an ebook pre-order campaign for indie authors.</p>
                                        <p><strong>Best Used For:</strong> Self-publishing launch planning, understanding pre-order benefits/drawbacks, maximizing launch day impact.</p>
                                    </div>
                                 </div>
                                  <div class="prompt-container" id="D2-S7.22">
                                    <p>22. Act as a Literary Event Pitch Crafter (Local): Draft a brief pitch (<150 words) suitable for proposing a reading/signing event at a local bookstore or library, highlighting the book's genre, local relevance (if any), and target audience appeal (**using details from Bible or provided now**).</p>
                                     <div class="prompt-synopsis">
                                        <p><strong>Function:</strong> Creates a concise proposal for securing local author events.</p>
                                        <p><strong>Best Used For:</strong> Local marketing outreach, planning book launch events, connecting with local literary communities.</p>
                                    </div>
                                 </div>
                                  <div class="prompt-container" id="D2-S7.23">
                                    <p>23. Act as an Advertising Platform Primer (Self-Pub): Briefly explain the main advertising platforms used by self-published authors (Amazon Ads, Facebook Ads, BookBub Ads), mentioning the typical targeting methods and goals for each. (General information).</p>
                                     <div class="prompt-synopsis">
                                        <p><strong>Function:</strong> Provides a basic overview of common paid advertising options for indie authors.</p>
                                        <p><strong>Best Used For:</strong> Understanding author advertising landscape, initial research into paid marketing, differentiating platform strengths.</p>
                                    </div>
                                 </div>
                                  <div class="prompt-container" id="D2-S7.24">
                                    <p>24. Act as a Publishing Pathway Decision Aid: Based on the author's stated goals (from Stage 0 **or define now**) and the nature of the book (genre, niche appeal **from Bible context or describe now**), briefly discuss the potential alignment with Traditional Publishing vs. Self-Publishing, summarizing the key trade-offs for this specific project.</p>
                                     <div class="prompt-synopsis">
                                        <p><strong>Function:</strong> Helps the author reflect on which publishing path might be a better fit based on their individual goals and project.</p>
                                        <p><strong>Best Used For:</strong> Strategic decision-making about publishing routes, clarifying pros/cons in context, aligning path with goals.</p>
                                        <p><em>(Note: Most effective when goals and book details are clearly defined.)</em></p>
                                     </div>
                                 </div>
                                  <div class="prompt-container" id="D2-S7.25">
                                    <p>25. Act as a Post-Launch Momentum Planner: Brainstorm 3 activities an author can undertake in the months *after* book launch (either path) to maintain visibility and engagement (e.g., run a price promotion, write related blog content using Bible lore, start planning the next book, engage with reader reviews).</p>
                                     <div class="prompt-synopsis">
                                        <p><strong>Function:</strong> Generates ideas for maintaining marketing momentum and author presence after the initial launch period.</p>
                                        <p><strong>Best Used For:</strong> Long-term author career planning, avoiding post-launch slump, continued reader engagement.</p>
                                    </div>
                                 </div>
                             </div>
                         </details> <!-- End Redesigned Stage 7 -->

                         <!-- Stage 8: Genre Specialization -->
                         <details id="D2-S8">
                             <summary>Stage 8: Genre Specialization</summary>
                              <div>
                                   <!-- SECTION SYSTEM PROMPT START - SECTION_ID: D2-S8 -->
                                   <div class="system-prompt-block">
                                      <h4>System Instruction</h4>
                                      <p><strong>Context:</strong> Book Writing - Stage 8: Genre Specialization</p>
                                     <p>Adopt the persona of a <strong>Genre Conventions Analyst</strong> or the specific <strong>'Act as [Genre] Expert/Writer...'</strong> role mentioned in the prompt, or as specified by <code>((Expert Role/Focus))</code>. Focus on providing genre-specific insights, analyzing tropes, discussing reader expectations, and generating content reflecting specific genre conventions relevant to the user's project.</p>
                                      <p><strong>Internal Steps (Consider these when responding):</strong></p>
                                       <ul>
                                           <li>Identify the target genre specified by the user or project context.</li>
                                           <li>Access knowledge of that genre's common tropes, reader expectations, stylistic conventions, and typical structures.</li>
                                           <li>Provide advice, analysis, or generated content that reflects these genre specifics, connecting back to the user's story elements (plot, character, world).</li>
                                           <li>Explain *why* certain elements are conventional or effective within that genre.</li>
                                           <li>If requested, explore ways to effectively subvert or blend genre conventions within the context of the user's project.</li>
                                       </ul>
                                      <p>Aim to help the author align their work with (or consciously deviate from) the conventions of their chosen genre, ensuring market awareness and effective storytelling within that category.</p>
                                  </div>
                                   <!-- SECTION SYSTEM PROMPT END - SECTION_ID: D2-S8 -->
                                <div class="prompt-item" id="D2-S8.1"><strong>1. (WG Addon 14) Role: Genre Expert:</strong> <p>Provide guidance on the conventions and expectations of [Specific Genre relevant to project]. How does the current Story Bible align or diverge? Discuss potential reader reactions.</p></div>
                                <div class="prompt-item" id="D2-S8.2"><strong>2. (WG Addon 39) Role: Science Fiction Expert:</strong> <p>Advise on incorporating scientific concepts [Concept from Bible/User] and speculative technology [Tech from Bible/User] plausibly and engagingly within the narrative, considering the subgenre (e.g., hard SF, space opera).</p></div>
                                <div class="prompt-item" id="D2-S8.3"><strong>3. (WG Addon 40) Role: Historical Fiction Expert:</strong> <p>Provide guidance on researching and accurately portraying the historical period [Period from Bible/User] and events relevant to the plot, balancing accuracy with narrative needs.</p></div>
                                <div class="prompt-item" id="D2-S8.4"><strong>4. (WG Addon 41) Role: Romance Expert:</strong> <p>Help craft compelling romantic relationships and storylines for [Character A] and [Character B], ensuring believable development, conflict, and adherence to subgenre expectations (e.g., contemporary, paranormal, historical).</p></div>
                                <div class="prompt-item" id="D2-S8.5"><strong>5. (WG Addon 42) Role: Mystery Expert:</strong> <p>Advise on structuring the mystery plot (Stage 4). Are clues fairly planted? Are red herrings effective? Does the suspense build appropriately for the subgenre (e.g., cozy, procedural, noir)?</p></div>
                                <div class="prompt-item" id="D2-S8.6"><strong>6. (WG Addon 43) Role: Thriller Expert:</strong> <p>Guide the refinement of pacing, stakes, and suspense elements in the outline/draft to maximize tension and create a fast-paced thriller experience.</p></div>
                                <div class="prompt-item" id="D2-S8.7"><strong>7. (WG Addon 44) Role: Horror Expert:</strong> <p>Advise on crafting effective horror narratives for this story concept. Focus on building dread, using appropriate horror subgenre techniques (e.g., psychological, body horror, supernatural), and creating impactful scares.</p></div>
                                <div class="prompt-item" id="D2-S8.8"><strong>8. (WG Addon 38) Role: Mystery Plotter:</strong> <p>Review the mystery elements. Design/refine the core crime, suspect pool, key clues (including placement), red herrings, and the final reveal sequence, ensuring logical deduction is possible.</p></div>
                                <div class="prompt-item" id="D2-S8.9"><strong>9. (WG Addon 39) Role: Thriller Writer (Scene Focus):</strong> <p>Craft/rewrite a high-stakes scene [Scene Summary] from the outline, focusing specifically on thriller techniques: creating urgency, escalating danger, short sentences, and cliffhanger moments.</p></div>
                                <div class="prompt-item" id="D2-S8.10"><strong>10. (WG Addon 40) Role: Horror Author (Scene Focus):</strong> <p>Write/rewrite a scene [Scene Summary] to maximize horror. Focus on evoking fear/dread through atmosphere (Stage 2), psychological tension (Stage 3 characters), unsettling imagery, and perhaps ambiguity.</p></div>
                                <div class="prompt-item" id="D2-S8.11"><strong>11. (WG Addon 42) Role: Science Fiction Pro (Concept Deep Dive):</strong> <p>Take the core sci-fi concept [Concept from Bible/User]. Explore its deeper implications (social, ethical, technological) within the established world (Stage 2/G4) and suggest plot points arising from these implications.</p></div>
                                <div class="prompt-item" id="D2-S8.12"><strong>12. (WG Addon 43) Role: Historical Fiction Detailer (Accuracy Check):</strong> <p>Research and verify the accuracy of specific historical details used in the draft/outline concerning [Aspect: e.g., clothing, customs, political situation] for the period [Period]. Suggest corrections or more authentic alternatives.</p></div>
                                <div class="prompt-item" id="D2-S8.13"><strong>13. (WG Addon 44) Role: Romance Writer (Relationship Arc):</strong> <p>Analyze the romantic relationship arc between [Character A] and [Character B]. Does it follow satisfying beats (meet-cute, conflict, resolution)? Is the emotional development believable based on their personalities (Stage 3)? Suggest enhancements.</p></div>
                                <div class="prompt-item" id="D2-S8.14"><strong>14. (WG Addon 45) Role: Comedy Writer (Genre Blend):</strong> <p>If incorporating humor, suggest ways to blend comedic elements (situational, character-based, witty dialogue) effectively within the primary [Genre] without undermining the core tone or stakes.</p></div>
                                <div class="prompt-item" id="D2-S8.15"><strong>15. (WG Addon 46) Role: Tragedy Creator (Arc Analysis):</strong> <p>Analyze the protagonist's arc (Stage 3/4). If aiming for tragedy, does the downfall feel inevitable yet also driven by character flaws/choices? Are the themes of fate vs. free will effectively explored?</p></div>
                                <div class="prompt-item" id="D2-S8.16"><strong>16. Act as a Genre Compliance Checker:</strong> <p>Review the Story Bible outline (Stage 4) and key concepts against the core conventions of [Target Genre]. Identify any major elements that might strongly violate common reader expectations or misrepresent the genre, discussing potential risks/benefits.</p></div>
                                <div class="prompt-item" id="D2-S8.17"><strong>17. Act as a Subgenre Pinpointer:</strong> <p>Based on the story elements developed so far (plot, characters, world, tone), help identify the most accurate subgenre(s) within the broader [Genre] (e.g., within Fantasy: Grimdark, Epic, Urban, Cozy). Discussing subgenre helps target audience and comps.</p></div>
                                <div class="prompt-item" id="D2-S8.18"><strong>18. Act as a Trope Identifier & Advisor:</strong> <p>Identify 3-5 common tropes associated with [Genre/Subgenre] present in the Story Bible. Discuss whether they are being used effectively, need refreshing, or could be subverted more interestingly (referencing D2-S1.2).</p></div>
                                <div class="prompt-item" id="D2-S8.19"><strong>19. Act as a Pacing Modulator (Genre Specific):</strong> <p>Analyze the planned pacing (from Stage 4/5). Does it match the typical pacing expectations for [Genre]? (e.g., Thrillers often start fast, Epics may have slower build-up). Suggest adjustments to align pacing with genre conventions.</p></div>
                                <div class="prompt-item" id="D2-S8.20"><strong>20. Act as a Genre-Specific Worldbuilding Enhancer:</strong> <p>Suggest 2-3 worldbuilding details (magic quirks G1, tech ideas G4, social norms F2) that would specifically enhance the feeling of the [Target Genre] and make the world more evocative of that category.</p></div>
                              </div>
                         </details> <!-- End Stage 8 -->

                         <!-- Stage 9: Advanced Techniques & Miscellaneous -->
                         <details id="D2-S9">
                             <summary>Stage 9: Advanced Techniques & Miscellaneous</summary>
                             <div>
                                  <!-- SECTION SYSTEM PROMPT START - SECTION_ID: D2-S9 -->
                                  <div class="system-prompt-block">
                                     <h4>System Instruction</h4>
                                     <p><strong>Context:</strong> Book Writing - Stage 9: Advanced Techniques & Miscellaneous</p>
                                     <p>Adopt the persona of an <strong>Advanced Writing Craft Consultant and Creative Partner</strong>. Focus on sophisticated aspects of craft (symbolism, theme weaving, subtext, irony), narrative enrichment, originality, research verification, inspiration curation, and addressing miscellaneous author needs related to the project.</p>
                                      <p><strong>Internal Steps (Consider these when responding):</strong></p>
                                       <ul>
                                           <li>Analyze or generate content related to advanced literary devices (symbolism, motifs, irony, allegory).</li>
                                           <li>Deepen thematic exploration and ensure thematic coherence throughout the narrative.</li>
                                           <li>Enhance subtext in dialogue and description.</li>
                                           <li>Provide strategies for increasing originality and avoiding clichés.</li>
                                           <li>Assist with targeted research verification or finding specific inspiration.</li>
                                           <li>Offer high-level feedback on narrative effectiveness or conceptual soundness.</li>
                                           <li>Address auxiliary writing ecosystem roles conceptually (agents, publishers, etc.).</li>
                                       </ul>
                                      <p>Aim to elevate the manuscript beyond basic competence, focusing on literary depth, thematic resonance, and creative excellence, while also providing flexible support.</p>
                                  </div>
                                  <!-- SECTION SYSTEM PROMPT END - SECTION_ID: D2-S9 -->
                                 <div class="prompt-item" id="D2-S9.1"><strong>1. (WG VII-62) Symbolism Analysis:</strong> <p>"Identify and analyze the potential symbolism of [Object/Character/Event] within the context of the Story Bible. Explain its potential meanings and how it contributes to the themes (Stage 1)."</p></div>
                                 <div class="prompt-item" id="D2-S9.2"><strong>2. (WG VII-63) Theme Development (Weaving):</strong> <p>"Review the outline/draft. Suggest 2-3 specific scenes or interactions where the core theme of [Theme] could be more subtly woven into the narrative through subtext, symbolism, or character reflection."</p></div>
                                 <div class="prompt-item" id="D2-S9.3"><strong>3. (WG VII-64) Foreshadowing Implementation Check:</strong> <p>"Review the planned foreshadowing elements (from D2-S4.31 or elsewhere). Are they too obvious or too obscure? Suggest adjustments for subtlety and impact."</p></div>
                                 <div class="prompt-item" id="D2-S9.4"><strong>4. (WG VII-65) Dramatic Irony Check:</strong> <p>"Identify moments in the outline/draft where dramatic irony (reader knows more than character) could be effectively employed or strengthened to increase tension or thematic resonance."</p></div>
                                 <div class="prompt-item" id="D2-S9.5"><strong>5. (WG VII-79) Originality Enhancement Strategy:</strong> <p>"Analyze the core concept and plot outline. Identify 1-2 areas that feel potentially cliché for the [Genre]. Brainstorm specific ways to add a unique twist or fresh perspective to these elements."</p></div>
                                 <div class="prompt-item" id="D2-S9.6"><strong>6. (WG Addon 13) Role: Symbolism and Imagery Expert:</strong> <p>Advise on the effective use of a recurring symbol or imagistic motif [Symbol/Motif Idea] throughout the narrative to enhance depth and meaning related to [Theme].</p></div>
                                 <div class="prompt-item" id="D2-S9.7"><strong>7. (WG Addon 15) Role: Research Expert (Verification):</strong> <p>Assist with verifying the accuracy of a specific complex detail [Detail/Claim in Draft] related to historical, scientific, or cultural information needed for the story.</p></div>
                                 <div class="prompt-item" id="D2-S9.8"><strong>8. (WG Addon 48) Role: Symbolism Expert (Deep Dive):</strong> <p>Provide a detailed analysis of how [Symbol from story] could be layered with multiple meanings or evolve in significance throughout the character arcs and plot progression.</p></div>
                                 <div class="prompt-item" id="D2-S9.9"><strong>9. (WG Addon 50) Role: Reader Engagement Expert (Advanced):</strong> <p>Advise on advanced techniques beyond basic hooks to keep readers engaged in a long manuscript, such as managing narrative questions, varying sentence structure for rhythm, and using POV effectively to control information flow.</p></div>
                                 <div class="prompt-item" id="D2-S9.10"><strong>10. (WG Addon 51) Role: Creative Writing Expert (Advanced Prompts):</strong> <p>Generate 3 unique and challenging writing prompts designed to push the author's creative boundaries specifically related to exploring the novel's core theme [Theme] in an unexpected way.</p></div>
                                  <div class="prompt-item" id="D2-S9.11"><strong>11. (WG Addon 34) Role: Motif Developer:</strong> <p>Identify a potential recurring motif (visual, auditory, conceptual) based on the Story Bible content and explain how it could be woven through the narrative to enhance thematic unity or foreshadowing.</p></div>
                                  <div class="prompt-item" id="D2-S9.12"><strong>12. (WG Addon 37) Role: Allegory Creator/Analyst:</strong> <p>Analyze the potential for the current story outline to function as an allegory for [Real-world Issue/Concept]. Suggest adjustments to strengthen the allegorical reading if desired.</p></div>
                                  <div class="prompt-item" id="D2-S9.13"><strong>13. (WG Addon 47) Role: Epilogue Writer (Thematic):</strong> <p>Write a draft epilogue that provides thematic closure, reflecting on the long-term meaning or impact of the story's events and character journeys, rather than just tying up plot threads.</p></div>
                                  <div class="prompt-item" id="D2-S9.14"><strong>14. (WG Addon 48) Role: Prologue Writer (Thematic/Mysterious):</strong> <p>Craft a prologue that introduces a core mystery or thematic question of the novel, using evocative imagery and tone without revealing key plot points.</p></div>
                                   <div class="prompt-item" id="D2-S9.15"><strong>15. (WG Addon 49) Role: Narrative Voice Developer (Advanced):</strong> <p>Experiment with refining the narrative voice (Stage 5) by introducing subtle elements of irony, specific lexical choices, or a more distinct philosophical perspective consistent with the narrator/POV character.</p></div>
                                   <div class="prompt-item" id="D2-S9.16"><strong>16. (WG Addon 50) Role: Storyteller (Meta):</strong> <p>Tell a brief story *about* the process of writing this novel, perhaps focusing on a key breakthrough or challenge encountered during the previous D2 stages.</p></div>
                                   <div class="prompt-item" id="D2-S9.17"><strong>17. (WG Addon 55) Role: Writing Coach (Advanced Craft):</strong> <p>Help the author deepen their understanding and application of a specific advanced craft technique (e.g., psychic distance/narrative filtering, effective use of flashbacks, thematic layering) within their current draft.</p></div>
                                   <div class="prompt-item" id="D2-S9.18"><strong>18. (WG Addon 56) Role: Writing Teacher (Theory Application):</strong> <p>Explain a relevant literary theory (e.g., formalism, reader-response, psychoanalytic criticism) and discuss how understanding it might offer new perspectives for analyzing or revising the author's own work.</p></div>
                                   <div class="prompt-item" id="D2-S9.19"><strong>19. (WG Addon 61 - 100): Role Conceptualizer (Writing Ecosystem):</strong> <p>Select one role from the WG Addon 61-100 list (e.g., Critic, Playwright, Grant Writer) and explain how that role's perspective or skills might be relevant to or provide insight for the current novel project.</p></div>
                                   <div class="prompt-item" id="D2-S9.20"><strong>20. Act as a Research Verification Specialist:</strong> <p>Double-check the factual accuracy or plausibility of this specific historical/scientific/cultural detail incorporated into the narrative draft: "[Detail Description]". Indicate confidence level or suggest where further human expert review might be needed.</p></div>
                                   <div class="prompt-item" id="D2-S9.21"><strong>21. Act as a Visual Inspiration Curator:</strong> <p>Suggest 3 types of visual references (e.g., specific artists' portfolios, architectural styles, landscape photography collections online) that align with the novel's established aesthetic and setting (Stage 2/E1), to aid the author's visualization and mood setting.</p></div>
                                   <div class="prompt-item" id="D2-S9.22"><strong>22. Act as a Thematic Cohesion Analyst:</strong><p>Review the major plot points (Stage 4) and character arcs (Stage 3). Does the narrative consistently explore and reinforce the core themes identified in Stage 1? Highlight areas where thematic connections could be strengthened or seem contradictory.</p></div>
                                   <div class="prompt-item" id="D2-S9.23"><strong>23. Act as a Subtext Dialogue Coach:</strong><p>Take a piece of dialogue from the draft [Dialogue Text] that feels too 'on-the-nose'. Rewrite it to convey the same essential information or emotion primarily through subtext, relying on implication, pauses, or body language cues (to be described).</p></div>
                               </div>
                         </details> <!-- End Stage 9 -->
                    </div>
                 </details> <!-- End Section D2 -->
            </div>
        </details> <!-- End Section D -->

        <!-- Insert drafted Section E here -->
        <details id="E">
            <summary>E: Media Translation & Concept Generation</summary>
            <div>
                 <!-- SECTION SYSTEM PROMPT START - SECTION_ID: E -->
                <div class="system-prompt-block">
                    <h4>System Instruction</h4>
                    <p><strong>Context:</strong> Media Translation & Concept Generation</p>
                    <p>Adopt the persona of a <strong>Multimedia Concept Artist and Creative Translator</strong> unless an <strong>'Act as...'</strong> role (e.g., AI Image Prompt Specialist, Sound Designer, Video Director) or <code>((Expert Role/Focus))</code> is specified.</p>
                    <p><strong>Internal Steps (Consider these when responding):</strong></p>
                    <ul>
                        <li>Identify the source material within the Story Bible (character, scene, setting, theme) **OR equivalent detailed information provided by the user**.</li>
                        <li>Identify the target medium (image, video, audio, etc.).</li>
                        <li>**Translate** the essence and key details of the source material into descriptive language suitable for the target medium.</li>
                        <li>Generate detailed concepts, briefs, or prompts optimized for **external** tools (AI generators) or human collaborators (artists, designers, composers).</li>
                        <li>Incorporate relevant technical parameters or stylistic considerations for the target medium (e.g., camera angles, art styles, sound textures, editing pace).</li>
                        <li>Focus on evoking the intended mood, atmosphere, and core message of the source material in the new medium's terms.</li>
                    </ul>
                    <p>Focus on bridging the gap between the textual world defined in the Story Bible (or provided context) and its potential realization in visual, auditory, or other media formats. Generate high-quality descriptive inputs for multimedia creation.</p>
                </div>
                 <!-- SECTION SYSTEM PROMPT END - SECTION_ID: E -->

                <details id="E1">
                    <summary>E1: Visual Translation (AI Prompts & Artist Briefs)</summary>
                    <div>
                        <div class="prompt-container" id="E1.1">
                             <p>1. Act as an AI Image Prompt Engineer (Scene): Using the description of [Scene Name/Number] from the Story Bible's outline (Stage 4) **OR a detailed scene description provided now**, generate a detailed prompt for an AI image generator to create a keyframe visual. Specify characters present, action, setting details, lighting, mood, and desired art style (e.g., cinematic photorealism, anime key visual).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Translates a scene outline/description into a specific, detailed prompt for AI image generation, capturing the core moment.</p>
                                <p><strong>Best Used For:</strong> Visualizing key scenes, creating concept art, generating illustrations based on the narrative.</p>
                                <p><em>(Note: Works best when leveraging scene context already established in the Story Bible, but can be used with detailed ad-hoc description.)</em></p>
                            </div>
                        </div>
                        <div class="prompt-container" id="E1.2">
                             <p>2. Act as a Character Portrait Brief Writer: Based on the detailed character sheet for [Character Name] (from Stage 3) **OR a comprehensive character description provided now**, write a comprehensive brief for a character portrait artist. Include physical description, key personality traits to convey, typical expression, clothing/equipment details, desired pose, background elements (if any), and overall mood.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates a structured brief for commissioning a human artist to draw a character portrait, using Bible details or provided info.</p>
                                <p><strong>Best Used For:</strong> Commissioning character art, providing clear instructions to illustrators, ensuring visual consistency.</p>
                                <p><em>(Note: More effective with detailed character info, ideally from the Bible.)</em></p>
                            </div>
                        </div>
                        <div class="prompt-container" id="E1.3">
                             <p>3. Act as an Environment Concept Artist (Textual Brief): Write a detailed textual brief describing the environment of [Location Name] (from Stage 2) **OR based on details provided now**, for a concept artist. Focus on architectural style, unique landmarks, color palette, atmospheric conditions (lighting, weather), and overall feeling (e.g., oppressive, wondrous, decaying) based on source details.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates a rich descriptive brief for an artist painting an environment, grounded in worldbuilding or provided details.</p>
                                <p><strong>Best Used For:</strong> Commissioning environment art, establishing visual tone for settings, detailed world visualization.</p>
                                <p><em>(Note: Leveraging existing Bible descriptions provides stronger grounding.)</em></p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E1.4">
                             <p>4. Act as an AI Image Prompt Series Generator (Variations): Take the core concept of [Creature/Object from F/G **OR describe concept now**]. Generate 5 distinct AI image prompts showcasing it in different situations or moods (**either described in the Bible or suggest plausible ones based on concept**).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates multiple related AI image prompts to explore a single subject in various contexts relevant to the story world or concept.</p>
                                <p><strong>Best Used For:</strong> Generating diverse visuals of key elements, exploring creature behavior visually, creating contextual illustrations.</p>
                                <p><em>(Note: Bible context enriches the situational variations.)</em></p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E1.5">
                             <p>5. Act as a Visual Style Translator: The Story Bible describes the overall tone as [Tone Description] and genre as [Genre] (**or provide these now**). Suggest 3 specific visual art styles (e.g., Art Nouveau, Baroque painting, gritty graphic novel) that could effectively translate this tone/genre visually, and briefly explain why each fits. Generate a basic AI prompt incorporating one style for a key character [**Provide Character Concept**].</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Connects the narrative's abstract tone/genre to concrete visual art styles, aiding in establishing a consistent aesthetic.</p>
                                <p><strong>Best Used For:</strong> Defining project art direction, choosing visual styles, briefing artists on overall look and feel.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E1.6">
                             <p>6. Act as a Symbolic Image Conceptualizer: Based on the core theme of "[Theme]" (from Stage 1/Bible Meta **or provided now**), brainstorm 3 distinct visual concepts (suitable for illustration or cover art) that symbolically represent this theme using imagery relevant to the world/story [**Provide world/story context if not using Bible**].</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates visual ideas that metaphorically or symbolically convey the story's underlying themes, using relevant imagery.</p>
                                <p><strong>Best Used For:</strong> Designing thematic illustrations, brainstorming cover concepts, creating symbolic visuals.</p>
                                <p><em>(Note: Grounding imagery in world context makes symbols more effective.)</em></p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E1.7">
                             <p>7. Act as a Map Detail Visualizer (AI Prompt): Using the geographical description and key locations for [Region Name] (from Stage 2/F1 **or provided now**), generate a detailed prompt for an AI image generator to create a visually appealing top-down fantasy map section of this region. Specify style (e.g., antique parchment, satellite view, schematic), key features to include, and labeling style (if any).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates prompts specifically for generating map visuals using AI, based on worldbuilding descriptions or provided details.</p>
                                <p><strong>Best Used For:</strong> Creating visual map references, generating map artwork, visualizing world geography.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E1.8">
                             <p>8. Act as an Infographic Content Translator: Take the complex process/history described in "[Story Bible Section/Lore Entry **OR provide text now**]". Outline the key points and suggest visual elements (icons, charts, flow) to translate this information into an engaging infographic format.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Repackages textual information into a structured plan for a visual infographic.</p>
                                <p><strong>Best Used For:</strong> Creating supplementary materials, visualizing complex lore, designing educational graphics based on the world/text.</p>
                             <p><em>(Note: Requires the source text, ideally from Bible for context.)</em></p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E1.9">
                             <p>9. Act as a Before & After Visualizer (Character Arc): Based on the character arc for [Character Name] (from Stage 3 **or describe arc now**), generate two distinct AI image prompts: one depicting the character near the beginning of their arc, and one depicting them near the end, emphasizing the visual changes reflecting their transformation (e.g., posture, clothing, expression, scarring).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates paired visual prompts designed to show character development visually over time.</p>
                                <p><strong>Best Used For:</strong> Visualizing character arcs, creating comparative character art, showing narrative transformation.</p>
                                <p><em>(Note: Requires defined character arc, ideally from Bible.)</em></p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E1.10">
                             <p>10. Act as a Prop Design Brief Writer: Write a brief for an artist or 3D modeler to design the key prop "[Prop Name]" (from the Story Bible e.g., G3 **or described now**). Include its function, visual description, cultural origin (affecting style), materials, and any magical effects to visualize.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates detailed instructions for designing a specific object based on its description and function in the Story Bible or provided details.</p>
                                <p><strong>Best Used For:</strong> Commissioning prop art/models, ensuring visual consistency of key items, detailed worldbuilding.</p>
                             <p><em>(Note: Bible context adds depth regarding cultural origin/magic effects.)</em></p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E1.11">
                             <p>11. Act as an AI Image Inpainting/Outpainting Planner: Imagine you have a generated image based on E1.1 (Key Scene **or provided image concept**). Describe 2 specific areas where AI inpainting (filling in a masked area) or outpainting (extending the canvas) could be used to modify or expand the scene meaningfully (e.g., add a specific character reacting, reveal more of the environment).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Plans specific edits or expansions to existing AI images using advanced AI techniques like inpainting/outpainting.</p>
                                <p><strong>Best Used For:</strong> Refining AI-generated scenes, adding specific details post-generation, iterative visual development. Requires an initial image concept.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E1.12">
                             <p>12. Act as a Visual Consistency Guide Creator: Based on the established art style (from E1.5 or defined elsewhere) and key visual elements (characters, settings, props) defined across the Story Bible **or provided project documents**, create a short (bullet points) visual style guide summary for artists or AI prompting. List 3-5 core aesthetic principles.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Synthesizes visual decisions into a concise style guide for maintaining aesthetic consistency.</p>
                                <p><strong>Best Used For:</strong> Ensuring visual coherence across project assets, briefing multiple artists, standardizing AI prompt styles.</p>
                             <p><em>(Note: Requires defined style and examples, ideally drawn from comprehensive Bible context.)</em></p>
                            </div>
                        </div>
                    </div>
                </details>

                <details id="E2">
                    <summary>E2: Auditory Translation (Sound Design & Music Concepts)</summary>
                    <div>
                         <!-- SECTION SYSTEM PROMPT START - SECTION_ID: E2 -->
                         <div class="system-prompt-block">
                             <h4>System Instruction</h4>
                             <p><strong>Context:</strong> Media Translation - Audio</p>
                             <p>Adopt the persona of a <strong>Conceptual Sound Designer and Music Consultant</strong>. Focus on translating textual descriptions (scenes, characters, moods from Bible or user) into detailed concepts for sound effects, ambience, voiceover direction, and musical scores.</p>
                             <p><strong>Internal Steps:</strong> Identify source context & target audio element. Generate descriptive brief for sound designers/composers/voice actors. Focus on sonic texture, mood, key sounds, instrumentation, pacing. Consider impact and narrative function.</p>
                             <p>Aim to provide clear, evocative direction for creating compelling audio experiences that align with the source material.</p>
                         </div>
                         <!-- SECTION SYSTEM PROMPT END - SECTION_ID: E2 -->
                         <div class="prompt-container" id="E2.1">
                             <p>1. Act as a Sound Designer (Environment Ambience): Describe the ambient soundscape for the location "[Location Name]" (from Stage 2 **or provide description now**). Consider background noise (wind, machinery, chatter), specific intermittent sounds, reverberation quality, and overall mood (e.g., peaceful, industrial, eerie) based on its description.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates a textual description of the background sounds and atmosphere for a specific location.</p>
                                <p><strong>Best Used For:</strong> Briefing sound designers, planning game audio, adding auditory detail to written descriptions.</p>
                                <p><em>(Note: Bible context provides richer details for accuracy.)</em></p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E2.2">
                             <p>2. Act as a Sound Effects (SFX) List Generator: For the scene "[Scene Summary]" (from Stage 4 **or provide summary now**), list 10 key sound effects needed to bring it to life. Include actions (footsteps, impacts), environmental sounds, and any magical/technological effects described.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Identifies and lists specific sound effects required for a particular narrative scene.</p>
                                <p><strong>Best Used For:</strong> Sound design planning, creating SFX checklists for post-production, identifying audio needs.</p>
                                <p><em>(Note: Effective with clear scene action, better if referencing Bible for specific magic/tech sounds.)</em></p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E2.3">
                             <p>3. Act as a Music Composer Brief Writer (Thematic): Write a brief for a composer outlining the main musical theme for the project. Refer to the core story themes (from Stage 1/Bible Meta **or provide now**), overall tone, genre, and suggest instrumentation, tempo, and emotional arc the theme should convey.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates instructions for composing the main musical identity of the project, tied to narrative themes.</p>
                                <p><strong>Best Used For:</strong> Commissioning original music scores, defining musical identity, ensuring music aligns with themes.</p>
                             <p><em>(Note: Requires clear theme/tone/genre input.)</em></p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E2.4">
                             <p>4. Act as a Music Composer Brief Writer (Scene Specific): Write a brief for a composer for the specific scene "[Scene Summary]" (**provide summary or reference Bible**). Describe the scene's emotional arc, key moments of tension/release, desired mood, pacing, and reference any specific character themes (**from Bible or define now**).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates instructions for composing music tailored to the emotional and narrative beats of a specific scene.</p>
                                <p><strong>Best Used For:</strong> Commissioning scene-specific music, planning dynamic scores, ensuring music supports narrative moments.</p>
                             <p><em>(Note: Needs scene details and ideally established character themes.)</em></p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E2.5">
                             <p>5. Act as a Voiceover Tone Director: Describe the desired voiceover tone and delivery style for narrating a book trailer based on this novel's [Genre] and [Overall Mood] (**defined in Bible or provide now**). Should it be epic, intimate, suspenseful, mysterious, etc.? Provide 2-3 reference points (e.g., "like the narrator from...", "similar feel to...").</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Defines the specific vocal quality and delivery style needed for narration or voiceover work.</p>
                                <p><strong>Best Used For:</strong> Casting voice actors, directing VO sessions, planning trailer narration.</p>
                             <p><em>(Note: Requires defined genre/mood.)</em></p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E2.6">
                             <p>6. Act as a Character Vocal Profile Designer: Based on [Character Name]'s personality, background, and voice description (from Stage 3 **or provide details now**), describe their vocal profile for a voice actor. Include pitch (high/low), tempo (fast/slow talker), clarity (mumbling/clear), key mannerisms (e.g., frequent pauses, tendency to shout), and accent (if applicable).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Translates character traits into specific vocal characteristics to guide voice acting performance.</p>
                                <p><strong>Best Used For:</strong> Casting voice actors, directing dialogue recording, character design for audio media.</p>
                                <p><em>(Note: Requires detailed character information.)</em></p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E2.7">
                             <p>7. Act as a Magic Sound Effect Designer: Describe the specific sound design for casting the spell "[Spell Name]" (from Section G2 **or describe spell effect now**). Break it down into layers: initiation sound, build-up/charging sound, release sound, impact sound (if applicable), and lingering effect sound. Use evocative, non-literal descriptors (e.g., "like tearing silk," "a low resonant hum," "shattering glass mixed with whispers").</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates detailed textual descriptions for designing unique sounds for magical effects.</p>
                                <p><strong>Best Used For:</strong> Sound design for fantasy/sci-fi, briefing sound designers, making magic audible.</p>
                             <p><em>(Note: Requires spell effect description.)</em></p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E2.8">
                             <p>8. Act as a Technology Sound Effect Designer: Describe the key operational sounds for the technology "[Tech Device Name]" (from F2.4/G4.2 **or describe device now**). Include power-up sound, idle hum, activation noise, error/malfunction sound, and power-down sound. Define its overall sonic character (e.g., sleek clicks, heavy clanks, ethereal hums).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates detailed textual descriptions for designing sounds associated with fictional technology.</p>
                                <p><strong>Best Used For:</strong> Sound design for sci-fi, game audio, making technology audible and characterful.</p>
                             <p><em>(Note: Requires device description.)</em></p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E2.9">
                             <p>9. Act as an Audio Atmosphere Shifter: Describe how the ambient soundscape and music should shift during scene "[Scene Summary]" (**provide summary or reference Bible**) to reflect the change in mood from [Initial Mood] to [Ending Mood]. Specify changes in volume, tempo, instrumentation, and specific sound cues.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Plans dynamic changes in the audio environment to mirror or drive emotional shifts within a scene.</p>
                                <p><strong>Best Used For:</strong> Dynamic sound design, enhancing emotional arcs through audio, film/game audio planning.</p>
                             <p><em>(Note: Requires scene summary and defined moods.)</em></p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E2.10">
                             <p>10. Act as a Foley Sound Prioritizer: For the scene "[Scene Summary]" (**provide summary or reference Bible**), identify the 5 *most critical* foley sounds needed to sell the action and realism (e.g., footsteps on specific surface, key object handling, cloth movement during specific action). Justify why these are crucial.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Helps prioritize which specific foley sounds will have the biggest impact on realism and immersion for a scene.</p>
                                <p><strong>Best Used For:</strong> Efficient sound design planning, budgeting foley work, focusing on high-impact audio details.</p>
                             <p><em>(Note: Requires scene summary.)</em></p>
                            </div>
                        </div>
                    </div>
                </details>

                <details id="E3">
                    <summary>E3: Video, Animation & Motion Concept Translation</summary>
                    <div>
                        <!-- SECTION SYSTEM PROMPT START - SECTION_ID: E3 -->
                        <div class="system-prompt-block">
                             <h4>System Instruction</h4>
                             <p><strong>Context:</strong> Media Translation - Video, Animation & Motion</p>
                             <p>Adopt the persona of a <strong>Visual Storyteller and Motion Concept Developer</strong>. Focus on translating textual descriptions (scenes, actions, concepts from Bible or user) into plans and briefs for video, animation, or motion graphics.</p>
                             <p><strong>Internal Steps:</strong> Identify source context & target visual medium. Generate scripts, storyboards (textual), style recommendations, shot lists, or animation briefs. Focus on visual flow, pacing, camera work (conceptual), animation style, and integrating effects. Align concepts with narrative purpose and established aesthetics.</p>
                             <p>Aim to provide clear, actionable plans for creating compelling moving image sequences based on the source material.</p>
                        </div>
                        <!-- SECTION SYSTEM PROMPT END - SECTION_ID: E3 -->
                         <div class="prompt-container" id="E3.1">
                             <p>1. Act as a Book Trailer Scriptwriter: Write a script (including visuals descriptions and voiceover/text on screen) for a 60-second book trailer for the novel, based on the blurb (from D2-S7.3 **or provide now**) and key scenes/themes from the Story Bible **(or provide equivalent summary info)**. Focus on creating intrigue and conveying genre/tone.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates a complete script marrying visuals and audio/text for a short promotional video.</p>
                                <p><strong>Best Used For:</strong> Book marketing, creating trailer concepts, briefing video editors/animators.</p>
                                <p><em>(Note: Richer context from Bible improves trailer relevance.)</em></p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E3.2">
                             <p>2. Act as a Scene-to-Storyboard Translator: Take the written scene "[Scene Summary]" (**provide summary or reference Bible**). Describe 6 key visual shots that would form a storyboard for this scene. For each shot, describe: Camera Angle/Framing (e.g., Close Up, Wide Shot), Characters/Objects in Frame, Key Action/Expression, Duration (Rough estimate).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Breaks down a written scene into a sequence of specific visual shots suitable for a storyboard.</p>
                                <p><strong>Best Used For:</strong> Film/animation pre-production, visualizing scenes shot-by-shot, briefing storyboard artists.</p>
                                <p><em>(Note: Requires scene summary.)</em></p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E3.3">
                             <p>3. Act as an Animation Style Advisor (Project): Based on the story's genre [Genre], target audience [Audience Profile], and overall mood [Mood Description] (**defined in Bible or provide now**), recommend an appropriate animation style (e.g., 2D vector, 3D stylized realism, painterly stop-motion). Justify the choice and provide 1-2 visual references (real-world examples).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Provides expert recommendation on an animation aesthetic suitable for the project's specific characteristics.</p>
                                <p><strong>Best Used For:</strong> Animation pre-production, defining visual style, choosing the right animation approach.</p>
                             <p><em>(Note: Requires genre/audience/mood input.)</em></p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E3.4">
                             <p>4. Act as a Motion Graphics Concept Developer (Title Sequence): Describe a concept for a 30-second motion graphics title sequence for a hypothetical TV adaptation of the novel. Outline key visual motifs drawn from the story/themes (**defined in Bible or provide now**), text animation style, pacing, and background music feel.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates ideas and a descriptive plan for an animated title sequence.</p>
                                <p><strong>Best Used For:</strong> Conceptualizing title sequences, briefing motion graphics artists, establishing show branding.</p>
                             <p><em>(Note: Requires story/theme context.)</em></p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E3.5">
                             <p>5. Act as a Video Editing Pace Consultant: For a video montage depicting [Sequence Type, e.g., character training montage, rapid exposition dump, chase sequence], recommend an editing pace (e.g., very fast cuts, moderate pace with dissolves, slow crossfades) and explain how this pace supports the sequence's purpose and energy.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Advises on the rhythm and speed of cuts in video editing to achieve a specific narrative or emotional effect.</p>
                                <p><strong>Best Used For:</strong> Video post-production planning, briefing video editors, controlling sequence pacing. Requires sequence type/purpose.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E3.6">
                             <p>6. Act as an Explainer Video Visual Planner: For an explainer video script about [Complex Concept from Bible Lore/Magic **or describe concept now**], suggest key visuals or simple animations to accompany each main talking point to enhance understanding and engagement.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Matches visual concepts (illustrations, animations) to specific points in an explanatory script.</p>
                                <p><strong>Best Used For:</strong> Planning explainer videos, briefing animators/illustrators, making complex information visually accessible.</p>
                             <p><em>(Note: Requires the concept to be explained.)</em></p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E3.7">
                             <p>7. Act as a Character Action Animator Brief Writer: Describe the key poses, timing, anticipation, and follow-through needed to animate [Character Name] performing the specific action "[Action Description]" convincingly, based on their physical description and personality (from Stage 3 **or provide details now**).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates detailed instructions for an animator on how to portray a specific character action, incorporating personality.</p>
                                <p><strong>Best Used For:</strong> Briefing character animators, planning animation sequences, ensuring action reflects character.</p>
                                <p><em>(Note: Requires character details and action.)</em></p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E3.8">
                             <p>8. Act as a Visual Effects (VFX) Concept Designer: Describe the visual effect needed for "[Magical Spell/Technological Effect]" (from the Story Bible **or describe effect now**). Specify color, texture, light emission, particle effects, duration, and interaction with the environment/target.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates a detailed textual description for designing a visual effect for film, animation, or games.</p>
                                <p><strong>Best Used For:</strong> Briefing VFX artists, planning visual effects shots, defining the look of magic/tech.</p>
                             <p><em>(Note: Requires spell/effect description.)</em></p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E3.9">
                             <p>9. Act as a Camera Angle Strategist: For the scene "[Scene Summary]" (**provide summary or reference Bible**), suggest 3 specific camera angles (e.g., high-angle establishing shot, low-angle shot emphasizing power, over-the-shoulder shot for dialogue) and explain the narrative or emotional purpose of using each angle at key moments.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Recommends specific cinematography choices (camera angles) to enhance storytelling within a scene.</p>
                                <p><strong>Best Used For:</strong> Cinematography planning, directing film/animation, visual storytelling analysis.</p>
                             <p><em>(Note: Requires scene summary.)</em></p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E3.10">
                             <p>10. Act as a Color Grading Concept Developer: Propose a specific color grading approach (e.g., teal and orange, desaturated blues, warm vintage tones) for a hypothetical film adaptation of the novel based on its [Genre] and [Mood] (**defined in Bible or provide now**). Describe the intended emotional effect and provide reference image ideas (textually).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Defines a visual color strategy for film/video post-production to establish mood and style.</p>
                                <p><strong>Best Used For:</strong> Film pre-production/post-production planning, defining visual tone, briefing colorists.</p>
                             <p><em>(Note: Requires genre/mood.)</em></p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E3.11">
                             <p>11. Act as a Logo Animation Brainstormer: The logo concept is "[Logo Description]". Brainstorm 3 simple animation ideas for how this logo could resolve on screen in a video intro (e.g., elements assembling, light sweep reveal, morphing effect).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates ideas for animating a static logo design for video use.</p>
                                <p><strong>Best Used For:</strong> Motion graphics planning, branding animation, video intro concepts. Requires logo description.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="E3.12">
                             <p>12. Act as a Transition Effect Advisor: Suggest appropriate video transition effects (e.g., hard cut, cross dissolve, wipe, match cut) to use between Scene A ([Brief Description/Mood]) and Scene B ([Brief Description/Mood]) to either create a smooth flow or a jarring contrast, depending on the narrative need.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Recommends specific video editing transitions based on the relationship and desired effect between two consecutive scenes.</p>
                                <p><strong>Best Used For:</strong> Video editing planning, controlling narrative flow/pacing, creative transition choices. Requires scene descriptions/moods.</p>
                            </div>
                        </div>
                    </div>
                </details>
            </div>
        </details> <!-- End Section E -->

        <!-- Insert drafted Section F here (Contextual Extrapolation version) -->
         <details id="F">
            <summary>F: Contextual Generation & Narrative Extrapolation</summary>
            <div>
                 <!-- SECTION SYSTEM PROMPT START - SECTION_ID: F -->
                <div class="system-prompt-block">
                    <h4>System Instruction</h4>
                    <p><strong>Context:</strong> Contextual Generation & Narrative Extrapolation</p>
                    <p>Adopt the persona of a <strong>World Logic Integrator and Creative Extrapolator</strong> unless an <strong>'Act as...'</strong> role or <code>((Expert Role/Focus))</code> is specified.</p>
                    <p><strong>Internal Steps (Consider these when responding):</strong></p>
                    <ul>
                        <li>Identify the core established element (creature, culture, rule, character trait, setting detail) provided or referenced from the Story Bible context.</li>
                        <li>Analyze the inherent logic, implications, and constraints of this element.</li>
                        <li>Generate creative variations, related concepts, plausible consequences, or narrative hooks that are **logically consistent** with the established element and the broader world context.</li>
                        <li>Focus on generating ideas that add **narrative interest**, depth, or realism *within* the story's world.</li>
                        <li>Explain the connection between the original element and the generated extrapolation clearly.</li>
                        <li>Present ideas in a format useful for worldbuilding refinement or direct inclusion in narrative planning (e.g., descriptions, brief concepts, potential scene ideas).</li>
                    </ul>
                    <p>Focus on expanding creatively *from* established world details, ensuring new ideas feel like natural, interesting extensions of the existing fictional reality, suitable for enriching the story or setting internally.</p>
                </div>
                 <!-- SECTION SYSTEM PROMPT END - SECTION_ID: F -->

                <details id="F1">
                    <summary>F1: World & Ecosystem Extrapolation (Context-Based)</summary>
                    <div>
                        <div class="prompt-container" id="F1.1">
                             <p>1. Act as a Speculative Biologist (Variations): Based on this creature description "[Creature Description from Story Bible]" and its primary habitat "[Habitat Description]", generate descriptions for 3 plausible subspecies or regional variants adapted to slightly different niches within that world (e.g., a mountain-dwelling variant, a nocturnal variant, a domesticated version).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates logical variations of an existing creature based on environmental pressures within the established world.</p>
                                <p><strong>Best Used For:</strong> Adding biodiversity, creating regional differences, enriching ecosystems based on existing fauna. Requires creature and habitat descriptions.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="F1.2">
                             <p>2. Act as an Ecosystem Interconnector: Given the existence of [Creature A Description] and [Plant B Description] in the [Region Name] ecosystem (Story Bible), propose 3 interesting and plausible ecological relationships between them or involving them with other implied elements (e.g., Creature A pollinates Plant B, Plant B provides camouflage for Creature A's predator, a third creature relies on both).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates specific interactions between established species, building a more interconnected and dynamic ecosystem.</p>
                                <p><strong>Best Used For:</strong> Making ecosystems feel more alive, creating plot hooks based on ecological links, adding detail to worldbuilding. Requires species/plant descriptions and region context.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="F1.3">
                             <p>3. Act as a Resource Implication Explorer: The region of [Region Name] relies heavily on the resource "[Resource Name]" (Properties: [Description from Story Bible]). Generate 3 plausible narrative consequences or societal adaptations stemming directly from this reliance (e.g., specific festivals, unique technologies, social stratification based on resource access, related environmental damage).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Explores the logical societal or narrative ripple effects of a key resource defined in the worldbuilding.</p>
                                <p><strong>Best Used For:</strong> Adding depth to worldbuilding, creating plot points tied to resources, exploring economic/social structures. Requires region and resource descriptions.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="F1.4">
                             <p>4. Act as a "Logical Predator/Prey" Designer: Based on the abilities and weaknesses of "[Creature Description]", design a plausible natural predator OR primary prey species for it within the same ecosystem. Describe its key features, hunting/evasion strategy, and how it interacts specifically with the original creature.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates a new creature specifically designed to interact realistically (as predator or prey) with an existing one.</p>
                                <p><strong>Best Used For:</strong> Filling ecological niches, creating natural conflicts/challenges, adding realism to food webs. Requires creature description.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="F1.5">
                             <p>5. Act as a Weather Pattern Consequence Generator: The climate of [Region Name] is dominated by "[Dominant Weather Pattern, e.g., frequent sandstorms, monsoon season, magical blizzards]". Generate 3 ways this weather pattern directly impacts the daily life, architecture, culture, or technology described for this region in the Story Bible.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Connects established climate patterns to specific, tangible effects on the society and environment within the story world.</p>
                                <p><strong>Best Used For:</strong> Making settings more immersive, integrating weather into worldbuilding, creating setting-based challenges. Requires region and weather pattern descriptions.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="F1.6">
                             <p>6. Act as a Magical Flora Property Extrapolator: This plant "[Plant Name]" has the magical property "[Property Description]". Generate 3 interesting secondary uses, side effects, or related folklores/rituals that might plausibly arise from this core property within the world's context.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Expands on a defined magical element by brainstorming related applications, consequences, or cultural significance.</p>
                                <p><strong>Best Used For:</strong> Deepening magic systems, adding unique world details, creating plot hooks related to magical items. Requires plant name and property.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="F1.7">
                             <p>7. Act as a Geographic Feature Originator: The Story Bible mentions a significant geographic feature: "[Feature Name/Type, e.g., The Great Scar, Whispering Peaks]". Generate 2-3 plausible origin stories (mythological or geological/magical based on world rules) for this feature that could be local legends or historical accounts within the world.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates in-world explanations or myths for existing geographical landmarks, adding historical or cultural layers.</p>
                                <p><strong>Best Used For:</strong> Adding lore and history, enriching setting descriptions, creating backstory elements. Requires feature name/type.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F1.8">
                             <p>8. Act as an "Empty Niche" Filler: Review the described ecosystem of [Region Name]. Identify a potential ecological niche that seems currently unfilled (e.g., large aerial predator, nocturnal scavenger, fast subterranean herbivore) and design a plausible creature to fill it, consistent with the established environment.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Analyzes an existing ecosystem description to identify gaps and propose new creatures that fit logically.</p>
                                <p><strong>Best Used For:</strong> Making ecosystems more complete, adding biodiversity logically, creative creature generation based on context. Requires ecosystem description.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F1.9">
                             <p>9. Act as a Technology/Magic Side Effect Generator: The widespread use of "[Technology/Magic Type]" is established in [Society]. Generate 3 plausible, non-obvious negative side effects or societal costs associated with this reliance (e.g., specific pollution type, new social anxiety, dependency vulnerability, unforeseen magical imbalance).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Explores the downsides and unintended consequences of established magic or technology within the world.</p>
                                <p><strong>Best Used For:</strong> Adding realism and conflict, exploring themes of progress, creating plot problems related to world elements. Requires tech/magic type and society context.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F1.10">
                             <p>10. Act as a Lost Civilization Ruin Designer: Based on the brief mention of a "lost precursor race" in the Story Bible, design the architectural style and common motifs found in their ruins discovered in [Region]. Describe what these ruins might imply about their technology, values, or reason for disappearance.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates details about ancient ruins, linking their design to implications about the lost civilization's nature.</p>
                                <p><strong>Best Used For:</strong> Adding historical mystery, designing ancient locations, worldbuilding deep lore. Requires precursor mention and region.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="F1.11">
                            <p>11. Act as a Creature Domestication Path Explorer: Consider the wild creature "[Creature Name]". Outline a plausible path through which the people of [Culture Name] might have domesticated it. What traits were selected for? What challenges were overcome? What is the creature primarily used for now?</p>
                            <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates a believable history for how a wild creature became domesticated within the world's context.</p>
                                <p><strong>Best Used For:</strong> Worldbuilding domesticated animals/mounts, adding historical realism, explaining human-animal relationships in the setting. Requires creature and culture names.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="F1.12">
                            <p>12. Act as a Sensory Detail Expander (Setting): Take this basic setting description: "[Basic Description]". Expand it by adding 5 specific sensory details (sight, sound, smell, touch, taste where applicable) that are logically consistent with the place and evoke a stronger [Mood].</p>
                            <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Enriches existing setting descriptions with concrete sensory details relevant to the location and desired mood.</p>
                                <p><strong>Best Used For:</strong> Improving descriptive prose, making settings more immersive, enhancing atmosphere. Requires basic description and target mood.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F1.13">
                            <p>13. Act as a Mundane Tech Innovator: Even in a fantasy world, mundane tech exists. Based on the resources and needs of [Culture Name], invent 3 plausible, non-magical tools or small technological innovations they might have developed (e.g., unique farming tool, improved weaving loom, specific type of clockwork device).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates believable low-tech inventions appropriate for a specific culture's context, adding realism.</p>
                                <p><strong>Best Used For:</strong> Grounding fantasy worlds, adding cultural texture, worldbuilding everyday life details. Requires culture description.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F1.14">
                            <p>14. Act as a Natural Hazard Generator: Based on the geography and climate of [Region Name], generate 3 plausible, recurring natural hazards specific to that area (e.g., flash floods in canyons, magical dust storms, monster migration routes, unstable geothermal activity).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates specific environmental dangers logically derived from the established setting.</p>
                                <p><strong>Best Used For:</strong> Adding conflict sources, making settings feel dynamic and dangerous, worldbuilding environmental challenges. Requires region description.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F1.15">
                            <p>15. Act as a World Detail Consistency Checker: Review these two worldbuilding details from the Story Bible: "[Detail A]" and "[Detail B]". Are they logically consistent with each other and the world's established rules? If not, explain the inconsistency and suggest a way to reconcile them.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Analyzes specific worldbuilding elements for potential contradictions or logical conflicts.</p>
                                <p><strong>Best Used For:</strong> Maintaining world bible consistency, identifying potential plot holes early, refining world rules. Requires two potentially conflicting details.</p>
                            </div>
                        </div>
                    </div>
                </details>

                <details id="F2">
                    <summary>F2: Cultural & Social Extrapolation (Context-Based)</summary>
                    <div>
                        <!-- SECTION SYSTEM PROMPT START - SECTION_ID: F2 -->
                        <div class="system-prompt-block">
                             <h4>System Instruction</h4>
                             <p><strong>Context:</strong> Contextual Generation - Culture & Society</p>
                             <p>Adopt the persona of a <strong>Fictional Sociologist and Cultural Anthropologist</strong>. Focus on extrapolating realistic and interesting cultural practices, social dynamics, subcultures, laws, and beliefs based on the established societal context in the Story Bible.</p>
                             <p><strong>Internal Steps:</strong> Identify source cultural/societal element. Analyze its implications based on world context. Generate plausible rituals, taboos, subcultures, laws, sayings, reactions, or artifacts that logically extend from the source. Explain the connection. Ensure generated elements add depth and narrative potential.</p>
                             <p>Aim to build richer, more believable, and internally diverse societies by extrapolating logically from established foundations.</p>
                        </div>
                        <!-- SECTION SYSTEM PROMPT END - SECTION_ID: F2 -->
                         <div class="prompt-container" id="F2.1">
                             <p>1. Act as a Cultural Ritual Designer: Based on the core values "[Value 1], [Value 2]" of [Culture Name], design a plausible social ritual or festival celebrating one of these values. Describe the key activities, participants, symbolism, and time of year.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates specific cultural practices (rituals, festivals) that logically reflect a society's stated values.</p>
                                <p><strong>Best Used For:</strong> Adding cultural depth and flavor, worldbuilding social customs, creating setting details for scenes. Requires culture name and core values.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F2.2">
                             <p>2. Act as a Social Taboo Explorer: The culture of [Society Name] has a strong taboo against "[Taboo Subject]". Generate 3 plausible social consequences or narrative scenarios that arise when a character (intentionally or accidentally) breaks this taboo.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Explores the narrative potential and social implications of violating a specific cultural prohibition.</p>
                                <p><strong>Best Used For:</strong> Generating social conflict, exploring cultural themes, creating character challenges. Requires society name and taboo subject.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F2.3">
                             <p>3. Act as a Subculture Generator: Within the larger society of [Society Name], propose 3 distinct subcultures that might realistically exist based on factors like profession, region, differing beliefs, or reaction against mainstream norms. Briefly describe each subculture's key characteristics and relationship with the dominant culture.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates internal diversity within a larger fictional society, making it feel less monolithic.</p>
                                <p><strong>Best Used For:</strong> Adding social complexity, creating sources of internal conflict/alliance, worldbuilding diverse populations. Requires society name/description.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F2.4">
                             <p>4. Act as a Proverb/Saying Creator: Generate 5 proverbs or common sayings that would likely exist in [Culture Name], reflecting their established history, values ([Value]), and environment ([Environment Type]).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates snippets of folk wisdom or common phrases that add linguistic and cultural flavor.</p>
                                <p><strong>Best Used For:</strong> Enhancing cultural voice, worldbuilding linguistic details, adding realism to dialogue. Requires culture name, values, environment.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F2.5">
                             <p>5. Act as a Cultural Reaction Predictor: An unprecedented event, "[Event Description]", occurs in [World Name]. How would the members of [Culture A] (Values: [List]) likely react compared to members of [Culture B] (Values: [List])? Describe the differing interpretations, emotional responses, and likely actions based on their cultural backgrounds.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Predicts differing cultural responses to the same event based on established societal values and norms.</p>
                                <p><strong>Best Used For:</strong> Generating realistic intercultural reactions, exploring cultural themes, creating plot points based on differing perspectives. Requires event and culture descriptions.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F2.6">
                             <p>6. Act as a Legal System Quirks Generator: Based on the history and core principles of the legal system in [Nation Name], generate 3 unique or quirky laws, legal procedures, or forms of punishment that logically derive from that context but might seem strange to an outsider.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates specific, memorable legal details that reflect the unique history or values of a fictional society.</p>
                                <p><strong>Best Used For:</strong> Adding flavor to legal/political worldbuilding, creating unique plot obstacles or procedures, enhancing setting distinctiveness. Requires nation/legal system context.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F2.7">
                             <p>7. Act as a Social Hierarchy Nuance Explorer: The social structure of [Society] is defined as [Basic Structure, e.g., Caste System, Meritocracy]. Explore 3 nuances or exceptions to the general rule (e.g., a loophole allowing limited mobility, a specific group that exists outside the main hierarchy, informal power structures that contradict the formal one).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Adds complexity and realism to a defined social structure by introducing exceptions and informal elements.</p>
                                <p><strong>Best Used For:</strong> Making social systems more believable, creating specific character backgrounds or conflicts, refining worldbuilding. Requires society and structure description.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F2.8">
                             <p>8. Act as a Fashion Trend Forecaster (Fiction): Based on the current technology level, climate, and cultural values of [Society Name], describe 3 plausible fashion trends that might emerge among different social groups (e.g., youth, elite, working class) in the next 5-10 years of the story's timeline.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates believable near-future fashion concepts grounded in the world's context.</p>
                                <p><strong>Best Used For:</strong> Adding visual detail to worldbuilding, showing passage of time, reflecting social status/group identity. Requires society details.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F2.9">
                             <p>9. Act as a Propaganda Theme Designer: The ruling power in [Nation] wants to promote [Ideology/Goal]. Design 3 distinct propaganda themes or slogans they might use, tailored to appeal to (or manipulate) the known values and fears of the populace described in the Story Bible.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates plausible propaganda messages reflecting the goals of a ruling power and the psychology of its populace.</p>
                                <p><strong>Best Used For:</strong> Worldbuilding political control mechanisms, exploring themes of manipulation, creating atmospheric details. Requires nation, goal, populace info.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F2.10">
                             <p>10. Act as a Cross-Cultural Misunderstanding Generator: Generate 3 plausible scenarios where a simple action or phrase by someone from [Culture A] would be significantly misinterpreted (leading to offense, humor, or conflict) by someone from [Culture B], based on their differing customs and communication styles outlined in the Story Bible.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates specific examples of intercultural friction based on defined cultural differences.</p>
                                <p><strong>Best Used For:</strong> Generating conflict/comedy from cultural clashes, highlighting cultural themes, creating realistic intercultural interactions. Requires descriptions of Culture A and B.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F2.11">
                             <p>11. Act as a Tradition Evolution Explorer: A long-standing tradition in [Culture Name] is "[Tradition Description]". How might this tradition plausibly evolve or change over 50 years due to [Influencing Factor, e.g., new technology, contact with another culture, environmental shift]? Describe the modified tradition.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Models how cultural practices can adapt or change over time while retaining some core elements.</p>
                                <p><strong>Best Used For:</strong> Worldbuilding dynamic cultures, showing passage of time, exploring themes of tradition vs modernity. Requires culture, tradition, influencing factor.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F2.12">
                             <p>12. Act as an Informal Economy Designer: In the city of [City Name], where formal regulations are [Strict/Lax], describe 3 types of informal economies or black markets that might plausibly arise to meet unmet needs or circumvent restrictions (e.g., smuggling specific goods, unlicensed service providers, information brokers).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates believable underground economic activities based on the formal systems and needs of a setting.</p>
                                <p><strong>Best Used For:</strong> Adding grit and realism to urban settings, generating underworld plot hooks, worldbuilding economic layers. Requires city context.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F2.13">
                             <p>13. Act as a Social Consequence of Magic/Tech Analyst: The magic/technology "[Name]" allows users to "[Function]". Explore 3 non-obvious social consequences this ability might have on relationships, community trust, or power dynamics within the society described.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Analyzes the subtle social ripple effects of a specific magical or technological capability within the world.</p>
                                <p><strong>Best Used For:</strong> Deepening the integration of magic/tech, exploring societal themes, generating nuanced conflict. Requires magic/tech description and society context.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F2.14">
                             <p>14. Act as a Minority Group Experience Conceptualizer: Within the dominant culture of [Society Name], describe the likely social position, common prejudices faced, and unique cultural adaptations of a minority group: "[Minority Group Description]". Ensure this is grounded in the logic of the established society.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates a plausible portrayal of a minority group's experience within a larger fictional society.</p>
                                <p><strong>Best Used For:</strong> Creating diverse and realistic societies, exploring themes of prejudice and identity, developing specific character backgrounds. Requires society and minority group descriptions.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F2.15">
                             <p>15. Act as a Cultural Artifact Generator: Design 3 mundane cultural artifacts (e.g., a common toy, a type of eating utensil, a popular board game) specific to [Culture Name] that reflect their values, environment, or history.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates small, everyday objects that reveal details about a fictional culture.</p>
                                <p><strong>Best Used For:</strong> Adding texture and realism to worldbuilding, providing props for scenes, showing culture implicitly. Requires culture description.</p>
                            </div>
                        </div>
                    </div>
                </details>

                <details id="F3">
                    <summary>F3: Character & Narrative Implication (Context-Based)</summary>
                     <div>
                        <!-- SECTION SYSTEM PROMPT START - SECTION_ID: F3 -->
                        <div class="system-prompt-block">
                             <h4>System Instruction</h4>
                             <p><strong>Context:</strong> Contextual Generation - Character & Narrative</p>
                             <p>Adopt the persona of a <strong>Narrative Catalyst and Character Analyst</strong>. Focus on exploring the narrative implications of established character traits, relationships, skills, flaws, and plot points from the Story Bible.</p>
                             <p><strong>Internal Steps:</strong> Identify source character/narrative element. Analyze its potential interaction with other established elements (plot, theme, other characters, world rules). Generate plausible consequences, conflicts, resonant moments, or alternative paths stemming from these interactions. Explain the causal links. Ensure generated ideas enhance character depth or narrative drive.</p>
                             <p>Aim to uncover deeper narrative potential and ensure character actions/traits have meaningful consequences within the story.</p>
                        </div>
                        <!-- SECTION SYSTEM PROMPT END - SECTION_ID: F3 -->
                        <div class="prompt-container" id="F3.1">
                             <p>1. Act as a Character Archetype Synergist: The protagonist ([Protagonist Description]) fits the [Archetype A] archetype, while the antagonist ([Antagonist Description]) fits [Archetype B]. Based on these archetypes and their specific goals from the Story Bible, generate 3 potential thematic conflicts or ironic situations that could arise specifically from the interaction of these two archetypal roles.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Explores the inherent dramatic potential arising from the clash or synergy of specific character archetypes in the story.</p>
                                <p><strong>Best Used For:</strong> Deepening thematic conflict, planning character interactions, ensuring archetypes serve the narrative actively. Requires character descriptions/archetypes.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="F3.2">
                             <p>2. Act as a Backstory Resonance Finder: Given [Character]'s key backstory event "[Event Description]", suggest 3 specific ways this past event could directly influence their decisions, fears, or relationships in the *present* plot outlined in the Story Bible.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Connects a character's past explicitly to their present actions and reactions within the plot.</p>
                                <p><strong>Best Used For:</strong> Making backstories relevant, deepening character motivation, creating internal conflict based on past trauma. Requires character and event description, plot context.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="F3.3">
                             <p>3. Act as a Skill/Ability Consequence Explorer: The character [Name] possesses the unique skill/ability "[Skill Description]". Generate 3 non-obvious narrative consequences or limitations stemming from this ability within the world's rules (e.g., social stigma, resource cost, psychological toll, attracts specific enemies, unforeseen interaction with other magic/tech).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Explores the downsides, costs, or unexpected implications of a character's special abilities, adding realism and conflict.</p>
                                <p><strong>Best Used For:</strong> Balancing powerful characters, creating unique challenges, grounding fantastical elements. Requires character name and skill description.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F3.4">
                             <p>4. Act as a Flaw Manifestation Scenarist: [Character]'s major flaw is "[Flaw Description]". Create 3 brief scene concepts where this specific flaw directly causes a setback, complicates a relationship, or leads them to make a poor decision relevant to the plot outline.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates specific plot moments where a character's defined weakness actively creates problems.</p>
                                <p><strong>Best Used For:</strong> Making character flaws impactful, generating conflict, driving character arcs through failure. Requires character and flaw description, plot context.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F3.5">
                             <p>5. Act as a Relationship Stress Tester: Consider the relationship between [Character A] and [Character B] ([Relationship Description]). Introduce a hypothetical stressor "[Stressor Event]". How would their relationship dynamics likely change? Would they grow closer, break apart, betray each other? Justify based on their established personalities.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Simulates how an established character relationship might react under pressure, testing its strength and nature.</p>
                                <p><strong>Best Used For:</strong> Developing relationship arcs, creating interpersonal conflict, testing character loyalty/dynamics. Requires character/relationship descriptions and stressor event.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F3.6">
                             <p>6. Act as a "Road Not Taken" Explorer (Character): At [Key Decision Point] in the outline, [Character Name] chose [Action A]. Briefly explore the plausible alternative narrative path if they had instead chosen [Action B], focusing on the immediate character and plot consequences.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates a brief alternate scenario based on a character making a different choice at a critical moment.</p>
                                <p><strong>Best Used For:</strong> Understanding the significance of character choices, exploring alternative plotlines (briefly), reinforcing the chosen path's logic. Requires decision point, character, actions.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F3.7">
                             <p>7. Act as a Secret Revelation Impact Analyst: A character is hiding the secret "[Secret Description]". Predict 3 different ways this secret could be revealed during the story, and analyze the potential impact of each revelation method on the character and plot.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Brainstorms different ways a character's secret could come to light and analyzes the dramatic consequences of each method.</p>
                                <p><strong>Best Used For:</strong> Planning plot twists involving secrets, maximizing the impact of revelations, creating suspense. Requires the secret.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F3.8">
                             <p>8. Act as a Goal Conflict Generator: [Character A]'s goal is "[Goal A]", while [Character B]'s goal is "[Goal B]". Based on their methods and personalities, generate 3 specific scenarios where their goals inevitably bring them into direct conflict, even if they aren't primary antagonists.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates specific conflict scenarios arising naturally from the differing objectives of two characters.</p>
                                <p><strong>Best Used For:</strong> Generating subplots, creating dynamic character interactions, adding layers of conflict. Requires character goals.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F3.9">
                             <p>9. Act as a Mentor/Protégé Dynamic Explorer: Define the mentor-protégé relationship between [Mentor Name] and [Protégé Name]. Generate 3 potential challenges or turning points in their relationship arc (e.g., disillusionment, mentor failure, protégé surpassing mentor, ethical disagreement).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Explores common arcs and conflict points within a specific relationship archetype (mentor-protégé).</p>
                                <p><strong>Best Used For:</strong> Planning relationship development, creating specific scenes for mentor/protégé interactions, adding depth to this dynamic.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F3.10">
                             <p>10. Act as a Narrative Theme Embodiment Analyst: The story's theme is "[Theme]". How does the protagonist's specific journey/arc ([Arc Summary]) embody or challenge this theme? Identify 2 key moments in their arc that most strongly resonate with the theme.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Analyzes the connection between a character's specific journey and the story's overarching theme.</p>
                                <p><strong>Best Used For:</strong> Ensuring thematic coherence, strengthening the link between plot and theme, analyzing character function. Requires theme and arc summary.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="F3.11">
                            <p>11. Act as an Internal Monologue Generator (Key Moment): Write a brief internal monologue for [Character Name] during the specific plot event "[Event Description]", revealing their immediate thoughts, fears, and rationalizations consistent with their established personality and the situation.</p>
                            <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates a snapshot of a character's inner thoughts during a critical moment, enhancing psychological depth.</p>
                                <p><strong>Best Used For:</strong> Exploring character perspective, adding emotional depth to scenes, developing character voice. Requires character, event.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="F3.12">
                            <p>12. Act as a Dialogue Style Consistency Check: Review these two dialogue excerpts spoken by [Character Name] from different parts of the Story Bible: "[Excerpt 1]", "[Excerpt 2]". Are the voice, vocabulary, and sentence structure consistent? If not, identify inconsistencies and suggest how to align them.</p>
                            <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Analyzes dialogue samples for consistency in a character's established voice across different contexts.</p>
                                <p><strong>Best Used For:</strong> Editing dialogue for consistency, maintaining character voice throughout a manuscript, refining characterization. Requires character name and excerpts.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F3.13">
                            <p>13. Act as a "Character Comfort Zone" Challenger: Identify [Character Name]'s primary comfort zone (e.g., relying on logic, avoiding confrontation, staying hidden). Design a specific plot scenario that forces them far outside this comfort zone and requires them to act in an uncharacteristic way to succeed.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates plot challenges specifically designed to push a character beyond their usual behaviors and limitations.</p>
                                <p><strong>Best Used For:</strong> Driving character development, creating high-stakes situations, testing character limits. Requires character comfort zone.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F3.14">
                            <p>14. Act as a Symbolic Action Generator: Suggest 3 symbolic actions [Character Name] could perform during the climax or resolution that visually represent their completed character arc or the story's final theme.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Brainstorms meaningful actions characters can take that have symbolic weight beyond their literal function.</p>
                                <p><strong>Best Used For:</strong> Enhancing thematic resonance, creating memorable ending moments, showing character change visually. Requires character arc/theme.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="F3.15">
                            <p>15. Act as a Supporting Cast Narrative Function Assessor: For supporting character [Name], what is their primary narrative function in relation to the protagonist (e.g., foil, mentor, ally, comic relief, catalyst)? Suggest a scene idea that highlights this function effectively.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Analyzes the role and purpose of a supporting character within the narrative structure.</p>
                                <p><strong>Best Used For:</strong> Ensuring supporting characters have purpose, refining character roles, streamlining cast functions. Requires character name.</p>
                            </div>
                        </div>
                    </div>
                 </details>
            </div>
        </details> <!-- End Section F -->

        <!-- Insert drafted Section G here -->
        <details id="G">
            <summary>G: Magic Systems, Spells & Enchanted Items</summary>
            <div>
                 <!-- SECTION SYSTEM PROMPT START - SECTION_ID: G -->
                <div class="system-prompt-block">
                    <h4>System Instruction</h4>
                    <p><strong>Context:</strong> Magic Systems, Spells & Enchanted Items</p>
                    <p>Adopt the persona of an <strong>Arcane Systems Architect and Enchantment Theorist</strong> unless an <strong>'Act as...'</strong> role (e.g., Spellcrafter, Artifact Historian) or <code>((Expert Role/Focus))</code> is specified.</p>
                    <p><strong>Internal Steps (Consider these when responding):</strong></p>
                    <ul>
                        <li>Identify the task: designing system rules, creating spells/items, analyzing consistency, exploring implications.</li>
                        <li>Reference and adhere strictly to the established magic system rules, limitations, costs, and world context provided or found in the Story Bible.</li>
                        <li>Focus on generating creative yet **logically consistent** magical effects, items, or system refinements.</li>
                        <li>Define clear properties, functions, limitations, costs, and potential side effects for generated spells/items.</li>
                        <li>Explore the narrative function and potential plot hooks associated with magical elements.</li>
                        <li>Analyze existing magical elements for internal consistency and plausible integration into the world.</li>
                    </ul>
                    <p>Focus on the creative generation, logical refinement, and consistent application of magical elements within the established fictional reality. Aim for originality grounded in the world's arcane framework.</p>
                </div>
                 <!-- SECTION SYSTEM PROMPT END - SECTION_ID: G -->

                <details id="G1">
                    <summary>G1: Magic System Design & Refinement</summary>
                    <div>
                        <div class="prompt-container" id="G1.1">
                             <p>1. Act as a Magic System Architect: Design a core magic system for a [Genre] setting based on [Core Concept, e.g., drawing power from emotions, manipulating fundamental forces, symbiotic pacts]. Define its source of power, basic principles of use, general limitations, and overall feel (e.g., hard vs. soft, common vs. rare).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates the foundational framework for a new magic system based on a core idea.</p>
                                <p><strong>Best Used For:</strong> Initial worldbuilding, creating the fundamental rules for magic in a new setting. Requires genre and core concept.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="G1.2">
                             <p>2. Act as a Magic System Rule Refiner: Review the established magic system "[System Name]" in the Story Bible. Define 3 specific, nuanced rules or limitations that add depth and prevent it from being overly powerful or easily exploitable (e.g., requires specific components, has emotional/physical costs, effectiveness varies by location/time).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Adds specific constraints and costs to an existing magic system to enhance realism and create narrative challenges.</p>
                                <p><strong>Best Used For:</strong> Balancing magic systems, adding depth, creating limitations for plot purposes. Requires existing system description.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="G1.3">
                             <p>3. Act as an Arcane Theorist (Consistency Check): Analyze the rules for "[Magic System A]" and "[Magic System B]" described in the Story Bible. Identify 2 potential areas of contradiction, logical inconsistency, or undefined interaction between these systems. Suggest ways to reconcile them.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Examines the interaction between different magic systems or rules within the same world for logical coherence.</p>
                                <p><strong>Best Used For:</strong> Ensuring worldbuilding consistency, preventing plot holes related to magic interactions, refining complex magic frameworks. Requires descriptions of the systems.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G1.4">
                             <p>4. Act as a Magic Source Detailer: The source of magic in this world is "[Source Description, e.g., ley lines, cosmic radiation, divine entities]". Elaborate on this source: Is it finite or infinite? Is access restricted? Does using it have environmental or personal consequences? How is it perceived by different cultures?</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Adds depth and detail to the origin and nature of magical power within the world.</p>
                                <p><strong>Best Used For:</strong> Deepening magic system lore, creating plot points related to the magic source, explaining limitations. Requires source description.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G1.5">
                             <p>5. Act as a Magic Skill Progression Designer: Outline a plausible progression system for learning magic within "[Magic System Name]". Define stages of learning (e.g., apprentice, adept, master), key skills acquired at each stage, and typical training methods used in [Society Name].</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates a structured path for how characters learn and improve their magical abilities within the world.</p>
                                <p><strong>Best Used For:</strong> Worldbuilding magical education, planning character skill development, adding realism to magic acquisition. Requires system and society names.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="G1.6">
                             <p>6. Act as a Counter-Magic Conceptualizer: Based on the strengths and mechanics of "[Magic System Name]", design 3 plausible methods or forms of counter-magic/magic resistance that could exist in the world (e.g., specific materials, null-magic zones, cancelling frequencies, opposing magical disciplines).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates ways to oppose or defend against the established magic system, creating balance and conflict.</p>
                                <p><strong>Best Used For:</strong> Balancing powerful magic, creating specific challenges for magic users, designing anti-magic factions or items. Requires system description.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G1.7">
                             <p>7. Act as a Forbidden Magic Architect: Define a specific school or type of magic considered "forbidden" within the context of "[Magic System Name]" and [Society Name]. Explain *why* it's forbidden (e.g., ethical reasons, uncontrollable power, societal disruption), its specific effects, and the consequences for practitioners.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates a specific type of taboo magic, defining its nature and societal implications.</p>
                                <p><strong>Best Used For:</strong> Adding dark elements to magic systems, creating specific villain motivations or protagonist temptations, generating moral conflicts. Requires system and society context.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G1.8">
                             <p>8. Act as a Magic System Visual Language Designer: Describe the typical visual manifestations or 'tells' associated with casting magic from "[Magic System Name]" (e.g., glowing runes, specific hand gestures, colored energy, environmental effects). Ensure variety for different power levels or types of spells.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Defines the common visual effects associated with magic use, adding sensory detail and consistency.</p>
                                <p><strong>Best Used For:</strong> Enhancing descriptive writing of magic, providing visual cues for readers/artists, making magic feel tangible. Requires system name.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G1.9">
                             <p>9. Act as a Magic Cost Analyst: Beyond mana/stamina, brainstorm 3 less common but plausible costs associated with using magic from "[Magic System Name]" (e.g., memory loss, shortened lifespan, emotional numbing, attracting specific entities, environmental decay nearby).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates unique and meaningful drawbacks or consequences for using magic, adding depth and stakes.</p>
                                <p><strong>Best Used For:</strong> Balancing magic, adding narrative cost to power, creating unique character challenges. Requires system name.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G1.10">
                             <p>10. Act as a Magic System Origin Myth Creator: Write a short in-world myth or legend explaining the origin of magic (or "[Specific Magic System]") as it might be told by the people of [Culture Name].</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates diegetic lore explaining the source or history of magic within the world's cultural context.</p>
                                <p><strong>Best Used For:</strong> Worldbuilding lore, adding cultural depth, providing in-game text or backstory elements. Requires system/culture name.</p>
                            </div>
                        </div>
                    </div>
                </details>

                <details id="G2">
                    <summary>G2: Spell Generation & Application</summary>
                    <div>
                         <!-- SECTION SYSTEM PROMPT START - SECTION_ID: G2 -->
                         <div class="system-prompt-block">
                             <h4>System Instruction</h4>
                             <p><strong>Context:</strong> Magic Systems - Spell Generation & Application</p>
                             <p>Adopt the persona of a <strong>Spellcrafter and Arcane Tactician</strong>. Focus on designing specific spells consistent with the established magic system (G1) and exploring their creative/tactical applications.</p>
                             <p><strong>Internal Steps:</strong> Generate spells adhering to system rules (source, cost, limits). Define spell effects, range, duration clearly. Describe visual/sensory details. Explore unconventional uses and combinations. Design rituals, counter-spells, or failure conditions as requested. Ensure spells fit the world context.</p>
                             <p>Aim to create interesting, balanced, and narratively useful spells and magical effects.</p>
                         </div>
                         <!-- SECTION SYSTEM PROMPT END - SECTION_ID: G2 -->
                         <div class="prompt-container" id="G2.1">
                             <p>1. Act as a Spellcrafter (Core Spells): Design 5 core spells (2 offensive, 2 defensive, 1 utility) for the "[Magic System Name]" based on its established principles. For each, define its name, effect, range, duration, casting requirement/cost, and a brief visual description.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates a balanced set of fundamental spells consistent with the defined magic system rules.</p>
                                <p><strong>Best Used For:</strong> Populating a magic system with basic abilities, defining common magic use, creating character spell lists. Requires system name/principles.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G2.2">
                             <p>2. Act as an Arcane Innovator (Creative Spell Use): Take the existing spell "[Spell Name]" (Effect: [Description]). Describe 3 unconventional or highly creative ways this spell could be used for purposes other than its obvious primary function, leveraging the world's rules and environment.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Explores non-standard applications of existing spells, encouraging clever problem-solving within the magic system.</p>
                                <p><strong>Best Used For:</strong> Generating clever character moments, making magic feel versatile, finding unique solutions to plot problems. Requires spell description.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G2.3">
                             <p>3. Act as a Ritual Magic Designer: Design a complex magical ritual within the "[Magic System Name]" framework intended to achieve [Significant Effect, e.g., ward a city, summon an entity, divine the future]. Specify necessary components, number of participants, required time, potential risks/failure conditions, and sensory details of the ritual process.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates detailed descriptions for large-scale, complex magical workings involving multiple steps and components.</p>
                                <p><strong>Best Used For:</strong> Designing climactic magical events, worldbuilding high-magic practices, creating intricate plot devices. Requires system name and desired effect.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G2.4">
                             <p>4. Act as a Spell Sensory Effect Artist: Describe the detailed sensory effects (visual, auditory, tactile, olfactory if applicable) of casting and impacting with the spell "[Spell Name]" from the Story Bible. Focus on making the experience vivid and unique.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates rich, multi-sensory descriptions for specific spells, enhancing written depictions.</p>
                                <p><strong>Best Used For:</strong> Improving prose for magic scenes, making spells feel impactful, providing clear visual/audio cues. Requires spell name/basic effect.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G2.5">
                             <p>5. Act as a Spell Failure Generator: What are 3 plausible ways the spell "[Spell Name]" could fail or backfire, based on the rules of "[Magic System Name]"? Describe the resulting unintended effect for each failure mode.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Brainstorms specific negative consequences or misfires for spellcasting, adding risk and unpredictability.</p>
                                <p><strong>Best Used For:</strong> Creating tension in magic use, generating plot complications, defining the risks of magic. Requires spell and system names.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G2.6">
                             <p>6. Act as a Low-Magic Utility Spell Creator: Design 5 simple, low-cost utility spells within "[Magic System Name]" that would be commonly used in everyday life by non-adventurers in [Society Name] (e.g., mending small tears, lighting a lamp, purifying water, finding lost keys).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates common, practical magic that integrates into the daily lives of ordinary people in the setting.</p>
                                <p><strong>Best Used For:</strong> Making magic feel integrated into the world, worldbuilding everyday life, creating minor conveniences/tools. Requires system and society names.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G2.7">
                             <p>7. Act as a Spell Combination Synergist: Suggest 2-3 interesting synergistic combinations using existing spells "[Spell A]", "[Spell B]", (and "[Spell C]") from the Story Bible. Describe the combined effect and potential tactical applications.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Explores how existing spells might be used together for enhanced or novel effects.</p>
                                <p><strong>Best Used For:</strong> Designing advanced magic tactics, creating clever character solutions, making magic systems feel deeper. Requires existing spell names/effects.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G2.8">
                             <p>8. Act as a Counter-Spell Designer: Design a specific counter-spell intended to negate or disrupt the effects of "[Target Spell Name]". Define its casting method, limitations, and visual/auditory interaction when it successfully counters the target spell.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates a specific spell designed explicitly to interfere with another defined spell.</p>
                                <p><strong>Best Used For:</strong> Designing magical defenses, creating tactical options in magic duels, balancing powerful spells. Requires target spell name.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G2.9">
                             <p>9. Act as a Lost or Ancient Spell Rediscoverer: Design a powerful spell "[Spell Name]" from a "lost" or "ancient" era of the world's history (based on Story Bible lore). Describe its potent effect, why it might have been lost or forbidden, and the difficulty/danger involved in rediscovering or casting it now.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates a specific piece of powerful, historical magic tied to the world's lore, often serving as a plot device.</p>
                                <p><strong>Best Used For:</strong> Creating MacGuffins, designing ancient mysteries, adding powerful but rare magic elements. Requires world history context.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G2.10">
                             <p>10. Act as a Spell Variant Generator (Environmental): How might the spell "[Spell Name]" manifest differently or have altered effects if cast in "[Environment A, e.g., underwater]" versus "[Environment B, e.g., high-altitude desert]"? Describe 2 key differences based on environmental interaction.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Explores how environmental conditions could plausibly affect the outcome or manifestation of a specific spell.</p>
                                <p><strong>Best Used For:</strong> Adding tactical depth to magic use, making environments interact with magic, creating situational challenges/advantages. Requires spell name and environments.</p>
                            </div>
                        </div>
                    </div>
                </details>

                <details id="G3">
                    <summary>G3: Enchanted Item Creation & Integration</summary>
                     <div>
                         <!-- SECTION SYSTEM PROMPT START - SECTION_ID: G3 -->
                         <div class="system-prompt-block">
                             <h4>System Instruction</h4>
                             <p><strong>Context:</strong> Magic Systems - Enchanted Items</p>
                             <p>Adopt the persona of an <strong>Artificer and Artifact Lore Master</strong>. Focus on designing unique enchanted items, developing their history, assessing their properties, and exploring their integration into the world based on Story Bible context.</p>
                             <p><strong>Internal Steps:</strong> Design items with clear functions, drawbacks, and activation methods consistent with G1 rules. Create plausible histories and cultural significance. Assess found items based on world context. Design cursed items. Brainstorm mundane enchantments. Ensure item aesthetics fit cultural origins.</p>
                             <p>Aim to create memorable, balanced, and narratively significant magical items that enhance the worldbuilding and plot.</p>
                         </div>
                         <!-- SECTION SYSTEM PROMPT END - SECTION_ID: G3 -->
                        <div class="prompt-container" id="G3.1">
                             <p>1. Act as an Enchanter (Item Design): Design a unique enchanted item: "[Item Type, e.g., amulet, boots, ring]" named "[Item Name Suggestion]". Define its primary magical property/function, a specific drawback or activation condition, its visual appearance reflecting [Culture]'s craftsmanship, and basic lore/origin.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates a complete concept for a new enchanted item, including power, cost, appearance, and background.</p>
                                <p><strong>Best Used For:</strong> Creating unique magical treasures, designing character equipment, populating world with magical artifacts. Requires item type, potential name, cultural context.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="G3.2">
                             <p>2. Act as an Artifact Historian: Generate a plausible history and lineage for the significant artifact "[Artifact Name]" mentioned in the Story Bible. Describe its creation, previous owners, notable deeds associated with it, and how it ended up in its current state/location.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates a detailed backstory for an existing magical item, adding lore and significance.</p>
                                <p><strong>Best Used For:</strong> Deepening the lore of important items, providing plot hooks related to artifact history, enriching worldbuilding. Requires artifact name.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="G3.3">
                             <p>3. Act as a Magical Item Appraiser: This item "[Item Description]" is found. Based on the world's magic rules (G1) and common enchantments, assess its likely function, potential power level (minor, moderate, major artifact), possible creator/origin culture, and any visible clues about its use or dangers.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Analyzes a description of a found magical item to deduce its properties and significance within the world's context.</p>
                                <p><strong>Best Used For:</strong> Identifying found loot, creating mystery around artifacts, integrating items logically into the world. Requires item description and world context.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G3.4">
                             <p>4. Act as a Cursed Item Creator: Design a cursed magical item "[Item Name]" that offers a tempting benefit "[Benefit]" but carries a significant, non-obvious curse "[Curse Description]". Explain how the curse manifests and the difficulty of removing it.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates magical items with detrimental effects, creating plot complications and moral dilemmas.</p>
                                <p><strong>Best Used For:</strong> Creating dangerous plot devices, adding risk to magic items, designing unique challenges. Requires benefit and curse concepts.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G3.5">
                             <p>5. Act as a Mundane Enchantment Brainstormer: Brainstorm 5 types of minor, common enchantments that might be applied to everyday objects in [Magical Society Name] to improve daily life (e.g., self-cleaning clothes, ever-sharp tools, light-emitting stones, temperature-regulating blankets).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates ideas for low-level, common magic integrated into everyday objects and routines.</p>
                                <p><strong>Best Used For:</strong> Making magic feel commonplace and integrated, worldbuilding daily life in magical settings, adding flavor details. Requires society name.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="G3.6">
                             <p>6. Act as an Item Synergy Designer: Suggest an interesting synergy or combined effect if "[Enchanted Item A]" and "[Enchanted Item B]" (from Story Bible) were used together by the same person.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Explores potential interactions between existing magical items, creating new possibilities or dangers.</p>
                                <p><strong>Best Used For:</strong> Designing advanced character builds, creating unexpected plot twists related to items, making item choices more strategic. Requires item descriptions.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G3.7">
                             <p>7. Act as an Artifact Activation Method Designer: The powerful artifact "[Artifact Name]" requires a specific, non-obvious method to activate its true power. Design 3 potential activation methods (e.g., requires a specific bloodline, needs to be used at a certain location/time, requires a specific emotional state, needs a forgotten command word).</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates unique and challenging requirements for using powerful magical items, adding obstacles for characters.</p>
                                <p><strong>Best Used For:</strong> Designing quests around artifacts, adding mystery and challenge to powerful items, creating plot gates. Requires artifact name.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G3.8">
                             <p>8. Act as a Sentient Item Personality Crafter: Design a basic personality, motivation, and communication method for a sentient magical item "[Item Name/Type]". How does its sentience affect its function or its relationship with its wielder?</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates a personality and goals for an intelligent magical item, turning it into a character.</p>
                                <p><strong>Best Used For:</strong> Designing unique companions/guides, creating sentient artifacts with agency, adding character dynamics through items. Requires item name/type.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G3.9">
                             <p>9. Act as a Magic Item Aesthetic Unifier: Review the descriptions of several magical items crafted by "[Culture/Group Name]" in the Story Bible. Define 3 recurring aesthetic motifs, materials, or design principles that visually unify items from this source.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Analyzes existing item descriptions to establish a consistent visual style for a specific cultural or magical tradition.</p>
                                <p><strong>Best Used For:</strong> Ensuring visual consistency in worldbuilding, defining cultural aesthetics, guiding artists. Requires item descriptions and source name.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G3.10">
                             <p>10. Act as a Limited-Use Consumable Item Generator: Design 5 different single-use or limited-charge magical consumable items (e.g., potions, scrolls, enchanted tokens) consistent with "[Magic System Name]". Define their effect, usage method, and relative rarity/cost.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates common magical items that offer temporary effects, often used in RPGs or as minor plot devices.</p>
                                <p><strong>Best Used For:</strong> Populating shops/loot tables, providing temporary solutions for characters, adding variety to magic use. Requires magic system context.</p>
                            </div>
                        </div>
                    </div>
                </details>

                <details id="G4">
                    <summary>G4: Magic Integration & World Impact</summary>
                    <div>
                         <!-- SECTION SYSTEM PROMPT START - SECTION_ID: G4 -->
                         <div class="system-prompt-block">
                             <h4>System Instruction</h4>
                             <p><strong>Context:</strong> Magic Systems - World Impact & Integration</p>
                             <p>Adopt the persona of a <strong>Socio-Magical Analyst and World Integration Specialist</strong>. Focus on exploring how the established magic systems (G1), spells (G2), and items (G3) realistically impact the society, economy, culture, military, and daily life within the world defined in the Story Bible.</p>
                             <p><strong>Internal Steps:</strong> Analyze specific magic elements. Extrapolate societal consequences (power structures, economy, law, culture). Conceptualize magitek blending magic/tech. Model magic's impact on warfare/military tactics. Describe integration into daily life. Explore anti-magic sentiment or regulation.</p>
                             <p>Aim to ensure the magical elements feel deeply integrated into the fabric of the world, creating plausible consequences and narrative opportunities.</p>
                         </div>
                         <!-- SECTION SYSTEM PROMPT END - SECTION_ID: G4 -->
                        <div class="prompt-container" id="G4.1">
                             <p>1. Act as a Socio-Magical Analyst: How does the existence and accessibility of "[Specific Magic Type/System]" fundamentally alter the power structure, economy, and social hierarchy of [Society Name] compared to a non-magical equivalent?</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Analyzes the broad societal transformations caused by the presence of a specific form of magic.</p>
                                <p><strong>Best Used For:</strong> Deep worldbuilding, ensuring magic has realistic societal impact, exploring themes related to power and inequality. Requires magic type and society details.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="G4.2">
                             <p>2. Act as a Magitek Conceptualizer: Combine the principles of "[Magic System Name]" with the technology level of "[Tech Era, e.g., steampunk, cyberpunk]" in [Society Name]. Brainstorm 3 plausible examples of "magitek"—devices or systems blending magic and technology—and describe their function and appearance.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Generates ideas for technology powered or enhanced by the world's magic system.</p>
                                <p><strong>Best Used For:</strong> Designing unique technology for fantasy/sci-fi settings, creating magitek items/infrastructure, blending genre elements. Requires magic system and tech level context.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="G4.3">
                             <p>3. Act as a Military Magic Strategist: How would the widespread availability of "[Combat Spell/Magic Type]" change military tactics, fortifications, and the nature of warfare for the armies of [Nation Name] described in the Story Bible?</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Explores the impact of specific magical abilities on military doctrine and battlefield realities.</p>
                                <p><strong>Best Used For:</strong> Worldbuilding military forces in magical settings, designing realistic magic-infused warfare, creating tactical challenges. Requires spell/magic type and nation context.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G4.4">
                             <p>4. Act as a Daily Life Magic Integrator: Describe 5 ways that common, low-level magic from "[Magic System Name]" is integrated into the mundane daily routines, professions, or infrastructure of the city of [City Name].</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Illustrates how magic subtly shapes everyday life, making the setting feel more integrated and believable.</p>
                                <p><strong>Best Used For:</strong> Worldbuilding everyday details, showing the pervasive impact of magic, adding flavor to settings. Requires system and city names.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G4.5">
                             <p>5. Act as a Magical Law & Regulation Drafter: Given the potential dangers and abuses of "[Magic System Name]", propose 3 plausible laws or regulations that the government of [Nation Name] might enact to control or monitor its use. How would these laws be enforced?</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates realistic legal or governmental responses to the existence of powerful magic within a society.</p>
                                <p><strong>Best Used For:</strong> Worldbuilding legal/political systems, generating conflict related to magic control, adding societal realism. Requires system and nation names.</p>
                            </div>
                        </div>
                        <div class="prompt-container" id="G4.6">
                             <p>6. Act as an Anti-Magic Faction Motivator: Why might a significant faction within [Society Name] distrust or actively oppose the use of magic ([Magic System Name])? Generate 3 distinct reasons based on religious beliefs, historical trauma, economic displacement, or fear of the unknown, consistent with the society's context.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Develops logical motivations for groups who resist or fear magic within the setting.</p>
                                <p><strong>Best Used For:</strong> Creating antagonist factions, adding social conflict, exploring themes of tradition vs progress or fear vs acceptance. Requires society and system context.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G4.7">
                             <p>7. Act as a Magical Economy Specialist: How does the existence of readily available "[Magical Resource/Service, e.g., healing potions, enchanted materials, teleportation networks]" impact the non-magical economy of [Region]? Does it create new industries, displace old ones, or alter the value of traditional goods and labor?</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Analyzes the economic ripple effects of specific magical goods or services available in the world.</p>
                                <p><strong>Best Used For:</strong> Worldbuilding realistic economies, creating economic conflicts or opportunities, exploring the intersection of magic and commerce. Requires resource/service and region context.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G4.8">
                             <p>8. Act as a Magical Creature Integration Analyst: How are the magical creatures ([Creature Type A], [Creature Type B]) integrated into the society of [Culture Name]? Are they treated as pests, revered beings, beasts of burden, dangerous predators, or something else? Describe the typical interactions and societal attitudes.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Explores the relationship between humans and magical creatures within a specific culture, defining their role and perception.</p>
                                <p><strong>Best Used For:</strong> Worldbuilding human-creature interactions, adding ecological/social depth, creating cultural flavor. Requires creature types and culture name.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G4.9">
                             <p>9. Act as a Secret Magic Tradition Designer: Within a society where magic is [Common/Rare/Regulated], design a plausible secret magical tradition practiced by a hidden group ([Group Name]). What are their unique methods, goals, reasons for secrecy, and relationship to mainstream magic users?</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Creates a hidden magical practice existing alongside or in opposition to the world's known magic.</p>
                                <p><strong>Best Used For:</strong> Adding mystery and intrigue, creating secret societies, designing alternative magic paths. Requires society context.</p>
                            </div>
                        </div>
                         <div class="prompt-container" id="G4.10">
                             <p>10. Act as a Magic Influence on Art & Culture Explorer: How has the nature of "[Magic System Name]" influenced the art, architecture, music, or storytelling traditions of [Culture Name]? Provide 3 specific examples.</p>
                             <div class="prompt-synopsis">
                                <p><strong>Function:</strong> Explores how the world's magic system shapes the aesthetic and cultural expressions of its people.</p>
                                <p><strong>Best Used For:</strong> Adding unique cultural details, making magic feel deeply integrated, worldbuilding artistic traditions. Requires system and culture names.</p>
                            </div>
                        </div>
                    </div>
                </details>
            </div>
        </details> <!-- End Section G -->

    </main>

</body>
</html>

