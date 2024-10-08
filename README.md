# Pokémon Doppelganger

<br>

# Description:
"Pokémon Doppelganger" is an innovative application that employs facial recognition technology and machine learning to find the Pokémon species most closely resembling a user's facial features. By analyzing facial embeddings extracted from user images and comparing them with pre-computed embeddings of Pokémon species, the system identifies the closest match using cosine similarity.

# Features:
-> Facial Feature Extraction: Utilizes a pre-trained VGG16-based model to extract facial embeddings from user-provided images. <br>
-> Cosine Similarity: Computes cosine similarity between user embeddings and pre-computed embeddings of Pokémon species to find the closest match. <br>
-> Dynamic Data Loading: Loads Pokémon embeddings from a CSV file, enabling easy updates and scalability. <br>
-> Error Handling: Handles scenarios where no faces are detected in the input image gracefully, providing informative messages to the user. <br>

# Installation:

1) Clone the repository: git clone [https://github.com/LaKsHiT013/Pokemon-Doppelganger]
2) nstall the required Python packages: pip install -r requirements.txt
3) Ensure proper setup of OpenCV and TensorFlow libraries for image processing and machine learning functionalities.


# Usage:

1) Run the pokemon_doppelganger.py script.
2) Provide the path to the image containing your face when prompted.
3) The system will analyze the image, extract facial features, compare them with Pokémon embeddings, and output the most similar Pokémon species.


# Improvements:
-> Currently classifies only 7 species of Pokemon, can be increased.<br>
-> Instead taking only face and doing prediction the modelis highlt effected by the clothes and colour in the     background for prediction.

# Disclaimer:

This project is developed for educational and entertainment purposes only. It is not affiliated with or endorsed by The Pokémon Company.
