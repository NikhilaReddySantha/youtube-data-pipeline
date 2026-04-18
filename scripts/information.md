Bronze bucket name : youtube-pipeline-bronze
Silver bucket name : youtube-pipeline-silver
Gold bucket name : youtube-pipeline-gold 
Scripts bucket : youtube-pipeline-scripts 

SNS ARN - arn:aws:sns:us-east-1:597447060973:youtube-data-pipeline-alerts-dev:178e96aa-7494-4b63-8f39-4aeff2d478ba

Glue bronze database : youtube-data-pipeline-bronze-dev
Glue silver database : youtube-data-pipeline-silver-dev 
Glue gold database : youtube-data-pipeline-gold-dev

--bronze_database youtube-data-pipeline-bronze-dev
--bronze_table raw_statistics
--silver_bucket youtube-pipeline-silver
--silver_database youtube-data-pipeline-silver-dev
--silver_table clean_statistics