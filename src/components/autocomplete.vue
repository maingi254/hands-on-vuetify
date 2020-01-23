<template>
    <v-container>
        <v-autocomplete
        label="what state are you from?"
        :items="states"
        hint="enter first letters"
        hide-no-data
        clearable
        multiple
        small-chips
        deletable-chips>
        </v-autocomplete>
    </v-container>
</template>

<script>
export default {
name:'autocomplete',
data:() =>({
    states:[
        "Alabama", "Alaska", "Arizona", "Arkansas", "California", "Colorado", "Connecticut", "Delaware", "District of Columbia", "Florida", "Georgia", "Hawaii", "Idaho", "Illinois", "Indiana", "Iowa", "Kansas", "Kentucky", "Louisiana", "Maine", "Maryland", "Massachusetts", "Michigan", "Minnesota", "Mississippi", "Missouri", "Montana", "Nebraska", "Nevada", "New Hampshire", "New Jersey", "New Mexico", "New York", "North Carolina", "North Dakota", "Ohio", "Oklahoma", "Oregon", "Pennsylvania", "Rhode Island", "South Carolina", "South Dakota", "Tennessee", "Texas", "Utah", "Vermont", "Virginia", "Washington", "West Virginia", "Wisconsin", "Wyoming"
    ]
})
}
</script>

<style>

</style>
