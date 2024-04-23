# Methodology & Limitations

Utilizing the Scrum methodology has significantly contributed to the development of an AI-based license plate detection system, focusing on the specific goal of detecting and recognizing characters within an image. Scrum is a popular Agile framework that effectively manages the development process, emphasizing continuous improvement and testing throughout.



By breaking down the development process into manageable sprint sessions, Scrum allows for a more focused and productive approach. This methodology enabled me to concentrate on specific goals and tasks at hand, thereby increasing productivity and ensuring that each sprint's objectives were met effectively. One of the key benefits of using Scrum is its emphasis on addressing issues early in the development process. This approach helped reduce costs associated with fixing bugs and other issues, ensuring that the development process was efficient and cost-effective.&#x20;



In the case of this AI-based license plate detection system, the development was carried out with zero costs, demonstrating the effectiveness of the Scrum methodology in managing resources and reducing development expenses. In summary, Scrum's iterative approach, continuous improvement, and early issue detection significantly contributed to the successful development of an AI-based license plate detection system. By breaking down the development process into manageable sprints, focusing on specific goals, and addressing issues early, Scrum proved to be a valuable tool in managing the development process effectively and efficiently.



### Limitations

The limitations of the AI-based license plate detection system include the inability to recognize embossed number plates using OCR due to the lack of NVIDIA's dGPU and CUDA cores on macOS machines. This issue can be addressed in future developments by implementing a different OCR technology that supports macOS or by providing a macOS version with NVIDIA's dGPU and CUDA cores. Additionally, the current system is not designed for video capturing systems where license plates are captured and saved within a system in real-time. To overcome this limitation, the system can be enhanced with video processing capabilities, enabling real-time license plate detection and recognition from video feeds. This feature can be particularly useful in surveillance and traffic management applications.&#x20;



The AI-based license plate detection system can be further improved by addressing the limitations of OCR for embossed number plates and real-time video capturing and processing. These enhancements can expand the system's capabilities and make it more versatile for various applications.



### Beta Product

The beta product is within my private GitHub repository that can recognize the characters within the embossed number plate, due to dependency error with paddleocr during deployment the feature was removed from the deployed app. For beta testing the app that can both recognize the conventional and embossed license plate please feel free to email @ **ssarthak20@tbc.edu.np**&#x20;



#### More Training + More Epochs + More Dataset

The product had been developed through secondary dataset, the images that were trained for the model are avilable within the internet. Datasets were utilized from Kaggle and Roboflow. As mentioned earlier regarding the limitations of the number of epochs I could have trained my model in, through a paid Google Colab model I can possibly train the model for a much longer period of time (increasing the epochs) which can deal with better results



#### Primary Dataset Collection

I could not collect license plates all by myself as there are privacy concerns with whether people would want their license plates to be trained for creating a ML model. Therefore, secondary dataset has been utilized for it.&#x20;







