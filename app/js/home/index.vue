<template>
    <div>
        <Heador/>
        <Slider/>
        <Novice/>
        <Money/>
    </div>
</template>

<script>
import Heador from "../public/header";
import Slider from "./slider";
import Novice from "./novice";
import Money from "./money";

export default {
    components: {
        Heador,
        Slider,
        Novice,
        Money,
    }
}
</script>
