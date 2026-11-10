# Analytics Event Tracking Plan

| Event name | Trigger | Required properties | User / session identity | Purpose |
|---|---|---|---|---|
| search_submitted | User submits a search | category, result_count, timestamp | Pseudonymous ID | Search funnel |
| option_selected | User selects an option | option_type, position | Pseudonymous ID | Selection funnel |
| checkout_started | Checkout begins | transaction_type | Pseudonymous ID | Checkout funnel |
| transaction_completed | Confirmed completion | transaction_type, outcome | Pseudonymous ID | Conversion |

Do not place passwords, payment card data, medical details or unnecessary personal information in analytics events. Apply consent, retention and access controls.