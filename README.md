# Caption-Generator-project
This project is a deep learning-based web application that generates human-like captions for uploaded images. It combines Convolutional Neural Networks (CNN) for visual feature extraction and Artificial Neural Networks (ANN) for language modeling to describe the content of images in natural language.

🖼️ Image Caption Generator using CNN & ANN (Flask Web App)
This project is a deep learning-based web application that generates human-like captions for uploaded images. It combines Convolutional Neural Networks (CNN) for visual feature extraction and Artificial Neural Networks (ANN) for language modeling to describe the content of images in natural language.

The model takes an image as input, processes it using a pre-trained CNN to extract key features, and then passes these features to an ANN-based language model to generate a relevant caption. This can be useful in applications such as image indexing, accessibility tools, visual content management, and more.

The web interface is built using Flask, a lightweight Python web framework. Users can upload an image through the browser, and the app will display both the image and the generated caption. The project is also structured in a way that it can be easily deployed online using platforms like Render, allowing others to use your model without needing to run Python code locally.

🔍 Features
Upload image and generate automatic captions

Deep learning model combining CNN and ANN

Flask-based web app with responsive UI

Easily deployable to Render or PythonAnywhere

Clean folder structure and beginner-friendly codebase

🧠 Technologies Used
Python

Flask

TensorFlow / Keras

PIL / OpenCV

HTML, CSS (for frontend)




git clone https://github.com/yourusername/image-caption-generator.git
cd image-caption-generator
pip install -r requirements.txt
python app.py
