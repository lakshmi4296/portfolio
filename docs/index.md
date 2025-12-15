# About Me

<div class="hero-container">
  <img src="assets/images/my_pic.jpeg" class="profile-pic" alt="Profile Picture">
  <div>
    <p><strong>Hi there! 👋</strong></p>
    <p>I'm an **AI/ML Engineer** who loves building intelligent systems that solve real problems.</p>
    <p>I code in Python, play with PyTorch, and love exploring new tech.</p>
  </div>
</div>

---

## What I Do

I enjoy working on:

*   **Machine Learning**: Teaching computers to see, read, and learn.
*   **Data Engineering**: Wrangling messy data into clean insights.
*   **Deployment**: Putting models into the real world.

[Read My Resume](#resume){ .md-button .md-button--primary }
[View My Projects](#projects){ .md-button }

---

# Resume

## Experience

### Senior ML Engineer | Tech Corp
*2023 - Present*

- Led a team of 4 engineers to deploy a recommendation engine serving 1M+ users.
- Reduced model inference latency by 40% using quantization.

### AI Researcher | University Lab
*2021 - 2023*

- Published 2 papers on Natural Language Understanding at NeurIPS.
- Developed a novel attention mechanism for transformer models.

---

## Education

### M.S. in Computer Science (AI Specialization)
*Tech University, 2021*

### B.S. in Computer Engineering
*State College, 2019*

---

## Skills

- **Languages**: Python, C++, SQL
- **Frameworks**: PyTorch, TensorFlow, Keras, Scikit-learn
- **Tools**: Docker, Kubernetes, Git, MLflow, Airflow
- **Cloud**: AWS (SageMaker, Lambda), Google Cloud Platform

---

# Projects

Here are some of the projects I've worked on.

## 🧠 Generative AI Chatbot

A RAG-based chatbot that answers questions from custom documentation.

- **Stack**: Python, LangChain, OpenAI API, FAISS
- **Key Features**: Contextual understanding, source citation.

```python
# Example snippet from the bot
def get_response(query):
    docs = vector_store.similarity_search(query)
    chain = load_qa_chain(llm, chain_type="stuff")
    return chain.run(input_documents=docs, question=query)
```

---

## 👁️ Computer Vision Traffic Analyzer

Real-time object detection model to count vehicles and analyze traffic flow.

- **Stack**: YOLOv8, OpenCV, PyTorch
- **Key Features**: Real-time inference on edge devices.

![Placeholder Image](https://via.placeholder.com/800x400?text=Computer+Vision+Project+Screencap)
*(Replace with your actual project image)*

---

## 📈 Stock Price Predictor

Time-series forecasting using LSTM networks to predict stock trends.

- **Stack**: TensorFlow, Pandas, Scikit-learn
- **Results**: Achieved 85% directional accuracy on test set.

$f(t) = \sigma(W_f \cdot [h_{t-1}, x_t] + b_f)$
