# 02 - Active Directory (AD DS)

Esta pasta documenta o planejamento lógico, a estrutura de diretórios e as evidências de implementação do Active Directory no laboratório **PeixeTech**.

## 🌐 Informações do Domínio
* **Nome do Domínio:** `PEIXETECH.LOCAL`
* **Função:** Controlador de Domínio Principal (`DC01`) rodando Windows Server 2022.

## 📁 Estrutura de Unidades Organizacionais (OUs)

A arquitetura de OUs foi desenhada para isolar objetos por departamento e finalidade administrativa, facilitando a aplicação de políticas de grupo (GPOs) e o controle de acesso:

```text
PEIXETECH.LOCAL
├── Usuarios
│   ├── TI
│   ├── RH
│   ├── Financeiro
│   └── Diretoria
├── Computadores
├── Servidores
├── Grupos
└── Administracao/GPO
