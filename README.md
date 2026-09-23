# AKCESS Terminal — versões

O `versao.json` deste repositório é o que o AKCESS Terminal instalado consulta ao abrir
e a cada 6 horas para saber se saiu versão nova. Os instaladores vão anexados aos
*releases*.

O código-fonte fica em outro repositório, privado. Aqui é público só para o programa
poder baixar a atualização sem token nenhum embutido no `.exe`.

Publicado por `installer\publicar.ps1` — não edite o `versao.json` à mão: o `sha256`
tem de bater com o instalador, senão o AKCESS recusa o arquivo e não atualiza ninguém.
