 java -jar openapi-generator-cli.jar generate \
 -i modules/openapi-generator/src/test/resources/3_0/petstore.json -g perl \
 --git-user-id "wing328" \
 --git-repo-id "petstore-perl" \
 --release-note "GitHub integration demo" \
 -o /var/tmp/perl/petstore
