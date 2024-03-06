FROM alpine:3.18
COPY entrypoint.sh /entrypoint.sh
COPY cleanup.sh /cleanup.sh
# Grant execute permissions to the scripts
RUN chmod +x /entrypoint.sh /cleanup.sh
ENTRYPOINT ["entrypoint.sh"]
CMD ["World"]