<template>
    <div class="btn-container">
        <div>
            <button class="confirm">Proceed to payment</button>
        </div>
        <div>
            <button class="cancel">Cancel Order</button>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Confirmation'
}
</script>

<style>
.btn-container {
    max-width: 400px;
    margin: auto;
    margin-top: 3em;
}
.confirm, .cancel{
    width: 100%;
    height: 50px;
    margin-top: 1em;
    font-size: 18px;
    font-weight: 700;
}
.confirm {
    background-color: hsl(245, 75%, 52%);
    color: white;
    border-style: none;
    border-radius: 12px;
    box-shadow: 0 2px 20px #888;
}
.cancel {
    background-color: transparent;
    border-style: none;
    color: darkgrey;
}
</style>