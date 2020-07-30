FROM boinc/server_makeproject:4.0.1-b2d
 	
COPY --chown=1000 html/ $PROJECT_ROOT/html
COPY --chown=1000 apps/ $PROJECT_ROOT/apps
COPY --chown=1000 templates/ $PROJECT_ROOT/templates
COPY --chown=1000 project.xml input $PROJECT_ROOT/
