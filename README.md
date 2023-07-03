# American Sign Language (ASL) Recognition

This project aims to build and train a deep learning model to recognize American Sign Language (ASL) gestures corresponding to the signs 'A', 'B', and 'C'. The code is written in Python using TensorFlow and Keras. The dataset consists of preprocessed hand gesture images representing the three different signs.

## Getting Started

### Prerequisites

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/asl-recognition.git
cd asl-recognition
```

2. Install the required dependencies:

```bash
pip install tensorflow keras numpy matplotlib
```

## Usage

1. Run the main script to load the ASL dataset, visualize the training data, examine the dataset statistics, and train the model:

```bash
python main.py
```

2. Once the model is trained, test its accuracy on the test set:

```bash
python test.py
```

3. If you want to visualize some mislabeled examples:

```bash
python visualize_mistakes.py
```

## Model Architecture

The model consists of a series of convolutional layers followed by max-pooling layers. The final layer is a softmax layer for multi-class classification. The summary of the model architecture can be found in the code.

## Dataset

The ASL dataset used in this project contains images of hand gestures for 'A', 'B', and 'C' signs.

## Results

After training the model for a few epochs, the test accuracy achieved is approximately 78.5%.

## Contributing

Contributions to this project are welcome. Please create a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to the creators of the ASL dataset used in this project.

Feel free to modify the README file according to your preferences and add more details about the project, results, and other relevant information.



