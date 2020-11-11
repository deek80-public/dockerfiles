# Install Pipenv and create a non-root user
FROM python:3.8
ENV PYTHONUNBUFFERED=1
RUN groupadd -r app-user \
  && useradd --no-log-init -rmg app-user app-user \
  && pip install pipenv
WORKDIR /opt/app

# Extend this image and do something like:
#COPY Pipfile Pipfile.lock ./
#RUN pipenv install --dev --system --deploy
#USER app-user
#CMD ["echo", "your python command here"]

# TODO: I'm sure there's a way to make this more
# convenient so that this can be used standalone
