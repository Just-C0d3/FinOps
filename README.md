# FinOps
In this project I will share a solution Ive desgined to monitor the expenditure of my azure subscription implementing a diverese set of tools : 
  - Azure Logic Apps
  - PowerBI
  - Azure Storage accounts
  - Azure Budgets

The objective of this project is to set a workflow that generates a monthly iteration of a logic app process that does as it follows: 
  
  1º Obtain all the data of the budgets
  2º Send said data to a table in azure
  3º Represent the data in a powerBi report.
