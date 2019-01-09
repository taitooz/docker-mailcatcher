Docker mailcatcher
===========

[Mailcatcher](http://mailcatcher.me) 

Run with : `docker run -d -p 2525:1025 -p 9290:1080 --name mailcatcher taitooz/mailcatcher`

Deliver mails to smtp://127.0.0.1:2525 and check out [http://127.0.0.1:9290/catcher]() to see them.

This images use the beta gem mailcatcher 0.7.0.beta1 to use the --http-path parameter in the mailcatcher app.

Environment variables
---------------------
**SMTP_PORT** Change default SMTP port (default: 1025)

**HTTP_PORT** Change default HTTP port (default: 1080)
