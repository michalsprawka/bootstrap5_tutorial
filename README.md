# bootstrap5_tutorial

## Text

### display

```
  <!-- display headings -->
  <h1 class="display-1">display 1 heading</h1>
  <h1 class="display-2">display 2 heading</h1>
  <h1 class="display-6">display 6 heading</h1>
  <p class="display-1">paragraph with display-1 class</p>
```
### alignment
```
  <p class="lead text-center">hello ninjas</p>
  <p class="lead text-end">hello ninjas</p>
  <p class="lead text-start">hello ninjas</p>
```
### text underline and bold
```
  <!-- text decoration & font weight -->
  <p class="text-decoration-underline">this is underlined text</p>
  <p class="text-decoration-line-through">this is line-through text</p>
  <p class="fw-bold">this bold text</p>
  <small>this is small text</small>
```
### text color
```
  <!-- text colours -->
  <p class="text-primary">theme primary colour</p>
  <p class="text-secondary">theme secondary colour</p>
  <p class="text-info">theme info colour</p>
  <p class="text-warning">theme warning colour</p>
  <p class="text-success">theme warning colour</p>
  <p class="text-danger">theme danger colour</p>
  <p class="text-muted">theme danger colour</p>
```
### text background colors
```
  <!-- bg colors -->
  <p class="text-white bg-primary">white text on primary bg</p>
  <p class="text-white bg-secondary">white text on secondary bg</p>
  <p class="text-light bg-danger">white text on secondary bg</p>
```
## buttons

### primary secondary buttons
```
  <button class="btn btn-primary">primary button</button> <!-- auto lightens text -->
  <button class="btn btn-secondary">secondary button</button>
```
### link as buttons
```
  <a href="#" class="btn btn-info">info anchor tag</a>
  <a href="#" class="btn btn-success">success anchor tag</a>
```
### sizes
```
  <button class="btn btn-lg btn-danger">large danger button</button>
  <button class="btn btn-sm btn-warning">small warning button</button>
```
### outline style
```
  <button class="btn btn-outline-primary">outlined button</button>
  <button class="btn btn-outline-secondary btn-lg">large outlined button</button>
```
### button group
```
  <div class="btn-group">
      <a href="#" class="btn btn-primary">button 1</a>
      <a href="#" class="btn btn-warning">button 2</a>
      <a href="#" class="btn btn-success">button 3</a>
  </div>
```
## Utility
### margin & padding
```
  <!-- margin & padding -->
  <div class="m-1 p-1 bg-primary">small margin & padding</div>
  <div class="m-5 p-5 bg-primary">large margin & padding</div>
  <div class="my-3 px-5 bg-primary">margin in y dir, padding in x dir</div>
  <div class="mt-3 mb-4 ps-5 pt-4 pe-2 pb-1 bg-primary">m & p for each direction</div>
```
### borders
```
  <!-- borders -->
  <div class="m-3 p-3 border">default border</div>
  <div class="m-3 p-3 border-top border-end">individual borders</div>
  <div class="m-3 p-3 border-start border-success">border success colour</div>
  <div class="m-3 p-3 border-start border-danger border-5">thicker border</div>
  <div class="m-3 p-3 rounded border border-5">rounded corners</div>
  <div class="m-3 p-3 rounded-pill border border-5">rounded corners</div>
### shadow
```
  <!-- box shadow -->
  <div class="m-3 p-3 shadow-sm">element with small shadow</div>
  <div class="m-3 p-3 shadow">element with shadow</div>
```
### font weight
```
  <!-- font weight -->
  <p class="fw-bold">bold text</p>
  <p class="fw-bolder">bolder text</p>
  <p>normal text</p>
  <p class="fw-light">light text</p>
  <p class="fst-italic">italic text</p>
  <p class="fst-italic fw-light">italic light text</p>
```
## containers
```
  <div class="container my-5">
    <h2>normal container</h2>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quos ratione labore modi vel facere pariatur. Nobis beatae ab officia assumenda nisi ea eos soluta accusamus iure minus iste reiciendis veritatis asperiores perferendis iusto, veniam tempora nulla repudiandae exercitationem? Eius rerum illo nulla corporis odio quos porro vero. Eveniet nulla deserunt odio tenetur vero nihil veritatis, quo repudiandae iusto blanditiis ipsum.</p>
  </div>

  <div class="container-fluid my-5">
    <h2>fluid container</h2>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis obcaecati consequuntur mollitia distinctio, ratione enim quia sint repellat velit accusantium. Vel id architecto facilis facere soluta veritatis suscipit praesentium deleniti numquam impedit doloremque, recusandae reiciendis similique eos labore, quisquam quia voluptate distinctio maiores! Assumenda iure doloremque cupiditate architecto odit maiores magni itaque in, numquam qui cumque, blanditiis magnam aperiam. Dolor.</p>
  </div>

  <div class="container-lg my-5">
    <h2>100% until lg screens, then container</h2>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nihil dolore doloremque iure corporis, cumque voluptate commodi minus. Accusantium magni ut omnis excepturi cumque! Debitis fugiat cumque nihil corrupti eius facere corporis natus? Cumque numquam vitae ipsam eum quaerat omnis vel corrupti perferendis totam iste quisquam, facere consequuntur aut, ea, doloribus aperiam. Ad eius facilis nulla! Ea optio in corporis ab.</p>
  </div>

  <div class="container-xl my-5">
    <h2>100% until xl screens, then container</h2>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nihil dolore doloremque iure corporis, cumque voluptate commodi minus. Accusantium magni ut omnis excepturi cumque! Debitis fugiat cumque nihil corrupti eius facere corporis natus? Cumque numquam vitae ipsam eum quaerat omnis vel corrupti perferendis totam iste quisquam, facere consequuntur aut, ea, doloribus aperiam. Ad eius facilis nulla! Ea optio in corporis ab.</p>
  </div>
