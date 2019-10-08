<template>
    <button v-bind:class="classObject">
        {{ text }}
    </button>
</template>

<script>
export default {
    name: 'h-button',
    data() {
        return {
            classes: []
        }
    },
    props: {
        // Size
        size: {
            type: String,
            validator: (value) => {
                if ( ['sm', 'lg'].indexOf(value) !== -1 ) {
                    return value
                }
            },
        },
        // Text
        text: String
    },
    computed: {
        classObject: function () {
            this.classes.push(this.size)
            return this.classes
        }
    }
}
</script>

<style type="text/css">
    button {
        transition: 0.2s ease all;
        padding: 12px 24px;
        border-radius: 4px;
        color: #FFC7BF;
        background-color: #212121;
        box-shadow: 0 2px 2px -1px rgba(0,0,0,0.5);
    }
    button.sm {
        padding: 6px 12px;
    }
    button.lg {
        padding: 18px 30px;
    }
    button:hover {
        background-color: #171717;
    }
</style>