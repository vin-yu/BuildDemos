FROM boxfuse/flyway

COPY ./V1_1__fixbug.sql /flyway/sql/V1_1__fixbug.sql 

COPY ./deploy_v2_job.sh /flyway/deploy_v2_job.sh

RUN chmod +x /flyway/deploy_v2_job.sh

