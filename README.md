Atividade Multidisciplinar – 3º Trimestre
Ciência de Dados e Técnicas Integradas em IA

1. Viés na Inteligência Artificial (Preconceito dos Dados)A IA não tem sentimentos nem opiniões próprias; ela apenas copia o que está nos dados que recebeu. O viés acontece quando esses dados vêm acompanhados de preconceitos humanos, omissões ou erros de contagem.   Exemplo prático: Se ensinarmos um sistema de reconhecimento facial usando apenas fotos de pessoas de pele clara, a IA terá grande dificuldade para reconhecer pessoas de pele escura. Ela não faz isso por malícia, mas sim porque não recebeu dados suficientes para aprender sobre a diversidade humana.
   
3. Overfitting (O Famoso "Decorar sem Entender")O overfitting (ou superajuste) acontece quando o modelo decora os dados de treino palavra por palavra, em vez de entender a lógica do assunto.   Exemplo da prova: Pense em um aluno que decora o gabarito exato de um simulado. Se a prova oficial tiver as mesmas perguntas, ele tira 10. Mas se a ordem das opções mudar ou aparecer uma pergunta inédita, ele tira 0 porque não aprendeu a matéria de verdade.   A solução: Para evitar o overfitting, sempre testamos a IA com dados novos que ela jamais viu antes, garantindo que ela realmente aprendeu a generalizar.

4. Como Funcionam os Algoritmos de Recomendação?Plataformas como TikTok, YouTube e Instagram monitoram seus passos: quais vídeos você curte, quanto tempo passa olhando cada publicação e em que horário você acessa.   O objetivo: Prever o que você quer ver em seguida para prender sua atenção no aplicativo.   O perigo da Bolha Digital: Ao mostrar apenas o conteúdo que você já gosta, o algoritmo esconde opiniões contrárias e temas novos. Isso cria uma "bolha", onde você consome apenas o mesmo tipo de informação, limitando sua visão de mundo.

5. Limpeza de Dados e Remoção de Colunas Sensíveis
Antes de colocar os dados para treinar uma Inteligência Artificial, precisamos passar por uma etapa de faxina chamada pré-processamento. Nem todas as informações de uma tabela ajudam a IA a aprender, e algumas podem até violar a privacidade das pessoas.
O que é o df.drop? É um comando em programação (usado na biblioteca Pandas do Python) que serve para apagar colunas inteiras de uma tabela de dados.   Por que remover dados sensíveis? Colunas como Nome, CPF, Endereço ou Número da Conta identificam uma pessoa diretamente. Para cumprir as leis de privacidade (como a LGPD) e garantir que a IA não seja preconceituosa, essas colunas são eliminadas.   Exemplo prático: Se quisermos prever se um aluno vai passar de ano, precisamos analisar a nota e a frequência dele. A coluna Cor Favorita ou o Nome do Aluno só trariam distração e risco de vazamento de dados, por isso usamos o df.drop para apagá-las antes do

6 Normalização de Dados (Escalonamento Min-Max)Os computadores não entendem o contexto das coisas como os humanos; eles enxergam apenas a grandeza dos números.   
O problema da escala: Se tivermos uma tabela com a Idade de uma pessoa (ex: 17 anos) e o Salário dela (ex: R$ 3.500,00), a IA vai achar que o Salário é 200 vezes mais importante do que a Idade, simplesmente porque o número 3500 é muito maior do que 17.   


Conclusão Em suma, a Inteligência Artificial não é uma ferramenta mágica, mas sim um sistema que depende diretamente da qualidade dos dados que recebe. Para que a IA funcione de forma justa, segura e eficiente, é fundamental realizar o pré-processamento correto dos dados — limpando informações sensíveis com o df.drop e ajustando escalas numéricas através da normalização.   
