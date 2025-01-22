FROM python:3.14.0a4
RUN pip install gcsfs
RUN pip install pandas
COPY ./visualize.py .
CMD ["python", 'visualize.py']