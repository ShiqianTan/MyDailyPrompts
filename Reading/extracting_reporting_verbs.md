
### **Prompt for Categorizing Reporting Verbs in Academic Literature**

**Objective:**
You are an expert in academic discourse analysis and English for Academic Purposes (EAP). Your task is to analyze provided text excerpts from research papers and identify all reporting verbs used to cite other authors' work. You will then classify each verb according to the specific taxonomy provided below.

**Instructions:**
1.  Carefully read the text excerpts from the academic paper, titled `[Paper Title]`.
2.  For every instance where the author cites another source (e.g., Lee (2015)) using a verb, extract the following information:
    a.  **Paper Title:** The title of the paper you are analyzing.
    b.  **Page Number:** The page number where the verb appears.
    c.  **Reporting Verb:** The specific verb used (e.g., *established, observed, thinks, disputes, argues, hypothesized*).
    d.  **Verb Type:** The category and sub-category from the taxonomy below that best fits the verb's usage in this context.
    e.  **Full Sentence:** The complete sentence in which the verb appears, for context.

**Output Format:**
Present your findings in a clear, structured list. Use the following format for each entry:

`[Paper Title], [Page Number], [Reporting Verb], [Verb Type], [Full Sentence]`

**Example of Output Format:**
*   `"The Role of Drilling in Hydrology, p. 12, established, Findings (Factive), Lee (2015) established that additional drilling would result in a higher water yield."`
*   `"Cognitive Theories of Grammar, p. 8, believes, Cognition acts (Tentative), Lee (2015) believes that theory should precede action in this model."`

---

### **Taxonomy for Classification**

Use this classification system to assign the **Verb Type**. Choose the most precise category based on the writer's intent.

| Category | Sub-category | Description |
| :--- | :--- | :--- |
| **Research acts:** Reference to research (including procedures and findings) in the real world | **Findings - Factive** | Demonstrate writer’s acceptance of cited proposition. |
| | **Findings - Counter-factive** | Demonstrate writer’s view of the cited proposition as false or incorrect. |
| | **Findings - Non-factive** | Convey no clear judgement on the reliability of the cited proposition. |
| | **Procedures** | Describes procedural aspects without attitudinal force. |
| **Cognition acts:** Writer attributes a particular attitude to the author | **Positive** | Suggest author’s positive attitude/agreement toward cited material. |
| | **Critical** | Suggest author’s negative or critical attitude toward cited material. |
| | **Tentative** | Suggest author’s uncertain attitude toward cited material. |
| | **Neutral** | Suggest author’s neutral attitude toward cited material. |
| **Discourse acts:** Represent the writer’s explicit attitude toward the cited information | **Assurance - Factive** | Reflect writer’s confidence of reported information as true. |
| | **Assurance - Non-factive** | Reflect writer’s perspective on reported information without truth valuations. |
| | **Doubt - Tentative** | Reflect writer’s uncertainty of reported information as true. |
| | **Doubt - Critical** | Reflect writer’s disbelief of or disagreement with reported information. |
| | **Counters (author focused)** | Reflect author’s own reservations or objections to the correctness of claims. |

---

**Text to Analyze:**
Analyze the uploaded pdfs.

---

## Example

