<template>

    <div class="element">

        <table class="mdl-data-table mdl-js-data-table mdl-data-table--selectable mdl-shadow--2dp">
            <thead>
            <tr>
                <th class="mdl-data-table__cell--non-numeric">Material</th>
                <th>Quantity</th>
                <th>Unit price</th>
                <th>Lorem ipsum.</th>
                <th>Lorem ipsum dolor.</th>
            </tr>
            </thead>
            <tbody>
            <tr>
                <td class="mdl-data-table__cell--non-numeric">Acrylic (Transparent)</td>
                <td>25</td>
                <td>$2.90</td>
                <td>$2.90</td>
                <td>$2.90</td>
            </tr>
            <tr>
                <td class="mdl-data-table__cell--non-numeric">Plywood (Birch)</td>
                <td>50</td>
                <td>$1.25</td>
                <td>$2.90</td>
                <td>$2.90</td>
            </tr>
            <tr>
                <td class="mdl-data-table__cell--non-numeric">Laminate (Gold on Blue)</td>
                <td>10</td>
                <td>$2.35</td>
                <td>$2.90</td>
                <td>$2.90</td>
            </tr>
            </tbody>
        </table>

    </div>

    <div class="element">

        <div class="demo-card-wide mdl-card mdl-shadow--2dp">
            <div class="mdl-card__title">
                <h2 class="mdl-card__title-text">Welcome</h2>
            </div>
            <div class="mdl-card__supporting-text">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                Mauris sagittis pellentesque lacus eleifend lacinia...
            </div>
            <div class="mdl-card__actions mdl-card--border">
                <a class="mdl-button mdl-button--colored mdl-js-button mdl-js-ripple-effect">
                    Get Started
                </a>
            </div>
            <div class="mdl-card__menu">
                <button class="mdl-button mdl-button--icon mdl-js-button mdl-js-ripple-effect">
                    <i class="material-icons">share</i>
                </button>
            </div>
        </div>

    </div>

    <div class="element">

        <!-- Simple Textfield -->
        <form action="#">
            <div class="mdl-textfield mdl-js-textfield">
                <input class="mdl-textfield__input" type="text" id="sample1">
                <label class="mdl-textfield__label" for="sample1">Text...</label>
            </div>
        </form>
        <!-- Numeric Textfield -->
        <form action="#">
            <div class="mdl-textfield mdl-js-textfield">
                <input class="mdl-textfield__input" type="text" pattern="-?[0-9]*(\.[0-9]+)?" id="sample2">
                <label class="mdl-textfield__label" for="sample2">Number...</label>
                <span class="mdl-textfield__error">Input is not a number!</span>
            </div>
        </form>

    </div>

    <div class="element">
        <input class="mdl-slider mdl-js-slider" type="range"
               min="0" max="100" value="0" tabindex="0">
        <!-- Slider with Starting Value -->
        <input class="mdl-slider mdl-js-slider" type="range"
               min="0" max="100" value="25" tabindex="0">
    </div>

</template>

<script>
    export default {
        data () {
            return {
                // note: changing this line won't causes changes
                // with hot-reload because the reloaded component
                // preserves its current state and we are modifying
                // its initial state.
                msg: 'Hello World!'
            }
        }
    }
</script>

<style>
    .element {
        padding: 20px;
    }
    .demo-card-wide > .mdl-card__title {
        color: #fff;
        height: 176px;
        background: url('http://protiumdesign.com/wp-content/uploads/2015/04/Material-Design-Landscape-1024.jpg') center / cover;
    }
</style>