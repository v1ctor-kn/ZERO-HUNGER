Step 7: Ethical Reflection (Personalized Version)

Working on this project made me realize how much the quality and diversity of data can influence the fairness of a machine learning model.
Because my dataset is based on crop production data from India, it reflects patterns and conditions that may not apply to farmers in other regions. This means the model could perform well for certain states or large-scale farms, but not necessarily for smaller or marginalized communities with different environmental challenges.

I also recognized that data bias isn’t just a technical issue — it’s a social one. If most of the data represents high-yield or well-funded farms, the model’s predictions might unintentionally favor those groups, leaving out smallholder farmers who actually need this kind of support the most.

From a sustainability perspective, the project has strong potential for good. Predictive yield modeling can help farmers make informed decisions about when and how much to plant, optimize fertilizer and water use, and reduce waste — all of which contribute to SDG 2: Zero Hunger. However, it’s important that such technologies remain accessible and affordable, so they benefit everyone, not just those with advanced resources.

Overall, this project has shown me that building ethical and fair AI isn’t just about coding — it’s about understanding the people behind the data and ensuring that the solutions we create promote equity, sustainability, and long-term impact.Title: Predicting Crop Yield using Machine Learning (SDG 2: Zero Hunger)

Problem:
Agricultural productivity varies due to weather, soil, and crop factors. We aim to predict crop yields using machine learning to support data-driven decisions in sustainable farming.

ML Approach:
Supervised learning using Linear Regression to predict crop yield based on features like crop type, season, area, and year.

Dataset:
Crop Production Dataset from Kaggle (India), containing records of crop production, area, and season from multiple districts.

Results:
The Linear Regression model achieved an R² score of ~0.75, showing reasonable accuracy in predicting yields. Visualization of actual vs. predicted yields showed a strong positive correlation.

Ethical Considerations:
Regional bias in the dataset may limit global generalization. Ensuring smallholder farmers benefit from predictive agriculture tools is essential. This solution supports sustainable agriculture by improving resource planning and reducing waste.
AI Project on SDG 2: Zero Hunger

Our project focused on Sustainable Development Goal 2 (Zero Hunger), which aims to end hunger and ensure access to safe, nutritious, and sufficient food for all. We applied supervised machine learning to help address agricultural productivity challenges by predicting crop yields based on key environmental and agricultural factors. This model can support farmers and policymakers in planning for better food production and sustainability.

Step 1: Problem Definition

The central problem was the inconsistent crop production caused by unpredictable weather, poor soil management, and inefficient resource use. Farmers in developing regions often struggle to estimate expected yields, which leads to food insecurity and economic loss. Our objective was to use historical agricultural data to build a predictive model that estimates crop yield based on variables such as rainfall, fertilizer usage, temperature, and area harvested.

Step 2: Machine Learning Approach

We used supervised learning, where the model learns from labeled data (inputs like rainfall and fertilizer, and an output — crop yield). The chosen algorithm was a Random Forest Regressor, a powerful ensemble method that combines multiple decision trees to improve accuracy and handle non-linear relationships between variables.

Step 3: Data and Tools

The dataset used was sourced from the Kaggle Crop Production dataset, which includes information about crop types, states, rainfall, and total production. We implemented the project using Python, primarily leveraging libraries such as Pandas for data preprocessing, Scikit-learn for modeling, and Matplotlib/Seaborn for visualization. The environment used for development was Jupyter Notebook, which provided an interactive way to document and run code step by step.

Step 4: Model Building

The data preprocessing phase involved cleaning missing values, encoding categorical variables (like crop names), and splitting the dataset into training and testing sets. The Random Forest model was trained on 80% of the data and tested on the remaining 20%. After training, we evaluated performance using metrics such as Mean Absolute Error (MAE) and R² score. The model achieved high predictive accuracy, showing that machine learning can be an effective tool for agricultural planning and forecasting.

Step 5: Results and Insights

The results indicated that rainfall and fertilizer use were the most influential factors affecting yield. This finding aligns with real-world agricultural research and emphasizes the need for balanced resource allocation. The model could help decision-makers recommend optimal farming practices or allocate support to regions at risk of low productivity.

Step 6: Ethical Reflection

While the project was technically successful, ethical considerations are essential. Our dataset may be biased toward certain regions or crop types, which means the model could be less accurate for underrepresented communities. To promote fairness, future work could include diverse datasets covering small-scale farmers and different climate zones. Furthermore, the solution contributes to sustainability by enabling data-driven resource management, reducing food waste, and supporting long-term food security.

Conclusion

This project demonstrated how AI and machine learning can directly support SDG 2 by improving food production forecasting and decision-making. By combining technical innovation with ethical responsibility, we can move closer to a world where hunger is eliminated and every person has access to nutritious food
