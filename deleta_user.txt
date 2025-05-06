#!/bin/bash

echo "Excluindo usuario..."

userdel -r carlos 
userdel -r maria
userdel -r joao
userdel -r debora
userdel -r sebastiana
userdel -r roberto
userdel -r josefina
userdel -r amanda
userdel -r rogerio

echo "Excluindo diretórios..."

rm -rf /publico
rm -rf /adm
rm -rf /ven
rm -rf /sec

echo "Excluindo grupos..."

groupdel GRP_ADM
groupdel GRP_VEN
groupdel GRP_SEC