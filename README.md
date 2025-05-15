# mvdio
Criação de máquina virtual
<p></p>
O passo inicial é criar uma conta, normalmente, mas depois, precisa ter algum tipo de assinatura. <br>
No meu caso, como curso ADS, consegui o acesso para ter a assinatura de estudante. <br>
Caso não tenha, qualquer pessoa poderá utilizar o acesso gratuito (por tempo limitado); apenas para teste.
<p></p>
Iniciando a criação da máquina virtual:<br>
Logo na página inicial do portal do Azure, tem vários ícones e um deles, é o de Máquinas <br>
Virtuais. É o segundo ícone, logo ao lado de "Criar um recurso". <br>
Ao acessar o ícone "Máquinas Virtuais", passa para a próxima página e clica no "+" que é o "criar". <br>
Clicar em "Máquina virtual do Azure".<br>

Detalhes do projeto:
Assinatura: Azure for Students (essa é a minha assinatura, mas existem outras);
Grupo de recursos: NetworkWatcherRG (caso não tenha recurso criado, podemos criar na hora mesmo).

Detalhes da instância:
Nome da máquina virtual: minhaMV (podemos ecolher o nome de nossa preferência);
Região: (South America) Brazil South
Opções de disponibilidade: Nenhuma redundância infraestrutura necessária (não preciso de infraestrutura para esse projeto).
     Obs.: as zonas de disponibilidade são localizações físicas distintas dentro de uma região do Azure. Cada zona é composta por 
     um ou mais datacenters equipados com energia, resfriamento e rede independentes. Ao distribuir VMs replicadas por múltiplas 
     Zonas de Disponibilidade, é garantido que, se uma zona inteira for afetada por uma falha, as VMs em outras zonas continuarão
     operacionais, mantendo a disponibilidade do aplicativo.   
Tipo de segurança: padrão
Imagem: Windows server 2019 Datacerner - x64 Gen2 
     Obs.: é o sistema operacional base para a máquina virtual
Executar com desconto de Spot do Azure: marcada (como é apenas um teste, ao marcar essaopção, o custo fica ínfimo, pois mesmo que 
não irei ser cobrada, não quero arriscar rs)

Conta de administrador:
Nome de usuário: xxx
Senha: xxx
Confirmar senha: xxx

Regras de portas de entrada:
Portas de entrada públicas: Permitir portas selecionadas
     Obs.: "Por padrão, o acesso à máquina virtual é restrito a fontes na mesma rede virtual e tráfego das soluções de balanceamento 
     de carga do Azure. Selecione Nenhum para confirmar ou escolha permitir o tráfego da internet pública a uma dessas portas comuns."

Clique em Revisar e criar (botão azul).
Aguarde ter a validação aprovada.
Clique em criar (botão azul)
Começará o carregamento para iniciar a implantação.
A implantação ficará em andamento.
Ao fima, a implantaç~çao é concluída!





