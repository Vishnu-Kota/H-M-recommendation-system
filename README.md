![image](https://user-images.githubusercontent.com/65905342/167622528-f6b7c3bc-8722-4a18-97ad-837bec400ed5.png)
# H-M-recommendation-system
A recommendation system created for H&amp;M created with the help of EDA(Exploratory Data Analysis) and ALS (Alternative Least Squares) which optimizes a users recommendations taking into considerations an account`s view history and uses matrix optimization to give the best possible recommendations.
We make use of 4 different csv files which are-articles.csv,customers.csv,transactions_train.csv and sample_submissions.csv.
We try to remove the null values from all those files and shape the data.
After optimizing each of the indiviadual files using matplotlib.img and seaborn, we visualize those images with the help of various graphs.
For customers we use this heatmap,
![image](https://user-images.githubusercontent.com/65905342/167623668-dec417dd-6840-4c7a-85b0-264c721ab8a9.png)

In this particular map the more close to one a matrix is to a particular account the more likely the customer will buy the product.

![image](https://user-images.githubusercontent.com/65905342/167623895-ababd633-751e-4c92-9040-1092b5aa3f4d.png)
This graph shows the variances of each customer`s age and what they are likely to buy.

![image](https://user-images.githubusercontent.com/65905342/167624287-e13669a3-7601-4cf0-9295-2c541e74d0f4.png)
The above graph shows the number of customers according to age.

For articles we use this graph
![image](https://user-images.githubusercontent.com/65905342/167626209-aed13325-e3e4-4b83-a4e6-2f234583a8b6.png)
This sorts various articles into various categories and displays the most common ones.

![image](https://user-images.githubusercontent.com/65905342/167626477-bcbd522c-edfa-46b4-adf0-531a5f03dd2d.png)
A heatmap of items on the articles file which displays how likely a person will buy the product or not.

This boxplot graph shows what different type of people buy different products.
![image](https://user-images.githubusercontent.com/65905342/167627267-ab13f340-25de-47ba-b50d-5883def60cb7.png)

Boxplot graph showing various articles using index values.
![image](https://user-images.githubusercontent.com/65905342/167627664-6880e86b-7043-4505-9433-4cc99248dc42.png)

The same principles used for transaction_train file.
![image](https://user-images.githubusercontent.com/65905342/167626839-43f1f04c-0858-45e0-9402-cb0aefb1211d.png)

This is logarithmic graph about the transactions done due to various accounts.
![image](https://user-images.githubusercontent.com/65905342/167627091-4b333087-566b-4665-ac5d-2cceed7c42f7.png)

