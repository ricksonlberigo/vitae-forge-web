# VitaeForge Web (Front-end)

[![PHP Version](https://img.shields.io/badge/PHP-8.2-blue)](https://www.php.net/)
[![Laravel](https://img.shields.io/badge/Laravel-12-red)](https://laravel.com)
[![Livewire](https://img.shields.io/badge/Livewire-3-purple)](https://livewire.laravel.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Aplicação front-end do projeto **VitaeForge**, construída com **Laravel 12**, **PHP 8.2** e **Livewire**, proporcionando uma experiência moderna, acessível e responsiva para criação de currículos integrados à API oficial.

## ✨ Destaques
- Formulários dinâmicos (Livewire) com validação em tempo real e autosave.
- Pré-visualização interativa do currículo durante a edição.
- Suporte a múltiplos layouts e temas personalizáveis.
- Integração segura com a API (tokens de acesso).

## 🏗️ Arquitetura
- Organização por componentes Livewire (cada seção do CV é modularizada).
- Views estruturadas e reutilizáveis (Blade).
- Camada de consumo da API com tratamento consistente de erros.
- Suporte a internacionalização (pt-BR, en-US).

## 🔐 Segurança & Qualidade
- Proteção CSRF e rate limiting de requisições sensíveis.
- Testes de unidade e integração de componentes Livewire.
- Padrões de commits (Conventional Commits) e linters para padronização.

## 📊 Observabilidade
- Integração com rastreamento de erros e métricas (via API).
- Logging consistente para auditoria e debug.

## 🚀 Roadmap
- Editor visual de templates de CV (drag & drop).
- Suporte offline-first com sincronização posterior.
- Exportação adicional (DOCX, JSON Resume Schema).

## 📄 Licença
Distribuído sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE).
