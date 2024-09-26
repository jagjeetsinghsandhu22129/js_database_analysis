# database_analysis
open telemetry collector for postgresql with db, prometheus and pgadmin

TLDR;

```bash
pip install -r requirements.txt
ansible-playbook playbook.yml
```

If you change a .yaml file you can re-run the playbook that recreates the services.

There is also a kubernetes version that I am struggling to actually observe metrics from:

```bash
ansible-playbook playbook_k8.yml
```

Pgadmin is available on port 8888 via the pgadmin service login user-name@domain-name.com/example. The first time in pgadmin you will need to add the server postgres with username postgres/example Prometheus is available on port 9090 via the prometheus service.


