//
Task 1: Git Basics
    step 1:  Login to github Account

    step 2: create a GitHub repository 

    step 3 : clone the new repo  in my local  terminal with help this code
             git clone https://github.com/prabhakar-98/vetty.git

    step 4: Then Navigate into the repository directory
            cd vetty

    step 5: Then Create a new branch named practical-test 
            git checkout -b practical-test

    STEP 6 : Create the hello.txt file:

    STEP 7: Add the file to the git:
            git add hello.txt

    STEP 8:Commit the change:
          git commit -m "Add hello.txt"
          
    STEP 8 :Push the changes to the practical-test branch on GitHub
            git push origin practical-test

  
//Task 2: Basic Linux Commands

STEP 1:OPEN the my Bash terminal

STEP 2:Create the VettyTest directory:
       mkdir VettyTest

STEP 3: Navigate into the VettyTest directory
        cd VettyTest

STEP 4:THEN Create and edit the script.sh file using any text editor Vi
       Vi script.sh

STEP 5:Write the following script in the file to print "Welcome to DevOps!" to the terminal:
       echo "Welcome to DevOps!"

STEP 6: To save the this file using these command
        :wq in editer
        
STEP 7:  Change the permissions to make the script executable
        chmod +x script.sh

 STEP 8: Finaly run the script
        ./script.sh




//Task 3: Docker
    STEP 1: Install the docker Software

    STEP 2:Create a file named Dockerfile in My  project directory

    STEP 3:Add the following content to the in my Dockerfile
           FROM nginx:latest
           EXPOSE 80
           CMD ["nginx", "-g", "daemon off;"]

    STEP 4:Build and Run the Docker Image
            docker build -t my-nginx-image 

    STEP 5:Run the Docker container with the following command
           docker run -d -p 80:80 --name my-nginx-container my-nginx-image

   STEP 6:Finaly run localhost server in Browser
           http://localhost:80
    
        
 

"# vetty" 
"# vetty" 
