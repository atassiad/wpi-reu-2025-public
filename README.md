# Visualized Log Anomaly Exploration: Pinpoint, Explain, and Query System Issues
## By Suhani Chaudhary, Ethan Shanbaum, Athanasios Tassiadamis
## WPI DS REU 2025

Welcome to the **Visualized Log Anomaly Exploration** information page. Here, you will find details about our website, poster, references, acknowledgements, user testing setup, and more.

---

### Website Info & Link
Our interactive demo site enables users to visualize log anomalies, query system issues, and understand the reasoning behind anomalies using LLM-powered explanations.  
[**Visit the KRONE Website**](PLACE_WEBSITE_LINK_HERE)
![KRONE Screenshot](./Krone_Website_Img.png)
Additional settings and configurations are available on the **Settings** page.

---

### Poster & Paper
- [**Poster PDF**](PLACE_POSTER_LINK_HERE)  
- Reference our work in: *PLACE PAPER CITATION HERE*

---

### User Testing Breakdown
We conducted structured user testing sessions to evaluate the usability, clarity, and functionality of KRONE’s visualization and anomaly detection features.  
Five participants (ages 18–22) were asked to complete the following tasks with minimal or no assistance:

1. **Load the Dataset:** Load the **Thunderbird dataset** onto the page.  
2. **Dataset Analysis:** Identify the total number of **abnormal** and **normal log keys** in the dataset.  
3. **Entity-Specific Analysis:** Identify the total number of **abnormal** and **normal log keys** for the **blk_4 entity**.  
4. **Symbol Legend:** Determine the colors that represent the **entity**, **action**, and **status** symbols.  
5. **Abnormal Status Lookup:** Find the log keys for the two **abnormal statuses** where the **entity** is **block_4** and the **action** is **writing_23**.  
6. **Anomaly Sequence Exploration:** Locate **anomalous sequence 1637**, identify the reason for the anomaly, and query this sequence in the knowledge base.  
7. **Similarity Search:** For the **blk_6 element** in the knowledge base, find the **five most similar sequences** to its first child sequence.  
8. **Feedback:** Suggest improvements or changes that could make the system easier to use.

**Key Observation:**  
Nearly all participants successfully completed all tasks with minimal guidance. However, some users found **Question 6 (similarity search)** unintuitive because they did not realize they could perform a similarity search directly on the anomaly sequence visualization page. This feedback inspired us to improve the visibility and appeal of the similarity search buttons.

---

### User Testing Results

| User   | Q1–Q7 Completed | AVG SUS | Avg Time |
|--------|-----------------|---------|----------|
| User 1 | 7/7             | 80      | 4m 52s   |
| User 2 | 7/7             | 70      | 3m 54s   |
| User 3 | 7/7             | 67      | 5m 27s   |
| User 4 | 6/7             | 65      | 5m 8s    |
| User 5 | 7/7             | 72.5    | 6m 22s   |

**Summary:**  
On average, participants completed the tasks in **5 minutes and 8.6 seconds** with a **~97% task success rate**. The **System Usability Scale (SUS)** [1] score averaged **70.9**, indicating above-average usability and an overall positive user experience. Users described the visualization as intuitive but suggested improving labeling and navigation clarity.

---

### Acknowledgements
Thanks to: ​
NSF for funding our project (#2349370)

---
### References
[1] Brooke, J. (1996). SUS: A “quick and dirty” usability scale. In P. W. Jordan, B. Thomas, B. A. Weerdmeester, & I. L. McClelland (Eds.), *Usability Evaluation in Industry* (pp. 189–194). London: Taylor & Francis.
