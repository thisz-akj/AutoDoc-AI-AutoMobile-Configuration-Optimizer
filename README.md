# AutoDoc AI - Automotive Feature Testing Process Optimizer (RapidMiner Version)

## Overview

This project was developed using **RapidMiner** to build a predictive model that optimizes the testing process for various feature combinations in automotive systems. The model leverages machine learning techniques to reduce testing time, improve accuracy, and enhance overall production efficiency. 

With **RapidMiner**, the project benefits from its intuitive drag-and-drop interface and built-in machine learning operators, making it easy to design, train, and deploy the model without extensive manual coding.

## Key Features

- **Data Preprocessing**: Cleans and preprocesses datasets using RapidMiner’s built-in operators to handle missing values and perform feature selection based on correlation analysis.
- **XGBoost Integration**: Implements **XGBoost** within RapidMiner to handle large datasets with complex feature interactions, ideal for automotive configurations.
- **Testing Time Prediction**: Predicts the testing time for different automotive feature combinations, enabling manufacturers to focus on efficient configurations.
- **Optimization**: Identifies optimal feature combinations that reduce testing time while maintaining product quality.
- **Performance Evaluation**: Assesses the model’s performance using metrics like **RMSE**, **precision**, **recall**, and **F1-score**.
- **Visualization**: Utilizes RapidMiner’s visualization tools to provide insights into factors affecting testing time, supporting informed decision-making.

## Benefits

- **RapidMiner-Based Automation**: Automates data preprocessing, model training, and prediction steps, reducing manual intervention.
- **Reduced Testing Time**: Prioritizes feature combinations that are efficient, reducing overall testing time.
- **Improved Accuracy**: Enhances the precision of testing predictions, ensuring better production quality.
- **Scalability**: Scales effectively across various automotive feature configurations.
- **Enhanced Visualization**: Offers detailed insights with RapidMiner’s built-in visualization tools, aiding in feature importance and decision-making analysis.

## Technologies Used

- **RapidMiner**: Main platform for model development, training, and evaluation.
- **XGBoost**: Integrated into RapidMiner for high-performance machine learning modeling.
- **Pandas, NumPy**: Data handling through RapidMiner's Python scripting extension when needed.
- **Matplotlib, Seaborn**: Visualization in RapidMiner, or via Python scripting for advanced visual analytics.

## Installation and Setup

### Requirements

- **RapidMiner Studio 9.10+**
- **XGBoost Extension for RapidMiner** (available via RapidMiner Marketplace)
- Python scripting environment (optional, for custom data processing or visualization)

### Steps to Install

1. **Download RapidMiner Studio**: If not already installed, [download and install RapidMiner Studio](https://rapidminer.com/downloads/).
2. **Install XGBoost Extension**: 
   - Open RapidMiner Studio.
   - Go to **Extensions** > **Marketplace** and search for “XGBoost”.
   - Install the XGBoost extension and restart RapidMiner Studio.
3. **Open the Project**: 
   - Clone or download this repository.
   - Open the project file (`.rmp`) in RapidMiner Studio.
4. **Run the Model**:
   - Ensure the dataset is properly linked in the process.
   - Execute the process to train the model and predict testing times.

## Usage

1. **Data Preprocessing**: The project uses RapidMiner operators to clean and preprocess the dataset. You can modify preprocessing steps based on your dataset's needs.
2. **Model Training**: Train the **XGBoost** model on your automotive feature dataset to predict testing times.
3. **Optimization**: Review the optimized configurations to minimize testing time and costs.
4. **Visualization**: Use RapidMiner’s visualization tools for a detailed understanding of how each feature affects the predicted testing time.

## Performance Evaluation

The model's performance is evaluated using the following metrics:

- **RMSE (Root Mean Squared Error)**: To measure the model’s accuracy in predicting testing times.
- **Precision, Recall, and F1-Score**: For evaluating classification performance if the model involves threshold-based classification of configurations.

## Tech Stack Icons (CSS Code)

For displaying tech stack icons in a project readme or documentation site, here’s an example of how you could integrate icons using HTML and CSS:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    .tech-stack {
      display: flex;
      justify-content: space-around;
      align-items: center;
      margin: 20px 0;
    }

    .tech-stack img {
      width: 60px;
      height: auto;
      margin: 10px;
      transition: transform 0.3s ease;
    }

    .tech-stack img:hover {
      transform: scale(1.2);
    }

    .tech-stack-title {
      text-align: center;
      font-size: 1.6em;
      margin-bottom: 15px;
      color: #333;
    }

    .tech-stack-container {
      padding: 30px;
      border: 1px solid #ddd;
      background-color: #f9f9f9;
      border-radius: 8px;
    }
  </style>
</head>
<body>

  <div class="tech-stack-container">
    <div class="tech-stack-title">Tech Stack</div>
    <div class="tech-stack">
      <img src="https://cdn-icons-png.flaticon.com/512/5968/5968350.png" alt="Python" title="Python">
      <img src="https://cdn-icons-png.flaticon.com/512/5969/5969104.png" alt="XGBoost" title="XGBoost">
      <img src="https://cdn-icons-png.flaticon.com/512/5969/5969175.png" alt="RapidMiner" title="RapidMiner">
      <img src="https://cdn-icons-png.flaticon.com/512/732/732223.png" alt="Seaborn" title="Seaborn">
      <img src="https://cdn-icons-png.flaticon.com/512/919/919842.png" alt="NumPy" title="NumPy">
    </div>
  </div>

</body>
</html>
```

### Explanation:
- **Flexbox**: Used to align and space out the icons.
- **Hover Effect**: Icons enlarge when hovered for a more engaging user experience.

## Contribution Guidelines

To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b new-feature`).
3. Commit your changes (`git commit -m "Added a feature"`).
4. Push to the branch (`git push origin new-feature`).
5. Open a Pull Request.

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---

For more details or inquiries, feel free to reach out via issues or discussions in the repository!



