# Introduction

In this part of the project our group had to identify the schemas used by each Back End Service.
In the following sections we explain what we did and we show our proposed delivery for the identified Schemas.

##### NOTE: We have the solution in a table in this `README.md` file but we also have a `.png` file with another view of the table

## What was done

As mentioned before our group identified the schemas used by each of the Back End Services.

The names mentioned in the Request and Response Schemas are the names of the components or query parameters used in the [API Specification](../back-end-api-specification).

## Proposed Solution

Here we have our proposed solution for this delivery:

| BE Services               | Requests                  | Resources                                             |
| :-----------------------: | :------------------------ | :---------------------------------------------------- |
| Authentication Management | username, password, token | token                                                 |
| Account Management        | User                      | User, user_id                                         |
| Product Management        | Product, token            | ProductList, Product, product_id                      |
| Feedback Management       | rating, Review, token     | ReviewList                                            |
| News Management           | News                      | NewsList, News, news_id                               |
| Stats Management          | Stats                     | Stats                                                 |
| Store Management          | Store, Category           | StoreList, Store, store_id, CategoryList, category_id |
| QR Code Management        | QRCode                    | Product                                               |

As mentioned before there is also an image in this folder that displays this table, if it is easier to see there.