# License Plate Recognition Project

## Project Overview
This project uses machine learning and computer vision techniques to detect and recognize license plates from video streams. It leverages technologies such as OpenCV, TensorFlow, and Keras to process video data, identify license plates, and recognize the alphanumeric sequences of the plates.

## Features
- **Real-Time License Plate Detection**: Detect license plates in real-time from video streams.
- **Character Recognition**: Utilize a Convolutional Neural Network (CNN) to accurately recognize the characters on the license plates.
- **Information Retrieval**: Fetch vehicle information using recognized license plate numbers through an external API.

## How It Works
1. **Video Processing**: The system processes video streams to detect potential license plates.
2. **License Plate Detection**: Uses Haar Cascade classifiers trained on license plate features to detect plates in video frames.
3. **Character Segmentation and Recognition**: Segments characters from the detected license plate and uses a CNN model to recognize these characters.
4. **Data Retrieval**: Retrieves detailed vehicle information from a registered API service based on the recognized license plate numbers.

## Visual Overview

## Visual Overview

![License Plate Recognition](https://github.com/nupurrathod/License_detection/blob/main/test2.jpeg)


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)

