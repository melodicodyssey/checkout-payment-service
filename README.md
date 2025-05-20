# checkout-payment-service
A Service for handling payment requests/storage for our sample Checkout application

# checkout-payment-service

## Overview

The `checkout-payment-service` is the microservice responsible for handling payment service logic.

## Responsibilities

- Create and confirm Stripe payment intents
- Handle Stripe webhook events
- Emit events on payment success/failure

## API (WIP)

This service exposes REST endpoints which will be documented as the application evolves.

## Development

Each service will be containerized with a `Dockerfile` and configured for local development via `docker-compose`.

## License

Licensed under the [MIT License](./LICENSE).

---

> Tagged with: `#1 Scope out Checkout app project`
