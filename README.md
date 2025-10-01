# Lista de Compras Simples 🛒

Um aplicativo Flutter simples e intuitivo para gerenciar listas de compras, desenvolvido para facilitar o controle de compras do dia a dia.

## 📱 Sobre o Projeto

Este aplicativo foi desenvolvido em Flutter para criar e gerenciar listas de compras de forma prática e organizada. Com uma interface limpa e funcional, permite aos usuários adicionar, marcar e remover itens de suas listas de compras.

## ✨ Funcionalidades

### 🎯 Principais Recursos
- ➕ **Adicionar Itens**: Adicione novos itens à sua lista de compras
- ✅ **Marcar como Comprado**: Marque itens como comprados com checkbox
- 🗑️ **Remover Itens**: Remova itens individuais da lista
- 🧹 **Limpar Lista**: Limpe toda a lista de uma vez
- 📊 **Estatísticas**: Visualize total de itens, comprados e restantes
- 🔍 **Validação**: Evita duplicação de itens na lista

### 🎨 Interface
- Design Material 3 moderno
- Visual intuitivo com ícones claros
- Feedback visual para itens comprados (riscado)
- Cores diferenciadas para status dos itens
- Mensagens de confirmação para ações importantes
- Estado vazio com ilustração amigável

## 🛠️ Tecnologias Utilizadas

- **Flutter** - Framework principal
- **Dart** - Linguagem de programação
- **Material Design 3** - Sistema de design
- **Widgets Flutter**:
  - `StatefulWidget` para gerenciamento de estado
  - `ListView.builder` para lista dinâmica
  - `TextField` para entrada de dados
  - `Checkbox` para marcar itens
  - `AlertDialog` para confirmações
  - `SnackBar` para feedbacks

## 📂 Estrutura do Projeto

```
lib/
├── main.dart          # Arquivo principal com toda a lógica do app
test/
├── widget_test.dart   # Testes do aplicativo
```

## 🚀 Como Executar

### Pré-requisitos
- Flutter SDK instalado
- Dart SDK (incluído com Flutter)
- Emulador ou dispositivo físico

### Passos para execução
1. Clone o repositório:
   ```bash
   git clone https://github.com/ViniciusXR/lista_compras_simples.git
   ```

2. Navegue até o diretório do projeto:
   ```bash
   cd lista_compras_simples
   ```

3. Instale as dependências:
   ```bash
   flutter pub get
   ```

4. Execute o aplicativo:
   ```bash
   flutter run
   ```

## 📋 Como Usar

1. **Adicionar Item**: Digite o nome do item no campo de texto e pressione "Adicionar" ou Enter
2. **Marcar como Comprado**: Clique no checkbox ao lado do item
3. **Remover Item**: Clique no ícone de lixeira e confirme a remoção
4. **Limpar Lista**: Use o ícone "Limpar lista" no AppBar para remover todos os itens
5. **Visualizar Estatísticas**: Veja o resumo de itens totais, comprados e restantes

## 🎯 Recursos Técnicos

### Gerenciamento de Estado
- Utiliza `StatefulWidget` com `setState()` para reatividade
- Listas sincronizadas para itens e status de compra

### Validações
- Prevenção de itens duplicados
- Validação de campos vazios
- Confirmações para ações destrutivas

### UX/UI
- Feedback imediato para todas as ações
- Estados visuais claros (comprado/não comprado)
- Interface responsiva e acessível

## 🔧 Configurações

### Dependências Principais
```yaml
dependencies:
  flutter:
    sdk: flutter
  cupertino_icons: ^1.0.8

dev_dependencies:
  flutter_test:
    sdk: flutter
  flutter_lints: ^5.0.0
```

### Versão
- **Versão Atual**: 1.0.0+1
- **SDK Dart**: ^3.9.2

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:
- Reportar bugs
- Sugerir novas funcionalidades
- Melhorar a documentação
- Submeter pull requests

## 📄 Licença

Este projeto está sob a licença especificada no arquivo `LICENSE`.

---
