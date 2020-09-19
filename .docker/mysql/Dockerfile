FROM mysql:5.7
# Não preciso instalar o usermod porque essa imagem ja vem com ele!
RUN usermod -u 1002 mysql
# utilize o comando "echo $UID" para ver qual uid do seu usuario na sua maquina no meu caso é 1002
# o comando usermod ele modifica o arquivo passwd de configuração dos usuarios do linux o -u significa UID novo uid para conta de usuário
