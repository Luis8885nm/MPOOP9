@startuml
class Event{
    +StartTime: DataTime
    +nombre: String
    +RegistrationClosed: boolean
    +execute()
}

class Hola{
    +perro int
    -gato: String
}

+class Foo{
    +estado: boolean
}

Hola<|-- Foo: interfaz

@enduml 

