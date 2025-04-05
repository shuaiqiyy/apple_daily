<script>
import { hear_first, hear_second, essay, add } from './index';
export default {
    components: {
        hear_first,
        hear_second,
        essay,
        add,
    }
}

</script>
<template>
    <hear_first></hear_first>
    <div class="two_grid">
        <div class="two_grid_item">
            <hear_second></hear_second>
        </div>
        <div class="two_grid_item"></div>
    </div>
    <div class="center">
        <essay></essay>
        <div style="height: 15px;"></div>
        <essay></essay>
        <div style="height: 15px;"></div>
        <essay></essay>
        <div style="height: 15px;"></div>
        <essay></essay>
        <div style="height: 15px;"></div>
    </div>
    <add></add>
</template>