```mermaid
flowchart TD
    A([Inicio])
    A --> B[/Capturar datos del asistente/]
    B --> C{¿Datos completos?}

    C -->|Sí| D{¿El correo existe?}
    C --> |No| F[/Mostrar Datos faltantantes/]

    D --> |Sí|E[/Advertencia/]
    D --> |No|G[Registro]

    E --> H([Fin])
    F --> H([Fin])
    G --> H([Fin])
    ```
    