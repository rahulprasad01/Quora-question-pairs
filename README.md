# Quora-question-pairs


This project aims to clarify whether adding a contrastive learning signal offers any inherent benefit over the vanilla supervised learning setup. When given a dataset with features and labels, we recommend using an extra contrastive learning loss signal that allows the model to learn a richer, more encapsulating representation compared to the same model trained simply on the supervised signal. We hypothesise doing the former leads to highly performant models.
The dataset we are using is Quora Question Pair from GLUE Benchmark. We are using the dataset from GLUE Benchmark which gives us the train-test-val splits in .tsv format, which makes it super easy to open via pandas.
