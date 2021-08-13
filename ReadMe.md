To start the move_group including the wrong config use the following command:
~~~bash
roslaunch bug_pipeline_config bug_chomp_pipeline.launch
~~~

Afterwards the loaded pipelines can be checked by calling the service on the move group:
~~~bash
rosservice call /query_planner_interface
~~~