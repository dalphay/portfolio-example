# portfolio-example

Step by step portfolio deployment and workflow for  simplonlyon.fr

1) Start by creating a github project that will contain your portfolio's webpages. It should contain an index.php page
2) Connect in ssh to simplonlyon.fr then navigate to your www folder ( /var/www/simplonlyon.fr/promo*/username )
3) Clone your portfolio project directly into this folder ( git clone https://github.com/username/project . )
4) Now you can work on your portfolio on your local machine and push your modification to github, then just connect in ssh to simplonlyon.fr and git pull inside your www folder