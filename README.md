# WarehouseGraph_RAG
Airline Warehouse Agent using LangChain: RAG and Cypher Query Generation

## Overview
This project utilizes LangChain to create an intelligent agent designed for interacting with an airline warehouse containing parts and tools for aircraft maintenance. The agent employs Retrieval-Augmented Generation (RAG) to enhance query accuracy and efficiency, and it generates Cypher queries to interact with the airline's warehouse graph database.

## Features
- **Retrieval-Augmented Generation (RAG):** Enhances the agent's ability to generate accurate responses by retrieving parts and tools description.
- **Cypher Query Generation:** Automatically generates Cypher queries to interact with the warehouse graph database, facilitating complex data retrieval and manipulation tasks.
- **Integration with LangChain:** Utilizes LangChain framework to streamline the development of natural language processing and understanding capabilities.

## Graph Database
Graph Databse Schema: See warehouse_db_screenshot.png  
Data used: See warehouse_data.csv

The database contains information about parts and tools for aircraft maintenance. The data is structured to include:

- pickslip id: A unique identifier for each pickslip.
- part id: A unique identifier for each part.
- part category: The category of the part (e.g., consumable, expendable, rotable, etc).
- part description: A detailed description of the part.
- part ata chapter: The ATA chapter that categorizes the part.
- pickslip status: The current status of the pickslip (code for pending/completed/canceled).
- pickslip creator id: The ID of the person who created the pickslip.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Neo4j database 
- OpenAI API key

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure your code adheres to the project's coding standards and include relevant tests.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements
LangChain - The framework used to build the agent.  
Neo4j - The graph database used for data storage and retrieval.  
OpenAI - The service providing the natural language processing capabilities.

## Contact
If you have any questions or feedback, please feel free to contact us at m.vitoropoulou@aegeanair.com, christos.grigoras@aegeanair.com.
