# Speech-Recognition-System
The Speech Recognition System is an artificial intelligence-based system that recognizes and transcribes spoken language into written text or other forms of output.

![image](https://user-images.githubusercontent.com/117058119/225616077-a67abb01-2b53-4dca-8f6b-e036035b45f8.png)

Inspiration:

The inspiration for creating speech recognition systems can be traced back to the desire to enable computers to interact with humans more naturally and efficiently. The ability to understand and interpret human speech would allow computers to perform tasks that previously required human intervention, such as transcribing audio recordings or responding to voice commands.
Early research into speech recognition systems began in the 1950s, and progress accelerated in the 1970s with the development of Hidden Markov Models (HMMs) and Dynamic Time Warping (DTW) algorithms. These techniques enabled computers to recognize isolated words and simple phrases accurately.
In the 1980s, the development of artificial neural networks and the availability of more powerful computers led to significant advances in speech recognition technology. With deep learning techniques in the 2010s, speech recognition systems became even more accurate and robust, allowing for real-time transcription and voice-controlled interfaces.
Today, speech recognition systems are used in various applications, from virtual assistants like Siri and Alexa to automated customer service and transcription services. The development of speech recognition technology promises to make human-computer interaction even more seamless and intuitive in the coming years.

![image](https://user-images.githubusercontent.com/117058119/225616158-c66ea81c-c106-4626-b873-2f1846bf6aef.png)

What does it do?

A speech recognition system using RNN (Recurrent Neural Network) is a deep learning model that teaches sequential data, such as sp processes. Our system trains the model on a large dataset of speech samples and their corresponding transcriptions. The RNN architecture allows the model to analyze the audio signal in a time-dependent manner, considering the temporal dependencies between different parts of the audio signal.
The RNN model typically consists of several layers of recurrent cells, each of which takes in an input vector and a hidden state vector from the previous time step. The isolated state vector is updated at each time step based on the input vector and the last remote state vector, allowing the model to learn temporal patterns in the input data.

![image](https://user-images.githubusercontent.com/117058119/225616324-1fb5ebc6-e0e9-4162-9e89-5df74bba6582.png)

Once the RNN model is trained, it can transcribe new speech samples by processing the audio signal in a time-dependent manner and outputting a sequence of phonemes or words corresponding to the input audio. The RNN model can also be combined with other deep learning models, such as convolutional neural networks (CNNs) and transformer models, to improve speech recognition accuracy.

![image](https://user-images.githubusercontent.com/117058119/225616385-ed9a55f2-d789-447c-9658-0897f185e929.png)

Overall, a speech recognition system using RNN is a powerful tool for converting audio signals into text and has many practical applications, including virtual assistants, speech-to-text transcription, and automated call centers.

![image](https://user-images.githubusercontent.com/117058119/225616188-9958b20a-b7b1-4366-bae4-2495c080a207.png)

How we built it?

First, we import libraries.
We understand the data.

![image](https://user-images.githubusercontent.com/117058119/225616506-65e18f2a-41d0-4e05-bfbe-24f71a7b22c6.png)

![image](https://user-images.githubusercontent.com/117058119/225617906-7e9d853e-b0ad-461a-9fa9-1490f767deb9.png)


Create a Correlation and visualize it.
Test Different Models and find the best model out of it.
Train the model on intel oneAPI and Speech recognition API.

![image](https://user-images.githubusercontent.com/117058119/225617308-d887d042-8946-4287-91b6-2d0eb3ed856a.png)

Save the Model.

![image](https://user-images.githubusercontent.com/117058119/225616005-67aace2f-d28b-42ee-a5cf-8945dc6ec8b0.png)

What I learned from one API
✅Building application using intel oneDAL: The Intel one API Data Analytics Library (oneDAL) contributes to the acceleration of extensive data analysis by providing highly optimized algorithmic building blocks for all phases of data analytics (preprocessing, transformation, analysis, modeling, validation, and decision making) in batch, online, and distributed processing modes of computation. The library optimizes data ingestion and algorithmic computation to increase throughput and scalability.

✅Machine Learning: I likely learned about different machine learning algorithms and how they can be applied to transcript speech and make recommendations for farmers.

✅Data Analysis: I likely gained experience collecting and analyzing large amounts of data, including speech patterns and noise separation, to train our machine learning models.

✅Collaboration: Building a project like this likely required collaboration with a team of experts in various fields, such as speech recognition, machine learning, and data analysis, and I probably learned the importance of working together to achieve common goals.

These are just a few examples of the knowledge and skills I likely gained while building this project. Producing a speech recognition application is a challenging and rewarding experience requiring technical expertise and auditory knowledge.
