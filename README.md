# CrisisFACTS: Real-Time Multi-Stream Data Summarization for Enhanced Crisis Response and Situational Awareness

**Enhancing Situational Awareness During Crises**

This project addresses the critical need for timely and relevant information during crises. CrisisFACTS is a real-time multi-stream data summarization system designed to enhance situational awareness by automatically generating concise daily summaries of crucial information extracted from diverse sources like Twitter, Reddit, and Web News.  These summaries empower local crisis response teams with the information they need to improve disaster response coordination and decision-making.

## Problem Statement

In crisis situations, information overload can hinder effective response.  CrisisFACTS tackles this challenge by intelligently filtering and summarizing vast amounts of real-time data, providing crisis responders with a clear and concise overview of the evolving situation.  This allows for faster and more informed decisions, ultimately leading to more effective disaster relief efforts.

## Key Features

* **Multi-Stream Data Integration:**  Aggregates data from multiple crucial sources, including Twitter, Reddit, and Web News, to provide a comprehensive view of the crisis.
* **Real-Time Summarization:** Generates daily summaries of the most relevant facts, ensuring responders have access to up-to-the-minute information.
* **Concise and Actionable Summaries:**  Focuses on extracting and summarizing key information, avoiding information overload and facilitating quick comprehension.


## Evaluation Strategy

The performance of CrisisFACTS' summarization capabilities is rigorously evaluated using established metrics:

* **ROUGE Score:**  A standard metric for evaluating the quality of automatic text summarization.  ([Lin, 2004](https://aclanthology.org/W04-1013/))
* **BERT-Score:**  A more recent metric that leverages contextualized word embeddings for a more nuanced evaluation of semantic similarity. ([Zhang et al., 2019](https://arxiv.org/abs/1904.09675))

## Dataset

The project utilizes the **crisisFACTS dataset**, available at: [https://crisisfacts.github.io/](https://crisisfacts.github.io/)

## Team

* **Team Name:** Rescue Retrieval
* **Team Members:**
    * Raj Kariya (202103048)
    * Asish Joel (202103015 )
    * Aadesh Minz (202103002)

## Resources

* **CrisisFACTS Overview Paper:** [https://crisisfacts.github.io/assets/pdf/crisisfacts2022.iscram2023.pdf](https://crisisfacts.github.io/assets/pdf/crisisfacts2022.iscram2023.pdf)
* **ROUGE: A Package for Automatic Evaluation of Summaries:** [https://aclanthology.org/W04-1013/](https://aclanthology.org/W04-1013/)
* **BERTScore: Evaluating Text Generation with BERT:** [https://arxiv.org/abs/1904.09675](https://arxiv.org/abs/1904.09675)


## Technologies Used
- Python, NLTK, BERT, BART, BM-25 Model

## Future Work
- We can enhance the performance of extractive and abstractive summarization by using ensemble techniques. 
