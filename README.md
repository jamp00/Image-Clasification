The permission part in .yaml file doesn't work right, is necessary give permissions manually
Go to AWS console -> Api Getaway -> Image-classification-multilabel-RestApi -> Resources -> Post -> Integration Request -> Image-classification-multilabel 
Now Deploy the Api, done


Test the api:
curl --location --request POST 'https://4apfx43bpc.execute-api.us-east-2.amazonaws.com/labels/Five' \
--header 'Content-Type: image/jpeg' \
--data-binary '@/E:/Download/71wZTVgMtpL._AC_SY450_.jpg'