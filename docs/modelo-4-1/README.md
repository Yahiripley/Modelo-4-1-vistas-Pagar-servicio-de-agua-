# Modelo 4+1: Pago de servicio de agua

Esta carpeta organiza la documentación del sistema antes de elaborar los
diagramas. Cada vista tiene su propio espacio para requisitos, decisiones,
descripciones y evidencias del diseño.

## Estructura

| Carpeta | Contenido |
| --- | --- |
| `01-casos-de-uso` | Actores, objetivos, casos de uso y flujos alternos |
| `02-vista-logica` | Entidades, responsabilidades, servicios e interfaces |
| `03-vista-procesos` | Flujo de ejecución, concurrencia, errores y estados |
| `04-vista-desarrollo` | Módulos, paquetes, componentes y dependencias |
| `05-vista-fisica` | Nodos de despliegue, infraestructura e integraciones |
| `06-escenarios` | Escenarios que validan y relacionan las cinco vistas |

## Convenciones

- Los documentos se escriben en español y usan nombres del dominio
  **Pago de servicio de agua**.
- Cada vista debe describir primero el comportamiento y las decisiones; los
  diagramas se agregarán después, cuando el contenido esté confirmado.
- Las decisiones que afecten varias vistas deben enlazarse desde la sección
  correspondiente de cada `README.md`.
- No se agregan datos reales de clientes, cuentas, tarjetas ni credenciales.

## Secuencia de documentación

1. Definir actores y escenarios principales.
2. Identificar entidades y responsabilidades lógicas.
3. Describir el flujo normal y los flujos alternos.
4. Organizar módulos y componentes de desarrollo.
5. Documentar el despliegue y las integraciones externas.
6. Revisar los escenarios para comprobar que las vistas sean consistentes.

Los diagramas se incorporarán en una etapa posterior, sin sustituir la
documentación textual de estas carpetas.
