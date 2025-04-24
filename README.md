<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=vimeo" alt="DIO - Project"></a>
<a href="https://en.wikipedia.org/wiki/Artificial_intelligence"><img src="https://img.shields.io/badge/AI-Project-FED564?logo=openai" alt="AI - Project"></a>
<a href="https://portal.azure.com/" title="Vá para a página inicial do Portal"><img src="https://custom-icon-badges.demolab.com/badge/Microsoft%20Azure-0089D6?logo=msazure&logoColor=white)](#)"></a>
<a href="https://www.sublimetext.com/" title="Vá para a página inicial do Editor"><img src="https://img.shields.io/badge/Sublime%20Text-%23575757.svg?logo=sublime-text&logoColor=important"></a>


# Resumo sobre Computação em Nuvem no Azure

## 1. O que é Computação em Nuvem?

Forneci serviços de computação pela Internet, habilitando inovações mais rápidas, recursos flexíveis e economias de escala.

**Vantagens**:  
- Escalabilidade  
- Redução de custos  
- Alta disponibilidade  
- Segurança gerenciada  

---

## 2. Modelo de Responsabilidade Compartilhada

Define as obrigações do provedor de nuvem e do cliente:

- **Azure (Provedor)**:  
  - Gerencia a infraestrutura física  
  - Rede e virtualização
  
- **Cliente**:  
  - Responsável por dados  
  - Controle de acesso  
  - Sistemas operacionais  
  - Configurações de segurança

---

## 3. Modelos de Nuvem

### Nuvem Pública

- Infraestrutura compartilhada entre múltiplos usuários e organizações, operada por um provedor terceirizado.

**Características:**
- Recursos alocados dinamicamente.
- Custos baseados em uso.
- Alta escalabilidade e disponibilidade.
- Gerenciamento pelo provedor.

**Casos de Uso:**
- Startups ou empresas com orçamento limitado.
- Aplicações web com tráfego variável.
- Desenvolvimento e teste de software (ambiente escalável).
- Big Data e análise de dados (processamento sob demanda).

### Nuvem Privada

- Infraestrutura dedicada a uma única organização, hospedada on-premises é instalada e gerenciada fisicamente dentro das instalações da própria empresa.

**Características:**
- Controle total sobre segurança e personalização.
- Ideal para dados sensíveis ou regulamentados.
- Custos mais elevados (hardware e manutenção).

**Casos de Uso:**
- Setores regulamentados (saúde, governo, financeiro) que exigem conformidade 
- Empresas com dados críticos (ex.: propriedade intelectual).
- Cargas de trabalho previsíveis e estáveis.

### Nuvem Híbrida

- Combinação de nuvens públicas e privadas interconectadas, permitindo compartilhamento de dados e aplicações entre elas.

**Características:**
- Flexibilidade para mover cargas de trabalho entre ambientes.
- Balanceamento entre custo, segurança e desempenho.
- Requer integração eficiente como VPNs e APIs.

**Casos de Uso:**
- Empresas em transição para a nuvem (migração gradual).
- Aplicações com picos sazonais (ex.: varejo no Natal, usando nuvem pública para escalar).
- Disaster Recovery (dados críticos em nuvem privada, backup na pública).
- Separação de cargas sensíveis (dados confidenciais em privada e front-end na pública).

### Modelo Baseado no Consumo (Pay-as-you-go)

- Os usuários pagam apenas pelos recursos e serviços que realmente utilizam.
- Baseado em métricas como: tempo de uso, quantidade de armazenamento, volume de dados transferidos ou número de chamadas de API.

**Vantagens:**
- Flexibilidade.
- Escala os recursos conforme a demanda.
- Evita custos desnecessários.

---

## Comparação dos Modelos de Preços de Nuvem

### Preço Baseado no Consumo (Pay-as-you-go)
- **Descrição:** Pagamento conforme o uso, sem taxas fixas.  
- **Vantagens:** Flexibilidade, custo controlado, ideal para startups e projetos temporários.  
- **Desvantagens:** Pode resultar em custos inesperados se não monitorado adequadamente.

