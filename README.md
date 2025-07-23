# Visualized Log Anomaly Exploration: Pinpoint, Explain, and Query System Issues
## By Suhani Chaudhary, Ethan Shanbaum, Athanasios Tassiadamis
## WPI DS REU 2025

Welcome to the Visualized Log Anomaly Exploration additional information page. Here you can find information regarding the link to our website, poster, references, acknowledgements, user-testing setup, and more!

---

### Website Info & Link
Our interactive demo site allows users to visualize log anomalies, query system issues, and understand the reasoning behind anomalies through LLM-powered explanations.  
[**Visit the KRONE Website**](PLACE_WEBSITE_LINK_HERE)

Additional settings and configurations can be found on the **Settings** page of the website.

---

### Poster & Paper
- [**Poster PDF**](PLACE_POSTER_LINK_HERE)  
- Reference our work in: *PLACE PAPER CITATION HERE*

---

### User Testing Breakdown
We conducted structured user testing sessions to evaluate the usability, clarity, and functionality of KRONE’s visualization and anomaly detection features. Participants were asked to complete the following tasks:

1. **Load the Dataset:** Load the **Thunderbird dataset** onto the page.  
2. **Dataset Analysis:** Identify the total number of **abnormal** and **normal log keys** in the dataset.  
3. **Entity-Specific Analysis:** Identify the total number of **abnormal** and **normal log keys** for the **blk_4 entity**.  
4. **Symbol Legend:** Determine the colors that represent the **entity**, **action**, and **status** symbols.  
5. **Abnormal Status Lookup:** Find the log keys for the two **abnormal statuses** where the **entity** is **block_4** and the **action** is **writing_23**.  
6. **Anomaly Sequence Exploration:** Locate **anomalous sequence 1637**, identify the reason for the anomaly, and query this sequence in the knowledge base.  
7. **Similarity Search:** For the **blk_6 element** in the knowledge base, find the **five most similar sequences** to its first child sequence.  
8. **Feedback:** Provide suggestions for improvements or helpful changes to the system.

**Results:** On average, users completed the tasks in **5 minutes and 8.6 seconds** with a **~97% task success rate**. The **System Usability Scale (SUS)** score was **70.9**, indicating above-average usability and an overall positive user experience. Participants found the visualization intuitive but suggested clearer labeling of certain elements.

---

### References
[1] Brooke, J. (1996). SUS: A “quick and dirty” usability scale. In P. W. Jordan, B. Thomas, B. A. Weerdmeester, & I. L. McClelland (Eds.), *Usability Evaluation in Industry* (pp. 189–194). London: Taylor & Francis.
