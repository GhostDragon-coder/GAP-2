1. Внутри Grafana созданы папки с названиями infra и app;

2. Внутри директории infra создан дашборд, который отображает сводную информацию по инфраструктуре (CPU, RAM, Network, etc.) "Node Exporter Full"; 

3. Внутри директории app создан дашборд, который отображает сводную информацию о CMS (доступность компонентов, время ответа, etc.) "Blackbox Exporter";

4. При помощи Grafana создан alert о недоступности одного из компонентов CMS и инфраструктуры (его настройки на скрине);
