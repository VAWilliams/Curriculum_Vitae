# Welcome
The following key value pairs show some details about me:

|Key       |Value     |
|:--------:|:--------:|
| Name:    | Vicario  |
| Surname: | Williams |

#### This code has me excited for some Reason
```javascript
let $ = (selector) => {
  this.element = document.getElementById(selector),
  this.html = function(_html) {
    this.element.innerHtml = _html;
  }
  return this;
}

$('card').html(
  `<h1> Hi </h1>
   <p>
      lorem ipsum
   </p>`
);
```
#### And this code
```c#
public class Person
{
  public string Name { private get; set; }
  public string Surname { private get; set; }
  
  public Person(string name = null; string surname = null)
  {
    this.Name = name;
    this.Surname = surname;
  }
  
  public void WriteFullName()
  {
    Console.WriteLine($"{Name} {Surname}");
  }
}
```