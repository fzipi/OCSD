# Sample Question Bank

These samples show the expected style and depth of the assessment.
They are not the real exam.

## Question format

- Single best answer, four options (A-D).
- Each question maps to one body-of-knowledge topic, shown in the traceability table.
- Questions test recognition and discrimination, not coding or tool operation.

## Traceability

| Question | Module | Topic |
|---|---|---|
| 1 | 1 | 1.3 |
| 2 | 1 | 1.2 |
| 3 | 1 | 1.2 |
| 4 | 2 | 2.5 |
| 5 | 2 | 2.2 |
| 6 | 2 | 2.4 |
| 7 | 2 | 2.7 |
| 8 | 2 | 2.6 |
| 9 | 3 | 3.2 |
| 10 | 3 | 3.3 |
| 11 | 3 | 3.4 |
| 12 | 4 | 4.3 |
| 13 | 4 | 4.4 |
| 14 | 4 | 4.2 |
| 15 | 5 | 5.2 |
| 16 | 5 | 5.3 |
| 17 | 5 | 5.7 |
| 18 | 6 | 6.3 |
| 19 | 6 | 6.4 |
| 20 | 6 | 6.5 |
| 21 | 7 | 7.3 |
| 22 | 7 | 7.4 |
| 23 | 7 | 7.6 |
| 24 | 8 | 8.4 |
| 25 | 8 | 8.5 |
| 26 | 8 | 8.3 |
| 27 | 9 | 9.3 |
| 28 | 9 | 9.1 |
| 29 | 9 | 9.6 |
| 30 | 9 | 9.2 |
| 31 | 10 | 10.4 |
| 32 | 10 | 10.4 |
| 33 | 10 | 10.5 |
| 34 | 11 | 11.4 |
| 35 | 11 | 11.3 |
| 36 | 11 | 11.2 |
| 37 | 12 | 12.1 |
| 38 | 12 | 12.3 |
| 39 | 12 | 12.8 |
| 40 | 13 | 13.1 |
| 41 | 13 | 13.3 |
| 42 | 13 | 13.4 |
| 43 | 14 | 14.5 |
| 44 | 14 | 14.4 |
| 45 | 14 | 14.7 |
| 46 | 15 | 15.1 |
| 47 | 15 | 15.2 |
| 48 | 15 | 15.5 |
| 49 | 16 | 16.6 |
| 50 | 16 | 16.4 |
| 51 | 16 | 16.9 |

## Question 1: Which question of the Four Question Framework for threat modeling asks "What can go wrong?"

- A. It lists what the system is working on
- B. It decides which threats to accept
- C. It identifies threats against the system being built
- D. It checks whether the work done was good enough

Correct answer: C

## Question 2: A design lets any internal service call any other internal service because the network is "trusted". Which design assumption does this violate?

- A. Fail open: errors should allow the request
- B. Security through obscurity: hide the internal network
- C. Single sign-on: users authenticate once
- D. Zero Trust: every request is verified explicitly and trust is not granted by network location

Correct answer: D

## Question 3: Which statement best distinguishes a design flaw from an implementation defect?

- A. A design flaw is always a missing patch, while an implementation defect is a missing feature
- B. A design flaw is in the design itself, so a perfect implementation of it is still insecure
- C. A design flaw can be found only by a penetration test
- D. A design flaw only appears in the user interface

Correct answer: B

## Question 4: What is cross-site request forgery (CSRF)?

- A. An attack that guesses passwords with a list of common values
- B. An attack that injects scripts into a page for other users
- C. An attack that causes a victim's browser to send an unwanted authenticated request to a site
- D. An attack that injects SQL commands into queries

Correct answer: C

## Question 5: Which is a good practice for storing user passwords?

- A. Hashing them once with SHA-1
- B. Hashing them with a slow, salted password hashing function such as Argon2id
- C. Encrypting them with AES and keeping the key in the source code
- D. Encoding them with Base64

Correct answer: B

