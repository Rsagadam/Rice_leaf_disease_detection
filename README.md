# Rice Leaf Disease Detection

## Project Overview
This project aims to identify and classify different diseases affecting rice leaves using image processing and machine learning techniques. By detecting diseases early, farmers and agricultural experts can take preventive measures to ensure healthy crop production and reduce losses.

## Dataset
The project uses a dataset of rice leaf images, stored in a directory. Each image represents a specific condition of a rice plant, ranging from healthy to various diseases. The images are preprocessed to make them suitable for training a machine learning model.

## Structure
- **Data Preparation**: The initial cells handle the setup of the working directory and load the images from the `rice_leaf_diseases` directory.
- **Preprocessing**: The images are preprocessed to ensure they are standardized, with techniques such as resizing, normalization, and augmentation applied.
- **Model Training**: A convolutional neural network (CNN) is trained to classify the images. The model architecture is optimized for image classification tasks, with an emphasis on accuracy and generalization.
- **Evaluation**: The performance of the model is evaluated using metrics such as accuracy, precision, recall, and F1 score. A confusion matrix is also used to visualize classification performance.

## Getting Started

### Dependencies
- Python 3.7+
- TensorFlow or PyTorch
- OpenCV
- NumPy
- Matplotlib

Install dependencies using:

```bash
pip install -r requirements.txt
```

## Dataset
- Download or prepare a dataset of rice leaf images.
- Ensure the images are organized in folders representing different classes (e.g., healthy, bacterial blight, leaf blast).

## Deleting a Local Git Repository
- Open Terminal: Launch the Terminal application on your Mac.
- Navigate to the Parent Directory: Use the cd command to go to the directory that contains your repository.

```bash
cd /path/to/parent/directory
```

- Delete the Repository: Use the rm command to delete the repository folder:
```bash
rm -rf your-repository-name
```

## Deleting a Remote Repository (e.g., GitHub)
- Log In: Go to the website of the platform (e.g., GitHub) and log in to your account.
- Navigate to the Repository: Find the repository you want to delete in your list of repositories.
- Go to Settings: Click on the "Settings" tab, usually found at the bottom of the repository menu.
- Scroll Down to Danger Zone: Scroll down to the "Danger Zone" section.
- Delete Repository: Click on the "Delete this repository" button.
- Confirm Deletion: You will be prompted to type the repository name to confirm the deletion. Follow the instructions to complete the process.

## Important Notes
- Backup Important Data: Make sure to back up any important files or data before deleting a repository, as this action is irreversible.
- Permissions: Ensure you have the necessary permissions to delete the repository, especially in a team or organization setting.
