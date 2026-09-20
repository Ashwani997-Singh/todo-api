# todo-api
Practice repo for DevSecOps lab - .NET API



## Branching strategy

- `main` : hamesha deployable, protected branch, direct push band hai
- `feature/<naam>` : naya feature ya change
- `bugfix/<naam>` : bug fix
- `hotfix/<naam>` : production emergency fix

Har change pull request se merge hoga. Minimum 1 approval zaroori hai,
aur saare comments resolve hone chahiye.

## Repository standards

- Secrets kabhi code me nahi. Environment variables ya secret store use karein.
- `.gitignore` follow karein, build output commit na karein.
- PR template ki checklist poori bharein.
- Har PR me review comments resolve karna zaroori hai.
