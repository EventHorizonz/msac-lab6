# Exercise 7 - More than one changed file

1. Ensure you have a clean working directory

        git status

2. Edit one of your `fruits.txt`, add a few items

        blueberry
        strawberry
        etc.

3. Edit `appliances.txt` and add a few items

        dishwasher
        dryer
        etc.

4. Look at git status, paste the output here

        git status

5. Can you commit both of the changed files in a single commit?

        Yes, by using "git add appliances.txt fruits.txt" and "commit appliances.txt fruits.txt -m "...""

6. After you do so, check that you have a clean working directory by running `git status`, and pasting the output here

        On branch master
        nothing to commit, working tree clean

7. Create a new file `equipment/furniture.txt`. Add content to both `vegetables.txt` and `furniture.txt`

8. How can you commit just one of the changed files?

        git add file.txt and commit file.txt -m "..."

9. Check your `git status`

10. What does red text mean in the output of `git status`?

        These files arent added to staging area

11. What does green text mean in the output of `git status`?

        this indicated that the highlighted files have been staged and ready to be commited

12. How can you make a single file show in both red and green in the output of `git status`?

        only a sinlge file can be either red or gren, never both. if there are 2 files and one is tracked, only the tracked one will appear green when git status is redone.

