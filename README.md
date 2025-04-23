🧠 Project Overview: AI Research Assistant

Academic research and writing a thesis is a demanding process. Researchers must not only discover, read, and digest a large number of papers but also understand their significance, compare them with others, and position their own work accordingly.

However, these tasks can be time-consuming and cognitively overwhelming — especially when papers are in PDF format, dense with jargon, or scattered across multiple platforms.

To address this pain point, our Capstone Project proposes a Generative AI-powered Research Assistant that leverages multiple GenAI capabilities to make research easier, smarter, and more interactive.


🧩 This project was voluntarily developed as part of the Google 5-Day GenAI Intensive Course. While participation in the Capstone Project was optional, we were motivated to explore how Generative AI can address real challenges in academic research. This assistant reflects our effort to apply what we learned in a meaningful, user-centric way.

Medium: https://medium.com/@esn.yilmaz1806/introduction-a-thesis-students-dilemma-518c746175de


Solution Overview
We built a research assistant that can:

Extract and summarize research papers (from PDF, URL, or plain text)
Retrieve topically similar papers from arXiv using the extracted topic
Use vector embeddings and FAISS to find semantically similar papers
Generate comparisons between user papers and retrieved ones
Provide structured abstracts, outlines, and even evaluate student writing for academic tone

This project demonstrates **6 GenAI** capabilities:

| Capability                               | How it's Used                                                                                                                                                                      |
| ---------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ✅Document Understanding                  | PDF or URL-based papers are available to be parsed and can be summarized using Gemini if the user includes with the input method. Various input methods for users were implicated. |
| ✅ Few-shot Prompting                     | Multiple few-shot prompts used for summarization, comparison, and writing evaluation.                                                                                              |
| ✅ Long Context Window                    | Gemini processes full-text research papers (from PDF or text) — this qualifies.                                                                                                    |
| ✅ GenAI Evaluation                       | Gemini evaluates and gives feedback on a student’s academic writing sample.                                                                                                        |
| ✅ Embeddings / Vector Search / Vector DB | SentenceTransformers + FAISS are used for similarity search based on research topic.                                                                                               |
| ✅ RAG                                    | arXiv retrieval + Gemini generation to compare user paper with others.    


Impact and Innovation
This project tackles a real academic pain point using state-of-the-art GenAI techniques. It bridges traditional literature review with modern GenAI workflows:

It saves hours of manual effort in summarizing, comparing, and outlining papers
It shows how retrieval + generation (RAG) can be combined with vector similarity search
It offers a glimpse into automated peer review, AI tutors for researchers, and future learning assistants
