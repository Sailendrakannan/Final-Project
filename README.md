Password Strength Checker using Machine Learning and Deep Learning

Table of Contents
1. Introduction
   - Background Research
   - Summary of Literature Review
   - Research Questions
   - Tools and Techniques Used
2. Summary of Progress to Date
   - Research
   - Data Description
   - Methodology
   - Progress
3. Consideration of Ethical, Legal, and Social Issues
4. Project Timeline
5. References


Introduction
Passwords have become an essential component of modern life. A typical computer user requires passwords for multiple activities such as accessing websites, databases, networks, and applications. Given the increasing dependency on passwords, selecting and using strong passwords has never been more critical. However, users tend to choose weak and easily guessable passwords, which makes them vulnerable to cyber threats. This project aims to develop a password strength checker using machine learning (ML) and deep learning (DL) techniques to assess the strength of user-generated passwords effectively.

Background Research
Various factors influence password strength, including composition policies, environment constraints, and user behavior. Research has shown that users often reuse or slightly modify passwords, making them vulnerable to attacks. Traditional password strength meters rely on heuristic approaches, which may not provide an accurate assessment of security. Machine learning models can improve password strength evaluation by learning from large datasets and identifying patterns in weak passwords.

Summary of Literature Review
| Title | Authors | Model | Result |
|---|---|---|---|
| Password Strength Prediction using Supervised Machine Learning Techniques | Vijaya MS | Naïve Bayes | Accuracy: 0.73 |
| Building a Multi-class Password Strength Generator and Classifier Model by Augmenting Supervised Machine Learning Techniques | Sakya Sarka | Decision Tree | Accuracy: 0.53 |
| Real-Time Password Strength Analysis on a Web Application Using Multiple Machine Learning Approaches | Umar Farooq | Naïve Bayes | Accuracy: 0.83 |

Research Questions
1. How well can user-generated password strength be evaluated using machine learning algorithms?
2. How do various models' performance measures, such as accuracy, precision, recall, and F1-score, differ from one another, and which model exhibits the best overall performance?
Tools and Techniques Used
- **Programming Language:** Python
- **Development Environment:** Anaconda Navigator
- **Libraries:** Sklearn, NumPy, Pandas, Matplotlib, TensorFlow, Keras
- **Visualization:** Tableau

Summary of Progress to Date

Research
Various password strength meters exist, including Google Password Meter, Microsoft Password Checker, and The Password Meter, but they rely on simple lexical rules. Machine learning models offer a more sophisticated approach to password strength classification.

Data Description
Dataset used: [Password Strength Classifier Dataset](https://www.kaggle.com/datasets/bhavikbb/password-strength-classifier-dataset)
- Rows: 669,639
- Columns: 2 (password, strength)

Methodology
1. Data Collection (Kaggle dataset)
2. Data Preparation and Exploratory Analysis
3. Feature Engineering and Dataset Partitioning
4. Model Selection and Training
5. Performance Evaluation
6. Final Model Application and Reporting

Progress
- Data collection and preliminary analysis completed
- Research articles reviewed for insights
- Tableau visualization in progress
- Next step: Model training and evaluation

Consideration of Ethical, Legal, and Social Issues
Ethical and legal compliance is critical in password security applications. Key considerations include:
- **User Privacy:** Ensure user data is anonymized
- **Legal Compliance:** Adhere to data protection regulations
- **Bias Prevention:** Avoid biases in model training
- **Transparency:** Clearly explain model decisions to users

Project Timeline
| Task | Week 1 | Week 2 | Week 3 | Week 4 | Week 5 | Week 6 | Week 7 | Week 8 | Week 9 | Week 10 |
|---|---|---|---|---|---|---|---|---|---|---|
| Analysis of the Problem | ✓ | | | | | | | | | |
| Investigating the Dataset | ✓ | ✓ | | | | | | | | |
| Preparing the Data | | ✓ | ✓ | | | | | | | |
| Conducting Exploratory Data Analysis | | | ✓ | ✓ | | | | | | |
| Training the Models | | | | ✓ | ✓ | | | | | |
| Evaluating Model Performance | | | | | ✓ | ✓ | | | | |
| Interpreting and Analyzing Results | | | | | | ✓ | ✓ | | | |
| Applying the Final Model | | | | | | | ✓ | ✓ | | |
| Reporting & Documentation | | | | | | | | ✓ | ✓ | ✓ |

References
1. Bergadano, F., Crispo, B., & Ruffo, G. (1997). Proactive password checking with decision trees. ACM Conference on Computer and Communications Security.
2. Melicher, W., et al. (2017). Better passwords through science (and neural networks). USENIX Security Symposium.
3. Hong, K. H., & Lee, B. M. (2022). A Deep Learning-Based Password Security Evaluation Model. Applied Science, 12(5), 2404.
4. LeCun, Y., Bengio, Y., & Hinton, G. (2015). Deep learning. Nature, 521(7553), 436-444.
5. Ur, B., Kelley, P. G., Komanduri, S., et al. (2012). How does your password measure up? The effect of strength meters on password creation. USENIX Security Symposium.

 How to Use This Repository
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/password-strength-checker.git
   ```
2. Navigate to the project directory:
   ```sh
   cd password-strength-checker
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the password strength model:
   ```sh
   python password_strength.py
   ```




