# 🔌 API Contracts — GharTak

## Auth
POST /auth/otp
POST /auth/login

## Stores
GET /stores/nearby
GET /stores/:id

## Products
GET /products
GET /products/search

## Cart
GET /cart
POST /cart/items
DELETE /cart/items/:id

## Orders
POST /orders
GET /orders/:id
GET /orders/history
PATCH /orders/cancel

## Payments
POST /payments/razorpay
POST /payments/webhook

## Delivery
POST /delivery/accept
POST /delivery/delivered

All APIs must use DTO validation.
