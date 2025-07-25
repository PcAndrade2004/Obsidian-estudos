# Ferramentas de compressão

A compressão de arquivos é utilizada quando queremos diminuir a quantidade de espaço em um conjunto de de dados. Muito utilizado para diminuir a quantidade de dados que serão enviados na rede. Algumas ferramentas de empacotamento devem ser utilizadas em conjunto a algumas ferramentas de compressão 
* Gzip
Compressão de dados, utilizamos o formato *gz*. Podemos usar esse comando da seguinte forma : ```gzip arquivos.txt``` 
```bash 
gzip 'ACESSOS-1-ANYDESK.XLSX'

//SAIDA 
ACESSOS-3-ANYDESK.xlsx.gz
```

* bzip2
Compressão de dados, utilizamos o formato *bz2*. Executamos esse comando da seguinte forma : ```bzip2 arquivo.txt```

```bash 
bzip2 'ACESSOS-2-ANYDESK.XLSX'

//SAIDA 
ACESSOS-1-ANYDESK.XLSX.bz2
``` 

* xz
Compressão de dados, utilizamos o formato **xz**. Executamos esse comando da seguinte
forma : ``` xz arquivo.txt```
```bash 
xz 'ACESSOS-3-ANYDESK.XLSX'

//SAIDA
'ACESSOS-2-ANYDESK.XLSX.xz'
``` 

## Descompactar Arquivos
Para descomprimir os arquivos acimas devemos usar os seguintes comandos.

* bzip2 
	Devemos usar o **bunzip2**, esse comando descomprimi o arquivo **.bz2** 

* Gzip
	Devemos usar o **gunzip**, esse comando descomprimi o arquivo **.gz**

* xz
	Devemos usar o **unxz**, esse comando descomprimi o arquivo **.xz**