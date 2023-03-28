# TP1_-Syst-mes-Distribu-s-
Développer une application client serveur de Chat
1-  Modèle Multi Threads Blocking IO (java.io)
  - Développer un serveur de Multi Thread Blocking IO de ChatServer
![image](https://user-images.githubusercontent.com/116807307/225692567-105ba108-64c9-40c3-a6b9-ba034c0c5cba.png)
  - Tester le serveur avec un client Telnet
  ![2](https://user-images.githubusercontent.com/116807307/225693392-93cf3887-d180-4e6c-a57a-3aa78c7e9f93.PNG)

 - Créer un client Java avec une interface graphique JavaFX
![image](https://user-images.githubusercontent.com/116807307/225693298-4b41f597-1aa4-4ccc-8bd5-66ec8fc5bd6c.png)
_______________________________________________________________________________________________________________________________________________________________________
_______________________________________________________________________________________________________________________________________________________________________
![2fx](https://user-images.githubusercontent.com/116807307/225693437-0f79d655-dc3d-4842-9b19-233ddfaadaf9.PNG)
   - Créer un client Python ou un autre langage quelconque
![image](https://user-images.githubusercontent.com/116807307/225694553-26e7d60c-5b4d-482c-b96a-8447268a32d0.png)
_______________________________________________________________________________________________________________________________________________________________________
_______________________________________________________________________________________________________________________________________________________________________
![py](https://user-images.githubusercontent.com/116807307/225693568-727e5c85-90e3-4107-80a1-e6b1f22f7352.PNG)
2-  Modèle Single Thread avec Non Blocking IO (java.nio)
      - Développer un serveur de Single Thread  utilisant des entrées sorties non bloquantes 
     ![image](https://user-images.githubusercontent.com/116807307/225694813-db8bb1ff-9a75-42ad-8e5b-f3cb646bf6d5.png) 
      - Tester le serveur avec un client Telnet.
     ![nottelet](https://user-images.githubusercontent.com/116807307/225696101-ee35b25c-447d-4078-9480-9632efa35e13.PNG)

      - un client java.
      ![image](https://user-images.githubusercontent.com/116807307/225694994-458025a7-d225-4c49-a008-80af34014521.png)
      ![not_fx](https://user-images.githubusercontent.com/116807307/225695509-076a89d4-efa3-462e-95ad-bfc6e9e38b31.PNG) 
![cnxfx](https://user-images.githubusercontent.com/116807307/225695442-211f534c-7192-4f99-8b68-3dca417baccf.PNG) 
![sendmsfx](https://user-images.githubusercontent.com/116807307/225695556-e0585445-c121-42f7-bef1-f75e71d7ab2b.PNG) 
![discfx](https://user-images.githubusercontent.com/116807307/225695293-3490d9a2-ab9d-49ef-86b5-b22e0287c550.PNG)  
![servcliFx](https://user-images.githubusercontent.com/116807307/225696281-5f2d37ee-09ab-40ba-9fdc-0483a5aadb17.PNG)

      - un client d'un autre langage
     ![image](https://user-images.githubusercontent.com/116807307/225695106-c040dcc0-9d47-4555-a975-94aef0d3333d.png) 
 ![notPython](https://user-images.githubusercontent.com/116807307/225695914-cc71f95c-6222-492b-b6d0-4e812b4b5012.PNG) 

 3- Utiliser un outil Comme JMeeter pour tester les performances des deux serveurs
  Ce test de performance est  de 100 utilisateurs simulés qui se connectent au serveur de chat en 10 secondes et restent connectés pendant 60 secondes avant de se déconnecter :

Number of Threads : 100
Ramp-Up Period : 10
Loop Count : 1
Duration : 60
Cela signifie que tous les 100 utilisateurs simulés se connecteront au serveur de chat en 10 secondes, resteront connectés pendant 60 secondes, puis se déconnecteront automatiquement.
--Le serveur de Multi Thread Blocking IO
![testserv1](https://user-images.githubusercontent.com/116807307/225696350-bc81f853-6308-45a8-a2e6-51fff4e496d3.PNG)
--Le serveur de Single Thread  utilisant des entrées sorties non bloquantes 
![resnot](https://user-images.githubusercontent.com/116807307/225696317-43347f06-3cbf-4dde-99f1-52e84ba2fb43.PNG)