## Question 6: Which measure reduces the exposure of session cookies?

- A. Storing the session identifier in localStorage so scripts can read it
- B. Using the same session identifier before and after login
- C. Setting the Secure and HttpOnly attributes and generating a new session identifier after login
- D. Storing the session identifier in the URL

Correct answer: C

## Question 7: Which finding is a sign of broken authentication?

- A. Rate limiting on login attempts
- B. Password hashing with bcrypt
- C. Multi-factor authentication on sensitive actions
- D. Hardcoded administrator credentials in the application

Correct answer: D

## Question 8: What does the signature on a signed JWT provide?

- A. Proof that the token will never expire
- B. Protection against modification of the claims, but not confidentiality
- C. Protection of the token against being stolen
- D. Encryption of the claims so that clients cannot read them

Correct answer: B

## Question 9: What does the principle of least privilege mean?

- A. Granting administrator rights to everyone by default
- B. Denying everything and never granting any right
- C. Granting only the minimum access rights needed to do the task
- D. Letting users raise their own privileges when needed

Correct answer: C

## Question 10: Where must an authorization decision for a request be enforced?

- A. In the client, by hiding buttons the user may not use
- B. Only in the load balancer
- C. Only at login time
- D. On the server, for every request, regardless of what the client hides or shows

Correct answer: D

## Question 11: A user changes the order number in a URL and sees another user's order. Which failure is this?

- A. Missing TLS
- B. Missing object-level authorization (insecure direct object reference)
- C. Cross-site request forgery
- D. Weak password hashing

Correct answer: B

## Question 12: What is the most effective way to prevent SQL injection?

- A. Encrypt all user input
- B. Concatenate strings and limit the input length
- C. Apply HTML encoding to the output
- D. Use parameterized (prepared) statements

Correct answer: D

## Question 13: Which control best mitigates cross-site scripting (XSS)?

- A. Hashing the request body
- B. Rate limiting requests
- C. Context-appropriate output encoding
- D. Using HTTPS instead of HTTP

Correct answer: C

## Question 14: Which approach to input validation is preferred?

- A. Validate only in the browser
- B. Remove the characters that look dangerous and accept the rest
- C. Validate on the server against an allowlist of expected values, format and length
- D. Reject a list of known bad strings and accept the rest

Correct answer: C

## Question 15: Which statement correctly distinguishes encoding, encryption, and hashing?

- A. Encoding needs a key, encryption does not, and hashing is reversible
- B. Hashing needs a key, and encryption is one-way
- C. All three protect confidentiality equally
- D. Encoding is reversible by anyone, encryption is reversible only with a key, and hashing is one-way

Correct answer: D

## Question 16: Which property does authenticated encryption (for example AES-GCM) provide in addition to confidentiality?

- A. Integrity and authenticity of the data
- B. Faster key generation
- C. Protection from weak passwords
- D. Non-repudiation of the sender

Correct answer: A

## Question 17: Where should an application keep the keys it uses to encrypt data?

- A. In a key management service or secrets manager, separate from the encrypted data
- B. In the browser, so that the user holds the key
- C. In the source code next to the encrypted data
- D. In a configuration file in the same database table

Correct answer: A

## Question 18: Which error message is appropriate to show to an end user in production?

- A. The server file path where the error occurred
- B. A generic message with a reference identifier, with the details written to the server log
- C. The full stack trace to help support
- D. The SQL error text returned by the database

Correct answer: B

## Question 19: An authorization service times out while checking a request. What does failing securely mean here?

- A. Return the internal exception to the client
- B. Deny the request and log the failure
- C. Skip the check and retry later without a result
- D. Allow the request so users are not blocked

Correct answer: B

## Question 20: Why use a centralized error handler?

- A. It lets each developer decide the message format
- B. It removes the need to log errors
- C. It makes every error return HTTP 200
- D. It gives consistent, safe responses and avoids unhandled exceptions leaking details

Correct answer: D

## Question 21: Which data must not be written to application logs?

