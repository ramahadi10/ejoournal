# Electronic Journal Application / EJournal
Electronic Journal Application

Full commit history at
www.github.com/farismfirdaus/ci-ej.git

Developed in
Oct 2020 - Dec 2020

# Filter EJ Logic
1. File will be uploaded to ./assets/upload/{ username }/
2. Reading limiter {{ datetime }} in Import.php (Controller)
3. Redirecting to Filter.php (Controller) or Filter_old.php (Controller), based on which type they got uploaded
4. Getting data from CRO App with API
5. Reading the entire transaction and filter based on their limiter.

# Developer Notes!
1. This program using a lot of CDN script, make sure internet is connected before using the app
2. This program won't filter the data, if the API isn't working. which means the API should be contain status whether is false or true, but cannot be error in any type
3. If the moment you were filtering data is pretty slow, probably its the hardware limitation. By the time its released, the filter EJ logic has already revised to make sure the app working as quick as possible

# User Manual
User Manual is located at assets/User Manual/User Manual EJ App.pdf



Beta Version.
released soon
