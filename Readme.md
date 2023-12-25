kubectl create deployment nginx-app --image=nginx

kubectl create service nodeport nginx-app --tcp=80:80
