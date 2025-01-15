# En linux
sudo apt updat

# Instalacion de apache
sudo apt intall apache2

# Inicio de sericio 
sudo systemctl start apache2

# Verificacion de servicio de apache
sudo systemctl status apache2

# Abrimos editor de texto NANO
sudo nano /etc/apache2/apache.2conf

# Modificar la direcctiva ServerRoot
ServerRoot: "/var/www/html/mi_area"

# Reiniciamos apache 
sudo systemctl restart apache2
