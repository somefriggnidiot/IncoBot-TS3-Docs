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
  - code_block: "# ==============================================\r\n# ====           META INFORMATION           ====\r\n# ==============================================\r\n# = Information used to identify this bot      =\r\n# =   instance.                                =\r\n# ==============================================\r\n\r\ninstance-name: 'testInstance'\r\n\r\n# ==============================================\r\n# ====        CONNECTION INFORMATION        ====\r\n# ==============================================\r\n# = Information used to initiate the           =\r\n# =   connection to the server.                =\r\n# ==============================================\r\n\r\nserver-address: 'localhost'\r\nserver-query-port: 10011\r\nvirtual-server-id: 1\r\n\r\nserver-query-name: 'serveradmin'\r\nserver-query-password: 'ultrasecretpass'\r\n\r\nbot-nickname: 'Oh Bot Johnson'\r\nbot-slow-mode: ''"
    title: ConnectionConfig
    language:
  - code_block: "# ==============================================\r\n# ====        Idle Mover Information        ====\r\n# ==============================================\r\n# = Determines when and where to move idle     =\r\n# =   users within the server.                 =\r\n# ==============================================\r\n\r\nidle-max-time-minutes: 45\r\nidle-destination-channel: 105093\r\nidle-ignore-groups:\r\n - 38113\r\n - 38114"
    title: IdleChecker
    language:
  - code_block: "# ==============================================\r\n# ====             Instructions             ====\r\n# ==============================================\r\n# = Add groups by their ID number. Each group  =\r\n# = should be on a new line, prefixed with     =\r\n# = a hyphen (-).                              =\r\n# ==============================================\r\n\r\n# This group has access to all functions, and\r\n#   cannot be removed from its role except by\r\n#   removing them directly from the config file.\r\nowner-groups:\r\n- 6\r\n\r\n# This group has access to all function, and\r\n#   can modify the roles of all non-owner users.\r\nsuper-admin-groups:\r\n\r\n# This group has access to all functionality\r\n#   except for that involved in role and config\r\n#   management.\r\nadmin-groups:\r\n - 12\r\n\r\n# This group has access to limited versions of\r\n#   disciplinary functionality.\r\nmoderator-groups:\r\n - 15\r\n - 17\r\n - 18\r\n\r\n# This group has access only to non-functional\r\n#   (cosmetic) commands.\r\nsponsor-groups:\r\n - 16\r\n\r\n# This group cannot access any functionality of\r\n#   this program.\r\nblacklisted-groups:\r\n- 8\r\n- 10\r\n- 11"
    title: ServerGroupAccess
    language:
---