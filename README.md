# Drools Rules Application Guide

## Overview
This guide will help you run and use the Drools Rules application effectively. Follow these steps to get started.

## Prerequisites
- Java JDK 8 or higher
- Maven installed
- Your favorite IDE (Eclipse, IntelliJ IDEA, or VS Code)

## Installation Steps

1. Clone the repository:
```bash
git clone https://github.com/mono789/drools_rules.git
```
2. Navigate to project directory:
```bash
cd drools-project
```
3. Build the project:
```bash
mvn clean install
```

## Running the Application
1. Start the application using Maven:
```bash
   mvn spring-boot:run
```

## Adding New Rules

1. Open  ```bash src/main/resources/rules/rules.drl```
2. Add new rules following this format:
```bash
   rule "Rule Name"
    when
        // Conditions
    then
        // Actions
    end
```

## Troubleshooting
1. Verify rule syntax in .drl files
2. Check KieSession configuration
3. Ensure facts are properly inserted
4. Review rule activation logs



