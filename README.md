# Neural-Network-Compression-Techniques-For-Deploying-AI-Models-On-Mobile-Devices-In-Rural-India

This project explores and implements neural network compression techniques to enable the deployment of AI models on low-end mobile devices, especially in rural areas of India. Due to limited hardware, memory, and poor internet access, running large AI models in such environments is challenging. This system provides an intelligent solution by recommending the most suitable compression method based on various constraints.

💡 Project Objective

To bridge the digital divide by helping AI models run efficiently, offline, and accurately on budget smartphones. The system uses machine learning algorithms to suggest the best compression technique for a given model scenario.

⚙️ Features

* Input form to enter AI model characteristics (size, accuracy, energy, etc.)
* Predicts the best compression technique: Pruning, Quantization, or Distillation
* Supports Random Forest, Decision Tree, and CNN-based prediction engines
* Web interface built using Flask
* Supports offline-first deployment logic

 🛠️ Technologies Used

* Python
* Scikit-learn (Random Forest, Decision Tree)
* TensorFlow / Keras (CNN model)
* Flask (for web application)
* HTML, CSS (frontend)
* Pandas, NumPy (data handling)
* Pickle (model saving)

📂 Dataset

A CSV file containing various AI model configurations and their pre- and post-compression performance details is used for training.

🚀 How It Works

1. User logs in or signs up on the web app
2. Enters technical details about the AI model and device conditions
3. Selects the desired algorithm (RF, DT, CNN)
4. The system predicts and displays the best compression method
5. Accuracy and performance are visualized on a dashboard

🌐 Use Cases

* AI-based crop disease detection in agriculture
* Basic offline healthcare diagnostics
* Educational tools for low-bandwidth environments

📌 Project Benefits

* Makes AI models accessible in remote and rural regions
* Supports offline operation without cloud dependency
* Promotes digital equity and inclusive AI deployment

