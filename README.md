FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

sudo apt -y update && apt -y upgrade

sudo apt install -y git

git clone https://github.com/euiff/autoinstalador.git

sudo chmod +x ./autoinstalador/install_primaria

cd autoinstalador && sudo ./install_primaria



ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:


sudo chmod +x ./autoinstalador/install_instancia

cd ./autoinstalador && sudo ./install_instancia


