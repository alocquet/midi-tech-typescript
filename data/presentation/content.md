## Midi Technique - typescript ![logo](data/presentation/logo.png)  <!-- .element width="40%"-->
Arnaud Locquet - arnaud.locquet@gfi.fr<br>
Nicolas Rousseau - nicolas.rouseau1@gfi.fr



https://github.com/alocquet/midi-tech-typescript

![qrcode](data/presentation/qrcode-slides.jpg)



### Plan
1. Origines
    * Besoin d'avoir des types
    * Erreurs à la "transpilation" (avant l'execution)
    * refactoring simplifié
    * Poussé par Angular2
1. Exemple
    * petite application Web, avec uniquement TS
1. Newbie
    * basic types
        * boolean, number, string
        * array : []
        * tuple : tableau de taille définie et dont les types sont connus : [string, number]
        * Enum, any, void
        * null, undefined
        * never
        * type assertion = cast
            * <string>value
            * value as string
    * variables
    * interfaces
    * classes
    * functions
1. Tools
    * Visual Code
    * Plugins
    * Debug
    * Declaration Files
        * file.d.ts
        * npm i --save-dev @types/jquery
    * tsconfig.json
1. Intermediate
    * Generics
    * Enum (avec surcharge du type par défaut)
    * Inference (montrer qu'il n'y a pas la surcharge des méthodes, sauf cast particulier)
    * type compatibility
    * 
1. Expert
    * advanced types
    * symbols
    * iterators/generators
    * Module / Namespace
    * Module resolution
    * Declaratino merging
    * JSX
    * Decorators
    * Mixins
    * Triple-Slash Directives


More Details
See https://www.typescriptlang.org/docs/