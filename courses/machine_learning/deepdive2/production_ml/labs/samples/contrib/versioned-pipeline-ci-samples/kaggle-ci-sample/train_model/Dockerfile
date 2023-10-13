FROM python:3.8.18
COPY ./train.py .
RUN pip install pandas==0.25.1
RUN pip install gcsfs numpy matplotlib seaborn sklearn
CMD ["python", "train.py"]