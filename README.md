# Virtual-Makeup-Try-On-System

It is an application to help users to visualize how makeup looks on them by using CNN model to apply makeup products. It implements features like face landmark detection using machine learning image recognition to try products. This application is used for virtual makeup try on for lipstick, eye brows and kajal.

## Model Workflow
<img width="328" alt="image" src="https://user-images.githubusercontent.com/79396759/217233752-999bd3c9-c7f4-4b16-9ef4-56ed53e3ac83.png">

In the above architectural diagram the input is taken either from webcam or input image. After the image preprocessing steps, face landmark detection algorithm is used to determine the facial keypoints of lips, eyebrows and eyes and then the mask is applied on the facial region and extract the face part and then the color is wrapped on the masked image and then placed this on the original image and that is the final image after applying makeup.

## CNN Architectural Diagram
<img width="358" alt="image" src="https://user-images.githubusercontent.com/79396759/217234024-48cd4053-bbe3-401c-869d-4efcf4640559.png">
