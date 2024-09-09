# Predicting Hotel Reservation Cancelations
## Background and motivation
Due to the evolution of technology, more and more hotels use websites to allow customers to make hotel reservations. This also means that it is much easier to cancel a reservation. We are trying to predict whether a customer will cancel their reservation or not depending on certain factors, such as previous cancellations, number of children, type of meal plan and more. This could be interesting and helpful to hotels to save money by knowing more exactly how many rooms are available for other costumers. It's interesting to see how much machine learning can help both small and big business to save money and optimize their business.

The goal of our project is to try to predict whether or not a customer will cancel their reservation.

## Dataset
Dataset: https://www.kaggle.com/datasets/ahsan81/hotel-reservations-classification-dataset

The Hotel Reservations Dataset contains data that helps to classify if a customer is going to cancel their room reservation. To helps with this there are numerous features in the dataset which are related to the customers reservation and are as follows:

Number of adults
Number of children
Number of weekend nights
Number of week nights
Required parking space
Lead time (The time between booking date and arrival date)
Arrival year
Arrival month
Arrival date
Repeated guest
Number of previous cancellations
Number of previous bookings not canceled
Average price per room
Number of special requests
Type of meal plan
Room type reserved
Market segment type
The last three are categorical while the rest are numerical. The time period for when each reservation was made are between 2017 and 2018.

In total there are 36275 cases, 67% were not cancelled while 33% of the reservations were cancelled. Since this dataset is not that balanced accuracy will not be a good metric for evaluation since it is impacted by the imbalance in the dataset

Methodology
The problem to solve is to identify whether a reservations is going to be cancelled or not and thus it becomes a classification problem.

## Our work consisted of three primary stages:

Analysis of the data
Execution
Evaluation

In this project the main evaluation metrics of interest will be Recall and precision. This is because we don't want the hotel to cancel a reservation because of the prediction and then realize that the guest would arrive anyway.

Precision is a metric that answers the question "What proportions of positive identifications was actually correct?". In other words the precision is calculated by True Positives/(True Positives + False Positives)

Recall is a metric that answers the question "What proportion of actual positives was identified correctly?" In other words the recall is calculated by True positives/(True Positives + False Negatives)

