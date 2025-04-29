# Machine Learning Assignment

---

![Image](https://github.com/user-attachments/assets/9ebe1846-8ca9-45bd-9a4a-856029e8666c)

---

## Assignment
This assignment requires applying various machine learning techniques to a diabetes dataset with clinical features such as age, BMI, glucose levels, and pregnancy history. The objective is to predict diabetes diagnosis (positive or negative) by building models like **logistic regression, Naïve Bayes, KNN, classification trees, random forests, boosted trees, and SVMs**. Students must split the data, evaluate models on a test set, and compare their performances. <br />
Additionally, the assignment involves selecting the two best models, addressing model uncertainty, and suggesting a method to combine classifiers. Unsupervised learning tasks like K-means and hierarchical clustering are also required, analyzing clustering results for positive and negative diagnoses separately. A clear and concise final report, limited to 12 pages, is expected. <br />
[Assignment Details](https://drive.google.com/file/d/1BvOFGqPXW4nUlrlY1DGVzyr9TTyNuGLh/view?usp=drive_link)

---

## Result
The analysis began by exploring the relationships between variables in the diabetes dataset, which included features like Age, BMI, Glucose, Blood Pressure, and Pregnancy history. After splitting the dataset into training and testing sets, multiple models were built and evaluated.<br />
A naïve classifier baseline yielded an error rate of 38.8%. Logistic regression improved performance, achieving an error rate of 24.1%, while logistic regression with regularization slightly worsened it to 25.4%. Logistic regression with PCA resulted in a higher error rate of 30.4%. Naïve Bayes and KNN models showed error rates of 26.3% and 27.2%, respectively. Single classification trees performed less effectively with a 29.9% error rate. Ensemble methods like Random Forests and Boosted Trees performed moderately well (around 24%-27% error).<br />
Support Vector Machines (SVM) emerged as the best-performing model, achieving the lowest error rate of 23.2%. Combining Logistic Regression and SVM models using an ensemble method resulted in a slightly higher error rate of 25.8%. Clustering methods (K-Means and Hierarchical Clustering) were also applied separately for positive and negative diabetes cases to explore underlying patterns in the dataset.<br />
Overall, SVM, Logistic Regression, and Random Forest were identified as the best-performing models. Combining classifiers offered promising results but didn't significantly outperform the best individual models.<br />
[Full Result](https://drive.google.com/file/d/1ts_je9x-r3XFnHStCjk4UUHRRVMKMfTB/view?usp=drive_link)
