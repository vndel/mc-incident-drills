# Backend loss exercise

## Preconditions
- Staging network, disposable data, tested backup, and communications channel.
- Abort if persistence errors occur or unrelated services degrade.

## Exercise
1. Record baseline health and active session count.
2. Remove one backend from service discovery.
3. Observe admission, player messaging, and remaining-node load.
4. Restore the backend and validate world/data integrity.

## Success criteria
- New sessions avoid the failed backend.
- Operators receive an actionable alert.
- No duplicate economic mutation is observed.
