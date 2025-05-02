# Resumo-do-lab
Resumo, aula de laboratorio Azure

# Aula 1
Apresentação da plafortma Azure, desde configurações, estilização da plataforma, e as ferramentas mais basicas. Foi abordado o conceito de Jump-Server, que no meu entendimento é uma porta de entrada para uma rede de maquinas virtuais, sendo mais facil, mapear e garantir a segurança. No geral, foi algo mais para conhecer a plataforma e os serviços oferecidos pela plataforma.

# Aula 2
 Criamos uma máquina virtual (VM) do zero na Azure. O processo foi o seguinte:

Acessamos o portal da Azure e fomos na opção de criar recurso. Selecionamos "Máquina Virtual" e preenchemos os dados básicos: nome, região, sistema operacional (Windows), tipo de conta e grupo de recursos. Escolhemos o tamanho da VM, configuramos usuário e senha para acesso, definimos as regras de rede, liberando a porta 3389 (RDP) pra conseguir acessar a máquina remotamente. Depois de finalizamos a criação, usamos o RDP (Remote Desktop) pra conectar nela. Já dentro da VM, conseguimos navegar, instalar programas e usar como se fosse um PC normal na nuvem. Deu pra ver bem como criar e acessar uma VM na prática, e entender os principais pontos de configuração.

# Aula 3 
Criação de uma instância de Banco de Dados SQL na Azure:

Acessamos o portal da Azure e buscamos por "SQL Database". Iniciamos a criação e preenchemos as informações básicas: nome do banco, grupo de recursos e criamos um servidor lógico com login e senha. Escolhemos uma camada de desempenho mais simples, ideal pra testes. Depois, configuramos as regras de firewall, liberando o nosso IP pra conseguir acessar o banco. Com tudo pronto, usamos o Query Editor dentro da própria Azure pra rodar alguns comandos SQL direto do navegador. Também foi mostrado como conectar o banco usando ferramentas como Azure Data Studio e SQL Server Management Studio (SSMS). Foi uma boa introdução prática pra entender como subir e interagir com um banco na nuvem.
