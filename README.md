﻿# Jasmine Snippet Pack for Visual Studio

[![Build status](https://ci.appveyor.com/api/projects/status/ws4nxf1ypue4xwy3?svg=true)](https://ci.appveyor.com/project/madskristensen/jasminesnippetpack)

Download this extension from the
[VS Gallery](https://visualstudiogallery.msdn.microsoft.com/423eb4a3-215f-4a8f-9287-1512618ffda3)
or get the
[nightly build](http://vsixgallery.com/extension/4b57f448-ba2e-4404-a0f7-ab1fac14daba/).

-----------------------------------------

A snippet pack to make you more productive working with the
Jasmine test library. Based on the awesome
[VS Code Jasmine snippets](https://github.com/xabikos/vscode-jasmine).

![Snippets demo](art/animation.gif)

This extension ships a bunch of useful code snippets for
the JavaScript editor. Get an overview from the
**Code Snippet Manager** in Visual Studio located under
the **Tools** top level menu.

![Snippet manager](art/snippet-manager.png)

Here's the full list of all the snippets:

### Specs
| Trigger      | Content |
| -------:     | ------- |
| `desc`      | describe method |
| `xdesc`     | xdescribe method |
| `fdesc`     | fdescribe method |
| `it`        | it method |
| `xit`       | xit method |
| `fit`       | fit method |
| `afterEach` | after each method |
| `beforeEach`| before each method |

### Expectations
| Trigger  | Content |
| -------: | ------- |
| exp 	   | expect |
| tb      | expect().toBe |
| tbct    | expect().toBeCloseTo |
| tbd     | expect().toBeDefined |
| tbf     | expect().toBeFalsy |
| tbgt    | expect().toBeGreaterThan |
| tblt    | expect().toBeLessThan |
| tbn     | expect().toBeNul |
| tbt     | expect().toBeTruthy |
| tbu     | expect().toBeUndefined |
| tc      | expect().toContain |
| te      | expect().toEqual |
| thbc    | expect().toHaveBeenCalled |
| thbcw   | expect().toHaveBeenCalledWith |
| tm      | expect().toMatch |
| tt      | expect().toThrow |
| tte     | expect().toThrowError |
| nb      | expect().not.toBe |
| nct     | expect().not.toBeCloseTo |
| nd      | expect().not.toBeDefined |
| nf      | expect().not.toBeFalsy |
| ngt     | expect().not.toBeGreaterThan |
| nlt     | expect().not.toBeLessThan |
| nn      | expect().not.toBeNull |
| nt      | expect().not.toBeTruthy |
| nu      | expect().not.toBeUndefined |
| nc      | expect().not.toContain |
| ne      | expect().not.toEqual |
| nm      | expect().not.toMatch |
| nt      | expect().not.toThrow |
| any     | jasmine.any |
| oc      | jasmine.objectContaining |

### Spies
| Trigger  | Content |
| -------: | ------- |
|so       | spyOn |
|sct      | spyOn.and.callThrough |
|scf      | spyOn.and.callFake |
|srv      | spyOn.and.returnValue |
|ss       | spyOn.and.stub |
|ste      | spyOn.and.throwError |
|ca       | spy.calls.all |
|caa      | spy.calls.allArgs |
|ca       | spy.calls.any |
|caf      | spy.calls.argsFor |
|cc       | spy.calls.count |
|cf       | spy.calls.first |
|cmr      | spy.calls.mostRecent |
|cr       | spy.calls.reset |
|cs       | createSpy |
|cso      | createSpyObj |

## Contribute
Check out the [contribution guidelines](.github/CONTRIBUTING.md)
if you want to contribute to this project.

For cloning and building this project yourself, make sure
to install the
[Extensibility Tools 2015](https://visualstudiogallery.msdn.microsoft.com/ab39a092-1343-46e2-b0f1-6a3f91155aa6)
extension for Visual Studio which enables some features
used by this project.

## License
[Apache 2.0](LICENSE)