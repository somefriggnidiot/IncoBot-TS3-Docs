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
  - code_block: '@me (Returns information about the caller only.)'
    title: Special Query Params
    language:
right_code_blocks:
  - code_block: '!userinfo TeamSpeak User'
    title: Full Name Example
    language:
  - code_block: '!userinfo speak'
    title: Partial Name Example
    language:
  - code_block: '!userinfo @me'
    title: Special Query Example
    language:
---

