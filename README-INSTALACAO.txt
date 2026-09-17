MEUS GASTOS — VERSÃO IPHONE / PWA OFFLINE

Esta versão foi criada para evitar Mac, Xcode e compilação de aplicativo nativo.
Ela funciona como um aplicativo instalado pela Tela de Início do iPhone.

IMPORTANTE
O iPhone não permite instalar um aplicativo a partir de um arquivo ZIP ou HTML simplesmente tocando nele.
Para o modo "Adicionar à Tela de Início" funcionar corretamente e ficar offline, estes arquivos precisam ser publicados uma vez em um endereço HTTPS.
Depois da instalação, o aplicativo funciona sem conexão.

ARQUIVOS QUE DEVEM SER PUBLICADOS JUNTOS
- index.html
- manifest.webmanifest
- sw.js
- pasta icons

INSTALAÇÃO NO IPHONE
1. Publique a pasta em qualquer hospedagem HTTPS de arquivos estáticos.
2. No iPhone, abra o endereço no SAFARI.
3. Toque no botão Compartilhar (quadrado com seta para cima).
4. Escolha "Adicionar à Tela de Início".
5. Confirme "Adicionar".
6. Abra pelo ícone "Meus Gastos" da Tela de Início.
7. Depois da primeira abertura completa, o aplicativo pode ser usado em modo avião.

DADOS
- O banco local usa IndexedDB do Safari/PWA.
- Não existe servidor de dados.
- Investimento é independente e NÃO reduz o saldo disponível.
- Saldo = renda - gastos fixos - gastos variáveis.
- Renda comprometida: até 59% verde; 60% a 79% amarelo; 80% ou mais vermelho.
- Gastos fixos e variáveis são totalmente editáveis.

BACKUP
Use "Exportar backup" dentro do aplicativo e salve o JSON no app Arquivos/iCloud Drive.
Se o aplicativo for removido do iPhone, o armazenamento local pode ser apagado.

MIGRAÇÃO DA VERSÃO WINDOWS
Exporte um backup JSON na versão Windows e use "Importar backup" na versão iPhone.
O formato de dados foi mantido compatível.
