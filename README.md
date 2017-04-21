# Angular2-todoApp
Angular2-todoApp


npm install
npm start


Видео уроки здесь: 
https://codedojo.ru/courses/angular2-intro/introduction
https://www.youtube.com/watch?v=RCok3uXqyk8&list=PLqHlAwsJRxANlSuRSgldPWsbNkPqVBeFp&index=11



если при комите Git пишет ошибку fatal: LF would be replaced by CRLF in ...

как необходимо настроить git что бы избавиться от данной ошибки?
совсем «избавиться» от сообщения можно, вернув значение по умолчанию:

$ git config --global core.safecrlf false
заменить же сообщение об ошибке на предупреждение можно так:

$ git config --global core.safecrlf warn
