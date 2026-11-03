1. Data Format (100% Match): All 9,900 rows, 25 columns, 50 Hz sampling, and 6 posture classes match the paper's specifications with zero missing values.
2. Angle Estimation: IMU pitch and roll correlate strongly with the reference angles (r > 0.99), matching Table 2 in the paper.
3. Model Performance on Unseen Subjects: 
   - Testing across unseen subjects (Leave-One-Subject-Out), the baseline achieves ~70% accuracy, which aligns closely with the paper's baseline (76%).
   - The multi-branch deep model reaches 94%.
4. Expected Posture Confusion: As noted in the paper, bending postures are recognized with high accuracy, while sitting straight and standing upright show minor expected overlap due to very close angles (~3°)
