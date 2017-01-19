# Groundwork

Groundwork is a lightweight, responsive, [BEM](http://getbem.com/) inspired, CSS grid.

* * *

## Roadmap

- [ ] Add fixed width containers
- [ ] Convert to @mixins
- [ ] Tests

## Configuration

Groundwork [variables](sass/_variables.scss) can be overwritten to suit your grid requirements. The following variables are Groundworks defaults.

````scss
$groundwork-columns: 12;
$groundwork-gutter-width: 20px;
$groundwork-breakpoints: (xs, 576px), (sm, 768px), (md, 992px), (lg, 1200px);

$groundwork-class-container: 'container';
$groundwork-class-row: 'row';
$groundwork-class-column: 'column';
````

## Usage

Groundwork classes are heavily based on [Bootstrap classes](https://getbootstrap.com/css/#grid). An example of the markup is shown below.

````html
<div class="container">
    <div class="row">
        <div class="column column--sm-6 column--xs-4">
            
        </div>
        <div class="column column--sm-3 column--xs-4">
            
        </div>
        <div class="column column--sm-3 column--xs-4">
            
        </div>
    </div>
</div>
````

## Why?

Because the internet already has too many grids. Another won't hurt anyone. Also they're fun to build.

## License

The MIT [License](LICENSE.md) (MIT).