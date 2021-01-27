---
title: Manifest Schemas
description: 
published: true
tags: 
---

## schema 1

Schema 1 is used for deviapps and devipkg libraries.

Example:

```json
{
    "schema": 1,
    "id": "globally-unique-id",
    "version": "1.0.1",
    "permissions": {
        "client": {
            "networking": true,
            "interface": true,
            "construct": true,
            "tween": true
        },
        "server": {
            "networking": true
        }
    },
    "dependencies": {
        "client": {
            "ui-library": "0.0.1"
        },
        "server": {
            "ui-library": "0.0.1"
        }
    }
}
```