
# Circle Detection with YOLOv8

This project demonstrates the process of training a YOLOv8 model to detect circles in images. The notebook contains a comprehensive pipeline for creating a synthetic dataset, training a custom YOLOv8 model, and evaluating its performance on circle detection tasks.

The notebook walks through the entire machine learning workflow, starting with the generation of a synthetic dataset containing images with randomly placed circles of various sizes and colors. This dataset is then used to train a YOLOv8 model specifically for circle detection. The training process is monitored and visualized using TensorBoard metrics, allowing for easy tracking of the model's performance over time. After training, the model is evaluated on a test set, and its inference capabilities are demonstrated on new images. 

## How to Run the Notebook

1. Open the notebook in Google Colab or a local Jupyter environment with GPU support.
2. Ensure you have the necessary dependencies installed, particularly the `ultralytics` package.
3. Mount your Google Drive if you're using Colab, as the dataset and model weights will be stored there.
4. Run the cells in order, following the comments and markdown explanations.
5. The notebook will guide you through dataset creation, model training, visualization of training metrics, and model evaluation.
6. After training, you can use the model to perform inference on new images by running the relevant cells at the end of the notebook.

