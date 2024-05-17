## MyCEP
- para busca cep do brasil pela linha de comando

### Start
1. go build -o nomeParaSeDoSeuBinario
2. ./nomeParaSeDoSeuBinario 01001000

### Como executar esse comando em qualquer pasta ?
- isso server para vc nao fica precisando entrar na pasta onde esta o seu binario e executar ele partir dela
- para isso so precisamso adicionar o caminho do nosso binario na variavel path **Isso so funcionar para sistema basiado no UNIX[macos / linux]**

### Macos
1. entramos na pasta onde esta nosso binario e rodamos no terminal ```pwd``` isso vai trazer o diretorio atual
2. abrimos o **~/.zshrc** - isso para o sistema com o chip da apple
3. e adicionamos ``` export PATH=$PATH:/caminhoRetornadoDoPWD ```

### LINUX e MacOs sem CHIP da apple
- ai voces procura na net haha... 