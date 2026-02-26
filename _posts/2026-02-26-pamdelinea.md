---
layout: post
title: "PAM - Privileged Access Management"
date: 2026-02-26
tags: [pam, blog]
---

Opa, você já ouviu falar em PAM?

PAM, ou Privileged Access Management, é uma solução de segurança de identidade que ajuda a proteger organizações contra ameaças cibernéticas, monitorando, detectando e impedindo acessos privilegiados não autorizados a recursos críticos.

Mas como funciona uma solução de PAM na prática? Neste post vou falar sobre a Delinea, uma solução bastante consolidada no mercado quando o assunto é gestão de acessos privilegiados.

<img src="{{ "/assets/delinea.png" | relative_url }}" class="post-image">

Tenho trabalhado com a Delinea e a experiência tem sido bem interessante. A plataforma conta com serviços como Secret Server, descoberta automática de inventário, mapeamento de usuários no Active Directory e diversos recursos voltados para governança de credenciais.

Agora vamos imaginar um cenário comum: você tem vários servidores na sua infraestrutura, e cada um deles possui uma credencial administrativa para acesso. Mesmo que a senha seja forte, o simples fato de ela existir e estar armazenada em algum lugar — seja em planilha, arquivo ou compartilhada entre pessoas — já representa um risco.

É aí que o PAM entra.

Com uma solução como a Delinea, as credenciais ficam criptografadas e armazenadas em um cofre seguro. O time não precisa mais saber a senha do servidor. O acesso passa a ser feito através da própria plataforma, respeitando políticas definidas pela organização. É possível exigir aprovação de um gestor antes da liberação do acesso, limitar a sessão por tempo determinado, gravar tudo que foi feito durante a conexão e até configurar a rotação automática da senha após o uso.

Ou seja, mesmo que alguém tivesse acesso à senha durante uma sessão, ela deixa de valer logo depois.

No meu caso, estou utilizando a Delinea integrada ao Active Directory da empresa onde trabalho. Isso significa que faço login na plataforma utilizando minhas próprias credenciais do AD, o que facilita bastante a gestão e mantém o controle centralizado.

É possível sincronizar usuários, aplicar grupos, definir permissões específicas e criar políticas de acesso alinhadas à estrutura da organização. A plataforma oferece diversos mecanismos para segmentar acessos e aplicar o princípio do menor privilégio, reduzindo bastante a superfície de ataque.

No fim das contas, trabalhar com PAM me fez perceber que segurança não é apenas sobre bloquear tráfego ou criptografar dados, mas também sobre controlar quem pode acessar o quê — e em que momento. Em ambientes corporativos, isso faz toda a diferença.

Se você está estudando segurança defensiva ou governança de identidade, entender como funciona um PAM na prática é um passo importante para evoluir na área.

##  📚 Bibliografia

- [Microsoft - O que é PAM? ](https://www.microsoft.com/pt-br/security/business/security-101/what-is-privileged-access-management-pam)
- [Delinea](https://delinea.com/)
