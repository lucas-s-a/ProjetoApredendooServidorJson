# ProjetoApredendooServidorJson
Criar um arquivo Json onde você pode usar uma extensão Thunder Client no próprio VScode que fará teste de requisições HTTP, na API criada

Passo a Passo:

1º - Para usar, após abrir a pasta no VScode ,abrir o terminal e iniciar o servidor usando o comando 
node server.js ou npm start

Após aparecer OK ("Abriu") como confirmação de servidor iniciado

Usar o Thunder Client ou qualquer outra que faça requisições API para executar os teste (Ele será o seu cliente API que 
irá consumir seus dados (Criar, Atualizar ,Ver ou Deletar))

o link padrão será Localhost:3000(Caminhos = ["/Medicamentos","/Vitaminas",ou "/Lanches_Rápidos"] (caminhos no arquivo db.json)

e você poderá ver os dados de cada caminho.
caso queira buscar um dado só usar a ID (Também descrita no arquivo db.json)
