# T81 559:Applications of Generative Artificial Intelligence

[Washington University in St. Louis](http://www.wustl.edu)

Instructor: [Jeff Heaton](https://sites.wustl.edu/jeffheaton/)

- Section 1. Fall 2024, Tuesday, 6:00 PM, Location: TBD

# Course Description

This course covers the dynamic world of Generative Artificial Intelligence providing hands-on practical applications of Large Language Models (LLMs) and advanced text-to-image networks. Using Python as the primary tool, students will interact with OpenAI's models for both text and images. The course begins with a solid foundation in generative AI principles, moving swiftly into the utilization of LangChain for model-agnostic access and the management of prompts, indexes, chains, and agents. A significant focus is placed on the integration of the Retrieval-Augmented Generation (RAG) model with graph databases, unlocking new possibilities in AI applications.

As the course progresses, students will delve into sophisticated image generation and augmentation techniques, including LORA (LOw-Rank Adaptation), and learn the art of fine-tuning generative neural networks for specific needs. The final part of the course is dedicated to mastering prompt engineering, a critical skill for optimizing the efficiency and creativity of AI outputs. Ideal for students, researchers, and professionals in computer science or related fields, this course offers a transformative learning experience where technology meets creativity, paving the way for innovative applications in the realm of Generative AI.

Note: This course will require the purchase of up to $100 in OpenAI API credits to complete the coruse.

# Objectives

1. Learn how Generative AI fits into the landscape of deep learning and predictive AI.
2. Be able to create ChatBots, Agents, and other LLM-based automation assistants.
3. Understand how to make use of image generative AI programatically.

# Syllabus

This [syllabus](https://data.heatonresearch.com/wustl/syllabus/jheaton-t81-559-fall-2024-syllabus.pdf) presents the expected class schedule, due dates, and reading assignments. Download current syllabus.

| Module                                                                        | Content                                                                                                                                                                                                                                                                                                                                                                                           |
| ----------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Module 1](t81_559_class_01_1_overview.ipynb)<br>**Meet on 08/27/2024**       | **Module 1: Introduction to Generative AI**<ul><li>1.1: Course Overview<li>1.2: Generative AI Overview<li>1.3: Introduction to OpenAI<li>1.4: Introduction to LangChain<li>1.5: Prompt Engineering<li>**We will meet on campus this week! (first meeting)**</ul>                                                                                                                                  |
| [Module 2](t81_559_class_02_1_dev.ipynb)<br>Week of 09/03/2024                | **Module 2: Prompt Based Development**<ul><li>2.1: Prompting for Code Generation<li>2.2: Handling Revision Prompts<li>2.3: Using a LLM to Help Debug<li>2.4: Tracking Prompts in Software Development<li>2.5: Limits of LLM Code Generation<li>[Module 1 Program](./assignments/assignment_yourname_class1.ipynb) due: 09/04/2024<li> Icebreaker due: 09/04/2024</ul>                          |
| [Module 3](t81_559_class_03_1_llm.ipynb)<br>Week of 09/10/2024                | **Module 3: Introduction to Large Language Models**<ul><li>3.1: Foundation Models<li>3.2: Text Generation<li>3.3: Text Summarization<li>3.4: Text Classification<li>3.5 LLM Writes a Book<li>[Module 2 Program](./assignments/assignment_yourname_class2.ipynb) due: 09/11/2024</ul>                                                                                                      |
| [Module 4](t81_559_class_04_1_langchain_chat.ipynb)<br>Week of 09/17/2024     | **Module 4: LangChain: Chat and Memory**<ul><li>4.1: LangChain Conversations<li>4.2: Conversation Buffer Window Memory<li>4.3: Conversation Token Buffer Memory<li>4.4: Conversation Summary Memory<li>4.5: Persisting Langchain Memory<li>[Module 3: Program](./assignments/assignment_yourname_class3.ipynb) due: 09/18/2024</ul>                                                               |
| [Module 5](t81_559_class_05_1_langchain_data.ipynb)<br>**Meet on 09/24/2024** | **Module 5: LangChain: Data Extraction**<ul><li>5.1: Structured Output Parser<li>5.2: Other Parsers (CSV, JSON, Pandas, Datetime)<li>5.3: Pydantic parser<li>5.4: Custom Output Parser<li>5.5: Output-Fixing Parser<li>[Module 4 Program](./assignments/assignment_yourname_class4.ipynb) due: 09/25/2024<li>**We will meet on campus this week! (second meeting)**</ul>                          |
| [Module 6](t81_559_class_06_1_rag.ipynb)<br>Week of 10/01/2024                | **Module 6: Retrieval-Augmented Generation (RAG)**<ul><li>6.1 Introduction to RAG<li>6.2 Embeddings<li>6.3 Indexing Networks<li>6.4 Q&A Over Documents<li>6.5 Vector Databases<li>[Module 5 Program](./assignments/assignment_yourname_class5.ipynb) due: 10/02/2024</ul>                                                                                                                         |
| [Module 7](t81_559_class_07_1_agents.ipynb)<br>Week of 10/15/2024             | **Module 7: LangChain: Agents**<ul><li>7.1: Introduction to Transformers<li>7.2: Accessing the ChatGPT API<li>7.3: LLM Memory<li>7.4: Introduction to Embeddings<li>7.5: Prompt Engineering<li>[Module 6 Program](./assignments/assignment_yourname_class6.ipynb) due: 10/16/2024</ul>                                                                                                            |
| [Module 8](t81_559_class_08_1_kaggle_intro.ipynb)<br>**Meet on 10/22/2024**       | **Module 8: Kaggle Assignment**<ul><li>8.1: Introduction to Kaggle<li>8.2: Kaggle Notebooks<li>8.3: Accessing Small LLM from Kaggle<li>8.4: Evaluating LLM Performance<li>8.5: Current Semester's Kaggle<li>[Module 7 Program](./assignments/assignment_yourname_class7.ipynb) due: 10/23/2024<li>**We will meet on campus this week! (third meeting)**</ul>                                                                                            |
| [Module 9](t81_559_class_09_1_streamlit.ipynb)<br>Week of 10/29/2024      | **Module 9: Introduction to StreamLit**<ul><li>9.1: Running StreamLit in Google Colab<li>9.2: StreamLit Introduction<li>9.3: Understanding Streamlit State<li>9.4: Creating a Chat Application<li>9.5: More Advanced Chat Application<li>[Module 8 Program](./assignments/assignment_yourname_class8.ipynb) due: 10/23/2024</ul> |
| [Module 10](t81_559_class_10_1_image_genai.ipynb)<br>Week of 11/05/2024       | **Module 10: Text to Image Generative AI**<ul><li>10.1: Stable Diffusion<li>10.2: Calling Dall-E<li>10.3: Upscaling Images<li>10.4: Introduction to Dreambooth<li>10.5: Adding Images to ChatBot<li>[Module 9 Program](./assignments/assignment_yourname_class9.ipynb) due: 11/06/2024</ul>                                                                                                    |
| [Module 11](t81_559_class_11_1_finetune.ipynb)<br>Week of 11/12/2024          | **Module 11: Fine Tuning**<ul><li>11.1: When is fine tuning necessary<li>11.2: Preparing a dataset for fine tuning<li>11.3: OepnAI Fine Tuning<li>11.4: Application of Fine Tuning<li>11.5: Evaluating Fine Tuning and Optimization<li>[Module 10 Program](./assignments/assignment_yourname_class10.ipynb) due: 11/13/2024</ul>                                                               |
| [Module 12](t81_559_class_12_1_prompt.ipynb)<br>Week of 11/19/2024            | **Module 12: Prompt Engineering**<ul><li>Kaggle Assignment due: 04/15/2024 (approx 4-6PM, due to Kaggle GMT timezone)<li>12.1 Towards the Perfect Prompt<li>12.2 Prompt Engineering for Images<li>12.3 Prompt Engineering for LLM<li>12.4 Advanced Tips for Prompt Engineering<li>12.5 Evaluating Bias in Prompts</ul>                                                                            |
| [Module 13](t81_559_class_13_1_voice.ipynb)<br>**Meet on 11/26/2024**         | **Module 13: Speech Processing**<ul><li>13.1: Audio Generation and Recognition <li>13.2: OpenAI Speech Generation<li>13.3: OpenAI Speech Recognition<li>Part 13.4: A Voice-Based ChatBot<li>13.5: Future Directions in GenAI<li>**We will meet on campus this week! (fourth meeting)**<li>Final project due: 12/03/2024</ul>                                                                      |
