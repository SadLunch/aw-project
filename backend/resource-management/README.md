# Introduction

In this part of the project our group had to identify for each of the Back End Services, their Requests and Resources.
Requests being the type of the HTTP Request used for the Resource.
Resources being the endpoints used in the Back End Service.

In the following sections we explain what we did and we show our proposed delivery for the identified Back End Services.

#### NOTE: We have the solution in tables in this `README.md` file but we also have `.png` files with other views of the tables
####       The `.png` files' naming convention is the following: `[name_of_be_service]_ResourceManagement.png`.

## What was done

As mentioned before, our group identified some Requests and Resources for each of the Back End Services.

The Requests and Resources identified were the following:

 - **Authentication Management**
    --> Requests: `GET`, `PUT`, `DELETE`
    --> Resources: `/auth/token`, `/auth/login`, `/auth/logout`

 - **Account Management**
    --> Requests: `GET`, `PUT`, `DELETE`
    --> Resources: `/users`, `/users/{user_id}`

 - **Product Management**
    --> Requests: `GET`, `PUT`, `DELETE`
    --> Resources: `/products`, `/products/{product_id}`, `/products/saved`, `/products/saved/{product_id}`

 - **Feedback Management**
    --> Requests: `GET`, `PUT`, `DELETE`
    --> Resources: `/reviews/{product_id}`, `/reviews/{product_id}/{review_id}`

 - **News Management**
    --> Requests: `GET`, `PUT`, `DELETE`
    --> Resources: `/news`, `/news/{news_id}`

 - **Stats Management**
    --> Requests: `GET`, `PUT`, `DELETE`
    --> Resources: `/stats/negative`, `/stats/postive`

 - **Store Management**
    --> Requests: `GET`, `PUT`, `DELETE`
    --> Resources: `/stores`, `/stores/{store_id}`, `/stores/{store_id}/categories`, `/stores/{store_id}/categories/{category_id}`

 - **QR Code Management**
    --> Requests: `GET`
    --> Resources: `/qrCode`

Here we have a table view of the above Requests and Resources for each Service:

| BE Services               | Requests  | Resources     |
| :-----------------------: | :-------: | :------------ |
| Authentication Management | GET       | /auth/token   |
|                           | PUT       | /auth/login   |
|                           | DELETE    | /auth/logout  |

| BE Services        | Requests  | Resources        |
| :----------------: | :-------: | :--------------- |
| Account Management | GET       | /users/{user_id} |
|                    | PUT       | /users           |
|                    | PUT       | /users/{user_id} |
|                    | DELETE    | /users/{user_id} |

| BE Services        | Requests  | Resources                    |
| :----------------: | :-------: | :--------------------------- |
| Product Management | GET       | /products                    |
|                    | GET       | /products/{product_id}       |
|                    | GET       | /products/saved              |
|                    | PUT       | /products                    |
|                    | PUT       | /products/{product_id}       |
|                    | PUT       | /products/saved              |
|                    | DELETE    | /products/{product_id}       |
|                    | DELETE    | /products/saved/{product_id} |

| BE Services         | Requests  | Resources                           |
| :-----------------: | :-------: | :---------------------------------- |
| Feedback Management | GET       | /reviews/{product_id}               |
|                     | GET       | /reviews/{product_id}/{review_id}   |
|                     | PUT       | /reviews/{product_id}               |
|                     | PUT       | /reviews/{product_id}/{review_id}   |
|                     | DELETE    | /reviews/{product_id}               |
|                     | DELETE    | /reviews/{product_id}/{review_id}   |

| BE Services     | Requests  | Resources       |
| :------------:  | :-------: | :-------------- |
| News Management | GET       | /news           |
|                 | GET       | /news/{news_id} |
|                 | PUT       | /news           |
|                 | PUT       | /news/{news_id} |
|                 | DELETE    | /news           |
|                 | DELETE    | /news/{news_id} |

| BE Services      | Requests  | Resources       |
| :-------------:  | :-------: | :-------------- |
| Stats Management | GET       | /stats/negative |
|                  | GET       | /stats/positive |
|                  | PUT       | /stats/negative |
|                  | PUT       | /stats/positive |
|                  | DELETE    | /stats/negative |
|                  | DELETE    | /stats/positive |

| BE Services      | Requests  | Resources                                    |
| :--------------: | :-------: | :------------------------------------------- |
| Store Management | GET       | /stores                                      |
|                  | GET       | /stores/{store_id}                           |
|                  | GET       | /stores/{store_id}/categories                |
|                  | PUT       | /stores                                      |
|                  | PUT       | /stores/{store_id}                           |
|                  | PUT       | /stores/{store_id}/categories                |
|                  | DELETE    | /stores/{store_id}                           |
|                  | DELETE    | /stores/{store_id}/categories                |
|                  | DELETE    | /stores/{store_id}/categories/{category_id}  |

| BE Services        | Requests  | Resources    |
| :---------------:  | :-------: | :----------- |
| QR Code Management | GET       | /qrCode      |

As mentioned before there are also images in this folder that display these tables, if it is easier to see there.