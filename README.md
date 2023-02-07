# go-micro
# 1. Broker service
  - Handle request
  - Call authentication service
# 2. Authentication service
  - Using postgres to store username and hashed password
  - Using bcrypt to hash and check password matches
