# Backstage.io Learning Implementation

## About This Project

This is my hands-on learning implementation of Spotify's Backstage Internal Developer Platform.

This is a learning sandbox, not a production system. It's my way of understanding how Internal Developer Platforms work before implementing them in real environments.

## Learning Objectives

- Understand Internal Developer Platform (IDP) concepts
- Learn Backstage architecture and plugin system
- Practice TypeScript/React in a real platform context
- Explore developer experience (DevEx) improvements
- Build foundation for future platform engineering roles

## What I've Implemented 

### Core Setup
- [x] **Local Development Environment** - WSL2 with Node.js setup
- [x] **Basic Backstage Installation** - Up and running locally
- [x] **Folder Structure Understanding** - Explored monorepo architecture

### Authentication & Security
- [x] **GitHub OAuth Integration** - Configured SSO authentication
- [x] **Custom Sign-In Resolver** - Implemented user mapping

### Software Catalog
- [x] **Git Integration** - Connected to GitHub for catalog files
- [x] **Entity Registration** - Added components, users, and groups
- [x] **Data Model Understanding** - Learned about kinds, types, and relations

### Documentation
- [x] **API Documentation** - Integrated OpenAPI/Swagger specs
- [x] **TechDocs** - Set up MkDocs-powered documentation
- [x] **Search Functionality** - Configured search architecture

### Customization
- [x] **Custom Sidebar** - Modified navigation structure
- [x] **Plugin Installation** - Added GitHub Actions plugin

## In progress

- [ ] **Catalog Entity Page Customization**
- [ ] **Creating Custom Backstage Plugin** 
- [ ] **Software Templates with Cookiecutter** 

## What I've Learned So Far

### Key Concepts
- **Service Catalog:** Central registry for all software components
- **TechDocs:** Documentation as code approach
- **Golden Paths:** Standardized ways to build software
- **Platform as Product:** Treating internal tools as products

### Technical Skills Gained
- TypeScript configuration in monorepos
- React plugin architecture
- YAML schema validation
- OAuth flow implementation
- PostgreSQL with TypeORM

### Challenges Encountered & Solved

**WSL2 Docker Issues:**
- Problem: TechDocs wouldn't build in Docker on WSL
- Solution: Switched to local MkDocs generation
- Learning: Environment-specific configurations matter

**GitHub OAuth Redirect:**
- Problem: Localhost redirect URLs failing
- Solution: Properly configured OAuth app settings
- Learning: Security boundaries in development vs production

## Tech Stack I'm Learning

- **Frontend:** React, TypeScript, Material-UI
- **Backend:** Node.js, Express
- **Database:** PostgreSQL (via Docker)
- **Auth:** OAuth 2.0, GitHub Apps
- **Build:** Yarn workspaces, Webpack
- **Container:** Docker, Docker Compose
