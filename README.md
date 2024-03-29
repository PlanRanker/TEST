# Data Source

https://tianchi.aliyun.com/dataset/140721

The entire dataset disclosure application is in progress and will be released later.

# Data Format

### user_behavior_transfer_plans.csv
The data set covers all behaviors (including clicks, favorites, adding, and purchases) of approximately 48.8M million random users from August 16, 2022 to September 17, 2022. The organization of the data set as fllows, namely Each row of the collection represents a user data behavior, which is composed of user ID, Transfer plan ID, behavior type, and Timestamp log. Each column summarizes the detailed information of the product under investigation.
| Field | Explanation |
| --- | --- |
| User ID | An integer, the serialized ID that represents a user |
| OD Query ID | An integer, the serialized ID represents a query which contains departure and destination |
| Transfer Plan ID | An integer, the serialized ID that represents an transfer plan |
| Behavior type | A string, enum-type from ('browsing', 'purchasing', 'reference') |
| Timestamp | An integer, the timestamp of the behavior |


### user_profile.csv
This data set mainly contains the basic attributes of about five million random users, such as age, gender, occupation, resident city ID, crowd tag, etc. Each row of the data set represents a piece of user information, separated by commas. The detailed description of each column in the data set is as follows:
| Field | Explanation |
| --- | --- |
| User ID | An integer, the serialized ID that represents a user |
| Age | An integer, the serialized ID that represents an user age |
| Gender | An integer, the serialized ID that represents the user gender |
| Occupation | An integer, the serialized ID that represents the user occupation |
| Habitual City | An integer, the serialized ID that represents the user habitual city，single value |

### transfer_plan_profile.csv
This data file mainly contains the basic attribute characteristics of about 69M products, such as product Depart City ID, Arrive City ID, Cost Time, Cost Price, etc. Each row of the data set represents the information of a transfer plan, separated by commas. The detailed description of each column in the data set is as follows:
| Field | Explanation |
| --- | --- |
| Query ID | An integer, the serialized ID represents a query which contains departure and destination |
| Query Depart City ID | An integer, the serialized ID of departure city for the query |
| Query Arrive City ID | An integer, the serialized ID of destination city for the query |
| Transfer Plan ID | An integer, the serialized ID that represents an transfer plan |
| First Train ID | An integer, the serialized ID of the first leg of the train number |
| First Depart City ID | An integer, the serialized ID of departure city for the first leg of the transfer plan |
| First Arrive City ID | An integer, the serialized ID of destination city for the first leg of the transfer plan |
| First Depart Time | A String, the departure time of the first leg of the transfer plan |
| First Arrive Time | A String, the arrive time of the first leg of the transfer plan |
| First Cost Price | A integer, the cost price ofthe first leg of the transfer plan |
| Second Train ID | An integer, the serialized ID of the second leg of the train number |
| Second Depart City ID | A integer, the serialized ID of departure city for the second leg of the transfer plan|
| Second Arrive City ID | A integer, the serialized ID of destination city for the second leg of the transfer plan |
| Second Depart Time | A String, the departure time of the second leg of the transfer plan |
| Second Arrive Time | A String, the arrive time of the second leg of the transfer plan |
| Second Cost Price | A integer, the cost price of the second leg of the transfer plan |
| Total Cost Time | A integer, the cost time of the transfer plan |
| Total Cost Price| A integer, the cost price of the transfer plan |

