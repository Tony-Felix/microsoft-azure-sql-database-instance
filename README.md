# Configuração de Instância Gerenciada de SQL no Microsoft Azure

## Introdução

Neste repositório, documentei o processo de criação de uma instância gerenciada de banco de dados SQL no Microsoft Azure, com base nas aulas e pesquisas que fiz durante o desafio da DIO. O objetivo foi entender e praticar a configuração do ambiente para banco de dados na nuvem, registrando os passos e as principais dicas para facilitar estudos futuros.

---

## Passo a passo que segui para criar a instância gerenciada

1. **Acessar o portal do Azure**  
   Primeiro, entrei no portal do Azure (https://portal.azure.com) usando minha conta.

2. **Buscar o serviço "Instância Gerenciada de SQL"**  
   No menu de serviços, pesquisei por “Instância Gerenciada de SQL” e comecei a criar uma nova instância.

3. **Preencher as informações básicas**  
   Escolhi minha assinatura, criei (ou selecionei) um grupo de recursos, e dei um nome único para a instância. Também escolhi a região onde ela ficaria hospedada.  
   Defini algumas configurações de hardware, como quantidade de vCores e armazenamento, sempre priorizando um setup básico para evitar custos altos.

4. **Configurar autenticação e rede**  
   Criei o usuário administrador com uma senha segura.  
   Configurei as regras de firewall para liberar o acesso do meu IP, assim consegui conectar à instância sem problemas.

5. **Revisar e criar a instância**  
   Depois de revisar tudo, confirmei a criação e aguardei alguns minutos até a instância ficar pronta para uso.

---

## Criando um banco de dados dentro da instância (opcional)

Após a instância estar pronta, fui até a aba de banco de dados para criar um banco dentro da instância. Coloquei o nome desejado e finalizei a criação. Essa etapa não é obrigatória, mas ajuda a entender como funciona o ambiente completo.

---

## Dicas importantes que aprendi

- Sempre verifique se seu IP está liberado no firewall da instância, pois isso impede conexões externas.  
- Use nomes e senhas que sejam fáceis de lembrar, mas difíceis de serem descobertos por outras pessoas.  
- Para fins de estudo, configurei a instância com o plano mais básico possível para evitar custos.  
- O processo todo pode levar alguns minutos, então tenha paciência enquanto a instância é criada no Azure.

