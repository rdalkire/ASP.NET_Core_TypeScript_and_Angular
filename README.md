# ASP.NET_Core_TypeScript_and_Angular
rdalkire  
4/11/2019  

Intended to be sample code for the [TypeScript ASP.NET Core](https://www.typescriptlang.org/docs/handbook/asp-net-core.html) tutorial, in order to help resolve the issue I've raised,  [#1012, ASP.NET Core tutorial - working source code please](https://github.com/Microsoft/TypeScript-Handbook/issues/1012)

As one can see by the .sln, .csproj and other included files, this is done using VS 2017 with the optional ".NET Core 1.0 - 1.1 development tools for Web", the ASP.NET Core 1.1 template, Microsoft.AspNetCore.StaticFiles 1.1.2 and everything else specified in the tutorial instructions.

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
