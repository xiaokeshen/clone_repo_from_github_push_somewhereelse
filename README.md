# clone_repo_from_github_push_somewhereelse


This tell us one method how to  clone the repo from git hub and push it to bitbucket as bitbucket has the free private choice.



#  Step 1
clone something from github


#  Step 2
create a new repos on bitbucket with a specified name   

#  step 3
copy the http link from the clone section of the new created repos from the bitbucket


#   step 4
go to the local folder of the repos cloned from the github, input those commands:  


 git init  
 git remote set-url origin https://xiaoke_shen@bitbucket.org/xiaoke_shen/faster-rcnn_tf.git
 git remote add personal https://xiaoke_shen@bitbucket.org/xiaoke_shen/faster-rcnn_tf.git    
 git add --all    
 git commit    
 git push origin master    
 
