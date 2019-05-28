# The first instruction in a Dockerfile must be FROM, which selects a base image. We are using the image I published from a previous post about containerising the Mule ESB. Change this line to your own repository if you have created your own image.
FROM mikeyryan/mule:4.2.0-ce

COPY ./target/mule-4-hello-world*.jar /opt/mule/apps/

RUN ls -la /opt
RUN ls -la /opt/mule


CMD ["/opt/mule/bin/mule"]
