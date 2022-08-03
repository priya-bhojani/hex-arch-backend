This is a typescript project based on Hexagonal architecture

Features :
1. Add message
2. Get messages

Directory structures: 

1. Handlers: src/adapters/api-gateway
2. Repository: src/adapters/message-repository
3. Domain: src/domain
4. Business logic: src/use-cases

Trade-off :

As I had very limited time to finish this sample, there are few trade-offs that I decided to make:

1. Clean architecture: Yes
2. Error handling : No
3. TDD: Yes
4. Database connection: No (static response from repository)
5. Simple responses from business use-cases and handlers: Yes
6. Clean code: A big Yes!
