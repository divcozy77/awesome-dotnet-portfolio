
# 🌍 GIS Urban Planning Platform

A web-based GIS decision-support system built for LGU Digos City to aid in urban planning, infrastructure mapping, and environmental monitoring.

## 📌 Project Overview
This platform integrates geospatial analysis tools with an interactive web frontend, supporting real-time updates and integration with city data services.

## 🔑 Features
- Interactive web maps using **Leaflet** and **OpenLayers**
- Integration with **PostGIS** and **GeoServer**
- Support for zoning, buffering, overlay analysis, and suitability modeling
- Blazor-based frontend with ASP.NET Core backend
- REST APIs for integration with external systems (PMS, DMS, GAD)
- Power BI dashboards for visual analytics (e.g., 1-Million-Trees project)
- Secure role-based access for government staff

## 🧱 Architecture
- **Frontend**: Blazor (C#), Bootstrap 5, JavaScript
- **Backend**: ASP.NET Core 7, C#, Entity Framework
- **GIS**: Leaflet, OpenLayers, PostGIS, GeoServer
- **APIs**: RESTful services for external integrations
- **Visualization**: Power BI embedded dashboards

```
                       +---------------------+
                       |     Blazor UI       |
                       +----------+----------+
                                  |
                     REST API (ASP.NET Core)
                                  |
                    +-------------+-------------+
                    |   Business Logic Layer    |
                    +-------------+-------------+
                                  |
               +------------------+-------------------+
               |  SQL Server / PostGIS / GeoServer    |
               +--------------------------------------+
```

## 🧰 Tech Stack
- ASP.NET Core 7, C#, EF Core
- Blazor, Bootstrap 5, Leaflet, OpenLayers
- SQL Server + PostGIS, GeoServer
- Power BI, Azure (for optional deployment)
- Git, GitHub Actions for CI/CD

## 📸 Screenshots
> Place screenshots in `/screenshots/` folder and embed here.

![Zoning Map Sample](../screenshots/zoning-map.png)
![Tree Dashboard](../screenshots/tree-dashboard.png)

## 🚀 Setup Instructions

```bash
# Clone the repo
git clone https://github.com/your-username/gis-urban-planning.git

# Navigate into project
cd gis-urban-planning

# Setup database and GIS extensions (PostGIS)
# Configure your GeoServer & map layers

# Run the backend
dotnet run

# Access the frontend via localhost or deploy to IIS/Azure
```

## 🌐 Live Demo
[Demo Link – if available]

## 📄 License
This project is maintained by David Jr. Osita. For licensing or use in other municipalities, please contact: divcozy@gmail.com