```
## Grid
### basic grid
```
  <div class="container-lg my-5">
    <h2>basic grid</h2>
    <div class="row">
      <div class="col">
        <div class="p-5 bg-primary text-light">col 1</div>
      </div>
      <div class="col">
        <div class="p-5 bg-primary text-light">col 2</div>
      </div>
      <div class="col">
        <div class="p-5 bg-primary text-light">col 3</div>
      </div>
    </div>
  </div>
  ```
### column width
```
 <div class="container-lg my-5">
    <h2>column widths</h2>
    <div class="row">
      <div class="col-6">
        <div class="p-5 bg-primary text-light">col 1</div>
      </div>
      <div class="col-3">
        <div class="p-5 bg-primary text-light">col 2</div>
      </div>
      <div class="col-3">
        <div class="p-5 bg-primary text-light">col 3</div>
      </div>
    </div>
  </div>
```
### responsive
on mobile it will stack !!!
```
  <div class="container-lg my-5">
    <h2>responsive column widths</h2>
    <div class="row gy-3"> <!-- manually change gutter using g{d}-{n}  gutters are gaps between columns-->
      <div class="col-sm-4 col-lg-6">
        <div class="p-5 bg-primary text-light">col 1</div>
      </div>
      <div class="col-sm-4 col-lg-3">
        <div class="p-5 bg-primary text-light">col 2</div>
      </div>
      <div class="col-sm-4 col-lg-3">
        <div class="p-5 bg-primary text-light">col 3</div>
      </div>
    </div>
  </div>
  ```
### justyfying columns
```
  <div class="container-lg my-5">
    <h2>justifying columns</h2>
    <div class="row justify-content-center"><!-- j-c-end, j-c-start, j-c-between, j-c-around -->
      <div class="col-md-3">
        <div class="p-5 bg-primary text-light">col 1</div>
      </div>
      <div class="col-md-3">
        <div class="p-5 bg-primary text-light">col 2</div>
      </div>
      <div class="col-md-3">
        <div class="p-5 bg-primary text-light">col 3</div>
      </div>
    </div>
  </div>
  ```
  ## hiding elements on small screen
  .d-none .d-sm-block
  ## navbar
  ```
  <!-- navbar -->
  <nav class="navbar navbar-expand-md navbar-light pt-5 pb-4">
    <div class="container-xxl">
      <!-- navbar brand / title -->
      <a class="navbar-brand" href="#intro">
        <span class="text-secondary fw-bold">
          Net Ninja Pro - the Book
        </span>
      </a>
      <!-- toggle button for mobile nav -->
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#main-nav" aria-controls="main-nav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <!-- navbar links -->
      <div class="collapse navbar-collapse justify-content-end align-center" id="main-nav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" href="#topics">About The Book</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#reviews">Reviews</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Get in Touch</a>
          </li>
          <li class="nav-item d-md-none">
            <a class="nav-link" href="#pricing">Pricing</a>
          </li>
          <li class="nav-item ms-2 d-none d-md-inline">
            <a class="btn btn-secondary" href="#pricing">buy now</a>
          </li>
          
        </ul>
      </div>
    </div>
  </nav>
  ```
  ## card
  ```
        <div class="row my-5 g-0 align-items-center justify-content-center">
        <div class="col-8 col-lg-4 col-xl-3">
          <div class="card border-0">
            <div class="card-body text-center py-4">
              <h4 class="card-title">Starter Edition</h4>
              <p class="lead card-subtitle">eBook download only</p>
              <p class="display-5 my-4 text-primary fw-bold">$12.99</p>
              <p class="card-text mx-5 text-muted d-none d-lg-block">Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia, vitae magni! Repellat commodi a fuga corporis saepe dolorum.</p>
              <a href="#" class="btn btn-outline-primary btn-lg mt-3">
                Buy Now
              </a>
            </div>
          </div>
        </div>

        <div class="col-9 col-lg-4">
          <div class="card border-primary border-2">
            <div class="card-header text-center text-primary">Most Popular</div>
            <div class="card-body text-center py-5">
              <h4 class="card-title">Complete Edition</h4>
              <p class="lead card-subtitle">eBook download & all updates</p>
              <p class="display-4 my-4 text-primary fw-bold">$18.99</p>
              <p class="card-text mx-5 text-muted d-none d-lg-block">Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia, vitae magni! Repellat commodi a fuga corporis saepe dolorum.</p>
              <a href="#" class="btn btn-outline-primary btn-lg mt-3">
                Buy Now
              </a>
            </div>
          </div>
        </div>
```
