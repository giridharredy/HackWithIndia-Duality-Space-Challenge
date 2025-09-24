# Duality AI's Space Station Challenge Submission
**Participant:** Giridhar reddy Singam

## Project Summary
This project addresses the Duality AI Space Station Challenge by training a YOLOv8 model on a synthetic dataset to detect seven critical safety items. The goal is to demonstrate the effectiveness of using synthetic data to build reliable safety monitoring systems for inaccessible environments like space.

---

## Final Results
The model was successfully trained for 60 epochs, completing in approximately 2 hours in a Google Colab environment.

The final model achieved a **Mean Average Precision (mAP@0.5) of 0.755 (75.5%)** on the validation set.

**Performance Metrics Screenshot:**
*(To show your image here, first upload it to the `results_screenshots` folder on GitHub, then edit this README file on GitHub and drag-and-drop the image file into this spot.)*
![Performance Metrics]<img width="2400" height="1200" alt="results" src="https://github.com/user-attachments/assets/d6aff969-4430-45d3-94be-108717f30f4a" />



---

## **Important Note on Trained Model Files**
The model training and validation completed successfully. Unfortunately, the Colab session was disconnected before the final output artifacts (the `.pt` model weights, confusion matrix graph, etc.) could be saved to permanent storage. The results and images presented in this repository are from screenshots taken from the completed run, and the included `.ipynb` notebook is the final, working code that produced these results.

---

## How to Run the Code
1.  Upload the hackathon dataset ZIP files to a `duality` folder in your Google Drive.
2.  Open the `duality.ipynb` notebook in Google Colab.
3.  Ensure the file paths in Cell 3 point to your dataset files.
4.  Run all cells from top to bottom. The script will install dependencies, prepare the data, and train the model.

---

## Sample Detections
Below are sample prediction images from the successful validation run.


![val_batch0_pred](https://github.com/user-attachments/assets/04b6725c-acad-42b0-8256-c3143628cb17)
![val_batch1_pred](https://github.com/user-attachments/assets/fc6ff68a-5120-44bf-bf9d-632241449f79)
