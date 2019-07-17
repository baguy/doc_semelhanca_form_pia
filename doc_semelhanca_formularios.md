# Plano Individual de Atendimento

### Documentação de semelhanças entre formulários tratadas diferentemente para tentativa de padronização

#### Mayra Dantas Bueno
###### GLPI 7397

##### Renda
- _Criança_
  - Item: 3.22
  - Campos divergentes: apresenta seleção de `sim ou não` e campo aberto para inserir valor.
- _Idoso_
  - Item: x
  - Campos de renda inclusos em renda familiar e renda de membros da família núcleo e família extensa.
  - Campos divergentes: não apresenta campo **renda** referente à renda pessoal.
- _Pessoa com deficiência (PcD)_
  - Item: x
  - Campos divergentes: igual **Idoso**.
  

 Renda      | *pessoal* | *familiar* | *grupo familar* | *família extensa*
----------- | --------- | ---------- | --------------- | ----------------
**Crianca** |     o     |      o     |        o        |         x
**Idoso**   |     x     |      o     |        o        |         o
 **PcD**    |     x     |      o     |        o        |         o
 
 
 ###### `Padronização`
  Nos três formulários, incluir o campo aberto de **renda pessoal** e campo de seleção de **renda familiar**, incluir em *grupo familiar* e *família extensa* campo de seleção e campo aberto de renda.
  
---

##### Responsáveis (ou pais ou curador)
- _Criança_
  - Item: 1.2
  - Campos de responsáveis identificados com pai e mãe.
  - Campo de **endereço** e **telefone** apenas abaixo dos dados da mãe.
  - Campos divergentes: em `pais ou responsáveis` não apresenta campo **profissão** e apresenta campo **filiação**.
  - Obs: no formulário online, todos os responsáveis possuem campos de endereço e telefone.
- _Idoso_
  - Item: 2
  - Campos de pai e mãe separados de responsável ou curador.
  - Campos divergentes: em `responsável ou curador` apresenta campo **profissão** e não apresenta campo **vínculo/filiação**.
- _Pessoa com deficiência (PcD)_
  - Item: 2
  - Campos divergentes: igual **Idoso**.
 

 Responsáveis | *profissão* | *filiação*
 ------------ | ----------- | ----------
**Crianca**   |      x      |     o
**Idoso**     |      o      |     x
 **PcD**      |      o      |     x
 

###### `Padronização`
  Nos três formulários, incluir **endereço**, **telefone**, **vínculo** e **profissão/ocupação** para responsáveis. Também incluir campo separado de endereço atual para formulário de Criança e Adolecente.
  
  ---

##### Grupo Familiar
- _Criança_
  - Item: 3.9
  - Campos divergentes: apesenta campo **data de nascimento** e apresenta **renda** como seleção de opções.
- _Idoso_
  - Item: 6 (9 no formulário online)
  - Campos divergentes: apesenta campo **idade** e campo aberto para preenchimento de **renda**.
- _Pessoa com deficiência_
  - Item: 6
  - Campos divergentes: igual **Idoso**.

Grupo familiar|  *DN*   | *idade* | *renda*
------------- | ------- | ------- | ------
**Crianca**   |    o    |    x    | seleção
**Idoso**     |    x    |    o    | aberto
**PcD**       |    x    |    o    | aberto


###### `Padronização`
Em todos os três formulários, incluir ambos campos de **renda** como seleção e campo aberto no item *grupo familiar* e substituir todos os campos de idade para **data de nascimento** apenas.

---

##### Família extensa e vínculos comunitários
- _Criança_
  - Item: 3.20
  - Família extensa e vínculos comunitários adicionados no mesmo item.
  - Campos divergentes: não apesenta campo **nome da empresa que filhos trabalham** (formulário online: profissão), não apresenta **renda**, apresenta **relação com a criança/adolescente** como campo aberto, **endereço**, não apresenta **telefone**.
- _Idoso_
  - Família extensa e vínculos comunitários separados em dois itens.
  - Item: 7/8 (10/11 no formulário online)
  - Campos divergentes: apesenta campo **nome da empresa que filhos trabalham** (formulário online: trabalho/empresa), **renda** como campo aberto, aparesenta **endereço** e **telefone** em vínculos comunitários, apresenta seleção de **atividades comunitárias** em família extensa.
- _Pessoa com deficiência_
  - Família extensa e vínculos comunitários separados em dois itens.
  - Item: 7/8
  - Campos divergentes: igual **Idoso**.

