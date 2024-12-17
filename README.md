
v1.0.0
latest -> v1.0.0
read app1/latest/tickets-uat.json abc123
write app1/latest/tickets-uat-status.json


v1.1.0
backup latest to v1.0.0
latest -> v1.1.0
read app1/latest/tickets-uat.json abc124
write app1/latest/tickets-uat-status.json


v1.2.0
backup latest to v1.1.0
latest -> v1.2.0
read app1/latest/tickets-uat.json abc125
write app1/latest/tickets-uat-status.json

---
<AppCode>/<version>/tickets-<env>.json

read app1/latest/tickets-uat.json abc123,abc124,abc125
write app1/latest/tickets-uat-status.json