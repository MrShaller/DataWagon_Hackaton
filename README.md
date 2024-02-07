# DataWagon_Hackaton

This is [DataWagon hackaton][1] which we (I, [Mikhail Vitko][2] and Efimova Anastasia) have participated and secured a spot in the top 10 out of 40 teams by the end of the competition.

**Task:**
Create a model for predicting the date of a wagon's scheduled maintenance.
---
The task at hand involves predicting when the wagon will go for maintenance in two stages:

1. Predicting that the wagon will go for planned maintenance within a month.
2. Predicting that the wagon will go for planned maintenance within 10 days.
   
🤔 Problem Description
---
Sending a wagon for planned maintenance can occur for various reasons, both based on regulations (time/mileage) and due to the accumulation of minor defects:

- There have been numerous ongoing repairs.
- There were no loading options, etc.

These reasons are diverse, and they all impact the feasibility of conducting maintenance.

Wagons are sent for maintenance upon receiving notifications of their malfunctions. Unfortunately, the current process does not allow for the distribution of the workload to repair depots, managing the last loading request before maintenance, and much more. Your task is to address this.

---

The business value of the solution is determined by the number of hidden correlations uncovered in the data. The criteria are as follows - the identified correlation describes a group of no less than 100 wagons sent for planned maintenance and uses non-trivial (i.e., not just residual mileage or the fact of repair in the past period) parameters. Thus, the more data sources are utilized and the more rules are identified for sending wagons for planned maintenance, the higher the business value of your solution.

💡 Data
---
All source data and their descriptions are presented in Russian at the following link:
https://drive.google.com/drive/folders/1Qh5ZMSDOJ0d0XuInbW4DyiuhaZ1mfmOv

Solve
---
The idea proposed by us is illustrated in the following diagram. Our team split into two parts. One part refined the algorithm, while the other processed the data and built the ML model.

The entire implemented code is available in an IPython notebook in Russian.

<p align="center">
  <img src="/diagrama2.png" alt="Algorithm/Decision-making process">
</p>




[1]: https://datawagon.ru/
[2]: https://github.com/mishantique