### Preço Fixo (Flat Rate)
- **Descrição:** Taxa fixa mensal ou anual por um conjunto de recursos.  
- **Vantagens:** Previsibilidade nos custos, fácil planejamento orçamentário.  
- **Desvantagens:** Pode não ser econômico se nem todos os recursos forem utilizados.

### Preço por Camadas (Tiered Pricing)
- **Descrição:** Preços estruturados em camadas conforme níveis de uso.  
- **Vantagens:** Incentiva uso eficiente e pode ser mais econômico para grandes volumes de utilização.  
- **Desvantagens:** Complexidade para entender e prever custos com flutuações.

### Preço Reservado (Reserved Pricing)
- **Descrição:** Pagamento antecipado por um período (1 ou 3 anos) em troca de descontos significativos.  
- **Vantagens:** Economia para cargas de trabalho estáveis e previsíveis.  
- **Desvantagens:** Compromisso a longo prazo com riscos caso as necessidades mudem.

---

## 4. Custo de Capital (CapEx) vs. Custo Operacional (OpEx)

- **CapEx:**  
  - Investimento inicial em hardware/data centers (alto custo fixo).

- **OpEx:**  
  - Gasto contínuo com serviços sob demanda (ex.: pagamento por uso no Azure).

**Vantagem da Nuvem:**  
- Elimina o alto CapEx, transformando-o em um OpEx escalável.

---

## Benefícios da Nuvem Azure

### 1. Alta Disponibilidade e Escalabilidade
- **Alta Disponibilidade:**
  - SLAs com até 99,99% de uptime.
  - Redundância em várias regiões e zonas de disponibilidade.
  - Recuperação rápida com Azure Site Recovery e backups automatizados.

- **Escalabilidade:**
  - **Vertical (Scale-up):** Aumento de recursos (CPU, memória) em uma única VM.
  - **Horizontal (Scale-out):** Adição de instâncias (ex.: Azure Kubernetes Service, Azure App Service).
  - **Escalocação Automática:** Azure Autoscale ajusta a capacidade conforme a demanda.

### 2. Confiabilidade e Previsibilidade
- **Confiabilidade:**
  - Infraestrutura global em mais de 60 regiões.
  - Monitoramento contínuo com Azure Monitor e Azure Service Health.

- **Previsibilidade:**
  - Modelo pay-as-you-go para controle dos custos.
  - Ferramentas como Azure Cost Management para otimização de gastos.
  - Desempenho consistente com SLAs para serviços críticos.

### 3. Segurança e Governança
- **Segurança:**
  - Proteção multicamada com Azure Security Center e Microsoft Defender for Cloud.
  - Criptografia de dados em repouso e em trânsito.
  - Controle de acesso com Azure Active Directory (Azure AD) e autenticação multifator (MFA).

- **Governança:**
  - Conformidade com normas como GDPR, ISO 27001, HIPAA, entre outras.
  - Utilização do Azure Policy e Azure Blueprints para aplicação de regras de conformidade.
  - Auditoria e logs centralizados via Azure Monitor e Azure Sentinel.

### 4. Capacidade de Gerenciamento

- **Automação e DevOps:**
  - Azure DevOps e GitHub Actions para CI/CD.
  - Azure Automation para scripts e gerenciamento de infraestrutura como código (IaC).

- **Gerenciamento Unificado:**
  - Administração centralizada pelo Azure Portal e Azure CLI.
  - Azure Arc para gerenciar recursos híbridos e multi-cloud.
  - Azure Resource Manager (ARM) para implantação e organização de recursos.

---

## Conclusão

O Azure oferece uma abordagem robusta para computação em nuvem, permitindo que empresas melhorem a escalabilidade e a segurança de suas operações. Com um modelo de responsabilidade compartilhada, a plataforma permite transformar investimentos iniciais elevados em custos operacionais flexíveis, ajustando-se à demanda do negócio. A alta disponibilidade, segurança reforçada e ferramentas avançadas de gerenciamento destacam o Azure como uma opção estratégica para organizações que procuram eficiência e inovação em suas infraestruturas de TI.
