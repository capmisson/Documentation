Pasos para la configuración de una IP dinámica de casa en una Raspberry con [Yunohost](www.yunohost.org). con [DonDominio](https://dondominio.com)

Recuerda primero asegurarte de que los puertos del router están abiertos y redireccionando a la raspberry. 

Entrar en la raspberry pi donde tengas yunohost


    git clone https://github.com/dondominio/dondns-bash.git
    cd dondns-bash/dondominio/
    nano dondomcli.conf

 Edita los parámetros:

    DDUSER="tunombredeusuariodondominio"
    DDPASSWORD="tuclaveapi"
    DDHOST="tudominio.org"

Para conseguir tu clave API, puedes hacerlo desde DonDominio "Mi cuenta" => "DonDNS KEY"
Guarda el archivo y:

    chmod a+x dondomcli.sh
    ./dondomcli.sh -c dondomcli.conf 

y para crontab

    nano /etc/crontab
    */5 * * * *     root    test -x /home/admin/dondns-bash/dondominio/dondomcli.sh && /home/admin/dondns-bash/dondominio/dondomcli.sh -c 


Y con esto ya deberías tenerlo


