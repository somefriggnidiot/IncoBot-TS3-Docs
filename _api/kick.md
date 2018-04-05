---
title: User Information
position: 1.5
type:
description: 'Minimum Permission Level: Moderator'
parameters:
  - name: query
    content: >-
      String containing a client's nickname, a portion of a client's nickname,
      or a special query.
content_markdown: >-
  Retrieves information about users whose names the query partially matches.
  Special query @me retrieves information about the user who called the command.
  Failing to provide a query results in all online users being returned.
left_code_blocks:
  - code_block: |-
      $.ajax({
        "url": "http://api.myapp.com/books/3",
        "type": "DELETE",
        "data": {
          "token": "YOUR_APP_KEY"
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
        "status": "deleted"
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

