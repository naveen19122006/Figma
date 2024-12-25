# Ex09 Event Registration Web Application
# Date:10-12-2024
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
page 1
~~~
<div style="width: 440px; height: 956px; position: relative; background: white">
  <img style="width: 440px; height: 956px; left: 0px; top: 0px; position: absolute" src="https://via.placeholder.com/440x956" />
  <img style="width: 425px; height: 64px; left: 7px; top: 63px; position: absolute" src="https://via.placeholder.com/425x64" />
  <div style="width: 272px; left: 16px; top: 895px; position: absolute; justify-content: flex-start; align-items: flex-start; display: inline-flex">
    <div style="color: #1E1E1E; font-size: 16px; font-family: Inter; font-weight: 400; text-decoration: underline; line-height: 22.40px; word-wrap: break-word">Forgot password?</div>
  </div>
  <div style="width: 192px; left: 116px; top: 523px; position: absolute; justify-content: flex-start; align-items: center; gap: 16px; display: inline-flex">
    <div style="flex: 1 1 0; height: 40px; padding: 12px; background: #2C2C2C; border-radius: 8px; overflow: hidden; border: 1px #2C2C2C solid; justify-content: center; align-items: center; gap: 8px; display: flex">
      <div style="color: #F5F5F5; font-size: 16px; font-family: Inter; font-weight: 400; line-height: 16px; word-wrap: break-word">Sign In</div>
    </div>
  </div>
  <div style="height: 70px; left: 83px; top: 408px; position: absolute; flex-direction: column; justify-content: flex-start; align-items: flex-start; gap: 8px; display: inline-flex">
    <div style="align-self: stretch; color: #1E1E1E; font-size: 16px; font-family: Inter; font-weight: 400; line-height: 22.40px; word-wrap: break-word">Password</div>
    <div style="align-self: stretch; padding-left: 16px; padding-right: 16px; padding-top: 12px; padding-bottom: 12px; background: white; border-radius: 8px; overflow: hidden; border: 1px #D9D9D9 solid; justify-content: flex-start; align-items: center; display: inline-flex">
      <div style="flex: 1 1 0"></div>
    </div>
  </div>
  <div style="height: 70px; left: 83px; top: 318px; position: absolute; flex-direction: column; justify-content: flex-start; align-items: flex-start; gap: 8px; display: inline-flex">
    <div style="align-self: stretch; color: #1E1E1E; font-size: 16px; font-family: Inter; font-weight: 400; line-height: 22.40px; word-wrap: break-word">Email</div>
    <div style="align-self: stretch; padding-left: 16px; padding-right: 16px; padding-top: 12px; padding-bottom: 12px; background: white; border-radius: 8px; overflow: hidden; border: 1px #D9D9D9 solid; justify-content: flex-start; align-items: center; display: inline-flex">
      <div style="flex: 1 1 0"></div>
    </div>
  </div>
</div>
~~~

page 2
~~~
<div style="width: 440px; height: 956px; position: relative; background: white">
  <img style="width: 440px; height: 956px; left: 0px; top: 0px; position: absolute" src="https://via.placeholder.com/440x956" />
  <img style="width: 440px; height: 66px; left: 0px; top: 49px; position: absolute" src="https://via.placeholder.com/440x66" />
  <div style="width: 314px; height: 720px; left: 63px; top: 59px; position: absolute; text-align: center"><span style="color: black; font-size: 16px; font-family: Inter; font-weight: 400; line-height: 16px; word-wrap: break-word"><br/></span><span style="color: black; font-size: 14px; font-family: Inter; font-weight: 600; line-height: 14px; word-wrap: break-word"><br/><br/>Cricket<br/><br/><br/>Football (Soccer)<br/><br/><br/>Basketball<br/><br/><br/>Volleyball<br/><br/><br/>Kabaddi<br/><br/><br/>Hockey<br/><br/><br/>Throwball<br/><br/><br/>Baseball/Softball<br/><br/><br/>Rugby<br/><br/><br/>Handball</span></div>
  <div style="width: 185px; height: 67px; padding: 12px; left: 128px; top: 712px; position: absolute; background: #EC221F; border-radius: 8px; overflow: hidden; border: 1px #C00F0C solid; justify-content: center; align-items: center; gap: 8px; display: inline-flex">
    <div style="color: #FEE9E7; font-size: 16px; font-family: Inter; font-weight: 400; line-height: 16px; word-wrap: break-word">REGISTER</div>
  </div>
</div>
~~~

