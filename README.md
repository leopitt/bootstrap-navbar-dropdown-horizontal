# bootstrap-navbar-dropdown-horizontal
Inline navbar dropdowns.

Wrap a div with .dropdown-wrapper class around .navbar .dropdown-menu elements to activate. E.g.

```html
<ul class="nav navbar-nav">
  <li class="active"><a href="#">Link <span class="sr-only">(current)</span></a></li>
  <li><a href="#">Link</a></li>
  <li class="dropdown">
    <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-expanded="false">Dropdown <span class="caret"></span></a>
    <div class="dropdown-wrapper">
      <ul class="dropdown-menu" role="menu">
        <li><a href="#">Action</a></li>
        <li><a href="#">Another action</a></li>
        <li><a href="#">Something else here</a></li>
        <li class="divider"></li>
        <li><a href="#">Separated link</a></li>
        <li class="divider"></li>
        <li><a href="#">One more separated link</a></li>
      </ul>
    </div>
  </li>
</ul>
```
