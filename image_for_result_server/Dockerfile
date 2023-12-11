FROM python:alpine 
COPY requirements.txt .
RUN pip install -r requirements.txt
COPY . /app
WORKDIR /app
EXPOSE 80
CMD python ./app.py


#1 uygulama pythonla yazıldığı için ilgili imaj alındı 
#2 imaj içi dosyaları requirement. txt ye kopyala 
#3 çinde pip install çalıstır req.txt dosyasında flask sql uygulamalşarını çalıstır 
#4 bu dosyaları app klasörü oluşrue ve kaydet
#5 80 portundan iş yapacak konteyner çalısacak
#6 komut yazıldığında uygulama çalısır 