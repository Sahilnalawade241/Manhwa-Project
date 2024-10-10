# Manhwa Web Application

## Overview
This web application displays a list of fantasy manhwa titles, their genres, and brief descriptions using mock data. It is designed to be hosted on AWS and demonstrates the use of EC2, RDS, and basic web technologies.

## Features
- Displays a list of manhwa titles.
- Shows genres and brief descriptions.
- Hosted on an AWS EC2 instance.
- Connects to a MySQL RDS database for data management.
- Supports HTTPS for secure connections.
- Configured for auto-scaling to handle traffic spikes.

## Technology Stack
- **Frontend:** HTML, JavaScript
- **Backend:** Python (HTTP Server)
- **Database:** MySQL (RDS)
- **Cloud Platform:** AWS (Amazon Web Services)

## Files
- `index.html`: Main HTML file that displays the manhwa list.
- `manhwa.json`: JSON file containing mock data for manhwa titles.
- `requirements.txt`: (if applicable) Lists dependencies for your backend.

## Setup Instructions

### Prerequisites
- AWS account with EC2 and RDS setup.
- Basic knowledge of using SSH to connect to EC2 instances.

### Deployment Steps

1. **Connect to Your EC2 Instance**
   ```bash
   ssh -i "your-key-pair.pem" ubuntu@your-ec2-public-ip

