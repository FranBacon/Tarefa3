# Tarefa3
AWS CloudFormation
Objetivo: Implementar minha primeira Stack usando AWS CloudFormation, automatizando a criação de um recurso
Criei: template para criar um Bucket S3 automaticamente.
Apliquei o cod abaixo 
{
  "AWSTemplateFormatVersion": "2010-09-09",
  "Description": "Template CloudFormation criado por Fran Medeiros - Criação de bucket S3",
  "Resources": {
    "BucketFran": {
      "Type": "AWS::S3::Bucket",
      "Properties": {
        "BucketName": "bucket-fran-cloudformation-20251027"
      }
    }
  }
}
Inicialmente deu um erro, descobri que já havia testado com esse nome.
Tive que refazer e na segunda vez deu certo. 
Printei o processo de tentativa e erroa até a criação correta. 
