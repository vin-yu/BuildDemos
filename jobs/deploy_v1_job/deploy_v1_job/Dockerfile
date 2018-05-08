FROM microsoft/mssql-tools

WORKDIR /opt/sql-provisioning-job

# COPY ./restore.sql .
# COPY ./adventureworks-restore.sql .
COPY ./deployV1.sql .
COPY ./deployV1.sh .

RUN chmod +x /opt/sql-provisioning-job/deployV1.sh