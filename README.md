Ansible execution environment image
==============================

Files to build Docker image with pre-configured interactive Ansible 
execution environment (based on Debian Linux). 

Build
---

```
./build.sh
```

Run
---

```
docker run -t \
  --name ansible \
  anmcarrow/ansible
```

Author
---
Andrey Makarov

Licence
---
MIT
