# ASP.NET_Core_TypeScript_and_Angular
rdalkire  
4/11/2019  

Intended to be sample code for the [TypeScript ASP.NET Core](https://www.typescriptlang.org/docs/handbook/asp-net-core.html) tutorial

## Current State - Build Errors

Output from Build:
```
1>------ Build started: Project: ASP.NET_Core_TypeScript_and_Angular, Configuration: Debug Any CPU ------
1>C:\Users\rdalk\Documents\src\ASP.NET_Core_TypeScript_and_Angular\ASP.NET_Core_TypeScript_and_Angular\node_modules\rxjs\Observable.d.ts(156,5): error TS2416: Build:Property 'groupBy' in type 'Observable<T>' is not assignable to the same property in base type 'CoreOperators<T>'.
1>C:\Users\rdalk\Documents\src\ASP.NET_Core_TypeScript_and_Angular\ASP.NET_Core_TypeScript_and_Angular\node_modules\rxjs\observable\dom\WebSocketSubject.d.ts(31,5): error TS2416: Build:Property 'lift' in type 'WebSocketSubject<T>' is not assignable to the same property in base type 'Subject<T>'.
1>C:\Users\rdalk\Documents\src\ASP.NET_Core_TypeScript_and_Angular\ASP.NET_Core_TypeScript_and_Angular\node_modules\rxjs\Subject.d.ts(18,5): error TS2416: Build:Property 'lift' in type 'Subject<T>' is not assignable to the same property in base type 'Observable<T>'.
1>C:\Users\rdalk\Documents\src\ASP.NET_Core_TypeScript_and_Angular\ASP.NET_Core_TypeScript_and_Angular\node_modules\rxjs\Observable.d.ts(156,5): error TS2416: Build:Property 'groupBy' in type 'Observable<T>' is not assignable to the same property in base type 'CoreOperators<T>'.
1>C:\Users\rdalk\Documents\src\ASP.NET_Core_TypeScript_and_Angular\ASP.NET_Core_TypeScript_and_Angular\node_modules\rxjs\observable\dom\WebSocketSubject.d.ts(31,5): error TS2416: Build:Property 'lift' in type 'WebSocketSubject<T>' is not assignable to the same property in base type 'Subject<T>'.
1>C:\Users\rdalk\Documents\src\ASP.NET_Core_TypeScript_and_Angular\ASP.NET_Core_TypeScript_and_Angular\node_modules\rxjs\Subject.d.ts(18,5): error TS2416: Build:Property 'lift' in type 'Subject<T>' is not assignable to the same property in base type 'Observable<T>'.
1>Done building project "ASP.NET_Core_TypeScript_and_Angular.csproj" -- FAILED.
========== Build: 0 succeeded, 1 failed, 0 up-to-date, 0 skipped ==========
```
