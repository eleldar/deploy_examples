~~~
docker build -t <username>/online_inference:v1 .
docker run -p 8000:8000 <username>/online_inference:v1
python make_request.py 

~~~
