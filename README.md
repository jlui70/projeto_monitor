# Projeto de Monitoramento e Observabilidade com Docker Compose

Este projeto configura rapidamente um ambiente completo de **monitoramento e observabilidade** utilizando containers Docker. São incluídos os seguintes serviços:

- **MySQL Server** (backend para o Zabbix)
- **Zabbix Server + Frontend**
- **Prometheus**
- **Grafana**

## 🚀 Como Usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/jlui70/monitoring-docker.git
   cd monitoring-docker

Suba os containers:

bash
Copiar
Editar
docker compose up -d

Acesse as interfaces web:

Zabbix: http://localhost:8080

Grafana: http://localhost:3000

Prometheus: http://localhost:9090

⚠️ Certifique-se de que essas portas estão livres na sua máquina.


📦 Requisitos

- Docker

- Docker Compose

📄 Licença

Este projeto está sob a licença MIT.