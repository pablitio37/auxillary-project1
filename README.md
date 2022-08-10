# auxillary-project1

## AUX PROJECT 1: SHELL SCRIPTING

In this project, you need to onboard 20 new Linux users onto a server. Create a shell script that reads a csv file that contains the first name of the users to be onboarded.

![Capture 2](https://user-images.githubusercontent.com/108102087/183995902-70528933-bf72-4da4-8f6f-0659a2292dcf.PNG)

## The Public key id_rsa.pub

![Capture3](https://user-images.githubusercontent.com/108102087/183996057-3a8afec1-65fd-48f7-a9f7-69d2e873c32e.PNG)

## The Private key id_rsa

![Capture4](https://user-images.githubusercontent.com/108102087/183996434-3faa0664-3a7e-4266-ace6-a3bc1e4ed1bb.PNG)

The script you created should read the CSV file, create each user on the server, and add to an existing group called developers (You will need to manually create this group ahead).

Ensure that your script will first check for the existence of the user on the system, before it will attempt to create that it.

Ensure that the user that is being created also has a default home folder

Ensure that each user has a .ssh folder within its HOME folder. If it does not exist, then create it.

For each user’s SSH configuration, create an authorized_keys file and add ensxure it has the public key of your current user.

![Capture5](https://user-images.githubusercontent.com/108102087/183996785-49b01417-095f-48e7-b8a3-0bbe479b9890.PNG)

Test a few of the users randomly, and ensure that you are able to connect to the server using the private key and the public key.

![Capture6](https://user-images.githubusercontent.com/108102087/183997464-7065dbef-15a1-49d0-8b12-2731770e4b2d.PNG)
