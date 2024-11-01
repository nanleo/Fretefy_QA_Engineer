# Fretefy | QA Engineer

Bem vindo,

Se você chegou até aqui é porque queremos conhecer um pouco mais sobre as suas habilidades no desenvolvimento de testes automatizados, para isso preparamos um projeto onde você terá que desenvolver um teste que contemple a escrita em gherkin, criação de passo usando SpecFlow (cucumber) e executando usando o driver do Selenium.

Caso você tenha alguma dúvida, pode esclarece-las por email, responderei o mais breve possível: christian.saddock@fretefy.com.br 

Esperamos que você faça tudo o que o projeto especifica, mas se você não conhecer alguma tecnologia, ainda faça aquilo que você domina. Descreve, pode ser na própria Feature de teste, quais foram suas dificuldades, o que teve dúvida ou até mesmo sugestões ;) 

Boa sorte!

# Como começar?

1. Faça o fork do projeto `https://github.com/christiansaddock/Fretefy_QA_Engineer`
2. Faça sua implementação
3. Suba seu código no fork criado
4. Nos avise sobre a finalização da implementação, preferencialmente por email: christian.saddock@fretefy.com.br 🚀


# Atividade

Implementar um teste automatizado na camada de interface a seu critério. O projeto já contem a estrutura basica, e um teste exemplo para que possa analisar qual é o modelo esperado. Pode utilizar outro site e determinar o que deseja validar, o importante é mostrar seu conhecimento sobre o assunto.

### Requisitos
- Crie um novo teste;
- O teste deve ter estrutura semelhante ao teste exemplo;
- O teste deve ter uma ação e um Assert pelo menos;

## Observações
1. Caso não esteja habituado com o formato do projeto, procure referencia nos exemplos ou faça da forma que você julgar melhor.
2. Fique a vontade para incluir mais operações que julgar necessário, mesmo que elas não estejam nos requisitos.
3. Para simplificar abstraimos testes na camada de negócio, mas caso queira implementar, será um diferencial.

## Dicas
1. É preciso instalar o SpecFlow no Visual Studio 😉
2. Acha que pode melhorar alguma coisa que está implementada, vá em frente 😎
3. Tem algum conhecimento extra que gostaria de demonstrar, a hora é agora 🏆

A definição da URL base a ser testada está no config do projeto:
![image](https://github.com/christiansaddock/Fretefy_QA_Engineer/assets/12252684/73d6ac32-c2fb-476f-96f0-70f20fdceaaf)

Para rodar o teste, é preciso ter o specflow instalado no projeto:

![image](https://github.com/christiansaddock/Fretefy_QA_Engineer/assets/12252684/2099df15-f4d9-4304-8fd2-23b811e36da8)

Depois só dar build na solução:

![image](https://github.com/christiansaddock/Fretefy_QA_Engineer/assets/12252684/d7557616-aa8e-43b6-932f-7a783fd85657)

E colocar para rodar os testes: 

![image](https://github.com/christiansaddock/Fretefy_QA_Engineer/assets/12252684/58447970-9848-4c1d-a6c6-7d0519575ce6)

Uma dica é rodar em modo de depuração(debug) após colocar um breakpoint no teste e então usar o F11 para acompanhar o passo-a-passo que o teste precisa executar até chegar no assert final ;)
