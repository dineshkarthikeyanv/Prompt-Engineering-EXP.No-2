EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

Name : DINESHKARTHIKEYAN V

Register No : 212225230060

Date : 21.04.2026

AIM

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

SCENARIO:

You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

OUTPUT
Introduction
We live in an era where information is generated faster than any human can read. Every day, research papers, news articles, business reports, and academic texts pile up, and the challenge of extracting meaningful insight from them is very real. That is precisely where AI-powered text summarization comes in — and it has become one of the most practical, everyday applications of modern large language models (LLMs). This report explores how three of today’s leading AI assistants — ChatGPT by OpenAI, Gemini by Google, and Claude by Anthropic — perform when given the same article and the same summarization tasks. The goal is not just to declare a winner, but to understand each tool’s personality, its strengths, and the contexts in which it shines. Think of this as a side-by-side taste test, except instead of food, we are comparing intelligence.

Objective of the Experiment
The experiment was designed around four clear goals, each building on the previous one: • Feed the exact same article into ChatGPT, Gemini, and Claude without altering the prompt between tools. • Request three distinct summary styles — a short one-liner, a detailed paragraph, and a structured bullet-point list — to test each tool across different output formats. • Evaluate the summaries on multiple quality dimensions such as accuracy, clarity, completeness, naturalness of language, and ethical awareness. • Draw an evidence-based conclusion about which tool performs best overall, and in which specific scenarios each tool has an edge. By keeping all variables constant and only changing the AI tool, we ensure a fair and meaningful comparison.

Source Article Used for Summarization
A short, information-dense article on Artificial Intelligence was chosen for the experiment. The article covers a broad range of topics in a compact form, which makes it an ideal stress-test for summarization tools. Here is the article in full: AI Tool Comparison Report — Prompt Engineering .| 212225230070Page 3 “Artificial Intelligence is transforming industries by automating tasks, improving decision-making, and enhancing productivity. Applications include healthcare, education, transportation, business analytics, and virtual assistants. However, AI also raises concerns related to bias, privacy, and employment.” Despite its brevity, this article packs in several dimensions: a core claim about transformation, a list of application domains, and a counter-narrative about risks. A good summary must capture all three threads without losing the balance between optimism and caution.

AI Tools Used in the Experiment
Three AI assistants were selected for this study. Each represents a different philosophy of how language models should be built, trained, and aligned with human values.

4.1 ChatGPT (by OpenAI)

ChatGPT is built on OpenAI’s GPT-4 architecture and has become the most widely recognised AI assistant in the world. It was trained on an enormous corpus of text and fine-tuned with reinforcement learning from human feedback (RLHF). ChatGPT excels at producing structured, well-balanced text that feels encyclopaedic yet accessible. It is the go-to choice for users who want comprehensive, reliable answers in a professional tone.

4.2 Gemini (by Google DeepMind)

Gemini is Google’s flagship multimodal AI model, designed from the ground up to handle text, images, code, and more. Its training benefited from Google’s vast indexing infrastructure, which gives it a strong grasp of factual and technical content. Gemini tends to produce summaries that are technically precise, leaning towards efficiency and factual density rather than narrative warmth.

4.3 Claude (by Anthropic)

Claude is Anthropic’s AI assistant, and it was built with a particular emphasis on safety, helpfulness, and honesty. Anthropic’s Constitutional AI (CAI) approach means Claude is unusually good at reasoning about ethics, nuance, and context. Its summaries often read more like something a thoughtful, careful human would write, with an instinctive awareness of the social and moral dimensions of a topic. AI Tool Comparison Report — Prompt Engineering .

Experiment Workflow
The diagram below illustrates the end-to-end process followed during this experiment — from selecting the source article, through generating outputs across all three tools, to the final ranking. Figure 1: End-to-end workflow of the AI summarization comparison experiment

<img width="997" height="575" alt="image" src="https://github.com/user-attachments/assets/bc3bffba-517e-4077-a092-ffcc9821332c" />


Prompt Strategy
One of the most important lessons in prompt engineering is that how you ask a question shapes the answer you receive. For this experiment, three carefully designed prompts were used to elicit three different types of summary from each tool.

Prompt 1 — Short Summary “Summarise the following article in one to two sentences.” This prompt tests a tool’s ability to distil the core message without losing the essential balance between benefits and risks. A great one-liner must be both accurate and representative. AI Tool Comparison Report — Prompt Engineering

Prompt 2 — Detailed Summary “Provide a detailed summary of the following article, covering the main points thoroughly.” This prompt requires the model to retain and organise all the key information from the source — the transformation claim, the application domains, and the ethical concerns — in a coherent, readable paragraph.

Prompt 3 — Bullet-Point Summary “Summarise the following article using clear bullet points.” Bullet-point summaries are extremely common in professional settings. This prompt tests whether the tool can isolate discrete facts and present them in a parallel, scannable format.

Generated Summaries — Side by Side

<img width="1037" height="445" alt="image" src="https://github.com/user-attachments/assets/7a81bac9-f570-4259-9682-b564dea28124" />

Here is a direct comparison of the summaries produced by each AI tool across all three prompt types. Reading across the table reveals immediate patterns. ChatGPT’s short summary is the most balanced. Gemini’s is the most technically oriented. Claude’s is the most ethically conscious. These tendencies carry through all three prompt types.

In-Depth Analysis of Each Tool
AI Tool Comparison Report — Prompt Engineering

