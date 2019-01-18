# HTML-Build-in-System-Sublime for MacOS users 
Here is a way to make your sublime compiles your code and runs it on any desired browsers 

1- Find the correct path of the desired web browser .  

<img width="500" alt="screen shot 2019-01-18 at 4 36 17 am" src="https://user-images.githubusercontent.com/32437621/51378960-543e3100-1adc-11e9-9efa-44cad5e53589.png">

# Usually in --> /Applications/Google Chrome.app <-- for Chrome 

-----------------------------------------------------------------------------------------------------------------------------
<img width="500" alt="screen shot 2019-01-18 at 4 39 37 am" src="https://user-images.githubusercontent.com/32437621/51379304-18579b80-1add-11e9-8f91-e1e8b00b91b0.png">

2- Launch your Sublime Text 3 , and then go to **Tools** --> **Build System**  --> **New Build System**


<img width="500" alt="screen shot 2019-01-18 at 4 39 52 am" src="https://user-images.githubusercontent.com/32437621/51379516-961ba700-1add-11e9-976c-77fc5103bd1a.png">
-----------------------------------------------------------------------------------------------------------------------------
3- Copy and paste the code . 


{
	"cmd":["open", "-a", "/Applications/Google Chrome.app", "$file"]
}
-----------------------------------------------------------------------------------------------------------------------------
4- <img width="400" alt="screen shot 2019-01-18 at 5 00 31 am" src="https://user-images.githubusercontent.com/32437621/51379740-1b9f5700-1ade-11e9-9011-b6bf6f4dd51a.png">

Save it as **HTML** OR you could name it whatever you like . 

You should have it as it shown in below 

<img width="500" alt="screen shot 2019-01-18 at 4 42 21 am" src="https://user-images.githubusercontent.com/32437621/51379822-50131300-1ade-11e9-89f8-f26c38d4dcbb.png">

-----------------------------------------------------------------------------------------------------------------------------
5- 
<img width="500" alt="screen shot 2019-01-18 at 5 04 21 am" src="https://user-images.githubusercontent.com/32437621/51380035-c3b52000-1ade-11e9-8281-d74facab1891.png">

-----------------------------------------------------------------------------------------------------------------------------
6- <img width="500" alt="screen shot 2019-01-18 at 5 06 45 am" src="https://user-images.githubusercontent.com/32437621/51380087-e1828500-1ade-11e9-8851-03e3f22f2dd3.png">

-----------------------------------------------------------------------------------------------------------------------------
7- Because in step 4 we saved it as **HTML** you should see the HTML in the menu 


<img width="400" alt="screen shot 2019-01-18 at 5 09 09 am" src="https://user-images.githubusercontent.com/32437621/51380283-5eadfa00-1adf-11e9-8554-991535924b6d.png">








