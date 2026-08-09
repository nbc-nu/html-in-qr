# html-in-qr
Use sua imaginação e coloque seu site INTEIRO dentro de um qrcode. Exatamente isso. a unica coisa fora do qrcode é o servidor mais o html estara no qrcode mesmo. muita gente tenta o data:text/html, mais não funciona em versões mais recentes então disponibilizo isto para os que desejam hospedar INTEIRAMENTE seus sites *(com limite de 5kb que é o limite em um qrcode)* igual um pendrive! 

# Porque hospedar um site em um QRCODE?
hospedar um site em um qrcode pode ser muito mais pratico do que pagar para alguem guardar seu html (claro que o github permite isso) mais se quizer algo mais compacto, ja o qrcode deixa tudo mais simples! é só ir escaniar e o html sera carregado em sua tela! Sem nenhum link especifico ele esta armazenado no SEU QRCODE. basicamente jogar um arquivo .html em um gerador de qrcodes.

# como fazer seu qrcode em 2 minutos
existem 3 passos supermega faceis para fazer isso com esse repositorio.
1. escreva seu site em html, CSS e JS (css e js opicional, é só porque tambem roda no qrcode).
2. cole o html com o link desse repositorio com isso no final ?t=html&c= <--- cole seu html ali no parametro de URL "c"
3. cole todo o link jundo no editor de qrcode sem quebra de linhas e sem espaços (opicional se quizer minimizar o arquivo para caber no qrcode)

# A ciencia por traz
esse repositorio simplesmente imita o data:text/html;, que é uma resposta do codigo que escreveu sendo exibido na tela. é exatamente isso. ele lê o html no parametro "c" e exibe na tela. simples. da até para utilizar este repositorio para hospedar um outro html qualquer. só o link que ninguem vai querer digitar de tão grande, anão ser que mande para copiar e colar. por isso serve no qrcode. a pessoa não precisa reescrever o HTML inteiro para acessar seu site, o html ja esta escrito no qrcode

# Para facilitar
aqui esta ja o link como deve colocar no qrcode
https://nbc-nu.github.io/html-in-qr/?t=html&c= <---- cole seu html em uma linha aqui
