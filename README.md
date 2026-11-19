# React Storefront Prototype

A storefront and checkout UI built with React and Vite. The project translates a shopping-page layout into React pages, with product imagery, ratings, quantity controls, and an order-summary view.

**Stack:** React 19 · React Router · JavaScript · Vite · CSS

[Published demo](https://sidd2006.github.io/ecommerce-project/) · [Application source](ecommerce-project/src)

## Current scope

- Product-card layouts with images, prices, and ratings.
- Shopping-header and search-field presentation.
- A checkout page with delivery-option and payment-summary layouts.
- Route declarations for the home page and `/checkout`.

The current pages use static product and order content. Search, cart mutations, persistence, and payment processing are not implemented as application behavior. Some navigation links still use the starter HTML paths.

## Run locally

The Vite app lives in a nested directory:

```bash
git clone https://github.com/sidd2006/ecommerce-project.git
cd ecommerce-project/ecommerce-project
npm ci
npm run dev
```

Open the URL printed by Vite.

## Development commands

| Command | Purpose |
| --- | --- |
| `npm run dev` | Start the development server |
| `npm run build` | Build the production assets |
| `npm run preview` | Preview the built application |
| `npm run lint` | Run ESLint |

## Repository guide

| Path | Purpose |
| --- | --- |
| [App.jsx](ecommerce-project/src/App.jsx) | Route declarations |
| [HomePage.jsx](ecommerce-project/src/Pages/HomePage.jsx) | Product listing layout |
| [CheckoutPage.jsx](ecommerce-project/src/Pages/CheckoutPage.jsx) | Checkout and order-summary layout |
| [public/images](ecommerce-project/public/images) | Product and interface assets |
| [starting-code](ecommerce-project/starting-code) | Retained starter HTML, CSS, and sample data |

## Project context

A frontend learning prototype built around starter storefront content. The repository retains the starter assets and files so their relationship to the React implementation is visible.

## License

See [LICENSE](LICENSE).
