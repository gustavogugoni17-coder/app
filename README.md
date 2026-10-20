# Barbearia Premium — MVP

Projeto inicial para testar um sistema multi-barbearia no navegador e Android (via Expo Web/Android).

## Requisitos
- Node.js LTS
- Expo Go no celular (opcional)
- Windows PowerShell

## Instalar
No PowerShell, dentro desta pasta:
```powershell
npm install
npx expo start
```
- Pressione `w` para abrir a versão web.
- Escaneie o QR Code com Expo Go para testar no Android.

## O que esta primeira versão inclui
- Tela de demonstração com tema preto e dourado.
- Escolha entre barbearias de exemplo.
- Lista de serviços e preços.
- Formulário de agendamento demonstrativo.
- Painel administrativo local com agendamentos criados nesta sessão.

## Importante
Esta é uma demonstração local. Os dados ficam apenas no estado do aplicativo e não são compartilhados entre dispositivos. Ainda não inclui autenticação real, banco online, pagamentos ou envio automático de WhatsApp. Para produção multi-barbearia, é necessário conectar uma API, PostgreSQL, autenticação e um provedor oficial de WhatsApp.
