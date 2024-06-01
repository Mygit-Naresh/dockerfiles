FROM almalinux:8
RUN adduser naresh
USER naresh
ADD https://raw.githubusercontent.com/daws-76s/notes/master/session-02.txt /tmp/
COPY --chown=naresh:naresh --chmod=644 /tmp/session-02.txt
CMD ["sleep","100"]