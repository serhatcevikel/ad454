# bash, sql, nosql and hadoop sessions
FROM gesiscss/binder-serhatcevikel-2dad454-5fbase-7021e4:1376d801a3420e418d043c4b45e02c8ba13f98c6
LABEL maintainer="serhatcevikel@yahoo.com"

# Make sure the contents of our repo are in ${HOME}
COPY --chown=jovyan:jovyan . ${HOME}

USER ${NB_USER}

RUN \
    rm -r ${HOME}/binder;

# Specify the default command to run
WORKDIR ${HOME}
