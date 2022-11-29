FROM python:3.8
LABEL maintainer="Danni Zhang"

COPY ./techtrends /app
WORKDIR /app
RUN pip install -r requirements.txt
RUN python3 init_db.py
# command to run on container start
CMD [ "python3", "app.py" ]
#push test 1
