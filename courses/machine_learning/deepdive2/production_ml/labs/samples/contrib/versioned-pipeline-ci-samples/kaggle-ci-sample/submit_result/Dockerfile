FROM python:3.11.9
ENV KAGGLE_USERNAME=[YOUR KAGGLE USERNAME] \
    KAGGLE_KEY=[YOUR KAGGLE KEY]
RUN pip install kaggle
RUN pip install gcsfs
COPY ./submit_result.py .
CMD ["python", "submit_result.py"]