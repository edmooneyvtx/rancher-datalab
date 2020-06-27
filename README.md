# Oseries (Rancher App)

- Oseries Dev
    Oseries
    DB
- Security

Values to be set:

## Values
vertexinc.initialuserpassword: set in gui
tomcat.username: the tomcat username

// tomcat-bitnami.tgz
helm install my-tomcat-app --set image.repository=USERNAME/java-app --set image.tag=latest --set image.pullPolicy=Always bitnami/tomcat
