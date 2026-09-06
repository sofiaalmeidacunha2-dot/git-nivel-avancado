# git-nivel-avancado

Atividade avaliativa nível avançado.



PARTICIPANTES:

NATHALIA

MARIA PAULA

SOFIA



O que já fizemos

1\. Branches individuais



Cada integrante criou seu próprio branch a partir do main, seguindo o padrão feature/nome-da-pessoa



2\. Alterações e commits



Cada integrante fez pelo menos 1 alteração no projeto dentro do próprio branch e registrou com commit.



3\. Push e Pull Requests



Cada branch foi enviado ao GitHub (git push) e um Pull Request foi aberto do branch individual para o main.



4\. Revisão entre integrantes



Cada Pull Request foi revisado e aprovado por outra integrante do grupo (nunca pelo próprio autor), usando a funcionalidade de Review changes → Approve do GitHub



5\. Conflito de merge — provocado e resolvido



Durante o merge do PR #2 (feature/sofia), o GitHub acusou conflito no arquivo README.md, porque duas integrantes alteraram a mesma parte do arquivo em branches diferentes (uma delas já havia sido mesclada ao main antes da outra tentar mesclar).



Como resolvemos:



Atualizamos o branch feature/sofia com o main mais recente (git pull origin main).

O Git marcou o trecho conflitante no arquivo com <<<<<<<, ======= e >>>>>>>.

Comparamos as duas versões do texto e decidimos manualmente qual conteúdo manter (unindo as partes relevantes de cada uma).

Removemos as marcações de conflito, salvamos o arquivo, e finalizamos com git add ., git commit e git push origin feature/sofia.

O Pull Request foi mesclado normalmente depois da resolução.


Issues abertas (melhorias futuras)



O que ainda falta fazer

&#x20;Finalizar a revisão e o merge de todos os Pull Requests pendentes.

&#x20;Criar a tag v1.0 no commit final (git tag v1.0 + git push origin v1.0).

&#x20;Deletar os branches já mesclados, local e remotamente.

