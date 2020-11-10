# typically change the listener to 8080

Listen 8080

# add some virtual webs

<VirtualHost *:8080>
  DocumentRoot /var/www/www
  ServerName www.example.com
</VirtualHost>

<VirtualHost *:8080>
  DocumentRoot /var/www/member
  ServerName member.example.com
</VirtualHost>

<VirtualHost *:8080>
  DocumentRoot /var/www/other
  ServerName other.example.com
</VirtualHost>
