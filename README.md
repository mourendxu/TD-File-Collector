# TD-File-Collector
A simple component for collecting and move/copy all referenced files to the project directory.


It's essentially bunch of Python scripts that recursively traverses all of the objects at the same level or below, looking for any File type parameters. Once the copying/moving has been done, all file references will be modified to point to the consolidated location.


It's best to put it at the project level, so, it can see all of the objects. 


All controls are in the Property panel's custom param page. It should be pretty straightforward.

