FROM microsoft/mssql-tools

WORKDIR /opt/sql-provisioning-job

# COPY ./restore.sql .
# COPY ./adventureworks-restore.sql .
COPY ./dosomething.sql .
COPY ./dosomething.sh .

RUN chmod +x /opt/sql-provisioning-job/dosomething.sh