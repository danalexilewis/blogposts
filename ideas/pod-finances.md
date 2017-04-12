# Pod Finances

### Design Principles
A pod operates with minimal and distributed administration/management.

Given this the financial system of a pod should whereever possible replace tasks with a process and always be transparent.

The financial model of a pod covers all incomings and outgoings. It defines where and how these occur and what safe guards and constraits exist. 

Incomes can be defined as the financial systems of recieving funds. This may include recieving:

 - Licence fees
 - Consulting services
 - Saas fees
 - Maintanance contracts
 - Retainers
 - Grants

Each of these may have different needs for supporting the management of them.

Outgoings can defined as how the pod spends/distributes funds. This may include paying:

 - Contractors
 - Expenses
  - Recuring
  - One off
 - **Core members (salaries/drawing/other)**
 - A revenue share with another pod
 - Commons contribution

### Paying Core Members
How core members of the pod are paid is the single most inportant outgoing, it will most likely be the largest and in the case of livelihood pods is high risk of causing friction within the group.  

Root Systems is a livelihood pod, therefor the financial model needs to provide a mechanism to provide financial security to its members.

## Model Requirements

 - Low Admin
 - Transparent
 - Provides financial security

Given these high level requirements Root Systems opted to use an algorythm to determine everyones pay. It can be reduced down to:

**Retainer + Pod Viability Bonus + Performance Bonus**

We also needed a lever to allow us to decrease the payout when we were not doing as well. Therefor both bonuses were bound to our buffer - viability measure:

A buffer level is the sum of all of the members retainers x their fte's (self set)

Buffer levels are multiplied against the bonuses, the amended algorythm looks like:

**Retainer + Buffer Level x Viability bonus + Buffer Level x Performance Bonus**


