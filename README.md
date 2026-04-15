# Documenta-o-em-Duplas
Atividade Prática: Instalação Linux &amp; Documentação


As imagens documentam a preparação completa de um ambiente virtual para o Linux Mint. Elas comprovam a definição correta dos recursos de hardware (processamento e memória) e a organização dos dispositivos de armazenamento, com a média de instalação (ISO) e o disco virtual prontos para iniciar o processo de instalação do sistema operativo



1-
<img width="954" height="539" alt="image" src="https://github.com/user-attachments/assets/09ef9b07-4708-40eb-82e8-704344c2340a" />
Configuração inicial de nome e recursos da máquina.
A imagem apresenta a interface do Oracle VM VirtualBox, um software de virtualização, configurado em português. Ela exibe os detalhes técnicos de uma máquina virtual (VM) específica.




2-
<img width="784" height="487" alt="{9AEBC470-4D0A-4AED-8077-FD3105FDB252}" src="https://github.com/user-attachments/assets/d05b4fd7-de2c-4b7d-8c57-54600880a662" />
Print da aba de armazenamento com a ISO selecionada
A imagem detalha a seção de Armazenamento das configurações da máquina virtual no VirtualBox, exibindo uma Controladora IDE com a imagem ISO de instalação (linuxmint-22.3-cinnamon-64bit.iso) montada como disco óptico e uma Controladora SATA contendo o disco rígido virtual (Linux-mint.vdi). Em resumo, a tela mostra que o ambiente está devidamente preparado para iniciar o processo de instalação do sistema operacional Linux Mint, conectando tanto a mídia de instalação quanto o espaço de armazenamento onde o sistema será gravado





3-
<img width="1120" height="759" alt="{A29BE94C-150A-4D2E-91E6-BE8550F93503}" src="https://github.com/user-attachments/assets/eeabb970-a014-4c7b-89c4-ef1ebd780e2d" />

A imagem mostra a tela de criação de usuário do instalador do Linux Mint, intitulada "Quem é você?". O sistema já foi configurado em português, com o fuso horário de São Paulo e o layout de teclado definidos em etapas anteriores.

Nesta tela, os campos estão preenchidos da seguinte forma:

Nome: NY.MA

Nome do computador: nyma-VirtualBox

Nome de usuário: nyma

Segurança: Uma senha foi definida e a opção "Solicitar minha senha para entrar" está selecionada para garantir a proteção dos dados.






<img width="1119" height="755" alt="{DFA2BF0A-3B58-45B5-A582-DCA0E97ADACB}" src="https://github.com/user-attachments/assets/c886b489-b15d-4a69-adf3-d860db1ed14c" />
Instalação do Sistema em carregamento.



<img width="1110" height="695" alt="{942C0507-1B41-4AA0-AB70-072CC8E76154}" src="https://github.com/user-attachments/assets/b0774db9-4514-4341-afe0-36624dbd1b0b" />
Carregamento do Sistema Concluído.






4-
<img width="612" height="448" alt="image" src="https://github.com/user-attachments/assets/402cfce7-0e1e-4fba-8655-46c873b0baa6" />
<img width="612" height="448" alt="{DBB85123-8244-43B3-B561-C36286BCF07A}" src="https://github.com/user-attachments/assets/c528c03a-cf28-4460-a367-383392692cc2" />
<img width="627" height="456" alt="image" src="https://github.com/user-attachments/assets/d65de9bd-cd59-4f0c-af09-643d3598de85" />
 Print do Desktop do Linux rodando em tela cheia no VirtualBox
As imagens apresentam o resultado final da instalação, exibindo o desktop do Linux Mint totalmente operacional após o reboot. A sequência demonstra o sistema em pleno funcionamento, com a rede conectada e o usuário já interagindo com o ambiente ao instalar e navegar no Google Chrome, o que comprova que a máquina virtual foi configurada com sucesso e está pronta para uso imediato.




obs: 
 Comandos Úteis (Pós-Instalação)
Abra o terminal (`Ctrl+Alt+T`) e execute:

```bash
# Atualizar a lista de repositórios
sudo apt update

# Instalar as atualizações do sistema
sudo apt upgrade -y





Feito por Mariana Archanjo e Nycolas Fernando
