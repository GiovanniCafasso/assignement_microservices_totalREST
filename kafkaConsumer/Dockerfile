# PYTHONUNBUFFERED -->
# python output or pipe output is sent to the terminal
# print output in real time

FROM python:3
ENV PYTHONUNBUFFERED=1
WORKDIR /usr/src/app
COPY ./requirements.txt ./
COPY ./ ./
RUN pip install -r requirements.txt
ENTRYPOINT [ "python3" , "notification.py"]