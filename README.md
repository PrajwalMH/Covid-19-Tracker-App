# majorproject_covid19_tracker

Major Project 

1.Any Dynamic Application using Flutter that should include following features:
2.Login & Logout [Firebase DB or shared preferences]
3.User Sign up [Firebase DB or shared preferences
4.Logic with state management
5.UI with almost all widgets discussed in session.
6.Burger Menu
7.Updated App Icon
8.Result screen


This is my Dynamic Flutter App for my verzeo major project.At first Login/Signup page is created which is provided with Email and password authentication.After logging it goes to splashscreen(loading page) until the data is fetched to homepage(by API).Then we go to the homepage where it displays worldwide covid-19 data.If we require country wise then we can go to regional and search for that particular country.Data is displayed in pie chart and below which 5 most effected country is listed.There is a comment button where user can comment which will be added to cloud firestore database and displayed by getting it from cloud firestore database in bubbleshaped container.There is also a refresh indicator where you can refresh the homepage to get the updated data.Then there is App drawer(Burger Menu)with information which takes to infomation screen where you can find basic Q/A information related to Covid-19.Ther other options are Donate which is directed to PM care fund website and next MYTH BUSTER which will direct to WHO website to know much about Covid-19.The Logout button will signout the user an navigate to Loginpage.App Icon is changed with default App Icon.


Execution of project:



https://user-images.githubusercontent.com/68767604/124381981-c4f45a80-dce2-11eb-9aa2-7107f2a4e87a.mp4



Here are some Screen shots by step by step Execution:

1.APPICON:
![IMG_20210704_011944](https://user-images.githubusercontent.com/68767604/124382717-82348180-dce6-11eb-8d08-a3ccae122530.jpg)
![Screenshot_2021-07-04-15-10-17-724_com miui home](https://user-images.githubusercontent.com/68767604/124382720-86f93580-dce6-11eb-8625-f5aee30de3c1.jpg)









2.Loginpage/Signuppage



![m1](https://user-images.githubusercontent.com/68767604/124382009-f836e980-dce2-11eb-84df-92622cb43611.png)
![m2](https://user-images.githubusercontent.com/68767604/124382023-008f2480-dce3-11eb-924b-d56cf8f00f2a.png)



3.loading page:



![m3](https://user-images.githubusercontent.com/68767604/124382092-392efe00-dce3-11eb-96cf-930e077bf668.png)





4.Homepage:



![m4](https://user-images.githubusercontent.com/68767604/124382113-67acd900-dce3-11eb-93c5-ec7526e706ed.png)
![m5](https://user-images.githubusercontent.com/68767604/124382130-801cf380-dce3-11eb-8c4e-94619eb0fe35.png)




5.Alert Dialog message from Appbar icon:


![m6](https://user-images.githubusercontent.com/68767604/124382179-b8243680-dce3-11eb-95c5-2ab571e14389.png)




6.Country wise data with search operation:




![m7](https://user-images.githubusercontent.com/68767604/124382275-2f59ca80-dce4-11eb-80d3-8710feb4bdf4.png)
![m8](https://user-images.githubusercontent.com/68767604/124382277-3254bb00-dce4-11eb-9193-3ad9c068cd3e.png)
![m9](https://user-images.githubusercontent.com/68767604/124382279-341e7e80-dce4-11eb-8bcc-06a9a63965b9.png)





7.Refresh Indicator:



![m10](https://user-images.githubusercontent.com/68767604/124382298-4c8e9900-dce4-11eb-8965-3ed19803af6f.png)




8.Comment Page:



![m12](https://user-images.githubusercontent.com/68767604/124382338-8bbcea00-dce4-11eb-9edf-fc2aa297cf23.png)
![m13](https://user-images.githubusercontent.com/68767604/124382343-937c8e80-dce4-11eb-8af7-334fe9adcd2b.png)
![m14](https://user-images.githubusercontent.com/68767604/124382351-98d9d900-dce4-11eb-97b6-2d5687f1334d.png)





9.DrawerApp:



![m15](https://user-images.githubusercontent.com/68767604/124382378-c3c42d00-dce4-11eb-9b5f-743f3c96e1b5.png)




10.Information Page:



![m16](https://user-images.githubusercontent.com/68767604/124382395-d9d1ed80-dce4-11eb-9bbf-28fb0761eb60.png)




11.Donate which will direct to PM CARES website with tooltip:




![m17](https://user-images.githubusercontent.com/68767604/124382558-b3608200-dce5-11eb-9207-32aefa8af80b.png)
![m18](https://user-images.githubusercontent.com/68767604/124382561-b65b7280-dce5-11eb-9780-7395736fbb98.png)





12.Myth buster which will direct to WHO website with tooltip:



![m19](https://user-images.githubusercontent.com/68767604/124382593-e6a31100-dce5-11eb-9087-2818501d64bc.png)
![m20](https://user-images.githubusercontent.com/68767604/124382608-f15da600-dce5-11eb-8561-bb1cdfe3406a.png)




13.Logout which shows alert dialog with yes or no option where no pops out the context where yes pops until it reaches loginpage:


![m21](https://user-images.githubusercontent.com/68767604/124382681-40a3d680-dce6-11eb-9e03-da63f0661a88.png)









