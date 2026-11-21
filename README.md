# Poultry Egg Production API

A simple REST API for logging daily egg production per shed. Built for a poultry farmer in Kiambu who currently tracks production via WhatsApp and wants a cleaner way to record and total eggs at the end of the week.

## Features

- **POST `/api/eggs`** – Log a daily egg record (shed name, date, count)
- **GET `/api/eggs`** – Retrieve all records with a running total
- In-memory storage (data resets when the server restarts)

## Requirements

- Python 3.8+
- Flask

## Installation

```bash```
pip install flask 

##  Who Can Use This in Kenya?

This kind of simple production tracker is useful for many small businesses:

| Business Type              | How they can use it                          | Suggested Price Point |
|---------------------------|----------------------------------------------|-----------------------|
| Poultry farmers           | Daily egg counts per shed                    | KSh 1,500 – 3,000/month |
| Dairy farmers             | Milk production per cow or session           | KSh 2,000 – 4,000/month |
| Greenhouse vegetable growers | Harvest records (kg of tomatoes, sukuma, etc.) | KSh 1,500 – 3,500/month |
| Fish farmers (ponds)      | Daily or weekly harvest logs                 | KSh 2,000 – 4,000/month |
| Small bakeries / hotels   | Daily production of bread, mandazi, etc.     | KSh 1,000 – 2,500/month |
| Beekeepers                | Honey harvest tracking                       | KSh 1,500 – 3,000/month |

**Recommended pricing strategy:**
- Free version with limited records
- Paid version (KSh 2,000 – 3,500 per month) with reports, multiple users, and data export