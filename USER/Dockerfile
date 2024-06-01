FROM almalinux:8
RUN adduser naresh
USER naresh
ADD https://raw.githubusercontent.com/daws-76s/notes/master/session-02.txt /tmp/
RUN chown -v naresh /tmp/session-02.txt
CMD ["sleep","100"]