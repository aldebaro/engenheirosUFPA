# engenheirosUFPA
Registro histórico de (futuros) engenheiros da UFPA

Caso não tenha familiaridade com git e github, veja o vídeo "Git e Github para iniciantes" em https://www.youtube.com/watch?v=UMhskLXJuq4

Os alunos de Projetos de Engenharia II da UFPA são convidados a participar.

1) Usando a plataforma Latttes - http://lattes.cnpq.br/ - cadastrar o seu currículo. Para terem ideia de como fica um currículo na academia de um pesquisador de renome, visualizar em http://lattes.cnpq.br/0261838076132788 o do prof. Antonio José Simões Costa, paraense, formado pela UFPA e atualmente professor da UFSC. Notem que obtive o URL acima olhando no "Endereço para acessar este CV:" mostrado no Lattes do prof. Simões. Será esse endereço que irão fornecer após terem seus currículos cadastrados. Para terem ideia de como alunos no inicio da carreira se cadastram no Lattes, vide os currículos de colegas que estão no LaPS http://www.laps.ufpa.br ou LASSE  http://www.lasse.ufpa.br, principalmente dos mais novos.

2) Cada turma de Projetos de Engenharia II deve criar um único arquivo fonte para toda a turma, em linguagem C, com o nome ufpa_projetos2_ano_mesDeInicio.c. Por exemplo, ufpa_projetos2_2016_outubro.c é o primeiro arquivo, já criado. Daí cada discente matriculado na turma deve editar o arquivo, colocando o seu nome, matricula, mantra pessoal e informando o URL do seu Lattes. Um exemplo de arquivo inicial segue abaixo.

3) Depois de baixar o arquivo .c, inserir sua contribuição, faça um "pull request" para que o administrador do repositório atualize a versão no "branch" principal e sua modificação passe a ser visível para toda a turma.

\#include <stdio.h>
int main() {

	puts("Esse programa \"apresenta\" a turma de 2011, 1o semestre");
	puts("Matricula - Nome - Curriculo Lattes");
	puts("A partir daqui cada um insere suas linhas, guardando uma linha em branco:\n");

	puts("0800494001 - Gonçalves Dias - http://lattes.cnpq.br/026183807613242428");
	puts("Meu mantra: A vida é luta renhida que aos fracos abate e aos fortes só faz exaltar.\n");

	puts("0800400141 - Sicrano de tal - http://lattes.cnpq.br/02618380761424788");
	puts("Meu mantra: No pain, no gain.\n");

	puts("08045440141 - Macunaima - http://lattes.cnpq.br/02618380763222788");
	puts("Meu mantra: Pouca saúde e muita saúva, os males do Brasil são!\n");
}
