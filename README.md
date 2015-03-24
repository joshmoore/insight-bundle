Steps to get a single-jar webstart:

 * mvn package -Domero.home=$OMERO_SOURCE
 * mkdir $OMERO_SOURCE/dist/lib/insight
 * cp target/insight-bundle.jar $OMERO_SOURCE/dist/lib/insight/omero.insight.jar
 * Load webstart
