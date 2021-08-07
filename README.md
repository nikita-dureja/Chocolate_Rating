## Chocolate Bar Rating

The dataset chocolate.csv contains the relevant information of a number of chocolate bars, along with expert ratings as the ground truth.

#### Columns description
- Company (Maker-if known): name of the company (string).
- Specific Bean Origin: the geographical origin for the chocolate bar (string).
- REF: a value indicating when the review was entered in the database. A higher value indicates more recently entered (integer).
- Review Year: the year of the review published (integer).
- Cocoa Percentage: cocoa percentage of the chocolate bar (string).
- Company Location: the country of the manufacturer (string).
- Rating: expert rating for the chocolate bar (float). This is the label to be predicted by the model. It is a number from 1 (lowest quality) to 5 (highest   quality).
- Bean Type: the type of cocoa bean used (string).
- Broad Bean Origin: the broader geographical origin of the cocoa bean (string)

### Goal of the project

To develop a machine learning model which takes the properties of a specific chocolate bar (e.g. the percentage of cocoa, the origin of beans), and output the rating

- Required data cleaning and pre-processing has been performed on the dataset
- Based on the model hyperparameter tuning, best model is selected that has the highest validation performance
- Selected model is applied on the test data to assess the model performance
