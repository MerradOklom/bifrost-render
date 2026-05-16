FROM maximhq/bifrost:latest

USER root
RUN mkdir -p /app/render-data && chown -R appuser:appuser /app/render-data
COPY render/config.json /app/render-data/config.json
RUN chown appuser:appuser /app/render-data/config.json
USER appuser
