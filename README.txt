I have assumed that this codebase is using the updated version of PHP (v8.*^) and Laravel (9.x^). So I applied the following changes.

- Applied constructor property promotion for Booking Controller and Booking Repository
- Implemented route model binding. Laravel automatically resolves Eloquent models defined in routes or controller actions whose type-hinted variable names match a route segment name
- Broke down the logic into smaller, more focused methods to improve readability and maintainability. This was applied on some of the methods of the BookingRepository class
- The naming of variables is sometimes in a camelCase and some of it is in a snake case.




