# Executando-ataques-com-medusa
Executando ataque de brute-force e com medeusa para exploração de vulnerabilidades

# Desafio de Brute Force e Enumeração: Análise de Vulnerabilidades de Senha

## 1. Técnicas e Ferramentas de Teste (Ofensiva)

Neste projeto, simulei ataques de Brute Force e Dictionary Attack contra serviços de rede e formulários de login.

Ferramenta Utilizada:
    * **Medusa:** Usada para simular combinações entre usuários e senhas em formulários de login e sistemas web.

   Ferramentas que foram vistas e explicadas suas funcionalidades: 
    Hydra, Ncrack, Patator: Exploradas para entender a aplicação de força bruta em diferentes protocolos.
    John the Ripper: Aprendi sobre sua função no cracking de hashes de senhas.
    WPScan: Utilizada para identificar vulnerabilidades específicas em ambientes WordPress.

Conclusão: Essas ferramentas são essenciais para testar a robustez das políticas de senha de um sistema.

## 2. Vulnerabilidades Comuns Identificadas

A exploração da vulnerabilidade de sistemas é frequentemente facilitada por falhas básicas, como:

Senhas Fracas: A principal vulnerabilidade explorada em ataques de força bruta.
Usuários Padrão: O uso de credenciais de fábrica que não foram alteradas.
Vazamentos de Arquivos: Exposição de informações que fornecem *wordlists* ou dados de enumeração.

## 3. Mitigação e Defesa (Melhores Práticas)

Para proteger um sistema contra esses ataques, é crucial que, além de uma boa segurança, os usuários adotem boas práticas.

Conscientização: É fundamental que as pessoas entendam a importância de:
  Senhas Fortes: Combinando caracteres complexos e únicos.
  Verificação em Duas Etapas (2FA): Adicionando uma camada extra de segurança.
  Bloqueio de IP/Conta: Implementar sistemas que bloqueiam IPs após um número limitado de tentativas de acesso falhas (*Rate Limiting*).
  Mandar o sistema atualizado, não passar e não deixas senhas amostras para qualquer pessoa.
  
