Hotel Booking Cancellation Prediction

OVERVIEW:

This project aims to predict hotel booking cancellations using machine learning techniques. By analyzing historical and current booking data, the model can assist hotel management in optimizing operations, improving customer retention, and minimizing revenue losses.

PROJECT STRUCTURE:

Files:

INNHotelsGroup_newdata.csvA CSV file containing new booking data for prediction and analysis. This dataset is expected to have similar features as the training data.

INNHotelsGroup_pastdata.csvA CSV file containing historical booking data used for model training and evaluation.

Key Components:

Data Preprocessing: Data cleaning, handling missing values, and feature engineering.

Model Training: Training the machine learning model using historical booking data.

Evaluation: Assessing the model's performance using metrics such as accuracy, precision, recall, and F1-score.

Prediction: Making predictions on new booking data to identify potential cancellations.

DATA DESCRIPTION:

Input Features

The datasets (INNHotelsGroup_newdata.csv and INNHotelsGroup_pastdata.csv) include the following columns:

Booking ID: Unique identifier for each booking.

Customer Type: Type of customer (e.g., transient, group, etc.).

Lead Time: Number of days between booking and arrival.

Booking Changes: Number of modifications made to the booking.

Special Requests: Number of special requests made by the customer.

Deposit Type: Deposit made by the customer (e.g., no deposit, refundable, non-refundable).

Market Segment: Segment from which the booking originated (e.g., direct, corporate, online travel agent).

Other Features: Additional booking-specific details.

Target Variable

Is Canceled: A binary column indicating whether the booking was canceled (1) or not (0).

INFERENCES:

Inventory Loss
In the three months prior to the Data Science solution, the inventory loss was at ~30%
In the three months post Data Science solution implementation, the inventory loss was down to ~10%
The Data Science solution has been able to cut the inventory loss to one-third of its previous value

Revenue Contribution
In the three months prior to the Data Science solution, the revenue contribution from rebookings stood at ~11.5%
Post implementation of the Data Science solution, the revenue contribution from rebookings stands at ~26%
The Data Science solution has helped in more than doubling the revenue contribution from rebookings from its previous value

Revenue
In the three months prior to the Data Science solution, the revenue from rebookings stood at $24.5k
Post implementation of the Data Science solution, the revenue from rebookings stands at $34k
The Data Science solution has resulted in an increase in revenue from rebookings by ~40%
Click to add a cell.

