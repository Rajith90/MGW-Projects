# Auto Generated Dockerfile

FROM wso2/wso2micro-gw:3.0.1
LABEL maintainer="dev@ballerina.io"

COPY bookstore.balx /home/ballerina 

EXPOSE  9090 9095 9096
CMD ballerina run --config ${CONFIG_FILE} bookstore.balx
