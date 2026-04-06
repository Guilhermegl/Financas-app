# 💰 Finanças — Controle Financeiro Pessoal

> App de controle financeiro pessoal, leve, offline-first e sem cadastro.  
> Construído em HTML, CSS e JavaScript puro — zero backend, zero cadastro, zero rastreamento.

---

## 📱 Como usar

**Opção 1 — Acessar online**  
Abra o link no navegador e use direto. Nenhuma instalação necessária.

**Opção 2 — Instalar como PWA (recomendado)**  
No Chrome do celular: toque nos 3 pontinhos → "Adicionar à tela inicial" → o app aparece como qualquer outro aplicativo, abre em tela cheia e funciona offline.

**Opção 3 — Rodar localmente**  
Baixe o repositório, abra a pasta e clique duas vezes no arquivo `index.html`.  
Funciona direto no navegador, sem precisar instalar nada.

---

## ✨ Funcionalidades

### 💼 Controle de Bolso
- Saldo calculado automaticamente a partir do salário
- Suporte a salários diferentes por mês
- Edição manual do bolso para correções pontuais
- Alerta visual e popup quando o saldo fica negativo

### 📅 Navegação por Mês
- Visualização independente para cada mês do ano
- Aviso ao acessar meses já encerrados
- Dados completamente separados por mês

### 💳 Gastos
- Categorias: débito, crédito e dinheiro físico
- Gastos no crédito não descontam do bolso imediatamente
- Parcelamento em até 12x
- Fatura gerada automaticamente no mês correspondente
- Ao excluir parcelado, todas as parcelas são removidas

### 🧾 Dívidas
- Registro com status (pago / não pago)
- Parcelas recorrentes sem limite de meses
- Data de vencimento com alertas automáticos
- Ao pagar, o valor é descontado do bolso

### 📥 Entradas Extras
- Registro de receitas além do salário (freela, venda, presente, reembolso)
- Somadas ao bolso automaticamente

### 🏦 Reservas
- Múltiplas reservas com nomes personalizados (CDB, Bitcoin, FII, Poupança...)
- Ao adicionar: escolha se o dinheiro vem do bolso ou já estava guardado
- Total de reservas exibido no dashboard

### 🎯 Meta de Economia
- Defina quanto quer guardar por mês
- Acompanhe o progresso anual com barra e percentual
- Alerta quando a meta do mês é cumprida

### 📊 Gráficos e Análises
- Distribuição do saldo: donut com bolso, reservas e pendentes
- Histórico anual: barras com saldo, gastos, entradas e dívidas
- Evolução da reserva vs meta: gráfico de linha com projeção anual
- Forma de pagamento: crédito vs débito com alertas inteligentes

### 🏥 Saúde do Mês
- Termômetro de comprometimento do salário (0% a 100%+)
- Linha do tempo dos dias do mês
- Projeção do saldo final após pagar dívidas pendentes

### ⚠️ Alertas Inteligentes
- 🚨 Saldo negativo — popup animado ao ficar no vermelho
- 📅 Mês encerrado — aviso ao navegar para meses passados
- 💳 Crédito alto — alerta quando mais de 50% dos gastos são no crédito
- 🔔 Vencimentos — banner para dívidas próximas do vencimento

### 📄 Relatórios PDF
- PDF mensal com todos os lançamentos
- PDF anual com resumo de todos os meses
- Cabeçalho personalizado com nome do usuário e data

### 💾 Backup e Restauração
- Exportar todos os dados como arquivo `.json`
- Restaurar com confirmação antes de sobrescrever
- Útil para migrar entre dispositivos ou navegadores

### 🌙 Tema
- Alternância entre modo escuro e claro
- Preferência salva automaticamente

---

## 💾 Como os dados são salvos

Todos os dados ficam no **localStorage do navegador**, no seu próprio dispositivo. Nenhuma informação é enviada para servidores.

