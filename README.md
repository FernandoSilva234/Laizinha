# Cartilha Viva — Obesidade & Saúde Mental

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://fernandosilva234.github.io/Laizinha/)

Material educativo e interativo sobre a relação entre obesidade, saúde mental e hábitos saudáveis. Conteúdo acessível, livre de estigma e alinhado a boas práticas de saúde pública.

## 📋 Sobre o Projeto

Cartilha informativa elaborada com base em conteúdos das áreas de psicologia, nutrição, psiquiatria e saúde pública. O objetivo é explicar a obesidade de forma clara, interdisciplinar e sem estigma, incentivando o autocuidado e a busca por acompanhamento multiprofissional.

### Autoria Acadêmica
- **Laize Lemes**
- **Andreia Cristina Specht**
- **Luana Valença Lopes**

Trabalho apresentado ao Curso de Graduação em Psicologia da UNICESUMAR Universidade Cesumar como requisito parcial para avaliação da AEP, 2º bimestre de 2025 (período noturno).

## 🚀 Como Usar

### Visualização Online
Acesse a cartilha diretamente através do GitHub Pages:
**[https://fernandosilva234.github.io/Laizinha/](https://fernandosilva234.github.io/Laizinha/)**

### Execução Local

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/FernandoSilva234/Laizinha.git
   cd Laizinha
   ```

2. **Inicie um servidor web local:**
   
   Usando Python 3:
   ```bash
   python3 -m http.server 8080
   ```
   
   Ou usando Python 2:
   ```bash
   python -m SimpleHTTPServer 8080
   ```
   
   Ou usando Node.js (com npx):
   ```bash
   npx http-server -p 8080
   ```

3. **Acesse no navegador:**
   ```
   http://localhost:8080/index.html
   ```

## 🎯 Funcionalidades

### Conteúdo Educativo
- **Relação Obesidade e Transtornos Mentais**: Explicação sobre a relação bidirecional
- **Transtornos Abordados**: TDAH, TEA, Personalidade Borderline, Esquizofrenia
- **Hábitos Práticos**: Ferramentas para criar consistência em movimento e alimentação
- **Respiração Box 4-4-4-4**: Técnica de regulação emocional
- **Recursos Confiáveis**: Links para apoio profissional (SUS, CVV, OMS, Ministério da Saúde)

### Recursos Interativos
- 🎯 **Meta diária de movimento** com timer e acompanhamento
- ✅ **Rotina guiada** (Aquecimento, Caminhada, Alongamento)
- 🧘 **Exercício de respiração** com animação visual
- 📊 **Registro de progresso** semanal (streak)
- 🌓 **Tema claro/escuro** para conforto visual
- 📱 **QR Codes** para acesso rápido via dispositivos móveis
- 📄 **Exportação para PDF** do conteúdo

### Características Técnicas
- 📱 **Totalmente responsivo** (mobile, tablet, desktop)
- ♿ **Acessível** com ARIA labels e navegação por teclado
- 💾 **Dados locais** salvos no localStorage (privacidade total)
- 🎨 **Animações Lottie** para ilustrações interativas
- 🎉 **Feedback visual** com confetes e notificações

## 📁 Estrutura do Projeto

```
Laizinha/
├── index.html              # Página principal com todo o conteúdo
├── cartilha-viva.pdf       # PDF estático da cartilha
├── UNICESUMAR.jpg          # Logo da universidade
├── Bord.png                # Ilustração Personalidade Borderline
├── TDAH.png                # Ilustração TDAH
└── README.md               # Este arquivo
```

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilização com variáveis CSS, grid, flexbox
- **JavaScript ES6+**: Funcionalidades interativas
- **Lottie Player**: Animações SVG
- **html2pdf.js**: Geração de PDF no cliente
- **QR Server API**: Geração dinâmica de QR codes

## 🌐 Implantação (GitHub Pages)

O projeto está configurado para ser hospedado no GitHub Pages automaticamente. Qualquer push para a branch principal será implantado automaticamente.

### Habilitar GitHub Pages (se necessário):
1. Vá em **Settings** > **Pages** no repositório
2. Em **Source**, selecione a branch `main` (ou branch desejada)
3. Clique em **Save**
4. O site estará disponível em: `https://fernandosilva234.github.io/Laizinha/`

## 📝 Notas Importantes

### Avisos Legais
- ⚠️ **Este material é educativo** e não substitui orientação profissional
- 🔒 **Privacidade**: Todos os dados são salvos localmente no navegador (localStorage)
- 🏥 **Não realiza diagnóstico**: Procure profissionais de saúde qualificados

### Emergências
- **SAMU**: 192
- **CVV (Centro de Valorização da Vida)**: 188 (24h, gratuito)
- **SUS/UBS**: Procure a unidade básica de saúde mais próxima

## 🤝 Como Contribuir

Este é um projeto acadêmico, mas sugestões são bem-vindas:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

## 📄 Licença

Projeto desenvolvido para fins educativos e acadêmicos.

## 📧 Contato

Para dúvidas ou informações sobre o projeto acadêmico, entre em contato através do repositório no GitHub.

---

**Desenvolvido com ❤️ por estudantes de Psicologia da UNICESUMAR**
