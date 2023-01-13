# Test

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.1.0.

## skills

- angular :
  - create component
  - create route
  - use HttpClient
  - use _dependency injection_ for HttpClientModule 
  - build and serve project
- styling (css, scss)
- type definitions and usage
- send and receive information with http requests

## Task Acceptance Criteria

1. შექმენი Login page ახალ route-ზე - `/auth`
2. [login page design](https://www.figma.com/file/ZNchn8BTcKarJyBNyMw9Cz/Starter-Template-Designs?node-id=920%3A653&t=TKkSHBKSO8ebGoun-0)

3. შეამოწმე ფორმის ინფუთების ვალიდურობა და შესაბამისად გააწითლე _border-color_ : `red`:
   - ორივე ინფუთი არის `required`
   - ორივე ინფუთი მასქიმალური ტექსტის ზომა არის 10
4. გააგზავნე _login request_
   - Request type : `post`
   - Send Data type
   ```typescript
   class User {
     public username: string = "";
     public password: string = "";
   }
   ```

- const API: string = 'https://starter-dev.ol.ge/back-starter/resources/admin/session'

<!-- 5. redirect to an empty page on **successful** login -->
6. show error text on **successful** login `პაროლი ან მომხმარებლის სახელი არასწორია`
7. build `production build`
8. serve build with http server (http-server, lite-server, etc...)