Família extensa |  *DN*   | *idade* | *renda* | *endereco* | *relação* | *telefone* | *atividades comunitárias*
| ------------- | ------- | ------- | ------- | ---------- | --------- | ---------- | ------------------------
**Crianca**     |    x    |    o    |    x    |      o     |     o     |     x      |          x
**Idoso**       |    x    |    o    |  aberto |      x     |     x     |     x      |          o
**PcD**         |    x    |    o    |  aberto |      x     |     x     |     x      |          o

Vínculos comunitários |  *DN*   | *idade* | *renda* | *endereco* | *relação* | *telefone* | *atividades comunitárias*
| ------------------- | ------- | ------- | ------- | ---------- | --------- | ---------- | ------------------------
**Crianca**           |    x    |    o    |    x    |      o     |     o     |     x      |          x
**Idoso**             |    o    |    x    |    x    |      o     |     x     |     o      |          x
**PcD**               |    o    |    x    |    x    |      o     |     x     |     o      |          x

 ###### `Padronização`
 Cadastro de *família extensa* e *vínculos comunitários* separados, campo de *nome da empresa que filhos trabalham* substituído por **ocupação**, **atividades comunitárias** para ambos.  **Renda** como campo de seleção e campo aberto para *família extensa* e não para *vínculos comunitários*.

---

##### Atividades (esporte, cultura e lazer)
- _Criança_
  - Item: 4 (4.1 Esporte, 4.2 Cultura e 4.3 Lazer)
  - Campos divergentes: apesenta campo aberto para descição (`caso pratique: quais e periodicidade; se não: interesse em praticar e dificuldades de inserção`). Itens separados para esporte, cultura e lazer.
- _Idoso_
  - Item: 14 (14.1 Esporte, 14.2 Atividade cultural e 14.3 Costuma sair de casa)
  - Campos divergentes: apesenta seleção de `sim e não` e campos separados  **qual?** e **onde**. Não apresenta opção de preenchimento para *lazer*.
- _Pessoa com deficiência_
  - Item: 14 (14.1 Esporte, 14.2 Atividade cultural e 14.3 Costuma sair de casa)
  - Campos divergentes: apesenta seleção de `sim e não` e campos separados  **qual?** e **onde**. Não apresenta opção de preenchimento para *lazer*, e apresenta campo de seleção `sim e não` para **necessidade de algum tipo de apoio**.

Atividades    | *onde* | *qual* | *lazer* | *se não* | *necessidade de algum tipo de apoio*
------------- | ------ | ------ | ------- | -------- | -----------------------------------
**Crianca**   |    x   |    x   |    o    |    o     |                x
**Idoso**     |    o   |    o   |    x    |    x     |                x
**PcD**       |    o   |    o   |    x    |    x     |                o

###### `Padronização`
Nos três formulários, designar campos abertos separados para **qual**, **periodicidade**, **interesse e dificuldade de inserção**, **necessidade de apoio** e **lazer** em todos.

---

##### Plano de ação
- _Criança_
  - Itens: 3.21 e 10
  - 3.21 Ações para capacitação e empregabilidade no mercado de trabalho
    - Campos divergentes: apesenta campo aberto para **prazo**, não apresenta campo para **objetivo** (subentendido que o objetivo é capacitação/empregabilidade) nem **assinatura**.
  - 10 Plano de ação da rede
    - Campos divergentes: apresenta campo aberta para **assinatura**, não apresenta opções de **prazo** (`curto, médio e longo`).
- _Idoso_
  - Itens: 18 (Plano de Ação da Rede) e 19 (Plano de Ação Familiar)
  - Campos divergentes: apesenta campo **equipamento** e **Assinaturas e seus respectivos registros profissionais nos Conselhos de Classe**.
- _Pessoa com deficiência_
  - Item: 18 (Plano de Ação da Rede) e 19 (Plano de Ação Familiar)
  - Campos divergentes: igual **Idoso**.

Planos de ação   |     *prazo*     | *equipamento* | *assinatura* | *registros profissionais*
---------------- | --------------- | ------------- | ------------ | ------------------------
**Crianca 3.21** |     aberto      |       x       |       x      |           x
**Criança 10**   | data início/fim |       x       |       o      |           x
**Idoso**        | data início/fim |       o       |       o      |           o
**PcD**          | data início/fim |       o       |       o      |           o

###### `Padronização`
Em todos os **planos de ação**, incluir campos de prazo **inicial** e **final** como data, incluir **equipamento**, assinatura como **nome**, **registro** e **conselho**.
