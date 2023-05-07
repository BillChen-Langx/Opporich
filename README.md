# Opporich
Opportunistically Rich

# 1000-Mile High Level Design

```mermaid
graph TD
 DataCollector[Data Collector]
 DataProcessor[Data Processor]
 ModelTrainer[Model Trainer]
 Model[Model]
 WebApp[OpperRich Web App]

DataCollector-->DataProcessor-->ModelTrainer-->Model
WebApp-->Model
