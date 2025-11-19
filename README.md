# Pizza Rex Simulator

Pizza Rex Simulator is a three-phase queueing simulation designed to model the daily operations of a pizzeria, developed at Metropolia University of Applied Sciences.

The simulator helps users analyze staffing levels, customer flow, pricing, operational capacity and profitability under various scenarios.

---

## Features

- Three-phase event-driven simulation model
- Realistic pizzeria workflow: customer arrivals and seating queue, waiter order handling, kitchen process, takeway handling
- Adjustabe parameters: staff and table count, pricing and ingredient costs, distribution averages, variances and probabilties, discount days
- Full GUI and queue visualization
- Detailed results: revenue, waiting times, throughput, utilization etc.

## Technical Specifications

- **Language**: Java
- **Libraries**: JavaFX, Hibernate
- **Build tool**: Maven
- **Database**: Local SQL database
- **Testing**: JUnit

---

## Getting Started

Requires:
- JDK 8+
- Maven 3.6+
- IDE compatible with Java

1. **Clone the repository**:  
   ```bash  
   git clone https://github.com/Alvaade/queue-simulator.git  
   cd queue-simulator  
   ```  

2. **Build the project**:  
   ```bash  
   mvn clean install
   ```  

3. **Run the application**:  
   ```bash  
   mvn exec:java -Dexec.mainClass="Main"
   ```    

---

## Documentation (FINNISH)

-[Project Documentation](./project_document_fin.pdf)

-[User Manual](./pizza_rex_manual_fin.pdf)

---

## Contributors
- **Ade Aiho**
- **Heta Hartzell**
- **Mika Laakkonen**
- **Jonne Roponen**