| ✅ Vantagens | ⚠️ Atenção |
|---|---|
| Funciona 100% offline | Limpar cache apaga os dados |
| Dados 100% privados | Cada navegador tem dados separados |
| Zero cadastro | Aba anônima não persiste dados |

> 💡 **Recomendação:** exporte o backup `.json` regularmente e guarde em local seguro (Google Drive, WhatsApp, etc.).

---

## 🛠️ Tecnologias

| Tecnologia | Uso |
|---|---|
| HTML5 | Estrutura do app |
| CSS3 | Visual, animações e temas |
| JavaScript ES6 | Toda a lógica |
| Chart.js | Gráficos interativos |
| localStorage | Persistência de dados |
| Service Worker | Funcionamento offline |
| Web App Manifest | Instalação como PWA |

> Zero dependências de backend. Zero banco de dados. Zero cadastro.

---

## 📁 Estrutura do projeto
# 💰 Finanças — Controle Financeiro Pessoal

> App de controle financeiro pessoal, leve, offline-first e sem cadastro.  
> Construído em HTML, CSS e JavaScript puro — zero backend, zero cadastro, zero rastreamento.

---

## 📱 Como usar

**Opção 1 — Acessar online**  
Abra o link no navegador e use direto. Nenhuma instalação necessária.

**Opção 2 — Instalar como PWA (recomendado)**  
No Chrome do celular: toque nos 3 pontinhos → "Adicionar à tela inicial" → o app aparece como qualquer outro aplicativo, abre em tela cheia e funciona offline.

**Opção 3 — Rodar localmente**  
Baixe o repositório, abra a pasta e clique duas vezes no arquivo `index.html`.  
Funciona direto no navegador, sem precisar instalar nada.

---

## ✨ Funcionalidades

### 💼 Controle de Bolso
- Saldo calculado automaticamente a partir do salário
- Suporte a salários diferentes por mês
- Edição manual do bolso para correções pontuais
- Alerta visual e popup quando o saldo fica negativo

### 📅 Navegação por Mês
- Visualização independente para cada mês do ano
- Aviso ao acessar meses já encerrados
- Dados completamente separados por mês

### 💳 Gastos
- Categorias: débito, crédito e dinheiro físico
- Gastos no crédito não descontam do bolso imediatamente
- Parcelamento em até 12x
- Fatura gerada automaticamente no mês correspondente
- Ao excluir parcelado, todas as parcelas são removidas

### 🧾 Dívidas
- Registro com status (pago / não pago)
- Parcelas recorrentes sem limite de meses
- Data de vencimento com alertas automáticos
- Ao pagar, o valor é descontado do bolso

### 📥 Entradas Extras
- Registro de receitas além do salário (freela, venda, presente, reembolso)
- Somadas ao bolso automaticamente

### 🏦 Reservas
- Múltiplas reservas com nomes personalizados (CDB, Bitcoin, FII, Poupança...)
- Ao adicionar: escolha se o dinheiro vem do bolso ou já estava guardado
- Total de reservas exibido no dashboard

### 🎯 Meta de Economia
- Defina quanto quer guardar por mês
- Acompanhe o progresso anual com barra e percentual
- Alerta quando a meta do mês é cumprida

### 📊 Gráficos e Análises
- Distribuição do saldo: donut com bolso, reservas e pendentes
- Histórico anual: barras com saldo, gastos, entradas e dívidas
- Evolução da reserva vs meta: gráfico de linha com projeção anual
- Forma de pagamento: crédito vs débito com alertas inteligentes

### 🏥 Saúde do Mês
- Termômetro de comprometimento do salário (0% a 100%+)
- Linha do tempo dos dias do mês
- Projeção do saldo final após pagar dívidas pendentes

### ⚠️ Alertas Inteligentes
- 🚨 Saldo negativo — popup animado ao ficar no vermelho
- 📅 Mês encerrado — aviso ao navegar para meses passados
- 💳 Crédito alto — alerta quando mais de 50% dos gastos são no crédito
- 🔔 Vencimentos — banner para dívidas próximas do vencimento

