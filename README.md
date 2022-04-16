# conde_nast
Conde Nast Data Science Hiring Challenge


Preferred UI theme

You are working in an e-commerce company. The management of the company has recently changed the UI of the website. Your company has conducted a survey among the users to collect their views on the new UI update.

**Task**

You are required to build a machine learning model that can predict the preferred UI theme, given a user’s UI engagement information.

**Dataset description**

The dataset folder contains the following files:

*   train.csv:  15150 x 16
*   test.csv:  1850 x 15
*   sample\_submission.csv: 5 x 2

The columns provided in the dataset are as follows:

|  Column name  |  Description  |
| --- | --- |
| CustomerID | Represents a unique identification of a user |
| Age | Represents the age of the user  |
| Gender | Represents the gender of the user  |
| City | Represents the city in which the user lives |
| State | Represents the state in which the user lives |
| No_of_orders_placed | Represents the total number of orders placed by a customer |
| Sign_up_date | Represents the date when a customer started using the website. |
| Last_order_placed_date | Represents the last date when the customer placed the order |
| is_premium_member | Represents whether a customer is a premium member or not. ( 0 or 1)  |
| Women’s_Clothing | Represents user’s engagement score in Women’s_Clothing section ( 0 to 10 ) |
| Men’s_Clothing | Represents user’s engagement score in Men’s_Clothing section( 0 to 10 ) |
| Kid’s_Clothing | Represents user’s engagement score in Kid’s_Clothing section ( 0 to 10 ) |
| Home_&_Living | Represents user’s engagement score in  Home_&_Living section ( 0 to 10 ) |
| Beauty | Represents user’s engagement score in Beauty products section ( 0 to 10 ) |
| Electronics | Represents user’s engagement score in  Electronics products section( 0 to 10 ) |
| Preferred_Theme | Represents the preferred theme ( Old_UI or New_UI ) |

**Evaluation metric**

    score = 100*(metrics.roc_auc_score(actual, predicted, average= "weighted" ))

**Result submission guidelines**

*   The index is "CustomerID" and the target is the "Preferred\_Theme" column. 
*   The submission file must be submitted in .csv format only.
*   The size of this submission file must be  1850 x 2.

Note: Ensure that your submission file contains the following:

*   Correct index values as per the test file
*   Correct names of columns as provided in the sample\_submission.csv file

**Instructions:** 

*   Click _Download dataset_ to download the dataset.
*   Solve the problem in your local environment.
*   Save the submission in a _.csv_ file.
*   Click _Upload File_ (under the _Upload File_ section) to upload your prediction file (_.csv_).
*   Click _Upload File_ (under the _Upload Source Code_ section) to upload your _.ipynb_ file along with any presentation file.
*   Add any instructions or comments in the _Your Answer_ section.
*   Click _Submit_.

[Download dataset](https://he-s3.s3.amazonaws.com/media/hackathon/condenast-data-scientist-hiring-challenge/preferred-ui-theme-9-7ec60e56/9d01f8acb01d11ec.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Expires=43200&X-Amz-Credential=AKIA6I2ISGOYH7WWS3G5%2F20220416%2Fap-southeast-1%2Fs3%2Faws4_request&X-Amz-SignedHeaders=host&X-Amz-Date=20220416T090343Z&X-Amz-Signature=09539c4707dfc84d89c112750d2f0dee65da04e38caa5ac6a8ac993de99725b8)
