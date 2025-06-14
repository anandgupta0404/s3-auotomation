sdsdds
# s3-auotomation


c

Helping Commands:
kubectl -n minio get secret minio -o jsonpath="{.data.rootUser}" | base64 --decode
kubectl -n minio get secret minio -o jsonpath="{.data.rootPassword}" | base64 --decode
kubectl create secret generic ack-secret \
  -n s3-operator \
  --from-literal=aws_access_key_id=q2lEvSkyuQ5I7n0veaaP \
  --from-literal=aws_secret_access_key=phdIGtTsVKLwZ9y8juxiHwDD9CpPMW2joUWB0R6X


Other Details:

admin Cred: 
username : 8xc0KrakRcBmIs8Pow3K
password: e7xZgaO7nv9e1gwuBknZqiG9TJyKHXbn4DspCY9O

access key: q2lEvSkyuQ5I7n0veaaP
secret key: phdIGtTsVKLwZ9y8juxiHwDD9CpPMW2joUWB0R6X
region: us-east-1
Endpoint:minio.minio.svc.cluster.local:9000