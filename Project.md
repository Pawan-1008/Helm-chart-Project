# Helm-chart-Project

🚀 Deploying Applications with Helm Charts on Kubernetes 🚀

Excited to share my recent project to deploying a web application using Helm charts on Kubernetes! 🎉

Here, we created the comics using hashtag#GenerativeAI and make the hashtag#application using hashtag#agile & hashtag#scrum method and deploying it through hashtag#helmcharts in hashtag#kubernetes.

Helm uses a packaging format called charts. A chart is a collection of files that describe a related set of Kubernetes resources. A single chart might be used to deploy something simple, like a memcached pod, or something complex, like a full web app stack with HTTP servers, databases, caches, and so on.

Charts are created as files laid out in a particular directory tree. They can be packaged into versioned archives to be deployed.


We used KillerKoda lab for some security concerns.


![image](https://github.com/user-attachments/assets/54177ed6-ef04-4990-b689-dd7329e86324)



![image](https://github.com/user-attachments/assets/627546d9-63b6-4ac8-b9b3-fcdbf1369ab6)

Cloning the Github-Repo from Orginal Source.



![image](https://github.com/user-attachments/assets/1fba6d5b-f6c3-4c7f-88a7-785d4515033f)

Creating Dockerfile with comic-file.


![image](https://github.com/user-attachments/assets/ab90e0e6-91a3-4982-9540-cad30c563405)

Building Image from Dockerfile comic-file.


![image](https://github.com/user-attachments/assets/79be5a72-f965-4d75-aa24-60c3b7530a06)
![image](https://github.com/user-attachments/assets/54927a25-4ca2-4e63-9b14-13b55e09d135)

Verifying the Docker images and running the test container from it.


![image](https://github.com/user-attachments/assets/346a9add-4f88-43fe-a04f-e50dd16e46ed)

Test output.



![image](https://github.com/user-attachments/assets/8e1b6e21-77a2-404e-bc0e-d0a1ca968b2b)

Docker Login and tag and push the image to the docker hub.



![image](https://github.com/user-attachments/assets/7add7312-fa6b-43da-a7b5-0ee5d545250d)

verifying the repo.



![image](https://github.com/user-attachments/assets/3af3cc2d-e57e-45b0-9cbb-c1074809b195)

pulling docker image from repository.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

creating a helm chart with the help
of following command

helm create NAME [flags]


![image](https://github.com/user-attachments/assets/d33b424e-d80e-45e5-8804-1a86fd5c683f)

Defining the values in the values.yaml in the chart directory



![image](https://github.com/user-attachments/assets/540d9f60-bbad-4cee-bd5c-9a2662686ea7)

updating the values in charts/values.yaml, templates/deployments.yaml and templates/service.yaml



![image](https://github.com/user-attachments/assets/a19c0a74-c9a2-4426-9666-f428249a12ca)

package a chart directory into a chart archive


![image](https://github.com/user-attachments/assets/7de45fe2-9817-43d8-8384-1f44471c0a93)

reverifying the values in charts/values.yaml templates/deployments.yaml and templates/service.yaml


![image](https://github.com/user-attachments/assets/34261a0b-49d9-4a4e-bb6d-1c0acb16a052)

This command installs a chart archive.



![image](https://github.com/user-attachments/assets/e842721f-51d8-4cef-8419-43126c0b3f18)

getting the deployments, pods and services that were created using helm-chart.



![image](https://github.com/user-attachments/assets/cd54d4e6-f000-4c93-aceb-8b09c817379c)

Accessing the NodePort using http://IP_Address:NodePort



![image](https://github.com/user-attachments/assets/ea5aed00-4804-447a-9a47-e1d0a4a60fdd)

comic page.