page 3
~~~
<div style="width: 440px; height: 956px; position: relative; background: white">
  <img style="width: 440px; height: 956px; left: 0px; top: 0px; position: absolute" src="https://via.placeholder.com/440x956" />
  <div style="width: 356px; height: 64px; left: 42px; top: 55px; position: absolute; text-align: center"><span style="color: black; font-size: 32px; font-family: Inter; font-weight: 600; line-height: 42.24px; word-wrap: break-word">REGISTRATION FOR</span><span style="color: black; font-size: 32px; font-family: Inter; font-weight: 600; line-height: 42.24px; letter-spacing: 7.36px; word-wrap: break-word">M</span></div>
  <div style="left: 42px; top: 171px; position: absolute; flex-direction: column; justify-content: flex-start; align-items: flex-start; gap: 8px; display: inline-flex">
    <div style="align-self: stretch; color: #1E1E1E; font-size: 16px; font-family: Inter; font-weight: 400; line-height: 22.40px; word-wrap: break-word">NAME</div>
    <div style="align-self: stretch; padding-left: 16px; padding-right: 16px; padding-top: 12px; padding-bottom: 12px; background: white; border-radius: 8px; overflow: hidden; border: 1px #D9D9D9 solid; justify-content: flex-start; align-items: center; display: inline-flex">
      <div style="flex: 1 1 0"></div>
    </div>
  </div>
  <div style="left: 42px; top: 254px; position: absolute; flex-direction: column; justify-content: flex-start; align-items: flex-start; gap: 8px; display: inline-flex">
    <div style="align-self: stretch; color: #1E1E1E; font-size: 16px; font-family: Inter; font-weight: 400; line-height: 22.40px; word-wrap: break-word">GENDER</div>
    <div style="align-self: stretch; padding-left: 16px; padding-right: 16px; padding-top: 12px; padding-bottom: 12px; background: white; border-radius: 8px; overflow: hidden; border: 1px #D9D9D9 solid; justify-content: flex-start; align-items: center; display: inline-flex">
      <div style="flex: 1 1 0"></div>
    </div>
  </div>
  <div style="left: 42px; top: 337px; position: absolute; flex-direction: column; justify-content: flex-start; align-items: flex-start; gap: 8px; display: inline-flex">
    <div style="align-self: stretch; color: #1E1E1E; font-size: 16px; font-family: Inter; font-weight: 400; line-height: 22.40px; word-wrap: break-word">YEAR</div>
    <div style="align-self: stretch; padding-left: 16px; padding-right: 16px; padding-top: 12px; padding-bottom: 12px; background: white; border-radius: 8px; overflow: hidden; border: 1px #D9D9D9 solid; justify-content: flex-start; align-items: center; display: inline-flex">
      <div style="flex: 1 1 0"></div>
    </div>
  </div>
  <div style="width: 240px; left: 42px; top: 439px; position: absolute; flex-direction: column; justify-content: flex-start; align-items: flex-start; gap: 8px; display: inline-flex">
    <div style="align-self: stretch; color: #1E1E1E; font-size: 16px; font-family: Inter; font-weight: 400; line-height: 22.40px; word-wrap: break-word">DEPARTMENT</div>
    <div style="align-self: stretch; padding-left: 16px; padding-right: 16px; padding-top: 12px; padding-bottom: 12px; background: white; border-radius: 8px; overflow: hidden; border: 1px #D9D9D9 solid; justify-content: flex-start; align-items: center; display: inline-flex">
      <div style="flex: 1 1 0"></div>
    </div>
  </div>
  <div style="left: 42px; top: 529px; position: absolute; flex-direction: column; justify-content: flex-start; align-items: flex-start; gap: 8px; display: inline-flex">
    <div style="align-self: stretch; color: #1E1E1E; font-size: 16px; font-family: Inter; font-weight: 400; line-height: 22.40px; word-wrap: break-word">SPORTS TO PARTICIPATE</div>
    <div style="align-self: stretch; padding-left: 16px; padding-right: 16px; padding-top: 12px; padding-bottom: 12px; background: white; border-radius: 8px; overflow: hidden; border: 1px #D9D9D9 solid; justify-content: flex-start; align-items: center; display: inline-flex">
      <div style="flex: 1 1 0"></div>
    </div>
  </div>
  <div style="width: 175px; height: 69px; padding: 12px; left: 134px; top: 737px; position: absolute; background: #2C2C2C; border-radius: 8px; overflow: hidden; border: 1px #2C2C2C solid; justify-content: center; align-items: center; gap: 8px; display: inline-flex">
    <div style="color: #F5F5F5; font-size: 16px; font-family: Inter; font-weight: 400; line-height: 16px; word-wrap: break-word">REGISTER</div>
  </div>
</div>
~~~
page 4
~~~
<div style="width: 440px; height: 956px; position: relative; background: white">
  <img style="width: 640px; height: 960px; left: -66px; top: -4px; position: absolute" src="https://via.placeholder.com/640x960" />
  <img style="width: 440px; height: 66px; left: 0px; top: 48px; position: absolute" src="https://via.placeholder.com/440x66" />
  <div style="width: 362px; height: 63px; left: 41px; top: 297px; position: absolute; text-align: center; color: black; font-size: 16px; font-family: Inter; font-weight: 400; line-height: 16px; word-wrap: break-word">THANK YOU FOR REGISTRATION</div>
</div>
~~~
# OUTPUT:
![image](https://github.com/user-attachments/assets/59b6e987-c683-4e17-aeb3-4bf1038b9e0c)
![image](https://github.com/user-attachments/assets/c80c6827-7c9d-4039-b477-f1f2e2b281f7)
![image](https://github.com/user-attachments/assets/e55b3176-4fbe-40dd-8838-48f325b0e1c3)
![image](https://github.com/user-attachments/assets/64010b28-cd07-42c8-8b66-613bda5cd297)


# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
