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

[View on GitHub](https://github.com/username/stock-predictor){ .md-button }
