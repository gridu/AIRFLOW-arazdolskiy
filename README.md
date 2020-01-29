

 The repo contains test airflow dags and plugin. Plus I have also added my docker compose yaml file and airflow configuration file just ot be saved here.

  To run

  0. create dags_working, tmp, logs, dags_working sub-folders in the current directory;
  1. copy dags into dags' folder;
  2. copy postgres plugin into plugin/ folder;
  3. start containers in the appropriate order;
  4. in the UI console set the following variables:
     - ex_file	/usr/local/airflow/tmp/ex.txt
     - output_path	/usr/local/airflow/tmp
     - run_file	/usr/local/airflow/tmp/run.trg
  5. in the Connection UI section for postgres connection id: postgres_default
     set login and password to be airflow

  6. create a run file run.trg in the /usr/local/airflow/tmp foilder;
 
