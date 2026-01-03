# Inventory Planning Excel Model

This repository contains an Excel-based inventory planning model that implements fundamental inventory control logic, including EOQ, safety stock, and reorder point calculations.

The purpose of this model is to make common inventory planning logic **transparent and inspectable**, rather than hidden behind configuration screens or embedded in proprietary systems.

It is not intended to replace an ERP or inventory management system, but to clarify how such systems translate demand assumptions and uncertainty into inventory policy decisions under the hood.

---

## Purpose

The model is designed to illustrate how demand assumptions and variability are translated into practical inventory policies, such as how much to order and when to reorder, under uncertainty.

It emphasizes transparency, interpretability, and traceability of calculations over automation or algorithmic complexity.

---

## What the model includes

The workbook implements:

- Economic Order Quantity (EOQ) calculations
- Safety stock estimation based on demand and lead-time variability
- Reorder point (ROP) logic
- Clear separation between inputs, calculations, and outputs
- A reference sheet explaining assumptions, formulas, and methodology

---

## Intended use

This model is intended for:

- Educational purposes
- Scenario analysis
- Explaining inventory planning and replenishment logic
- Supporting inventory policy discussions

It is not intended to replace an ERP system or inventory planning platform. Most production systems perform these calculations internally; this model exists to make those calculations visible and understandable.

---

## Limitations

- The model is not automated or optimized for large-scale production use.
- Results depend on the quality and representativeness of demand and lead-time inputs.
- External constraints such as supplier capacity limits, contract terms, or dynamic pricing are not explicitly modeled.
- The model assumes stable process behavior over the historical window.

---

## Related work

This project complements a demand forecasting model that focuses on estimating demand uncertainty and forecast error, which serve as inputs to inventory policy decisions.
