# EasyGrid
A simplest yet powerful 12 Grids Responsive CSS Layout for your website.

## Usages

Add reset.css and grid.css in your html.
The file reset.css will override default styling of the browser 
where the grid.css file is the actual responsive grid layout system.

For
```
===============================================  
Default Screen (1024px - 1366px): col-*
Extra Small Screen (Bellow 480px): col-xs-*  
Small Screen (Bellow 768px): col-sm-*      
Medium Screen (Bellow 1024px): col-md-*     
Medium Large Screen (Above 1366px): col-ml-*
Large Screen (Above 1440px): col-lg-*     
Extra Large Screen (Above 1920px): col-xl-*     
===============================================      
```
### Examples

```

<div class="row">
  <div class="col col-md-6">
    <h1>Heading Title 01</h1>
    <p> Lorem Ipsum dolor sit amet consectetur adipisicing elit. 
    Ex rem voluptate dignissimos qui mollitia dolorum alias, 
    uisquam placeat asperiores omnis. Ipsam molestiae fugit 
    minima quo adipisci maiores reprehenderit perferendis. </p>
  </div>
  <div class="col col-md-6">
    <h1> Heading Title 02</h1>
    <p> Lorem Ipsum dolor sit amet consectetur adipisicing elit.
    Ex rem voluptate dignissimos qui mollitia dolorum alias, 
    quisquam placeat asperiores omnis. Ipsam molestiae fugit 
    minima quo adipisci maiores reprehenderit perferendis. </p>
  </div>
</div>

```