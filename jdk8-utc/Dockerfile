FROM ibmjava:8-jre-alpine

# Install base packages
RUN apk update && apk add tzdata \
    && cp -r -f /usr/share/zoneinfo/UTC /etc/localtime \
    && echo "UTC" > /etc/timezone

# Define sh as default command
CMD ["sh"]