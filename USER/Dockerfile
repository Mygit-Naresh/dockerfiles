FROM almalinux:8
RUN adduser naresh
USER naresh
COPY --chown=naresh:naresh  /tmp/session-02.txt
ADD https://raw.githubusercontent.com/daws-76s/notes/master/session-02.txt /tmp/
CMD ["sleep","100"]