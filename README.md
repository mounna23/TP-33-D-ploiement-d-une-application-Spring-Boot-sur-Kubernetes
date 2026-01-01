# TP-33-D-ploiement-d-une-application-Spring-Boot-sur-Kubernetes

## Objectifs pédagogiques
- À la fin de ce lab, l’étudiant est capable de :
- Conteneuriser une application Spring Boot avec Docker.
- Créer les manifests Kubernetes de base : Deployment et Service.
- Déployer l’application sur un cluster Kubernetes local (par exemple Minikube).
- Exposer l’API Spring Boot vers l’extérieur du cluster.
- Vérifier le fonctionnement et observer les pods.
  
## Étape 1 – Création d’un petit projet Spring Boot
<img width="2940" height="1838" alt="image" src="https://github.com/user-attachments/assets/94d707cd-3d4c-4c41-9607-d127707f2171" />
- Test : 
<img width="682" height="483" alt="Capture d’écran 2026-01-01 à 11 59 44" src="https://github.com/user-attachments/assets/2fcdbf62-0b53-4eb0-9c75-da7f92fa1346" />

## Étape 2 – Création de l’image Docker
<img width="2940" height="1838" alt="image" src="https://github.com/user-attachments/assets/7512cf88-35b3-4334-a467-8913173b9030" />
<img width="2940" height="1838" alt="image" src="https://github.com/user-attachments/assets/c32d07d1-1a1d-4f05-9edf-875dd7c8f5f0" />
- Test : 
<img width="1364" height="966" alt="image" src="https://github.com/user-attachments/assets/e1bb5b8a-3d4a-48dc-b286-b49ce7b83606" />

## Étape 3 – Préparation de Minikube
<img width="2940" height="1838" alt="image" src="https://github.com/user-attachments/assets/0441f09a-c9db-4188-9da5-858d48c915de" />

## Étape 4 – Création d’un namespace dédié
<img width="2178" height="506" alt="image" src="https://github.com/user-attachments/assets/6f5aa333-7fb8-4b79-8620-fcb823f6dcb1" />

## Étape 5 – Manifest Kubernetes : Deployment

<img width="2940" height="1838" alt="image" src="https://github.com/user-attachments/assets/90594385-51fb-4676-8f5d-030dbfd1c220" />

## Étape 6 – Manifest Kubernetes : Service (NodePort)
<img width="2940" height="1838" alt="image" src="https://github.com/user-attachments/assets/838bebb3-142f-4f31-813f-ff88d08d4118" />

## Étape 7 – Test d’accès à l’API via Kubernetes
<img width="2178" height="448" alt="image" src="https://github.com/user-attachments/assets/747e636f-1578-40e7-a220-e2f2cb6019f6" />

## Étape 8 – Observation et diagnostic
<img width="2940" height="1838" alt="image" src="https://github.com/user-attachments/assets/46bec6f0-ab17-4478-bc7d-8d696a18db79" />

 - Accès inside cluster 
<img width="2662" height="358" alt="image" src="https://github.com/user-attachments/assets/2d6abe16-2a1a-43ca-a6b8-998af2610918" />

## Étape 9 – Variante avec ConfigMap (optionnel)
<img width="2940" height="1838" alt="image" src="https://github.com/user-attachments/assets/fef15261-fef6-4a71-a83e-192ce1da03f6" />

## Étape 10 – Nettoyage du lab
<img width="2940" height="1838" alt="image" src="https://github.com/user-attachments/assets/8ebd27ba-cf04-4469-b3f6-0db5f0bcc3ba" />
