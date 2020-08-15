FROM rocker:binder/latest
LABEL maintainer='Matt Dray'
USER root
COPY . ${HOME}
RUN chown -R ${NB_USER} ${HOME}
USER ${NB_USER}

RUN installGithub.r matt-dray/r2eng

RUN wget https://github.com/matt-dray/try-r2eng/raw/master/DESCRIPTION && R -e "options(repos = list(CRAN = 'http://mran.revolutionanalytics.com/snapshot/2020-08-15/')); devtools::install_deps()"

RUN rm DESCRIPTION.1; exit 0
