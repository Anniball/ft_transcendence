## Remember
`psql setup on school mac`  

`brew install postgresql`  
`brew services start postgresql`  
`psql postgres`  
`create database ft_transcendence`  
`create user ft_transcendence_user with password 'GbXfciERgi7kAad9rmrvADL2mUmWuo'`  
`grant all privileges on database ft_transcendence to ft_transcendence_user`  

#### Note that you can and should change any of the user name, database name or password in the .env file.
#### Those which are presents are just here for the example !

## Create an html documentation  
Go into the client/server folder and use command line :   
`npx typedoc --tsconfig tsconfig.json`   
A folder docs/ will be created/modified and index.html is inside.
