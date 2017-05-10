[![StackRoute Online Learning System](http://stackroute.in/images/logo.jpg)](https://learn-dev.stackroute.in)
# The Demo - Story and Steps
#### Following are the steps for running the demonstration.
> Accessing the Assignment
  1. Navigate to **learn-dev.stackroute.in**
  2. Sign in as *cadetRaghu / cadet123* 
  3. Select ***Full Stack MEA/RN Developer*** course and select ****Course Schedule****.
  4. Check the *Week 4* > *Assignment - Data Munging & Data Visualization* > **Chicago Crime Data**
![Assignment Page](https://lh5.googleusercontent.com/jQiwN0RRir8W_SwBXseokbmUw7SX9mYAUwkaeYsco7sgujx0622XRqKhN06rHOLxbIfnTN3lFqCX7Oc=w2560-h1452-rw)
![Assignment Page](https://lh3.googleusercontent.com/GX6YtvAazu37MlJ4_zZ94yd4xiaJUg8P-6eZAhoCdcBO9Z4xzLUlrb2sCNjkyBMinIHWwHVFcEB97KM=w2560-h1452-rw)
  5. Participant reads through the problem statement and then navigate to the following url:
  https://tree.taiga.io/project/projectstackroute-javascript-data-munging-assignment/taskboard/data-munge
 to look at detailed user stories.
 ![Taiga Stories](https://lh6.googleusercontent.com/BMeTpam7hp4UP6kiVJtZPhz7BQbO0PruuL25j-ddbXGozSEBmJbXfCAiBnLensAmvPnUmID3XAUXx9k=w2560-h1452-rw)
 > Start Working on the Assignment
 6. The page also contains the Seed Code repo URL. However, the participant opens up the cloud dev environment using the ***+*****(Plus)** > **Write a Program** link given at the bottom right.
 7. The participant can now see the Cloud Dev Environment workspace. The SEED repo automatically gets cloned into the Workspace for him/her to start working on the assignment.
![Cloud Based Dev Environment](https://lh6.googleusercontent.com/5hPxl1nZWj-qF1YJcq1-fn_g1zeJufFhDGVqpaqKTgVX62mHQ6TSaOjeISDKrsKSRZ6Z4CgGBGwyePc=w2560-h1452-rw)
 8. The participant can start coding the Step 1 of the assignment and keep pushing the code in thier gitlab - however for that they would need to first create a empty repository in the gitlab and do some initializations in the dev environment project folder. Navigate inside the project folder by ```cd myJSAssignment``` and the execute the following: 
 ```sh
 rm -rf .git/
 ``` 
 then 
 ```sh 
 git init
 ``` 
 and then add the remote origin of the git repository i.e. 
 ```sh 
 git remote add origin https://gitlab-dev.stackroute.in/cadetraghu/myjsassignment.git
 ```
 9. Participants to do a initial commit and provide git initial configurations to the environment and to verify whether the git is initialized with thier repository - they need to do a
 ```sh
 $ git add .
 ````
 ```sh
 $ git global --user.email "cadetraghu@gmail.com"
 $ git global --user.name "cadetraghu"
 ```
 then do 
 ```sh
 git commit -m "First base repo commit"
 ```
 then finally 
 ```sh
 git push origin master
 ```
 10. Particpants to fetch the data from the data source url - and untar the dataset to start working with the dataset - crimes
 ```tar -xcf ...  ```
 11. Participants to write the code and submit the code back to thier git repository. 
 > Submitting for Evaluation
 12. When they are ready for submission, the need to Open the Automated Evaluation System - Hobbes by navigating to the following URL:
 internal.stackroute.in
 13. Click the Login icon and provide ***cadetraghu / cadet123*** as the credentials. The following page will open:
![Hobbes](https://lh5.googleusercontent.com/quDbDb3dbRbhi3h0mPRzZjTs7cs8ANJ99nILmTgp_4l39mjPzt1NjlFRRjfcJaX67dRgyNrOuChjV8s=w1540-h1324-rw)
 14. Participants to provide the Assignment name - type ```Chicago..``` the drop down for assignment will be visible.
 15. Participants to provide thier completed assignment repository for evaluation - select from the list of repositories being shown in the drop down.
 16. Select the icon on the the top right and select ***Feedback***
 17. Participants can see the status of thier submission - it may take a while to bring the evaluation results.