- A. Passwords, session identifiers, and full payment card numbers
- B. The ID of the user who performed an action
- C. The time of the event
- D. The result of a login attempt

Correct answer: A

## Question 22: An attacker submits a username containing a line break and a fake log line. What is this attack?

- A. Cross-site request forgery
- B. Log injection
- C. Session fixation
- D. Directory traversal

Correct answer: B

## Question 23: Which practice best helps detect suspicious user behavior?

- A. Blocking all cookies
- B. Changing passwords every week
- C. Enabling HTTPS
- D. Logging security events and monitoring and alerting on them

Correct answer: D

## Question 24: Which approach gives a pseudonym that cannot be recovered by guessing common email addresses?

- A. Base64 encoding of the email address
- B. A keyed hash (HMAC) with the key stored separately, or a token lookup
- C. MD5 of the email address with a fixed salt
- D. SHA-256 of the email address

Correct answer: B

## Question 25: Which method is the most reliable way to make data on cloud or SSD storage unrecoverable?

- A. Move the file to the recycle bin
- B. Cryptographic erasure: destroy the key that encrypts the data
- C. Overwrite the file once
- D. Rename the file

Correct answer: B

## Question 26: What does data minimization mean?

- A. Keep personal data forever in case it is useful
- B. Compress personal data to save space
- C. Store personal data in one table
- D. Collect and keep only the personal data that is needed for the stated purpose

Correct answer: D

## Question 27: Which HTTP response header tells a browser to use HTTPS only for a site after the first visit?

- A. Strict-Transport-Security
- B. X-Frame-Options
- C. Access-Control-Allow-Origin
- D. Referrer-Policy

Correct answer: A

## Question 28: Why is HTTPS important for all pages, not only login pages?

- A. It protects confidentiality and integrity of all traffic, including session cookies
- B. It improves search ranking
- C. It stops SQL injection
- D. It makes cookies work

Correct answer: A

## Question 29: What is the purpose of Content Security Policy (CSP)?

- A. To set cookie expiry times
- B. To encrypt API data in transit
- C. To enforce password complexity
- D. To tell the browser which sources of content a page may load and execute

Correct answer: D

## Question 30: A client application cannot verify the server certificate and the developer disables certificate validation to make the error go away. What is the risk?

- A. The server runs more slowly
- B. Anyone on the network path can impersonate the server (man-in-the-middle)
- C. The certificate expires sooner
- D. Cookies stop working

Correct answer: B

## Question 31: Which practice helps identify known vulnerable dependencies?

- A. Reading the README of each package
- B. Installing only packages that have many downloads
- C. Running a firewall in front of the application
- D. Maintaining a component inventory and running software composition analysis (SCA) on it

Correct answer: D

## Question 32: What is a static application security testing (SAST) tool used for?

- A. Analyzing the code you write for weaknesses without running it
- B. Monitoring traffic between client and server
- C. Listing known vulnerabilities of third-party libraries
- D. Managing firewall rules

Correct answer: A

## Question 33: What does verifying a digital signature on a downloaded build artifact show?

- A. That it is the newest version
- B. That it contains no vulnerabilities
- C. That it was signed by the holder of the key and has not been changed since
- D. That the publisher is trustworthy

Correct answer: C

## Question 34: A shop accepts the price of an item in the request from the browser. Which is the correct control?

- A. Hide the price field in the page
- B. Limit the price field to numbers
- C. Calculate the price on the server from trusted data
- D. Sign the page with HTTPS

Correct answer: C

## Question 35: Two requests redeem the same single-use coupon at the same moment, and both succeed. What is this flaw?

- A. SQL injection
- B. Cross-site scripting
- C. A race condition (time-of-check to time-of-use)
- D. Weak session identifier

Correct answer: C

## Question 36: A multi-step checkout can be completed by sending the last step directly. Which control addresses this?

- A. Disable the back button
- B. Encode the step number in the URL
- C. Check the stored workflow state on the server at each step
- D. Use a longer session timeout

