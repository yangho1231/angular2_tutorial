interpolation {{}}
Double binding [(ngModel)]

CSS:
    Encapsulating Styles by: styles and styleUrls

LifeCycle
    Create -> Render -> Create and render Children -> Process Changes -> Destory
    OnInit: Perform component initialization, retrieve data
    OnChanged: Perform action after changes.
    OnDestory: clean up.

Custom Pipe
    export class SomeThing implements PipeTransform {
        transform(value: IProduct[],
            filterBy: string): IProduct[] {

            }
    }
    value: IProduct[] -> value you want to transform
    filterBy: string -> Arguments you need to filter criteria.
    IProduct[] -> Return type

module.id: contains the absolute URL of the component class module file. With this you don't have to specify abosulte URL just the path you are in.

Nesting:
    Directives
    @Input to get property from other files