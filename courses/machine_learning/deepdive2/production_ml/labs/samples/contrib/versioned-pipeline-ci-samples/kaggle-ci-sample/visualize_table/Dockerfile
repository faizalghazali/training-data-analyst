FROM python:3.8.18
RUN pip install gcsfs
RUN pip install pandas
COPY ./visualize.py .
CMD ["python", 'visualize.py']