# Arch Project

O Arch é um sistema integrado de inteligência legislativa e análise automatizada para estudos de viabilidade arquitetônica. A plataforma processa parâmetros de documentos técnicos (memoriais descritivos e plantas) para validar regras de zoneamento e diretrizes do plano diretor.

## 🎯 Objetivos e Arquitetura
* **Foco:** Automatizar a verificação de conformidade de projetos arquitetônicos com a legislação municipal, otimizando o tempo de análise e garantindo a precisão técnica da ocupação do lote.
* **Arquitetura:** O ecossistema frontend é construído com Vite e hospedado em infraestrutura de borda (Cloudflare Pages). O backend e a segurança relacional operam via Supabase (PostgreSQL com RLS). O ecossistema também contempla uma versão mobile para submissão de PDFs e plantas.
* **Diferencial:** A capacidade do motor de extrair dados reais de projetos (área, pavimentos, taxa de permeabilidade) e confrontá-los imediatamente com as variáveis urbanísticas, sustentado por um fluxo rigoroso de CI/CD e automação de testes (Playwright e Vitest).

## 🚀 Repositórios Principais
* [ArchLandingPage](https://github.com/Arch-project-org/ArchLandingPage) - Ponto de entrada do sistema, responsável pela captação de leads (waitlist), com validações estritas de formulário e roteamento Cloudflare.
* [BlogArch](https://github.com/Arch-project-org/BlogArch) - Plataforma de conteúdo focada na aquisição de usuários e integração com newsletter.
* [ArchApp/Core](#) - Aplicativo mobile e motor central para criação de "Novos Estudos Arquitetônicos" e processamento de documentação (DWG/PDF). *(Adicione o link real do repositório)*

## 🛠 Como Contribuir
Procuramos colaboração ativa, com foco em código limpo, testes consistentes e estabilidade estrutural. Consulte os nossos guias antes de submeter código:
* [Guia de Contribuição](.github/CONTRIBUTING.md)
* [Código de Conduta](.github/CODE_OF_CONDUCT.md)

## 📬 Contactos e Links Úteis
* **Aplicação em Produção:** [https://arch.ia.br](https://arch.ia.br)
* **Organização no GitHub:** [https://github.com/Arch-project-org](https://github.com/Arch-project-org)
