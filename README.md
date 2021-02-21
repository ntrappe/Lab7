# Lab7
#### Nicole Trappe
A15003578

#### Published Site
https://ntrappe.github.io/Lab7/

#### Notes to Self
- if not running server via `json-server --watch db.json` will get back a Network error
- if running server, get an 'OK' response and data
- DO NOT use innerHTML for displaying data bc it says undefined; instread, use textContent
- DO NOT use `return response.json();` becase it's actually html/text content so just do `return response.text();`
- using `response.ok` checks that codes (e.g. `GET /posts 304 8.349 ms - -`) are valid aka between 200-299
  - throw error ref: https://gist.github.com/odewahn/5a5eeb23279eed6a80d7798fdb47fe91