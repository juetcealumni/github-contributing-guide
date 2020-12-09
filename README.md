# How to start contributing in github ?

Please follow the steps for any kind of open source contributions


- **One time steps**:
1. Fork the repository. 
2. Clone the forked repository.

      `git clone https://github.com/your_user_name/repo_name.git`
    
3. Create a new branch for tracking your progress. Let's name this *your_user_name*

      `git checkout -b your_user_name`
      
4. Add remote

      `git remote add your_user_name https://github.com/your_user_name/repo_name.git`
  
- **Marking tasks as completed and pushing to your branch**:

      git add .
      git commit -m "Completed tasks x and y"
      git rebase your_user_name/master
      git push --force
    
- **Keeping your fork's list updated with the changes made here**:

      git remote add upstream https://github.com/sahilbansal17/repo_name.git
      git checkout master
      git pull upstream master
      git push your_user_name master

Refer to [this](https://github.com/susam/gitpr/blob/master/README.md) for understanding more about Fork and PR workflow.
