# Como Configurar o setup local

### Instalar SetupLocal
- Instalar [JDK 8](https://drive.google.com/file/d/1_0uoGegV5532hgNLyfIpiV5SIXUU4wJn/view?usp=drive_link)
- Criar a pasta PrintOrtolook no seguinte caminho ```C:/PrintOrtolook```
- Baixar [SetupLocalUpdate](https://github.com/convexus-source/convexus-source.github.io/raw/master/SetupLocalUpdate.jar) e colar na pasta Inicializar do Windows (```%APPDATA%/Microsoft/Windows/Start Menu/Programs/Startup```)

- Reiniciar o computador OU Iniciar o ```SetupLocalUpdate.jar``` com dois click
- Verificar se o download será iniciado após o computador reiniciar.
- Acesse [localhost:8080/properties/all](http://localhost:8080/properties/all) para acessar o mac. 

### Configurar Impressora
- Criar a pasta PrintOrtolook no seguinte caminho ```C:/PrintOrtolook```
- Criar arquivo ```impressora.convexus``` com o nome da impressora no seguinte formato ```name.print.ortolook=NOME_DA_IMPRESSORA``` (Respeitando letras maiúsculas e minúsculas) [exemplo](./impressora.convexus)
  > O nome do arquivo é composto de ```impressora``` (nome do arquivo) + ```.convexus``` (extensão)  
  
  > O nome da impressora pode ser obtido na Propriedade da impressora.
  ![image](https://user-images.githubusercontent.com/24610869/225085313-fbd23408-ce67-4658-bc28-a582de909d93.png)

### Configurar Navegador (Chrome) 
- Ao acessar dttsistemas.com.br deve habilitar `Apps no dispositivo`  
![image](https://github.com/user-attachments/assets/1e30be23-6239-4b38-939f-d33cebe698e5)



### Configurar Navegador (Chrome DEPRECIADO) 
- Copie o link a seguir ```chrome://flags/#block-insecure-private-network-requests``` cole na barra de pesquisa do navegador.
- Altere a flag “Block insecure private network requests.” de “default” para “Disabled”.
- Reinicie o navegador.
![image](https://user-images.githubusercontent.com/24610869/150806805-aad13afb-10ba-404d-964e-b5ade09dcd35.png)
