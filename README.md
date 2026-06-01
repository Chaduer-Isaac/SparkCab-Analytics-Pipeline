# RideFlow Spark Pipeline

## Overview

RideFlow Spark Pipeline is an end-to-end data engineering project built using Spark Declarative Pipelines (SDP) and the Medallion Architecture pattern. The project processes cab and ride-hailing trip data across multiple regions, transforming raw operational data into analytics-ready datasets.

## Architecture

Bronze Layer → Silver Layer → Gold Layer

* **Bronze Layer:** Ingests and stores raw transportation data from source systems.
* **Silver Layer:** Applies data cleansing, validation, standardization, and CDC (Change Data Capture) processing.
* **Gold Layer:** Produces business-ready datasets and aggregated metrics for analytics and reporting.

## Features

* Spark Declarative Pipelines (SDP)
* Streaming data processing
* Data quality expectations and validation
* Change Data Capture (CDC) upserts
* Medallion Architecture (Bronze, Silver, Gold)
* Delta Lake optimization
* Scalable analytics pipeline design

## Tech Stack

* Apache Spark
* PySpark
* Spark Declarative Pipelines (SDP)
* Delta Lake
* Databricks
* GitHub

## Use Case

This project simulates a real-world transportation analytics platform similar to ride-hailing services. The pipeline processes trip data to generate insights on operational performance, customer activity, revenue trends, and regional transportation demand.

## Project Structure

project_transportation/
├── bronze/
├── silver/
├── gold/
├── project_setup/
└── README.md

## Learning Objectives

* Build production-style data pipelines using Spark
* Implement Medallion Architecture
* Apply CDC patterns using SDP
* Enforce data quality rules
* Develop scalable analytics workflows on Databricks