### 📄 Relatórios PDF
- PDF mensal com todos os lançamentos
- PDF anual com resumo de todos os meses
- Cabeçalho personalizado com nome do usuário e data

### 💾 Backup e Restauração
- Exportar todos os dados como arquivo `.json`
- Restaurar com confirmação antes de sobrescrever
- Útil para migrar entre dispositivos ou navegadores

### 🌙 Tema
- Alternância entre modo escuro e claro
- Preferência salva automaticamente

---

## 💾 Como os dados são salvos

Todos os dados ficam no **localStorage do navegador**, no seu próprio dispositivo. Nenhuma informação é enviada para servidores.

| ✅ Vantagens | ⚠️ Atenção |
|---|---|
| Funciona 100% offline | Limpar cache apaga os dados |
| Dados 100% privados | Cada navegador tem dados separados |
| Zero cadastro | Aba anônima não persiste dados |

> 💡 **Recomendação:** exporte o backup `.json` regularmente e guarde em local seguro (Google Drive, WhatsApp, etc.).

---

## 🛠️ Tecnologias

| Tecnologia | Uso |
|---|---|
| HTML5 | Estrutura do app |
| CSS3 | Visual, animações e temas |
| JavaScript ES6 | Toda a lógica |
| Chart.js | Gráficos interativos |
| localStorage | Persistência de dados |
| Service Worker | Funcionamento offline |
| Web App Manifest | Instalação como PWA |

> Zero dependências de backend. Zero banco de dados. Zero cadastro.

---

## 📁 Estrutura do projeto

# 💰 Finanças — Controle Financeiro Pessoal

> App de controle financeiro pessoal, leve, offline-first e sem cadastro.  
> Construído em HTML, CSS e JavaScript puro — zero backend, zero cadastro, zero rastreamento.

---

## 📱 Como usar

**Opção 1 — Acessar online**  
Abra o link no navegador e use direto. Nenhuma instalação necessária.

**Opção 2 — Instalar como PWA (recomendado)**  
No Chrome do celular: toque nos 3 pontinhos → "Adicionar à tela inicial" → o app aparece como qualquer outro aplicativo, abre em tela cheia e funciona offline.

**Opção 3 — Rodar localmente**  
Baixe o repositório, abra a pasta e clique duas vezes no arquivo `index.html`.  
Funciona direto no navegador, sem precisar instalar nada.

---

## ✨ Funcionalidades

### 💼 Controle de Bolso
- Saldo calculado automaticamente a partir do salário
- Suporte a salários diferentes por mês
- Edição manual do bolso para correções pontuais
- Alerta visual e popup quando o saldo fica negativo

### 📅 Navegação por Mês
- Visualização independente para cada mês do ano
- Aviso ao acessar meses já encerrados
- Dados completamente separados por mês

### 💳 Gastos
- Categorias: débito, crédito e dinheiro físico
- Gastos no crédito não descontam do bolso imediatamente
- Parcelamento em até 12x
- Fatura gerada automaticamente no mês correspondente
- Ao excluir parcelado, todas as parcelas são removidas

### 🧾 Dívidas
- Registro com status (pago / não pago)
- Parcelas recorrentes sem limite de meses
- Data de vencimento com alertas automáticos
- Ao pagar, o valor é descontado do bolso

### 📥 Entradas Extras
- Registro de receitas além do salário (freela, venda, presente, reembolso)
- Somadas ao bolso automaticamente

### 🏦 Reservas
- Múltiplas reservas com nomes personalizados (CDB, Bitcoin, FII, Poupança...)
- Ao adicionar: escolha se o dinheiro vem do bolso ou já estava guardado
- Total de reservas exibido no dashboard

