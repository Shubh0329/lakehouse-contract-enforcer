# lakehouse-contract-enforcer
The pitch: A PySpark-based "data contract" enforcement layer that sits between raw ingestion and your Silver layer. It validates incoming files against versioned YAML contracts, detects schema drift, quarantines bad records,
