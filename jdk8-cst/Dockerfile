FROM ibmjava:8-jre-alpine

# Install base packages
RUN apk update && apk add tzdata \
    && cp -r -f /usr/share/zoneinfo/Asia/Shanghai /etc/localtime \
    && echo "Asia/Shanghai" > /etc/timezone

# Define sh as default command
CMD ["sh"]