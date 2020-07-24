FROM boinc/server_makeproject:4.0.1-b2d
 	
COPY --chown=1000 project_description.php $PROJECT_ROOT/html/project
COPY --chown=1000 water.jpg $PROJECT_ROOT/html/user/img
COPY --chown=1000 apps/ $PROJECT_ROOT/apps
COPY --chown=1000 project.xml $PROJECT_ROOT/
COPY --chown=1000 templates/ $PROJECT_ROOT/templates
COPY --chown=1000 input $PROJECT_ROOT/
