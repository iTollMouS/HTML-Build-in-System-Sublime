# HTML-Build-in-System-Sublime for MacOS users 
Here is a way to make your sublime compiles your code and runs it on any desired browsers 

1- Find the correct path of the desired web browser .  

<img width="500" alt="screen shot 2019-01-18 at 4 36 17 am" src="https://user-images.githubusercontent.com/32437621/51378960-543e3100-1adc-11e9-9efa-44cad5e53589.png">

# Usually in --> /Applications/Google Chrome.app <-- for Chrome 

-----------------------------------------------------------------------------------------------------------------------------
<img width="500" alt="screen shot 2019-01-18 at 4 39 37 am" src="https://user-images.githubusercontent.com/32437621/51379304-18579b80-1add-11e9-8f91-e1e8b00b91b0.png">

2- Launch your Sublime Text 3 , and then go to **Tools** --> **Build System**  --> **New Build System**


<img width="500" alt="screen shot 2019-01-18 at 4 39 52 am" src="https://user-images.githubusercontent.com/32437621/51379516-961ba700-1add-11e9-976c-77fc5103bd1a.png">

3- Copy and paste the code . 


{
	"cmd":["open", "-a", "/Applications/Google Chrome.app", "$file"]
}


