1 - Para o Projeto Webservices libs necessárias 
a) jersey-bundle 1.17.1 
b) jackson-jaxrs 1.9.2 
c) mysql-conector 5.1.36 

2 - Para o Projeto gerenciar-clientes libs necessárias 
a) jstl 1.2 
b) bootstrap-4.5.2

3 - Para todos 
a) Java 8
b) ide eclipse versão mais atual

4 - Executar o script abaixo para criar banco, mysql.

CREATE DATABASE IF NOT EXISTS banco2 /*!40100 DEFAULT CHARACTER SET latin1 */; USE banco2; -- MySQL dump 10.13 Distrib 8.0.16, for Win64 (x86_64)
-- Host: localhost Database: banco2

-- Server version 5.7.26-log

/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT /; /!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS /; /!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION /; SET NAMES utf8 ; /!40103 SET @OLD_TIME_ZONE=@@TIME_ZONE /; /!40103 SET TIME_ZONE='+00:00' /; /!40014 SET @OLD_UNIQUE_CHECKS=@@UNIQUE_CHECKS, UNIQUE_CHECKS=0 /; /!40014 SET @OLD_FOREIGN_KEY_CHECKS=@@FOREIGN_KEY_CHECKS, FOREIGN_KEY_CHECKS=0 /; /!40101 SET @OLD_SQL_MODE=@@SQL_MODE, SQL_MODE='NO_AUTO_VALUE_ON_ZERO' /; /!40111 SET @OLD_SQL_NOTES=@@SQL_NOTES, SQL_NOTES=0 */;

-- -- Table structure for table cliente
DROP TABLE IF EXISTS cliente; /*!40101 SET @saved_cs_client = @@character_set_client /; SET character_set_client = utf8mb4 ; CREATE TABLE cliente ( id int(11) NOT NULL AUTO_INCREMENT, cpf varchar(15) DEFAULT NULL, nome varchar(30) DEFAULT NULL, sobrenome varchar(50) DEFAULT NULL, PRIMARY KEY (id) ) ENGINE=InnoDB AUTO_INCREMENT=32 DEFAULT CHARSET=latin1 COMMENT='Tabela de clientes.'; /!40101 SET character_set_client = @saved_cs_client */;

-- -- Dumping data for table cliente
LOCK TABLES cliente WRITE; /*!40000 ALTER TABLE cliente DISABLE KEYS /; INSERT INTO cliente VALUES (9,'12345678910','Bernadete','Silvay'),(10,'12345678911','Felisberta','de Souza'),(12,'04296997947','Elizangela Cristina','Silva'),(13,'12399999999','Maristela dos Santos','Mattos'),(14,'12349999999','Rubens da Fonsca','e Mariano'),(15,'12345999997','Afonso Bianchi','da Silva'),(17,'12345688888','Genilval dos Santos','Ramos'),(18,'12345677777','Valesca Macarenhas','Albuquerque'),(19,'12345678666','Karina Bittencout','dos Santos'),(21,'23456789555','Mariangela Fernanda','da Silva'),(22,'12345678912','Teste12','Teste12'),(23,'57489632154','Teste dia 07-01','Teste dia 07-01'),(30,'89547123549','Herminio','de Souza'),(31,'a','a','a'); /!40000 ALTER TABLE cliente ENABLE KEYS /; UNLOCK TABLES; /!40103 SET TIME_ZONE=@OLD_TIME_ZONE */;

/*!40101 SET SQL_MODE=@OLD_SQL_MODE /; /!40014 SET FOREIGN_KEY_CHECKS=@OLD_FOREIGN_KEY_CHECKS /; /!40014 SET UNIQUE_CHECKS=@OLD_UNIQUE_CHECKS /; /!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT /; /!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS /; /!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION /; /!40111 SET SQL_NOTES=@OLD_SQL_NOTES */;

-- Dump completed on 2021-07-08 21:12:29
