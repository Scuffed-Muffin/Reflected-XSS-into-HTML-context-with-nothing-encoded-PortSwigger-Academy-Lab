**Lab name: Reflected XSS into HTML context with nothing encoded**
<br>
*Link to Lab* https://portswigger.net/web-security/cross-site-scripting/reflected/lab-html-context-nothing-encoded
<br><br><br><br><br>
When I enetered the Lab, I was presented with a website full of blogs.
<img width="1706" height="949" alt="image" src="https://github.com/user-attachments/assets/45f1395d-dae8-48b2-99cb-aa8cb9df781d" />
After explorig the page further I found 2 possible XSS points, the search bar and the comments section.
From the information given before the lab, I knew that the simplest XSS payload would be: 
```
<script>alert()</script>
```
When this payload is put in either the search bar or the comments section an alert pops up on screen and the Lab is marked as done.
However, when using the comments box you must fill out all the details before submiting making it harder in the future to trial different payloads.
