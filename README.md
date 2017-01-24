# REACTIVE SASS #
### A responsive, lightweight css framework for your next project ###

Get a responsive, recursive grid system and lightweight framework in place in seconds. Reactive-sass helps you to set up a css grid using variables, allowing you to easily change or modify it when you please. Also includes helpful helpers allowing you to code code quicker and cleaner. Happy coding :)

Setup:
`$ git clone ...`

##### Set up your grid:
1. Import or include reactiveSASS.scss into your project
2. Set your row and gutter width, select your column padding and count as well as your base font size.
```
$row-width : 100%;
$gutter-width : 0%;
$column-paddng : 0%;
$column-count : 12;
$base-font-size: '16px';
```
3. Start using!

##### Usage:
To call the grid simply use the class name of row and col on your div's. Eg.
```
  <div class="row">
    <div class="w6 col">
    </div>
    <div class="w6 col">
    </div>
  </div>
```

To set your column width use `w$`

To set an offset use `osb$`

##### Helper classes:
  - hidden
  - visible
  - block
  - display-none
  - noselect
  - h100
  - vh100
  - h-inherit
  - text-bold
  - text-italic
  - text-no-style
  - equalizer

##### Coming next...
    - More helper classes
    - Move to flexbox
    - React integration


## Contributing:
Everyone brings something awesome to the party so please raise any suggestions and contribute.
So... <br/>
1. Fork it! <br/>
2. Create your feature branch: `git checkout -b my-new-feature` <br/>
3. Commit your changes: `git commit -am 'Add some feature'` <br/>
4. Push to the branch: `git push origin my-new-feature` <br/>
5. Submit a pull request :D <br/>
