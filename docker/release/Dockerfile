FROM dpaws/microtrader-base
MAINTAINER Justin Menga <justin.menga@gmail.com>
LABEL application=trader-dashboard

# Copy application artefacts
ARG app_version
LABEL application.version=${app_version}
COPY target/trader-dashboard-${app_version}-fat.jar /app/app.jar
