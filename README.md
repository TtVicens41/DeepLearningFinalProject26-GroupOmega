# DeepLearningFinalProject26-GroupOmega
Deep Learning Final Project UPF 2026 - Facial Keypoint Detection - Group Omega

## Repository Contents

This repository includes the main deliverables for the project:

- `final_report.pdf`: the final project report.
- `finalPresentation.pdf`: the slides used during the project presentation.
- `finalProject_template.ipynb`: the main notebook where the full project workflow was developed.
- `PretrainedeModel/`: a folder containing the notebook from which it was extracted the pretrained model.

## Running the Project

To run the project code, you will need a Kaggle API token. Add your token in the first cell of the notebook, replacing the `<your-kaggle-token>` placeholder.

If you want to run the pretrained model in Section 8, you need to download the model executting the following command

kaggle kernels output adavi214/transfer-learning-facial-features -p /path/to/dest

(Here you will find the instructions to download the kaggle CLI https://github.com/Kaggle/kaggle-cli/blob/main/docs/README.md)

Then, make sure to update the model path in the first block at Section 8 so it matches the folder structure and configuration of your local project setup.
