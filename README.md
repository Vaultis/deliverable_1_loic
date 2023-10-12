# Deliverable 1: Shaped Work
```yaml
Name: Jean Loic Kandikandi
Student Id: 300113205
Course: SEG 4105
```
## Context
Our product is called *Vaultis*. It is a web application designed to help users effortlessly track their accounts cash flow including income, expenses, investments. Current features primarily focus on individual use. Finances are after all, a private matter. However, we are actively exploring integration of group features to rapdily expand user base.

## Problem
While finances are typically considered a personal affair, they can be a shared responsibility. For example, such is the case when a group of friends have to split the cost of a car rental, but can only record a single transaction. It can be a source of frustration and confusion, leading to strained relationships and financial disputes among friends, family, and colleagues. Finding an equitable way to divide and track shared costs accurately and efficiently remains a common challenge, often resulting in misunderstandings and delayed reimbursements.

## Appetite
We aim to deliver a functional expense splitting solution within a six-week development timeframe. We will target an initial user base of 200 individuals and gradually increase. A simple user experience and best security practices should remain a top priority when developing the solution.

## Solution
Our solution is implementing a split feature that enables a *Vaultis* user to distribute the cost of a transaction among other *Vaultis* users and record them as owing their respective shares to the user who initially covered the expense. Vaultis would provide real-time balance updates, notifications, and a secure payment option for settling debts.

The breadboarding artefact below illustrates the execution flow of a typical split cost feature.

![Breadboarding_Vaultis](/assets/Breadboarding_Vaultis.png)

## Rabbit Holes
There are several potential rabbit holes worth exploring to ensure the project success:

- **Enhanced Participant Display:** The participants section within transaction details should condense shows participant names, amounts, and status together to avoid excessive form length. This could enhance the user experience and streamline the transaction entry process.
- **Visual Cue for Unpaid Transactions:** If a transaction has not been settled, include "[Not Paid]" in its title to maintain maximum awareness of its unsettled status.
- **Email Validation for Participants:** When adding participants, users are required to input the email address associated with their Vaultis account. If the provided email is not linked to a Vaultis account, an error message will be displayed to inform the user of this issue.


## No Gos
While we aim for efficiency in our six-week timeline, there are important constraints we must acknowledge:

- **Equal Splitting Only:** At this stage, we are limited to splitting expenses equally among participants. We do not offer more complex splitting options, such as percentage-based or custom amount splits.
- **International Currencies:** We will not address transactions involving multiple currencies; our focus is on a single currency for simplicity.
- **Limited Group Size:** While we cater to small groups, our system will not support groups exceeding a predefined limit of 5 users associated to one transaction to keep the scope manageable.

These constraints are necessary to maintain project feasibility within our six-week timeframe and align with our initial user-focused approach.