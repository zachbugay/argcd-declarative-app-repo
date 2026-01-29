# Argo CD Bootstrap (App of Apps)

This repository bootstraps Argo CD applications using the App of Apps pattern.

## Bootstrap

kubectl apply -f apps/root-app.yaml

## Layout

- apps/root-app.yaml: Parent Argo CD Application that points at ./apps
- apps/guestbook/application.yaml: Child Argo CD Application deploying guestbook
