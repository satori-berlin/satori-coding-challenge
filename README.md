
Here's a coding challenge for you focused on blocking fraudulent transactions in a user interface (UI).

Let's say you're working on a payment system that is experiencing an influx of fraud. To combat this, we need to implement a new feature that allows our anti-fraud team to manage reported transactions.

Your task is to develop a web-based UI that enables the anti-fraud team to block reported transactions and resolve tickets. You can use the provided wireframe as a guide and the example listing response (`data/transactions.json`) as a basis for your listing, but please ignore the "Details" link.

The two buttons in the UI should make calls to your backend service to either block the transaction or resolve the ticket. The blocking implementation is up to you, but resolving should be defined as a `PUT` request to an endpoint with the structure `/transactions/:transactionID`. An example request for updating a report is included in (`data/update_transaction.json`).

- `Block`: Denotes that the transaction should be denied and blocked as fradulent.
- `Resolve`: Denotes that the transaction has been "resolved" and is no longer visible to the anti-fraud team.

### Guidelines

- Please aim to finish within 3 hours.
- React/React Native or another modern frontend framework should be used.
- Provide a link to the solution source code, and if you don't want it public, invite us to a private repository.

### Criteria

- High code quality is preferred over quantity.
- Pragmatic technical choices are necessary.
- A functional UI that fulfills the requirements is required.