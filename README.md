# Text_classification_NB
* Text classification using MNNB (Sklearn) and own (Scratch) and compare the result.
* # Naive Bayes Text Classification

This project demonstrates text classification using Naive Bayes. It includes two parts:
1. Using sklearn's Multinomial Naive Bayes for text classification.
2. Implementing Naive Bayes from scratch and using it for text classification.

## Dataset

The dataset used is the "Twenty Newsgroups" dataset, which is available from the UCI Machine Learning Repository.

## Files

- `Project_Text_classification.ipynb`: Jupyter notebook containing the code for both the sklearn implementation and the custom Naive Bayes implementation.
- `README.txt`: This readme file.

## Instructions

1. **Prerequisites**: Make sure you have the following libraries installed:
    - numpy
    - pandas
    - scikit-learn

2. **Running the code**:
    - Open the `Project_Text_classification.ipynb` file in Jupyter Notebook or Jupyter Lab.
    - Run the cells sequentially to perform text classification using both sklearn's Multinomial Naive Bayes and the custom Naive Bayes implementation.

3. **Understanding the code**:
    - The notebook is divided into sections with comments explaining each step:
        - Loading and preprocessing the dataset.
        - Implementing and training the sklearn Multinomial Naive Bayes model.
        - Implementing Naive Bayes from scratch.
        - Comparing the results of both models.

## Results

- The accuracy and classification report for both the sklearn model and the custom model are displayed in the notebook.
- The performance comparison between the two models is also provided.

## Notes

- The dataset is fetched programmatically in the notebook, so there is no need to download it manually.
- The custom Naive Bayes implementation may not be as optimized as the sklearn implementation but serves as a good educational exercise.

## License

This project is licensed under the MIT License - see the LICENSE file for details.


