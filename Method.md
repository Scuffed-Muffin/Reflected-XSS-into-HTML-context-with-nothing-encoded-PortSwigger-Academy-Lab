**Lab name: Reflected XSS into HTML context with nothing encoded**
<br>
*Link to Lab* https://portswigger.net/web-security/cross-site-scripting/reflected/lab-html-context-nothing-encoded
<br><br><br><br><br>
When I enetered the Lab, I was presented with a website full of blogs.
<img width="1706" height="949" alt="image" src="https://github.com/user-attachments/assets/45f1395d-dae8-48b2-99cb-aa8cb9df781d" />
After exploring the page further I found a possible reflected XSS point, the search bar.
From the information given before the lab, I knew that the simplest XSS payload would be: 
```
<script>alert()</script>
```
When this payload is put in the search bar an alert pops up on screen and the Lab is marked as done.
Since this was the easiest lab, it was no surprise that the basic payload works, however in future labs, the payloads required will be more complex to bypass filters.
