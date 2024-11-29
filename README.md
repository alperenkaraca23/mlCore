
```markdown
# Machine Learning Image Recognition Project

This project is a basic image recognition application that uses **Core ML** and a pre-trained model to identify objects in photos. Designed as a training exercise, it lays the groundwork for integrating machine learning capabilities into larger and more complex projects in the future.

## Features

- Object recognition using a pre-trained machine learning model.
- User-friendly interface for photo selection and result display.
- Fast and efficient image processing powered by Core ML.

## How It Works

1. **Core ML Integration**:
   - Explored Core ML documentation on [Apple Developer](https://developer.apple.com/documentation/coreml/) to understand how to integrate ML models into iOS projects.

2. **Pre-trained Model**:
   - Selected and integrated **MobileNetV2**, a lightweight and efficient model, as the most suitable option for this project.

3. **Interface Design**:
   - Created a simple and clean user interface:
     - **Photo Picker**: Allows users to upload or select an image from their library.
     - **Result Label**: Displays the predicted object name based on the uploaded image.

4. **Project Workflow**:
   - Integrated the model using Core ML tools.
   - Developed the UI with **Storyboard**.
   - Wrote the necessary Swift code to process the selected image and display predictions.

## Requirements

- Xcode 14+ 
- iOS 15+ 
- Swift 5.7+
- Core ML Model: [MobileNetV2](https://developer.apple.com/machine-learning/models/)

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your_username/ml-image-recognition.git
   cd ml-image-recognition
   ```

2. **Download the MobileNetV2 model**:
   - Visit [Apple's pre-trained models page](https://developer.apple.com/machine-learning/models/) and download the MobileNetV2 model.
   - Add the model file (`MobileNetV2.mlmodel`) to your Xcode project.

3. **Run the project**:
   - Open the project in Xcode and build it on a simulator or physical device.

## Video Demo

https://github.com/user-attachments/assets/c941b1e2-dac5-461c-bd2e-1a528bf95832



## Technologies Used

- **Core ML**: For integrating the pre-trained machine learning model.
- **MobileNetV2**: Lightweight and efficient ML model for image classification.
- **Swift**: Programming language for the project.
- **Storyboard**: For designing the user interface.

## Future Improvements

- Enhance the UI for a more polished look.
- Add support for custom-trained ML models.
- Enable real-time object recognition using the device camera.
- Expand the app to support multiple ML models for broader use cases.
