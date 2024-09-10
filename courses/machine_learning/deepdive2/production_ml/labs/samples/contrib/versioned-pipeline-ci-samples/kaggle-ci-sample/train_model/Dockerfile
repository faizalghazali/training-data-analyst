FROM python:3.12.5
COPY ./train.py .
RUN pip install pandas==0.25.1
RUN pip install gcsfs numpy matplotlib seaborn sklearn
CMD ["python", "train.py"]