<template>
    <div style="height: 100%; max-width:400px;  overflow-x : visible;">
        <Card />
        <CardMail />
        <CardDoubleSocial />
        <CardSkill />
        <CardExperience />
        <CardMemoryGame />
        <CardScreen />
    </div>
</template>

<script>
import {defineComponent} from "vue";
import Card from "@/components/Card.vue";
import CardMail from "./components/CardMail.vue";
import CardDoubleSocial from "./components/CardDoubleSocial.vue";
import CardSkill from "./components/CardSkill.vue";
import CardExperience from "./components/CardExperience.vue";
import CardMemoryGame from "./components/CardMemoryGame.vue";
import CardScreen from "./components/CardScreen.vue";

export default defineComponent({
    components: { Card, CardMail, CardDoubleSocial, CardSkill, CardExperience, CardMemoryGame, CardScreen },
})
</script>


