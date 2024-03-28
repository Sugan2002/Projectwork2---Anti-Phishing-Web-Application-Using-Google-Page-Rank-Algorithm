## Anti-Phishing Web Application Using Google Page Rank Algorithm
This project focuses on developing a robust anti-phishing system using machine learning techniques. By leveraging features extracted from URLs and employing machine learning models, it aims to accurately classify URLs as either legitimate or phishing. The system's effectiveness is validated through model training, evaluation, and deployment via a Flask web application.

## About
This project revolves around the development of an advanced anti-phishing system using machine learning methodologies. Phishing, a prevalent cyber threat, involves deceptive techniques aimed at acquiring sensitive information from users. Traditional methods for identifying phishing attempts often fall short due to the evolving nature of cyber threats. Therefore, this project proposes an innovative solution that harnesses the power of machine learning algorithms to detect and thwart phishing attempts effectively.

The system employs a multifaceted approach to phishing detection. It begins by extracting relevant features from URLs, encompassing various aspects such as URL length, presence of IP address, domain age, and redirection count. These features are then utilized as input for machine learning models trained on labeled datasets containing examples of both legitimate and phishing URLs. Leveraging supervised learning techniques, the models learn to discern patterns indicative of phishing behavior, thereby enabling accurate classification of URLs.

To ensure the system's robustness and efficacy, rigorous evaluation is conducted using metrics such as accuracy, precision, recall, and F1-score. Additionally, the system's performance is assessed through receiver operating characteristic (ROC) analysis, providing insights into its ability to balance true positive and false positive rates.

Furthermore, the project encompasses the development of a user-friendly web interface using Flask, allowing users to input URLs and receive instant feedback on their legitimacy. This interface serves as a practical implementation of the anti-phishing system, providing a seamless experience for users seeking protection against cyber threats.

Overall, this project represents a comprehensive endeavor to combat phishing attacks through the integration of machine learning, data analysis, and web development techniques, contributing to the enhancement of cybersecurity in the digital landscape.

## Features
- Incorporates advanced neural network techniques for robust performance in phishing detection.
- Utilizes a framework-based application architecture to facilitate seamless deployment and maintenance.
- Designed for high scalability to accommodate varying workload demands and user traffic.
- Optimized for reduced time complexity, ensuring efficient processing and response times.
- Includes a specific scope for implementing a Chatbot response model, utilizing JSON data format for streamlined communication and integration.

## Requirements
- Web Server: Requires a web server environment such as Apache or Nginx for hosting the application.
- Programming Language: Python 3.x for server-side scripting and implementing the machine learning models.
- Framework: Flask or Django for building the web application framework.
- Machine Learning Libraries: Scikit-learn for implementing machine learning models, such as logistic regression, decision trees, or neural networks.
- Data Collection: Mechanism for gathering datasets containing labeled examples of phishing and legitimate URLs for training and evaluation.
- Data Preprocessing: Methods to clean and normalize URLs, extract relevant features, and prepare them for input into machine learning models.
- Google PageRank Integration: Incorporate the Google PageRank algorithm as a feature in the phishing detection model.
- Model Training: Design and train machine learning models using the prepared datasets, employing techniques like cross-validation to assess performance and prevent overfitting.
- Model Evaluation: Evaluate model performance using metrics such as accuracy, precision, recall, F1 score, and ROC-AUC score.
- User Interface: Develop a user-friendly interface for users to interact with the application, input URLs, and view phishing detection results.


## System Architecture

![Screenshot 2024-03-28 105714](https://github.com/Sugan2002/Projectwork2---Anti-Phishing-Web-Application-Using-Google-Page-Rank-Algorithm/assets/77089743/98912f68-706f-4947-8561-79a2710c1d5b)


## Output

#### Output1 - Home Page

![Screenshot 2024-03-28 000147](https://github.com/Sugan2002/Projectwork2---Anti-Phishing-Web-Application-Using-Google-Page-Rank-Algorithm/assets/77089743/a4ecbb4d-311b-4a62-a55c-d3bdb3fa8d21)

#### Output2 - Phishing URL detected

![WhatsApp Image 2024-03-16 at 9 50 29 PM](https://github.com/Sugan2002/Projectwork2---Anti-Phishing-Web-Application-Using-Google-Page-Rank-Algorithm/assets/77089743/3befc9a5-ccdc-40f9-ac16-71720b446de0)

#### Output3 - Legitimate URL detected

![WhatsApp Image 2024-03-16 at 9 50 31 PM](https://github.com/Sugan2002/Projectwork2---Anti-Phishing-Web-Application-Using-Google-Page-Rank-Algorithm/assets/77089743/f085ae62-7313-43ed-9b12-f0f7111ae4ef)

Detection Accuracy: 92.4%


## Results and Impact
The Anti-Phishing Web Application utilizing the Google PageRank algorithm significantly improves online security by accurately identifying and blocking phishing websites. By integrating advanced machine learning techniques with the renowned PageRank algorithm, the application effectively distinguishes between legitimate and malicious URLs, safeguarding users from potential cyber threats.

This project's implementation empowers users to browse the internet with confidence, mitigating the risk of falling victim to phishing attacks. By providing real-time phishing detection, the application enhances online safety and fosters a more secure digital ecosystem.

The impact of this project extends beyond individual users to businesses, organizations, and internet service providers, offering a scalable solution to combat phishing attempts at a broader level. By reducing the prevalence of phishing attacks, the application helps protect sensitive information, safeguard financial assets, and preserve the integrity of online transactions.

Overall, the Anti-Phishing Web Application with Google PageRank integration contributes to fostering a safer online environment, promoting trust and security in the digital realm.

## Articles published / References
[1]	  Sumitra Das Guptta, Khandaker Tayef Shahriar, Hamed Alqahtani, Dheyaaldin Alsalman & Iqbal H. Sarker, " Modeling Hybrid Feature-Based Phishing Websites Detection Using Machine Learning Techniques." (2022)

[2]	  Vedantika Jagtap, Vaishnavi Baraskar, Vaibhavi Gavali, Bhakti Jadhav, Suvarna Sonavane, "PHISHING WEBSITE DETECTION [DL]." (2024)

[3]	  Mohith Gowda HR, Adithya MV, Gunesh Prasad S & Vinay S, "Development of anti-phishing browser based on random forest and rule of extraction framework." (2020)

[4]	Jian Mao; Wenqian Tian; Pei Li; Tao Wei; Zhenkai Liang. " Phishing-Alarm: Robust and Efficient Phishing Detection via Page Component Similarity." (2022)

[5]	Chidimma Opara a, Yingke Chen b, Bo Wei., " Detecting phishing web pages by exploiting raw URL and HTML characteristics.”. (2019)





