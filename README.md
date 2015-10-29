Vizualization Workshop
=======================


Data
----
* [Federal Data Sets](http://www.data.gov/)
* [NYC Data](https://data.cityofnewyork.us/)
* [NY State Data](https://data.ny.gov/)
* Other:
	* http://rs.io/2014/05/29/list-of-data-sets.html
	* https://www.google.com/cse/publicurl?cx=002720237717066476899:v2wv26idk7m
	* http://www.datasciencecentral.com/profiles/blog/show?id=6448529%3ABlogPost%3A268197
	* http://vincentarelbundock.github.io/Rdatasets/datasets.html
	* http://blog.thedataincubator.com/2014/10/data-sources-for-cool-data-science-projects-part-1/
	* http://arcane-coast-3553.herokuapp.com/sna/visual

Hands on Viz
------------
* [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
* Data file: https://github.com/GCDigitalFellows/officechartsviz/blob/master/train.csv

|VARIABLE| DESCRIPTION|
|--------|---------------|
|survival | Survival (0 = No; 1 = Yes)|
|pclass  | Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)|
|name    | Name |
|sex     | Sex |
|age     | Age |
|sibsp   | Number of Siblings/Spouses Aboard|
|parch   | Number of Parents/Children Aboard|
|ticket  | Ticket Number|
|fare    | Passenger Fare|
|cabin   | Cabin |
|embarked | Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)|

### SPECIAL NOTES:
* Pclass is a proxy for socio-economic status (SES): 1st ~ Upper; 2nd ~ Middle; 3rd ~ Lower
* Age is in Years; Fractional if Age less than One (1): If the Age is Estimated, it is in the form xx.5

With respect to the family relation variables (i.e. sibsp and parch) some relations were ignored.  The following are the definitions used for sibsp and parch.
* Sibling:  Brother, Sister, Stepbrother, or Stepsister of Passenger Aboard Titanic
* Spouse:   Husband or Wife of Passenger Aboard Titanic (Mistresses and Fiances Ignored)
* Parent:   Mother or Father of Passenger Aboard Titanic
* Child:    Son, Daughter, Stepson, or Stepdaughter of Passenger Aboard Titanic
Other family relatives excluded from this study include cousins, nephews/nieces, aunts/uncles, and in-laws.  Some children travelled only with a nanny, therefore parch=0 for them.  As well, some travelled with very close friends or neighbors in a village, however, the definitions do not support such relations.

Task
-----
* Working with a partner, visualize some relationship in the data. It can be as simple or complicated as you wish. 
