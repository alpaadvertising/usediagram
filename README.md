## System Model - Use Case Diagram

```mermaid
graph TD
    User[User] -->|Authenticate| Authentication[User Authentication]
    User -->|Search Content| Search[Search Functionality]
    User -->|Access Features| Features[Access Content]
    Authentication -->|Login| System[System Backend]
    Search -->|Retrieve Results| System
    Features -->|Display Data| System
