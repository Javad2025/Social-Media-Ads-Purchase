# Social Network Ads — Purchase Prediction

This project explores whether information about a social-network user can help predict if they will purchase a product after seeing an advertisement.

## Project Goal

The goal is to predict the `Purchased` outcome:

- `0` — The user did not purchase the product
- `1` — The user purchased the product

## Dataset

Each row represents one social-network user. The dataset includes:

- **Gender** — The user’s gender
- **Age** — The user’s age
- **EstimatedSalary** — The user’s estimated annual salary
- **Purchased** — Whether the user purchased the advertised product

## Why This Matters

Businesses can use this kind of prediction to better understand which users may be interested in a product. This can support more relevant advertising, audience targeting, and marketing decisions.

## Example Prediction

For a new user:

| Gender | Age | Estimated Salary |
|---|---:|---:|
| Male | 24 | 19,000 |

The project estimates the probability that the user will purchase the product and assigns a predicted outcome of either purchased (`1`) or not purchased (`0`).
