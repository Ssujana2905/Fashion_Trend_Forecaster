A powerful AI-powered web app that helps users forecast future fashion sales and explore real-time trends using Reddit sentiment analysis and Unsplash image intelligence.

🚀 Features
📈 Sales Forecasting: Predicts future revenue using SARIMAX based on historical fashion retail data.
👗 Product-wise Trends: Country-specific product selection for accurate forecasting.
📊 Sentiment Analysis: Gathers Reddit posts and performs sentiment analysis using TextBlob.
🌍 Festival Insights: Displays relevant upcoming fashion-related festivals for enhanced business planning.
🌟 Image Insights: Uses ResNet50 to pick the most relevant fashion image from Unsplash using feature-based ranking.


🧠 Technologies Used
Python, Gradio – Frontend interface and user interaction
Pandas, NumPy – Data preprocessing
SARIMAX (statsmodels) – Time-series sales forecasting
PRAW – Reddit API integration
TextBlob – Sentiment analysis
Torch, torchvision (ResNet50) – Deep learning-based image feature extraction
Unsplash API – Fetching fashion-related images
Matplotlib – Sentiment visualization
