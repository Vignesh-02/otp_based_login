# otp_based_login

two apis
1.get otp
POST https://otp-based-login-ran6.onrender.com/getOTP
Requires 1 field in the body - "email"

2.login
POST https://otp-based-login-ran6.onrender.com/login
Requires 2 fields in the body - "email" and "otp"
