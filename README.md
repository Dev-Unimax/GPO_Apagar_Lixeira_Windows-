# GPO_Apagar_Lixeira_Windows
Foi elaborada uma GPO no Windows Server para que a lixeira de todos os usuários seja apagada após o desligamento da máquina.

# Etapas para a elaboração da GPO
- Primeiro, verifique se todos os computadores que devem receber a GPO estão no domínio e dentro das pastas corretas no AD (Active Directory).
- Depois, é necessário criar uma GPO na pasta desses computadores e, ao editá-la, navegar até o caminho: Computer Configuration - Polices - Windows Settings - Scripts(Startup/Shutdown) - Shutdown
<img width="643" height="561" alt="image" src="https://github.com/user-attachments/assets/3dd16e2b-c2dd-4c88-ab73-e5dc8bf417f9" />

- Após clicar nas propriedades do script, basta clicar em Adicionar, selecionar o arquivo .bat e aplicar.

# Resumo
Esse procedimento foi utilizado em uma Instituição de Ensino Superior, onde foi aplicado em todas as máquinas dos Laboratórios de Informática.
Seguindo as etapas acima, foi possível realizar a remoção dos arquivos da lixeira, contribuindo para a economia de espaço em máquinas com pouco armazenamento livre e utilizadas por muitos usuários.
