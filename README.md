# Service Desk Tool

![Version](https://img.shields.io/badge/version-2.0.0-blue.svg)
![PowerShell](https://img.shields.io/badge/powershell-5.1+-green.svg)
![Windows](https://img.shields.io/badge/windows-10/11-orange.svg)
![License](https://img.shields.io/badge/license-Proprietary-red.svg)

> Ferramenta de automação para suporte técnico desenvolvida para a equipe de Service Desk do Hospital Nipo Brasileiro

---

## 📋 Índice

- [Sobre a Ferramenta](#sobre-a-ferramenta)
- [Menu Principal](#menu-principal)
- [Funcionalidades](#funcionalidades)
- [Como Usar](#como-usar)
- [Segurança](#segurança)
- [Requisitos](#requisitos)
- [Instalação](#instalação)
- [Suporte](#suporte)

---

## 🖥️ Sobre a Ferramenta

O **Service Desk Tool** é uma aplicação PowerShell desenvolvida para a equipe de Service Desk do Hospital Nipo Brasileiro para automatizar tarefas rotineiras do Service Desk. A ferramenta centraliza instalações, configurações e manutenção de equipamentos em um único lugar.

### Objetivo

- **Automatizar** instalação de softwares padrão
- **Centralizar** manuais e documentação
- **Padronizar** configurações de equipamentos
- **Agilizar** o atendimento do Service Desk
- **Reduzir** erros operacionais

---

## 📁 Menu Principal

```
+ - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - +
                  DESENVOLVIDO PELA EQUIPE DE INFRAESTRUTURA
+ - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - +

                         00. Mapa do sistema
                         01. Manuais - Base de apoio
                         02. Refazer elevação de usuário
                         03. Instalar programas padrão
                         04. Programas essenciais
                         05. Programas opcionais
                         06. Drivers scan/printer
                         07. Configurações
                         08. Lista de softwares
                         09. Copiar pasta de Softwares

                         99. Sair
```

---

## ✨ Funcionalidades

### 📚 01. Manuais - Base de Apoio
| Opção | Manual | Descrição |
|-------|--------|-----------|
| 01 | Avaya | Sistema de telefonia |
| 02 | Unity | Sistema Unity |
| 03 | BIP | Configuração de dispositivos de áudio |
| 04 | Zebra ZT230 | Impressora de etiquetas |
| 05 | VPN | Guia de conexão VPN |
| 06 | Inventário | Processo de inventário |
| 07 | Aptron | Sistema de portaria |
| 08 | Argox | Impressora Argox |
| 09 | CWM e Sinapse | Sistemas médicos |
| 10 | CIHA | Sistema de internação |
| 11 | Simpro | Sistema contábil |
| 12 | TISS | Padrão TISS |
| 13 | Mapa HNB | Layout do hospital |
| 14 | Criação de ISO | Imagens ISO |
| 15 | Instalação padrão | Setup de máquina |
| 16 | Backup | Guia de backup |
| 17 | Encaminhamento de chamada | Desvio de ligações |
| 18 | MV Palm | Sistema palm |
| 19 | Pulseiras | Impressora de pulseiras |
| 20 | ConnectBit/Fleury | Sistema Fleury |
| 21 | Welch Allyn | Equipamentos médicos |
| 22 | VECWIN | Sistema de prontuário |
| 23 | Madis Biometric | Leitor biométrico |
| 24 | SCNES | Sistema CNES |
| 25 | Criação de usuários | Procedimento de criação |
| 26 | Connect | Sistema Connect |
| 27 | CapturaBio | Leitor biométrico |

### 💻 03. Instalar Programas Padrão
- Instala MV, Kaspersky e realiza inventário automaticamente
- Configuração completa para novas máquinas

### ⭐ 04. Programas Essenciais
| Opção | Programa | Descrição |
|-------|----------|-----------|
| 01 | MV | Sistema principal MV Soul (32/64 bits) |
| 02 | Avaya | Telefonia e comunicação |
| 03 | Kaspersky | Antivírus corporativo |
| 04 | Visualizador de fotos | Visualizador padrão Win11 |
| 05 | Chrome | Navegador Google Chrome |
| 06 | Adobe | Leitor de PDF |
| 07 | Simple Sticky Notes | Bloco de notas adesivas |
| 08 | Teams | Microsoft Teams |

#### Submenus Avaya
- **Avaya Agent**: HNB / Enkyo / Nenhum
- **Avaya Dashboard**: HNB / Enkyo / Nenhum

### 🎯 05. Programas Opcionais
| Opção | Programa | Descrição |
|-------|----------|-----------|
| 01 | VPN Forticlient | Cliente VPN |
| 02 | Office | Microsoft Office 365 / LibreOffice |
| 03 | Módulos de banco | Bradesco / Banco do Brasil |
| 04 | Corel Draw | 2017 / X6 / Cloud |
| 05 | 7Zip | Compactador de arquivos |
| 06 | Zoom | Reuniões virtuais |
| 07 | Validador TISS | Validador do padrão TISS |
| 08 | Java | Ambiente de execução |
| 09 | Bizagi | Modelagem de processos |
| 10 | CIHA | Controle de internação |
| 11 | Aptron | Portaria e controle de acesso |
| 12 | Dietoterapia | Controle dietético |
| 13 | Madis Biometric | Leitor biométrico (x32/x64) |
| 14 | Leitor CapturaBio | Leitor biométrico (Win10/Win11) |
| 15 | Welch Allyn | Equipamentos médicos |
| 16 | Software Crachas | Emissão de crachás |
| 17 | SERPRO | Certificação digital |
| 18 | Connect | Sistema de conectividade |
| 19 | Unity | Sistema de laboratório |
| 20 | Etiquetas Fleury | Impressão de etiquetas |
| 21 | RM Smart Client | Cliente RM |

### 🖨️ 06. Drivers Scan/Printer
| Opção | Categoria | Modelos |
|-------|-----------|---------|
| 01 | Impressora de etiquetas | Argox, Zebra |
| 02 | Impressora de pulseiras | TSC, GP |
| 03 | Scanners | ES-50, DR-C225 II, Kodak I1100, DR-C230 |
| 04 | Impressora Totem | Diebold, Bematech |

### ⚙️ 07. Configurações
| Opção | Funcionalidade | Descrição |
|-------|----------------|-----------|
| 01 | Inventariar máquina | Coleta informações do hardware |
| 02 | Configs TV e Totem | Painéis, totens e displays |
| 03 | Resetar perfil de usuário | Remove e recria perfil corrompido |
| 04 | Reconfigurar LPTs Zebra | Configura portas LPT |
| 05 | Ativar/Desativar WSUS | Controla atualizações |
| 06 | Ativar/Desativar Serviços | Gerencia serviços do Windows |
| 07 | Acesso remoto pelo RDS | Remote Desktop Shadow |

#### Submenu 07.02 - Configs TV e Totem
| Opção | Configuração |
|-------|--------------|
| 01 | Painel de chamada |
| 02 | Painel de indicador |
| 03 | Totem |
| 04 | Config sem MV |
| 05 | Perfil auditório |
| 06 | TV Refeitório |
| 07 | Desfazer configurações |

#### Submenu 07.07 - RDS
| Opção | Descrição |
|-------|-----------|
| 01 | Painel/totem (conexão individual) |
| 02 | Paineis/totens em massa (por setor) |

### 📋 08. Lista de Softwares
- Abre uma lista em HTML com todas as pastas de software disponíveis

### 📂 09. Copiar Pasta de Softwares
- Copie qualquer pasta de softwares usando apenas o nome
- Destino: `C:\Temp`

### 🔐 10. Atualizar Autologon
- Configura login automático para usuários específicos:
  - `hnb.painel` - Painéis
  - `hnb.totem` - Totens
  - `auditorio` - Auditório
  - `tv.refeitorio` - TV do refeitório

---

## 🚀 Como Usar

### Execução do Script

```powershell
# 1. Execute como administrador
.\menu.ps1

# 2. Selecione uma opção do menu
Escolha uma opcao: 04

# 3. Navegue pelos submenus
Qual programa instalar: 01
Qual a estrutura do Windows? 02
```

### Exemplo - Instalar MV

```powershell
# 1. Menu Principal -> Opção 04 (Programas Essenciais)
# 2. Selecione 01 (Instalar MV)
# 3. Escolha a arquitetura:
#    01 - 32 bits
#    02 - 64 bits
# 4. Aguarde a instalação automática
```

### Exemplo - Acesso RDS em Massa

```powershell
# 1. Menu Principal -> Opção 07 (Configurações)
# 2. Selecione 07 (Acesso remoto pelo RDS)
# 3. Escolha:
#    01 - Conexão individual
#    02 - Conexão em massa por setor
# 4. Para conexão em massa, selecione o setor desejado
```

---

## 🔒 Segurança

### Elevação de Privilégios

A ferramenta verifica automaticamente se o usuário pertence ao grupo `ENK-GLOBAL-DESKTOP-ADMINS`:

1. **Usuário no grupo**: Acesso total às funcionalidades
2. **Usuário fora do grupo**: Opção de elevação com credenciais de domínio
3. **Sem elevação**: Acesso limitado a funções que não exigem admin

### Sincronização de Script

- Verifica automaticamente se há nova versão na rede
- Atualiza o script local se necessário
- Garante que todos usem a versão mais recente

### Controle de Sessão

- Desconexão após inatividade
- Limpeza de variáveis sensíveis
- Remoção de arquivos temporários

---

## 📋 Requisitos

### Sistema Operacional
- Windows 10 ou superior
- Windows Server 2016 ou superior

### Permissões
- Usuário do domínio `nipo.local`
- Membro do grupo `ENK-GLOBAL-DESKTOP-ADMINS` (para funções administrativas)

### Dependências
- PowerShell 5.1 ou superior
- Acesso à rede corporativa
- Conexão com servidores de arquivos

---

## 🛠️ Instalação

### 1. Baixar o Script

```powershell
# O script deve estar em:
C:\Scripts\menu.ps1
```

### 2. Configurar Execução

```powershell
# Liberar execução de scripts
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

### 3. Executar como Administrador

```powershell
# Clique com botão direito no PowerShell
# Executar como administrador
# Navegue até a pasta
cd C:\Scripts
.\menu.ps1
```

### 4. Criar Atalho (Opcional)

```powershell
$WshShell = New-Object -comObject WScript.Shell
$Shortcut = $WshShell.CreateShortcut("$Home\Desktop\Service Desk Tool.lnk")
$Shortcut.TargetPath = "powershell.exe"
$Shortcut.Arguments = "-ExecutionPolicy Bypass -File `"C:\Scripts\menu.ps1`""
$Shortcut.Save()
```

---

## 🎬 Demonstração

**[Demonstração Service Automation]**(https://github.com/Thgcp/service-automation/releases/download/demonstration/Demonstration.gif)

---

## ❗ Solução de Problemas

### Erro: "File cannot be loaded"

```powershell
# Solução: Liberar execução
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

### Erro: "Access Denied"

```powershell
# Solução: Executar como administrador
# Clique com botão direito no PowerShell -> Executar como administrador
```

### Erro: "Cannot find network path"

```powershell
# Verificar conectividade com servidores
Test-Connection HNPSRVFSV01 -Count 2
```

### Erro: "Autologon not configured"

```powershell
# Verificar configuração no registro
REG QUERY "HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Winlogon"
```

---

## 📝 Logs e Auditoria

### Sincronização de Script
- Verificação automática de versão
- Atualização com hash SHA256
- Log de atualizações

### Elevação de Privilégios
- Registro de tentativas de elevação
- Verificação de grupo de administradores
- Validação de credenciais

---

## 📄 Licença

Esta ferramenta é **propriedade intelectual do Hospital Nipo Brasileiro**. Seu uso, cópia, modificação ou distribuição é restrito conforme acordo de confidencialidade.

---

## 📊 Status do Projeto

| Métrica | Status |
|---------|--------|
| **Versão** | 2.0.0 |
| **Ambiente** | Produção |
| **Última Atualização** | Julho 2026 |
| **Suporte** | Ativo |

---

## 🏷️ Tags

`powershell` `service-desk` `automation` `windows` `infrastructure` `hospital` `sysadmin` `helpdesk`

---

*Desenvolvido para a Equipe de Service Desk - Hospital Nipo Brasileiro* 🏥