### 🎯 Meta de Economia
- Defina quanto quer guardar por mês
- Acompanhe o progresso anual com barra e percentual
- Alerta quando a meta do mês é cumprida

### 📊 Gráficos e Análises
- Distribuição do saldo: donut com bolso, reservas e pendentes
- Histórico anual: barras com saldo, gastos, entradas e dívidas
- Evolução da reserva vs meta: gráfico de linha com projeção anual
- Forma de pagamento: crédito vs débito com alertas inteligentes

### 🏥 Saúde do Mês
- Termômetro de comprometimento do salário (0% a 100%+)
- Linha do tempo dos dias do mês
- Projeção do saldo final após pagar dívidas pendentes

### ⚠️ Alertas Inteligentes
- 🚨 Saldo negativo — popup animado ao ficar no vermelho
- 📅 Mês encerrado — aviso ao navegar para meses passados
- 💳 Crédito alto — alerta quando mais de 50% dos gastos são no crédito
- 🔔 Vencimentos — banner para dívidas próximas do vencimento

### 📄 Relatórios PDF
- PDF mensal com todos os lançamentos
- PDF anual com resumo de todos os meses
- Cabeçalho personalizado com nome do usuário e data

### 💾 Backup e Restauração
- Exportar todos os dados como arquivo `.json`
- Restaurar com confirmação antes de sobrescrever
- Útil para migrar entre dispositivos ou navegadores

### 🌙 Tema
- Alternância entre modo escuro e claro
- Preferência salva automaticamente

---

## 💾 Como os dados são salvos

Todos os dados ficam no **localStorage do navegador**, no seu próprio dispositivo. Nenhuma informação é enviada para servidores.

| ✅ Vantagens | ⚠️ Atenção |
|---|---|
| Funciona 100% offline | Limpar cache apaga os dados |
| Dados 100% privados | Cada navegador tem dados separados |
| Zero cadastro | Aba anônima não persiste dados |

> 💡 **Recomendação:** exporte o backup `.json` regularmente e guarde em local seguro (Google Drive, WhatsApp, etc.).

---

## 🛠️ Tecnologias

| Tecnologia | Uso |
|---|---|
| HTML5 | Estrutura do app |
| CSS3 | Visual, animações e temas |
| JavaScript ES6 | Toda a lógica |
| Chart.js | Gráficos interativos |
| localStorage | Persistência de dados |
| Service Worker | Funcionamento offline |
| Web App Manifest | Instalação como PWA |

> Zero dependências de backend. Zero banco de dados. Zero cadastro.

---

## 📁 Estrutura do projeto

# 💰 Finanças — Controle Financeiro Pessoal

> App de controle financeiro pessoal, leve, offline-first e sem cadastro.  
> Construído em HTML, CSS e JavaScript puro — zero backend, zero cadastro, zero rastreamento.

---

## 📱 Como usar

**Opção 1 — Acessar online**  
Abra o link no navegador e use direto. Nenhuma instalação necessária.

**Opção 2 — Instalar como PWA (recomendado)**  
No Chrome do celular: toque nos 3 pontinhos → "Adicionar à tela inicial" → o app aparece como qualquer outro aplicativo, abre em tela cheia e funciona offline.

**Opção 3 — Rodar localmente**  
Baixe o repositório, abra a pasta e clique duas vezes no arquivo `index.html`.  
Funciona direto no navegador, sem precisar instalar nada.

---

## ✨ Funcionalidades

### 💼 Controle de Bolso
- Saldo calculado automaticamente a partir do salário
- Suporte a salários diferentes por mês
- Edição manual do bolso para correções pontuais
- Alerta visual e popup quando o saldo fica negativo

### 📅 Navegação por Mês
- Visualização independente para cada mês do ano
- Aviso ao acessar meses já encerrados
- Dados completamente separados por mês

### 💳 Gastos
- Categorias: débito, crédito e dinheiro físico
- Gastos no crédito não descontam do bolso imediatamente
- Parcelamento em até 12x
- Fatura gerada automaticamente no mês correspondente
- Ao excluir parcelado, todas as parcelas são removidas

