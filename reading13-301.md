# CRUD

## -

### *Which HTTP method would you use to update a record through an API?

- Togo is really adorable, maybe we should see him sooner! For us to reschedule the appointment for an earlier time we can use the corresponding HTTP method for updating your playdate with PUT. This replaces all current data of the target resource (Togo) with the uploaded content (new appointment time/date). The ‘id’ in the route is how the resource is targeted (Togo) to ensure we only update the specified appointment, while leaving any others we may have scheduled untouched

### *Which REST methods require an ID parameter?

- Delete and update

### *What’s the relationship between REST and CRUD?

- CRUD is an action performed to write data into a database, whereas REST is compatible with any object or resource, from a media file, website to document, and other services

### *If you had to describe the process of creating a RESTful API in 5 steps, what would they be?

- recommend splitting your API into 3 layers, each responsible for a single requirement.

- Currently, REST is the most popular approach to building web APIs, representing over 70% of public APIs.

- Poorly designed APIs can be a major source of vulnerabilities – improper authentication, API keys in URI, unencrypted sensitive data, injections, replay attacks, stack trace leaks, DDoS attacks, and so on. So pay strict attention to security at the design stage by incorporating these 4 security layers

- After you’ve finished your API design, it’s time to build your own API. This is an iterative process. We like to build our APIs one endpoint at a time, gradually adding more functionalities, testing them, and writing detailed documentation

- Sometimes, API responses contain too much data. For example, there can be thousands of products relevant to a search in an e-commerce app. Sending all of that in a single response would be extremely taxing on your database.

To decrease response times and protect your API against DDoS attacks, split the data into several “pages”. For easier navigation, each page should have its own URI. The API should only display a portion of data in one go and let users know how many pages remain. There are several pagination methods to choose from: