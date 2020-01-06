# angular-gqraaq

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/angular-gqraaq)


1.five common features of Angular's template syntax:

*ngFor

*ngIf

Interpolation {{ }}

Property binding [ ]

Event binding ( )

2.Components

A component consists of three things:

A component class that handles data and functionality. In the previous section, the product data and the share() method in the component class handle data and functionality, respectively.

An HTML template that determines the UI. In the previous section, the product list's HTML template displays the name, description, and a "Share" button for each product.

Component-specific styles that define the look and feel. Though product list does not define any styles, this is where component CSS resides.

input using component
  @Input()
  
  Output using component
  @output()
  event binding to call the notify.emit() method.
  For output events Recall that it's the parent, product list component—not the product alerts component—that acts when the child raises the event. (Choose the parent that acts when the event occurs)
  
 I've learned about the foundation of Angular: components and template syntax. I've also learned how the component class and template interact, and how components communicate with each other.Successfully completed

3.Routing

 Angular router enables you to show different components and data to the user based on where the user is in the application. The router enables navigation from one view to the next as users perform application tasks:
 
 Steps 
   Generate component
   
   Add router path in app.module.ts
   
   Add router link
   
   The routerLink defines how the user navigates to the route (or URL) declaratively in the component template.

4.Using route information

inject the ActivatedRoute into the constructor.

The ActivatedRoute is specific to each routed component loaded by the Angular Router. It contains information about the route, its parameters, and additional data associated with the route.

Angular calls ngOnInit() shortly after creating a component.

The route parameters correspond to the path variables defined in the route. The productId is provided from the URL that was matched to the route. You use the productId to display the details for each unique product.

Managing Data

 1.Services
 
  In Angular, a service is an instance of a class that can be made available to any part of your application using Angular's dependency injection system.

Services are the place where you share data between parts of your application. For the online store, the cart service is where you store your cart data and methods.

Create Cart Service

Use Cart Service

Retrieve shipping prices

HTTP CLient

The Angular HTTP client (HttpClient) is a built-in way to fetch data from external APIs and provide them to your application as a stream
