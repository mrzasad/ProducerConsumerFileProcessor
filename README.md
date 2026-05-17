# SafetyChain Read Files Application

A .NET console application for loading, processing, and saving files using configurable folder paths and the Producer-Consumer design pattern.

This application allows users to:

- Read files from a configured or custom folder
- Load and process documents
- Save processed data to a database
- Use dependency injection and configuration management
- Process documents asynchronously using the Producer-Consumer pattern

---

# 🚀 Features

## ✅ Configurable File Reading

Users can:

1. Read files from a configured folder in `appSettings.json`
2. Enter a custom folder path at runtime

---

## ✅ Dependency Injection

Uses `Microsoft.Extensions.DependencyInjection` for service registration and management.

---

## ✅ Configuration Support

Uses `Microsoft.Extensions.Configuration` to load:

- Folder paths
- Database connection strings
- Application settings

from:

```text
appSettings.json
