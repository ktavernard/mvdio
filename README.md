# mvdio
Criação de máquina virtual

O passo inicial é criar uma conta, normalmente, mas depois, precisa ter algum tipo de assinatura. <br>
No meu caso, como curso ADS, consegui o acesso para ter a assinatura de estudante. <br>
Caso não tenha, qualquer pessoa poderá utilizar o acesso gratuito (por tempo limitado); apenas para teste.

Iniciando a criação da máquina virtual:<br>
Logo na página inicial do portal do Azure, tem vários ícones e um deles, é o de Máquinas <br>
Virtuais. É o segundo ícone, logo ao lado de "Criar um recurso". <br>
Ao acessar o ícone "Máquinas Virtuais", passa para a próxima página e clica no "+" que é o "criar". <br>
Clicar em "Máquina virtual do Azure".<br>

Detalhes do projeto:<br>
Assinatura: Azure for Students (essa é a minha assinatura, mas existem outras);<br>
Grupo de recursos: NetworkWatcherRG (caso não tenha recurso criado, podemos criar na hora mesmo).<br>

Detalhes da instância:<br>
Nome da máquina virtual: minhaMV (podemos ecolher o nome de nossa preferência);<br>
Região: (South America) Brazil South<br>
Opções de disponibilidade: Nenhuma redundância infraestrutura necessária (não preciso de infraestrutura para esse projeto).<br>
     Obs.: as zonas de disponibilidade são localizações físicas distintas dentro de uma região do Azure. Cada zona é composta por <br>
     um ou mais datacenters equipados com energia, resfriamento e rede independentes. Ao distribuir VMs replicadas por múltiplas <br>
     Zonas de Disponibilidade, é garantido que, se uma zona inteira for afetada por uma falha, as VMs em outras zonas continuarão<br>
     operacionais, mantendo a disponibilidade do aplicativo. <br>
Tipo de segurança: padrão<br>
Imagem: Windows server 2019 Datacerner - x64 Gen2 <br>
     Obs.: é o sistema operacional base para a máquina virtual<br>
Executar com desconto de Spot do Azure: marcada (como é apenas um teste, ao marcar essaopção, o custo fica ínfimo, pois mesmo que <br>
não irei ser cobrada, não quero arriscar rs)<br>

Conta de administrador:<br>
Nome de usuário: xxx<br>
Senha: xxx<br>
Confirmar senha: xxx<br>
<p></p>
Regras de portas de entrada:<br>
Portas de entrada públicas: Permitir portas selecionadas<br>
     Obs.: "Por padrão, o acesso à máquina virtual é restrito a fontes na mesma rede virtual e tráfego das soluções de balanceamento <br>
     de carga do Azure. Selecione Nenhum para confirmar ou escolha permitir o tráfego da internet pública a uma dessas portas comuns."<br>

<p>Clique em Revisar e criar (botão azul).<br>
Aguarde ter a validação aprovada.<br>
Clique em criar (botão azul)<br>
Começará o carregamento para iniciar a implantação.<br>
A implantação ficará em andamento.<br>
Ao fima, a implantaç~çao é concluída!<br>
</p>




