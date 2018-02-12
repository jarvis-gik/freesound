Home, not logged: (the ellipsis icon and the dropdowns won't load correctly inside styleguidist)

```jsx
require('../../src/components/navbar');

<nav class="bw-nav container">
  <div class="bw-nav__logo">
    <a href="" class="no-hover" />
  </div>
  <ul class="bw-nav__actions">
    <li class="bw-nav__action">
      <a class="bw-link--grey" href="">
        Sounds
      </a>
    </li>
    <li class="bw-nav__action">
      <a class="bw-link--grey" href="">
        Packs
      </a>
    </li>
    <li class="bw-nav__action">
      <a class="bw-link--grey" href="">
        Forum
      </a>
    </li>
    <li class="bw-nav__action">
      <a class="bw-link--grey" href="">
        Map
      </a>
    </li>
    <li class="bw-nav__action dropdown">
      <a
        class="bw-link--grey bw-nav__menu dropdown-toggle no-hover"
        id="three-dots-menu"
        aria-haspopup="true"
        aria-expanded="false"
        data-toggle="dropdown"
      />
      <ul class="dropdown-menu" aria-labelledby="three-dots-menu">
        <li class="bw-nav__action dropdown-item">
          <a class="bw-link--black" href="">
            Tags
          </a>
        </li>
        <li class="bw-nav__action dropdown-item">
          <a class="bw-link--black" href="">
            Charts
          </a>
        </li>
        <li class="bw-nav__action dropdown-item">
          <a class="bw-link--black" href="">
            Donors
          </a>
        </li>
        <li class="bw-nav__action dropdown-item">
          <a class="bw-link--black" href="">
            Help
          </a>
        </li>
        <li class="bw-nav__action dropdown-item">
          <a class="bw-link--black" href="">
            Developers
          </a>
        </li>
        <li class="bw-nav__action dropdown-item">
          <a class="bw-link--black" href="">
            Freesound Blog
          </a>
        </li>
        <li class="bw-nav__action dropdown-item">
          <a class="bw-link--black" href="">
            Freesound Labs
          </a>
        </li>
        <li class="bw-nav__action dropdown-item">
          <a class="bw-link--black" href="">
            Freesound t-Shirt
          </a>
        </li>
      </ul>
    </li>
    <li class="bw-nav__action">
      <a class="bw-link--black" href="">
        Log in
      </a>
    </li>
    <button class="btn-primary">Join</button>
  </ul>
</nav>;
```