# Categorization of Reporting Verbs in "Can Reasoning Power Significantly Improve the Knowledge of Large Language Models for Chemistry? Based on Conversations with LLMs"
## 1. List of Reporting Verbs with Categorization and Explanation
| Paper Title | Page Number | Reporting Verb | Verb Type | Full Sentence | Explanation of Verb Meaning in the Sentence |
| --- | --- | --- | --- | --- | --- |
| "Can Reasoning Power Significantly Improve the Knowledge of Large Language Models for Chemistry? Based on Conversations with LLMs" | 9516 | leveraged | Research acts - Procedures | "Numerous scientists leveraged LLMs to advance research endeavors, including guiding the discovery of novel materials,2−6 designing and planning multistep scientific experiments,7 constructing AI-powered chemistry assistants,8−10 and enhancing chemical education.11−13" | Refers to scientists making practical use of LLMs as a tool to carry out and advance various research activities in chemistry-related fields, describing the procedural application of LLMs in research. |
| "Can Reasoning Power Significantly Improve the Knowledge of Large Language Models for Chemistry? Based on Conversations with LLMs" | 9516 | conducted | Research acts - Procedures | "A prior study by Nascimento and Pimentel18 conducted a preliminary investigation into the chemical knowledge of Large Language Models (LLMs), utilizing OpenAI’s GPT-3 model with a limited set of questions." | Describes the action of Nascimento and Pimentel carrying out a preliminary research study to explore the chemical knowledge of LLMs, focusing on the procedural aspect of conducting an investigation. |
| "Can Reasoning Power Significantly Improve the Knowledge of Large Language Models for Chemistry? Based on Conversations with LLMs" | 9516 | demonstrated | Research acts - Findings (Factive) | "Compared to Llama-3.1−405B, DeepSeek V3, and Qwen2.5−72B, the Qwen2.5-Max model demonstrated significant advantages across most benchmarks, achieving a score of 60.1 on the GPQA Diamond benchmark.19" | Indicates that the Qwen2.5-Max model showed or proved its notable advantages over other models in benchmark tests; the current paper accepts this observed result as a valid finding. |
| "Can Reasoning Power Significantly Improve the Knowledge of Large Language Models for Chemistry? Based on Conversations with LLMs" | 9517 | showed | Research acts - Findings (Factive) | "Previous research has shown that the OpenAI-GPT-3 model achieved an accuracy of only 41.67% on the same task.18" | Means previous research presented evidence that the OpenAI-GPT-3 model had low accuracy on the molecular geometry determination task; the current paper acknowledges this result as a confirmed finding. |
| "Can Reasoning Power Significantly Improve the Knowledge of Large Language Models for Chemistry? Based on Conversations with LLMs" | 9519 | showed | Research acts - Findings (Factive) | "Previous research has shown that the OpenAI GPT-3 model had a mean relative error as high as 31% on the same task.18" | Signifies that prior research revealed the OpenAI GPT-3 model had a large mean relative error in log P value prediction; the current paper accepts this as a true finding from previous work. |
| "Can Reasoning Power Significantly Improve the Knowledge of Large Language Models for Chemistry? Based on Conversations with LLMs" | 9520 | showed | Research acts - Findings (Factive) | "Compared to the research published by Nascimento and Pimentel, the five reasoning-oriented Large Language Models in our study showed a significant improvement in accuracy, even with a comprehensively expanded test set, achieving a maximum accuracy of 90.91% (with Gemini 2.5 Pro)." | Indicates that the five reasoning-oriented LLMs in the current study presented or exhibited a notable increase in accuracy compared to Nascimento and Pimentel’s research; the current paper confirms this improvement as a valid finding. |
| "Can Reasoning Power Significantly Improve the Knowledge of Large Language Models for Chemistry? Based on Conversations with LLMs" | 9525 | extend | Discourse acts - Assurance (Non-factive) | "In the realm of prompt engineering, we further extend the findings of He et al. and Wang et al.42,43 to the chemical domain: in most cases, overly complex prompts are not beneficial for well-trained LLMs and may even degrade their performance." | Means the current study takes the findings of He et al. and Wang et al. (related to prompt engineering) and applies them to the chemical field to expand their scope of application; the current paper presents this extension without making a truth judgment on the original findings beyond their relevance to chemistry. |
| "Can Reasoning Power Significantly Improve the Knowledge of Large Language Models for Chemistry? Based on Conversations with LLMs" | 9525 | establishes | Research acts - Findings (Factive) | "This study establishes a key framework for evaluating the performance of reasoning-enabled Large Language Models in chemical research, revealing their performance in the chemical domain and the influence of prompt engineering." | Refers to the current study creating and putting forward a crucial evaluation framework for reasoning-enabled LLMs in chemistry research; the paper presents this framework as a confirmed, valid outcome of the study. |
| "Can Reasoning Power Significantly Improve the Knowledge of Large Language Models for Chemistry? Based on Conversations with LLMs" | 9526 | elicit | Research acts - Findings (Factive) | "Wei, J.; Wang, X.; Schuurmans, D.; Bosma, M.; Chi, E. H.; Xia, F.; Le, Q.; Zhou, D. Chain of Thought Prompting Elicits Reasoning in Large Language Models. 2022. arXiv:2201.11903. arXiv.org ePrintarchive https://doi.org/10.48550/arXiv.2201.11903." | Means Wei et al.’s research found that chain-of-thought prompting brings out or induces reasoning abilities in LLMs; the current paper accepts this as a true finding from that study. |
| "Can Reasoning Power Significantly Improve the Knowledge of Large Language Models for Chemistry? Based on Conversations with LLMs" | 9527 | predict | Research acts - Findings (Non-factive) | "Palm, K.; Stenberg, P.; Luthman, K.; Artursson, P. Polar Molecular Surface Properties Predict the Intestinal Absorption of Drugs in Humans. Pharm. Res. 1997, 14 (5), 568−571." | Indicates that Palm et al.’s work claims polar molecular surface properties can foretell or estimate the intestinal absorption of drugs in humans; the current paper presents this claim without expressing a clear judgment on its reliability. |


## 2. Full List of All Reporting Verbs
leveraged, conducted, demonstrated, showed, extend, establishes, elicit, predict
