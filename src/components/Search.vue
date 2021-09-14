<template>
    <form>
        <span>
            <div class="_search">
            <v-text-field
            append-icon = "mdi-microphone"
            prepend-inner-icon = "mdi-magnify"
            rounded
            solo
            >

            </v-text-field>
            <div class="_action_buttons">
                <v-btn type="submit" class="buttons" depressed>
                    Google Search
                </v-btn>
                <v-btn class="buttons" depressed>
                    I'm Feeling Lucky
                </v-btn>
                <div class="mt-8 _lang">
                    Google offered in <router-link to="/">Magyar</router-link>
                </div>
            </div>
            </div>
        </span>
    </form>
</template>
<script>
export default {
}
</script>

<style scoped>
._action_buttons .buttons{
    margin: 5px;
    padding: 7px 45px;
    background-color: #f8f8f8;
    border: 1px solid white;
    text-transform: initial;
    color: #5f6368;
    font-size: 13px;
}
._action_buttons .buttons:hover{
    box-shadow: 0 1px 1px rgba(238, 238, 238, 0,1);
    background-image: -webkit-repeating-linear-gradient(top, #f8f8f8, #f1f1f1);
    background-color: #ffffff;
    border: 1px solid #c6c6c6;
    color: #222;
}
._lang {
    font-size: 13px;
}
a:hover {
    text-decoration: none;
}
._search {
    max-width: 100%;
}
</style>