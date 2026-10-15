# Storingsmelder

1. Clone git repo
````bash
git clone https://github.com/ThibaultUcll/cloud-computing.git
```` 

2. Move to the folder containing the config.
````bash
cd cloud-computing/
```` 

3. Create a .env file and fill them with your own variables
````bash
cp .env.example .env
```` 
 
4. Start the app.
````bash
    1. Use this command if you want to see the ip where web client on runs.
    sudo docker compose up --build

    2. Use this command if you want the app to start in the background. 
    sudo docker compose up -d build
```` 

5. Go to the webclient on https://localthost:8000

6. To turn the app off use this command
````bash
    1. Use this combo of keys if you did not use -d.
    control + C

    2. Use this command if you used -d. 
    sudo docker compose Down
```` 




