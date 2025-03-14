Initiation git
----------------------------
**Préalable.** Création d'un repo distant sur la plateforme GitHub  
  
1 Création d'un dossier sur le PC => pour le momment, un dossier classique  
  
2 On crée le prémier fichier readme.md (qui va être la page d'accueil de notre repo)  
  
3 On va initialiser ce dossier classique, comme un repo local avec la commande
  
'''git init'''  
Cette commandeentraîne la Création d'un dossier d'un sous répertoire  .git, notre dossier "classique" local est devenu un repository au sens git du terme  
  
4 On va *"stogger"* le fichier readme.md  

'''git add readme.md'''  
  
5 On *"commit"* avec l'option message -m (qui va apparaitre dans le repo GitHub)  
  ![](image/message_comit.png)  
  
'''git comit-m "first commit"
  
6 on renomme la branche principale en main (car git en local a créé la branche master, mais GitHub attend main par convention)  
  
  '''git branch -M main'''
7 On crée le liern de notre repo local avec le repo distant  
  
'''git remote add origin https://github.com/Lezcob/exo_git_cpgeom.git'''  
  
8 On *"push"* le repo local vers le distant  
  
'''git push -u origin main'''  
  
**Conclusion**  
  
  Notre repo local est jumelé avec le distant. Vu que je viens de complèter ce fichier readme après le premier comit, je me contredis moi même, je dois donc faire un comit pour être "iso"