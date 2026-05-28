# Login-IOS
Tela de login básica com campos de texto para nome de usuário e senha, um botão de login e labels informativas, tudo construído programaticamente em Swift.

Guia 6

## Entendendo as Constraints:


- **centerXAnchor.constraint(equalTo: view.centerXAnchor)**: Centraliza o elemento horizontalmente na view principal.
  
- **topAnchor.constraint(equalTo: view.safeAreaLayoutGuide.topAnchor, constant: 50)**: Posiciona o elemento a 50 pontos da parte superior da "safe area" (região visível da tela, levando em conta a barra de status, notch, etc.).
  
- **widthAnchor.constraint(equalTo: view.widthAnchor, multiplier: 0.8)**: Define a largura como 80% da largura da view principal.
- **heightAnchor.constraint(equalToConstant: 40)**: Define uma altura fixa de 40 pontos.
  
- **leadingAnchor.constraint(equalTo: view.leadingAnchor, constant: 20) e trailingAnchor.constraint(equalTo: view.trailingAnchor, constant: 20)**: define as margens laterais
