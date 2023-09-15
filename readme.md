<h1>Transcrição de Vídeo com Melhorias usando Prompt</h1>
Este é o repositório da aplicação que permite a transcrição de vídeos e utiliza prompts para melhorias. Através do front-end, os usuários podem fazer o upload de um vídeo e obter uma transcrição textual de todo o conteúdo falado no vídeo.

<h1>Funcionalidades</h1>
Envio de vídeo: Os usuários podem fazer o upload de um arquivo de vídeo no formato suportado pela aplicação.
Transcrição: A aplicação utiliza técnicas de processamento de linguagem natural para transcrever todo o conteúdo falado no vídeo em texto.
Melhorias com prompts: Para aprimorar a qualidade da transcrição, a aplicação utiliza prompts, que são sugestões de texto fornecidas aos modelos de linguagem para ajudar a obter resultados mais precisos e coerentes.
Tecnologias Utilizadas
Front-end: O front-end da aplicação foi desenvolvido utilizando HTML, CSS e JavaScript.
Back-end: O back-end é construído com o uso de uma API de processamento de linguagem natural, como a OpenAI GPT-3 ou uma versão mais recente, caso disponível.
Armazenamento: Os vídeos enviados pelos usuários são armazenados temporariamente no servidor para processamento e em seguida removidos para garantir a privacidade dos dados.
Configuração
Para executar a aplicação em sua máquina local, siga as etapas abaixo:

<h1>Clone este repositório para o seu diretório local.</h1>
<h3>front-end:</h3>
- instale as dependências usando o <code>npm i</code>
<br><br>
<h3>back-end:</h3>
- instale as dependências usando o <code>npm i</code><br>
- configure sua chave da API da OpenAI no .env no lugar de <code>"openai-api-key-here"</code><br>
- faça a migration com o código <code>npx prisma migrate dev</code><br>
- faça o seed com  o código <code>npx prisma db seed</code><br>

<h1>Aviso Legal.</h1>
Esta aplicação é fornecida sem garantias de qualquer tipo, expressas ou implícitas. Os desenvolvedores não se responsabilizam por quaisquer danos diretos ou indiretos decorrentes do uso desta aplicação.