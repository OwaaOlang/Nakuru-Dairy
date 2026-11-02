# Nakuru Dairy Co-op Report

What it does: Merges daily milk collection with farmer details, then pivots by zone to give total litres, total payout, and top farmer per zone.

Inputs needed:
1. collection.csv (farmer_name, date, litres)
2. farmers.csv (farmer_name, zone, rate_per_litre)

Run: python nakuru_dairy.py