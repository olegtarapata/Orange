# Orange
User management system

A lot of projects need user management systems(UMS). UMS includes creating/updating/deleting users, 
keeping passwords, handling authentication and authorization, integrating with OAuth providers, etc.

This project intended to simplify and speed up developing new projects which operates with users.
It can be deployed as microservice.

Also key concept is high extensibility, it should be like lego for end clients.

Main functionality:
- CRUD user operations
- Authentication
- OAuth integration
- Authorization

What should Orange support:
- Transports: 
  - rest
  - grpc
- Databases:
  - Cassandra
  - Mongo
  - Postgres
- Service discovery
- Auto scaling/descaling
