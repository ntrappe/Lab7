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