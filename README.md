# Openflow Local Demo – Oracle + NiFi + Snowflake Bundle

## Setup
1) `.env` mit ORACLE_PASSWORD=*** / NIFI_USER=*** & NIFI_PASS=***
2) **Snowflake NARs** in `./nifi-extensions/` legen  
3) **JDBC JARs** in `./nifi-lib/` legen (snowflake-jdbc.jar, optional ojdbc11.jar)
4) Public & Private key erzeugen und lokal im repo ablegen
5) Starten:
   ```bash
   docker compose up -d
