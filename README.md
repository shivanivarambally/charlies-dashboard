# Charlie's Coffee dashboard

A single-page, interactive dashboard of Charlie's six San Francisco stores: sales, inventory, market demand and seventh-store site options.

- Open `index.html` in a browser. It is self-contained: no build step, no external requests.
- Data is summary tables only, taken from workshop (synthetic) BigQuery and AlloyDB datasets as of Oct 26, 2026.
- Revenue estimates for candidate sites are a simple model (forecast ZIP coffee spend x capture rate, minus rent). They are not profit forecasts.
