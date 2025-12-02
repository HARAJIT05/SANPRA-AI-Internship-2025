# SANPRA-AI-Internship-2025

This repository is organized into three main projects:

1.  **AI Face Detection**: A system that can detect and recognize faces from a live video stream.
2.  **Recommendation System**: A movie recommender system that suggests movies to users based on their ratings.
3.  **Tic-Tac-Toe**: A classic Tic-Tac-Toe game where you can play against an AI.

---

### 1. AI Face Detection

This project consists of three parts: creating a dataset of faces, training a face recognition model, and running the face recognition application.

**a. Create Dataset**

*   **File:** `Ai Face Detection/create_dataset.py`
*   **Purpose:**  Captures 150 images of a person's face from a webcam and saves them in a dataset folder.
*   **How to Run:**
    ```bash
    python "Ai Face Detection/create_dataset.py"
    ```
    You will be prompted to enter a user ID for the person whose face is being captured.

**b. Train Model**

*   **File:** `Ai Face Detection/train_deep.py`
*   **Purpose:** Trains a K-Nearest Neighbors (KNN) model on the dataset of faces created in the previous step. The trained model is saved as `trainer/deep_model.pkl`.
*   **How to Run:**
    ```bash
    python "Ai Face Detection/train_deep.py"
    ```

**c. Face Recognition**

*   **File:** `Ai Face Detection/face_recognition_app.py`
*   **Purpose:** Uses the trained model to recognize faces in a live video stream from a webcam.
*   **How to Run:**
    ```bash
    python "Ai Face Detection/face_recognition_app.py"
    ```

**d. Check GPU**

*   **File:** `Ai Face Detection/check_gpu.py`
*   **Purpose:** Checks if a GPU is available and detected by TensorFlow.
*   **How to Run:**
    ```bash
    python "Ai Face Detection/check_gpu.py"
    ```

---

### 2. Recommendation System

This project is a movie recommender system that uses collaborative filtering to recommend movies to users.

*   **File:** `RECOMMENDATION SYSTEM/movie_recommender.py`
*   **Purpose:**  Asks the user to rate a movie and then recommends other movies based on that rating.
*   **Dataset:** The movie data is located in the `RECOMMENDATION SYSTEM/mdb/` directory.
*   **How to Run:**
    ```bash
    python "RECOMMENDATION SYSTEM/movie_recommender.py"
    ```

---

### 3. Tic-Tac-Toe

This project is a command-line based Tic-Tac-Toe game that you can play against an AI.

*   **File:** `Tic-Tac-Toe/game.py`
*   **Purpose:**  Allows a human player to play Tic-Tac-Toe against an AI that uses the minimax algorithm.
*   **How to Run:**
    ```bash
    python "Tic-Tac-Toe/game.py"
    ```

---

## Authors

*   **Harajit Chandra Das**  - [GitHub Profile](https://github.com/harajit05
