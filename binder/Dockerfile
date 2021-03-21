FROM gesiscss/binder-serhatcevikel-2dad454-5fbase-7021e4:393eb1a188a13214f05c8c54a07c0f9be503cfcb
LABEL maintainer="serhatcevikel@yahoo.com"

# Make sure the contents of our repo are in ${HOME}
COPY --chown=jovyan:jovyan . ${HOME}

USER ${NB_USER}

RUN \
    rm -r ${HOME}/binder;

# Specify the default command to run
WORKDIR ${HOME}
