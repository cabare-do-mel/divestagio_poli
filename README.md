# DivEstagio
Sistema para a Divisão de Estágio da Poli-UPE


### Especificações dos Casos de Uso
[Especificações](./Casos%20de%20Uso/Especifica%C3%A7%C3%B5es/)

### Diagrama dos Casos de Uso
```plantuml
@startuml
left to right direction
actor UsuárioVisitante as uv
actor Sistema as sys
package UsuárioLogado as ul{
  actor Professor as p
  actor Administrador as adm
  actor Aluno as al
}
package AppDivisãoDeEstágio {
  usecase "Ver Perfil" as UC1
  usecase "Ver Modelo de Relatório" as UC2
  usecase "Iniciar cadastro de estágio" as UC3
  usecase "Casdrastrar empresa" as UC4
  usecase "Ver Perfil de Professor" as UC5
  usecase "Acompanhar entrega de relatório" as UC6
  usecase "Assinar relatório" as UC7
  usecase "Aprovar castrastro de empresa" as UC8
  usecase "Cadastrar Professor" as UC9
  usecase "Editar Perfil" as UC10
  usecase "Coletar Assinatura" as UC11
  usecase "Fazer Login" as UC12
  usecase "Cadastrar Aluno" as UC13
  usecase "Ver Solicitações de Empresas" as UC14
  usecase "Ver Solicitações de Alunos" as UC15
  usecase "Ver Professores" as UC16
  usecase "Ver Alunos" as UC17
  usecase "Ver Solicitações de Alunos" as UC18
  usecase "Fazer Logout" as UC19
  usecase "Ver Notas" as UC20
  usecase "Ver Perfil do Aluno" as UC21
  usecase "Ver Perfil do Professor" as UC22
}

UC11 <-- sys


adm --> UC5
adm --> UC8
adm --> UC7
adm --> UC9
adm --> UC14
adm --> UC16
adm --> UC17
adm --> UC21
adm --> UC22


p --> UC6
p --> UC7
p --> UC15
p --> UC17
p --> UC18
p --> UC21

al --> UC2
al --> UC3
al --> UC4
al --> UC5
al --> UC6
al --> UC20
al --> UC22

uv --> UC12
uv --> UC13

ul --> UC1
ul --> UC10
ul --> UC19
@enduml
```

![DivEstagio](./Casos%20de%20Uso/Diagrama-UML.png)