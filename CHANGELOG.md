# 1.1.0 (2021-10-27)
* Bugfix: Allow any list for field value updates for category fields (see #4).
* Feature: Log request body (DEBUG level).
* Chore: Run builds on ubuntu 20.

# 1.0.3 (including 1.0.1/1.0.2)
* Allow for custom filter implementations
* Handle http errors without defined HTTP status gracefully.
* Make custom jackson json provider available for clients that create a custom http client.

# 1.0.0
* Changed maven coordinates.
* Upgraded http client from jersey 1 to jersey 2.
* Removed `APITransportException`. Instead a `javax.ws.rs.ProcessingException` will be thrown.
