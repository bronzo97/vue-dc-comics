<template>
    <div>
        <div>
            <img :src="cardImg" alt="" class="my-card-img">
        </div>
        <div class="card-title">
            <h5>{{cardTitle}}</h5>
        </div>
    </div>
</template>

<script>


export default {
    props: {
        cardImg: String,
        cardTitle: String,
    },
    data () {
        return{

        }
    }
}

</script>