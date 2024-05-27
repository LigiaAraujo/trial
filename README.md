# trial

Material de Apoio

# Git na máquina

	Comandos Básicos do Git

		1. Instalar Git na máquina através do link: https://gitforwindows.org/

		2. Verificar a instalação:
			- Abrir a linha de comandos ou PowerShell
			- Correr o comando git --version
			
		3. Abrir o terminal do VSCode
			- Verificar instalação do Git: git --version
	
		4. Configurar Git (se necessário)
			- git config --global user.name "Nome no Git"
			- git config --global user.email "Email do Git"
	
		5. Iniciar um repositório Git
			- git init nomeRepositório
	
		6. Verificar o status do repositório
			- git status
			
		7. Adicionar ficheiros alterados à fase staging
			- git add filename
			- git add .
			
		8. Commit das alterações	
			- git commit -m "Mensagem de commit"
		
		9. Visualizar histórico de commits
			- git log
		
	
	Trabalhar com Repositórios Remotos
	
		1. Clonar um repositório
			- git clone repository-url
			
		2. Criar branch novo
			- git branch nomeBranch
			
		3. Mudar para um branch 
			-  git checkout branch-name
		
			.  Criar novo branch e mudar para branch criado
				- git checkout -b nomeBranch
				
		4. Enviar alterações para um repositório remoto
			- git push origin branch-name
			
		5. Merge as alterações de um branch noutro (em geral no main)
			- git merge nomeBranch
			
		5. Puxar alterações de um  repositório remoto
			- git pull origin branch-name


# Comandos Adicionais
		
		git config --global --list (para confirmar a ligação à conta)
		
		git fetch nomeBranch (git fetch atualiza o repositório local com as alterações do repositório remoto, mas sem fazer merge no branch local)
		
