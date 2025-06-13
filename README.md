# Divine Vision - Comparative Analysis for Image Caption Generation for Indian-Deities

The project includes a comparative analysis of five different models: ResNet50, ResNet152, DenseNet201, InceptionV3, and MobileNetV2. The analysis evaluates the performance of these models using metrics such as ROUGE, METEOR, and BLEU scores. Based on the evaluation, DenseNet201 emerged as the most accurate model for caption generation among the five. 
## Models Comparison

- **ResNet50:** Utilizes a deep architecture with 50 layers and residual connections to combat the vanishing gradient problem, allowing for the training of very deep networks with improved accuracy.

- **ResNet152:** An even deeper version of the ResNet model with 152 layers, providing enhanced performance on complex tasks due to its increased depth and residual connections.

- **DenseNet201:** Features 201 layers with dense connections between layers, ensuring maximum information flow and reducing the vanishing gradient problem, leading to improved efficiency and performance.

- **InceptionV3:** Employs an inception architecture with 48 layers that includes factorized convolutions, aggressive regularization, and auxiliary classifiers, achieving high accuracy with computational efficiency.

- **MobileNetV2:** Optimized for mobile and edge devices with 53 layers, it uses depthwise separable convolutions and an inverted residual structure, offering a good trade-off between latency and accuracy.

## Evaluation Metrics
- **ROUGE SCORE:** Measures summary quality by comparing overlap with reference summaries. Higher scores indicate better content coverage.

- **METEOR SCORE:** Evaluates translation quality considering matches, synonyms, and order. Higher scores mean better semantic accuracy.

- **BLEU SCORE:** Assesses translation quality by comparing n-gram matches with reference translations. Higher scores indicate better fluency and precision.

## Dependencies
This project uses the following technologies and frameworks:

- Python: Python is a high-level, dynamically typed programming language known for its simplicity and readability.
- https: A package for creating api calls to establish a communication medium b/w backend and frontend.
- Jupyter Notebook: It is an open-source web application that allows you to create and share documents containing live code, equations, visualizations, and narrative text.
- [Divine Vision Mobile Application]()
- [Divine Vision Flask Server](https://github.com/Kaizoku01/Divine-Vision-Flask-Server)

## Conclusion
Based on the comparative analysis and evaluation metrics, DenseNet201 demonstrated superior performance in terms of accuracy for caption generation of Indian god and goddess images. Consequently, DenseNet201 was chosen for integration into the Flask backend of the mobile application.

## License
Basic MIT licensed

## Contributing
Contributions to this project are welcome! If you'd like to contribute, please follow the usual GitHub flow: fork the repository, make your changes, and submit a pull request.
