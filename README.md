# CognifyAI
Machine-learning based diagnosis of alzheimer's disease using the DARWIN dataset. More information on the dataset can be found on the paper Cilia et al. (2022)


The program will ask for numerical values of metrics of various hanwriting tasks. The tasks are listed below.
For example, air_time1 would indicate the amoutn of time a user's pen was in the air for task 1. num_pendown7 would be the average times a user lifts the pen and puts it back down during the task.
All time values should be in milliseconds (ms)

1. Signature drawing   

2. Join two points with a horizontal line, continuously for four times   

3. Join two points with a vertical line, continuously for four times   

4. Retrace a circle (6 cm of diameter) continuously for four times   

5. Retrace a circle (3 cm of diameter) continuously for four times   

6. Copy the letters ‘l’, ‘m’ and ‘p’   

7. Copy the letters on the adjacent rows   

8. Write cursively a sequence of four lowercase letter ‘l’, in a single smooth movement   

9. Write cursively a sequence of four lowercase cursive bigram ‘le’, in a single smooth movement   

10. Copy the word ‘‘foglio’’   

11. Copy the word ‘‘foglio’’ above a line   

12. Copy the word ‘‘mamma’’   

13. Copy the word ‘‘mamma’’ above a line   

14. Memorize the words ‘‘telefono’’, ‘‘cane’’, and ‘‘negozio’’ and rewrite them   

15. Copy in reverse the word ‘‘bottiglia’’   

16. Copy in reverse the word ‘‘casa’’   

17. Copy six words (regular, non regular, non words) in the appropriate boxes   

18. Write the name of the object shown in a picture (a chair)   

19. Copy the fields of a postal order   

20. Write a simple sentence under dictation   

21. Retrace a complex form   

22. Copy a telephone number   

23. Write a telephone number under dictation   

24. Draw a clock, with all hours and put hands at 11:05 (Clock Drawing Test)   

Certain features will require external calculations or external programs. The external application included in the git will be required in parallel to use the program.

---

## How to Use the Application

1. **Download the Files and place the .exe and .joblib files in the same folder**
   
2. **Run the .exe File**: Double-click the .exe file in the folder and be sure to fullscreen the application.

3. **Enter the Data**: You’ll be asked to enter several health-related values. Just type the values into the fields provided.

4. **Get the Prediction**: After entering the values, click the "Submit" button. The tool will analyze the data using a pre-trained machine learning model and predict whether the person is a regular patient or has Alzheimer's disease.

5. **See the Results**: The prediction will be displayed, along with the confidence for the prediction.

---


---

## What You Need

Windows OS

---

## Troubleshooting

- **The app doesn’t launch**: Make sure you downloaded the `.exe` file correctly. If it's still not working, try restarting your PC and running the app again.
- **Missing Files**: If you receive an error about missing files or something undefined, please make sure that the `.joblib` files (`scaler.joblib`, `best_model.joblib`, `selector.joblib`) are in the same folder as the `.exe` file.
