#on part d'une image de base nginx
FROM nginx

#On remplace le fichier de conf de base d'nginx par le notre qui s'appel default.conf
ADD ./default.conf /etc/nginx/conf.d/

#on ajoute la commande // au debut du nouveau fichier de conf, qui va desactiver le mode daemon d'nginx afin de pouvoir récupéré les log en cas de besoin
RUN echo "daemon off;" >> /etc/nginx/nginx.conf

#lance le service nginx une fois que le container est démarré
CMD service nginx start
