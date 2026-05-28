# EcoContador - Recicle e Ganhe

Um aplicativo web mobile-first inovador que incentiva a reciclagem e recompensa usuários com moeda ecológica (Ecomoedas).

## 🌱 Sobre o Projeto

EcoContador é uma solução sustentável que:
- ✅ Permite que usuários criem contas e gerenciem perfil
- 📍 Localize lixeiras seletivas mais próximas com GPS
- 📸 Escaneie e fotografe resíduos para ganhar pontos
- 💰 Acumule Ecomoedas através de ações ecológicas
- 🎨 Interface moderna com design glassmorphism
- 🌍 Suporte bilíngue (Português Brasileiro)

## 🚀 Funcionalidades

### Autenticação
- Login com Google (OAuth 2.0)
- Criar conta nativa com celular
- Perfil personalizável com foto e nome

### Dashboard Principal
- Contador visual de Ecomoedas
- Botão rápido para ativar localização
- Acesso à câmera para escanear resíduos
- Loja de troca (em desenvolvimento)
- Customização de fundo do aplicativo

### Localização
- Integração com Geolocation API
- Busca de ecopontos próximos
- Suporte para modo offline

### Câmera
- Captura de fotos via câmera do dispositivo
- Fallback para modo simulador em ambientes sem suporte HTTPS
- Recompensa automática ao registrar resído

## 📋 Requisitos

- Navegador moderno com suporte a:
  - MediaDevices API (câmera)
  - Geolocation API (localização)
  - FileReader API (upload de imagens)
  - CSS Grid & Flexbox
  - Backdrop Filter (Chrome 76+, Safari 9+, Firefox 103+)

## 💻 Como Usar

### Opção 1: Abrir Diretamente
```bash
# Clone o repositório
git clone https://github.com/starkinandys-ui/Ecocontador.git
cd Ecocontador

# Abra o arquivo index.html no navegador
open index.html  # macOS
start index.html # Windows
# Ou arraste para o navegador
