# Teste de PSI 1 - Turno 2 - Versão 2

## Informação do aluno

    Nome: Pablo

Teste termina às 13:25.

Escreve as respostas dentro dos blocos correspondentes.
Substitui as reticências pelo que é pedido em cada pergunta.
Não desformates o documento.

### P1. Indica o que é impresso pelo seguinte código. Justifica a tua resposta

    ulong uL = ulong.MaxValue;

    Console.WriteLine(uL + 1);

P1 - Resposta

    0 
    é um overflow e a variavel tem um valor e quando adiciono +1 ele "da a volta" e volta a zero.

### P2. Considera o seguinte código com um *bug*

    float f = double.MaxValue;

    Console.WriteLine(f);

### Indica uma possível correção para que o código não apresente erros. Explica porque foi necessário fazer essa correção

P2 - Resposta

    double f = double.MaxValue;
     pq nao posso converter float para double, pq double é maior q float.

### P3. Escreve um programa que solicite ao utilizador dois números reais e apresente o resultado do segundo (base) elevado ao primeiro (expoente). Não podes usar um método da classe Math para obter o resultado

P3 - Resposta

    ...

### P4. Estás na pasta raiz do teu repositório local, onde atualizaste um ficheiro de nome 'Perks.cs'. Queres enviar **apenas** esta atualização para o teu repositório remoto. Indica os comandos necessários. A mensagem de commit deve ser apropriada

P4 - Resposta

    git add Perks.cs
    git commit -m "enviar a atualizaçao do ficheiro "Perks.cs" "
    git push
    
    
    
