# Fruit Image Classification: A Model Comparison Study

Classification of fruit images using techniques such as the transfer learning, pruning, model trimming and custom model development.
An attempt to adapt the model to multi-label classification with real-life examples.

## Authors

Konrad Pawlik - konradpawlik@student.agh.edu.pl </br>
Jan Fiszer - fiszer@student.agh.edu.pl

## Conclusion

A thorough report detailing the project, the models selected and the decisions taken can be found in [AML-Fruits360-Report.pdf](https://github.com/Milan-Exchange/Advanced-Machine-Learning/blob/main/AML-Fruits360-Report.pdf)

## Prerequisite

- Python3
- numpy
- matplotlib
- pandas
- tensorflow
- tensorflow_model_optimization

## Source code

1. exploratory_data_analysis.ipynb 
2. transfer_learning.ipynb
3. custom_model.ipynb
4. multi_label_and_pruning.ipynb

## Data

* data
  * fruits-360_dataset
    * fruits-360
      * Training
      * Test
      * test-multiple_fruits

The original dataset contains images of the fruit in the native resolution, but these have been omitted due to their scarcity. </br>
Data can be downloaded from https://www.kaggle.com/datasets/moltean/fruits?datasetId=5857&sortBy=voteCount