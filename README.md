# 🎮 Amiibo App

Aplicativo iOS desenvolvido com **SwiftUI** utilizando a arquitetura **MVVM**. Ele consome a [Amiibo API](https://amiiboapi.com/) para exibir uma lista de personagens Amiibo, mostrando informações como imagem, nome, série de jogos e tipo (Card ou Figure).

---

## 🚀 Funcionalidades

- Lista de Amiibos com:
  - 📸 Imagem
  - 🎮 Jogo
  - 🏷️ Tipo (Card ou Figure)
- Ícones representativos para tipo
- Suporte à **internacionalização (i18n)** 🇧🇷 🇺🇸
- Arquitetura limpa com separação de responsabilidades (MVVM)
- Testes Unitários e de UI

---

## 🛠️ Tecnologias e Ferramentas

- ✅ Swift 5.9+
- ✅ SwiftUI
- ✅ MVVM
- ✅ Alamofire (para requisições HTTP)
- ✅ Async/Await
- ✅ XCTest (Testes Unitários e de Interface)
- ✅ Suporte a Localização com `.strings`

---

## 📦 Estrutura do Projeto
amiibo_app/
├── Models/
├── ViewModels/
├── Views/
├── Services/
├── Resources/
│   ├── Localizable.strings
├── Tests/
│   ├── amiibo_appTests/
│   └── amiibo_appUITests/


----

## 🧪 Rodando os Testes

Para executar os testes unitários e de UI no Xcode:

```bash
⌘ + U

Certifique-se de que o destino selecionado seja My Mac (iOS Simulator) e que o esquema do projeto esteja ativo.
```

## 📲 Requisitos
	•	iOS 16+
	•	Xcode 15+
