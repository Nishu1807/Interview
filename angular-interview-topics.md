# 🔥 Angular Interview Topics Cheat Sheet

## 1. Core Angular Fundamentals
- Angular architecture (Modules, Components, Templates, Metadata, Data Binding, Directives, Services, Dependency Injection)
- Lifecycle Hooks (`ngOnInit`, `ngOnChanges`, `ngAfterViewInit`, etc.)
- Modules (`AppModule`, `SharedModule`, `FeatureModule`, `Lazy-loaded Modules`)
- Change Detection mechanism (`Zone.js`, `OnPush` strategy)

---

## 2. Data Binding & Templates
- Interpolation
- Property Binding
- Event Binding
- Two-Way Binding (`[(ngModel)]`)
- Structural Directives (`*ngIf`, `*ngFor`, `*ngSwitch`)
- Attribute Directives (`ngClass`, `ngStyle`, custom directives)
- Template Reference Variables (`#var`)

---

## 3. Components & Communication
- Input/Output decorators (`@Input`, `@Output`, `EventEmitter`)
- `@ViewChild` & `@ContentChild`
- Content Projection (`ng-content`, multi-slot, `ngTemplateOutlet`)

---

## 4. Services & Dependency Injection
- Creating and providing services (`providedIn: 'root'`, module-level, component-level)
- Hierarchical Injector
- Restricting service scope (specific component/module)
- Singleton vs multiple service instances

---

## 5. Routing & Navigation
- Angular Router basics (`<router-outlet>`, `RouterModule`)
- Route Guards (`CanActivate`, `CanDeactivate`, `Resolve`, `CanLoad`)
- Lazy Loading Modules
- Route & Query Parameters
- Router events (`NavigationStart`, `NavigationEnd`)

---

## 6. Forms in Angular
- Template-driven forms (ngModel, validations)
- Reactive forms (FormGroup, FormControl, FormBuilder)
- Form validation (built-in, custom, async validators)
- Difference between Template-driven & Reactive forms

---

## 7. RxJS & Observables
- Observable vs Promise
- Subjects & BehaviorSubjects
- Common operators: `map`, `filter`, `switchMap`, `mergeMap`, `debounceTime`, `takeUntil`
- Handling async data with `async` pipe
- Unsubscribing strategies (`takeUntil`, `AsyncPipe`)

---

## 8. HTTP Client
- `HttpClientModule`
- Interceptors (logging, authentication, error handling)
- Error handling with RxJS (`catchError`, `retry`)
- REST API integration best practices

---

## 9. Angular Security
- Sanitization (`DomSanitizer`)
- XSS protection
- Authentication & Authorization (JWT, route guards)
- CORS handling

---

## 10. Performance Optimization
- Change detection strategies (`Default`, `OnPush`)
- Pure vs Impure pipes
- Lazy loading & Preloading strategies
- `trackBy` in `*ngFor`
- Bundle optimization (AOT, tree shaking)

---

## 11. Testing in Angular
- Unit testing with Jasmine & Karma
- Component testing (`TestBed`, `ComponentFixture`)
- Service testing with `HttpTestingController`
- Mocking dependencies with spies

---

## 12. Advanced Topics
- Angular Universal (SSR)
- Progressive Web Apps (PWA)
- State Management (NgRx, Akita, BehaviorSubject)
- Micro-frontend architecture

---

✅ **Focus for Interviews**: Lifecycle, Data Binding, Dependency Injection, Routing with Guards, Forms, RxJS, HTTP & Interceptors, Change Detection.
