# Data-Analysis-2

Applied Data Modeling Concepts on 8 .asc files containing financial data of 8 regions of Czech Republic.

Framed the report after analyzing data using concepts like Graph Data Modeling, Relational Modeling, and Spatio-Temporal Modeling.

Language used : Python

Modules used : Numpy, Pandas, datetime

Data Visualization Tool: Tableau

Data description:

The data about the clients and their accounts consist of following relations:
• relation account (4500 objects in the file ACCOUNT.ASC) - each record describes static characteristics of an account.

• relation client (5369 objects in the file CLIENT.ASC) - each record describes characteristics of a client.

• relation disposition (5369 objects in the file DISP.ASC) - each record relates together a client with an account.

• relation permanent order (6471 objects in the file ORDER.ASC) - each record describes characteristics of a payment order.

• relation transaction (1056320 objects in the file TRANS.ASC) - each record describes one transaction on an account.

• relation loan (682 objects in the file LOAN.ASC) - each record describes a loan granted for a given account.

• relation credit card (892 objects in the file CARD.ASC) - each record describes a credit card issued to an account.

• relation demographic data (77 objects in the file DISTRICT.ASC) - each record describes demographic characteristics of a district.
