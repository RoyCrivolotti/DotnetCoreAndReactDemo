# Demo app

Small project to refresh my memory of .NET. Using .NET Core for the first time, and React on the front-end.

Clean architecture: API ring as entry point -> application ring with business logic -> domain ring without dependencies

Application project has a dependency on the Domain, which contains our Domain's entities and is dependent on nothing.
Persistence layer provides access to the database.
