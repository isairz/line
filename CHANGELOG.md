## 2.0.0.0 (4 Dev 2016)

* Make `Line.Messaging.Webhook.Validation` independent from WAI. As it does not
  use `Request` of WAI, its argument type is changed.
* Remove `WebhookResult`, as returning other than empty string is meaningless
  for webhook response
* Add Scotty version of webhook handler
* Add Stack yaml to fix macOS Sierra problem
* Derive `Eq` type class for `APIErrorBody`
* Make optional fields of template messages have type of `Maybe a`

## 1.0.1.0 (28 Nov 2016)

* Update lower bound of `base` to 4.8 (Issue: #2)
* Add Stack yamls for lts-6.26 resolver

## 1.0.0.1 (27 Nov 2016)

* Documentation fix

## 1.0.0.0 (27 Nov 2016)

* Initial release