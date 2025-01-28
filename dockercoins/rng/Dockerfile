FROM python:alpine
RUN pip install Flask
COPY rng.py /
STOPSIGNAL SIGTERM
CMD ["python", "rng.py"]
EXPOSE 80
