FROM python:3.8.2-alpine
WORKDIR /src
COPY requirements.txt .
COPY HelloAbi.py /src
RUN pip install -r requirements.txt
CMD ["python", "/src/HelloAbi.py"]