# Interface gráfica Airflow
A IU do Airflow permite vários métodos para visualizar o estado dos DAGs. O Tree Viewlista as tarefas e qualquer ordenação entre elas em uma estrutura de árvore, com a capacidade de comprimir / expandir os nós. O Graph Viewmostra todas as tarefas e suas dependências em uma estrutura de gráfico, junto com a capacidade de acessar mais detalhes sobre a execução de tarefas. A Codevisualização fornece acesso total ao código Python que compõe o DAG.

# Operators

A tarefa mais comum no Airflow é o **Operador**

- Os operators do airflow representa uma única tarefa em um fluxo de trabalho.


- **Definindo uma tarefa BashOperator**
O *BashOperatorpermite* que você especifique qualquer comando ou script do Shell e adicione-o a um fluxo de trabalho do Airflow. Isso pode ser um ótimo começo para implementar o Airflow em seu ambiente.

# Airflow Tasks

No airflow, podemos entender como tarefas (tasks) os operadores instanciados.

- As tarefas geralmente são atribuídas a uma variável no código python.

# Aditional Operators

- Python Operator

    - Executa uma função do python ou um "método chamavel";

            from airflow.operators.python_operator import PythonOperator


# Airflow Scheduling

- DAG Runs


- cron syntaxe

# 3 - Maintaining and monitoring Aiflow workflows

## Airflow sensors

Um sensor é um tipo especial de operador que espera que uma determinada condição seja verdadeira.

        airflow.sensors.base_sensor_operator

## Airflow Executors

No Airflow, um executor é o componente que reamnete executa as tarefas definidas em seus fluxos de trabalho.


# 4 - Building production pipelines in Airflow
