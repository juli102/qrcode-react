# qrcode-react

Para adicionar um botão na interface para gerar o QR Code dinamicamente. Use a biblioteca qrcode.react para gerar o código QR:

📌 Instale a biblioteca
--------------------------------------------------------------------------------------------------------------------

npm install qrcode.react

--------------------------------------------------------------------------------------------------------------------

📌 Adicione este código na sua tela
--------------------------------------------------------------------------------------------------------------------

import QRCode from "qrcode.react";

const appUrl = "https://seu-dominio.com/boleto-pay"; // Substitua pela URL correta

       <Box mt="md" style={{ textAlign: "center" }}>
         <Text size="sm">Escaneie este QR Code no celular para abrir a câmera</Text>
          <QRCode value={appUrl} size={200} />
       </Box>
-------------------------------------------------------------------------------------------------------------------
       
****** Dica: Se estiver testando localmente, troque "https://seu-dominio.com" por "http://seu-ip-local:3000" para acessar pelo celular na mesma rede.

Passo 2: Acesse no Celular

Agora, basta escanear o QR Code com a câmera do celular e abrir o link. Assim, você conseguirá usar a câmera do próprio dispositivo para escanear o código de barras. 🚀
