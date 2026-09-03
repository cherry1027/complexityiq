# ComplexityIQ

ComplexityIQ is a manufacturing analytics prototype developed for a Master's thesis on **Product & Portfolio Complexity Cost Management**.

It helps manufacturing companies answer:

> **Is reducing product complexity economically worthwhile?**

The application converts product and portfolio complexity into measurable operational costs, financial savings, and investment decisions.

## Main features

- **Executive Dashboard** — KPIs for products, variants, components, suppliers, complexity costs, commonality, and potential savings.
- **Complexity Driver Map** — analysis of Product Design, Manufacturing, Supply Chain, Engineering, and Lifecycle complexity.
- **Product Portfolio** — comparison of production volumes, components, suppliers, engineering hours, tooling, inventory, and complexity scores.
- **ABC Analysis** — identifies high-complexity and low-volume components as rationalization candidates.
- **Complexity Cost Calculator** — calculates direct, indirect, and lifecycle complexity costs.
- **Business Case Simulator** — compares current complexity with reduction proposals such as three regional variants becoming one global platform.
- **Scenario Comparison** — compares the current portfolio with component standardization, modularization, and global-platform strategies.
- **Value / Function Trade-off** — evaluates whether savings justify additional material costs or reduced customer functionality.
- **Industry Benchmark** — presents illustrative complexity-reduction methods such as modularization, common components, SKU rationalization, platform sharing, and late variants.
- **Methodology & Report** — summarizes assumptions, calculations, findings, and the recommended decision.

## Financial calculations

All financial results are calculated deterministically from editable assumptions. The application does not use AI-generated financial numbers.

- **ROI** = `(cumulative net benefit − investment) / investment`
- **Payback period** = `investment / annual net benefit`
- **NPV** = `−initial investment + Σ net cash flow / (1 + discount rate)^t`
- **Five-year benefit** = `five-year net operating benefit − initial investment`

Financial values are displayed in Swedish kronor using SEK and MSEK.

## Data notice

> **Synthetic demonstration data – not actual company data.**

All products, components, suppliers, production volumes, costs, savings, and benchmark values are fictional and intended only for research and prototype demonstration.

## Technology stack

- React
- Vinext / Next.js-compatible structure
- TypeScript
- Tailwind CSS
- shadcn/ui
- Recharts
- Cloudflare Workers-compatible build

## Run locally

Node.js 22.13 or newer is recommended.

```bash
npm install
npm run dev
