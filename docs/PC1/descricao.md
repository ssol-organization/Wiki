# Descrição

<div style="text-align: justify">
O projeto funciona através de processamento de imagens, utilizando o aplicativo Ftool que calcula e demonstra os diagramas de esforços existentes na viga. 
</div>

<div style="text-align: justify">
Nele se encontra uma bancada fixa, que possui uma câmera disposta a uma certa distância que permite a identificação adequada das forças. A bancada possui dois extremos, nos quais ficam posicionados a viga e a câmera.
</div>

<div style="text-align: justify">
O experimento consiste na construção da bancada, disposta em uma caixa transparente (ou branca), que permite todas as medidas e iluminação necessárias para a realização do experimento. Além disso, a caixa também contém os apoios que são fundamentais para fixar a viga e a câmera de forma estável e vital para uma coleta precisa de dados.
</div>

<div style="text-align: justify">
A viga é elaborada por algum material que é fácil visualizar a deflexão, por exemplo uma placa de fibra de média densidade, composta por fibras de madeira, pois é o material ideal para a análise de deformação, visto que outros materiais, como o aço, necessitam de forças elevadas para se deformarem.
</div>

<div style="text-align: justify">
Tal viga, com suas medidas definidas, é milimetrada, pois é necessário saber o local exato de posicionamento dos apoios e das aplicações das forças. A viga, que contém furos em sua direção horizontal, permite a aplicação de momentos, deixando a estrutura um pouco mais próxima da vida real.
</div>

<div style="text-align: justify">
Cada apoio, carga e momento aplicado é representado por meio de corpos de prova com massas pré determinadas, cada qual com sua própria identificação de intensidade e de tipo (carga distribuída ou concentrada, no caso das carga aplicadas, e qual o gênero, no caso dos apoios).
</div>

<div style="text-align: justify">
A captação dessas informações é feita por meio de um módulo câmera para o Raspberry Pi - disposta sobre um suporte ajustável em uma distância suficiente para que se enquadre toda a viga - e que também permite o envio dos dados via Wi-Fi para o celular do aluno, em um aplicativo desenvolvido pelo grupo para tal propósito.
</div>

<div style="text-align: justify">
Através do processamento de imagens, esse aplicativo, que tem como base o software “Ftool”, identifica e diferencia todas as informações presentes nos corpos de prova e, em seguida, faz os cálculos das reações de apoio, plota os diagramas de esforços internos e repassa esses resultados para o usuário.
</div>

<div style="text-align: justify">
O projeto até então tem a viabilidade apenas em aplicações de forças no sentido vertical e de momento, vindo de cima e, é claro, as forças vindas dos apoios, cada apoio será representado via uma identificação também.
</div>

<div style="text-align: justify">
Substancialmente, o projeto faz essa identificação e dimensiona virtualmente como a viga se comporta e logo em seguida realiza os cálculos com o Ftool e envia via Wi-Fi para o celular do aluno, os cálculos e diagramas.
</div>