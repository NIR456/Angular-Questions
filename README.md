# Angular-Questions

## Angular Decorators
  - Decorators are design patterns used to isolate the modification or decoration of a class without modifying the source code.

  - In AngularJS, decorators are functions that allow a service, directive, or filter to be modified before it is used. 

    **There are four main types of angular decorators:**
     ####  Class decorators, such as @Component and @NgModule
     #### Property decorators for properties inside classes, such as @Input and @Output
     #### Method decorators for methods inside classes, such as @HostListener
     #### Parameter decorators for parameters inside class constructors, such as @Inject
## Services    
  - A service in Angular is a class that provides a specific functionality to be used across different components. Services are usually decorated with the @Injectable 
    decorator, which allows them to be injected into other classes using Angular’s Dependency Injection (DI) system.
## Scope in Angular 
 - In AngularJS (Angular 1.x), the $scope object was used to link the view (HTML) and the controller. It allowed for two-way data binding, meaning changes in the scope were 
   reflected in the view and vice versa.
 - Angular (2 and later) moved away from $scope and adopted a component-based architecture. In this architecture, components encapsulate data and behavior. Each component 
  has its own context, meaning.
 - **Component Class:** Contains the logic and data (similar to the controller in AngularJS).
 - **Template:** Contains the HTML and uses data binding to display and interact with the data from the component class.
 - **Service:** Used to share data or functionality between components.

        
    
