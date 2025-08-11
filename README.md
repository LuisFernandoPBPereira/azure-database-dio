<h1 align="center">Instância de Banco de Dados Azure</h1>

## Criando Banco de Dados

Em `Criar Banco de Dados SQL` devemos preencher alguns campos, como:

- Nome do Banco de Dados
- Servidor
- Deseja usar pool elástico SQL?
- Ambiente de carga de trabalho
- Redundância do armazenamento de backup (relacionado ao tema de SLA, escolha dependendo da preferência de uptime do seu serviço)

>[!IMPORTANT]
>Antes de preenchermos todos os campos, precisamos criar um novo servidor de banco de dados caso não possua;

## Criando Servidor

Em `Criar Servidor do Banco de Dados SQL`, precisamos definir:

- Nome do servidor
- Localização
- Autenticação

>[!NOTE]
>Caso escolha uma opção que tenha autenticação com Microsoft Entra, é preciso definir um perfil administrador

Por fim, clique em "Revisar + criar"
