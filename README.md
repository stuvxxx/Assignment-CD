# my-project

For the sake of simplicity I didnt build alot as asked so I continued on with earlier examples! 

Some components: 

- GitHub actions: for adding the workflow with a yml file that fires on a push! 
- GitHub secrets for inserting the needed information in Github so it can be read in the yml file! 
- Digital Ocean to have a server where the files are saved
- Visual Studio to write the code
- Yaml file to run tests and allow the push!  

I like the way how Visual Studio - GitHUb - Digital Ocean - Internet - Browser all are connected!! Things are getting more clear everyday

Three problems: 

- There is alot of old documentation of yml everywhere on internet and it took me a while to figure out I can just use the "needs" 
  instead of struggles with stages and and "dependsOn". The problem solved here is only continue the yml when certain tests succeed.
  
- Updating the files on the server! Solved with the appleboy/scp-action repo

- Allowing access to Github and the Digital Ocean server: 
  an SSH-key generated with a CLI-command and stored in both the server and the Github secret so they one can access the other! 
  
  
