# App de Detecção de Movimentos Suspeitos e Furtos

## 1. Como iniciar o aplicativo?


### Passos:

1. **Faça download do app**: https://mega.nz/folder/jQpw1RAI#TjkRRk_2Q8OSwQ0Ka0LK9w
2. Extraia o .zip
3. Crie um atalho para a área de trabalho se quiser.

4. **Clique no main.exe**: Este é o arquivo executável do aplicativo.
5. **Nova Sessão**: Dentro do aplicativo, clique no botão **"Nova sessão +"** para começar.

## 2. Como preencher o formulário?

### Informações necessárias:
Para preencher os dados, obtenha as seguintes informações do [Bot de Telegram](https://t.me/visivel_bot):

1. **ID**:
   - Digite "ID" na conversa do bot.
   - O bot retornará um código único.
   - Copie e cole este código no campo correspondente no aplicativo.
2. **Email**:
   - Insira seu email de contato padrão.
3. **URL**:
   - Digite "IP" na conversa do bot.
   - O bot retornará uma URL.
   - Copie e cole esta URL no campo correspondente no aplicativo.
4. **API Key**:
   - Utilize a chave padrão para o MVP: **4cda6177-3d73-4bb4-9a1a-cc936bf789a3**.
5. **Sessão**:
   - Defina a origem do vídeo:
     - Índices (0, 1, 2, ...) para webcams.
     - Caminho para um vídeo (ex: caminho/para/video.mp4).
     - IP público da câmera (ex: http://000.000.00.0:4747/video).

## 3. Como rodar as sessões?

### Observações importantes:
- **Limite de Sessões**: Para este MVP, apenas duas sessões podem ser conectadas simultaneamente.

### Instruções:
1. **Iniciar Sessão**:
   - Após preencher o formulário, clique no botão **"Iniciar Sessão"**.
   - As telas de vídeo das câmeras com as detecções serão exibidas.
2. **Encerrar Sessão**:
   - Para encerrar uma sessão, acesse a tela da sessão e pressione a tecla **"q"**.

### Alertas de Detecção:
- Se movimentos suspeitos forem detectados, o bot enviará um vídeo de 5 segundos com as detecções:
  - Para o seu chat privado no Telegram.
  - Para o seu email de contato.

## 4. Perguntas Frequentes

### P: O que fazer se eu não receber o ID ou URL do bot?
- R: Verifique se você está digitando os comandos corretos ("ID" e "IP"). Caso persista, reinicie a conversa com o bot ou entre em contato com o suporte.

### P: Posso usar mais de duas câmeras ou vídeos?
- R: Não, este MVP permite a conexão de no máximo duas sessões simultâneas.

### P: Como faço para alterar a API Key?
- R: Para este MVP, a API Key é fixa e padrão para todos os usuários. Em futuras versões, será possível configurar uma chave personalizada.

### P: Como receberei os alertas de detecção?
- R: Os alertas serão enviados automaticamente para o seu chat privado no Telegram e para o email cadastrado.

### P: Posso usar o aplicativo com câmeras IP de diferentes marcas?
- R: Sim, desde que você tenha o IP público e o formato de vídeo suportado, o aplicativo deve funcionar com a maioria das câmeras IP.

Se você tiver outras dúvidas ou problemas, por favor, entre em contato com o suporte técnico através do email fornecido ou pelo bot de Telegram.

### P: Preenchi o formulário e cliquei no "Iniciar Sessão", mas nada acontece. O que devo fazer?
- R: Verifique as informações do formulário. Espere alguns minutos e tente novamente. Compartilhe o arquivo **app.log** com o email de suporte para tomarmos uma providência.

Se você tiver outras dúvidas ou problemas, por favor, entre em contato com o suporte técnico através do email fornecido ou pelo bot de Telegram.

**suporte**: shoppfy1@gmail.com
