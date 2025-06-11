FROM python:3.13.4
RUN pip install gcsfs
RUN pip install pandas
COPY ./visualize.py .
CMD ["python", 'visualize.py']