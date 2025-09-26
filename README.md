# PAM_APK_Delivery

<div align="center">

[![React Native](https://img.shields.io/badge/React%20Native-0.72-61DAFB?style=for-the-badge&logo=react)](https://reactnative.dev/)
[![Expo](https://img.shields.io/badge/Expo-49.0-000020?style=for-the-badge&logo=expo)](https://expo.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)

**Aplicativo movel nativo para a Plataforma PAM**

[Demo](#demo) â€¢ [Documentacao](#documentacao) â€¢ [Instalacao](#instalacao) â€¢ [Contribuicao](#contribuicao)

</div>

---

## Sobre o Projeto

Aplicativo movel para entregadores e tecnicos da plataforma PAM. Interface otimizada para profissionais em campo, com funcionalidades de gerenciamento de rotas, atualizacao de status de pedidos, comunicacao com clientes, relatorios de campo, navegacao GPS e otimizacao de entregas. Desenvolvido com React Native e Expo.

### Principais Funcionalidades

- **Navegacao GPS**: Rotas otimizadas e navegacao turn-by-turn
- **Lista de Pedidos**: Gestao eficiente de tarefas diarias
- **Status em Tempo Real**: Atualizacoes instantaneas
- **Relatorios de Campo**: Fotos e documentacao de servicos
- **Chat com Clientes**: Comunicacao direta e eficiente
- **Controle de Tempo**: Registro de horas trabalhadas
- **Performance**: Metricas pessoais e metas
- **Notificacoes**: Alertas de novos pedidos
- **Modo Offline**: Funcionalidades basicas sem internet
- **Seguranca**: Autenticacao biometrica

## Tecnologias

### Mobile Framework
- **[React Native](https://reactnative.dev/)** - Framework para desenvolvimento mobile
- **[Expo](https://expo.dev/)** - Plataforma de desenvolvimento
- **[TypeScript](https://www.typescriptlang.org/)** - Tipagem estatica

### Navegacao e Estado
- **[React Navigation](https://reactnavigation.org/)** - Navegacao entre telas
- **[Redux Toolkit](https://redux-toolkit.js.org/)** - Gerenciamento de estado

## Pre-requisitos

- **[Node.js 18+](https://nodejs.org/)** (versao LTS recomendada)
- **[Expo CLI](https://docs.expo.dev/get-started/installation/)** - Ferramenta de desenvolvimento
- **[Git](https://git-scm.com/)** - Controle de versao

## Instalacao

### 1. Clone o Repositorio

`ash
git clone https://github.com/EmmanuelSMenezes/PAM_APK_Delivery.git
cd PAM_APK_Delivery
`

### 2. Instalar Dependencias

`ash
npm install
# ou
yarn install
`

### 3. Configuracao do Ambiente

`ash
cp .env.example .env
`

### 4. Executar em Desenvolvimento

`ash
expo start
`

### 5. Executar no Dispositivo

#### Expo Go (Recomendado)
1. Instale o **Expo Go** no seu dispositivo
2. Escaneie o QR code exibido no terminal

#### Simuladores/Emuladores
`ash
# Android
expo start --android

# iOS (apenas macOS)
expo start --ios
`

## Build e Deploy

### Build de Desenvolvimento

`ash
# Android APK
eas build --platform android --profile development

# iOS IPA
eas build --platform ios --profile development
`

### Build de Producao

`ash
# Android (Google Play)
eas build --platform android --profile production

# iOS (App Store)
eas build --platform ios --profile production
`

## Testes

`ash
npm test
`

## Contribuicao

1. Fork o projeto
2. Crie uma branch (git checkout -b feature/nova-funcionalidade)
3. Commit suas mudancas (git commit -m 'feat: nova funcionalidade')
4. Push para a branch (git push origin feature/nova-funcionalidade)
5. Abra um Pull Request

## Licenca

Este projeto esta sob a licenca **MIT**. Veja [LICENSE](LICENSE) para mais detalhes.

## Suporte

- **Email**: suporte@pam.com
- **Issues**: [GitHub Issues](https://github.com/EmmanuelSMenezes/PAM_APK_Delivery/issues)

---

<div align="center">

**PAM - Plataforma de Agendamento de Manutencao**  
*Desenvolvido com amor pela equipe PAM*

</div>