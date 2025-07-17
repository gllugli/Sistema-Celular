# 📱 Sistema Celular - Projeto em C#

Este projeto simula o funcionamento básico de dois tipos de smartphones — **iPhone** e **Nokia** — utilizando os conceitos de **POO (Programação Orientada a Objetos)** em C#. O foco principal está na herança, abstração e polimorfismo.

## 📌 Objetivos

- Implementar uma classe abstrata `Smartphone` com propriedades e métodos comuns.
- Criar subclasses `Iphone` e `Nokia`, que herdam de `Smartphone` e implementam o método abstrato `InstalarAplicativo`.
- Simular ações básicas como ligar, receber ligação e instalar aplicativos.

---

## 📁 Estrutura do Projeto

```
Sistema_Celular/
├── Models/
│   ├── Smartphone.cs
│   ├── Iphone.cs
│   └── Nokia.cs
└── Program.cs
```

- `Smartphone.cs`: classe abstrata base com propriedades como número, modelo, IMEI e memória, além dos métodos `Ligar`, `ReceberLigacao` e o método abstrato `InstalarAplicativo`.
- `Iphone.cs` e `Nokia.cs`: classes concretas que herdam de `Smartphone` e implementam o método `InstalarAplicativo` de acordo com o sistema operacional correspondente.
- `Program.cs`: classe principal que instancia objetos das classes `Iphone` e `Nokia`, simula a instalação de aplicativos e exibe as ações no console.

---

## ▶️ Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/gllugli/Sistema-Celular.git
   ```

2. Abra o projeto no Visual Studio ou outro editor de sua preferência.

3. Compile e execute o projeto.

---

## 💻 Exemplo de Saída

```plaintext
Instalando WhatsApp no iPhone na App Store
Instalando Instagram no Nokia na Play Store
```

---

## 📚 Conceitos Trabalhados

- Classes e Objetos
- Herança
- Abstração
- Polimorfismo
- Encapsulamento (uso de modificadores de acesso como `public` e `protected`)

---

## ✍️ Autor

Desenvolvido por Gabriel Lugli