### 🧾 Dívidas
- Registro com status (pago / não pago)
- Parcelas recorrentes sem limite de meses
- Data de vencimento com alertas automáticos
- Ao pagar, o valor é descontado do bolso

### 📥 Entradas Extras
- Registro de receitas além do salário (freela, venda, presente, reembolso)
- Somadas ao bolso automaticamente

### 🏦 Reservas
- Múltiplas reservas com nomes personalizados (CDB, Bitcoin, FII, Poupança...)
- Ao adicionar: escolha se o dinheiro vem do bolso ou já estava guardado
- Total de reservas exibido no dashboard

### 🎯 Meta de Economia
- Defina quanto quer guardar por mês
- Acompanhe o progresso anual com barra e percentual
- Alerta quando a meta do mês é cumprida

### 📊 Gráficos e Análises
- Distribuição do saldo: donut com bolso, reservas e pendentes
- Histórico anual: barras com saldo, gastos, entradas e dívidas
- Evolução da reserva vs meta: gráfico de linha com projeção anual
- Forma de pagamento: crédito vs débito com alertas inteligentes

### 🏥 Saúde do Mês
- Termômetro de comprometimento do salário (0% a 100%+)
- Linha do tempo dos dias do mês
- Projeção do saldo final após pagar dívidas pendentes

### ⚠️ Alertas Inteligentes
- 🚨 Saldo negativo — popup animado ao ficar no vermelho
- 📅 Mês encerrado — aviso ao navegar para meses passados
- 💳 Crédito alto — alerta quando mais de 50% dos gastos são no crédito
- 🔔 Vencimentos — banner para dívidas próximas do vencimento

### 📄 Relatórios PDF
- PDF mensal com todos os lançamentos
- PDF anual com resumo de todos os meses
- Cabeçalho personalizado com nome do usuário e data

### 💾 Backup e Restauração
- Exportar todos os dados como arquivo `.json`
- Restaurar com confirmação antes de sobrescrever
- Útil para migrar entre dispositivos ou navegadores

### 🌙 Tema
- Alternância entre modo escuro e claro
- Preferência salva automaticamente

---

## 💾 Como os dados são salvos

Todos os dados ficam no **localStorage do navegador**, no seu próprio dispositivo. Nenhuma informação é enviada para servidores.

| ✅ Vantagens | ⚠️ Atenção |
|---|---|
| Funciona 100% offline | Limpar cache apaga os dados |
| Dados 100% privados | Cada navegador tem dados separados |
| Zero cadastro | Aba anônima não persiste dados |

> 💡 **Recomendação:** exporte o backup `.json` regularmente e guarde em local seguro (Google Drive, WhatsApp, etc.).

---

## 🛠️ Tecnologias

| Tecnologia | Uso |
|---|---|
| HTML5 | Estrutura do app |
| CSS3 | Visual, animações e temas |
| JavaScript ES6 | Toda a lógica |
| Chart.js | Gráficos interativos |
| localStorage | Persistência de dados |
| Service Worker | Funcionamento offline |
| Web App Manifest | Instalação como PWA |

> Zero dependências de backend. Zero banco de dados. Zero cadastro.

---

## 📁 Estrutura do projeto

financas-app/
├── index.html       # App completo (HTML + CSS + JS em arquivo único)
├── manifest.json    # Configuração PWA
├── sw.js            # Service Worker para offline
├── icon-192.png     # Ícone 192x192
└── icon-512.png     # Ícone 512x512

---

---

## 🔐 Privacidade

Este app não coleta nenhum dado. Não há cadastro, login, envio para servidores, analytics ou cookies de terceiros.  
Seus dados financeiros ficam **exclusivamente no seu dispositivo**.

---

## 📝 Licença

MIT — use, modifique e distribua livremente.

---
