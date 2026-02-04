# SmartPlate

SmartPlate is a meal planning and recipe management platform that helps
users organize meals, manage ingredients, track pantry inventory, and
automatically generate shopping lists.

The platform supports web and mobile applications and will later include
intelligent meal planning based on available ingredients and user
preferences.

This project is built using recipe data and concepts based on the unofficial
HelloFresh API provided at:

https://hfresh.info/

SmartPlate also plans to implement machine learning to assist users in
automatically generating optimized weekly meal plans based on:

-   Available pantry ingredients
-   User preferences
-   Previously selected meals
-   Ingredient usage optimization
-   Reduced food waste

------------------------------------------------------------------------

## Core Features (Planned)

### Recipe Management

-   Store and manage recipes
-   Add, update, and remove recipes
-   Manage ingredients per recipe
-   Import recipes via HelloFresh-based API data

### Meal Planning

-   Weekly meal planning
-   Assign recipes to days
-   Automatic ingredient aggregation

### Pantry / Inventory Tracking

-   Track ingredients currently available
-   Update inventory based on planned meals
-   Manual add/remove inventory items

### Shopping List System

-   Automatic shopping list generation
-   Subtract pantry ingredients from required recipes
-   Track purchased items
-   Manual add/remove shopping items

### Smart Planning (Future)

-   Suggest meals based on available ingredients
-   Reduce food waste
-   Optimize shopping purchases
-   ML-based meal planning

------------------------------------------------------------------------

## Solution Structure

    SmartPlate
    │
    ├── SmartPlate.API               # ASP.NET Core Web API
    ├── SmartPlate.Infrastructure    # Business logic & service interfaces
    ├── SmartPlate.Domain            # Data access & repository implementations
    ├── SmartPlate.ML                # Machine learning & planning engine (planned)
    ├── SmartPlate.Web               # Web frontend (planned)
    └── MobileApp                    # Mobile app (planned)
    
------------------------------------------------------------------------

### Project Responsibilities

**SmartPlate.Domain Layer** - Data storage and retrieval - Database/file
persistence

**SmartPlate.Infrastructure Layer** - Business logic - Service interfaces - Coordinates
repositories and rules

**SmartPlate.API Layer** - Exposes HTTP endpoints - Handles requests from web/mobile
clients - Connects frontend to services - Integrates external recipe
sources

**SmartPlate.Web Frontend** - Browser-based user interface (planned)

**Mobile App** - Shopping list and meal planning on mobile (planned)

------------------------------------------------------------------------

## Technology Stack

-   .NET 8
-   ASP.NET Core Web API
-   C#
-   REST API
-   Planned database integration
-   External recipe API integration
-   Future ML integration
-   Mobile & Web clients

------------------------------------------------------------------------

## Roadmap

### Phase 1 -- Core Backend

-   Project structure
-   Recipe management
-   Basic API endpoints

### Phase 2 -- Planning System

-   Meal planner
-   Shopping list generation
-   Ingredient aggregation

### Phase 3 -- Inventory System

-   Pantry tracking
-   Automatic ingredient updates

### Phase 4 -- Applications

-   Web frontend
-   Mobile application

### Phase 5 -- Smart Planning

-   Ingredient-aware meal suggestions
-   ML-based planning

------------------------------------------------------------------------

## Future Goals

-   Multi-user support
-   Cloud deployment
-   Nutrition tracking
-   Shopping optimization
-   Household collaboration

------------------------------------------------------------------------

## License

Private development project for learning and portfolio purposes.
