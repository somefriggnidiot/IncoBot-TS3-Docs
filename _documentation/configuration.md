---
title: Configuration
position: 2
parameters:
  - name:
    content:
content_markdown: |-
  #### Connection Configuration

  `test code script`

  ```testing code block```
left_code_blocks:
  - code_block:
    title:
    language:
right_code_blocks:
  - code_block: |2-
       $.get("http://api.myapp.com/books/", { "token": "YOUR_APP_KEY"}, function(data) {
         alert(data);
       });
    title: JQuery
    language: javascript
  - code_block: ' curl http://api.myapp.com/books?token=YOUR_APP_KEY'
    title: Curl
    language: bash
---