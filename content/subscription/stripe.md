+++
fragment = "stripe"
weight = 200
background = "light"

post_url = "https://europe-west1-stripe-226317.cloudfunctions.net/stripe"
stripe_token = "pk_live_Y8F97q5eue7uaHcf9h68ZlpI"

product = "TXTDirect Subscription"

[[prices]]
  text = "$4000/year"
  currency = "usd"

[email]
  label = "Your email address"
+++

*Payment secured and provided by Stripe*