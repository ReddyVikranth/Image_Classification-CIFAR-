🧠 CIFAR-10 Image Classification with PyTorch
Welcome to my deep learning project where I train and evaluate convolutional neural networks on the CIFAR-10 dataset! This project focuses on building an image classification model using PyTorch and covers the full pipeline—from data loading to model training, evaluation, and plotting performance graphs.

Goal: Achieve high classification accuracy on CIFAR-10 using custom CNNs and training optimizations.

📂 Dataset
The CIFAR-10 dataset contains 60,000 32x32 color images in 10 classes, with 6,000 images per class:

Airplane

Automobile

Bird

Cat

Deer

Dog

Frog

Horse

Ship

Truck

The dataset is divided into 50,000 training images and 10,000 test images.

🔧 Features
📦 Built with PyTorch for flexibility and performance

🧠 Uses Convolutional Neural Networks (CNNs)

🔁 Implements Data Augmentation (Random Crop, Flip)

🧪 Includes Training & Validation loops

📉 Plots loss and accuracy curves

🚀 Designed to be easily extendable (try ResNet, etc.)

🛠️ Installation
Clone this repo:

bash
Copy
Edit
git clone https://github.com/ReddyVikranth/Image_Classification-CIFAR-.git
cd Image_Classification-CIFAR-
Install dependencies:

bash
Copy
Edit
pip install torch torchvision matplotlib
You're good to go! ✅

🚀 How to Run
Train the model:

bash
Copy
Edit
python train.py
Test the model:

bash
Copy
Edit
python test.py
Check training and validation graphs after the training completes.

📊 Results
Metric	Value (Example)
Training Acc.	82.5%
Validation Acc.	78.3%
Final Test Acc.	77.9%

Note: Results may vary based on training time, model changes, and hyperparameters.

📈 Visualization
After training, the script will plot:

📉 Loss vs Epochs

📈 Accuracy vs Epochs

These graphs help visualize how well the model is learning over time.

🧠 Future Improvements
Add support for pretrained models like ResNet or EfficientNet

Integrate TensorBoard or W&B for experiment tracking

Implement early stopping, learning rate scheduling, and model checkpointing

Try training on CIFAR-100

🤝 Contributing
Pull requests are welcome! If you find issues or have suggestions, feel free to fork and enhance this project.

📄 License
This project is open-sourced under the MIT License.

🙋‍♂️ Author
Built by Vikranth Reddy
Feel free to connect or raise an issue in the repo!
