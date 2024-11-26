# resumo-do-lab

Criar uma máquina virtual no Azure é um processo direto e intuitivo. Primeiro, você precisa acessar o portal do Azure e navegar até a seção de máquinas virtuais. Lá, inicia-se o processo de configuração, onde você escolhe a assinatura vinculada, define ou seleciona um grupo de recursos existente e insere o nome da VM. Em seguida, seleciona-se a região onde a máquina será hospedada, levando em conta a proximidade e as necessidades de desempenho.

O próximo passo envolve a escolha da imagem do sistema operacional, como Windows ou Linux, e o tamanho da máquina, com opções baseadas em CPU, memória e custo. Para configurar o acesso, você pode optar por autenticação via senha ou chave SSH, dependendo do sistema escolhido. A configuração de rede também é essencial, onde você define uma rede virtual, sub-rede e habilita portas como RDP para Windows ou SSH para Linux.

Após ajustar as opções de armazenamento, selecionando o tipo de disco mais adequado para sua aplicação, você pode revisar todas as configurações para garantir que estejam corretas. Ao finalizar, basta clicar em "Criar" e aguardar o provisionamento da máquina. Quando a VM estiver pronta, você pode acessá-la pelo IP público fornecido, usando ferramentas como RDP ou SSH, dependendo do sistema operacional configurado. Assim, a máquina virtual estará pronta para ser utilizada conforme suas necessidades.


Os serviços do Azure são amplamente categorizados em três modelos principais: Infraestrutura como Serviço (IaaS), Plataforma como Serviço (PaaS) e Software como Serviço (SaaS). Cada um deles oferece diferentes níveis de responsabilidade entre o provedor e o cliente, permitindo que as empresas escolham o nível de controle e gerenciamento que melhor atende às suas necessidades.

No modelo IaaS, como máquinas virtuais e redes virtuais, o Azure fornece a infraestrutura básica, como servidores, armazenamento e conectividade de rede. Nesse caso, o cliente é responsável pela gestão do sistema operacional, aplicativos, tempo de execução e segurança interna da aplicação. É ideal para empresas que precisam de flexibilidade para configurar e gerenciar seus próprios ambientes.

Já o PaaS oferece um nível maior de abstração. Aqui, o Azure gerencia a infraestrutura subjacente e o sistema operacional, enquanto o cliente se concentra no desenvolvimento e gerenciamento das aplicações. Exemplos incluem serviços como Azure App Services e Azure Functions. Este modelo é perfeito para desenvolvedores que desejam agilidade no desenvolvimento e redução da sobrecarga operacional.

Por fim, o SaaS é o nível mais gerenciado, no qual o Azure fornece aplicativos prontos para uso, como o Microsoft 365. Nesse caso, o cliente apenas utiliza o serviço, sem precisar se preocupar com a infraestrutura, atualizações ou manutenção, que são totalmente gerenciadas pelo provedor. Este modelo é mais adequado para empresas que buscam simplicidade e desejam se concentrar exclusivamente no uso do software para suas atividades.

Em resumo, a responsabilidade do cliente diminui à medida que avançamos de IaaS para PaaS e SaaS, oferecendo maior conveniência e menor necessidade de gerenciamento técnico direto, ao mesmo tempo em que se adapta a diferentes necessidades e níveis de expertise técnica.
