---
cover: >-
  https://images.unsplash.com/photo-1511497584788-876760111969?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=3432&q=80
coverY: 0
---

# primary

| key      | type   | description                                          |
| -------- | ------ | ---------------------------------------------------- |
| id       | string | nanoid generated 10-character unique ID              |
| objType  | string | type of object from pre-defined list                 |
| name     | string | name of object, does not need to be unique           |
| ipfsHash | string | does not include "ipfs/" or "ipfs://"; just the hash |
| parent   | string | comma seperated list of IDs                          |
| children | string | comma seperated list of IDs                          |
