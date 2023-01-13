# Test

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.1.0.

## Task Acceptance Criteria

1. create Login page
2. https://www.figma.com/file/ZNchn8BTcKarJyBNyMw9Cz/Starter-Template-Designs?node-id=920%3A653&t=TKkSHBKSO8ebGoun-0
    - use any styling library if preferred ( tailwind, bootstrap, etc...)
3. check form input validations:
   - both inputs are required
   - both inputs max-length is 10
4. send login request
   - Data type
   ```typescript
   export class User {
     public username: string = "";
     public password: string = "";
   }
   ```
- const API: string = 'https://starter-dev.ol.ge/back-starter/resources/admin/session'
5. redirect to an empty page on **successful** login
6. show error text on **successful** login `პაროლი ან მომხმარებლის სახელი არასწორია`
7. build `production build`
8. serve build with http server (http-server, lite-server, etc...) 
