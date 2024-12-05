Latest Logs From Latest Build
==============================

Generated On: 2024-12-05 17:49:56 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/Greon101/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-12-05_17:42:51] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-12-05_17:43:02] STEP 2: Create topics started

  [INFO 2024-12-05_17:43:55] STEP 2: Completed

  [INFO 2024-12-05_17:44:15] STEP 3: producing data started

  [ERROR 2024-12-05_17:44:23] Cannot connect to MQTT broker in tml_read_MQTT_step_3_kafka_producetotopic_dag-greonproject-4ce8.py - invalid literal for int() with base 10: ''

  [INFO 2024-12-05_17:44:28] STEP 4: Preprocessing started

  [INFO 2024-12-05_17:44:35] STEP 4: Preprocessing started

  [INFO 2024-12-05_17:44:40] STEP 7: Visualization started

  [INFO 2024-12-05_17:44:47] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-12-05_17:45:17] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2024-12-05_17:45:22] STEP 9: Starting privateGPT

  [INFO 2024-12-05_17:45:33] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --gpus all -v /var/run/docker.sock:/var/run/docker.sock:z --env PORT=8001 --env TSS=1 --env GPU=1 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-with-gpu-nvidia-amd64

  [INFO 2024-12-05_17:45:37] STEP 8: Starting docker push for: greon101/greonproject-4ce8-amd64

  [INFO 2024-12-05_17:46:26] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit 3723ead1b40a greon101/greonproject-4ce8-amd64 - message=0

  [INFO 2024-12-05_17:49:29] STEP 8: Successfully ran Docker push: docker push greon101/greonproject-4ce8-amd64 - message=0

  [INFO 2024-12-05_17:49:55] STEP 10: Started to build the documentation

  [INFO 2024-12-05_17:49:56] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


