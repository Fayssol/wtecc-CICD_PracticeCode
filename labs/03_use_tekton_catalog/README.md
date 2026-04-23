# Use Tekton CD Catalog

This folder holds the files for the lab: _Use Tekton CD Catalog_ which is part of the **IBM-CD0215EN-Skills Network Introduction to CI/CD** course.
## installer la tache git-clone de tekton

kubectl apply -f https://github.com/tektoncd/catalog/raw/main/task/git-clone/0.10/git-clone.yaml

ou

kubectl apply -f https://raw.githubusercontent.com/tektoncd/catalog/main/task/git-clone/0.9/git-clone.yaml

## verifiera

kubectl get task git-clone
