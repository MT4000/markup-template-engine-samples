
These files represent samples of HTML templates, intended for use with template engine, which uses BBCode-style square brackets [] for markup tags indication.

Example:


[form]
    my form!
    
    [view] MY [form]SUPER[/form] VIEW 2![/view]
    
    [form]
      [input]  [form]another {!someval!}  {!myval = 555!} [/form]   [/input]
      
      {!myval!}
    [/form]
    
[/form]



