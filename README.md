# GIT assignment
### 1. On the local repository, make branches for:
- Postman
- Jmeter
- Checklists
- Bag reports
- SQL
- Charles
- mobile testing
> git branch Postman
>
> git branch Jmeter
>
> git branch Checklists
>
> git branch Bag_reports
>
> git branch SQL
> 
> git branch Charles
>
> git branch mobile_testing

### 2. Push all branches to an external repository
> git push --all origin
### 3. In the Bag_reports branch, make a text document with the bug report structure
> git checkout Bag_reports
>
> touch Bag_reports_structure.txt
### 4. Push the bug report structure to the external repository
> git add .
>
> git commit -m "Comment"
> git push -u origin Bag_reports
### 5. Merge the Bag Reports branch into Main
> git checkout main
>
> git merge Bag_reports
### 6. Push main to the external repository.
> git push -u origin main
### 7. In the CheckLists branch, outline the checklist structure.
>> git checkout CheckLists
>
> touch CheckLists_structure.txt
>
> vim CheckLists_structure.txt
### 8. Push the structure to an external repository
> git push -u origin CheckLists
### 9. On the external repository, make a Pull Request of the CheckLists branch in main
### 10. Synchronize External and Local branches Main
> git pull 
