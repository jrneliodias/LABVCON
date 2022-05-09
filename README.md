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
   
   ![alt text](https://github.com/jrneliodias/Imagens_LABVCON/blob/main/Estruturas%20PID%202.png)
   
   1. **Tipos de estruturas**
       
       Aqui você escolhe entre os tipos de estruturas clássicas disponíveis: 
        
        - PID Ideal
        - PID Paralelo
        - PID Serie 
        - I+PD
        - PI+D 
    
   2. **Ganhos do controlador**
  
        Na parte 2, devemos inserir os coeficientes Ki, Kc e Kd dos controladores na estrutura selecionada 
        
       <img src="https://render.githubusercontent.com/render/math?math=e^{i \pi} = -1">
