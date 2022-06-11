FROM tensorflow/tensorflow:2.2.2-py3
RUN pip install gcsfs pandas matplotlib seaborn
COPY ./visualize.py .
CMD ["python", 'visualize.py']