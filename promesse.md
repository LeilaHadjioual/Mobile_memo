 
 **Notion de promesse :**

 -> gérer du code asynchrone en Javascript 
 
 https://frank.taillandier.me/2017/03/23/comprendre-les-promesses-en-javascript/

 

 .then()   
 
     retourne toujours une promesse

 Promise.all()   

    La promesse est tenue quand chacun des éléments (les promesses) sont tenues (une fois que tout est fait, il retourne la promesse)

Promise.race()   

    ressemble à Promise.all(). Mais elle est tenue ou rejetée dès que l’une d’entre elles est tenue ou rejetée
