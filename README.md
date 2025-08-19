This project includes a complete setup with MongoDB and Redis integration, secure authentication using JWT with refresh and access tokens, and Stripe-powered payments. It covers essential e-commerce features such as product and category management, shopping cart and checkout flows, coupon code support, and an admin dashboard with sales analytics. The frontend is built with Tailwind for a clean design, while caching with Redis ensures fast performance, and robust security measures protect user data.

### Setup .env file

```bash
PORT=5000
MONGO_URI=your_mongo_uri

UPSTASH_REDIS_URL=your_redis_url

ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

STRIPE_SECRET_KEY=your_stripe_secret_key
CLIENT_URL=http://localhost:5173
NODE_ENV=development
```

### Run this app locally

```shell
npm run build
```

### Start the app

```shell
npm run start
```
