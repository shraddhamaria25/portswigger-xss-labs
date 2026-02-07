## Lab: Reflected XSS – simple case

**Platform:** PortSwigger Web Security Academy  
**Vulnerability:** Reflected Cross-Site Scripting (XSS)

### Entry Point
Search / URL parameter

### Payload Used
<script>alert(1)</script>

### Result
Injected JavaScript executed in the browser, confirming a reflected XSS vulnerability.

### Learning
Unsanitized user input reflected in responses can lead to arbitrary JavaScript execution.
