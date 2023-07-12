### Live Link: [https://digital-cow-hut-backend-2.vercel.app/](https://digital-cow-hut-backend-2.vercel.app/)

### Application Routes:

## Main part

### Auth (User)

- Route: [https://digital-cow-hut-backend-2.vercel.app/api/v1/auth/login](https://digital-cow-hut-backend-2.vercel.app/api/v1/auth/login) (POST)

- Route: [https://digital-cow-hut-backend-2.vercel.app/api/v1/auth/signup](https://digital-cow-hut-backend-2.vercel.app/api/v1/auth/signup) (POST)

- Route: [https://digital-cow-hut-backend-2.vercel.app/api/v1/auth/refresh-token](https://digital-cow-hut-backend-2.vercel.app/api/v1/auth/refresh-token) (POST)

### Auth (Admin)

- Route: [https://digital-cow-hut-backend-2.vercel.app/api/v1/admins/create-admin](https://digital-cow-hut-backend-2.vercel.app/api/v1/admins/create-admin) (POST)

- Route: [https://digital-cow-hut-backend-2.vercel.app/api/v1/admins/login](https://digital-cow-hut-backend-2.vercel.app/api/v1/admins/login) (POST)

### User

- Route: [https://digital-cow-hut-backend-2.vercel.app/api/v1/users](https://digital-cow-hut-backend-2.vercel.app/api/v1/users) (GET) (Can only be accessed by admin)

- Route: [https://digital-cow-hut-backend-2.vercel.app/api/v1/users/64a12342ffc1f18e5d7e0e4f](https://digital-cow-hut-backend-2.vercel.app/api/v1/users/6177a5b87d32123f08d2f5d4) (Single GET) Include an id that is saved in your database (Can only be accessed by admin)

- Route: [https://digital-cow-hut-backend-2.vercel.app/api/v1/users/64a12342ffc1f18e5d7e0e4f](https://digital-cow-hut-backend-2.vercel.app/api/v1/users/6177a5b87d32123f08d2f5d4) (PATCH) Include an id that is saved in your database (Can only be accessed by admin)

- Route: [https://digital-cow-hut-backend-2.vercel.app/api/v1/users/64a12342ffc1f18e5d7e0e4f](https://digital-cow-hut-backend-2.vercel.app/api/v1/users/6177a5b87d32123f08d2f5d4) (DELETE) Include an id that is saved in your database (Can only be accessed by admin)

#### Cows

- Route: [https://digital-cow-hut-backend-2.vercel.app/api/v1/cows](https://digital-cow-hut-backend-2.vercel.app/api/v1/cows) (POST) (Can only be accessed by seller)

- Route: [https://digital-cow-hut-backend-2.vercel.app/api/v1/cows](https://digital-cow-hut-backend-2.vercel.app/api/v1/cows) (GET) (Can only be accessed by buyer,seller & admin)

- Route: [https://digital-cow-hut-backend-2.vercel.app/api/v1/cows/64a126d441ac7283a445a8bf](https://digital-cow-hut-backend-2.vercel.app/api/v1/cows/6177a5b87d32123f08d2f5d4) (Single GET) Include an id that is saved in your database (Can only be accessed by buyer,seller & admin)

- Route: [https://digital-cow-hut-backend-2.vercel.app/api/v1/cows/64a126d441ac7283a445a8bf](https://digital-cow-hut-backend-2.vercel.app/api/v1/cows/6177a5b87d32123f08d2f5d4) (PATCH) Include an id that is saved in your database (Can only be accessed by the seller of the cow)

- Route: [https://digital-cow-hut-backend-2.vercel.app/api/v1/cows/64a126d441ac7283a445a8bf](https://digital-cow-hut-backend-2.vercel.app/api/v1/cows/6177a5b87d32123f08d2f5d4) (DELETE) Include an id that is saved in your database (Can only be accessed by the seller of the cow)

#### Orders

- Route: [https://digital-cow-hut-backend-2.vercel.app/api/v1/orders](https://digital-cow-hut-backend-2.vercel.app/api/v1/orders) (POST) (Can only be accessed by the buyer)

- Route: [https://digital-cow-hut-backend-2.vercel.app/api/v1/orders](https://digital-cow-hut-backend-2.vercel.app/api/v1/orders) (GET) (Can be accessed only by the admin, by the **`specific buyer`** of this order & by the **`specific seller`** of this order)

## Bonus Part

#### Admin Profile

- Route: [https://digital-cow-hut-backend-2.vercel.app/api/v1/admins/my-profile](https://digital-cow-hut-backend-2.vercel.app/api/v1/users/my-profile) (GET) (Can be accessed only by the admin of the profile (Optional Task))

- Route: [https://digital-cow-hut-backend-2.vercel.app/api/v1/admins/my-profile](https://digital-cow-hut-backend-2.vercel.app/api/v1/users/my-profile) (PATCH) (Can be accessed only by the admin of the profile (Optional Task))

#### My Profile

- Route: [https://digital-cow-hut-backend-2.vercel.app/api/v1/users/my-profile](https://digital-cow-hut-backend-2.vercel.app/api/v1/users/my-profile) (GET) (- Can be accessed only by the **`specific user (buyer, seller)`** of the profile)

- Route: [https://digital-cow-hut-backend-2.vercel.app/api/v1/users/my-profile](https://digital-cow-hut-backend-2.vercel.app/api/v1/users/my-profile) (PATCH) (- Can be accessed only by the **`specific user (buyer, seller)`** of the profile)

#### Order:

- Route: [https://digital-cow-hut-backend-2.vercel.app/api/v1/orders/64a143bda50aeea1cf4dbd55](https://digital-cow-hut-backend-2.vercel.app/api/v1/orders/6177a5b87d32123f08d2f5d4) (GET) (Can be accessed only by the admin, by the **`specific buyer`** of this order & by the **`specific seller)`** of this order)
