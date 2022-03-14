http-echo
=========
HTTP Echo is a small go web server that serves the contents it was started with
as an HTML page.

The default port is 5678, used in EXPOSE section.
Defined EXPOSE port useful for GitLab CI. 


Port can be configurable via the `-listen` flag:

```
http-echo -listen=:8080 -text="hello world"
```

Then visit http://localhost:8080/ in your browser.
