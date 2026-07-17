# SCA
SISTEMA DE GESTÃO DE EXAMES OCUPACIONAIS
sistema criado para suprir a necessidade do dp no acompanhamento
de vencimento dos exames para agendar sua renovação.
Funcionalidades do sistema:
1º - Dashboard -  no Dashboard possui 5 cards (Total de ASOs, Em dia, A vencer, Vencidos, Agendados)
também possui um grafico com os indicadores para cada unidade, e possui 2 gridview sendo um para 
próximos vencimentos e outro para exames vencidos  e por fim possui 2 combobox sendo 1 empresa e o outro loja
para filtrar os resultados.
2º - Cadastros - essa guia é dividia em 2 partes 
  a) Colaboradores
    º - Modelo excel
      Efetua download do modelo para importação de colaboradores em massa
    º - Importar excel
      Importação em massa de colaboradores
    º - Novo colaborador
      Abre um formulario de registro com as seguintes informações:
      Matrícula , Nome Completo, CPF, Nascimento, Sexo, Admissão
      Empresa Registrada, Loja Atuante, Cidade, Função, GHE, Gestor
      Telefone, E-mail, Situação, Desligamento, Observações
  b) Regras de Exames 
    º - Vizualização e cadastro de GHE 
3º -  ASOs
  a) Modelo com ASOs
    Exporta planilha com todas as informações de ASOs cadastrada no sistema
  b) Importar/alterar Excel
    Faz alteração em massa usando a planilha de modelo e inclusão de algum exame
  c) Novo Exame 
    Abre um formulario com as seguintes campos:
    Colaborador, nome do exame , Periodicidade, Data do ultimo ASO, Agendamento
    Realização, Resultado, Clínica, Médico, Caminho do anexo, botao para anexar exame.
4º - Administração - Esta guia é divida em 3 partes
  a) Empresa e envio relatorio semanal email
    º Dados da empresa
        Razão social, Nome Fantasia, CNPJ, Telefone, Endereço, Cidade, UF, CEP, Email e Logo
    º Configuração SMTP - Envio de Relatorio semanal 
        Servidor SMTP, Porta, Usuário SMTP, Senha SMTP, Nome do remetente, E-mail remetente
        Segurança, Ativar envio semanal, Destinatarios
    º Historico de envios
5º Ajuda - Esta guia e dividia em 2 partes 
  a) Sobre 
      Informaçõe sde instalação (usuario conectado, perfil de acesso, ambiente mysql ativo,tecnologia utilizada, banco de dados
      Principais recursos 
  
  
