# \<paper-fab-speed-dial\>

A floating action button flinging out related actions.

## Demo
![Demo](https://raw.githubusercontent.com/pomber/paper-fab-speed-dial/master/docs/images/paper-fab-speed-dial.gif)

Live demo in [component page](https://pomber.github.io/paper-fab-speed-dial/)

## Usage

Install:

```sh
bower install --save paper-speed-dial
```

Import:

```html
<link rel="import" href="bower_components/paper-fab-speed-dial/paper-fab-speed-dial.html">
```

Use:

```html
<paper-fab-speed-dial>      
    <paper-fab icon="add"></paper-fab>
    <div class="dropdown-content">
        <paper-fab mini icon="rowing"></paper-fab>
        <paper-fab mini icon="weekend"></paper-fab>
        <paper-fab mini icon="pets"></paper-fab>
    </div>
</paper-fab-speed-dial>
```

## Styling

The following custom properties and mixins are available for styling:

| Custom property | Description | Default |
| --- | --- | --- |
| `--paper-fab-speed-dial` | Mixin applied to the element | `{}` |
| `--paper-fab-speed-dial-position` | Position of the element | `absolute` |
| `--paper-fab-speed-dial-bottom` | bottom value of the element. | 10px |
| `--paper-fab-speed-dial-right` | right value of the element. | 10px | 
