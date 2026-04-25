# Student Engagement Platform

## Requirements

### Backend
- [Swift](https://www.swift.org/install)

### Frontend
- [NPM](https://nodejs.org/en/download/)

## Setup

### Pull down repo:
```
git clone --recurse-submodules https://github.com/NyxStrong/Student-Engagement-Platform
cd Student-Engagement-Platform
```

### Start Backend
```bash
cd Student-Engagement-Backend

# Setup and seed db
swift run STB migrate -y

# Configure ip and port in Sources/STB/configure.swift

# Start backend
swift run STB
```