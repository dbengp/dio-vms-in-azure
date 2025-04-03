# dio-vms-in-azure

## Demonstração de implantação de máquinas Virtuais na Azure: implantação de uma VM Linux simples no Azure que possa ser acessada pela Internet. A VM executará um servidor Web Nginx básico.

### As máquinas virtuais (VMs) na nuvem representam uma das tecnologias fundamentais da computação sob demanda, oferecendo flexibilidade, escalabilidade e eficiência para empresas e indivíduos. Uma máquina virtual é uma espécie de emulação de um sistema de computador. Em vez de possuir hardware físico, você aluga o poder de computação de um provedor de nuvem. Essas VMs executam sistemas operacionais e aplicativos, sem o overhead de manuntenção de um servidor físico, mas residem em servidores remotos mantidos pelo provedor de nuvem. 

### Benefícios das Máquinas Virtuais na Nuvem:
  - Escalabilidade: Aumente ou diminua os recursos conforme necessário, pagando apenas pelo que você usa.
  - Flexibilidade: Escolha entre uma variedade de sistemas operacionais, configurações de hardware e software.
  - Redução de custos: Elimine a necessidade de investir em hardware caro e manutenção.
  - Acessibilidade: Acesse suas VMs de qualquer lugar com uma conexão à Internet.
  - Confiabilidade: Os provedores de nuvem oferecem infraestrutura robusta e redundante, garantindo alta disponibilidade.

### Casos de uso comuns:
  - Hospedagem de aplicativos e sites: Implante e execute aplicativos da web em servidores virtuais.
  - Desenvolvimento e teste: Crie ambientes de desenvolvimento e teste sob demanda.
  - Análise de dados: Processe grandes volumes de dados usando VMs de alto desempenho.
  - Backup e recuperação de desastres: Armazene dados e aplicativos de backup em VMs para recuperação rápida.
  - Computação de alto desempenho (HPC): Execute simulações complexas e cálculos científicos.

### Considerações importantes:
  - Tipos de instâncias: Os provedores de nuvem oferecem vários tipos de instâncias de VM, cada uma com diferentes configurações de CPU, memória e armazenamento.
  - Preços: Os preços variam dependendo do tipo de instância, sistema operacional e região.
  - Segurança: Implemente medidas de segurança adequadas para proteger suas VMs e dados.
  - As máquinas virtuais na nuvem revolucionaram a maneira como as empresas e os indivíduos utilizam a computação, oferecendo uma solução flexível, escalável e econômica para uma ampla gama de necessidades.

### Pré-requisitos para o exemplo aqui usado:
  - Uma conta do Azure com uma assinatura ativa.
  - Terraform instalado em sua máquina local.
  - Azure CLI instalado e configurado (para autenticação).
    
### Para implantar essa infraestrutura usando o Terraform com CLI é bem simples (por garantia, esteja no mesmo diretório que o arquivo main.tf se encontra):
  - Execute terraform init para inicializar o Terraform e baixar os provedores.
  - Execute terraform plan para visualizar as alterações que serão feitas.
  - Execute terraform apply para criar os recursos no Azure. 
