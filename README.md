# Diet-Recommendation-System
Nutrition is about eating a healthy and balanced diet. Food and drink provide the energy and
nutrients you need to be healthy. Understanding these nutrition terms may make it easier for
you to make better food choices.
Each person is different, whether it be physical factors like weight or height or their lifestyle
for example whether their job is a dynamic one or a sedentary one, if they go to the gym or
indulge in sports and also if they have some comorbidity. Therefore, the nutrition requirements
of every person would be different.
A dietary plan is unique to each person. Our nutrition recommendation system works on
considering the various factors affecting a person's nutrition requirements and formulates a
dietary plan which is Indian cuisine friendly.

# Objectives
1. Aim to develop a recommendation system, advising the user about their daily nutritional
requirements based on their daily logs
2. The recommendation system would sort out nutritional values of various Indian food items,
and recommend the user on their missing nutritional values and also recommend food item/s
that would fulfil their respective daily nutrition(required)
3. Our other objective would also be to recommend the user about the deficiency diseases that
they could develop if they do not fulfil their daily nutritional requirement(which the system
would recognize by the user's daily logs)

# Dataset-Description
The dataset, which consists of
90 distinct items with all 16 of the aforementioned
attributes, is going to develop a machine learning system
that will assess if a certain type of food or range of packaged
foods is suitable for a specific client in a bid to keep his or
her nutritious diet. Whether or not a certain food item
successfully fits the column requirements is indicated by the
number 0 or. The data set is a collection of foods that are
essential to a person's existence, and each has the following
characteristics: dietary items, including breakfast, lunch,
and supper; vegetarian or non-vegetarian options;
carbohydrates; lipids; proteins; minerals; calcium; salt;
sodium; carbohydrates; fiber; and sugars.


# Methodology
Machine learning techniques were employed in the
creation of this project. The meal was first grouped by
calories using KMeans clustering, then depending on the
input supplied, the food was then classified and predicted
using a random forest classifier.

Separating food products into categories for breakfast,
lunch, and supper is the first step in teaching the system
what meals they belong in. According to which nutrients are
required for a healthy weight reduction, weight increase,
and weight maintenance, various nutrients are categorised.
After clustering, the Random Forest classifier predicts
which nearby foods are most suited for the suggested diet.

The user interface asks the user to enter details like gender,
stature, bodyweight, as well as the justification for needing
a diet. Some food products are classed and recommended to
the user based on it and the suitable clustering.


