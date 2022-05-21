FROM python:3.9-slim

COPY . /app/

RUN echo "Cookies and cheesecakes are my favorites" > favorites_cakes.txt

RUN pip install sklearn
RUN pip install pandas
RUN pip install numpy

CMD python /app/app.py