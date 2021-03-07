# MobileAppsDev

Here is the login page. This is the first activity opened when we lunch the application.

![image_2021-03-07_171420](https://user-images.githubusercontent.com/80149866/110246609-8e8f1480-7f68-11eb-8e3f-479dd70557c0.png)


The user have to fullfiled his name and password in order to access the next screen. Nonetheless if the user failed 5 times he cannot login anymore beacause the login button will be locked

![image_2021-03-07_171631](https://user-images.githubusercontent.com/80149866/110246684-dd3cae80-7f68-11eb-8ed0-8f233c58f11a.png)

Once the user has login, the access to the data is granted and we can choose between 3 options, which are represented by 3 buttons.
The first one is called "Save" and is used to download the data in order to be able to read them again even offline with the 3rd button.
The second one is named "Refresh" and is used to refresh the page. The goal is to redownload the json file. In the Offline case the refresh button will display no data at all.
The last one is named "load" and is used to read data from the internal storage of the smartphone. This button always work except if the users didn't even save once.

![image_2021-03-07_173242](https://user-images.githubusercontent.com/80149866/110247161-1fff8600-7f6b-11eb-91ca-1b250c4a9df2.png)


The API key is hidden in gradle.properties and we access the key via the buildconfig as showed below 

![image_2021-03-07_181058](https://user-images.githubusercontent.com/80149866/110248258-78855200-7f70-11eb-9ddc-cbcc4209a313.png)

![image_2021-03-07_181126](https://user-images.githubusercontent.com/80149866/110248282-8935c800-7f70-11eb-91e3-16556f56bc28.png)

![image_2021-03-07_181208](https://user-images.githubusercontent.com/80149866/110248309-a1a5e280-7f70-11eb-8308-f08246350584.png)


Finally the file containing the data is protected by the phone's system. Moreover at the creation of the file a "private mode" is specified. Therefore the access to this file cannot be done by mainstream ways

![image_2021-03-07_182005](https://user-images.githubusercontent.com/80149866/110248483-be8ee580-7f71-11eb-8851-4cacb3b60116.png)
