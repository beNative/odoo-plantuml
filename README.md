
# Odoo Data Model Documentation

This repository contains PlantUML diagrams documenting the data models for different versions of Odoo. These diagrams are intended to help developers and users understand the structure and relationships of the various models within Odoo.

## Getting Started

To view and edit these PlantUML files, you'll need a PlantUML viewer or editor. You can use tools like [PlantUML QEditor](http://plantuml.com/qa) or any IDE that supports PlantUML plugins (such as Visual Studio Code, IntelliJ IDEA, or Eclipse).

### Prerequisites

- [Java](https://www.java.com/en/download/) (required for PlantUML)
- PlantUML (you can install it using your preferred package manager or download it directly from [PlantUML's website](http://plantuml.com/download))
- A PlantUML viewer or editor

### Viewing the Diagrams

To view the PlantUML diagrams, you can use any of the following methods:

1. **Using PlantUML Online Server**: You can paste the PlantUML code into the [PlantUML Online Server](http://www.plantuml.com/plantuml/uml/) to generate the diagram.

2. **Using a Local PlantUML Installation**:
    ```sh
    java -jar plantuml.jar path/to/diagram.puml
    ```

3. **Using IDE Plugins**: Many IDEs support PlantUML through plugins. Install the appropriate plugin for your IDE and open the `.puml` files to view the diagrams.

## Branches for Different Odoo Versions

Each version of Odoo has its corresponding diagrams placed in branches named after the Odoo version. For example, the diagrams for Odoo 17 are in the `17` branch.

### Accessing a Specific Version

To access the diagrams for a specific version of Odoo:

1. Go to the main page of the repository.
2. Click on the "Branch" dropdown.
3. Select the branch corresponding to the Odoo version you are interested in (e.g., `17` for Odoo 17).

Alternatively, you can clone the repository and checkout the desired branch:
```sh
git clone https://github.com/yourusername/odoo-data-models.git
cd odoo-data-models
git checkout 17  # Replace '17' with the desired Odoo version branch
```

## Contributing

We welcome contributions from the community! If you have suggestions for improving the diagrams or notice any discrepancies, please open an issue or submit a pull request.

### How to Contribute

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Open a pull request.

## License

This project is licensed under the Apache License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [PlantUML](http://plantuml.com/) for providing the tools to create UML diagrams.
- The Odoo community for their continuous support and contributions to the Odoo platform.

---

Feel free to explore the diagrams and contribute to the project!
