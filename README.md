# 🔄 Conversor Item.txt ↔ Item.xml

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![MuOnline](https://img.shields.io/badge/MuOnline-Tool-blue.svg)](https://github.com)

## 📋 Sobre o Projeto

Este é um conversor web desenvolvido especialmente para servidores de **MuOnline**, permitindo a conversão bidirecional entre os formatos **Item.txt** e **Item.xml**. A ferramenta facilita o trabalho de administradores de servidores que precisam migrar ou editar configurações de itens do jogo.

## ✨ Funcionalidades

- ✅ **Conversão TXT → XML**: Transforma arquivos Item.txt para o formato XML
- ✅ **Conversão XML → TXT**: Transforma arquivos Item.xml para o formato TXT
- ✅ **Interface Intuitiva**: Design moderno e responsivo
- ✅ **100% Client-Side**: Todas as conversões são feitas no navegador (privacidade garantida)
- ✅ **Download Direto**: Baixe os arquivos convertidos instantaneamente
- ✅ **Sem Instalação**: Basta abrir o arquivo HTML no navegador

## 🎮 Para que serve?

Esta ferramenta é voltada para administradores de servidores privados de **MuOnline**, facilitando:

- Migração de configurações entre diferentes versões de servidor
- Edição em massa de configurações de itens
- Backup e conversão de arquivos de configuração
- Compatibilidade entre diferentes sistemas de servidor

## 🚀 Como Usar

1. **Abra o arquivo** `conversor.html` em qualquer navegador moderno
2. **Selecione o arquivo** que deseja converter (Item.txt ou Item.xml)
3. **Clique em "Converter"** para processar o arquivo
4. **Baixe o resultado** clicando no botão de download

### Formato TXT → XML
Converte arquivos no formato texto tradicional para o formato XML estruturado, incluindo todos os atributos necessários como:
- Índices e nomes dos itens
- Estatísticas (dano, defesa, durabilidade)
- Requisitos de personagem
- Classes compatíveis

### Formato XML → TXT
Converte arquivos XML de volta para o formato de texto tradicional, mantendo a estrutura e formatação originais.

## 💻 Tecnologias Utilizadas

- HTML5
- CSS3 (com design gradiente moderno)
- JavaScript (Vanilla JS)
- DOM Parser para processamento XML

## 📦 Estrutura do Projeto

```
conversor-xml/
├── conversor.html    # Aplicação principal
└── README.md         # Documentação
```

## 🎨 Características Técnicas

- **Design Responsivo**: Funciona perfeitamente em desktop e mobile
- **Validação de Dados**: Tratamento de erros durante a conversão
- **Escape de Caracteres**: Tratamento adequado de caracteres especiais em XML
- **Parsing Inteligente**: Reconhece automaticamente seções e índices
- **Preservação de Dados**: Mantém todos os atributos e propriedades dos itens

## 📝 Formato dos Arquivos

### Item.txt
```
//Type   Slot   Skill   Width   Height   ...
0
    123      0      0      1      2   "Item Name"   50   ...
```

### Item.xml
```xml
<?xml version="1.0"?>
<ItemList>
    <Section Index="0">
        <Item Index="123" Name="Item Name" Slot="0" ... />
    </Section>
</ItemList>
```

## ⚠️ Requisitos

- Navegador moderno (Chrome, Firefox, Edge, Safari)
- JavaScript habilitado
- Nenhuma dependência externa necessária

## 🤝 Contribuindo

Sugestões e melhorias são sempre bem-vindas! Sinta-se à vontade para:

1. Fazer um fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abrir um Pull Request

## 📄 Licença

Este projeto é de código aberto e está disponível para uso livre.

## 👤 Autor

**GBSOficial**

- Ferramenta desenvolvida para a comunidade MuOnline
- Criada para facilitar o trabalho de administradores de servidores

## 🌟 Agradecimentos

Agradecimentos à comunidade MuOnline por todo o suporte e feedback que tornam ferramentas como esta possíveis!

---

**⭐ Se esta ferramenta foi útil para você, considere dar uma estrela no projeto!**

*Desenvolvido com ❤️ para a comunidade MuOnline*

