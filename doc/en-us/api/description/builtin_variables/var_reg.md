---
api: true
key: var_reg
name: $(reg)
version: 2.1.5
refer: winos.registry_query
---

### ${anchor var_reg}

#### Get the value of the windows registry configuration item

Get the value of an item in the registry by `regpath; name`:

```lua
${link print}("${link var_reg $(reg HKEY_LOCAL_MACHINE\\SOFTWARE\\Microsoft\\Windows NT\\CurrentVersion\\XXXX;Name)}")
```

