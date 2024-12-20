Title : Impact of Outside Noise of Speech Volume

Contributions: Report Writing, Data Collection, Analysis, Model Training and Validation, Graph Plotting (sample contributions)

Member 1 Hallie Liu: Data Collection, Model Training and Validation
Member 2 Jason Chen: Data Collection, Analysis
Member 3 Sandy Son: Data Collection, Graph Plotting
Member 4 Sehwa Hong: Data Collection, Report Writing


Problem Statement
The objective of this project is to develop a sound detection application capable of monitoring frequencies and sensor data. The primary emphasis is on detecting voices and adjusting volume levels when individuals are in scenarios involving headphone use – whether they are wearing headphones, not wearing headphones, or using headphones with elevated sounds levels. By delivering precise and contextually relevant information, the application seeks to discern users’ self imposed sound pressure and its impact on their voice. 

Potential Applications of the Project
The developed sound sensor application has various potential applications. In public transport settings, it can alert users if their voice exceeds safe levels while wearing headphones, promoting awareness and preventing potential safety hazards. Additionally, in corporate settings, implementing the technology in meeting rooms will optimize audio levels based on the number of people present and their vocal volumes, ensuring effective communication. This application could assist users in calibrating noise-canceling headphones for optimal performance by analyzing ambient noise and adjusting the headphones accordingly. Finally, elderly could utilize the application to detect and control their volume levels while using headphones. 


Data Collection, Model Training, and Testing/ Analysis
Data Collection: Gather a diverse dataset of voice recordings in various scenarios, including different environments, background noises, and headphone usage. Including recordings of people wearing headphones, not wearing headphones, and using headphones with elevated sound levels. 
Model Training: Extract features from the voice data, such as frequency, amplitude, and duration of sounds. Manually label the dataset based on different sound scenarios (wearing headphones, not wearing headphones, and using headphones with elevated sound levels). 
Test/Analysis: Split the dataset into training, validation, and test sets for model evaluation. Perform cross-validation to ensure the model’s generalizability. 

Results
Graphs/Tables, Comparison charts to show the differences between each situation

Learnings from the Project
The project can be useful for real-world application if refined more. A personal lesson would be being more aware of my own volume when I have headphones on. However, for a broader application, it would be useful to analyze potential room for error when analyzing speech for other studies (for example, if a research study required participants to use headphones).

How to Improve the Project Further:
We would want to incorporate more scenarios in the future and possibly stress test the volume level of the speaker (how loud can the headphone volume be before the speaker’s volume reaches the peak?). We would also like to incorporate the possibility of allowing an immediate response to when the speaker passes a certain volume for better implementation in real world scenarios.

References:
Real-time Target Sound Extraction
https://ieeexplore.ieee.org/abstract/document/10094573?casa_token=A2ALJO73Yp0AAAAA:07fIgtLNymq3MyBqfzsKlDicWzctFHz7caTK9RpfiubMkQOkhbOOu4Gzxp-Nyte6maT1CKpVIQ
