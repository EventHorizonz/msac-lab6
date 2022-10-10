# Exercise 10 - Understanding Commits

1. Look at your commit log

        git log --oneline

2. Choose a commit hash

6d4c373

3. See what type of object that hash names

        git cat-file -t <hash>
        
        commit

4. Examine the contents of that commit closely

        git cat-file -p <hash>
        
        tree a2da5363215639daa5d0f49edca3b40e3f2ed8f1
        parent 50ad11e6536d27c483e4be9052ce66e0ee622b6b
        author Danny H <dahernandezni@icloud.com> 1665360672 -0700
        committer Danny H <dahernandezni@icloud.com> 1665360672 -0700

5. Find the parent's hash in the commit log

        50ad11e6536d27c483e4be9052ce66e0ee622b6b

6. Look at the contents of the tree

        git cat-file -p <hash>

7. Examine the contents of one of the blobs

8. What type of object does the parent hash represent?

        git cat-file -t <hash>
        
        commit

9. Examine the contents of the parent and its tree

10. Do the trees you looked at have any matching hashes listed?

        the global inputs previously placed.
