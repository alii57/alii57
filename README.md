- 👋 Hi, I’m @alii57
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
alii57/alii57 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
//Java Program to demonstrate the use of continue statement  
//inside the for loop.  
public class ContinueExample {  
public static void main(String[] args) {  
    //for loop  
    for(int i=1;i<=10;i++){  
        if(i==5){  
            //using continue statement  
            continue;//it will skip the rest statement  
        }  
        System.out.println(i);  
    }  
}  
}  

4! = 4*3*2*1 = 24  
5! = 5*4*3*2*1 = 120  


@{ 
    var a = 1;
    var b = 2;
}
Basic Calc
a + b = @(a + b)
The equivalent in #Script using code language blocks:

```code
var a = 1
var b = 2
```
Basic Calc
a + b = {{a + b}}
{{ products
    |> groupBy => it.Category
    |> map => { Category: it.Key, MostExpensivePrice: it.max(p => p.UnitPrice) }
    |> htmlDump }}
    
    
        {{#if test.isEven() }}
{{test}} is even
{{else}}
{{test}} is odd
{{/if}}
```code
#if test.isEven()
    `${test} is even`
else
    `${test} is odd`
/if
```   
   var context = new ScriptContext {
    Args = { ... },              // Global Arguments available to all Scripts, Pages, Partials, etc
    ScriptMethods = { ... },     // Additional Methods
    ScriptBlocks = { ... },      // Additional Script Blocks 
    FilterTransformers = { .. }, // Additional Stream Transformers
    PageFormats = { ... },       // Additional Text Document Formats
    Plugins = { ... },           // Encapsulated Features e.g. Markdown, Protected or ServiceStack Features

    ScanTypes = { ... },         // Auto register Methods, Blocks and Code Page Types
    ScanAssemblies = { ... },    // Auto register all Methods, Blocks and Code Page Types in Assembly
}.Init();

// render code statements
var output = context.RenderCode("now |> dateFormat('HH:mm:ss')"); 

// async
var output = await context.RenderCodeAsync("now |> dateFormat('HH:mm:ss')"); 
These APIs match the high-level APIs for rendering normal #Script:
                                                   
     
