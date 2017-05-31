# Commands for terminal Linux


## Task Manager

#### What is running
`ps aux`

#### Search program (e.x. phpstorm) from the list
`ps aux | grep storm`

#### Stop the program
`kill <program_id>`

## -------------------------

## Create a user in magento
#### Connect to your virtual box as root at your project root folder and run

`n98-magerun.phar admin:user:create`

## -------------------------

## If your Xdebug keeps running
#### Connect to your virtual box as root and change xdebug.ini name

`cd /etc/php.d`

`mv xdebug.ini xdebug.ini.bak`

## -------------------------
