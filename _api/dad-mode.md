---
title: Dad Mode
position: 1.4
type:
description: 'Minimum Permission Level: Moderator'
parameters:
  - name: action
    content: '"enable" or "disable"'
content_markdown: Update an existing book in your collection.
left_code_blocks:
  - code_block: |-
      $.ajax({
        "url": "http://api.myapp.com/books/3",
        "type": "PUT",
        "data": {
          "token": "YOUR_APP_KEY",
          "score": 5.0,
          "title": "The Book Stealer"
        },
        "success": function(data) {
          alert(data);
        }
      });
    title: jQuery
    language: javascript
right_code_blocks:
  - code_block: |-
      {
        "id": 3,
        "title": "The Book Stealer",
        "score": 5,
        "dateAdded": "5/1/2015"
      }
    title: Response
    language: json
  - code_block: |-
      {
        "error": true,
        "message": "Book doesn't exist"
      }
    title: Error
    language: json
---