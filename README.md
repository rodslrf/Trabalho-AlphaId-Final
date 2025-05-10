# Projeto Alfa Engenharia

Este é um sistema desenvolvido para a empresa **Alfa Engenharia**, com arquitetura fullstack. O front-end (mobile) foi construído com **Flutter (Dart)** para garantir performance e responsividade em múltiplas plataformas, e o back-end foi desenvolvido com **Laravel (PHP)** (mobile e web), oferecendo uma API robusta e segura. Também fizemos a integração dos mesmos

## 🚀 Tecnologias Utilizadas

### Front-End
- **Dart**
- **Flutter** (Web, Mobile e Desktop-ready)
- Gerenciamento de estado: `Provider` / `Bloc` (especifique o que usou)
- Consumo de API REST com `http` ou `Dio`

### Back-End
- **PHP**
- **Laravel** 10+
- Autenticação via `Sanctum` / `JWT`
- Banco de Dados: MySQL / PostgreSQL (especifique)
- API RESTful

---

## ⚙️ Funcionalidades

- Autenticação de usuários (login, cadastro, recuperação de senha)
- Dashboard administrativo com controle de permissões
- Cadastro e gerenciamento de obras/projetos de engenharia
- Upload de documentos e imagens
- Relatórios PDF e exportações
- Notificações em tempo real (opcional, caso tenha usado Firebase ou WebSockets)

---

## 🔧 Instalação e Execução

### Backend (Laravel)
```bash
cd backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
