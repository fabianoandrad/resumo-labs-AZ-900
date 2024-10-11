# resumo-labs-AZ-900

![](assets/2202518_37a7_2.jpg)
### Resumo dos desafios de projetos do bootcamp Microsoft Azure Essentials

* Necessario ter conta criada na plataforma Microsoft Azure
* Acesse o [Portal do Azure](https://azure.microsoft.com/pt-br/get-started/azure-portal/) para criar sua conta.
* O portal vai ser o mesmo pra todos os tipos de usuários na plataforma.

## Localizando Serviços por categoria

* Alterando idioma 
![](assets/232952.png)
* Na imagem abaixo podemos ver todos os serviços por categoria
![](assets/234516.png)

## Criando máquinas virtuais na azure

* No menu lateral esquerdo acesse Maquinas virtuais (irá abrir outra página) como imagem abaixo e clique em +Criar e depois em Maquina virtual do Azure
![](assets/000315.png) 
* Em assinatura mantenha a sua que já estará disponível
* Crie um grupo de recurso - onde sua VM passará a fazer parte deste grupo, servirá como organização do seus projetos
* Coloque um nome pra sua VM
* Escolha uma região para criar sua VM - Obs, nem todos os tamanhos de VM estão disponíveis em todas as regiões.
* Escolha a opção de disponibilidade - saiba mais sobre [zona de disponibilidade](https://learn.microsoft.com/pt-br/azure/virtual-machines/availability)
* Tipo de segurança - O tipo de segurança refere-se aos diferentes recursos de segurança disponíveis para uma máquina virtual. saiba mais sobre [Tipos de segurança](https://learn.microsoft.com/pt-br/azure/virtual-machines/trusted-launch)
* Imagem - Escolha o aplicativo ou sistema operacional base para a VM
* Arquitetura de VM - 
O Azure oferece uma opção de máquinas virtuais baseadas em x64 ou Arm64 para executar seus aplicativos.

## Configurando uma instância de Banco de Dados na Azure
* No menu lateral esquerdo acesse Bancos de dados SQL (irá abrir outra página) como imagem abaixo e clique em +Criar
![](assets/003517.png)
* Em assinatura mantenha a sua que já estará disponível
* Crie um grupo de recurso (o mesmo da criação de VM)
* Adicione um nome ao BD SQL
* Selecione um servidor - um existente ou crie um servidor. A cadeia de conexão e as credenciais serão baseadas no servidor.
## Construindo Arquiteturas no Azure
* A Azure está em mais 60 regiões do nosso globo terrestre
* Neste [link](https://azure.microsoft.com/en-us/explore/global-infrastructure) você poderá ver varios assuntos sobre os datacenters da Azure
* Na imagem abaixo podemos ver todos os locais que estão os datacenters da Azure
![](assets/005041.png)
* Veja o globo em 3D neste [link](https://datacenters.microsoft.com/globe/explore)

#### Criando um grupo de recurso na Azure
* No lateral esquerdo clique em Grupos de recursos e será direcionado pra proxima página como a imagem abaixo
![](assets/010644.png)
* Clique em +Criar
* Em assinatura mantenha a sua que já estará disponível
* Crie um grupo de recurso - Um grupo de recursos é uma coleção de recursos que compartilha o mesmo ciclo de vida, permissões e políticas
* Escolha uma região - a que seja ideal para você e seus clientes
* Clique em Avançar:Marcações e sera direcionado pro próximo passo como imagem abaixo
![](assets/011452.png)
* Nesta passo não é obrigatório, saiba mais em [Marcações](https://learn.microsoft.com/pt-br/azure/azure-resource-manager/management/tag-resources)
* Clique em Avançar para Revisar e Criar Recurso, veja na imagem abaixo este passo
![](assets/011920.png)
* Após recurso criando você poderá navegar sobre as opções do recurso no menu lateral esquerdo como imagem abaixo.
![](assets/012344.png)
#### Após criado o recurso vc pode trazer itens de outros locais pra colocar no recurso criado
* Vamos criar uma Rede virtual para colocar no nosso recursos, veja na imagem abaixo.
![](assets/012812.png)
* Clique em +Criar
* Em seguida configure como exemplo na imagem abaixo, perceba que ele já seleciona o grupo de recurso já criado.
![](assets/013236.png)
* Adicione um nome pra sua rede virtual
* Selecione uma região como por ex: South America Brazil South
* Agora Clique em Analisar e criar
* Tudo feito vá no seu recurso criado e dentro dele já vai estar seu recurso de rede virtual criado, como na imagem abaixo.
![](assets/013632.png)

