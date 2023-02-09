# go-micro
# 1. Broker service
  - Handle request
  - Call authentication service
# 2. Authentication service
  - Using Postgres to store username and hashed password
  - Using bcrypt to hash and check password matches
# 3. Logger service
  - Call by another service only (Broker, Authentication)
  - Using MongoDB to store log
# 4. Mail service
  - Send email to Mailhog
