# dL03-ANN
ANN Indepth Intuition


🧠 Artificial Neural Networks (ANN) in Deep Learning
🔍 Overview
Artificial Neural Networks (ANNs) are the foundational building blocks of deep learning. Inspired by the structure and function of the human brain, ANNs consist of interconnected layers of nodes (neurons) that transform input data into meaningful outputs through learned weights and activation functions.

🧩 Core Architecture
Input Layer: Accepts raw features (e.g., pixel values, sensor readings, embeddings).

Hidden Layers: One or more layers where neurons apply weighted sums and nonlinear activations to learn complex representations.

Output Layer: Produces final predictions (e.g., class probabilities, regression values).

Each neuron computes: $$ y = f\left(\sum_{i=1}^{n} w_i x_i + b\right) $$ Where:

𝑥
𝑖
: input features

𝑤
𝑖
: weights

𝑏
: bias

𝑓
: activation function (ReLU, sigmoid, tanh, etc.)

🚀 Role in Deep Learning
Deep learning extends ANNs by stacking multiple hidden layers, enabling the network to learn hierarchical features. This depth allows models to:

Detect edges → shapes → objects in images (CNNs)

Capture short-term and long-term dependencies in sequences (RNNs, LSTMs)

Learn semantic meaning in text (Transformers)

🧪 Training Process
Forward Propagation: Data flows through the network, producing predictions.

Loss Calculation: Measures error between predictions and ground truth.

Backpropagation: Gradients are computed and propagated backward.

Weight Update: Optimizers (e.g., SGD, Adam) adjust weights to minimize loss.

📈 Applications
Image classification (e.g., CIFAR-10, MNIST)

Time-series forecasting (e.g., energy demand)

Natural language processing (e.g., chatbots, sentiment analysis)

Smart grid optimization using hybrid ANN + LSTM models
