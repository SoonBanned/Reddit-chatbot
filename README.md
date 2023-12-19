# Reddit chatbot


Ce projet a pour but final d'être un chatbot utilisant la technique GPT et ayant été entrainé sur les message reddit r/france depuis 2015.


Il y a 4 partie dans ce projet :


Reddit Scraper (fait):

Après de nombreuses mésaventure à cause de PRAW j'ai finalement trouvé une solution pour récupérer plus de 100 post à la fois. J'ai donc utiliser PMAW pour récupérer tout les post du r/france depuis 2015 ainsi que leurs commentaires grâce à PRAW pour conserver le lien (auteur, répondant). J'ai du (après coups) retirer tout ce qui n'étais pas une lettre ou un chiffre des textes car j'ai eu quelques erreur d'insertion dans la base de données.
 

Posts-Comments DB (a-uploader):

La base de données a été fait sous mySql et contient 4 tables Post, Post_norm, Comments, Comments_norm, les versions norm sont "normalisés" car la filtration des caractères problématiques a été faite à la moitié du scraping.


Learning script (TODO)


ChatBot (TODO)
MIS EN PAUSE A CAUSE DE PROBLEMES MATERIELS
