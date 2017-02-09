Tooltip allows the user to specify text to be displayed when the mouse hover over an element.

## Installation

Install the npm package.

    npm i ng2-tooltip-directive
        
Import `Ng2Module`:

    import { NgModule }         from '@angular/core';
    import { BrowserModule }    from '@angular/platform-browser';
    import { AppComponent }     from './app.component';
    import { TooltipDirective } from 'ng2-tooltip-directive/components';
     
    @NgModule({
        imports:      [ BrowserModule ],
        declarations: [ AppComponent, TooltipDirective ],
        bootstrap:    [ AppComponent ]
    })
    export class AppModule { } 

## Usage
    
    <span tooltip="Tooltip">Tooltip on top</span>

## Development server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.