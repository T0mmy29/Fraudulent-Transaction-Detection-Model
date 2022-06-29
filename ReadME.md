#DESCRIPTION


I have developed a machine learning model to detect fraudulent transactions based on the details of a bank customer.


This code is written in JUPYTER NOTEBOOK.


You must have jupyter notebook if you want to access the code and run it.



The following is the data dictionary for the dataset in the provided link.



step - maps a unit of time in the real world. In this case 1 step is 1 hour of time. Total steps 744 (30 days simulation).

type - CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER.

amount - amount of the transaction in local currency.

nameOrig - customer who started the transaction

oldbalanceOrg - initial balance before the transaction

newbalanceOrig - new balance after the transaction

nameDest - customer who is the recipient of the transaction

oldbalanceDest - initial balance recipient before the transaction. Note that there is not information for customers that start with M (Merchants).

newbalanceDest - new balance recipient after the transaction. Note that there is not information for customers that start with M (Merchants).

isFraud - This is the transactions made by the fraudulent agents inside the simulation. In this specific dataset the fraudulent behavior of the agents aims to profit by taking control or customers accounts and try to empty the funds by transferring to another account and then cashing out of the system.

isFlaggedFraud - The business model aims to control massive transfers from one account to another and flags illegal attempts. An illegal attempt in this dataset is an attempt to transfer more than 200.000 in a single transaction.


Forward to the link for the Data Set on which I've trained the Model.

https://drive.google.com/file/d/192kGDXBHYHmq01I6KH1uf-KLqaV2I6Vr/view?usp=sharing
