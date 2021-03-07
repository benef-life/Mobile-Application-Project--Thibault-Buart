# Mobile-Application-Project--Thibault-Buart
This is the login page when the application is launching

![image](https://user-images.githubusercontent.com/64968616/110255712-6964cb00-7f95-11eb-91bf-bafa37e077ed.png)

To get access to his bank informations, the app user has to fill the two EditText boxes with his ID(id) and password(password). After 5 failed tries, the login button locks and it quits the application for security.

![image](https://user-images.githubusercontent.com/64968616/110255718-72ee3300-7f95-11eb-925b-8dfb2ebb5331.png)

Once the user has login, the access to the data is granted and he can make 3 actions, which are represented by 3 buttons. The first one is called "SAVE" and is used to download the data in order to be able to read them again even offline with the "LOAD". The second one is named "REFRESH" and is used to refresh the page. The goal is to redownload the json file. If the user is offline, the refresh button will display no data at all. The last one named "LOAD" and is used to read data from the internal storage of the smartphone. This button always work except if the user never saved his bank data.

![image](https://user-images.githubusercontent.com/64968616/110255725-7b466e00-7f95-11eb-96c6-3eda4851cc0c.png)

The API key is hidden in gradle.properties and we access the key via the buildconfig function as showed below

![image](https://user-images.githubusercontent.com/64968616/110255736-86999980-7f95-11eb-9a7c-d8eb2aa8a8bd.png)

![image](https://user-images.githubusercontent.com/64968616/110255741-8ac5b700-7f95-11eb-87a6-898fd865bbf5.png)

![image](https://user-images.githubusercontent.com/64968616/110255745-8f8a6b00-7f95-11eb-9a12-b5eb53a7fc31.png)

Finally the file containing the data is protected by the phone's system. Moreover at the creation of the file a "private mode" is specified. Therefore the access to this file cannot be done by mainstream ways.

![image](https://user-images.githubusercontent.com/64968616/110255749-944f1f00-7f95-11eb-955e-c84ff0346d7c.png)
