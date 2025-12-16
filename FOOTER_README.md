# Footer Thera - Componente Reutilizável

Este diretório contém um footer reutilizável usado no site da Thera.

## 📁 Arquivos

- **footer.html** - Estrutura HTML do footer
- **footer.css** - Estilos CSS do footer
- **marca_csv_neg.png** - Logo do Grupo CSV (versão negativa/branca)

## 🚀 Como Usar

### 1. Incluir o CSS

Adicione o arquivo CSS no `<head>` do seu HTML:

```html
<link rel="stylesheet" href="footer.css">
```

### 2. Incluir o HTML

Copie o conteúdo de `footer.html` para o final do seu `<body>`:

```html
<body>
    <!-- Seu conteúdo aqui -->
    
    <!-- Footer -->
    <footer class="footer">
        <!-- ... conteúdo do footer.html ... -->
    </footer>
</body>
```

### 3. Incluir a Imagem

Certifique-se de que o arquivo `marca_csv_neg.png` está no mesmo diretório ou ajuste o caminho no HTML.

## 🎨 Personalização

### Cores

O footer usa a variável CSS `--thera-teal`. Você pode personalizá-la:

```css
:root {
    --thera-teal: #7DD3C0; /* Cor padrão */
}
```

### Links

Edite os links no `footer.html` conforme necessário:

- **Links Úteis**: AxiaCare, MedValor, Guilherme Thomé
- **Contato**: E-mails de contato

### Copyright

Atualize o ano e o texto do copyright conforme necessário.

## 📋 Estrutura

O footer contém:

1. **Grid de Links** (2 colunas responsivas)
   - Links Úteis
   - Contato

2. **Seção CSV**
   - Logo do Grupo CSV (clicável, leva para grupocsv.com)
   - Texto descritivo
   - Copyright

## 📱 Responsividade

O footer é totalmente responsivo:
- **Desktop**: Grid de 2 colunas
- **Mobile** (< 768px): Grid de 1 coluna, centralizado

## 🎯 Características

- ✅ Fundo semi-transparente com blur
- ✅ Borda superior sutil
- ✅ Links com hover effect
- ✅ Logo CSV com link para grupocsv.com
- ✅ Totalmente responsivo
- ✅ Acessível

## 💡 Exemplo Completo

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site</title>
    <link rel="stylesheet" href="footer.css">
</head>
<body>
    <!-- Seu conteúdo -->
    
    <!-- Footer Thera -->
    <footer class="footer">
        <div class="footer-content">
            <div class="footer-grid">
                <div class="footer-section">
                    <h3>Links Úteis</h3>
                    <a href="https://axcare.com.br" target="_blank">AxiaCare</a>
                    <a href="https://medvalor.med.br" target="_blank">MedValor</a>
                    <a href="https://guithome.com.br" target="_blank">Guilherme Thomé</a>
                </div>

                <div class="footer-section">
                    <h3>Contato</h3>
                    <a href="mailto:contato@thera.tech">contato@thera.tech</a>
                    <a href="mailto:guilherme@guithome.com.br">guilherme@guithome.com.br</a>
                </div>
            </div>

            <div class="csv-section">
                <a href="https://grupocsv.com" target="_blank" class="csv-logo-link">
                    <img src="marca_csv_neg.png" alt="Grupo CSV" class="csv-logo">
                </a>
                <p class="csv-text">Uma empresa do Grupo CSV – Cuidados em Saúde com Valor</p>
                <p class="copyright">Copyright © 2025 | TheraTech® | Todos os direitos reservados</p>
            </div>
        </div>
    </footer>
</body>
</html>
```

---

**Criado para**: Thera - Cuidado Inteligente  
**Parte do**: Grupo CSV - Cuidados em Saúde com Valor
