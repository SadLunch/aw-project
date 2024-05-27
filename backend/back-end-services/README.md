# Introduction

In this part of the project our group had to identify Back End Services for the QRMeat app.
In the following sections we explain what we did and we show our proposed delivery for the identified Back End Services

##### NOTE: We have the solution in a table in this `README.md` file but we also have a `.png` file with another view of the table

## What was done

As mentioned before our group identified some Back End Services for the application QRMeat.
The identified Back End Services were:
    - **Authentication Management**
    - **Account Management**
    - **Product Management**
    - **Feedback Management**
    - **News Management**
    - **Stats Management**
    - **Store Management**
    - **QRCode Management**

These Back End Services were identified, so that we could have separation of concerns in the back end.

Although in the case of the `Auhtentication Management` and the `Account Management`, it could be reasoned that since both work on with the user, that they could be joined, but we found that separating both made more sense, since the `Account Management` service works with the **user** and the `Authnetication Management` works with the **authentication of the user**.

## Proposed Solution

Here we have our proposed solution for this delivery:

| BE Services               | Service Description                                                      | Resource Description            |
| :-----------------------: | :----------------------------------------------------------------------- | :------------------------------ |
| Authentication Management | Service that handles every aspect of the user’s authentication           | User Credentials                |
| Account Management        | Service that handles every aspect of the user’s account                  | User detail, User preferences   |
| Product Management        | Service that handles every aspect of the management of the products      | Product details, Saved products |
| Feedback Management       | Service that handles every aspect of the feedback of products            | Product feedback                |
| News Management           | Service that handles every aspect of the management of the news articles | News details                    |
| Stats Management          | Service that handles every aspect of the stats                           | Negative Stats, Positive Stats  |
| Store Management          | Service that handles every aspect of the management of the stores        | Store details, Category details |
| QR Code Management        | Service that handles every aspect of the QR Code                         | QR Code                         |

As mentioned before there is also an image in this folder that displays this table, if it is easier to see there.

