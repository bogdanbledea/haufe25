# Haufe Summer Practice 2025 | Git Basics

This is the repository for the Git Basics module @ Haufe Summer Practice 2025.

The course support can be found inside `git-basics-at-haufe.pdf`.

Practical exercises proposed:

## PR with no conflict

1. Clone https://github.com/bogdanbledea/haufe25.git

2. Verify that you received collaborator role for this repo

3. Create a branch locally, then create a folder with your chosen name, and a dummy file inside. (should not conflict with other users)

4. Commit the changes.

5. Push the branch to remote repository.

6. Create PR with the changes, and assign the CODEOWNER for review.

7. After PR is approved, merge it(with Rebase strategy).

## PR with conflict

8. Then, modify `file-to-be-conflicted.txt` in another branch(after you pull from main, of course!), with your username that you received, on a new line.

*As a rule of thumb: an odd username(e.g. USER-1) will need to remain on main branch. (e.g. in a conflict, choose USER-1 instead of USER-2). If both are odd, then leave yours.*

9. Commit changes locally. then rebase the branch main into yours. Push the branch to GitHub and then create PR.