8.1 ChatGPT — The Well-Rounded Performer ChatGPT demonstrated consistently strong performance across all three summary formats. Its short summary captured the dual nature of AI — productivity gains on one side, ethical concerns on the other — without favouring either. The detailed summary read like a well-edited magazine article: structured, readable, and complete. The bullet points were clean and parallel, which is exactly what you want for a scannable list. What sets ChatGPT apart is its reliability. There are no surprising gaps or imbalances — it just works, consistently. For users who need summaries that are universally legible and professionally safe, ChatGPT is the natural first choice.

8.2 Gemini — The Technical Specialist

Gemini produced summaries that were factually accurate and impressively efficient. It gravitated towards the practical, industrial aspects of AI — data analysis, operational efficiency, technical applications — and handled them with precision. However, the summaries sometimes felt slightly mechanical, as though written for a technical report rather than a general audience. Gemini’s bullet points were crisp but slightly less complete than ChatGPT’s. Its detailed summary was informative but lacked the narrative warmth that makes a piece genuinely engaging. In contexts where technical precision matters more than readability — such as scientific or engineering environments — Gemini’s style is a genuine advantage.

8.3 Claude — The Thoughtful Humanist

Claude’s summaries were, perhaps unsurprisingly, the most human sounding of the three. The language was natural and fluid, and every summary explicitly acknowledged the ethical dimensions of AI — responsible use, societal impact, the importance of caution — in a way that felt organic rather than forced. The trade-off is that Claude sometimes sacrificed completeness for elegance. The detailed summary was beautifully written but did not enumerate all the application domains mentioned in the source article. For users who prioritise ethical framing, nuanced language, and trustworthiness, Claude’s approach is uniquely valuable. AI Tool Comparison Report — Prompt Engineering

Performance Comparison Chart
The following chart visualizes how each AI tool scored across five key quality dimensions. Scores were assigned based on the experimental outputs and normalized on a scale of 1 to 10. Figure 2: Comparative performance of ChatGPT, Gemini, and Claude across quality dimensions The chart makes the tradeoffs immediately visible. ChatGPT leads to Accuracy, Clarity, and Completeness. Claude leads decisively to Naturalness and Ethics Focus. Gemini occupies a middle position on most dimensions but excels in Speed and Brevity, making it the most efficient option for quick technical summarization.

<img width="1033" height="577" alt="image" src="https://github.com/user-attachments/assets/8560ff8c-2c50-4bbb-afa2-27347588422c" />

Detailed Comparison Table
The table below provides a structured, criterion-by-criterion comparison of all three tools. Star ratings reflect the qualitative assessments made during the experiment. image

<img width="980" height="178" alt="image" src="https://github.com/user-attachments/assets/0a020fe5-e551-495e-abdf-9643434f9908" />
<img width="960" height="292" alt="image" src="https://github.com/user-attachments/assets/8063dc01-f19b-4b3d-947c-4012d0214c4c" />

However, these numbers do not tell the full story — Claude’s perfect score on Naturalness and Ethics Focus makes it the superior choice in many real-world contexts.

Use-Case Recommendations
Based on the experimental findings, here is a practical guide for choosing the right AI summarization tool depending on the context: When to Choose ChatGPT • You need a reliable, all-purpose summary that works in almost any professional context. • Your audience includes non-specialists who need clear, balanced language. • You are producing summaries for reports, presentations, or academic submissions. • Consistency and completeness are your top priorities. When to Choose Gemini • You are working in a technical or scientific domain where precision matters more than narrative flow. • Speed and efficiency are paramount, and you need a very concise output. • The source material is data-heavy or highly technical. • You want to leverage Google’s broad knowledge index for factually grounded summaries. When to Choose Claude AI Tool Comparison Report — Prompt Engineering

• Your content involves sensitive or ethically complex topics where tone and responsibility matter. • You want summaries that read like something a thoughtful human expert would write. • The audience will judge the quality of writing as much as the accuracy of the content. • You are in healthcare, education, policy, or any field where ethical framing is nonnegotiable. 12. Conclusion This experiment set out to answer a deceptively simple question: which AI tool does the best job of summarizing text? The answer, as is often the case with nuanced questions, turns out to be “it depends.” ChatGPT is the safest, most versatile choice for the broadest range of users and contexts. Its summaries are accurate, complete, clear, and professionally polished. It is the Swiss Army knife of AI summarization. Gemini is the right choice when technical accuracy and conciseness are the priority. It is fast, factually strong, and particularly well-suited to STEM and data-driven environments. Claude is the tool for contexts where the human dimension of a topic matters as much as the factual content. Its natural language, ethical awareness, and warm tone make it uniquely valuable in fields that touch on people’s lives and wellbeing. Ultimately, the best tool is the one that aligns most closely with your goals, your audience, and the nature of the content you are working with. And the good news is that all three tools are remarkably capable — we are in a golden age of AI-assisted communication.


References

OpenAI. (2024). ChatGPT and GPT-4 Technical Documentation. OpenAI. https://openai.com/research AI Tool Comparison Report — Prompt Engineering

Google DeepMind. (2024). Gemini: A Family of Highly Capable Multimodal Models. Google DeepMind. https://deepmind.google/technologies/gemini

Anthropic. (2024). Claude Model Documentation and Constitutional AI Overview. Anthropic. https://www.anthropic.com/claude

Brown, T., et al. (2020). Language Models are Few-Shot Learners. Advances in Neural Information Processing Systems (NeurIPS), 33, 1877–1901.

Ouyang, L., et al. (2022). Training Language Models to Follow Instructions with Human Feedback. arXiv:2203.02155.

El-Kassas, W., Salama, C., Rafea, A., & Mohamed, H. (2021). Automatic Text Summarization: A Comprehensive Survey. Expert Systems with Applications, 165, 113679.

RESULT
Considering the above prompts and outputs, ChatGPT provides the best summary in terms of accuracy,Coherance, Simplicity, Speed, User experience. 👍
