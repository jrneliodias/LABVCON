# Laboratório Virtual de Engenharia de Controle - LABVCON

Esse projeto tem como objetivo desenvolver um software que simula um laboratório de engenharia de controle para um usuário que não tenha acesso aos instrumentos 
básicos necessários. 

## 🤝 Autores

* Antonio Moises Nascimento Araújo ([Lattes](http://lattes.cnpq.br/3944952251812665))
* Nélio Dias Santos Júnior ([Lattes](http://lattes.cnpq.br/0040496197667559))
* Profª Rejane de Barros Araújo ([Lattes](http://lattes.cnpq.br/8760830024389437))
* Caio César Silva de Carvalho ([Lattes](http://lattes.cnpq.br/0242293088447650))

## ⚙ Instalação
O softaware já é um executável, porém é necessário instalar o Matlab Runtime 2019b. O MATLAB Runtime é um conjunto autônomo de bibliotecas 
compartilhadas que permite a execução de MATLAB compilado, aplicativos Simulink ou componentes. Abaixo segue o link para o download conforme seu sistema operacional.

* [Windows 64-bit](https://ssd.mathworks.com/supportfiles/downloads/R2020b/Release/7/deployment_files/installer/complete/win64/MATLAB_Runtime_R2020b_Update_7_win64.zip)
* [Linux 64-bit](https://ssd.mathworks.com/supportfiles/downloads/R2020b/Release/7/deployment_files/installer/complete/glnxa64/MATLAB_Runtime_R2020b_Update_7_glnxa64.zip)

Para mais informações, pode-se acessar a documentação do copilador nesse link: [Matlab Runtime](https://www.mathworks.com/help/compiler/matlab-runtime.html)

Feito isso, pode-se baixar o executável no botão **"Code"** na parte superior da página e em seguida clicar em **"Download Zip"**. 
Pode-se baixar também nesse [link](https://github.com/jrneliodias/LABVCON/archive/refs/heads/main.zip)


## 💻  Manual de utilização

Para a utilização da primeira tela, devemos seguir a ordem numerada na figura abaixo. Temos duas interfaces no software: Estruturas PID e Sintonia PID. 

### Estruturas PID

   <p align="center">
   <img width = 900 src=https://github.com/jrneliodias/Imagens_LABVCON/blob/main/Estruturas%20PID%202.png>
   </p>
   
   
 <ol>
 <li>Tipos de estruturas
    <p> Aqui você escolhe entre os tipos de estruturas clássicas disponíveis: </p>
 <ul>
   <li> PID Ideal</li>
   <li> PID Paralelo</li>
   <li> PID Serie </li>
   <li> I+PD </li>
   <li> PI+D </li>
 </ul>
</li>                <!-- Aqui está a tag de fechamento </li> -->
   
   
<li>Ganhos do controlador
   <p>Na parte 2, devemos inserir os coeficientes Ki, Kc e Kd dos controladores na estrutura selecionada </p> 
</li>
<li>Configurações de simulação
    <img src="https://github.com/jrneliodias/Imagens_LABVCON/blob/main/Configura%C3%A7%C3%B5es%20de%20simula%C3%A7%C3%A3o.png"
        align="right"/>
    <p> Após inserir os ganhos do controlador, clica-se no botão <b>Configurações de Simulação</b> e abre-se a janela ao lado.  </p>
    <p><b>Tempo de Simulação:</b> Insere-se o tempo total de simulação desejada.  </p>
    <p><b>Sinal de Referência:</b> Aqui configura-se quantas referências sua simulação irá conter. Pode-se escolher até 3 amplitudes de sinais
       e os 3 momentos que eles irão mudar.  </p>
   <p><b>Planta:</b> Aqui configura-se a função de transferência da planta do sistema. Especifica-se os coeficientes do polinômio do numerador e denominador
   separando-os por espaço. Exemplo: s^2 + 3s + 5  será [2 3 5] </p>
   <p><b>Atraso:</b> configura-se o atraso de transporte da planta se houver. </p>
   
   </li>
</ol>

