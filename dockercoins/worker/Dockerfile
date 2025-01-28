FROM python:alpine
RUN pip install redis
RUN pip install requests
COPY worker.py /
STOPSIGNAL SIGTERM
CMD ["python", "worker.py"]
