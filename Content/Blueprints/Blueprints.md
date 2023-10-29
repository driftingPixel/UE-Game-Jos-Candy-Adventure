# Blueprints

This is documentation of blueprints for Jo's Candy Adventure Game

## Detail documntation

### Character/Actor blueprints

```mermaid

classDiagram
    BP_PlatformCharacter <|-- BP_Jo
    class BP_PlatformCharacter{
        +die()
    }
    class BP_Jo{
        - Camera camera
        - IA_Jump
        - IA_Move
    }

```
