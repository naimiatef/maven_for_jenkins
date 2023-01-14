# maven_for_jenkins
## Exercice :
Considérons un cas de Test simple :
   - Accédez au Site de démonstration: https://opensource-demo.orangehrmlive.com/ à travers un parametre "Browser" pour indiquer le types de navigateur(Chrome, Edge) qui lance le site web

## Quelles sont les conditions préalables pour l'exécution de notre projet ? :
- L'installation de Jenkins
- la configuration de jenkins
- l'installations des plugins nécessaire (Configuration de plugin maven dans Jenkin, Git, JDK ...)
- Création d'un projet maven dans Jenkins (New Job)

![image](https://user-images.githubusercontent.com/7100940/212469834-2028b4f5-2e6d-4baf-857a-cfa31e0cb8d6.png)


## Correction  :

## 1- Configuration de notre projet Maven dans Jenkins ? :
- Tout d’abord, donnez le chemin relatif de pom.xml dans la zone de texte POM racine, car nous avons le pom.xml à la racine du projet, nous avons donc directement fourni le nom du fichier.
- Deuxièmement, tapez « clean install » dans la zone de texte Objectifs et options comme « maven clean », « maven install », ainsi que « maven test » sont les commandes maven lors de l’exécution de maven build, mais ici la commande « clean install ».
- Enfin, cliquez sur le bouton Enregistrer.

![image](https://user-images.githubusercontent.com/7100940/212468956-e4684476-4a7e-46e4-9870-50ef74d9fe82.png)

![image](https://user-images.githubusercontent.com/7100940/212468985-93d44ffd-ef17-4c68-ad39-6618da399a74.png)

![image](https://user-images.githubusercontent.com/7100940/212469004-644eae25-48a0-42da-a49c-07713479b922.png)

## 2- Le code sur GitHub ? :
#A- 
![image](https://user-images.githubusercontent.com/7100940/212470142-16adb4ca-61ac-4ffb-b9d4-08b0f80964c9.png)

#B- 
![image](https://user-images.githubusercontent.com/7100940/212470198-cf34386d-1d96-409f-8f02-d7224d84b755.png)

#C- 
![image](https://user-images.githubusercontent.com/7100940/212470266-f1bf880d-db1b-4d51-9318-281e794cde66.png)


## 3- le résultat final aprés l'exécution de notre projet :
![image](https://user-images.githubusercontent.com/7100940/212469091-6ac7910e-fa1b-42ee-b437-1f0683f5b98b.png)
