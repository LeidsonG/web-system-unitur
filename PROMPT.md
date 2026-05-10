# PROMPT COMPLETO — DESENVOLVIMENTO DO SISTEMA WEB SM UNITUR

Desenvolva um sistema web completo para a empresa SM Unitur, focado em confecção de roupas personalizadas, uniformes e produtos têxteis personalizados.

O sistema deve possuir:

- Landing page profissional
- Sistema de orçamento
- Integração com WhatsApp
- Banco de dados MySQL
- Painel administrativo completo
- Acompanhamento de produção
- SEO otimizado
- Responsividade mobile premium

---

# 1. OBJETIVO DO PROJETO

O projeto consiste em uma landing page profissional da SM Unitur para divulgação de serviços de confecção personalizada.

O sistema deverá permitir que:

- Clientes conheçam os produtos e serviços
- Clientes solicitem orçamentos personalizados
- Clientes acompanhem o andamento da produção utilizando o número do orçamento
- Os dados sejam armazenados em banco MySQL
- A administração gerencie produtos, orçamentos e status da produção através de um painel administrativo

O projeto deve ter aparência moderna, premium, rápida e totalmente responsiva.

---

# 2. TECNOLOGIAS

A stack poderá ser escolhida pela IA desenvolvedora, porém deve priorizar tecnologias modernas.

Preferências:

- Node.js
- TypeScript
- JavaScript
- Framework moderno frontend
- Backend escalável
- MySQL
- XAMPP para ambiente local

Requisitos:

- Estrutura preparada para futura hospedagem online
- Código organizado e escalável
- Separação entre frontend e backend
- Estrutura pronta para upgrades futuros

---

# 3. BANCO DE DADOS

Utilizar:

- MySQL
- Ambiente local com XAMPP

Os produtos NÃO terão preço fixo.
O sistema será baseado em orçamento personalizado.

## usuarios_admin

Campos sugeridos:

- id
- nome
- email
- senha
- nivel
- created_at

---

# 4. LANDING PAGE

Criar uma landing page moderna e premium.

Requisitos:

- Totalmente responsiva
- SEO otimizado
- Mobile first
- Performance otimizada
- Layout premium
- Animações suaves e modernas
- Menu hambúrguer animado no mobile
- Fontes escaláveis
- Design profissional

A landing page deve possuir seções padrão de um site de confecção, como:

- Hero principal
- Sobre a empresa
- Produtos
- Nossos tipos de serviços
- Orçamentos
- Contato
- FAQ
- Rodapé

A logo será enviada posteriormente e deverá ser integrada ao layout.

# 5. FORMULÁRIO DE ORÇAMENTO

Criar formulário dinâmico de orçamento.

Categorias iniciais:

- Camisetas
- Moletons
- Jalecos
- "Futuramente poderá ter mais"

O formulário deve possuir:

- Nome
- Telefone
- CPF/CNPJ caso seja empresa
- E-mail
- Produto desejado
- Quantidade
- Tamanhos
- Campo de detalhes personalizados, incluindo cor
- Campo de observações
- Upload de imagem de referência

Detalhes importantes:

- Quantidade deve aceitar apenas números inteiros
- Campo de cores será um campo textual livre
- Cliente poderá escrever detalhes personalizados
- Cliente poderá enviar imagens de referência

Campos obrigatórios devem possuir validação.

---

# 6. WHATSAPP

Implementar integração com WhatsApp.

Número temporário para testes:
5517981322215

IMPORTANTE:
Adicionar comentário no código explicando que o número é apenas temporário para ambiente de testes e deverá ser substituído posteriormente pelo número oficial da empresa.

A mensagem do WhatsApp deve:

- Ser organizada
- Ser legível
- Conter todos os dados importantes do orçamento
- Conter número do orçamento, o numero começa em 100 (Por enquanto)

---

# 7. ACOMPANHAMENTO DE PRODUÇÃO

Criar sistema de acompanhamento de produção.

O cliente deverá conseguir:

- Informar o número do orçamento
- Consultar status da produção

Exemplos de status:

