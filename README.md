- [Manutenção do Running](#manutenção-do-running)
  - [Verificação das Fontes](#verificação-das-fontes)
  - [Verificação do Nível de água dos tanques](#verificação-do-nível-de-água-dos-tanques)
  - [Verificação das Bombas e Ventilador (ON/OFF)](#verificação-das-bombas-e-ventilador-onoff)
    - [Procedimento de verificação das Bombas e Ventilador (TE-101)](#procedimento-de-verificação-das-bombas-e-ventilador-te-101)
      - [**Bomba de Bacia**](#bomba-de-bacia)
      - [**Bomba de Tanque**](#bomba-de-tanque)
      - [**Ventilador**](#ventilador)
    - [Procedimento de verificação das Bombas e Ventilador (TE-102)](#procedimento-de-verificação-das-bombas-e-ventilador-te-102)
      - [**Bombas**](#bombas)
      - [**Ventilador**](#ventilador-1)
  - [Limpeza dos coolers da fonte](#limpeza-dos-coolers-da-fonte)
  - [Verificação de agulhas](#verificação-de-agulhas)
  - [Verificar conexão de saída da fonte](#verificar-conexão-de-saída-da-fonte)
  - [Verificar aperto dos parafusos dos bornes](#verificar-aperto-dos-parafusos-dos-bornes)
  - [Finalização](#finalização)


# Manutenção do Running
*Documentação complementar do anexo L IT 08.05*

<div style="text-align:center"><img src="https://i.imgur.com/Lk1tzLt.png" width="120" height="105"/></div>

<br>

<mark><span style="color:red;font-style:italic">**ATENÇÃO: ESSE EQUIPAMENTO OPERA COM TENSÕES DE 220VAC E 24VDC! PARA SUA SEGURANÇA, DESLIGUE A CHAVE GERAL, DISJUNTORES E REMOVA A TOMADA DE ALIMENTAÇÃO DO EQUIPAMENTO. CERTIFIQUE-SE QUE NADA LHE OFERECE RISCO.**</span></mark>

Para auxiliar na verificação dos equipamentos, imprimas os templates a seguir:
[Template running TE-101 (INV-126)](https://inovaeletronicos.sharepoint.com/:w:/r/sites/metodoseprocessos/_layouts/15/Doc.aspx?sourcedoc=%7BFD571D04-3C41-4714-A6DC-71A00C815301%7D&file=Template%20Running%20TE-101%20(INV-126).docx&action=default&mobileredirect=true&wdsle=0)
[Template running TE-102 (INV-155)](https://inovaeletronicos.sharepoint.com/:w:/r/sites/metodoseprocessos/_layouts/15/Doc.aspx?sourcedoc=%7B788B6548-8D90-4361-B398-3C5E044807F9%7D&file=Template%20Running%20TE-102%20(INV-155).docx&action=default&mobileredirect=true&wdsle=0)
[Template running Híbrido TRH-01](https://inovaeletronicos.sharepoint.com/:w:/r/sites/metodoseprocessos/_layouts/15/Doc.aspx?sourcedoc=%7B1FD02B8D-A8FD-4D81-9CE9-2458F0760E0F%7D&file=Template%20Running%20TE-101%20(INV-126)1.docx&action=default&mobileredirect=true&wdsle=0) 
## Verificação das Fontes

* Remova a tampa traseira inferior do equipamento, soltando os parafusos de fixação. 
    * <span style="color:red"> **CUIDADO: a tampa pode cair ao soltar os parafusos.**</span>

    ![](https://i.imgur.com/kcuPlJI.jpg)

* Puxe o gabinete das fontes para fora da máquina, tomando cuidado com os cabos elétricos.

    ![](https://i.imgur.com/H2g4GUp.jpg)

* Desconecte os terminais das fontes do Running e puxe-a para fora parcialmente, a fim de ter livre acesso aos seus terminais para medição.

* Utilize o multímetro <em>**MU-153**</em>.
    
   
* Conecte o multimetro MU-153 aos terminais da fonte.


* **Anote o valor medido no MU-153**, faça o mesmo para a outra fonte.

    
## Verificação do Nível de água dos tanques

* Puxe o gabinete dos tanques para fora da máquina, tomando cuidado com o nível da água e com os cabos elétricos.

* Abra o tanque e verifique o nível e qualidade da água. Complete o nível caso necessário ou substitua o fluído caso haja corpos estranhos, limo ou mofo.
 
* Verifique se há entupimentos ou qualquer anomalias nas bombas.
    
## Verificação das Bombas e Ventilador (ON/OFF)

O teste consiste em medir a intensidade da corrente elétrica durante o acionamento dos componentes. Para cada 'slot' repita o procedimento:

* Utilize o Multímetro <em>**MU-153.**</em>

    
* Selecione a escala de corrente contínua pelo botão **'DCI'** e em seguida, a opção **10A** através do botão **'F2'**.

### Procedimento de verificação das Bombas e Ventilador (TE-101)
    
<span style="color:blue"> **Utilize a configuração do controlador INV-126601-01 para as chaves de configuração dos Runnings.**</span>

<div style="text-align:center"><img src="https://i.imgur.com/TawY7EH.png"/></div>

#### **Bomba de Bacia**
* Conecte a ponteira negativa do multímetro à agulha GND **[6]** do slot e a ponteira positiva à agulha da Bomba da Bacia **[9]**. Isso fará com que o multímetro feche o circuito, acionando a bomba.

* **Anote o valor medido** e preencha o campo <em>**'Bomba de Bacia'**</em> para o slot em análise na tabela anteriormente aberta.


#### **Bomba de Tanque**
* Conecte a ponteira negativa do multímetro à agulha GND **[6]** do slot e a ponteira positiva à agulha da Bomba do Tanque **[8]**. Isso fará com que o multímetro feche o circuito, acionando a bomba.

* **Anote o valor medido** e preencha o campo <em>**'Bomba do Tanque'**</em> para o slot em análise na tabela anteriormente aberta.

#### **Ventilador**
* Conecte a ponteira negativa do multímetro à agulha GND **[6]** do slot e a ponteira positiva à agulha do Ventilador **[5]**. Isso fará com que o multímetro feche o circuito, acionando a bomba.

* **Anote o valor medido** e preencha o campo <em>**'Ventilador'**</em> para o slot em análise na tabela anteriormente aberta.

    * <span style="color:red">**ATENÇÃO: cuidado ao realizar o procedimento. Encostar nas outras agulhas do slot com a ponteira causará curto-circuito, capaz de danificar os equipamentos.**</span>
    * <span style="color:green">**DICA: Remova a agulha e encoste as ponteiras do multímetro diretamente ao tubo do receptáculo para evitar escorregamento das mesmas.**</span>

### Procedimento de verificação das Bombas e Ventilador (TE-102)

<span style="color:blue"> **Utilize a configuração padrão para os controladores da família INV-155 para as chaves de configuração dos Runnings.**</span>

<div style="text-align:center"><img src="https://i.imgur.com/9YwBIIu.png"/></div>

#### **Bombas**
* Conecte a ponteira positiva do multímetro à agulha VCC **[1]** do slot e a ponteira negativa à agulha da Bomba **[4]**. Isso fará com que o multímetro feche o circuito, acionando a bomba.

* **Anote o valor medido** e preencha o campo <em>**'Bomba'**</em> para o slot em análise na tabela anteriormente aberta.

#### **Ventilador**
* Conecte a ponteira negativa do multímetro à agulha GND **[2]** do slot e a ponteira positiva à agulha do Ventilador **[3]**. Isso fará com que o multímetro feche o circuito, acionando a bomba.

* **Anote o valor medido** e preencha o campo <em>**'Ventilador'**</em> para o slot em análise na tabela anteriormente aberta.

    * <span style="color:red">**ATENÇÃO: cuidado ao realizar o procedimento. Encostar nas outras agulhas do slot com a ponteira causará curto-circuito, capaz de danificar os equipamentos.**</span>
    * <span style="color:red">**ATENÇÃO: caso seja necessário realizar a troca de algum ventilador do running, deve-se sempre utilizar ventiladores da marca IMOBRÁS.**</span>
    * <span style="color:green">**DICA: Remova a agulha e encoste as ponteiras do multímetro diretamente ao tubo do receptáculo para evitar escorregamento das mesmas.**</span>
    * <span style="color:orange">**Depois da verificação, carregue todos os slots com as peças padrão e execute um ciclo. Os controladores não devem apresentar erro.**</span>

## Limpeza dos coolers da fonte

* Com um **pincel anti-estático**  remova a poeira e detritos dos coolers.

* Utilize ar comprimido para limpar o dissipador na parte interna da fonte. Lembre-se de travar a hélice para evitar que ela rotacione com a passagem do ar, evitando danos.

## Verificação de agulhas

* Verifique o estado das agulhas de todos os slots, checando se as mesmas ainda possuem capacidade de contato elétrico, ausência de danos, carbonizações, desgastes e alinhamento.

* Verifique se ainda possuem força na mola ou se estão travadas, bem como o seu modelo, que é direfente para cada tipo de produto.

* Substitua as agulhas carbonizadas ou danificadas.

## Verificar conexão de saída da fonte

* Remova os cabos dos conectores e verifique se os terminais da fonte apresentam sujeita, oxidação, carbonização ou derretimento. Certifique-se os mesmos ainda possuem capacidade de uma boa condução elétrica.

* Verifique se os cabos estão oxidados ou danificados ou com qualquer outro problema na sua ponta. Caso seja necessário, refaça a ponta do cabo utilizando terminal tubular de bitola compatível com os equipamentos.

* Estando tudo em ordem, insira novamente os cabos e reapete o terminal da fonte com firmeza, utilizando as ferramentas adequadas.

## Verificar aperto dos parafusos dos bornes

* Verifique o aperto de todas as conexões elétricas do equipamento, chicotes de slots, PCIs, soldas em agulhas e chicotes e conectores de bombas e ventiladores.

* Verifique as conexões elétricas dos disjuntores, tomadas, conectores de alimentação de fontes.

* Verifique as conexões dos cabos da bateria e barramentos.

## Finalização

* Após a realização do procedimento, registre na tabela de manutenção periódica a data da sua realização.

* Empurre para dentro o gabinete dos tanques de bombas e das baterias, tomando cuidado com os cabos elétricos.

* Feche as tampas traseiras do equipamento.
