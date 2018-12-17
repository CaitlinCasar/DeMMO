# DeMMO
DeMMO website

##### Dictionary of commands #####

#restart nginx server 

    service nginx restart


#restart shiny server

    sudo systemctl restart shiny-server



##### important file locations #####

#DeMMO server-side repo port 443

    /var/www/DeMMO


#DeMMO server config (symbiotic link with sites-enabled)

    /etc/nginx/sites-available


#DeMMO_Shiny server-side repo port 3838

    /srv/shiny-server/DeMMO_Shiny


#Shiny server config

    /etc/shiny-server



##### ssh into server #####
    ssh username@ip_address

##### git workflow #####

#list changes in repo

    git status


#add all new files staging - only needed if new files have been added, otherwise skip to commit

    git add .


#view differences in files

    git diff 


#commit all changes in files to staging

    git commit -a -m "message"


#sync changes to github repo

    git push


#update server from github repo

    git pull 


##### commands for vim #####

#quit vim

    esc + :q


#save file

    esc + :wq


#edit a line 

    i 
    
    
##### style Shiny apps #####
https://shiny.rstudio.com/articles/css.html

##### deploy Shiny apps #####

https://www.r-bloggers.com/deploying-your-very-own-shiny-server/
