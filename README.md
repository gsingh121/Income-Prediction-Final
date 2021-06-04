# Income-Prediction-Final

Problem Statement:

To build a classification methodology to determine whether a person makes over 50K per year.

Data Description

The client will send data in multiple sets of files in batches at a given location. The data has been extracted from the census bureau. 
The data contains 32561 instances with the following attributes:
Features:

    1. age: continuous. It denotes the age of the person.
    2. workclass: It denotes the working class of the person. Sample values: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.
    3. fnlwgt: continuous.
    4. education: It denotes the educational qualification of the person. Sample values: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.
    5. education-num: continuous. It denotes the quantitative values with reference to education. 
    6. marital-status: It denotes the marital status of the person. Sample values:  Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.
    7. occupation: It denotes the occupation of a person. Sample values: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.
    8. relationship: It denotes the people present in the family. Sample values: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
    9. race: It denotes the person’s origins. Sample values: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.
    10. sex: It denotes the person's gender. Sample values: Female, Male. 
    11. capital-gain: continuous. It denotes the monitory gains by the person.
    12. capital-loss: continuous. It denotes the monitory loss by the person.
    13. hours-per-week: continuous. It denotes the number of working hours per week by the person.
    14. native-country: It denotes the country to which the person belongs. Sample values: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.

Target Label:
Whether a person earns more or less than 50000 dollars per year.
    15. Income:  >50K, <=50K.
    
    Apart from training files, we also require a "schema" file from the client, which contains all the relevant information about the training files such as:
Name of the files, Length of Date value in FileName, Length of Time value in FileName, Number of Columns, Name of the Columns, and their datatype.
