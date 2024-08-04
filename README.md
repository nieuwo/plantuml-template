# plantuml-template

@startuml

title Template

skinparam linetype ortho

left to right direction

skinparam backgroundColor transparent

skinparam padding 20
'skinparam nodesep 100
skinparam ranksep 70

usecase P0 as "P0"
rectangle A as "A"

' P0 requests A
P0 --> A

@enduml
