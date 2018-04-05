---
title: Idle Checker
position: 1
type:
description: 'Minimum Permission Level: Admin'
parameters:
  - name: action
    content: '"enable", "disable", or "status"'
content_markdown: >-
  Controls aspects of the Idle Checker / Idle Mover functionality. When enabled,
  users who are idle longer than the designated time threshold will be
  automatically moved to the specified channel.
left_code_blocks:
  - code_block:
    title: Enable Module
    language:
  - code_block: '!idlechecker disable'
    title: Disable Module
    language:
  - code_block: '!idlechecker status'
    title: Check Module Status
    language:
right_code_blocks:
  - code_block: '!idlechecker enable'
    title: Enable Module
    language:
  - code_block: '!idlechecker disable'
    title: Disable Module
    language:
  - code_block: '!idlechecker status'
    title: Check Module Status
    language:
---