Correct answer: C

## Question 37: Which is a safe way to handle a user-uploaded file?

- A. Validate its type, size, and content on the server, and store it outside the web root with a generated name
- B. Store it in the web root using the original name
- C. Trust the file extension and the Content-Type sent by the client
- D. Execute it to check that it works

Correct answer: A

## Question 38: A download endpoint builds a path from the file name in the request. What attack should the developer expect?

- A. Clickjacking
- B. Cross-site request forgery
- C. Session fixation
- D. Path traversal, for example a name containing ../

Correct answer: D

## Question 39: What does server-side request forgery (SSRF) let an attacker do?

- A. Make the server send requests to internal or other unintended destinations
- B. Make the browser send a form without the user knowing
- C. Read the source code of the client
- D. Guess user passwords

Correct answer: A

## Question 40: What does the API Security Top 10 call a missing check that lets a caller access another user's object by changing its ID?

- A. Broken Object Level Authorization
- B. Server-Side Request Forgery
- C. Security Misconfiguration
- D. Unrestricted Resource Consumption

Correct answer: A

## Question 41: Which control helps limit abuse of an API by one client?

- A. Rate limiting and quotas per client
- B. Logging requests without limits
- C. Allowing unlimited page sizes
- D. Returning all fields for every object

Correct answer: A

## Question 42: An API returns the whole database record, and the client hides the sensitive fields. What is wrong?

- A. The API should use GET instead of POST
- B. The record should be sent as XML
- C. The server should return only the fields the caller is allowed to see
- D. The client should hide more fields

Correct answer: C

## Question 43: Which is a secure way to handle API secrets in a deployed application?

- A. Send them to developers by email
- B. Store them in a version-controlled .env file
- C. Store them in a dedicated secrets manager and give the application access at runtime
- D. Hardcode them in the source code

Correct answer: C

## Question 44: What is a secure default for a new deployment?

- A. The default administrator password left in place
- B. Directory listing enabled
- C. Debug features and sample accounts are disabled, and only needed services are enabled
- D. Verbose error pages enabled to help troubleshooting

Correct answer: C

## Question 45: Which practice protects a build pipeline?

- A. Give pipeline jobs only the permissions they need and keep secrets out of build logs
- B. Run builds on any pull request with full secrets
- C. Disable logging to save space
- D. Share one administrator token across all jobs

Correct answer: A

## Question 46: Which risk happens when a model's output is passed to a database or shell without validation?

- A. Unbounded Consumption
- B. Misinformation
- C. Vector and Embedding Weaknesses
- D. Improper Output Handling

Correct answer: D

## Question 47: Which statement about system prompts is correct?

- A. A system prompt can be revealed, so no secret or access rule should depend on it staying hidden
- B. Obfuscating the prompt makes revealing it impossible
- C. A system prompt is a safe place for API keys
- D. Telling the model to keep it secret is a reliable control

Correct answer: A

## Question 48: An LLM agent can send emails and delete files for any user request. Which risk does this show?

- A. Model compression
- B. Excessive Agency
- C. Prompt hashing
- D. Misinformation

Correct answer: B

## Question 49: Where should a developer keep access tokens for tools such as source hosting?

- A. In a password manager or secrets store, never in the repository
- B. In a text file in the project folder
- C. In the commit message
- D. In a shared chat channel

Correct answer: A

## Question 50: What is a security concern when installing an IDE plugin?

- A. The plugin runs with the developer's privileges and may be malicious or compromised
- B. Plugins cannot access the files in the project
- C. Plugins make the IDE slower only
- D. Plugins are always reviewed by the vendor

Correct answer: A

## Question 51: You receive an unexpected message asking you to run a command to "fix" your build. What is the right action?

- A. Run it with administrator rights
- B. Forward it to the team without checking
- C. Run it in your normal account to see what happens
- D. Do not run it, verify the request through another channel, and report it

Correct answer: D
