# Architecture Guide

## Overview
This project follows **Clean Architecture** principles with modular organization.

## Layers

### 1. **Presentation Layer** (`app/ui`)
- Jetpack Compose UI
- ViewModels
- Navigation

### 2. **Domain Layer** (`domain/`)
- Use Cases
- Repository Interfaces
- Business Logic
- Entities

### 3. **Data Layer** (`data/`)
- Repository Implementations
- Remote Data Sources (API)
- Local Data Sources (Database)
- Data Models

### 4. **Core Module** (`core/`)
- Shared UI Components
- Utilities
- Common Dependencies

## Dependencies Flow
## Benefits
✅ Testability
✅ Maintainability
✅ Scalability
✅ Code Reusability
