# Laravel Learning Flow - Roadmap

### Basic:
[*] Laravel Directory Structure <br>
[*] Create first page <br>

**REF:** https://laravel.com/docs/8.x/structure

---
### Routing:
[*] What is Routing and make Basic dummy route <br>
[*] Pass parameter in url <br>
[*] Optional Parameter <br>
[*] Regular Expression Constraints <br>
[*] Route Prefixes <br>
[*] Named Routes <br?>
[*] anchor Tags <br>
[*] Redirection <br>
[*] Fallback Routes <br>

**REF:** https://laravel.com/docs/5.1/routing
**REF:** https://www.w3schools.com/php/php_regex.asp
---

### Controller:
[*] What is Controller<br>
[*] Create a First Controller<br>
[*] Make function in controller<br>
[*] Call controller from routing<br>
[*] Pass parameter with url<br>
[*] Optional Parameters Controlller<br>
[*] Resource Controllers<br>

**REF:** https://laravel.com/docs/8.x/controllers#single-action-controllers
 - `php artisan make:controller AnyControllerName`
 - `php artisan make:controller PhotoController --resource`
---

### View:
[*] What is View<br>
[*] Create a First View<br>
[*] Call View<br>
[*] Call By Router<br>
[*] Call By Controller<br>
[*] Passing Data To Views<br>

**REF:** https://laravel.com/docs/8.x/views
---

### Component:
[*] What is Component<br>
[*] Create a First Component<br>
[*] Use Components <br>
[*] Passing Data To Components <br>

**REF:** https://laravel.com/docs/8.x/blade#components
 - `php artisan make:component ComponentName`
---

### Blade Template:
[*] What is Blade Template<br>
[*] Template inheritance <br>
[*] Conditional rendering <br>
[*] Blade Directives[@yield,@section,@include,@extends,@forEach]<br>
[*] Php in js<br>
[*] Csrf token<br>
[*] Layouts Using Template Inheritance<br>

**REF:** https://laravel.com/docs/8.x/blade
 - **@section** directive, as the name implies, defines a section of content
 - **@yield** directive is used to display the contents of a given section.
 - **@extends** Blade directive to specify which layout the child view should "inherit". Views which extend a Blade layout may inject content into the layout's sections using @section directives.
 - **@include** directive allows you to include a Blade view from within another view.

---

### Blade HTML Form:
[*] Create Html Form<br>
[*] Create GET Route to Show Form<br>
[*] Create Controller For Handel Form data<br>
[*] Create Post Route For submit Request<br>

---
### Blade HTML Form Validation:
[*] Use Validation functions<br>
[*] Show error message<br>
[*] Error with every field<br>
[*] Prefill data every field<br>

**REF:** https://laravel.com/docs/8.x/validation#introduction
---

## 1st MileStone Challenge
