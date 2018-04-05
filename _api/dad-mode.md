---
title: Dad Mode
position: 1.4
type:
description: 'Minimum Permission Level: Moderator'
parameters:
  - name: action
    content: '"enable" or "disable"'
content_markdown: >-
  Enables or disables DadMode functionality. When enabled, the bot will
  automatically respond to messages along the lines of "I'm {X}" with "Hi, {X}.
  I'm dad!"
left_code_blocks:
  - code_block: |-
      enable
      on
    title: '"Enable" Aliases'
    language:
  - code_block: |-
      disable
      off
    title: Disable
    language:
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