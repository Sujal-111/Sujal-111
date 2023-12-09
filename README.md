graph TD
  A(User) -->|Enters Details| B(Reservation System)
  B -->|Processes| C{Database}
  C -->|Stores Data| B
  B -->|Notifies| A
  B -->|Manages Tables| D(Restaurant)

  style A,B,C,D fill:#E6E6FA,stroke:#000

