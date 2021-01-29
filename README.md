# TensorSecurity Harbor-Scanner
## Features
Support Chinese display    
Support CVE、CNVD、CNNVD、CVSS   
 
## Deploy
```
git clone https://github.com/tensorsecurity/harbor-scanner.git
cd harbor-scanner/
kubectl create namespace harbor-scanner
kubectl create -f deploy/ -n harbor-scanner

Login to Harbor to add scanner. address: http://tensorsec-scanner service IP:8080/harbor
```
