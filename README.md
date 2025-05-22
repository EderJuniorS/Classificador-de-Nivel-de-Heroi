# 🏆 Classificador de Nível de Herói  

**Um projeto simples em JavaScript que determina o nível de um herói com base em sua experiência (XP).**  

## 📝 Descrição  

Este projeto classifica o nível de um herói de acordo com a quantidade de experiência (XP) adquirida. O programa verifica o XP e retorna o nível correspondente, seguindo a seguinte tabela:  

| XP            | Nível       |  
|---------------|-------------|  
| ≤ 1.000       | Ferro       |  
| 1.001–2.000   | Bronze      |  
| 2.001–5.000   | Prata       |  
| 5.001–7.000   | Ouro        |  
| 7.001–8.000   | Platina     |  
| 8.001–9.000   | Ascendente  |  
| 9.001–10.000  | Imortal     |  
| ≥ 10.001      | Radiante    |  

Ao final, o programa exibe a mensagem:  
**"O Herói de nome {nome} está no nível de {nivel}"**  

## 🚀 Como Usar  

1. **Modifique as variáveis no código:**  
   - Altere `nome` para o nome do seu herói.  
   - Altere `xp` para a quantidade de experiência desejada.  

2. **Execute o código:**  
   - No terminal, rode:  
     ```bash
     node index.js
     ```  

3. **Veja o resultado:**  
   - O programa exibirá o nível do herói com base no XP fornecido.  

## 📋 Exemplo  

```javascript
let nome = "Guerreiro Imortal";
let xp = 7500; // Ouro
```
**Saída:**  
```
O Herói de nome Guerreiro Imortal está no nível de Ouro
```

## 📌 Melhorias Futuras  

- [ ] Permitir entrada de dados via terminal (`prompt` ou `readline`).  
- [ ] Adicionar validação para garantir que o XP seja um número positivo.  
- [ ] Transformar em uma função reutilizável.  

## 🤝 Contribuição  

Contribuições são bem-vindas! Sinta-se à vontade para abrir **issues** ou **pull requests** com melhorias.  

---

⭐ **Se gostou do projeto, deixe uma estrela no GitHub!** ⭐  

🔗 **Link do repositório:** [https://github.com/EderJuniorS/Classificador-de-Nivel-de-Heroi](https://github.com/EderJuniorS/Classificador-de-Nivel-de-Heroi)  

---  

**Desenvolvido com 💙 por Éder Junior**  

---

### 📄 Licença  

Este projeto está sob a licença **MIT**. Consulte o arquivo [LICENSE](LICENSE) para mais informações.  

---  

🔹 **Tecnologias usadas:** JavaScript, Node.js  

🔹 **Tags:** #JavaScript #Games #Logic #BeginnerFriendly
