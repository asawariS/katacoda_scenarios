Deploy the Guestbook application by running the *kubectl apply -f /root/course/guestbook.yaml* command:

`kubectl apply -f /root/course/guestbook.yaml`{{execute}}

Check to see if the pods are running:

`kubectl get pods`{{execute}}

If the pods are not all running, then wait a minute and run the *kubectl get pods* command again.

Once the pods are all running, switch to the Guestbook tab and enter some messages into the Guestbook.
