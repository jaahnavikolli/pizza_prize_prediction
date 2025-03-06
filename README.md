🍕📊 Pizza Price Prediction
📖 Overview 📝
This project focuses on predicting pizza prices based on various attributes such as size, toppings, and additional ingredients. Using machine learning techniques, the model analyzes the dataset to provide accurate price estimations.

📊 Dataset 📁
The dataset (pizza.csv) consists of 129 entries and 9 features related to different pizzas, their characteristics, and pricing.
📌 Dataset Features:
🏢 company: The pizza brand or company.
💰 price_rupiah: The price of the pizza in Indonesian Rupiah (target variable).
📏 diameter: The diameter of the pizza (e.g., "22 inch", "16 inch").
🍕 topping: The primary topping used (e.g., "chicken", "mushrooms").
🍽 variant: The variant or category of the pizza (e.g., "double_signature").
📐 size: The pizza size (e.g., "jumbo", "regular").
🥫 extra_sauce: Indicates if extra sauce is added ("yes" or "no").
🧀 extra_cheese: Indicates if extra cheese is added ("yes" or "no").
🍄 extra_mushrooms: Indicates if extra mushrooms are added ("yes" or "no").

🛠 Technologies Used 🖥️
🐍 Python
📊 Pandas
🔢 NumPy
🤖 Scikit-Learn
📉 Matplotlib & Seaborn (for data visualization)
☁️ Google Colab (for model training and analysis)

🚀 Usage Guide 🏁
🔍 Load the dataset and perform Exploratory Data Analysis (EDA).
🔧 Preprocess the data (convert price to numeric, clean diameter values, encode categorical variables, etc.).
🏗 Train a machine learning model (e.g., Linear Regression, Random Forest).
📊 Evaluate model performance using:
📉 Mean Absolute Error (MAE)
📏 Mean Squared Error (MSE)
🎯 R-squared Score

🔮 Make predictions and visualize results.
Run the main script using:
python main.py

📈 Model Performance 📊
The trained model is evaluated based on key performance metrics such as MAE, MSE, and R² score to ensure accuracy.

🤝 Contributing ✨
Contributions are always welcome! If you have ideas for improvements, feel free to open an issue or submit a pull request.
