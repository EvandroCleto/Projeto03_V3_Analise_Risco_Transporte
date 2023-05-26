# Projeto03_V3_Analise_Risco_Transporte

Formação Cientista de Dados da Data Science Academy.

Curso: Big Data Real-Time Analytics Com Python e Spark Versão 3.0

Projeto com Feedback: Análise de Risco no Transporte Público

Objetivo deste projeto foi responder 10 perguntas de negócios através de análise de dados usando os pacotes parkSQL, PandaSQL, SQLAlchemy, MySql e Docker

Este foi um projeto desafiador pois foi desenvolvido no Linux Ubuntu 22.04, através de virtualização pelo Oracle VM VirtualBox executado de uma máquina com Windows 11.

Esse projeto teve início baixando um dataset do Microsoft Excel do link https://data.world/makeovermonday/2018w51, no Linux.

O dataset foi carregado através do pacote Pandas, que também foi usado para análise exploratória, em formato de dataframe.

O dataframe do Pandas foi gravado em uma tabela no SGBD MySQL e para a conexão do SGBD ao Python, foi usada a biblioteca SQLAlchemy.

Para extração dos dados do MySQL foi usada a biblioteca PandaSQL, usando o SQLAlchemy como conector com Python.

Já o MySQL foi instalado à partir de um container Docker, que devido à falta de suporte à KVM pelo VirtualBox foram instalados via command line. 

O guia para a instalação do Docker está aqui: https://github.com/EvandroCleto/Projeto03_V3_Analise_Risco_Transporte/blob/main/Guia_Instalacao_Docker_Linux.txt

E o guia para instalação do container com o MySQL está aqui: https://github.com/EvandroCleto/Projeto03_V3_Analise_Risco_Transporte/blob/main/Guia_Instalacao_MySQL_Docker.txt

As 10 pergutas de negócio foram respondidas usando querys pelo SparkSQL, que alimentaram gráficos plotados através do pacote Matplotlib. 