- Recebido
- Em análise (Quando alugém visualizar, ela podera colocar em "Em análise" ou algo do tipo, você pode me dar ideias)
- Em produção
- Finalizado
- Enviado

---

# 8. PAINEL ADMINISTRATIVO

Criar painel administrativo profissional.

O painel deve possuir:

- Login de múltiplos usuários
- Controle de sessão
- CRUD completo
- Interface moderna
- Layout claro
- Responsivo

Funcionalidades:

## Produtos

- Cadastro
- Edição
- Desativação
- Upload de imagem
- Categorias

## Orçamentos

- Visualização
- Busca
- Filtros
- Alteração de status
- Visualização detalhada

## Produção

- Atualização de status
- Histórico básico

## Usuários administrativos

- Cadastro
- Permissões básicas
- Login

O painel deve apresentar:

- Informações relevantes
- Indicadores rápidos
- Estatísticas básicas
- Organização visual profissional

---

# 9. SEO E INDEXAÇÃO

Implementar:

- Meta tags
- Open Graph
- Sitemap
- URLs amigáveis
- Estrutura otimizada para Google
- Performance otimizada

---

# 10. POSSÍVEIS UPGRADES FUTUROS

Apenas deixar preparado estruturalmente.

NÃO implementar agora.

Exemplos:

- Integração com pagamentos
- Automação
- Email marketing
- Integrações externas
- Sistema avançado de produção

---

# 11. README.md OBRIGATÓRIO

Durante TODO o desenvolvimento do projeto, criar e manter atualizado um arquivo:

README.md

Esse arquivo deve funcionar como documentação completa do projeto.

O objetivo é permitir que:

- Outra IA
- Outro desenvolvedor
- Outro responsável

consiga entender completamente:

- O que já foi feito
- O que está em andamento
- O que ainda falta

---

# 12. O README.md DEVE CONTER

## Objetivo do projeto

Explicação completa do sistema.

## Estrutura criada

Registrar:

- páginas
- componentes
- seções
- APIs
- funcionalidades

## Tecnologias utilizadas

Documentar:

- frameworks
- bibliotecas
- banco
- ferramentas

## Estrutura do banco

Documentar:

- tabelas
- campos
- relacionamentos

## Funcionamento do formulário

Explicar:

- regras
- validações
- funcionamento dinâmico

## Integração WhatsApp

Documentar:

- estrutura da mensagem
- geração do link
- organização dos dados

## Painel administrativo

Documentar:

- CRUDs
- permissões
- funcionalidades
- filtros

## Decisões importantes

Registrar:

- arquitetura
- organização
- estrutura
- padrões adotados

## Problemas e soluções

Registrar:

- erros encontrados
- soluções aplicadas
- pendências

## Pendências

Registrar:

- melhorias futuras
- funcionalidades incompletas
- ajustes necessários

## Histórico de alterações

Registrar cronologicamente:

- data
- alteração
- descrição

IMPORTANTE:
Sempre atualizar o README.md quando qualquer funcionalidade for:

- criada
- alterada
- corrigida
- removida

---

# 13. QUALIDADE DO CÓDIGO

Requisitos:

- Código limpo
- Componentização
- Organização profissional
- Escalabilidade
- Responsividade
- Segurança básica
- Estrutura pronta para crescimento futuro

---

# 14. EXPERIÊNCIA VISUAL

O projeto deve transmitir:

- Profissionalismo
- Modernidade
- Credibilidade
- Performance
- Facilidade de uso

Priorizar:

- UX/UI moderna
- Animações suaves
- Boa hierarquia visual
- Navegação intuitiva
- Excelente experiência mobile

# 15.IMPORTANTE

Preciso que você a cada passo a passo um git commit e a mensagem do que foi alterado. Pode ter vários commits ou se precisar usar branchs, pode usar. Mas preciso que seja comitado e versionado.


# Precisamos fazer:

Precisa arrumar o envio pelo whatsapp, está enviando somente para o e-mail -> Verificar se arrumou

A margem superior de cada começo de sessão, está muito grande -> OK

Precisa colocar para mudar a senha do usuario no admin
