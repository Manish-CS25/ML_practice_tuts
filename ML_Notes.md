
# Chapter-1 The Machine Learning Landscape

- **Machine Learning** is about making machines get better at some task by learning from data, instead of having to explicitly code rules.

- **Types of ML Systems**: There are many different types of ML systems: supervised or not, batch or online, instance-based or model-based, and so on.

- **ML Project Workflow**:
  - Gather data in a training set.
  - Feed the training set to a learning algorithm.
    - If the algorithm is **model-based**, it tunes some parameters to fit the model to the training set (i.e., to make good predictions on the training set itself), and then hopefully it will be able to make good predictions on new cases as well.
    - If the algorithm is **instance-based**, it just learns the examples by heart and uses a similarity measure to generalize to new instances.

- **Challenges**:
  - The system will not perform well if your training set is too small, or if the data is not representative, noisy, or polluted with irrelevant features (garbage in, garbage out).
  - Your model needs to be neither too simple (in which case it will underfit) nor too complex (in which case it will overfit).

- **Model Evaluation and Fine-tuning**:
  - Once you have trained a model, you don’t want to just “hope” it generalizes to new cases. You want to evaluate it, and fine-tune it if necessary.


