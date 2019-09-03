Focus will be on the Frontend
1. In the Docker Terminal, you will build the project - $ docker build -f Dockerfile .(. - is important at the end of the build). You will then check if the container has been created - $ docker ps 
You will then execute/deploy - $ node app.js

Add item:
Edit the create new todo item: driver.findElement(By.xpath("//input[@id='newtodo']")).sendKeys("info");
And click submit - driver.findElement(By.xpath("//input[@type='submit'];

Delete item:
Click on the X and the added item should be deleted - driver.findElement(By.xpath("//a[contains(@href,'delete/1')]")).click();

Edit item:
Enter in the text - driver.findElement(By.xpath("//input[@id='newtodo']")).sendKeys("info");
Click Update - driver.findElement(By.xpath(""//a[contains(@id,'submit-1')]")).click();