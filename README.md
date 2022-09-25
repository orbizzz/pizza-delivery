POST /auth/jwt/refresh/ | Refresh the access token | All users

POST /auth/jwt/verify/ | Verify the validity of a token | All users

POST /orders/ | Place an order | All users

POST /orders/ | Get all orders | All users

GET /orders/{order_id}/ | Retrieve an order | Superuser

PUT /orders/{order_id}/ | Update an order | All users

PUT /update-status/{order_id}/ | Update order status | Superuser

DELETE /orders/{order_id}/ | Delete/Remove an order | All users

GET /user/{user_id}/orders/ | Get user's orders | All users

GET /user/{user_id}/orders/{order_id}/ | Get user's specific order

GET /docs/ | View API documentation | All users


