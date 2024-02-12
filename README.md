SYSTEM HELP APOIO 

## Instalação de Programas

- **Chatwoot**
- **TYPEBOT**
- **EVOLUTION_API**
- **MINIO**
-


## Dependências

- **Redis**
- **POSTGRES**
- **MONGO-dB**

---
# instalaçao e configuraçao da vps  1PANEL com dominio ssl  ngix

curl -sSL https://raw.githubusercontent.com/jefferson-system-help-oficial/1Panel-brasil-oficial/dev/quick_start.sh -o quick_start.sh && sudo bash quick_start.sh^C
 
 sequecia :: enter 
  porta  99
  user    video 
  senha   0102030405
  letra q



  - Instalação do Docker
   
 
   - Ativação do Docker no modo swarm
    
    docker swarm init




# volumes ! 

docker volume create meu_volume && docker volume create mongodb_configdb_data && docker volume create mongodb_data && docker volume create chatwoot_data && docker volume create redis_data && docker volume create postgres_data && docker volume create evolution_store && docker volume create evolution_instances && docker volume create minio_data && docker volume create npm_letsencrypt && docker volume create npm_data


# redes usada
  ## modo bridge

minha_rede

typebbot_default




# user e senha do ngix 


Email:    admin@example.com
Password: changeme


## Criar Banco de Dados PostgreSQL




psql -U postgres

create database chatwoot;

create database n8n_queue;

### liberar funçoess

psql -U postgres

\c chatwoot;

update installation_configs set locked = false;
\q


# configuraçao do ngix 

 # # serviçes 

 chatwoot_app    : 3000 underscores_in_headers on; 
 
 evolution       : 8080

 minio           : 9000 e 9001 

 app             : 81

 typebot_builder : 3000

 typebot_viewer  : 3001



- **PIX PARA TOMAR UM CAFÉ**
  - CNPJ: 48.590.314/0001-18 
