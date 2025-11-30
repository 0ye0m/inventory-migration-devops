# 🚀 DevOps & Backend Challenge: Legacy Migration

## 📋 Project Overview
Modernized a legacy inventory system by migrating from static JSON files to a SQL database with REST API, Nginx reverse proxy, systemd service, and public access via ngrok.

## 🛠 Technologies Used
- **Backend**: FastAPI (Python)
- **Database**: SQLite with SQLAlchemy
- **Web Server**: Nginx
- **Process Management**: Systemd
- **Public Access**: Ngrok
- **OS**: WSL Ubuntu

## 🚀 Quick Start
1. Clone repository
2. Run `pip install -r requirements.txt`
3. Run `python migrate.py` to setup database
4. Start with `python main.py`

## 🌐 Live Demo
- **Public URL**: https://unmined-lowell-anguishedly.ngrok-free.dev/api/products
- **API Documentation**: https://unmined-lowell-anguishedly.ngrok-free.dev/docs

## ✅ API Endpoints
- `GET /api/products` - Get all products
- `POST /api/order` - Place order with price calculation

## 📸 Screenshots
- Database migration proof
- Price calculation logic
- Systemd service status

- Public URL access
