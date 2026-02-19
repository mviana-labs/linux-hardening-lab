# Hardening em Linux: Proteção de SSH, Firewall e Permissões
Laboratório prático focado na aplicação de técnicas de Hardening em ambientes Linux, simulando boas práticas de segurança sob a ótica do Blue Team.

## Objetivo
Aplicar medidas essenciais de Hardening para reduzir a superfície de ataque de um servidor Linux, fortalecendo o acesso remoto, o controle de rede e as permissões de arquivos sensíveis.

## Ferramentas utilizadas
- Linux (Ubuntu Server e Kali Linux)
- OpenSSH
- UFW
- unattended-upgrades

## Atividades realizadas
- Desativação do login do usuário root via SSH
- Restrição de acesso ao SSH por IP com UFW
- Atualização do sistema e aplicação de patches de segurança
- Habilitação de atualizações automáticas
- Revisão e ajuste de permissões sensíveis (/etc/shadow, /etc/passwd, ~/.bash_history)

## Artigo relacionado
📄 Medium: https://medium.com/@matheusgabrielcorreaviana/hardening-em-linux-implementando-controles-essenciais-de-segurança-ab56864a13a1
