# 🚀 Proyecto Docker: NGINX + PostgreSQL + Docker Compose

Este proyecto contiene una configuración completa para levantar un entorno con NGINX como servidor web y PostgreSQL como base de datos, utilizando Docker Compose.

---

## 📁 Estructura del Proyecto

\`\`\`
proyecto-docker/
├── contenedor1/
│   └── docker-compose.yml
├── contenedor2/
│   └── docker-compose.yml
├── contenedor3/
│   └── docker-compose.yml
├── web/
│   └── index.html
└── README.md
\`\`\`

---

## 🧱 Tecnologías usadas

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)
- [NGINX](https://www.nginx.com/)
- [PostgreSQL](https://www.postgresql.org/)

---

## ⚙️ Cómo ejecutar el proyecto

1. Clona el repositorio:

\`\`\`bash
git clone git@github.com:AdonyUlloa/dockercompose.git
cd dockercompose
\`\`\`

2. Levanta los servicios:

\`\`\`bash
sudo docker compose up -d
\`\`\`

3. Accede a la web:

\`\`\`
http://localhost
\`\`\`

---

## 🧪 Servicios disponibles

| Servicio   | Puerto Host | Descripción                   |
|------------|-------------|-------------------------------|
| NGINX      | 80          | Servidor web estático         |
| PostgreSQL | 5432        | Base de datos relacional      |

---

## 🌐 Red personalizada

Todos los contenedores están conectados a una red bridge personalizada:

- Subred: \`192.168.19.0/24\`
- Gateway: \`192.168.19.1\`
- IP fija para NGINX: \`192.168.19.10\`

---

## 📄 Licencia

Este proyecto es de uso educativo y libre de compartir.
