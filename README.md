**STOCK PRICE PREDICTION USING LSTM AND EXPLAINABLE AI 
**
  → “Because stock prices depend on past trends, and LSTM is best at handling sequential/time-series data.”
  -> In this project, I used an LSTM deep learning model to predict stock prices based on past trends.Used LIME (Local Interpretable Model-agnostic Explanations) to explain predictions.
  -> Explainable AI refers to techniques that make AI models transparent by showing why a prediction was made. Instead of just giving results, XAI highlights which features influenced the decision, so users can trust and understand the model better.
  -> By adding Explainable AI using LIME, I could show which factors like ‘High’, ‘Low’, or ‘Volume’ influenced the prediction, making the system more reliable and user-friendly
  -> LIME stands for Local Interpretable Model-agnostic Explanations. It explains a single prediction by slightly changing the input values and checking how the model’s output changes. Based on this, it assigns importance scores to each feature, showing which features affected that particular prediction most.
  -> "LSTM is a type of deep learning model that is very good at handling time-series data — data where the past influences the future. For example, stock prices or weather predictions depend on previous values. LSTM remembers past trends and uses them to predict future values better than normal models."
  -> An LSTM cell works with three gates. The Forget Gate removes unimportant past data, the Input Gate adds new useful information, and the Output Gate decides what part of memory to pass forward. This way, LSTM learns from past trends and predicts future values, which makes it powerful for stock price forecasting.
  -> Frontend (Gradio) - Used Gradio to create a simple, interactive UI.
  -> Why Gradio? → “Because it provides an easy-to-build, web-based frontend for ML models without needing complex web development.”
  -> Backend Processing (LSTM + LIME) using python implementation.
  -> Output to UI → Gradio displays prediction, chart, and explanation.
  -> For my project, I used Python with TensorFlow/Keras in the backend to build and train the LSTM model, and integrated Explainable AI with LIME for transparency. For the frontend, I used Gradio, which allowed me to build a clean, interactive web interface. Users can input stock symbols, and the app instantly shows predicted prices along with visualizations of actual vs predicted trends and feature importance. This made the project both technically strong and user-friendly.



