[in postman it shows errors like these][1]


  [1]: https://i.stack.imgur.com/uwNK4.png

[org.springframework.web.bind.MethodArgumentNotValidException: Validation failed for argument [0] in public org.springframework.http.ResponseEntity<?> com.loizenai.jwtauthentication.controller.AuthRestAPIs.registerUser(com.loizenai.jwtauthentication.message.request.SignUpForm): [Field error in object 'signUpForm' on field 'password': rejected value [null]; codes [NotBlank.signUpForm.password,NotBlank.password,NotBlank.java.lang.String,NotBlank]; arguments [org.springframework.context.support.DefaultMessageSourceResolvable: codes [signUpForm.password,password]; arguments []; default message [password]]; default message [must not be blank]] ]
.l.j.security.jwt.JwtAuthEntryPoint  Unauthorized error. Message - Bad credentials

[2m2021-07-23 08:59:20.759[0;39m [33m WARN[0;39m [35m10404[0;39m [2m---[0;39m [2m[nio-8080-exec-5][0;39m [36m.w.s.m.s.DefaultHandlerExceptionResolver[0;39m [2m:[0;39m Resolved [org.springframework.web.bind.MethodArgumentNotValidException: Validation failed for argument [0] in public org.springframework.http.ResponseEntity<?> com.loizenai.jwtauthentication.controller.AuthRestAPIs.registerUser(com.loizenai.jwtauthentication.message.request.SignUpForm): [Field error in object 'signUpForm' on field 'password': rejected value [null]; codes [NotBlank.signUpForm.password,NotBlank.password,NotBlank.java.lang.String,NotBlank]; arguments [org.springframework.context.support.DefaultMessageSourceResolvable: codes [signUpForm.password,password]; arguments []; default message [password]]; default message [must not be blank]] ]
